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

1. Completed: ~~Project Setup : We would like to have a GitHub project setup and a GitHub project setup to make a single repository for the project code and use the project integrations in Github to track new features and issues.~~
    1. Date: October 1 - November 1
    2. Tasks: 1, 2, 3
2. Completed: ~~Research and Mockups: We would like to research VR technology and use cases for our project~~
    1. Date: November 1 - December 31
    2. Tasks: 4, 6, 11, 13, 8
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

## 5.

## 6.

## 7.

## 8. Professional Biographies

[Jake Huseman's Biography](/Assignments/Biographies/ProfessionalBiographyHuseman.md)

[Caleb Hendrix's Biography](/Assignments/Biographies/ProfessionalBiographyHendrix.md)

[Sean Thomas' Biography](/Assignments/Biographies/ProfessionalBiographyThomas.md)

## 9. Budget

The team has not incurred any expenses for this project to date and has not accepted any donated software or materials. This team does not forsee needing to purchase or aquire any additional software or hardware to complete the project objectives.

## 10. Appendix

Each team member spent an average of 3 hours on each assignment for the course. Additionally, our team met once a week for an hour each week of the semester to plan and discuss next steps. With 10 assignments for this course and 15 weeks of the semester each member of this team has put in an average of 45 hours of work.
