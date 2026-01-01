# FitSphere – Gym Management System

## Project Proposal

### Problem Statement
Most local gyms still manage members, payments, and schedules using registers or basic spreadsheets. This causes issues like lost records, missed payment reminders, poor member tracking, and no clear way to monitor progress. There is a need for a centralized, digital system that simplifies gym operations and improves member engagement.

### Proposed Solution
FitSphere is a web-based Gym Management System that automates member management, trainer assignments, attendance tracking, and payments. It provides separate dashboards for Admin, Trainers, and Members.

## Software Requirements Specification (SRS)

### User Classes
* **Admin:** Full access to the system (Manage members, trainers, plans, payments).
* **Trainer:** Manages assigned members, tracks attendance.
* **Member:** Views profile, attendance, payments, membership status.

### Functional Requirements

#### Admin Panel
* Secure login.
* Add, update, delete trainers and members.
* Create and manage membership plans.
* View attendance reports and manage payments.

#### Trainer Panel
* Login.
* View assigned members.
* Mark attendance.

#### User (Member) Panel
* Register and login.
* View membership details.
* View attendance history and payment records.
* Update personal information.

### Non-Functional Requirements
* **Security:** Encrypted passwords, authorized access only.
* **Performance:** < 2s response time.
* **Usability:** Mobile-friendly, easy to use.
* **Reliability:** Data consistency, no duplicate records.
*

## Database Design (ER Diagram Summary)
* **Users:** Stores login info and role.
* **Members:** specific member info, linked to User and Membership Plan.
* **Trainers:** specific trainer info, linked to User.
* **Membership_Plans:** Plan details.
* **Attendance:** Linked to Member.
* **Payments:** Linked to Member.
