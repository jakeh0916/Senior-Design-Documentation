# Fishbowl Design Report

## 1. Our Team & Project Abstract

Our team includes Caleb Hendrix (hendricw@mail.uc.edu), Jake Huseman (husemajd@mail.uc.edu), and Sean Thomas (thoma3sw@mail.uc.edu). Our faculty advisor is Jillian Aurisano (aurisajm@ucmail.uc.edu).

## 2. Project Description

Fishbowl is a virtual reality (VR) application for learning skills that require spatial thinking or precise physical actions.

Using a set of built-in tools and prefabricated objects, an Instructor user can create a "lesson" in Fishbowl, which can then be searched for and taken by any number of Student users.

For example, let's consider a fictional power company: FossilPower. At FossilPower, management has noticed an uptick in the frequency of new-hire injuries and mistakes. With relative ease, management uses Fishbowl to create a 3D model of the main work area, and through Fishbowl's scenario-creation tools, management programs a series of common actions that workers may engage in. Moving forward, FossilPower employees are required to complete this VR lesson before entering the power plant work area, ensuring that a worker's first experience in that dangerous environment is safe-guarded and limited to the confines of virtual reality.

Fishbowl is an application primarily designed for use with VR/AR/Mixed Reality headsets, such as the Meta Quest or Apple Vision Pro. We also envision a web application that can be used to search for and download public Fishbowl lessons, though we consider this deliverable to be a stretch goal.

## 3a. User Stories

The two core user types in Fishbowl are Instructor and Student. An Instructor creates and assigns Fishbowl lessons. Students take lessons and obtain a pass/fail grade.

In addition to the example provided above, let's detail two specific use cases (with two user stories earch) for the Fishbowl application:

User Stories 1 & 2: Welding.
* Instructor: As a welding instructor, I would like to provide a safe and simple introduction to welding a T Joint for my students.
* Student: As a welding student, I would like to safely practicing welding particular joints.

User Stories 3 & 4: Factory Navigation.
* Instructor: As a manager, I would like to provide new-hires with an in-depth tour of the factory, including an assessment on safety precautions.
* Student: As a worker, I would like to safely tour the factory in a virtual environment and be briefed on safety precautions before beginning work.

## 3b. Design Diagrams

