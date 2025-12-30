# Online-Meditation-Mindfulness-Platform-2

Project Overview=
The Online Meditation & Mindfulness Platform is a Java web-based application designed to help users practice mindfulness through guided meditation sessions while tracking their progress.
The system also provides instructors/admins with tools to manage content, monitor user engagement, and interact with users.

This project follows MVC architecture, uses JSP, Servlets, JDBC, and is developed according to Review-2 requirements focusing on robustness, validation, integration, and code quality.

Objectives-
Provide guided meditation sessions to users
Track user mindfulness progress and activity history
Enable instructor-user interaction
Ensure secure, validated, and error-free data handling
Demonstrate clean Java Web Application architecture

Technologies Used-
Frontend: JSP, HTML, CSS, JavaScript
Backend: Java (Servlets)
Database: MySQL
Connectivity: JDBC
Server: Apache Tomcat
Architecture: MVC (Model–View–Controller)

Project Structure-
Online-Meditation-Mindfulness-Platform/
│
├── src/
│   ├── controller/        # Servlets (request handling & control flow)
│   ├── dao/               # Database access logic (JDBC)
│   ├── model/             # JavaBeans / Entity classes
│   ├── util/              # Database utility & helpers
│
├── WebContent/
│   ├── css/               # Stylesheets
│   ├── js/                # Client-side validation & scripts
│   ├── jsp/               # JSP pages (Views)
│   ├── login.jsp
│   ├── register.jsp
│   └── dashboard.jsp
│
├── db/
│   └── schema.sql         # Database schema
│
├── README.md
└── pom.xml (if applicable)

Core Features Implemented (Review-2)
User Module
User Registration & Login
Guided Meditation Sessions
Mindfulness Progress Tracking
Activity History & Session Logs
Profile Management
Instructor/Admin Module
Upload & Manage Meditation Content (Audio/Text)
View User Progress & Trends
Review User Feedback
Interaction History with Users

Review-2 Requirements Mapping
1. Core Feature Implementation

✔ Fully working authentication
✔ Meditation session management
✔ Progress tracking dashboards

2. Error Handling & Robustness

✔ Try–catch blocks in Servlets & DAO
✔ Graceful handling of invalid inputs
✔ No application crashes

3. Integration of Components

✔ JSP ↔ Servlet ↔ DAO ↔ Database flow
✔ Proper MVC separation

4. Event Handling & Processing

✔ Optimized servlet request handling
✔ JavaScript-based form validation

5. Data Validation

✔ Client-side validation using JavaScript
✔ Server-side validation using Java logic

6. Code Quality & Innovation

✔ Modular and readable code
✔ DAO pattern for database operations
✔ Role-based access concept

7. Project Documentation

✔ Clear README
✔ Structured folder hierarchy
✔ Setup and usage instructions

 Testing

Tested all user inputs for invalid data

Verified database operations (CRUD)

Checked session handling and navigation flow

Ensured smooth execution on Apache Tomcat

How to Run the Project
1️⃣ Database Setup
CREATE DATABASE mindfulness;
USE mindfulness;
-- Run db/schema.sql

2️⃣ Configure Database

Update credentials in:

src/util/DatabaseUtil.java

3️⃣ Run on Server

Import project into Eclipse / VS Code

Configure Apache Tomcat

Start the server

4️⃣ Access Application
http://localhost:8080/OnlineMeditationPlatform/login.jsp

🚀 Future Enhancements

Meditation recommendation system

Mobile-friendly UI

Advanced analytics & reports

Notification & reminder system
