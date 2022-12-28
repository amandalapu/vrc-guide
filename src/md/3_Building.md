# 3 - Building

# 3.1 - Introduction to Building: Principles

In Section 3, I’ll try to go over everything to do with building a quality robot including parts.

### **3.1.1 - Keep it stupid simple**

The idea behind this is fairly straightforward, keep designs as simple as possible.

With the nature of VEX Robotics, it is only a matter of time before something will break. Keeping your robot as simple as possible allows for you to lower the chance that if something breaks, your robot becomes completely useless.

Following this principle also applies to trying to minimize the amount of setup needed before a match. If you are suddenly called up to a match and you cannot get your robot setup in time, the match will continue on without you in most cases. For that reason, it is best to minimize the setup time needed.

### **3.1.2 - The idea of reducing jankiness**

The idea of ‘jank’ is a solution that is haphazard and unreliable and generally looks as if it was quickly put together. This also applies to temporary fixes to a problem as jank versus a more permanent fix.

The idea behind this principle is to try not to have jank solutions to issues on your robot as much as possible. Take the time to build a well thought out solution as a well thought-out solution will not require as much effort as a haphazard one later on (even if you do not keep the robot for a long time). After all you do not want to spend more time constantly fixing a jank solution rather than doing it right the first time.

### **3.1.3 - Be observant and consistent when building**

Most of the time good build quality comes from strong attention to details and staying consistent. A lot of the mistakes I have seen watching other people build comes from not paying close enough attention to how the mechanism is built. This is especially true when it comes to replicating something from one side to the other or from a different robot.

Paying attention to overall center of gravity, friction on a mechanism and how the mechanism is built will ensure that each mechanism is built well.  All of the things to look out for cannot be distilled in one guide though I would recommend making sure structures and axles are lined up properly and when free-spinning the mechanism by hand there is not much friction.

### **3.1.4 - Testing for Consistency**

One of the fundamental goals of your robot has to be that it is consistent. One of the things I have learned is to always test for consistency first when trying to diagnose a problem. Make sure that the robot is consistently facing the same issue before trying to adjust and account for it.

This logic applies to almost everything you do in robotics, whether it be building, programming or driving. Being consistent is key.

You never want to lose the final round of the world championships due to your robot being inconsistent (Nothing But Net Finals, Team 1104Z).

