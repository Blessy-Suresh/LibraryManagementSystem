Library Management System

A simple Java-based Library Management System built using Servlets, JDBC, and Oracle Database.
This application allows an administrator to add and search books stored in a database.

 Features

*  Add new books
*  Search book by ISBN
*  View book details (Title, Author, Contact, ISBN)
*  Input validation in Service Layer
*  MVC Architecture (Servlet → Service → DAO → DB)
*  Oracle Database integration using JDBC

 Technologies Used

* Java (JDK 8+)
* Servlets & JSP
* JDBC
* Oracle Database (XE / XEPDB1)
* Apache Tomcat
* HTML


Project Architecture

Client (HTML Form)
        ↓
MainServlet
        ↓
Service Layer (Administrator)
        ↓
DAO Layer (BookDAO / AuthorDAO)
        ↓
Oracle Database




