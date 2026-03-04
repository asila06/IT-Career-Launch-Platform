# IT-Career-Launch-Platform
# 1. Course Name.
Cap1: System Analysis and Design
  
# 2. Team Information
**Team Name:** chenada

| Name    | Student ID | Group | Role            | Phone Number      |
| ------- | ---------- | ----- | --------------- | ----------------- |
| Khusnutdinova Alina  | 202490372  | I24B  | Leader          | +998 (93) 5124637 
| Avazbekov Abduraxmonbek | 202490056 | I24B  | Project Manager | --
| Shamsutdinov Doniyorbek | 202490285 | I24A  | Coder | -- 
| Isayev Yorkinjon | 202490139 | I24B  | Ideator | --

# 3. Project Title and Description
The IT Career Launch Platform is a web-based system designed to support IT students and junior specialists in gaining practical experience through real projects and guided learning.
The platform serves as a centralized environment where students can explore available projects, apply for participation, and improve their skills through courses, while mentors and employers can post projects and manage applications.

The system is supported by a relational SQL database that ensures structured data storage, data integrity, and efficient retrieval of information.

Key Features and System Processes:
- User Registration and Role Management
- Project Creation and Management
- Project Browsing and Application
- Application Status Tracking
- Course Listing for Skill Development
- Data Management and Integrity

Related tables:
- One user → many projects
- One user → many applications
- One project → many applications
- Many users ↔ many courses 
- Many projects ↔ many skills 
- Many users ↔ many skills 

# 4. Problem Statement
Many IT students face difficulties entering the job market due to a lack of practical experience, real projects, and professional mentorship.
Traditional education often focuses on theory, while employers require hands-on skills. As a result, students struggle to build portfolios, and companies struggle to find prepared junior specialists.

# 5. Project Objectives
The main objectives of the project are:

- To provide IT students with access to real projects and practical experience
- To connect students with mentors and employers
- To simplify the process of applying for projects
- To store and manage information about users, projects, and applications using an SQL database
- To improve students’ employability and career readiness

# 6. Scope of the System
The system includes:

- User registration and role management (student, mentor, employer)
- Project creation and management
- Project application and status tracking
- Course listing for skill development
- Data storage and management using an SQL database

System Limitations:

The system has the following limitations:
- The platform does not include online payment or financial transactions
- Real-time communication features (such as live chat or video calls) are not supported
- The system does not provide automated project matching or AI-based recommendations
- Advanced analytics and reporting features are not included
- The system is designed for academic and demonstration purposes only and may not support large-scale commercial usage

# 7. Expected Users
The platform is designed for the following users:

- Students – apply for projects, join courses, and gain experience
- Mentors – create projects and guide students
- Employers – post projects and find junior specialists
- Administrators – manage users and system data

# 8. Project Timeline (5 Weeks)
| Week                           |           Activities                   |
|------------------------       |-------------------------------------|
| Week 1(06.Feb ~ 13.Feb)  | Project planning                    |
| Week 2(13.Feb ~ 20.Feb)  | BPM,Use case                |
| Week 3(20.Feb ~ 27.Feb)  | BPM,Use case                 |
| Week 4(27.Feb ~ 06.Mar)  | ERD Design                                 |
| Week 5(06.Feb ~ 13.Feb)  | Report writing and presentation preparation |

# Business Process Model (BPM)

<img width="994" height="465" alt="image" src="https://github.com/user-attachments/assets/e7fbf228-c136-462d-917d-cc0de8656868" />
<img width="877" height="475" alt="image" src="https://github.com/user-attachments/assets/c9d14cce-efee-4fa4-b89f-01d2ee0a0d6c" />
<img width="896" height="606" alt="image" src="https://github.com/user-attachments/assets/f1811f8e-7719-4cbb-af06-c35064761e1b" />

# Enterprise Resource Planning (ERP) System Design
The ERP design of the IT Career Launch Platform defines the system architecture and modules that support business processes such as user registration, project management, and application handling. The system follows a modular structure where all functional components are integrated through a centralized SQL database.

