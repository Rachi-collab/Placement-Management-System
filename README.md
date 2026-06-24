# Placement Management System

## Overview

Placement Management System is a full-stack application designed to simplify and automate the campus placement process. The platform provides a centralized system for students, recruiters, and placement administrators to manage placement activities efficiently.

The system reduces manual effort by digitizing student registrations, company interactions, placement applications, and recruitment workflows.

---

## Problem Statement

Managing placement activities manually involves handling large amounts of student data, recruiter information, applications, and communication. This often leads to inefficient tracking, data duplication, and difficulty in maintaining records.

This project provides a centralized platform that streamlines the entire placement lifecycle.

---

## Solution

A scalable placement management platform that enables:

- Students to create profiles and apply for opportunities
- Recruiters to manage job postings and applications
- Administrators to monitor placement activities
- Efficient tracking of recruitment workflows

---

## Features

### Student Module

- Student registration and profile management
- Resume and academic information management
- Browse available placement opportunities
- Apply for job openings
- Track application status


### Recruiter Module

- Recruiter/company registration
- Create and manage job postings
- View eligible student applications
- Manage recruitment processes


### Admin Module

- Manage students and recruiters
- Monitor placement drives
- Maintain placement records
- Control application workflows


### Core Functionalities

- Authentication and authorization
- Role-based access control
- RESTful API communication
- Database management
- Modular backend architecture

---

## Technology Stack

### Backend

- Java
- Spring Boot
- Spring MVC
- REST APIs

### Database

- MySQL

### Architecture

- Microservices Architecture
- Service-based backend design

### Tools

- Git
- GitHub
- Maven

---

## System Architecture
Client Application
|
|
v
REST API Layer
|
|
v
Spring Boot Services
|
|
v
MySQL Database

---

## Project Structure

Placement-Management-System

├── backend
│ ├── controllers
│ ├── services
│ ├── repositories
│ ├── models
│ └── configurations
│
├── frontend
│
├── database
│
└── README.md

---

## Installation and Setup

### Clone Repository

```bash
git clone <repository-url>

Navigate to Project
cd Placement-Management-System

Backend Setup
mvn clean install
mvn spring-boot:run

Database Setup
Install MySQL
Create database
Configure credentials in application.properties
Start the application

Future Improvements
JWT-based authentication
Email notifications
Resume parsing using AI
Cloud deployment
Analytics dashboard
Docker containerization
Learning Outcomes
Developed REST-based backend services
Worked with Spring Boot application structure
Designed database models and relationships
Implemented scalable software architecture
Improved understanding of full-stack application development

Author

Rachi Rajpal

Computer Science Undergraduate
