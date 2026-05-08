# ULMS-SDT621-Aneesah_20240150
ULMS (Umoja Learning Management System)
Project Overview

The ULMS (Umoja Learning Management System) is a Windows Forms application developed in C#. It is designed to manage core academic processes such as student registration, login authentication, course enrollment, marks capture, and report generation.

This project was developed as part of a Software Design and Testing module (SDT621), focusing on software testing, debugging, and quality assurance practices.

Features
Student Login Authentication
Student Registration
Course Enrollment System
Marks Capture and Average Calculation
Report Generation Module
Input Validation and Error Handling
Technologies Used
C# (.NET Framework / Windows Forms)
Visual Studio
Object-Oriented Programming (OOP) principles
Manual Software Testing techniques
Testing Overview

The system was tested using structured functional and non-functional testing approaches.

Functional Testing
Login validation (correct/incorrect credentials)
Course enrollment validation
Marks input and calculation
Report generation accuracy
Non-Functional Testing
Performance testing (report generation speed)
Usability testing (navigation and UI clarity)
Security testing (invalid login attempts)
Reliability testing (repeated operations stability)
Known Issues (Before Fixes)
Incorrect login validation logic
System crash on invalid marks input
Incorrect average calculation
Duplicate course enrollment allowed
Report generation freeze issue
Fixes Implemented
Improved login authentication logic
Added input validation using TryParse
Corrected average calculation formula
Prevented duplicate course enrollment
Removed performance delays in report generation
Improved error handling and user feedback
Test Results Summary

After debugging and testing:

All core functions operate correctly
System handles invalid inputs safely
Reports generate successfully without freezing
Data validation and calculations are accurate
How to Run the Project
Clone the repository:
git clone https://github.com/your-username/ULMS.git
Open the solution file in Visual Studio
Build the project
Run the application (Start Debugging)
Future Improvements
Database integration (SQL Server)
Password encryption for security
Improved UI design
Role-based access (Admin / Student / Lecturer)
Cloud-based deployment
Developer

Developed as part of SDT621 Software Design and Testing module
