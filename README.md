## SmartLeave – Leave Management System

SmartLeave is a web-based Leave Management System developed using Java, JDBC, MySQL, HTML, CSS, and Servlet-JSP. It is designed to simplify leave application and approval processes in educational institutions or organizations through role-based access.

### Project Overview

The system allows students to apply for leave online, faculty to review and approve or reject requests, and admin to manage users, monitor applications, and generate reports. This project was developed as part of an academic curriculum.

### Features

**Student**

* Apply for leave
* View leave application status

**Faculty**

* View pending leave requests
* Approve or reject leave applications

**Admin**

* Manage student and faculty users
* View all and pending applications
* Change admin password
* Generate PDF reports

### Tech Stack

* Java
* Servlet & JSP
* JDBC
* MySQL
* HTML/CSS
* Apache Tomcat

### How to Run

1. Clone the repository

```bash
git clone <repository-url>
```

2. Import the project into Eclipse IDE

3. Configure MySQL database and run the SQL script from `resources/databaseStructure.txt`

4. Add MySQL connector JAR from `WEB-INF/lib` to the build path

5. Deploy on Apache Tomcat and run the project

6. Access in browser:
   `http://localhost:8080/LeaveManagementSystem/`





