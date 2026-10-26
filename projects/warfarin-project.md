---
Title: 3rd Year Individual Project
Description: Automatic Warfarin Dose Management Using Model Based Control Systems
---

![Photo of the project](/images/warfarin-project/hero.png)

## What was the project brief?

After choosing from a vast selection of project options, I settled on a brief that was to investigate model-based control systems for the specific application of managing anticoagulant (warfarin) doses for patients on long-term treatment plans.

The ultimate aim of the project was to produce a long-form report explaining the work I completed alongside my findings. Additionally, I would be evaulated on my understanding of the field and my presentation skills through a project viva which was weighted at 20%.

## What was my approach?

I chose to approach my project from a purely simulation/mathematical angle rather than conducting any patient-based research. I felt from the beginning that it was important to appreciate the time constraints associated with my project

Working with my supervisor, we agreed that I should start by using numerical analysis to identify transfer functions which could relate the dose of warfarin that a patient took to a bleeding time test (using INR). Then, I could create several different controllers and implement the transfer functions as plant models in the simulation, and compare their behaviour/performance for this application.

In addition to these technical tasks, I also worked on a literature review as part of my research, and also made use of several project management tools to help me schedule my work over the roughly 6 months I had to complete my final report. 

## Outcomes - How successful was the project?

I was pleased that my project allowed me to explore different types of control systems (PID, PIP) and make compelling comparisons between their behaviour and performance for warfarin dose management. However, the approach I used initially to identify the transfer functions did not yield many results. Perhaps a future project could use a larger dataset, or different numerical techniques.

This coursework allowed me to significantly improve my project management skills. Without the skills I gained throughout the 6 months that I worked on it, I would not have been able to achieve all of my goals. 

One of the most interesting challenges I faced during the project was the need to discretise my controller's response to the error, as a patient can only be prescribed warfarin in discrete units (25mg, 10mg etc..). This caused my controller to exhibit an unwanted behaviour known as "limit cycle oscillations". This could only be corrected by adding a dead zone to introduce a fuzzy element to the reference value rather than making it an exact target as is typical in control engineering. 

Overall, I received 76% on the written (project report) element of the coursework and 80% on the viva. The success of this project has encouraged me to pursue further work in control engineering, informing some of my module choices in my fourth year.


## Learning Opportunities

This project is by far the most challenging and involved academic task that I have ever taken on, and I was extremely pleased that I had interesting findings to discuss in both my report and viva presentation. 

I gained experience in:
- Project management techniques (Gantt Charts, Risk Assessments, Supervisor Meetings ...)
- Numerical analysis in MATLAB on a provided dataset, skills that I've managed to further develop with other personal projects.
- Simulation using SIMULINK and Python. Implementing and testing a variety of control systems by considering both performance metrics and real-world interpretations of their behaviour. 

## Controller Output after correcting for Limit Cycle Oscillations

![Group Photo](/images/warfarin-project/second.png)
