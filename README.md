# School Result Management System

The **School Result Management System** is a Python-based application developed using Object-Oriented Programming (OOP) principles. It allows users to manage student academic records efficiently. With this system, users can add new student details, view all existing student records, and remove specific students based on their roll number. One of the core functionalities includes generating a comprehensive report card by entering subject-wise marks for each student.

The system calculates the total marks, percentage, and assigns a grade based on performance. The grading system is straightforward: students scoring 90% and above receive an A+, 80–89% receive an A, and it continues down to an F grade for scores below 40%. These calculations help in quickly assessing a student's academic standing.

All student details are stored in a CSV file named `students.csv`, and the subject-wise marks are saved in a separate `marks.csv` file. Once the report card is generated, the system saves it in both `.txt` and professionally formatted `.pdf` formats. The PDF report card is generated using the `reportlab` library, which ensures a clean and printable design.

This project demonstrates practical applications of Python file handling, CSV operations, and PDF generation. It's suitable for students, beginners, and educators who want a real-world Python project to manage and present academic records in a structured and automated manner.
