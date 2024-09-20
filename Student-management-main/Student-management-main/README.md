# Student Management System (SMS) using Django
This is a simple Student Management System developed while learning Django. The project allows administrators, staff, and students to manage student-related information. It includes features such as attendance tracking, result management, leave requests, and feedback.

# Features

A. Admin Users
View overall summary charts of student performances, staff performances, courses, subjects, and leave status.
Manage students (add, update, and delete).
Manage courses (add, update, and delete).
Manage subjects (add, update, and delete).

View student attendance.
Review and reply to student/staff feedback.
Approve or reject student/staff leave requests.

B. Staff/Teachers
View overall summary charts related to their students, subjects, and leave status.
Take/update student attendance.
Add/update student results.

C. Students
View overall summary charts related to their attendance, subjects, and leave status.
View attendance records.
View results.
Apply for leave.
Send feedback to the HOD.
Installation and Setup
# Pre-Requisites:
Install Git Version Control 1.
Install Python (latest version) 2.
Install Pip (Package Manager) 3.
Create a Virtual Environment:
Create a folder where you want to save the project.
Create a virtual environment (venv):
For Windows: python -m venv venv
For Mac: python3 -m venv venv
For Linux: virtualenv .
Activate the virtual environment:
For Windows: source venv/scripts/activate
For Mac/Linux: source venv/bin/activate
Clone the Project:
Clone this project from GitHub:
git clone https://github.com/Pugazhendhi-github/student-management-system.git
cd student-management-using-django

Install Dependencies:
Install required packages from requirements.txt:
pip3 install -r requirements.txt

Configure Allowed Hosts:
In settings.py, set ALLOWED_HOSTS = [] (for local development). Avoid using default allowed settings from the repository for security reasons.
Run the Server:
Run the development server:
For PC: python manage.py runserver
For Mac: python3 manage.py runserver
For Linux: python3 manage.py runserver
Demo
Check out the live demo of this project.

If you find this project useful, don’t forget to give it a ⭐️!

Feel free to customize the content and add any additional sections relevant to your project. Good luck with your Student Management System! 🚀
