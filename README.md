🎓 Academic Performance Management System (APMS) v1.0
📌 Overview

The Academic Performance Management System (APMS) v1.0 is a desktop-based academic result processing system developed using Python and Tkinter GUI.

It is designed to manage students, courses, enrollments, academic sessions, and academic performance while automatically calculating GPA and CGPA.

This system is suitable for:

Universities

Polytechnics

Colleges

Secondary Schools

Academic Final Year Projects

🚀 Features
🔐 Authentication System

Admin Login

Student Login

Password Change Functionality

Role-based Access Control

👨‍💼 Admin Features

Manage Students (Add / Edit / Delete / Search)

Manage Courses

Manage Academic Years

Manage Semesters

Enroll Students into Courses

Record and Update Scores

Automatic Grade Calculation

Automatic GPA & CGPA Computation

View Student Academic Reports

👨‍🎓 Student Features

View GPA per Semester

View CGPA

GPA Performance Chart

Transcript Preview

Change Password

Secure Logout

📊 Academic Calculations

Automatic Grade Assignment (A–F)

Grade Point Calculation

GPA Calculation per Semester

CGPA Calculation (Cumulative)

GPA Visualization Chart

🎨 User Interface

Modern Dark Theme

Dashboard Card Layout

Professional Header Design

Responsive Tkinter Layout

Scrollable Tables with Search

🛠️ Built With

Python 3.x

Tkinter (GUI Framework)

SQLite3 (Database)

Matplotlib (GPA Chart Visualization)

📂 Project Structure
APMS_v1.0/
│
├── main.py
├── database.db
├── README.md
└── requirements.txt
⚙️ Installation Guide
1️⃣ Clone the Repository
git clone https://github.com/angelnaitbj/APMS-v1.0.git
2️⃣ Navigate to the Project Folder
cd APMS-v1.0
3️⃣ Install Required Packages
pip install matplotlib

(Tkinter and SQLite come pre-installed with Python)

4️⃣ Run the System
python main.py
🧮 GPA & CGPA Calculation Logic
GPA Formula:
GPA = Total Quality Points / Total Credit Units
CGPA Formula:
CGPA = Total Cumulative Quality Points / Total Cumulative Credit Units
Grading Scale Example:
Score	Grade	Grade Point
70 – 100	A	5.0
60 – 69	B	4.0
50 – 59	C	3.0
45 – 49	D	2.0
40 – 44	E	1.0
0 – 39	F	0.0
🖥️ Screenshots

<img width="1536" height="1024" alt="loginppt" src="https://github.com/user-attachments/assets/30719f4e-234f-4fac-be68-49a97530f066" />
<img width="1024" height="1536" alt="Admindashboardppt" src="https://github.com/user-attachments/assets/4a108835-9150-493c-bcd9-b3c2c57e6fa9" />
<img width="1536" height="1024" alt="CRUDppt" src="https://github.com/user-attachments/assets/56e8ab26-9bfc-41c9-895d-2760ea50f893" />
<img width="1536" height="1024" alt="studentdashboardppt" src="https://github.com/user-attachments/assets/df7a918f-9111-47af-9778-3762bf08e53d" />


Login Interface

Admin Dashboard

Student Dashboard

GPA Chart

Transcript Preview

🔐 Security Features

Password authentication system

Role-based system separation

Protected admin panel

Controlled student data access

🎯 Project Objectives

Digitize academic performance management

Automate GPA & CGPA calculations

Provide real-time academic analytics

Improve data accuracy and efficiency

Reduce manual result processing

🏆 Version History
v1.0

Basic student and course management

Manual GPA system

v0.0

Full CRUD functionality

Automatic GPA & CGPA

Enrollment system

v1.0 (Current Version)

Modern Dashboard UI

GPA Chart Visualization

Transcript Preview

Improved UI Design

Enhanced Security

Search & Scrollable Tables

📌 Future Improvements (v2.0 Ideas)

Multi-Admin Support

Web-Based Version (Flask/Django)

Cloud Database Integration

👨‍💻 Author

ANGEL NAITBJ

Final Year Project – Academic Performance Management System
Developed using Python & Tkinter

📜 License

This project is for educational and academic purposes.