- 1 User Management Module
Functions:
User registration
Login authentication
Role management (Student, Mentor, Employer)
Profile data storage
Related Database Table:
users

- 2 Project Management Module
Functions:
Create new project
Edit project
View project list
Store project details
Related Database Table:
projects

- 3 Application Management Module
Functions:
Submit application
Track application status
Approve / Reject application
Related Database Table:
applications

- 4 Course Management Module
Functions:
Add courses
View courses
Related Database Table:
courses

                ┌────────────────────┐
                │   User Management  │
                └─────────┬──────────┘
                          │
                ┌─────────▼──────────┐
                │  Project Management│
                └─────────┬──────────┘
                          │
                ┌─────────▼──────────┐
                │ Application Mgmt   │
                └─────────┬──────────┘
                          │
                ┌─────────▼──────────┐
                │   SQL Database     │
                └────────────────────┘
# Database Design and SQL Implementation
The system database is implemented using a relational model. The main entities include Users, Projects, Applications, and Courses. Relationships between tables are established using primary and foreign keys.

<img width="560" height="656" alt="image" src="https://github.com/user-attachments/assets/0353d105-0a53-42a1-bdb4-bf4682f756db" />
<img width="486" height="200" alt="image" src="https://github.com/user-attachments/assets/3893b362-d97e-441b-b7b9-e1c0e800fba3" />
<img width="1280" height="440" alt="image" src="https://github.com/user-attachments/assets/391d156e-1cee-4c93-811c-3367364391a3" />

The SQL implementation demonstrates how business processes are supported through relational database design, ensuring data integrity and efficient information management.

# 9. Outcome of the Project
As a result of this project:

- A structured SQL database will be created to manage users, projects, and applications
- Students will gain easier access to practical IT experience
- Mentors and employers will be able to find motivated beginners
- The system will demonstrate effective use of relational databases, including tables, relationships, and SQL queries

# 10. Conclusion
The IT Career Launch Platform project demonstrates how business processes can be supported through a structured ERP system and relational database design using MySQL.
The system integrates core modules such as User Management, Project Management, and Application Management into a centralized database structure. Business processes were modeled using BPM, while ERP design illustrated the system architecture. The SQL implementation provided practical evidence of how data is stored, managed, and connected through primary and foreign keys.
This project highlights the importance of database systems in modern digital platforms. It also demonstrates how structured data management improves efficiency, organization, and transparency within an information system.
Overall, the project successfully combines business logic, system architecture, and technical implementation into a functional academic prototype.

# 11. References
The following resources were used during the development of this project:
- MySQL Official Documentation – https://dev.mysql.com/doc/
- W3Schools SQL Tutorial – https://www.w3schools.com/sql/
- Programiz MySQL Tutorial – https://www.programiz.com/sql
- Draw.io (Diagrams.net) – https://www.diagrams.net/
- Lucidchart BPMN Templates – https://www.lucidchart.com

# 12. Appendix
## Important SQL Code Snippets
#### Database Creation
```sql
CREATE DATABASE it_platform;
USE it_platform;
```

---
#### Example Table with Relationship
```sql
CREATE TABLE applications (
    application_id INT PRIMARY KEY AUTO_INCREMENT,
    user_id INT,
    project_id INT,
    status ENUM('Pending', 'Approved', 'Rejected') DEFAULT 'Pending',
    FOREIGN KEY (user_id) REFERENCES users(user_id),
    FOREIGN KEY (project_id) REFERENCES projects(project_id)
);
```

---
#### Example JOIN Query
```sql
SELECT users.name, projects.title, applications.status
FROM applications
JOIN users ON applications.user_id = users.user_id
JOIN projects ON applications.project_id = projects.project_id;
```

---
## Additional Materials

- BPM Diagram (Business Process Model)
- ERP System Architecture Diagram
- Screenshots of SQL execution
- Sample data output tables
