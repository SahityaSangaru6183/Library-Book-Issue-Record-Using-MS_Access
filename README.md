📚 Library Management System (Microsoft Access Project)
🔍 Overview
This project is a Library Management System built using Microsoft Access. It is designed to streamline the process of managing books, students, and issue/return records in a small to medium-sized library setting.

🎯 Features
Add, update, and delete book records

Manage student/member details

Track book issues and returns

Automatic fine calculation (if applicable)

Generate reports for inventory, issued books, and late returns

Simple and user-friendly form-based interface

🧱 Tables (Entities)
Here are the core tables included in the database:

Books: Contains information like BookID, Title, Author, Genre, Publisher, and Availability

Students / Members: Tracks StudentID, Name, Class, Contact Info

IssueRecords: Logs which student has borrowed which book, including IssueDate and DueDate

Returns (optional): Manages return status and late return penalties

Users (optional): Admin login system (if included)

📄 Forms
The system includes multiple forms for ease of use:

Book Entry Form

Student Registration Form

Issue Book Form

Return Book Form

Search or Filter Forms

📊 Reports
List of currently issued books

Overdue books with fines

Book inventory reports

Student borrowing history

⚙️ Technologies Used
Microsoft Access .accdb

Access Queries (SQL)

Macros (if any)

Visual Basic for Applications (VBA) for form logic (if included)

📝 How to Use
Open the .accdb file using Microsoft Access (2016 or later recommended)

Navigate through the switchboard or main menu

Use the forms for data entry and queries for analysis

Generate reports using the built-in report section

💡 Use Case
Perfect for:

School or college libraries

Personal or community book management

Project submissions for students learning databases

📥 Future Enhancements
Add barcode scanning for books and students

Add multi-user login with roles (Admin, Librarian, etc.)

Export reports to PDF

Add email reminders for due books
