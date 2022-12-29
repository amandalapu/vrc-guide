# 4 - Electronics

# 4.1 - Electronics

### 4**.1.1 - ADI Sensor vs V5 Sensors + General Troubleshooting**

ADI Sensors interface with the (10x) 3 wire ports on the side of the brain and they include:

- Optical Shaft Encoders (require (2x) 3 wire ports)
    - Useful for detecting how much something has rotated, without relying on the internal encoders of the motor
    - Useful applications include: tracking wheels
- Line Sensors
    - Useful for detecting if something is touching or to read the lines on the field
- Potentiometer
    - Useful in lift systems where you do not need 360 degree movement
    - Will break if you spin past 270 or so degrees
    - Do not reset after program reset
- Bumper Switches
    - Act as a button that sends a signal when pushed
- Ultrasonic Sensor
    - Allows you to detect objects

I would highly recommend reading the VEX Knowledge Base ([www.help.vex.com](http://www.help.vex.com/)) and the specific section on sensors  ([https://kb.vex.com/hc/en-us/sections/360007306311-Sensors](https://kb.vex.com/hc/en-us/sections/360007306311-Sensors))

There are two V5 Sensors as of the time this is written that interface directly into the V5 Brain’s Smart Ports: **Vision Sensor and Inertial Sensor**

The **Vision Sensor** has not been very reliable as you have to calibrate the colors at every tournament and for different lighting conditions, I personally have not used it and I cannot say I would recommend it.

The **Inertial Sensor (IMU)**  shows some promise as it combines both an accelerometer and a gyroscope though be very careful in interpreting the values that are returned from the Inertial Sensor when writing algorithms.

![Sensors](/vrc-guide/src/assets/4_assets/sensors.png)

### 4**.1.2 - Motors**

Motors are the backbone of your robot and there are a few things to note about them.

**One, like bearings they have a little piece that is meant to “snap” into the C-Channel holes.**

Oftentimes these tiny pieces of metal get worn down. Ideally, you would buy the replacements and replace them but if not what ends up working is screwing through a bearing and screwing the motor in after the nylock nut. One caveat is that this is extremely time consuming.

**Two,  the motors panel on V5 Brain provides a lot of useful information about the motor.** One of the things to pay attention to is the power draw on the motor. In almost all applications, you do not want your power draw to be consistently high. That is a possible indication of the mechanism encountering unneeded stress.

**Three, motors will start to overheat over time.** When motors overheat, their performance is reduced in order to prevent overheating. Monitor your motor temperature frequently and use compressed air to help cool them down.

**Four, know the difference between the 3 cartridges.** The standard green one has a top speed of 200 rpm and is the most balanced in terms of torque and speed. The red cartridge has a top speed of 100 rpm but provides much more torque. The blue cartridge has a top speed of 600 rpm but does not have much torque.

### ****

**Five, invest in using “quick swap”.** “Quick swap” is the idea of using zip ties to hold the motor together rather than the standard motor screws. Due to motor screws being easily strippable, constantly taking apart the screws putting back together could mean that one day you cannot take out the screw. When using zip ties, make sure to prevent them from slipping off the motor.

![Motors](/vrc-guide/src/assets/4_assets/motors.png)

### 4**.1.3 - Electronics: Battery, Brain and VEXnet Radio**

There is not much to comment about the Brain and VEXnet Radio except to take care of them.

The battery has a significant amount of weight and so it is optimal to place it as low as you can and to use it to slightly balance out the center of gravity of your robot. It is good to use at least two battery clips and to place the battery in a spot that can be accessed easily.

Use wireless downloading as much as possible for your code since the Brain comes with a very delicate microUSB port. It is much easier to replace the controller than it is to replace the Brain.

For the VEXnet Radio, you want to place it as high as possible and to mount it on rubber links. It is believed that mounting the radio on rubber links helps prevent disconnections.

### Navigation

| Previous Page | Next Page |
| ----------- | ----------- |
| [3 - Building](3_Building.md) | [5 - Programming Basics](5_Programming_Basics.md)  |