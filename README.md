# My-Projects-C_language-
School Management System (C Language)

A console-based School Management System built using C that allows efficient management of student records with features like search, update, delete, and file storage.

** Features**
 Add Student Records
 Search by Roll Number
 Search by First Name
 Search by Course
 Update Student Details
 Delete Student Records
 Count Total Students
 File Storage (Save & Load Data)
🔐 Input Validation & Duplicate Check
🧠 System Workflow

[ USER ] ──▶ [ MENU ] ──▶ [ OPERATIONS ] ──▶ [ DATA STORAGE ]

📂 Project Structure

School-Management-System/
│
├── main.c
├── students.txt
├── README.md
└── LICENSE

⚙️ Compilation & Execution
🔧 Compile:

gcc main.c -o school

▶️ Run:

./school

💾 Data Storage
Uses file handling (fwrite, fread)
Data stored in:
students.txt
Persistent storage (data saved after exit)
🔐 Security Features
Input validation to prevent invalid entries
Duplicate roll number prevention
Structured data handling
📸 Sample Output

---- School Management System ----

Add Student
Find by Roll Number
Find by First Name
Find by Course
Count Students
Delete Student
Update Student
Exit
⚠️ Limitations
Console-based UI only
Fixed size (MAX = 100)
No encryption for stored data
🔮 Future Improvements
🔐 Login Authentication System
📊 GUI Interface (C / Web)
🗄️ Database Integration (MySQL/SQLite)
🌐 Web-based version
📱 Mobile App integration
📜 License

Copyright (c) 2026 Mandapalle Uma Sri Krishna

All Rights Reserved.
