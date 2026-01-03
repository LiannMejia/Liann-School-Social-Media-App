# Below is a simple Software Requirements Specification (SRS) style template for my anonymous class discussion app.
1. Introduction
1.1 Purpose
This document describes the basic requirements for an educational mobile/web application that supports anonymous class discussion. It specifies user roles and the key functions available to each role
1.2 Scope
The app will be used by schools, teachers, and students to facilitate anonymous discussions while protecting student identity. This application will only be used for my current school (Northfield Mount Hermon School).
2. User Roles
The app will support the following primary user roles:
Administrator (Myself)
Teacher
Student
(Maybe) School IT / Support Staff

3. Role: Administrator
3.1 Description
The Administrator manages how students sign up for the app, levels of access, and facilitates discussions.
3.2 Functional Requirements
The Administrator shall be able to:
User and school management
Create, edit, and deactivate accounts.
Create and manage teacher accounts (invite, reset password, assign to school).
View and manage student accounts if needed (e.g., bulk import, deactivate).
Configuration and security
Configure global settings (password rules, sign-up restrictions, data retention).
Set content moderation policies and escalation rules.
Monitoring and reports
View high-level usage statistics (number of active classes, posts, reports).
Access audit logs for compliance (who did what, when), without revealing student names in the content itself.

4. Role: Teacher
4.1 Description
The Teacher is part of the class and can respond to anonymous posts, clarifying questions and helping students in a less formal way.
4.2 Functional Requirements
The Teacher shall be able to:[1]
Account and profile
Register / log in using email or school SSO.
Create and manage a teacher profile (name, subject, school, avatar).
Moderation
View all posts and replies, including anonymous posts.
Receive and review content reports from students (e.g., bullying, offensive language).
Communication
Send direct messages to individual students (non-anonymous)
Post clarifications or follow-up questions in a thread.

5. Role: Student
5.1 Description
The Student anonymously posts questions and answers, and interacts with peers directly or in small groups (not anonymously).
5.2 Functional Requirements
The Student shall be able to:
Account and profile
Register / log in using class code plus email or school SSO.
Create a simple profile (first name or nickname, grade).
Class participation
Join classes using a class code or QR code
Anonymous discussion
Post questions, comments, and replies under an anonymous identity as configured by the teacher.
Small group/individual messaging
Message other students under their account for group projects or direct questions
Notifications and activity
Receive notifications when:
Someone replies to their post.
Someone messages them/groups they are in
Reporting and safety
Report posts or replies as inappropriate.
Mute or hide specific threads they do not want to see.
Personal view and history
View their own participation history (number of posts, replies, likes).
See teacher feedback on their contributions.

7. Role: School IT / Support Staff (Optional)
7.1 Description
IT / Support staff help with technical onboarding and troubleshooting
7.2 Functional Requirements
The School IT / Support Staff shall be able to:
Technical onboarding
Integrate with school SSO or directory if applicable.
Batch import students and teachers.
Support and diagnostics
Access an admin dashboard with non-content technical logs (login errors, device types, etc.).
Reset accounts or fix enrollment issues without seeing sensitive discussion content.

8. Non-Functional Requirements (Brief)
Privacy: Student identities should be protected in anonymous mode
Security: Encrypted communication (HTTPS), secure password storage, and role-based access control.
Usability: Simple mobile-first UI for students; quick setup for teachers (class creation in a few steps)


