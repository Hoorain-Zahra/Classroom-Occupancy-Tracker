# Classroom-Occupancy-Tracker

 Project Description:
A C++ Object-Oriented Programming (OOP) project that simulates a classroom management system for educational institutions. The system allows administrators to manage classrooms, teachers, and students with various operations.

 Key Features:
Classroom Management: Add, view, and manage classrooms with capacity tracking

Personnel Management:
Add/assign teachers to classrooms
Enroll/remove students from classrooms
Search Functionality: Find students/teachers by ID
Transfer System: Move students between classrooms
Data Visualization: View occupancy status with percentage and visual indicators
Activity Logging: Automatic logging of all system activities

Technical Implementation:
OOP Concepts:
Inheritance (Person → Student/Teacher)
Polymorphism (virtual functions)
Encapsulation
Data Structures: Arrays for storing classrooms, students, and logs
Input Validation: Robust input handling for all user interactions


Menu Options:
Add Classroom: Create new classrooms with room numbers and capacities
Assign Teacher: Assign teachers to specific classrooms
Add Student: Enroll students in classrooms
Remove Student: Remove students from classrooms
Show All Classrooms: Display detailed information about all classrooms
Search Student: Find a student by ID
Search Teacher: Find a teacher by ID
Transfer Student: Move students between classrooms
Show Summary: View building-wide statistics
Save Data: Export current system data
Exit: Quit the program

 Data Persistence:
The system currently displays data in console-friendly format
Can be extended to save to files/databases

Limitations:
Uses fixed-size arrays (MAX_STUDENTS = 100, MAX_CLASSROOMS = 50)


Future Enhancements:
Implement file I/O for data persistence
Add GUI interface
Expand to multiple buildings
Add more search/sort capabilities
