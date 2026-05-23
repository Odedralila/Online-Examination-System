# Online Exam System

An Online Exam System developed using PHP and MySQL. This project allows users to register, log in, attend exams, and view results. Admin can manage exams, questions, and user data.

## Features

- User Registration and Login
- Admin Login
- Create and Manage Exams
- Add and Manage Questions
- Submit Exam Answers
- Automatic Score Calculation
- Result Display
- User Score Tracking

## Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: PHP
- Database: MySQL
- Server: XAMPP / Apache

## Project Structure

```text
Project/
│
├── admin/
├── user/
├── pic/
├── header.php
├── index.php
├── signup.php
├── logout.php
├── submit_exam.php
└── result.php
```

## Database Setup

Database Name:

```sql
exam_system
```

Tables Used:

```sql
admin
exams
questions
scores
users
```

## Installation Steps

1. Download or clone the repository

2. Copy project folder into XAMPP htdocs directory

```text
C:/xampp/htdocs/
```

3. Start Apache and MySQL from XAMPP

4. Open phpMyAdmin

5. Create database:

```sql
CREATE DATABASE exam_system;
```

6. Import the SQL file into phpMyAdmin

7. Open browser and run:

```text
http://localhost/project_folder_name
```


## Future Improvements

- Timer for exams
- Negative marking system
- Email notifications
- Better UI design
- Password encryption

## Author

Created by: Odedra Lila
