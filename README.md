# PROG211 OOP Individual Assignment
## Project: Student Record System

### 1. Project overview
This is a beginner-friendly Python console program that stores and displays basic student records. It is an education-domain example for demonstrating Object-Oriented Programming (OOP).

### 2. Features
- Add a student record.
- Display all student records.
- Search for a student by ID.
- Display the number of Student objects created.
- Prevent duplicate student IDs.

### 3. OOP concepts demonstrated
- **Class:** `Student` is the blueprint for student records.
- **Objects:** Each `Student(...)` call creates a student object.
- **Attributes:** `student_id`, `name`, and `programme` store each student's data.
- **Instance method:** `display_info()` displays one object's details.
- **Class method:** `display_student_count()` uses `@classmethod` to display the number of Student objects created.
- **Data structure:** A list named `students` stores multiple Student objects.
- **Functions:** `add_student()`, `display_students()`, `find_student()`, and `main()` organize the program into reusable parts.

### 4. How to run
1. Install Python 3 if it is not already installed.
2. Save `student_record_system.py` to your computer.
3. Open a terminal or command prompt in that folder.
4. Run: `python student_record_system.py`
5. Follow the menu displayed on screen.

### 5. Example input/output
Example menu:
```text
===== STUDENT RECORD SYSTEM =====
1. Add student
2. Display all students
3. Find student by ID
4. Display number of student objects created
5. Exit
Choose an option (1-5): 2
```

Example records:
```text
--- Student Records ---
Student ID: ICT001
Name: John Kamara
Programme: Information Communication Technology
School: Limkokwing University of Creative Technology
------------------------------
Student ID: ICT002
Name: Mary Sesay
Programme: Information Communication Technology
School: Limkokwing University of Creative Technology
------------------------------
```

### 6. Digital Public Goods (DPG) alignment
- **Open-source:** The code can be published in a GitHub repository for others to inspect and reuse.
- **Inclusive and accessible:** It uses a simple text menu and does not require a graphical interface.
- **Privacy-respecting:** The sample does not ask for sensitive personal information. Records are held in memory and are not saved to a database or external service.
- **Modular and reusable:** The program separates adding, displaying, searching, and counting into methods and functions.

### 7. Limitations and possible improvements
The program stores records only while it is running. Closing it clears records added during that session. Future versions could use file storage, stronger input validation, and user authentication, provided privacy and security are considered.

### 8. Submission checklist
- [ ] Read and understand the source code.
- [ ] Run the program and test each menu option.
- [ ] Take screenshots of the running program for the hardcopy.
- [ ] Upload the `.py` file and this README to your GitHub repository.
- [ ] Add your lecturer as a collaborator, as instructed in the assignment brief.
- [ ] Print the required hardcopy and screenshots.
- [ ] Follow your lecturer's formatting instructions: Tahoma, 10-point font, 1.15 line spacing, justified alignment.

### 9. Academic note
Use this project as a learning draft. Read the code, test it yourself, and make sure you can explain each class, method, and data structure before submitting it. Follow your university's academic-integrity rules.
