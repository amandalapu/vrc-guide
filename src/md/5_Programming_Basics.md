# 5 - Programming Basics

# 5.1 - Programming: Basics

Some of this content may be outdated especially when it comes to PROS as this was originally written on April 2020. Please check the PROS website: [https://pros.cs.purdue.edu/](https://pros.cs.purdue.edu/) for the most updated information.

### 5**.1.1 - Terminology**

- Variable
    - A variable allows you to store some data for use in your code and it is able to be changed
    - Variables have to be declared and defined for use in your program
- Function
    - A function is a portion of code that can be executed multiple times after it is declared
- Parameter
    - An input that the function takes and uses in its execution
- Task
    - Allows the program to run multiple commands at the same time, it is very useful for asynchronous program execution where you do not want to wait for one part of the code to finish executing before starting the other
- Class
    - A template of sorts to create objects that have their own set of variables and methods (functions)
- Object
    - An instance of a class that has a set of variables and functions associated with it

### 5**.1.1 - Logic: If, Else If and Else Statements**

If statement - Runs code if the provided condition evaluates to true

Else If statement - Runs code if the condition in the if statement evaluates to false and the condition in the else if statement evaluates to true. You can have multiple else if statements

Else statement - Runs code if the condition in the if statement evaluates to false and/or all of the conditions in the else if statements evaluate to false

[https://lh3.googleusercontent.com/XwPr_kMTD2kfDLYKafM9klVA1MQ7REqjCCymHaPmwqGRtjW1IC4TY9rekb1faTcGLLCw1SNjfdiD0o5gFQOdohFEI85SxseuCnr2tNW6_DpOnoGpgLfPfYXE3YuRfa_GRmY3L4Vb](https://lh3.googleusercontent.com/XwPr_kMTD2kfDLYKafM9klVA1MQ7REqjCCymHaPmwqGRtjW1IC4TY9rekb1faTcGLLCw1SNjfdiD0o5gFQOdohFEI85SxseuCnr2tNW6_DpOnoGpgLfPfYXE3YuRfa_GRmY3L4Vb)

An example from the 2019-2020 Year where the code checks for if the intake button is pressed and runs intake at 200 rpm. If that is false, then the computer moves on to check if the outtake button is pressed and if it is, the intake motors will spin backwards at 200 rpm. If the first else if statement is false, then the second else if statement is read. This statement checks if both the intake and outtake button are pressed and if it is, the intake motors are spun backwards at half speed. If all of the statements are evaluated to false (when none of the buttons are pressed), then the motors are not spinning and the brake mode is set to hold.

5**.1.2 - While Statements**

While statement - Runs code while a certain condition evaluates to false. There is one thing to be cautious of and that is making infinite loops that either do not have an exit condition (something that makes the loop stop) or if they are not in their own separate task.

Oftentimes while loops are used to update controller values and in control loops such as PID (Proportional-Integral-Derivative) Loops to constantly update motor output values.

[https://lh5.googleusercontent.com/egTop6nNxqE485Scbj75yY78RWve2-wLH_-A6J5NZv6wno1sY3vzprWC-is07E6DGU1CdK05R3e7faVlKijbxuqF0IOVU2kL40DJsZXMf_3TwNewGo41w6fGMIcAAKbmrWVQfIam](https://lh5.googleusercontent.com/egTop6nNxqE485Scbj75yY78RWve2-wLH_-A6J5NZv6wno1sY3vzprWC-is07E6DGU1CdK05R3e7faVlKijbxuqF0IOVU2kL40DJsZXMf_3TwNewGo41w6fGMIcAAKbmrWVQfIam)

In this example, this while loop was contained in a separate task to make sure it did not block the main thread. This loop constantly checks if the boolean ‘trayIsUp’ is true or false. If it is true, it sets the velocity of the tray angling motor to be a proportion of target - its current position.

In a loop that runs infinitely, it is good to specify a tiny delay of at least 20ms to make sure it does not take up all of your resources.

### 5**.1.3 - Data Types**

- int - integer -1, 0, 1, 2, 3 etc.[](https://www.w3schools.com/cpp/cpp_data_types.asp)
- float - floating point -12.323, 123.34 (has decimals)[](https://www.w3schools.com/cpp/cpp_data_types.asp)
- double - double floating point - -123.23123123
    - Has double the space for decimals
- void- means no data exists there[](https://www.w3schools.com/cpp/cpp_data_types.asp)
- boolean - has either a value of true or false
- string - text such as “robotics”

It is important when using functions and defining objects to use the proper data type or else you will run into errors.

### 5**.1.4 - Motion Control Algorithms**

The two major ones include PID Controller and Motion Profiling.

PID Controllers can be used for almost anything, not just moving in a straight line.

Here is an excellent document describing what PID is and how to tune it:

[https://bit.ly/3cNalt2](https://bit.ly/3cNalt2)

You will have to tune every PID loop, even if you built identical robots, you cannot use the exact same values and expect to get the same performance.

A quick recap of how to tune:

1. Set all constants to zero
2. Start with a small kP and increase slowly
3. Increase until you get oscillation
4. Increase kD until oscillation stops
5. Repeat 3 and 4 as many times until oscillation cannot stop no matter the kD
6. Use the previous set of values and you are done with kP and kD
7. Slowly increase kI until the loop runs smoothly without constant error

Motion Profiling is specific to movement of the robot and for the most part is complicated to build on your own. Motion profiling is the idea of using a trapezoidal motion profile to smoothly accelerate, coast and then smoothly decelerate. You will have to tune

Okapi provides this functionality in the library, this will be discussed in the Okapi section.

### 5**.1.5 - Hardware**

Brain - The computer that controls the motors, receives input from sensors and executes code on your robot

Motors - Devices that allow for rotation of a shaft

The V5 Motors have an encoder inside of them to detect how much the shaft has rotated.

One caveat to the motor encoder is that sometimes the wheel may slip, resulting in inaccuracy.

Encoders detect how much a shaft has rotated and with that you can calculate the speed of the rotation and other properties.

### 5**.1.6 - Tasks**

Multitasking allows for code to happen at the same time. I would consult the PROS documentation on the best practices with tasks and multitasking here: [https://pros.cs.purdue.edu/v5/tutorials/topical/multitasking.html](https://pros.cs.purdue.edu/v5/tutorials/topical/multitasking.html)

Here is an example of a tray controller I used that did not block my main program’s execution.

[https://lh5.googleusercontent.com/f4WTXNNidgw1skNoi_rVA-NYzfEAHlvRdyTJz0h7blYihqoiFrh_D84_kw42iX5ZgqPT7jK8JHnBp0vX16qkCteCkNF1j_Ij6czIEgOIZQNUyV6FeNnqV3WLVsjEub0Gr-u7V4JZ](https://lh5.googleusercontent.com/f4WTXNNidgw1skNoi_rVA-NYzfEAHlvRdyTJz0h7blYihqoiFrh_D84_kw42iX5ZgqPT7jK8JHnBp0vX16qkCteCkNF1j_Ij6czIEgOIZQNUyV6FeNnqV3WLVsjEub0Gr-u7V4JZ)

### 5**.1.6 - Best Practices**

Admittedly, I have not been the best when it comes to following programming best practices but do not be like me and try to follow them.

- Assume someone else is working with you on your code
- Make variables easy to understand
- Keep your code simple
- Avoid copy pasting the same code repeatedly in your program, using functions can help with this tremendously
- Keep your code maintainable
- Always keep backups of your code
- Separate out your code, do not just have one giant file that is not clearly organized

The overall summary of these ideas is that keep your code simple, maintainable and organized.

An excellent example in my opinion would have to be 285R’s code from the 2019-2020 Season:  [https://github.com/cvhs/285R-TowerTakeover](https://github.com/cvhs/285R-TowerTakeover)

### 5**.1.7 - Github**

Github is an excellent way to keep your code online, to maintain versions of your code and to collaborate with others.

I would recommend [https://guides.github.com/introduction/git-handbook/](https://guides.github.com/introduction/git-handbook/) as quick start to get up to speed with Git and Github.