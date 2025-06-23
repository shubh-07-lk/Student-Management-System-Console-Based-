# 🎓 Console-Based Student Management System (Java)

This is a **console-based Student Management System** built in **Java**. It allows users to perform basic operations related to student records such as adding, updating, deleting, and viewing student information.

## 🛠️ Features

- Add new student
- View all students
- Search student by ID
- Update student details
- Delete student record
- Exit the program safely

## 🧰 Technologies Used

- Java (JDK 8 or later)
- Java Collections (ArrayList)
- Console I/O

> 📌 No external libraries or database are used. All data is stored temporarily in memory.

## 📂 Project Structure

StudentManagementSystem/
├── Student.java # Model class representing a student
├── StudentService.java # Contains logic for CRUD operations
├── StudentManagementApp.java # Main class with menu and user interaction
└── README.md # Project documentation


## 🚀 How to Run

### Prerequisites:
- Java installed on your system (JDK 8+)

### Steps:
1. Clone the repository or download the source code.
2. Open terminal/command prompt.
3. Navigate to the project directory.
4. Compile the Java files:
   ```bash
   javac *.java
5.Run  the main application
java StudentManagementApp

========= Student Management System =========
1. Add Student
2. View All Students
3. Search Student by ID
4. Update Student
5. Delete Student
6. Exit
Enter your choice:


👨‍🎓 Sample Student Fields
Student ID (int)

Name (String)

Age (int)

Grade (String)

📌 Limitations
Data is not persistent. All student records are lost when the application is closed.

No support for file or database storage (can be added later).

📈 Future Enhancements
Store data in a file or database (e.g., MySQL, SQLite)

Add GUI using Java Swing or JavaFX

Implement user authentication

Validate inputs
