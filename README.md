🎓 Student Management System
📌 Project Overview

The Student Management System is a web-based application developed using Flask and SQLite that helps manage student records efficiently.

This system allows users to:

Register students

View student details

Edit student information

Delete student records

Login authentication system

The project follows a Flask MVC structure using templates, static files, and backend logic.

🚀 Features

✅ User Login System
✅ Add New Students
✅ View Student Records
✅ Edit Student Details
✅ Delete Students
✅ Clean and Responsive UI
✅ SQLite Database Integration

🛠️ Technologies Used

Frontend

HTML5

CSS3

Backend

Python

Flask Framework

Database

SQLite3

📂 Project Structure
Student-Management-System/
│
├── app.py
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── add.html
│   ├── edit.html
│   └── view.html
│
├── static/
│   └── style.css
│
├── students.db
│
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/student-management-system.git
cd student-management-system
2️⃣ Create Virtual Environment (Optional but Recommended)
python -m venv venv

Activate environment:

Windows

venv\Scripts\activate

Mac/Linux

source venv/bin/activate
3️⃣ Install Required Packages
pip install flask
4️⃣ Run the Application
python app.py
5️⃣ Open in Browser
http://127.0.0.1:5000/
🧠 How the System Works
🔹 app.py

Contains:

Flask routes

Database connection

CRUD operations

Login authentication

Request handling

🔹 Templates Folder

Stores all HTML pages:

File	Description
index.html	Home page
login.html	User login page
register.html	User registration
add.html	Add student details
edit.html	Update student data
view.html	Display all students
🔹 Static Folder

Contains:

style.css → UI styling and layout design

🗄️ Database

SQLite database (students.db) stores:

Student ID

Name

Age

Course

📸 Screens Included

Login Page

Registration Page

Student Dashboard

Add/Edit Student Forms

Student List View

🔮 Future Enhancements

Search functionality

Role-based login

Password encryption

Pagination

REST API integration

Deployment on cloud

👩‍💻 Author

Pratyusha Kotni

📜 License

This project is developed for learning and educational purposes.
