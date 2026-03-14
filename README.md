# SDLC-Assignment-Amrinder
Project Overview

This assignment analyzes how different Software Development Life Cycle (SDLC) models handle changing project requirements. The scenario involves a mobile application called Smart-Attend, which automates classroom attendance using Geo-fencing technology.

The application detects when a student enters the classroom area and automatically marks attendance. During development, a new requirement is introduced to integrate Biometric Face ID verification to prevent proxy attendance.

The assignment evaluates how this requirement change affects the development process when using the Waterfall model, and how the Agile Scrum framework provides a more flexible solution.

Repository Contents

This repository contains the following files:

1. Analysis Document
analysis.pdf
Explains:

Why the Waterfall model struggles with mid-project requirement changes

Key limitations such as rigidity, high cost of change, and delayed testing

How Agile Scrum can handle evolving requirements using short development sprints

2. Sprint Backlog
sprint_backlog.xlsx
A spreadsheet representing the Sprint 1 backlog, including:

User stories

Task priorities

Estimated development hours

This backlog represents the tasks required to develop the Minimum Viable Product (MVP) of the Smart-Attend application.

Agile Sprint Plan
Sprint 1 (2 Weeks – MVP)

The first sprint focuses on building the core features of the application:

Basic mobile application interface

Student login using university credentials

Geo-fencing logic for classroom detection

Automatic attendance marking

Notification when attendance is recorded

The goal is to deliver a working MVP that demonstrates the main functionality of the system.

Sprint 2 (Feature Enhancement)

In the second sprint, the team integrates additional functionality based on new requirements and early feedback:

Face ID biometric verification

Integration of biometric authentication with attendance logic

Improvements to the teacher reporting dashboard

UI refinements

Why CI/CD is Important for This Project

Using Continuous Integration and Continuous Deployment (CI/CD) helps the development team deliver updates quickly and reliably.

Continuous Integration (CI)

CI allows developers to frequently merge their code into a shared repository. Each update automatically triggers builds and tests to ensure the new code does not break existing features.

Benefits:

Early detection of bugs

Improved code quality

Faster collaboration between developers

Continuous Deployment (CD)

CD enables the application to be automatically deployed after successful testing. This ensures that new features and fixes reach users without manual intervention.

Benefits:

Faster release cycles

Rapid delivery of sprint updates

Reduced deployment errors

For the Smart-Attend project, CI/CD would allow the team to quickly release improvements from each sprint, such as the Face ID feature, while ensuring the system remains stable for students and teachers.

Conclusion

This assignment demonstrates the impact of changing requirements on software development. While the Waterfall model struggles with mid-project modifications, Agile Scrum provides a flexible approach through short sprints and iterative development.

By combining Agile practices with CI/CD pipelines, development teams can deliver reliable updates and continuously improve the application based on feedback.
