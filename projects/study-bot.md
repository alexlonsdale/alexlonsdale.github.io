---
Title: Study/Revision Support Desk Robot, "Kit"
Description: A small device/robot that assists with studying and focus
---

![PCB for the current design](/images/study-bot/hero.png)

## What was the project brief?

This is a personal project that I've wanted to work on for a very long time. It's currently a work in progress as I continue with my MEng degree this year. 

I've always had an interest in researching/building study tools that minimise the use of smartphones. Over the past three years, I've tried numerous study/focus/routine apps and workflows, alongside several note-taking programs such as Notion (AI based) and Obsidian (more focused on building connected pages). I have always felt that tools that rely on the use of smartphones are fundamentally undermined because they require you to spend more time on the device that it likely distracting you in the first place!

My workflow has always been to sit with a laptop and paper, and as such I envision this device as a small lower power system that can offer some of the key features of a study/focus app (timers, Pomodoro techniques, breathing exercises, reminders ...) without compromising on the core principle by requiring me to use a smartphone. 

## What was my approach?

After several discussions with my coursemates and some research, I realised that the first step in building a device like this is to design a PCB. Over the past few years, designing and fabricating a small custom board for an embedded electronics project like this has become both cheap and accessible to a relative newcomer to hobby electronics and programming. I've based my design around an ESP32 Devkit v1 microcontroller from ELEGOO. I'm also using a couple of off-the-shelf components such as a boost convertor, MPU, and clock module. The user will interact with the device using a small lower power OLED screen and several buttons. 

In addition to designing this PCB, I've started to write the code and conceptualise some of the core functionality of this device. With the experience I gained working on other projects (my second year robot project, DIY drone) I was quickly able to put together some basic code. 

## Outcomes - How successful was the project?

This project is a work-in-progress, and I'm still very much at the beginning of the work. I'm pleased with the early milestones that I've reached so far, and excited to learn more as the project goes on.

## Learning Opportunities

The main learning opportunity from this project is PCB design and fabrication. As a mechanical engineering student, I did not have more than a basic understanding of how integrated/factory-fabricated electronics worked before beginning this project. It's been very rewarding to design a custom PCB for this device - this approach will allow for much greater customisation of the final structural design. 
