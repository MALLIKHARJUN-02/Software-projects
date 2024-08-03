# Student Database Management System

Project Overview:
The Student Database Management System is a console-based application written in C++. It allows users to manage student records, including creating new records, 
accessing and updating existing records, and deleting records. The system can also display all student records and calculate their CGPA (Cumulative Grade Point Average) and percentage.

 Features
 
•	Create Database: Add new student records to the database.

•	Access by Name: Retrieve student records using the student's first name.

•	Access by Roll Number: Retrieve student records using the student's roll number.

•	Access by Course ID: Retrieve student records using the student's course ID.

•	Number of Students: Display the total number of students in the database.

•	Update Student Database: Update existing student records.

•	Delete Student Database: Delete student records from the database.

•	Display All Students: Display all student records in the database.

 Getting Started

 Prerequisites

Basic knowledge of C++ and file handling

 Usage

When you run the program, you will see a menu with various options. Enter the corresponding number to select an option:

1. Create database

2. Access With name of the student

3. Access With roll number

4. Access with Course ID

5. Find number of students

6. Update student database

7. Delete student database

8. Display all Students

9. Exit

 Code Structure

The main code structure includes several functions for managing student records:

create_database: Creates a new student record.

access_name: Accesses student records by name.

access_roll_number: Accesses student records by roll number.

access_course_id: Accesses student records by course ID.

number_of_students: Displays the total number of students.

update: Updates existing student records.

delete_student: Deletes student records.

display_all_students: Displays all student records.

 Validation

The program includes basic validation for string and numeric inputs:

validateString: Ensures that input strings contain only alphanumeric characters and spaces.

validateNumeric: Ensures that input strings contain only digits and a single decimal point (optional).

File Handling

Student records are stored in a text file named `Student_Database_Management.txt`. The file is updated whenever a new record is created. 

Here is an example of how to use the program:

1. Select option `1` to create a new student record.

2. Enter the student's first name, last name, roll number, SGPA for up to 8 semesters, and course IDs for up to 5 courses.

3. The student record will be saved to the file and added to the list of students in memory.

 Acknowledgments

This project was created as a learning exercise in C++ programming and file handling. 

