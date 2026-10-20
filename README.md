# digital-exam-result-management-system
A Pathon -based system for managing student examination records and results
Digital Exam and Results Management System
 1. Project Overview
The Digital Exam and Results Management System is a Python-based educational project designed to demonstrate how Object-Oriented Programming (OOP) can be used to organise student examination records.
The system allows students and examinations to be represented as objects, records marks, calculates grades, updates results, validates marks, and displays examination results.
This project is a learning prototype, not a complete production system. All example student records are fictional.

2. Problem Statement
Managing examination records manually can make it difficult to locate student results, update marks, and identify invalid entries. This project demonstrates a simple computerised approach to organising student and examination information.
The system helps demonstrate how student records can be registered, examinations can be added, marks can be recorded and updated, and results can be displayed in an organised format.


 3. Project Objectives
- To apply OOP concepts to an education-related problem.
- To create classes for students, examinations, and results management.
- To record, validate, update, and display examination results.
- To calculate grades using defined example boundaries.
- To prevent duplicate student and examination IDs.
- To demonstrate object interaction and Python lists.
- To consider Digital Public Goods (DPG) principles.

 4. Main Features
- Register student records.
- Add examination records.
- Prevent duplicate student and examination IDs.
- Record examination marks.
- Validate marks within the permitted range.
- Calculate grades.
- Update student information and examination results.
- Display student details and examination results.
 The grade boundaries used in this educational project are illustrative and are not an official institutional or WAEC grading scale.


5. Object-Oriented Programming Concepts
Classes
The project uses three main classes:

- `Student` — represents a student.
- `Exam` — represents an examination.
- `ResultsManagementSystem` — manages student records, examinations, and results.

Objects
Objects are created from the classes to represent individual students, examinations, and the management system.

 Attributes
Attributes store information such as student ID, name, course, examination ID, subject, maximum mark, and results.

 Instance Methods
Instance methods perform actions on objects, including displaying student details, validating marks, calculating grades, and updating records.

Class Method
The `change_school_name()` class method changes class-level school information.

Static Method
The `valid_student_id()` static method checks whether a student ID follows the required example format.

 Lists and Object Interaction
Python lists store multiple student and examination objects. The management system connects students with examinations when recording results.


 6. Requirements
- Python 3
- No additional third-party Python packages are required.

7. How to Run the Program
1. Download or clone this GitHub repository.
2. Open a terminal or command prompt in the project folder.
3. Run the following command:

   `python digital_exam_results.py`

   If your computer uses Python 3 through the `python3` command, run:

   `python3 digital_exam_results.py`

4. Review the displayed student records, examination results, updated mark, and invalid-mark test.

8. Sample Input and Output
The program uses fictional test records defined in the source code. The file `sample_input_output.txt` contains the sample test data and the actual output from running the program.


 9. Digital Public Goods (DPG) Alignment
 Open-Source
The source code can be published in a public GitHub repository so that other students and developers can inspect, study, reuse, and adapt it.
To support this principle, the repository should include an appropriate open-source licence, with its complete text saved in a file named `LICENSE`.

 
 Inclusive and Accessible Design
The program uses a straightforward text interface, clear labels, and understandable messages. It runs with Python 3 and does not require specialist hardware or paid software.
These choices support basic accessibility and ease of use. Formal accessibility testing has not been conducted.


 Privacy-Respecting
The project uses fictional student names and IDs. It does not request sensitive personal information.
Records are stored in memory and disappear when the program closes. A real examination system would require appropriate access controls and data-protection measures.


Modular and Reusable
The project separates student information, examination information, and management operations into different classes.
This structure makes the code easier to understand, maintain, test, and extend. Future developers could add database storage, user roles, or additional reporting features.


  10. Limitations and Future Improvements
The current version is a command-line demonstration. It does not provide permanent database storage, user authentication, a graphical interface, or official transcript generation.

Future improvements could include:
- Permanent file or database storage.
- Authorised user roles.
- A graphical user interface.
- Printable examination reports.
- Additional input validation.
- Configurable, institution-approved grading boundaries.

Conclusion
The Digital Exam and Results Management System demonstrates how Python OOP can be applied to an education-related problem. It uses classes, objects, attributes, methods, lists, and object interaction to organise student examination records.
The project also demonstrates basic validation and considers open-source sharing, accessible design, privacy, and modularity in line with the DPG principles discussed in this assignment.