![image](https://github.com/user-attachments/assets/f4e1edb0-60f2-47ac-9fc2-ba3c7e5f6746)

Our D0 Diagram describes the relation between the User, the Fishbowl VR Application, and the Fishbowl Website.

All diagrams follow UML conventions extended for the [C4](https://c4model.com/) diagramming method (in this case, simplified to three levels: D0, D1, D2.)

![image](https://github.com/user-attachments/assets/de7c9308-355f-4fe4-af17-df098bdcc672)

Our D1 and D2 Diagrams show the main components at play for this project. We envision our application as being primarily a VR Application (requiring a PC and VR Headset) that allows users to create and experience virtual lessons (such as changing a tire, welding, setting an IV, etc.). The left half of the diagram expresses this part of the application.
 
On the right for both diagrams, we’ve detailed a “stretch goal” for the project where users can upload/download lessons to/from the website and database. This allows users to share their custom lessons and experience lessons created by other users.

![image](https://github.com/user-attachments/assets/25b1bb7b-e47b-4b15-88f1-81bf7740a064)

In the D2 Diagram, the detail is increased, and we can now see the inner workings of saving and loading lessons, interacting with the Fishbowl application, and interacting with the Fishbow web interface and database.

## 4a. Task List

| No.   | Task  | Primary Person |
| ----- | ----- | -------------- |
| 1     | Setup GitHub repository for project code. | Caleb |
| 2.    | Define code repository structure / main folders. | Caleb |
| 3.    | Setup a GitHub project and begin to place development tasks into the backlog | Jake |
| 4.    | Investigate basics and best practices of VR development in Godot in the current state. | All |
| 5.    | Specify an appropriate proof of concept prototype for the Fishbowl VR application | Jake |
| 6.    | Investigate services available to host a web interface for the Fishbowl VR application and cloud storage options. | Sean |
| 7.    | Mockup a UI and user flow diagram for the web interface. | Sean |
| 8.    | Develop proof of concept prototype of the Fishbowl VR application. | All |
| 9.    | Document all issues encountered in the development process of the proof of concept prototype. | Caleb |
| 10.   | Document major design goals for the full Fishbowl VR application.  | Jake |
| 11.   | Research and Design the needed networking layer for Fishbowl VR. | Sean |
| 12.   | Design the necessary save file elements / structure for saving complete 3D lessons. | Caleb |
| 13.   | Design a UI mockup / prototype for the UI of Fishbowl VR. | Sean |
| 14.   | Validate the design of the Networking, Save File Structure, Web Interface and Core Object Design for compatability. | Jake |
| 15.   | Implement the 3D lesson creation, placing assests, recording states. | Caleb |
| 16.   | Implement 3D lesson playback, state recognition, undo/redo, placing assests. | Jake |
| 17.   | Implement UI for Fishbowl VR, local search, interface with the web, common UI widgets used throughout. | Sean |
| 18.   | Test and validate functionality of Fishbowl VR in basic cases. | All |
| 19.   | Create some sample VR tutorials for Fishbowl VR. | All |

## 4b. Timeline

1. **Completed.** ~~Project Setup : We would like to have a GitHub project setup and a GitHub project setup to make a single repository for the project code and use the project integrations in Github to track new features and issues.~~
    1. ~~Date: October 1 - November 1~~
    2. ~~Tasks: 1, 2, 3~~
2. **Completed.** ~~Research and Mockups: We would like to research VR technology and use cases for our project~~
    1. ~~Date: November 1 - December 31~~
    2. ~~Tasks: 4, 6, 11, 13, 8~~
3. VR Prototype : We would like to create a basic proof of concept application that solves the most basic instance of the problem which is creating and taking interactive 3D lessons.
    1. Date: Jan 1 - Mar 1
    2. Tasks: 5, 9, 10, 12
4. VR Deliverable : We want to end up with a full scale application which allows our two user groups, teachers and students, to both create interactive 3D lessons, upload them and also search and take these 3D lessons on various topics.
    1. Date: Mar 1 - Apr 1
    2. Tasks: 14, 15, 16, 17, 19
5. Web Prototype : We would like to create a basic mockup of the the web application side to decide on some basic UI and usability. 
    1. Date: Jan 1 - Mar 1
    2. Tasks: 7, 9, 10, 12
6. Web Deliverable : We need to design any needed network layouts in order for our web application to talk with our VR application, as well as have a functional web application.
    1. Date: Mar 1 - Apr 1
    2. Tasks: 17
7. Testing
    1. Date: Apr 1 - Expo Date
    2. Tasks: 18

| October 2024 | November 2024 | December 2024 | January 2025 | February 2025 | March 2025 | April 2025 |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| ~~Project Setup (Task: 1, 2, 3)~~ | ~~Project Setup (Task: 1, 2, 3)~~ |
|| ~~Research and Mockups (Tasks: 4, 6, 11, 13, 8)~~ | ~~Research and Mockups (Tasks: 4, 6, 11, 13, 8)~~ |
||| VR Prototype (Tasks: 5, 9, 10, 12) |  VR Prototype (Tasks: 5, 9, 10, 12) | VR Prototype (Tasks: 5, 9, 10, 12) |
||| Web Prototype (Tasks: 7, 9, 10, 12) |  Web Prototype (Tasks: 7, 9, 10, 12) |  Web Prototype (Tasks: 7, 9, 10, 12) |
||||| VR Deliverable (Tasks: 14, 15, 16, 17, 19) |  VR Deliverable (Tasks: 14, 15, 16, 17, 19) |
||||| Web Deliverable (Tasks: 17) |  Web Deliverable (Tasks: 17) |
||||||| Testing (Tasks: 18) |

## 4c. Effort Matrix

| Task # | Assigned Person(s) | Assigned Person Effort | Other Effort |
| ----- | ----- | ----- | ----- |
| 1 | Caleb | 80% | 20% |
| 2 | Caleb | 80% | 20% |
| 3 | Jake | 80% | 20% |
| 4 | Caleb, Jake, Sean | 33% from all | N/A | 
| 5 | Jake | 80% | 20% |
| 6 | Sean | 80% | 20% |
| 7 | Sean | 80% | 20% |
| 8 | Caleb, Jake, Sean | 33% from all | N/A |
| 9 | Caleb | 80% | 20% |
| 10 | Jake | 80% | 20% |
| 11 | Sean | 80% | 20% |
| 12 | Caleb | 80% | 20% |
| 13 | Sean | 80% | 20% |
| 14 | Jake | 80% | 20% |
| 15 | Caleb | 80% | 20% |
| 16 | Jake | 80% | 20% |
| 17 | Sean | 80% | 20% |
| 18 | Caleb, Jake, Sean | 33% from all | N/A |
| 19 | Caleb, Jake, Sean | 33% from all | N/A |

## 5. ABET Concerns Essay
We have a few constraints that we need to keep in mind when working on our project including funds, knowledge, and safety.

One of our main constraints has to do with funds as we have to supply them ourselves. We need to be able to acquire at least one VR/AR headset in order to develop, test, and demo our project. Our project also involves hosting a web application which is going to cost us some amount of money even if it’s not large. Luckily, a lot of the development tools we need are open source or free to use but there is a chance that we might need to purchase a tool in order to use in our project. Where we are now in our project, we have yet to have to purchase anything for our project and we do not forsee the need to in the near future.

In order to successfully complete the project that we have planned, an interactive 3D Virtual Reality course lab, each member will need to acquire professional expertise in this niche area. Acquiring this technical skill will take time to research best practices, become familiar with the standards of the tools used and develop some skill in using these tools. There will need to be a conscious effort made so that the time spent acquiring these skills does not impede the development of the final solution. If we can succeed in mitigating the upfront time spent developing these professional skills, then we can increase the likelihood of completing our desired project.

Safety in VR is a constraint that we will have to consider throughout development, testing, and eventually in our final product and demo. Features like “passthrough” allow users to see real-world obstacles in front of them (as to avoid collision, etc.), and many of these safety features are built into the Quest headsets we will be using. Additionally, we will want to consider how the connection cords affect the ability of users to perform different actions in VR. (This is a common problem in VR.) Finally, during our demo at the Senior Design expo, we will need to ensure that we have an open space free of obstructions to allow users to test our application, and they should be comfortable and safe within our area.

## 6. PPT Slideshow
![image](https://github.com/user-attachments/assets/55f0800e-8b5b-4e28-9305-f775edad0490)

![image](https://github.com/user-attachments/assets/9b2257d0-0784-4b62-b6a1-e20a49d66755)

![image](https://github.com/user-attachments/assets/ce7df373-efcf-4a91-82cc-a92cca66a7ed)

![image](https://github.com/user-attachments/assets/b9eb9a98-71f7-4133-b6e6-c6fed91af535)

![image](https://github.com/user-attachments/assets/b1825f8b-944b-414d-bdab-2de0340ed4cf)

![image](https://github.com/user-attachments/assets/0921b4b8-1d78-4c42-89eb-8ce33f45fb88)

![image](https://github.com/user-attachments/assets/8e09a195-0f62-4432-91dd-354b7f32f7d8)

![image](https://github.com/user-attachments/assets/fd464d1a-2b08-4202-b1fe-94f05de9dc41)

![image](https://github.com/user-attachments/assets/4c9f7eb4-157b-4160-bd23-99b21af2cb92)

![image](https://github.com/user-attachments/assets/8615440f-2e02-480d-8bca-a7e3394df80f)

![image](https://github.com/user-attachments/assets/bd522790-bb1d-4149-9043-a31c23d14163)

## 7. Self-Assessment Essays
[Jake Huseman's Self-Assessment](/Assignments/CapstoneAssessments/IndividualAssessmentHuseman.md)

[Caleb Hendrix's Self-Assessment](/Assignments/CapstoneAssessments/IndividualAssessmentHendrix.md)

[Sean Thomas' Self-Assessment](/Assignments/CapstoneAssessments/IndividualCapstoneAssesmentSeanThomas.md)

## 8. Professional Biographies

[Jake Huseman's Biography](/Assignments/Biographies/ProfessionalBiographyHuseman.md)

[Caleb Hendrix's Biography](/Assignments/Biographies/ProfessionalBiographyHendrix.md)

[Sean Thomas' Biography](/Assignments/Biographies/ProfessionalBiographyThomas.md)

## 9. Budget

The team has not incurred any expenses for this project to date and has not accepted any donated software or materials. This team does not forsee needing to purchase or aquire any additional software or hardware to complete the project objectives.

## 10. Appendix

Each team member spent an average of 3 hours on each assignment for the course. Additionally, our team met once a week for an hour each week of the semester to plan and discuss next steps. With 10 assignments for this course and 15 weeks of the semester each member of this team has put in an average of 45 hours of work.
