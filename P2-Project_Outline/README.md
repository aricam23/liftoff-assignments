# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
My project will be a time clock web app. The app will have the capability to have multiple users be able to register, login, and see a list of saved time punches, along with their timestamps. 

### Features
User login: The time clock will allow multiple users to login'

View shifts: The time clock will keep track of each user's time punch history and allow them to see a saved history of their shifts

Tag shifts: Each shift or individual time punch can be tagged or catagorized with a range of descriptors like "Late", "Unexcused", or "Vacation"

Access levels: In order to simulate a workplace environment, there will be 3 user levels: Employee, employer, and administrator. Employers will have the ability to view and edit time cards for their own employees. Administrators can view and edit time cards for both employees and employers.

Geolocation: If at all possible, in order to encourage accountability, the web app will take advantage of any geolocation APIs that can be called. It's important that employers and administrators are aware of if the employee was at the workplace or worksite when they clocked in.


### Technologies
A .NET C#/EFCore/Razor technology stack would probably work best here. Working a geolocation API that's compatible with .NET Core into the project would work best as a Backlog release.

### What I'll Have to Learn
I'll need to learn how to associate objects in many more many-to-many and one-to-many relationships than in CheeseMVC. Users will need to be associated with their own time cards, as well as their "role". Users who are employers will need to be associated with their own employee groups. Time punches or shifts will need to be associated with any applicable categories or tags. I'll need to select and incorporate a geolocation API. Eventually (Backlog) I'll need to find a way to make time cards look visually appealing and informative.
