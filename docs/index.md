# ECE 3400 Intelligent Physical Systems

**Cornell, Fall 2017, room: PH 414**

**Instructor:** Kirstin Petersen (khp37)

**TA's:** Ryan O'Hern (rmo26), Claire Chen (clc288), Christopher Fedors (cjf83), Daniel Kim (dsk252), Leah Forrest (lmf232), Adarsh Jayakumar (aj373)

**Piazza page:** ADD LINK!

## Course Description

Students will engage in a holistic design approach to Intelligent Physical Systems which can perceive, reason about, and act upon their environment. This course will expand on the ECE 2000-level courses, and include topics on algorithms, field programmable gate arrays, wireless communication, sensors, actuators, power, and mechanics. Students will learn the value and trade-offs between theory, simulation, and physical implementations, and gain familiarity with rapid prototyping techniques, system debugging, team work, leadership skills, time management, and how to disseminate work to a broader audience through webpages.

_Specific outcomes include:_

 - The ability to apply specific design methodologies to the course project
 - The ability to evaluate what problems are best solved in software, electronics, or mechanics; as well as the trade-offs between theory, simulation, and practical implementations.
 - Efficient team work, as a member and as a leader.
 - Effectively communication skills through online media.
 - Awareness of professional and ethical responsibilities in the context of Intelligent Physical Systems.

Prerequisites include ECE 2100  ECE 2200 and ECE 2300.  Recommended prerequisite: ECE 2400 (or equivalent).
All information is gathered on this page; no additional textbooks are required.

## Semester Project

In teams of 6-8 people, you will design, fabricate, and program a robot to explore a maze. The robot microcontroller will be based on an Arduino Uno; the default propulsion method will be differential drive with continuous rotation servos. The robot will traverse the maze by following black lines on a white floor; it must also be able to detect walls, an audible start signal, and treasures emitting infrared light at different frequencies. The robot must continuously transmit its progress wirelessly to a base station (also based on Arduino Uno). This base station will communicate with an FPGA that in turn must drive a screen through a VGA interface. Points will be awarded for speed, accuracy, and innovative design methods. The entire robot can cost no more than $100; this chart shows how the price is calculated.

All designs must be documented throughout the semester on a group website. The goal is for these websites to be used as a source of reference for future classes. Accordingly, they will be graded with respect to thoroughness and clarity. To give teams a competitive advantage, we ask everyone to keep explicit code and circuit designs private until the end of the semester, however.

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

[Rules and final scoring chart](./Grading/Readme.md)

## Team Composition

The teams will be composed by the TA's and lecturer without exception.

Teams will be dependent on lab-time sign-up, student skillsets, and personalities. Before midnight August 28th please fill out these Google forms such that the teams can be formed immediately.

All labs are divided into two sub-labs. To ensure a good mix, it is required that you keep switching partners for the different labs. For example, if student A-F is a team; lab 1 should be solved by A-B-C and D-E-F; lab 2 by A-C-D and B-E-F; lab 3 by A-D-E and B-C-F; and lab 4 by A-E-F and B-C-D.  

We will host internal team evaluations and practice constructive critiscism. Receiving and giving profesional feedback may be uncomfortable at first, but it is a skill that will help you in any future career.

This [folder](./Grading/Readme.md) includes documents detailing how students will be graded. Be aware that a lot of changes has been made for Fall 2017 and that the score-chart may be changed throughout the semester.  

## Schedule and Hand-Outs

Please be aware that the following schedule is tentative and may change throughout the semester.

