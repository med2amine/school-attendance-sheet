🎓 EduTruck – Student & Teacher Management System
EduTruck is a Python-based CLI application for managing students, teachers, grades, and attendance records. It’s built using simple Python and JSON for persistent data storage — no database or web server required.

✅ Great for small schools, classrooms, or learning how to build real-world CRUD apps with Python.

✨ Features
📚 Student Management

Add/update student information

Assign grades by subject

Track attendance by date

🧑‍🏫 Teacher Management

Add/update teachers

Link them to subjects and classes

📊 Reports

Class average by subject

Student average across all subjects

Attendance tracking and reporting

🔍 Search & Filter

List students by class or group

List teachers by subject

Get individual student profiles

📁 File Structure
bash
Copy
Edit
├── class_sheet.json      # All student & teacher data saved here
├── edutruck.py           # Main application file
└── README.md             # Project documentation
⚙️ How It Works
Run the script:

bash
Copy
Edit
python edutruck.py
Use the menu to choose actions (add student, add grade, mark attendance, etc.)

All data is saved to class_sheet.json for future sessions.

🛠 Technologies Used
Python 3

JSON (for data storage)

datetime for date handling

🧠 Skills Practiced
Python data structures (dicts, lists)

File handling and JSON

CLI menu design

Debugging and logic building

Modular programming
