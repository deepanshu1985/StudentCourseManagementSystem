# Requirement Analysis Document

## Project Name

Student Course Management System

## Version

Version 1 - Console Based Java OOP Application

## 1. Introduction

Student Course Management System is a Java-based console application designed to manage students, teachers, courses, and enrollments.

The main purpose of this project is to apply Object-Oriented Programming concepts in a real-world project and follow proper software engineering practices such as requirement analysis, design, implementation, testing, documentation, and future deployment.

## 2. Problem Statement

In many institutions, student and course records are managed manually or through basic spreadsheets. This creates problems such as:

- Difficulty in managing large student records
- Time-consuming course enrollment process
- Chances of duplicate or incorrect data
- Difficulty in searching and updating records
- Lack of proper structured data management

This system aims to solve these problems by providing a structured console-based application to manage students, teachers, courses, and enrollments.

## 3. Project Objectives

The main objectives of this project are:

1. To build a Java-based console application using OOP concepts.
2. To manage student records.
3. To manage teacher records.
4. To manage course records.
5. To manage student-course enrollments.
6. To write clean, modular, and maintainable code.
7. To prepare the project for future database, web, AI, Docker, and CI/CD integration.

## 4. Project Scope

### 4.1 Current Scope

The current version is a console-based Java application.

It will include:

- Student management
- Teacher management
- Course management
- Enrollment management
- Basic input validation
- Menu-driven console interface
- In-memory data storage using Java Collections

### 4.2 Out of Scope for Version 1

The following features are not included in Version 1:

- Database integration
- Login and authentication
- Graphical user interface
- Web application
- REST APIs
- AI features
- Docker deployment
- CI/CD pipeline
- Cloud deployment

These features will be added in future versions.

## 5. Users / Actors

### 5.1 Admin

In Version 1, Admin is the main user of the system.

Admin can:

- Add students
- View students
- Search students
- Update students
- Delete students
- Add teachers
- View teachers
- Add courses
- View courses
- Enroll students in courses
- View enrollment details

### 5.2 Future Actors

In future versions, the system will include:

1. Student
2. Teacher
3. AI Recommendation System
4. Email Notification System

## 6. Functional Requirements

Functional requirements define what the system should do.

### 6.1 Student Management Requirements

| Requirement ID | Requirement Description |
|---|---|
| FR-01 | The system shall allow Admin to add a new student. |
| FR-02 | The system shall allow Admin to view all students. |
| FR-03 | The system shall allow Admin to search a student by ID. |
| FR-04 | The system shall allow Admin to update student details. |
| FR-05 | The system shall allow Admin to delete a student. |

### 6.2 Teacher Management Requirements

| Requirement ID | Requirement Description |
|---|---|
| FR-06 | The system shall allow Admin to add a new teacher. |
| FR-07 | The system shall allow Admin to view all teachers. |
| FR-08 | The system shall allow Admin to search a teacher by ID. |

### 6.3 Course Management Requirements

| Requirement ID | Requirement Description |
|---|---|
| FR-09 | The system shall allow Admin to add a new course. |
| FR-10 | The system shall allow Admin to view all courses. |
| FR-11 | The system shall allow Admin to search a course by ID. |
| FR-12 | The system shall allow Admin to delete a course. |

### 6.4 Enrollment Management Requirements

| Requirement ID | Requirement Description |
|---|---|
| FR-13 | The system shall allow Admin to enroll a student in a course. |
| FR-14 | The system shall allow Admin to view courses enrolled by a student. |
| FR-15 | The system shall allow Admin to view students enrolled in a course. |

## 7. Non-Functional Requirements

Non-functional requirements define the quality of the system.

| Requirement ID | Requirement Description |
|---|---|
| NFR-01 | The system should be easy to use. |
| NFR-02 | The code should be clean and readable. |
| NFR-03 | The application should follow Object-Oriented Programming principles. |
| NFR-04 | The system should handle invalid inputs properly. |
| NFR-05 | The application should be modular and maintainable. |
| NFR-06 | The project structure should support future database integration. |
| NFR-07 | The project should be easy to convert into a Spring Boot application later. |
| NFR-08 | The system should be scalable for future web and AI features. |

## 8. Assumptions

The assumptions for Version 1 are:

1. The application will run on the console.
2. Only Admin will use the system.
3. No login system will be available in Version 1.
4. Data will be stored temporarily in memory.
5. Student ID will be unique.
6. Teacher ID will be unique.
7. Course ID will be unique.
8. One student can enroll in multiple courses.
9. One course can have multiple students.

## 9. Constraints

The constraints for Version 1 are:

1. No database will be used.
2. No file storage will be used initially.
3. Data will be lost when the program stops.
4. No graphical user interface will be available.
5. No authentication or authorization will be available.
6. The system will run only as a Java console application.

## 10. Future Enhancements

Future versions may include:

1. File handling for data storage
2. MySQL database integration
3. JDBC implementation
4. DAO pattern
5. Spring Boot REST APIs
6. React frontend
7. Spring Security
8. JWT authentication
9. Role-based access control
10. AI course recommendation
11. AI chatbot
12. AI performance analysis
13. Docker support
14. GitHub Actions CI/CD
15. Cloud deployment

## 11. Technology Stack Roadmap

### Version 1

- Java
- OOP
- Collections
- Console-based interface

### Version 2

- File Handling
- Exception Handling
- JUnit Testing

### Version 3

- MySQL
- JDBC
- DAO Pattern

### Version 4

- Spring Boot
- Spring Data JPA
- Hibernate
- REST API

### Version 5

- Spring Security
- JWT
- Role-Based Access Control

### Version 6

- React
- Axios
- Tailwind CSS

### Version 7

- AI Integration
- Course Recommendation
- Chatbot
- Performance Summary

### Version 8

- Docker
- GitHub Actions
- CI/CD
- Cloud Deployment

## 12. Success Criteria

The project will be considered successful in Version 1 if:

1. Admin can manage students successfully.
2. Admin can manage teachers successfully.
3. Admin can manage courses successfully.
4. Admin can enroll students in courses.
5. The application follows OOP principles.
6. The code is modular and readable.
7. Basic documentation is maintained.
8. The project is pushed properly to GitHub.

## 13. Conclusion

This requirement analysis document defines the basic requirements, scope, assumptions, constraints, and future roadmap of the Student Course Management System.

This document will act as the foundation for the design, implementation, testing, and future enhancement of the project.