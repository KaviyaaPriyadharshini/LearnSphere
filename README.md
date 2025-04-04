# Learning Management System (LMS)

## Overview
The **Learning Management System (LMS)** is a web-based platform designed to manage online courses, assessments, progress tracking, and user interactions efficiently. It is built using **React.js** for the frontend, **Spring Boot** for the backend, and **MySQL** as the database.

## Features

### User Management
- User registration and authentication (Login/Signup).
- User profile management with update functionality.

### Course Management
- Admin can create, edit, and delete courses.
- Course details include name, instructor, description, and syllabus.

### Assessments
- Users can take assessments related to enrolled courses.
- Admin can create and manage assessment questions.

### Progress Tracking
- Track user progress and course completion status.
- Visual progress representation using dashboards.

### Certificate Generation
- Auto-generate certificates upon course completion.
- Personalized certificates with user details.

### Discussion Forum
- Course-specific discussion boards.
- Facilitates interaction between users and instructors.

### Admin Dashboard
- Course and assessment management.
- Tracking of students, courses, and enrollments.

## Technologies Used

### Frontend:
- React.js
- Styled with CSS and Bootstrap

### Backend:
- Spring Boot
- RESTful API architecture

### Database:
- MySQL
- Core tables: `course`, `learning`, `progress`, `discussion`, `feedback`, `question`, `user`, `assessment`

## Setup & Installation

### Prerequisites
- **Node.js** (for frontend)
- **Java & Spring Boot** (for backend)
- **MySQL** (for database)

### Steps to Run the Project
1. **Clone the repository:**
   ```bash
   git clone https://github.com/KaviyaaPriyadharshini/LearnSphere
   ```
2. **Backend Setup:**
   - Navigate to the backend folder and set up the Spring Boot application.
   - Configure the MySQL database connection in `application.properties`.
   - Start the backend server:
     ```bash
     mvn spring-boot:run
     ```
3. **Frontend Setup:**
   - Navigate to the frontend folder and install dependencies:
     ```bash
     npm install
     ```
   - Start the React development server:
     ```bash
     npm start
     ```
4. **Access the application:**
   - Frontend runs on: `http://localhost:3000`
   - Backend runs on: `http://localhost:8080`

## Usage Guide

- **Admin Panel (`http://localhost:3000/dashboard`)**
  - Manage courses and assessments.
  - Track students and enrollments.
- **User Panel**
  - Register, log in, and browse courses.
  - Enroll in courses and attempt assessments.
  - View progress and download certificates.

## Contribution Guidelines
Contributions are welcome! Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit changes and push the branch.
4. Open a Pull Request (PR).
