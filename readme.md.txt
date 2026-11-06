Student Information Management System A robust, menu-driven command-line application developed in C as part of an incremental software engineering project.
SIMS allows users to manage student profiles, record course grades, evaluate academic standing, track cumulative session statistics, and persist records to file storage.
Features: 
Student Profile Management: Add and validate student records, including unique Student IDs, full names, and GPAs (ranging from 0.00 to 4.00).
Grade Tracking & Analytics: Input up to 5 course grades with range validation (0–100) and automatically calculate grade statistics (Average, Highest, and Lowest grades).
Automated Academic Standing: Dynamically classifies students into categories based on GPA:Honors: $\ge 3.50$Good Standing: $\ge 2.00$Academic Probation: $\ge 1.00$Academic Suspension: $< 1.00$
Session Statistics: Tracks and displays aggregate runtime data, including total students entered, cumulative average GPA, and total honor students count.
File Persistence: Saves complete student profiles and grade reports directly to student_records.txt.Input 
Validation & Error Handling: Employs safe input buffering via fgets and sscanf to gracefully handle empty inputs, malformed strings, and out-of-range values without crashing.
Menu Options
Add Student – Input and validate student credentials and GPA.
Display Student – View the complete student summary and grade breakdown.
Enter Grades – Record 5 individual course grades.
Save Student Record – Export current record details to a local text file (student_records.txt).Exit – 
Terminate the application safely.
Display Statistics – View real-time aggregate metrics for all students entered during the session.
Technical Stack:
Language: C (Standard C99 / C11)
Concepts Demonstrated:Modular functions and control flow loops
One-dimensional arrays and string manipulation (string.h)
File input/output operations (stdio.h)
Variable scope management (Local vs. Global state variables)
Robust input sanitization and error checking
