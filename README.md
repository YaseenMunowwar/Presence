# Presence
## An AI-powered Django web application that uses facial recognition to mark attendance.

![image](https://github.com/YaseenMunowwar/Presence/assets/120727198/4cd52b82-f2aa-439a-a396-155ca27ba5b7)

# Attendance Management System Using Face Recognition 💻
Overview
This project aims to build an advanced attendance system that utilizes facial recognition technology to mark the presence, time-in, and time-out of employees. The system offers features such as facial detection, alignment, and recognition, along with the development of a web application that caters to various use cases such as employee registration, addition of photos to the training dataset, and viewing attendance reports. The goal is to provide an efficient substitute for traditional manual attendance systems and enhance security in corporate offices, schools, and organizations.

# Key Features
Facial detection, alignment, and recognition for accurate attendance marking
Web application with user-friendly UI for easy navigation and management
Employee registration and photo addition to the training dataset
Generation of attendance reports with filters for date and employee

# Scope of the Project 🚀
Facial recognition technology is gaining prominence in various domains, particularly in the field of security. This project serves as a foundation for future advancements in facial detection and recognition, with potential applications in areas like ATMs, access control systems, and more. The project also covers web development and database management, providing a comprehensive solution for attendance management. Organizations of all types can benefit from this system by replacing traditional attendance methods and generating detailed attendance reports.

# User Roles
The system caters to two types of users:

Admin: Performs administrative tasks such as login, employee registration, photo addition, model training, and viewing attendance reports.
Employee: Marks their time-in and time-out by scanning their face, and can view their attendance report.

# Technology Stack
#### Language: Python
#### Framework: Django
#### Front-end: HTML, CSS, JavaScript
#### Libraries: Dlib (HOG facial detector and 68 point shape predictor), face_recognition, scikit-learn
#### Database: SQLite

# Documentation 📰
The documentation folder contains detailed information about the project, including UML diagrams and other relevant documents.

# How to Run
#### 1. Clone the repository to your local machine.
#### 2. Set up a Python virtual environment: python -m venv env
#### 3. Activate the virtual environment:
 ##### 3.1 Windows: env\Scripts\activate
 ##### 3.1 macOS/Linux: source env/bin/activate
#### 4. Install dependencies: pip install -r requirements.txt
#### 5. Run the application: python manage.py runserver
