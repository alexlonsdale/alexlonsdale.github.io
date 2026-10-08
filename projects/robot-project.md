---
Title: 2nd Year Robot Project (group)
Description: For the ENGR204 module, our group was tasked with building an autonomous robot which could follow a line and then fire two projectiles at two different targets.
---

![Photo of the finished project](/images/project-name/hero.jpg)

## What was the project brief?

To build a small autonomous robot that can follow a black line on the ground and then fire two projectiles at two different targets. It should use basic electronic components, such as LDRs and brushed DC motors.

## How did our design work?

The robot was built entirely around an STM32 Nucleo microcontroller. This, along with many of the other components, was provided by the engineering department. The more complex subsystems such as the light sensing module for the line-following element of the project were built using LDRs in a Wheatstone Bridge configuration.

The most complex element of our robot was the so-called "firing mechanism" - a pair of 3D printed catapults that used elastic bands to propel the two projectiles (ping-pong balls) into the target area. We calibrated these manually by adding/removing elastic bands of different type to dial in the correct launch force. The catapults were actuated by using a servo motor and a small riser which was also 3D printed.

To follow the line and to control the behaviour of the robot, we developed a basic control system which would "zig-zag" the robot back and forth to keep it as aligned with the black line as possible while moving forward at a fixed speed. 

![Diagram of the control loop](/images/project-name/diagram.png)

## Outcomes - How successful was the project?

Our robot successfully completed the line-following task without any errors or manual corrections needed during the assessed run. It also completed the tasks well under the time limit outlined in the initial specification. Furthermore, the two projectiles were successfully launched into the defined target areas. Based on this, we felt that our design was highly successful as it completed the tasks outlined in the project brief.

We felt that our robot could have benefitted from a better control system, as the one we implemented did not take full advantage of the motor hardware that we had implemented. In theory, our design could have used differential speed control to steer much more effectively, instead of in the zig-zag motion that we chose. In addition, our light sensors were not as well-built as they could have been as this was the first task we undertook - we gained a lot of experience throughout the project and would have made small tweaks to the design in retrospect. 

## Video

<video controls width="100%" src="/videos/project-name/demo.mp4"></video>