Week | Topic | Week | Topic
-----|-------|------|-------
1 | Intro, IPS fundamentals | 8 | Prototyping EE, [_Milestone 2_](./Grading/Milestone_score.md)
2 | Embedded Control, team work/time management | 9 | Algorithms, team assessment, [_LAB 4_](./lab4.md)
3 | Sensors and filters, [_LAB 1_](./lab1.md) | 10 | Algorithms, [_Milestone 3_](./Grading/Milestone_score.md)
4 | Actuators and control | 11 | Prototyping ME
5 | FPGA, [_LAB 2_](./lab2.md), team assessment | 12 | Power, [_Milestone 4_](./Grading/Milestone_score.md)
6 | FPGA, VGA, [_Milestone 1_](./Grading/Milestone_score.md) | 13 | Debugging IPS, team assessment
7 | Wireless communication, [_LAB 3_](./lab3.md) | 14 | IPS Ethics, Final Competition
See detailed schedule [here](./schedule.md.

**Deadlines**
- Tuesday, Aug 29th @ 8am: Fill in [Google Forms](https://goo.gl/forms/Zc9Jxlri2DHeXqfx1)
- Saturday, Sep 2nd @ 8am: Submit [team contract](./Teamwork/Team_Contract.md) to the lecturer. Also, make your first team website and add a link to the contract.
- Friday, Sep 22nd @ 8am: The websites will be graded for contents on lab 1
- Saturday, Sep 23rd @ 8am: Fill out and send the [team assessment form](./Teamwork/GroupProcess-QualitativePeerSelfEval.docx) to the instructor
- Friday, Oct 6th @ 8am: The websites will be graded for contents on lab 2
- Friday, Oct 20th @ 8am: The websites will be graded for contents on lab 3
- Saturday, Oct 21st @ 8am: Fill out and send the [team assessment form](./Teamwork/GroupProcess-QualitativePeerSelfEval.docx) to the instructor
- Friday, Nov 3rd @ 8am: The websites will be graded for contents on lab 4
- Friday, Oct 6th during class hours: Milestone 1 demonstration
- Friday, Oct 20th during class hours: Milestone 2 demonstration
- Friday, Nov 3rd during class hours: Milestone 3 demonstration
- Friday, Nov 17th during class hours: Milestone 4 demonstration
- Saturday, Nov 18th @ 8am: Fill out and send the [team assessment form](./Teamwork/GroupProcess-QualitativePeerSelfEval.docx) to the instructor
- Friday, Dec 1st: Final Competition, time to be determined (Mandatory attendance)
- Wednesday, Dec 6th @ 8am: The final websites will be graded

# Tutorials and Helpful links

We have and will continue to upload helpful tutorials and links on this webpage. We would love for you to contribute, please contact the TA's to do this!

**Related to Team Work**
- [How to create Gant charts](https://www.smartsheet.com/blog/gantt-chart-excel01) for free in Microsoft Excel for time management
- Excellent [Ted talk](https://www.ted.com/talks/tim_urban_inside_the_mind_of_a_master_procrastinator/transcript?language=en) for those who tend to procrastinate

**Related to GitHub**

- [Markdown cheat sheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
- [How to make a webpage with github](tutorials/webpages.md)
- [Desktop github](https://desktop.github.com/)

**Solutions**

[Team Alpha Repository](https://cei-lab.github.io/ECE3400-2017-teamAlpha/)
This is the repository for the team of TA's that solved all the labs during the Summer of 2017. Please use this website for support and inspiration; no credits will be given for close copies of these solutions. Also, the TA's were under strict timelines - hopefully you will upload more comprehensive and better websites over the course of the semester.

**Related to Control**

- [Arduino Uno online references and tutorials](https://www.arduino.cc/en/Reference/HomePage)
- [A useful script to report on the internal state of your Arduino](https://playground.arduino.cc/Main/ShowInfo) and [here](https://playground.arduino.cc/Main/ShowInfo?action=sourceblock&num=1)
- Also, for problems with Arduino, look at wiring.c on your development machine to see the firmware settings that are being uploaded to your Arduino.
- [PID control]
- [Helpful FPGA-related Links and Tips](./tutorials/FPGA_resources.md)

**Related to fabrication:**

For the first time ever, we have a Skunkworks available to the class. This is located in PH427. Please be aware that you will only have access to this lab after you have taken a safety training, and in the presence of a TA.

- A zip file "ECE3400_Fall 2017_SolidWorks.zip", with all the mechanical parts drawn in SolidWorks can be found [here](https://github.com/CEI-lab/ece3400/blob/master/docs/ECE3400_Fall%202017_SolidWorks.zip)
- [Tutorials on Solid Works]
- [Tutorials on Autocad]
- [How to use the XYYZ 3D printer]
- [How to use the Epilog laser cutter]
- [Tutorials on Eagle]
- [How to etch your own PCB]
- [How to solder components and wires](./tutorials/Soldering_Tutorial.md)
- [Wiring a robot]
- [What goes on inside a servo?]

**Related to debugging**

- [How to build a simple Arduino oscilloscope](https://www.build-electronic-circuits.com/arduino-oscilloscope/)
- [Simple Matlab program to read in data from the serial port]
- [This folder](docs/simulation/) has software in Java, Processing, Matlab, and C++ for simulating robot search


