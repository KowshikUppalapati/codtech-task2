**NAME**: UPPALAPATI KOWHIK
**COMPANY**:CODTECH IT SOLUTIONS
**DOMAIN NAME**:PYTHON PROGRAMMING
**DURATION**:30 NOV 2024 TO 15 JAN 2025
**ID**:CT6WDS23

### **Overview of the Code**

**PROJECT NAME**:SIMPLE CALCULATIOR

### **Objective**

The objective of this program is to create a **Student Grade Manager** that allows users to:  
1. Add grades for various subjects.  
2. Calculate and display average grades, corresponding letter grades, and GPA for each subject.  
3. Provide a simple and interactive system to manage and view student performance.


### **Overview**

The program is a command-line tool for managing student grades. Users can:  
- Add grades to specific subjects.  
- View all grades, their averages, letter grades, and GPA.  
- Exit the program when done.  

The system utilizes a **dictionary-based structure** to store grades for multiple subjects and provides real-time calculations for average grades, letter grades, and GPA.



### **Key Points**

1. **Grade Management**:
   - Grades for each subject are stored in a dictionary, where the key is the subject name and the value is a list of grades.

2. **Adding Grades**:
   - Grades can be added interactively by specifying the subject and the grade.

3. **Average Grade Calculation**:
   - The program calculates the average of all grades for a given subject.

4. **Grade Display**:
   - Displays:
     - The list of grades for each subject.
     - The calculated average.
     - Corresponding letter grade (`A` to `F`) based on predefined criteria.
     - GPA (Grade Point Average), where `A = 4.0`, `B = 3.0`, etc.

5. **Letter Grade and GPA**:
   - Uses helper methods (`get_letter_grade` and `get_gpa`) to determine the letter grade and GPA based on the average grade.

6. **User Interaction**:
   - Menu-driven interface with options to add grades, view grades, or exit.

7. **Error Handling**:
   - Handles invalid menu inputs gracefully with a retry mechanism.



### **Technologies and Concepts Used**

1. **Python Programming**:
   - The program is implemented entirely in Python.

2. **Object-Oriented Programming (OOP)**:
   - **Class**: `StudentGradeManager` encapsulates grade-related logic.
   - **Methods**: Used for operations like adding grades, calculating averages, and displaying grades.

3. **Data Structures**:
   - **Dictionary**: Stores grades for each subject, allowing efficient access and updates.

4. **Mathematical Operations**:
   - Used for calculating averages and mapping grades to GPA.

5. **Control Structures**:
   - **Loops**: For continuous user interaction.
   - **Conditional Statements**: To handle menu choices and grade classifications.

6. **Input/Output**:
   - Interactive input for adding grades and menu selection.
   - Formatted output for displaying grades, averages, and GPA.

