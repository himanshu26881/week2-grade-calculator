Week 2 Internship Project – Python (Control Flow & Data Structures)

This project is a Python-based Grade Calculator that collects student marks, calculates averages, assigns grades, and generates class statistics. It follows the Week-2 task requirements from your internship.

📌 Project Overview

The program performs the following:

Takes input for multiple students

Accepts marks for 3 subjects (Math, Science, English)

Calculates average percentage

Assigns grade (A, B, C, D, F)

Provides feedback/comments

Displays results in a formatted table

Shows class statistics (highest, lowest, average)

Provides a search feature

Allows saving results to a file

🎯 Objectives

Practice Python decision-making (if/elif/else)

Learn loops (for, while)

Use functions for modular code

Implement lists and dictionaries

Handle user input errors

Create meaningful console output

Add optional features (search, save results, menu system)

🛠️ Setup & Installation

Install Python (3.x recommended) from: https://www.python.org

Create a folder named week2

Add the file: grade_calculator.py

Run the program in terminal:

python grade_calculator.py


Follow the on-screen instructions.

📂 Code Structure
grade_calculator.py
│
├── calculate_grade()        # Determines grade + comment
├── get_valid_number()       # Validates input for marks
├── get_positive_int()       # Ensures user enters positive count
├── enter_student_data()     # Collects names & marks
├── display_results()        # Shows formatted table of results
├── search_student()         # Searches for student by name
├── save_to_file()           # Saves results to text file
├── menu()                   # Displays menu options
└── main()                   # Runs overall program

🧪 Features Implemented
✔ Input Validation

Names cannot be empty

Marks must be between 0–100

Student count must be a positive number

✔ Grading System
Average Marks	Grade	Comment
90–100	A	Excellent!
80–89	B	Very Good
70–79	C	Good
60–69	D	Needs Improvement
Below 60	F	Failed
✔ Class Statistics

Class average

Highest scorer

Lowest scorer

✔ Additional Features

Search student by name

Save results to grade_results.txt

Clean formatted console output

📄 How to Use

Enter number of students

Enter each student’s name

Enter marks for 3 subjects

View:

Individual averages

Grades

Comments

Statistics

Use menu options to:

Show results again

Search a student

Save to file

Exit program

🧑‍💻 Developer

Himanshu Kumar
Python Developer Intern – Week 2 Project
Arka Jain University
