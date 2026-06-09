# CodeVault
A personal DSA Problem Tracker built with Spring Boot and MySQL to track coding problems, organize them with tags, add notes, and visualize progress through an interactive dashboard.

## 🔐 Authentication
Secure login and registration system with form validation and user account management.
<img width="1888" height="592" alt="image" src="https://github.com/user-attachments/assets/a9fce0c5-00e8-44a5-8fec-77cdd008ece1" />

## 📊 Dashboard
Get an overview of your coding journey with progress statistics, difficulty distribution, recent problems, starred problems, and topic tags.
<img width="1884" height="587" alt="image" src="https://github.com/user-attachments/assets/d57e5ff0-b24c-4347-84e3-0c355c89a8b8" />

## 📚 Problem Library
Manage all your DSA problems in one place with filtering, searching, starring, editing, and deletion capabilities.
<img width="1891" height="576" alt="image" src="https://github.com/user-attachments/assets/1d026241-6d9c-485d-874e-d516e8aacb43" />

## ➕ Add Problems
Store important details such as difficulty, status, topic, platform, complexity analysis, notes, and problem links.
<img width="1898" height="776" alt="image" src="https://github.com/user-attachments/assets/dc09bc8c-c6c4-4d52-acbf-5f76ba1fa820" />

## 📝 Problem Details & Notes
Review complexity analysis, personal notes, approaches, attempt history, and quickly access the original problem.
<img width="1893" height="634" alt="image" src="https://github.com/user-attachments/assets/7d167b82-3cee-415e-bf94-8a1799d2a292" />

# CodeVault

CodeVault is a web application I built to keep track of my DSA practice. While solving problems on platforms like LeetCode, GeeksforGeeks, and Codeforces, I often found it difficult to remember which problems I had solved, which ones needed revision, and the approaches I had used. This project was created to solve that problem.

With CodeVault, users can add problems, store notes and complexity analysis, mark important questions, and view their overall progress from a dashboard. The goal is to have a single place to organize and revisit coding problems.

## Features

* User registration and login
* Add, edit, and delete problems
* Track problem status (Solved, Attempted, Revisit, Pending)
* Store time and space complexity
* Save personal notes and approaches
* Mark important problems with a star
* Search and filter problems
* View statistics from the dashboard
* Organize problems by topic and platform

## Architecture

The project follows the MVC (Model-View-Controller) architecture and uses a layered backend structure.

```
User
  ↓
Thymeleaf Views
  ↓
Controllers
  ↓
Services
  ↓
Repositories
  ↓
MySQL Database
```

### Backend Flow

1. The user interacts with the UI built using Thymeleaf.
2. Requests are handled by Spring Boot controllers.
3. Business logic is implemented inside service classes.
4. Spring Data JPA repositories communicate with the database.
5. Problem and user information is stored in MySQL.

## Tech Stack

**Backend**

* Java 17
* Spring Boot
* Spring MVC
* Spring Data JPA

**Frontend**

* Thymeleaf
* HTML
* CSS
* JavaScript

**Database**

* MySQL

**Build Tool**

* Maven

## Project Structure

```
CodeVault
├── controller
├── service
├── repository
├── entity
├── templates
├── static
└── database (MySQL)
```

This project was built mainly to make DSA revision easier and to maintain a record of solved problems and approaches instead of relying on spreadsheets or scattered notes.