[185A’s lift mechanism broke in the final round of world championships and ended up costing them 50 crucial points and the championship.](https://lh3.googleusercontent.com/xFVBWdufdCqZtKkCFDujUtc4wS8zFss2UaDHpYgCzCmtUNjEEZj2PxExQS5U-aEXUbWCSEeA1xdoRSuSrjZOQf5TdLOXwVO0gLN1mZ3xouhzUM1_nKnPPOiijmKZtGw_e_G8FKMw)

185A’s lift mechanism broke in the final round of world championships and ended up costing them 50 crucial points and the championship.

# 3.2 - Building: The Parts

At the high school level, VEX Robots are limited to basically anything you can order off of the EDR/V5/Cortex section of the VEX online store ([www.vexrobotics.com/](https://www.vexrobotics.com/)), and a few custom parts off of other websites such as Robosource ([www.robosource.net/](https://www.robosource.net/)).

Always check the game manual each year to know the exact limits on what parts you can use for your robot. I will try and cover information about as many of the parts as possible.

### **3.2.1 - Nuts and Bolts (Screws)**

Screws come in all sizes from 0.25 inches to 2 inches in the following increments: 0.25, 0.375, 0.5, 0.625, 0.75, 0.875, 1, 1.25, 1.5, 1.75, 2.

There are two major types of screw heads, **hex** and **torx (star-shape)**

- **Hexagonal** are the older ones and in my time, we have begun phasing them out as the main type of screw
    - VEX Shoulder Screws and Shaft Collar inserts still use them
- **Torx or Star-Shaped** are the main type of screw heads and they are preferred since it is harder to strip them (wearing away the metal on the screw head so that tools do not grip as well)

There are also two major sizes of screw heads (as in the size of the hex or torx shape in the screw): **5/64 and 3/32 (for Hex)** and **T8 and T15 (for Torx).**

There are also two major types of nuts: Keps and Nylock

- **Keps Nuts (0.125 in. wide approx.)**:
    - Very easy to put on
    - Very easy to remove (both by hand and through the robot vibrating and moving)
    - **Not recommended for fastening applications as they are unreliable, but good for prototyping**
- **Nylock Nut (0.25 in. wide approx.)**
    - Require a wrench to put on properly
    - Has nylon at the end so loctite does not do much
    - **Recommended for fastening applications**
    - Oftentimes, teams will build their robot out of Keps nuts, then replace them with Nylock nuts before a competition.

[Keps Nut](https://lh5.googleusercontent.com/W22zS4aIOOBNsFYc1gBKWCNXBypxlNduqehhI6gEYQ5mIPfFkPaLu4Uj2NoOQr9WsB1hgmx8NoRlwLLwF3YLGt3xv5TRkCpa8U80lX8UztwF3eVo25f6NxZsY5btqoipSqRqcJol)

Keps Nut

[Nylock Nut](https://lh4.googleusercontent.com/QIcxkWC3GnEkT2BK_k3NrrhC2H4QnYUT-A0kENC2yu7uVFSJPE_-_70ANwPNx1lmf6yIHlGRnfg6PrZu_E49FCg39MIpyy_00BDopxxAQI7yzLguW7cVt0-M7zjtcq_xSEGgT_WN)

Nylock Nut

0.325 in screws are perfect to attach metal on metal using a nylock nut

0.5 in screws are perfect to mount bearing flats on metal using a nylock nut

0.25 and 0.5 inch screws come with the option of having blue loctite on them.

Blue Loctite helps prevent loosening when the robot vibrates when connecting metal to metal (for example, a screw and a standoff)

### **3.2.2 - Structural Metal**

To build a robot you will be using a combination of C-Channels and L-Channels (named after their shape) for the most part.

There are two main materials to be used, **Aluminum** and **Steel**. For the most part you will be using Aluminum unless you want to add weight to your robot or try and shift the center of gravity. Aluminum is slightly weaker compared to steel but is much lighter and is very strong for its weight.

**Aluminum is the go-to for 95% of applications.**

C-Channels will be the bread and butter of building your robot while L-Channels and “Halfcuts” (1x1 L-Channels) have specific use cases since they are not as strong.

Most of the time, metal is measured in “holes” and a quick conversion to know is that 2 holes long is an inch long.

Every 5 holes on a C-Channel there is a small divot in the metal.

[The tiny divots or notches are placed every 5 holes on the C-Channel](https://lh3.googleusercontent.com/gMAphSsMMYcZED78Qvzw-Wi44E-_8vozhM5hcDdFDWyThDdyIODH3oYrir42xyUAGQIMtERW0LInvJ1EdUpqPGZbemdUAVmD42MxorSE30bq1ltaBD-f17ca0YSdkW94GeeTXrTB)

The tiny divots or notches are placed every 5 holes on the C-Channel

Another important thing to know is that fitting a 0.375 in. and a 0.5 in. spacer inside the C-Channel prevents the C-Channel from caving inwards, as shown in the example below. Even though 2 holes is technically 1 inch, the flange of the C-Channel makes it so that only a combined height of 0.875 works.

[https://lh5.googleusercontent.com/KrRpI55J7ujENrR5WwrVC8JVkvvA8ySDYIsGsB_lSVycwzrPPobx40JzIk-odHB4Pn2smQW1l2A5cf5WKyJHMy8ialm5Zta2NRuQZfOQafKFw_uYwP2kL8ClwYxRqDzDYthANd5A](https://lh5.googleusercontent.com/KrRpI55J7ujENrR5WwrVC8JVkvvA8ySDYIsGsB_lSVycwzrPPobx40JzIk-odHB4Pn2smQW1l2A5cf5WKyJHMy8ialm5Zta2NRuQZfOQafKFw_uYwP2kL8ClwYxRqDzDYthANd5A)

### **3.2.3 - Standoffs**

Standoffs are useful in attaching metal, providing bracing and offsetting components.

All standoffs up to the 1 inch. length are fully threaded meaning that you can screw in a screw all the way.

Standoffs larger than that are threaded for 0.5 inch. on each end.

When it comes to making sure your standoffs stay on, there are a few points to keep in mind:

- Tighten screws all the way
- Use loctite on the screw
    - Loctite helps prevent the standoff from loosening over time due to vibration or general wear and tear
        - Most of the time, use **blue** loctite, if you use red loctite, you will not be able to remove the screw no matter what
        - Heat helps undo the effect of loctite

You can also mount standoffs on a shaft collar or a high strength clamping collar using a standoff coupler (0.5 in.) or a screw (for the clamping collar) as shown below:

When trying to screw through a standoff and into a nut, I find it helpful to loosen the screw in the standoff just a little bit so that you can screw in both the nut and screw in one go. It is a bit difficult to describe via text but once you figure it out by trial, it is relatively easy.

[https://lh4.googleusercontent.com/1Sk9ry2Rgj_bVL7w55cScskHxROCAO9KiovOF4flxC0padztsQHbaeeUPZhZ3hNCI7Iv9a1-upT7X3jMziSP82Pdmy8L7KoC_SXUUssf31blboCN-Zy4boH6L-VtGZTmAo_LYjzQ](https://lh4.googleusercontent.com/1Sk9ry2Rgj_bVL7w55cScskHxROCAO9KiovOF4flxC0padztsQHbaeeUPZhZ3hNCI7Iv9a1-upT7X3jMziSP82Pdmy8L7KoC_SXUUssf31blboCN-Zy4boH6L-VtGZTmAo_LYjzQ)

You can also combine standoffs with each other to make even longer standoffs using a 1 inch. standoff coupler. Be cautious with this as the longer you go the more unstable the standoffs may become without the proper precautions.

You always want at least 2 contact points if not more when it comes to situations where you do not need movement.

### **3.2.4 - Bearing Flats**

Bearing flats are used to keep axles straight and to minimize friction in rotating systems.

There are a few best practices when it comes to bearing flats to make sure that your joints have minimized friction.

First off: there are 3 holes in the bearing flat and you want to be using two of them to attach the bearing flat as shown below. **Mounting the bearing on both sides and leaving the center hole for the joint is ideal though the other setups are also valid although significantly worse.**

[https://lh5.googleusercontent.com/A_fafinRBkIC7JSS382s_4Tr44xnVd_voowXAWyYjMy9qmlA4YRyKDswlVALNiqxdRdIUg2TQhZiK7Ynm8odTDLzI1USi7Qg0ACvglDbYCc8y-IoHz6F5BWvsthnqAUVk6jck4Zy](https://lh5.googleusercontent.com/A_fafinRBkIC7JSS382s_4Tr44xnVd_voowXAWyYjMy9qmlA4YRyKDswlVALNiqxdRdIUg2TQhZiK7Ynm8odTDLzI1USi7Qg0ACvglDbYCc8y-IoHz6F5BWvsthnqAUVk6jck4Zy)

The most important mistake I have seen is not making sure the bearing “snaps” into the C-Channel holes. Bearings have small divots on the back side as shown here.

[https://lh6.googleusercontent.com/dSgMxCOGJKmIKwOdCJkJDfQvSm0Eo6kbczS_KpPeD4uMB7sm-lp_JCUxjh9EKGrho8t4HrmkN0-qzL6HEkXtMyrFadIH9ZjpqKA3rleAnF1dBhKnnkmYl2Ek4UKhEd8iQjeyL-Z5](https://lh6.googleusercontent.com/dSgMxCOGJKmIKwOdCJkJDfQvSm0Eo6kbczS_KpPeD4uMB7sm-lp_JCUxjh9EKGrho8t4HrmkN0-qzL6HEkXtMyrFadIH9ZjpqKA3rleAnF1dBhKnnkmYl2Ek4UKhEd8iQjeyL-Z5)

There is also one final thing that must be noted about bearing flats. You need to shave down the bearing a little bit when placing it on holes that are next to the flange.

### **3.2.5 - Joints**

Joints allow for rotational motion and for the most applications the screw joint is preferred.

Axle joints are used primarily with 12T metal pinions and with motors.

Most of the joint information is based off of the BNS Joints Video

(Link: [https://www.youtube.com/watch?v=rhfNeMwAKnI](https://www.youtube.com/watch?v=rhfNeMwAKnI))

**Axle Joints** are the most basic but also have the highest slop and friction.

Always make sure your axles are straight (this is done by placing it on a flat surface and tapping one end and seeing if the other end does not start to raise).

They are very simple to make: you need two bearings on each end, an axle and shaft collars on both ends to secure the axle from falling out.

[https://lh6.googleusercontent.com/YPSuxYmQhaNo05eNCcWGhEqTAa2-eia1BkmfB5owDbzsf9aLXJSvjsdoSDbQEKBBp5RJeWTKf6eZ0US31R_fS_GlgKDoXlVXVhL3B9pSRXSxY9oa5a-K4RalwWCujyOSTUb4HtWI](https://lh6.googleusercontent.com/YPSuxYmQhaNo05eNCcWGhEqTAa2-eia1BkmfB5owDbzsf9aLXJSvjsdoSDbQEKBBp5RJeWTKf6eZ0US31R_fS_GlgKDoXlVXVhL3B9pSRXSxY9oa5a-K4RalwWCujyOSTUb4HtWI)

**Screw Joints** are a little bit more complicated but offer lower friction and slop but are tricky to optimize how tight the nut at the end is versus making it too loose.

Most of the time for a screw joint you only need a bearing on the other end. You want the keps nut to be tight and the nylock at the end loose yet secure enough. Make sure that are beings on both sides of the joint.

[https://lh5.googleusercontent.com/RrRkFcy-UHcwnznZxOEJo15O6lTs-z9-I3Rrmx_IYeusEz9P1xOP0jOwHHzmAP1rqcFovukhnIES0gyit3SdVdZLKH8VX8uBalaX5OXTOVWffYveF8_D0M0ptvjqibFQsCIxr3_Q](https://lh5.googleusercontent.com/RrRkFcy-UHcwnznZxOEJo15O6lTs-z9-I3Rrmx_IYeusEz9P1xOP0jOwHHzmAP1rqcFovukhnIES0gyit3SdVdZLKH8VX8uBalaX5OXTOVWffYveF8_D0M0ptvjqibFQsCIxr3_Q)

### **3.2.6 - Chain and Sprockets**

Most of the chain and sprockets you will be using are actually from the High Strength Sprocket and Chain Kit. Chain and Sprockets are primarily used for power transfer over distances.

There are the following sprocket sizes, 6T, 12T, 15T (Grey), 18T, 24T and 30T and several varieties of chain as shown below.

[https://lh4.googleusercontent.com/PlS_PSO1INepAS4ME2dS1R2dp7uiVYFyuA0amoxODE9tVRTmeRPRPe-oKXLMurZ82acySraoif2AKi04wGlHPLCdfknyyTFfDGxkkQ1D_BL-9XtSa2ilz-C7FvodwMDIEC6LKp-b](https://lh4.googleusercontent.com/PlS_PSO1INepAS4ME2dS1R2dp7uiVYFyuA0amoxODE9tVRTmeRPRPe-oKXLMurZ82acySraoif2AKi04wGlHPLCdfknyyTFfDGxkkQ1D_BL-9XtSa2ilz-C7FvodwMDIEC6LKp-b)

There are a few things to keep in mind when working with chain and sprockets:

Assume that your chain will break, it has happened to one of our teams at the world championships and it has cost them the match. The main takeaway is to build in redundancies and fail-safes.

I would advise against using the 6T sprocket as much as possible since it is so small the chain does not make proper contact with the sprocket.

For applications such as the chaining wheels together I would recommend using 18T sprockets and larger because of the fact that they have better contact with the chain. 12T sprockets are fine but not ideal and 6T **should not be used**. To make sure your wheels do not slip, it is also best practice to bolt the wheel to the sprocket using a metal lockbar.

Ideally you want your chain to be in a fine balance between not too loose and not too tight. You can use free-spinning 6T sprockets or spacers to act as tensioners to make certain parts of the chain tighter. In general, slightly loose is preferred than too tight.

### **3.2.7 - Shoulder Screws**

Shoulder Screws are some of the most useful parts you could use to build your robot.

Normal screws are just slightly too small so oftentimes pieces of metal are slightly out of alignment and can shift around.

Shoulder Screws ensure that two pieces of metal are attached to each other without any room for movement.

The VEX shoulder screws require a 0.125 in. spacer to be placed between the  screw and the nut as shown below.

For applications such as drivetrains and mechanisms where you need minimal friction, you should use shoulder screws to ensure alignment.

[https://lh5.googleusercontent.com/5Y2zG1k1xLrkTERX4cdOxQS8a19niwU934AiKBwWgNlT8aebQBx2s1AFjfPLN97D1tw5KvblIRo0_RGqUcbsUkS5aDZfvX0ThEW61ZaklIJ94_zXknqtHkDqufIf9xcPUBijZvIO](https://lh5.googleusercontent.com/5Y2zG1k1xLrkTERX4cdOxQS8a19niwU934AiKBwWgNlT8aebQBx2s1AFjfPLN97D1tw5KvblIRo0_RGqUcbsUkS5aDZfvX0ThEW61ZaklIJ94_zXknqtHkDqufIf9xcPUBijZvIO)

### **3.2.8 - Pneumatics**

Pneumatics were not really that popular in my time but since then, competition rules have made them an extremely vital component of robots. 

The BLRS wiki is the better reference for information about pneumatics: [https://wiki.purduesigbots.com/hardware/pneumatics](https://wiki.purduesigbots.com/hardware/pneumatics) 

### 3.2.9 - Gear Ratios

While this was something that is at the core of robotics, I originally did not include this topic in my original guide.

I would like suggest the BLRS wiki again for this resource since its much more thoroughly and constantly being updated, especially with the new gears that have been introduced.

[https://wiki.purduesigbots.com/hardware/misc.-vex-parts](https://wiki.purduesigbots.com/hardware/misc.-vex-parts)

# 3.3 - Building Best Practices

### 3**.3.1 - Bracing**

Structural components should be as sturdy as possible.

For the most part, you cannot have too much bracing. The only exceptions would be if that mechanism needs to be light or in extreme cases where you clearly have too much bracing.

There are several different ways to brace ****either using **straight connections or diagonal ones**.

**Standoffs can be used for bracing but the preferred ideal would be using 1x1 L-Channels or ‘halfcuts’.**

Basic bracing involves having multiple attachment points. One is not sufficient as rotation is still possible with just one attachment point. Two is the minimum but more is needed if the component spans a large distance.

The principle of at least two points of support also applies to joints.

Diagonal bracing is more effective since it covers a larger area than just straight across bracing.

Cross bracing is an extension of this idea with two diagonals forming an X. Cross bracing is particularly nice because one brace will be under tension while the other compresses which makes it sturdier.

Here is an example of diagonal bracing and cross bracing from the 62A CAD model created by Zach from 929U

[https://lh5.googleusercontent.com/D7sfcfvNoi3H3hayNBY7VEeqRZz99vPUjPjQ_TPlFjEBfgkJ-AqJpMlET0FVHJbagG5QrFfkCR4WEZgXkviDjZoST-Ltf-glYO-XF-cA3DR_0ZPob74NpSmAmC2hsweq25Q_6_VH](https://lh5.googleusercontent.com/D7sfcfvNoi3H3hayNBY7VEeqRZz99vPUjPjQ_TPlFjEBfgkJ-AqJpMlET0FVHJbagG5QrFfkCR4WEZgXkviDjZoST-Ltf-glYO-XF-cA3DR_0ZPob74NpSmAmC2hsweq25Q_6_VH)

### 3**.3.2 - Reducing Friction**

To ensure that you get the most out of your motors, you have to eliminate friction as much as possible.

**Make sure everything is aligned:** This includes metal support towers and bearings, any bit of misalignment results in the axle digging into metal and creating a bunch of friction.

**Use washers:** Steel or Teflon washers can greatly reduce friction between a component rubbing on something else. Especially with teflon washers having a generally lower coefficient of friction.

**Let things be a little bit loose:** Especially with axles and screw joints leaving a little bit of a gap between spacers and the ends of the axle to allow the axle to wiggle a little but not too much that it falls out greatly reduces friction. The same idea applies to slightly loosening the nylock nut at the end of a screw joint.

**Use lubricant**: Especially for gears and axles, using a lubricant such as white lithium grease can do wonders in reducing friction. I would recommend the Lucas Oil one.

**Test friction by comparing free-spin time:**

Letting something free spin means to disconnect it from other components such as other sprockets, gears or a motor and spinning the joint with your hand. Short free spin time is indicative that there is a lot of friction in your system.

### 3.3.3 - Build Mindset for Building a Robot

(By Sai Senapathi)

Even with technical knowledge, building a robot is often a daunting task for novice builders, and it’s something that takes a lot of practice to get right. This is because anywhere from 80% - 90% of the build process is based on your mental workflow and design philosophy rather than technical knowledge, or even building the robot. It can thus be said that most of learning how to build is learning how to think about design. While it is difficult to impossible to completely cover every aspect of design philosophy, in this portion of the guide we hope to provide a basic understanding of what this looks like so that you may use it to form a mental workflow for your builds.

First though, a few operational definitions:

- **Design philosophy**- Our mental framework for setting design trends/preferences in a build and the approach to evaluating trade-offs.
- **Mental workflow**- How you organize and manage your mental space and faculties while you work, or in other works how you optimize your build process.

Most good build mindsets use the engineering design process (EDP) as a launch point, so we will discuss how to implement the EDP effectively by using design philosophy and mental workflow. It should be noted that in practice **the stages of the EDP do not exist as temporally bound independent steps, but as intertwined aspects in a single creative process. Meaning that each step of the EDP is not necessarily limited to being in a particular order in time but can be revisited over and over depending on what is happening in your design.**

**Setting Goals:** The first step to any build process is setting your goals and expectations for the build. This is where design parameters are established as is typically established after the game analysis. Things usually included here are:

- What is your primary scoring method?
- What do you want your bot’s play-style to look like?
- How will you handle defense and other bot on bot interactions (usually involves chassis decisions)
- How complex is your robot (this question asks you to think about the possible subsystems you may want to use and how viable it is to have those subsystems. *think about how your mechanisms may work together*)
- How to you expect your design to change over the course of the season? Do you expect to rebuild often or use most of your time in tuning?

These questions are kept vague because you are not meant to come up with definitive answers at this stage, your goals will evolve as the season continues. The purpose of this step is NOT to constrain your thought process, but to give it an initial direction. The ideas that rise here will form your initial conceptions of your bot's design, forming the foundations of your design philosophy.

**Brainstorming:** Once you understand what general direction you want your build to go, its time to figure out the general robot design. It should be noted that, like with goals, brainstorming is an ongoing process that is active at all stages of the build timeline. The brainstorming stage consists of the following:

- Researching the designs of other teams from both previous and current seasons (while direct hole counting is discouraged, it’s important for builders to first learn from more experiences builders before fully committing to making their own original designs.
    - It’s ok to take inspiration from other teams, so if you decide to copy something make sure that you are learning from them instead of being lazy and blindly looking to good designs.
- Figure out the subsystems to be used and their general layout, the priority here to make a coherent system that is as simple as possible.
    - Many builders make the mistake of choosing the ‘best’ mechs and throwing them all into one bot thinking that they will work, when in reality all they end up with is an incoherent mess. Another way to think about this is like choosing members for a team. You want team members that will work together and produce results over talented members that struggle to work with each other and produce individually brilliant but ultimately fractured results. Chose the right mechs (the one that will work together well), not the best ones.

This step is still not overly concerned with design details. Use this step to slowly build your understanding of what your design will be and what design challenges you are headed for. The key here is to not become fixated on a single design too quickly - lest you miss out on better solutions. Let your imagination run wild here, it's your last chance to easily pivot between designs without requiring a rebuild. It is ok to take more time for this step (time allowing) if you want to do more initial research or watch where the meta goes for a bit, but make sure you are still actively thinking about design during this time. When you feel that you have developed a satisfactory layout, you can move on to the next stage.

**Balancing creativity:** Brainstorming and creativity go hand and hand, so builders that are able to leverage their creativity effectively are often very successful. Creativity is a mostly random process that continues both in our conscious and unconscious minds 24/7 where our brains explore many different ideas. The key to using creativity is knowing when to let it ‘go wild’ or restrain it to focus on a specific task. Builders often have to practice operating in a middle ground where they are able to rally their creative process behind a specific task while also remaining aware of other possibilities to avoid missing good ideas. The best way to develop these skills is to use the “focused” mode as a default, while consciously taking a moment to stop and ‘zoom out’ and look at what you are doing as a whole through a much wider lens and see what other thing you could be doing. This serves 2 functions: the first one is to make yourself aware to how you can improve your designs with out of the box thinking while not sacrificing work efficiency. The second function is to help you catch potential problems you may face in the future by considering how your mech works in a greater spatial context (aka your bot). While a seemingly simple concept, it helps prevent the vast majority of building mistakes and mental roadblocks most builders will run into in initial design and prototyping stages. Ultimately, diligent observance of these practices should, in time, engrave flexible thinking as an intrinsic though process in your head, helping build intuition and refining your mental workflow.

**Prototyping and Initial builds:** Congratulations! About half of your mental roadblocks are over. Now you are about to start fleshing out aspects of your design logic into function concepts and mechs (In other words, this is the beginning of design implementation). By the end of this step, you should have a complete robot built. Contrary to popular belief, this step is actually one of the easiest in the build and design process (assuming you did the previous steps right - if you didn't, then well….). There is a large amount of flexibility in how you go about this process, but generally falls along 2 paths: 1) using CAD as a prototyping tool and 2) winging it. Both of these are valid process, and which one you choose depends heavily on your familiarity/access to CAD software, your adaptability and willingness to take risks, and the nature of your team (do you work better on online or physical platforms). For more novice builders, the CAD route is highly recommended since it minimizes risks, it's easy to fix mistakes, and encourages creative freedom with most CAD software's (namely inventor and fusion) relatively easy-to-learn assembly UI’s and the vast amount of recourses out there for VEX CAD. It should be noted that more experienced builders with exceptional build intuition may opt to wing it, which is perfectly acceptable given there are some safety nets to cushion some of the inevitable risks that come along with that route. 

Design advice for this step follows the same spirit as the advice in the “Balancing creativity” section. Please remember that you will spend most of this step in thought rather than putting new parts on your bot, so setting your mental workflow to be as efficient as possible is much more important than the speed at which you are able to build a mechanism (although that matters as well). Even though you are perusing a certain design at this point, remain open to different options during this process as this is the time to experiment and come up with the best design. Building is an exploratory process, not a restrictive one.

There's one other thing worth mentioning here-managing tradeoffs. At this point in the build process, you are likely handling a large number of build tradeoffs simultaneously. Of course, regular people have trouble managing the parallel processing needed to think through these tradeoffs in an efficient and organized manner without getting very lost in the details. Developing intuition does help with this so a certain extent, as it simplifies the choices you have to make, but intuition is a skill that comes with time, so it doesn't help novice builders much. This is why its important to have a framework for evaluating tradeoffs. There are 2 guiding forces to this:

- Design philosophy - The constitution of your design philosophy will help you prioritize what aspects of your design you want to emphasize and what you are willing to sacrifice on.
- Risk - No decision comes without a certain amount of risk. Risks include time, complexity, material, and skill factors, and there is no real ‘correct’ way to evaluate them - even educated guesses are just guesses. The best way to deal with risk is to be well informed about about the risks you are taking and where you can afford to take risks without negatively impacting yourself, your build, or the other sub teams on your team.

Don't forget to have fun with this step! I mean, you are building a robot ultimately with the purpose of having fun while competing.

### 3.3.4 - Build Mindset for After Building a Robot

**Testing and tuning:** Congrats pt. 2! You have a robot! Unfortunately, it probably doesn't work as you intended. It’s ok, most robots don't. The goal of testing and tuning to identify performance problems with the robot and improve upon them, while improving existing aspects of your robot wherever possible. There are 2 major components:

- Problem diagnosis: It’s easy enough to look at a poorly performing robot and say that it has problems, but it’s often harder to find the specific points of failure in a design. Sometimes a single point of failure may be causing several different problems or multiple points of failure may be causing a single problem. These points of failure are often unpredictable and hard to find, so it’s important to take the time to make testing schemes for every problem you want to diagnose and thoroughly collect data on them. There are a couple of factors when it comes to designing tests:
    - Come up with a list of possible variables that may be causing the problem, and test one individually (aka only change one variable at a time)
    - Come up with a consistent test model that simulates real life match scenarios to the best of your ability. This often takes a lot of time and patience, but its well worth it.
- Finding solutions: Now that you have diagnosed the sources of the problem, its time to come up with a solution. The same advice from the prototyping step applies here, as you essentially redesigning a portion of your robot.

I cant stress the importance of being patient with this step enough - rushing through this step will only make things worse for you down the line. It’s also important to be systematic, as that will increase efficiency and reduce errors.

**Summary:** And with that, we have covered all the most important aspects of a good build cycle. I know I’ve said a lot here, so I will summarize the main points again:

- Building is an exploratory and creative process, so time spent honing your mental workflow will be better spent than improving your build speed. Additionally, don't restrict your mind, consider all the possibilities.
- The steps of the EDP don't have a strict chronological order, they are all parallel processes that happen continuously and consciously through the build cycle.
- Practice staying focused on certain design tasks while also seeing the bigger picture. This will expand your horizons and give you better designs while helping you make fewer errors.

### Navigation

| Previous Page | Next Page |
| ----------- | ----------- |
| [2 - Team Organization + Project Management](/src/md/2_Team_Organization_Project_Management.md) | [4 - Electronics](/src/md/4_Electronics.md)  |