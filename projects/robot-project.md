---
Title: 2nd Year Robot Project (group)
Description: For the ENGR204 module, our group was tasked with building an autonomous robot which could follow a line and then fire two projectiles at two different targets.
---

![Photo of the finished project](/images/robot-project/hero.jpg)

## What was the project brief?

To build a small autonomous robot that can follow a black line on the ground and then fire two projectiles at two different targets. It should use basic electronic components, such as LDRs and brushed DC motors.

## How did our design work?

The robot was built entirely around an STM32 Nucleo microcontroller. This, along with many of the other components, was provided by the engineering department. The more complex subsystems such as the light sensing module for the line-following element of the project were built using LDRs in a Wheatstone Bridge configuration.

The most complex element of our robot was the so-called "firing mechanism" - a pair of 3D printed catapults that used elastic bands to propel the two projectiles (ping-pong balls) into the target area. We calibrated these manually by adding/removing elastic bands of different type to dial in the correct launch force. The catapults were actuated by using a servo motor and a small riser which was also 3D printed.

To follow the line and to control the behaviour of the robot, we developed a basic control system which would "zig-zag" the robot back and forth to keep it as aligned with the black line as possible while moving forward at a fixed speed. 

![Circuit Diagram](/images/robot-project/circuit-diagram.png)

## Outcomes - How successful was the project?

Our robot successfully completed the line-following task without any errors or manual corrections needed during the assessed run. It also completed the tasks well under the time limit outlined in the initial specification. Furthermore, the two projectiles were successfully launched into the defined target areas. Based on this, we felt that our design was highly successful as it completed the tasks outlined in the project brief.

We felt that our robot could have benefitted from a better control system, as the one we implemented did not take full advantage of the motor hardware that we had implemented. In theory, our design could have used differential speed control to steer much more effectively, instead of in the zig-zag motion that we chose. 

With more time to work on the project, we could have invested more into the physical design and organisation of the components. However, we were very time-constrained due to our group's lack of experience with electronics requiring use to spend much of our lab time researching and working on the wiring and sensor hardware. 

## Learning Opportunities

I improved many key engineering skills during this project:
- Teamwork and collaboration with my group
- Electronic design and assembly
- Programming (specifically with embedded systems/microcontrollers) and control systems
- CAD + 3D printing

## Video of our robot successfully following the black line on the ground during one of our tests
<video width="640" height="360" controls>
  <source src="/images/robot-project/demo1.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

## Group Photo - After successful project practical assessment!
![Group Photo](/images/robot-project/group-photo.jpg)

