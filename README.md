# College-Management-Portal-
TechNova College of Engineering -- College Management Portal

A clean, responsive College Management Portal built with HTML and
CSS. The project provides a centralized interface for students to view
academic information, attendance, courses, timetable, examination
results, assignments, campus notices, events, faculty information, fees,
library records, and support details.

Project Type: Static Front-End Web Project
Technologies: HTML5, CSS3, Boxicons
Theme: College / Student Management Portal

📌 Project Overview

The TechNova College of Engineering -- College Management Portal is
designed as a single web interface that brings commonly used college
services together in one place.

The portal includes:

Student login and role selection

Student dashboard

Student profile

Attendance tracking

Current courses

Weekly timetable

Examination results

Assignment tracking

Campus notices

Upcoming college events

Faculty directory

Fee details

Library book information

Contact and student support

The pages are connected through a common navigation bar and footer to
provide a consistent user experience.

✨ Features

🔐 Login Page

The login page provides:

College branding and logo

Student, Faculty, and Management role selection

User ID field

Password field

Remember Me option

Forgot Password link

Login button

Contact Support link

The current implementation is a front-end demonstration. The form
navigates to the dashboard and does not implement server-side
authentication or password verification.

📊 Student Dashboard

The dashboard provides an overview of student activities, including:

Overall attendance

Number of current courses

Pending assignments

Current semester

Today's classes

Class status such as:

Completed

Current

Upcoming

College announcements

Attendance overview with progress bars

The dashboard also provides quick links to the Academic, Student, and
Campus pages.

👨‍🎓 Student Profile

The Student page contains:

Student name

Student ID

Department

Year

Semester

Email

Phone number

Admission year

Overall attendance

Subject-wise attendance

Current courses

Faculty information

Course credits

📚 Academics

The Academics page provides:

Weekly Timetable

A structured timetable containing subjects and class periods for Monday
to Friday.

Examination Results

Displays:

Subject

Internal marks

External marks

Total marks

Grade

Assignments

Displays:

Assignment name

Subject

Due date

Submission status

🏫 Campus

The Campus page provides general college information and campus-related
updates.

It includes:

Campus introduction

Latest notices

Upcoming events

Faculty directory

Department-wise faculty information

Examples of campus events include:

Tech Fest

Annual Sports Day

Cultural Fest

Hackathon

Career Guidance Seminar

Science Exhibition

🛠️ Student Services

The Services page provides:

Fee Details

Shows:

Fee type

Total amount

Amount paid

Balance

Payment status

Library

Displays issued books along with:

Book name

Author

Issue date

Due date

Contact & Help Desk

Provides:

College administration contact details

Student support information

Contact form

🗂️ Project Structure

TechNova-College-Management-Portal/
│
├── index.html
├── dashboard.html
├── student.html
├── academics.html
├── campus.html
├── services.html
├── style.css
│
├── logo.png
├── logo2.png
└── campus.jpg

File Description

File               Purpose

index.html       Login / landing page
dashboard.html   Student dashboard
student.html     Student profile, attendance and courses
academics.html   Timetable, results and assignments
campus.html      Campus information, notices, events and faculty
services.html    Fees, library and support services
style.css        Main stylesheet for the website
logo.png         Portal logo / branding asset
logo2.png        College logo used across pages
campus.jpg       Campus image

🎨 Design

The project uses a consistent college-portal design across its pages.

Design elements

Card-based layouts

Navigation bar

Responsive grids

Tables for structured information

Progress bars for attendance

Status badges

Gradient backgrounds

Consistent typography

College logo and branding

Footer with quick links and contact information

The stylesheet also contains responsive rules for smaller screens.

🔧 Technologies Used

HTML5

Used to create:

Page structure

Navigation

Forms

Tables

Cards

Sections

Footer

Semantic content structure

CSS3

Used for:

Layout

Colors

Typography

Gradients

Cards

Tables

Responsive design

Hover effects

Progress bars

Login interface

Boxicons

The project uses Boxicons for interface icons such as user, book,
calendar, education, and dashboard-related icons.

🚀 How to Run the Project

This is a static website, so no database or server is required for the
current version.

Option 1 -- Open directly

Download or clone the project.

Open the project folder.

Open index.html in a web browser.

Select a role.

Enter any required demo values.

Click Login to Portal.

Navigate through the portal using the navigation menu.

Option 2 -- Using VS Code

Open the project folder in Visual Studio Code.

Install the Live Server extension if required.

Open index.html.

Right-click the file.

Select Open with Live Server.

⚠️ Important File Naming Note

In the uploaded project, the files are currently named:

index(1).html
style(1).css

However, the HTML pages reference:

index.html
style.css

For the links and stylesheet references to work correctly, rename:

index(1).html  →  index.html
style(1).css   →  style.css

Also make sure all HTML files and image files are kept in the same
project folder unless you update their paths.

🔗 Page Navigation

The main navigation follows this structure:

Login
  ↓
Dashboard
  ├── Student
  ├── Academics
  ├── Campus
  ├── Services
  └── Logout → Login

The footer also contains quick links to the main portal sections.

📱 Responsive Design

The CSS includes responsive styling so that the portal can adapt to
smaller screen sizes.

The login page, for example, changes the role-selection layout on
smaller screens, while the common stylesheet provides responsive
behavior for the portal components.

🔮 Future Enhancements

The current project is a static front-end implementation. It can be
extended into a complete college management system by adding:

Real user authentication

Student and faculty accounts

Backend database

Admin dashboard

Dynamic attendance management

Online fee payment

Assignment upload and submission

Online examination results

Real-time announcements

Library issue/return system

Faculty management

Student leave requests

Notifications

Search functionality

Profile editing

Password reset functionality

Role-based access control

API integration

🔒 Current Limitations

This version is primarily a UI/front-end prototype.

Login credentials are not verified by a backend.

Role selection is visual and does not currently change permissions.

Student information is static HTML content.

Attendance and academic records are static.

Fee and library data are static.

Contact form does not currently submit data to a backend.

Several footer links are placeholders.

🎓 Project Objective

The main objective of this project is to design a simple and centralized
digital platform for college-related information.

The portal demonstrates how different college services can be organized
into a user-friendly interface, allowing students to access academic,
campus, and administrative information from a single platform.

👥 Intended Users

The portal concept is designed for:

Students

Faculty

College Management

Administration

The current interface primarily demonstrates the student-facing
experience, while the login page provides role options for Student,
Faculty, and Management.

📄 License

This project is created for educational and academic purposes.

You may modify and extend the project for learning, demonstration, and
college project submissions.

👨‍💻 Project Credits

Project: TechNova College of Engineering -- College Management
Portal

Built using: HTML5, CSS3 and Boxicons

Project Category: Web Development / College Management System

⭐ If you found this project useful

Consider improving it by adding a backend, database, authentication, and
dynamic college-management features to transform the static prototype
into a complete web application.
