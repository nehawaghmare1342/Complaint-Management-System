# Complaint-Management-System

📝 Complaint Management System

A web-based Complaint Management System built using Spring Boot, Spring Data JPA, Thymeleaf, and MySQL.
This application allows users to create, view, search, update, and delete complaints, along with a dashboard to track complaint status.

🚀 Features
Create new complaints
View complaint details
Edit & update complaints
Delete complaints
Search complaints by keyword
Dashboard with:
Total complaints
Open complaints (New + In Progress)
Resolved complaints (Resolved + Closed)
Automatic date handling:
Created date for new complaints
Resolved date when status is Resolved/Closed

🛠️ Technologies Used
Java
Spring Boot
Spring MVC
Spring Data JPA (Hibernate)
Thymeleaf
MySQL
Maven
HTML / CSS

📂 Project Structure
com.project.complaint
│
├── controller
│   ├── ComplaintController.java
│   └── DashboardController.java
│
├── service
│   ├── ComplaintService.java
│   └── ComplaintServiceImpl.java
│
├── repository
│   └── ComplaintRepository.java
│
├── entity
│   └── Complaint.java
│
└── resources
    ├── templates
    │   ├── dashboard.html
    │   ├── complaints-list.html
    │   ├── complaint-form.html
    │   └── complaint-view.html
    └── application.properties
