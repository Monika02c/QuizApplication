# QuizApplication
 Java-based Quiz Application with a Swing GUI and MySQL database integration.
This project allows users to take quizzes, store scores, and manage questions using JDBC connectivity.

📌 Features
✅ User-friendly Swing GUI

✅ Connects to MySQL database for storing questions and results

✅ Multiple-choice questions (MCQs) support

✅ Timer for each quiz session (optional)

✅ Displays score after completion

✅ Easy to add, update, or delete questions

🛠️ Tech Stack
Programming Language: Java

GUI Framework: Java Swing & AWT

Database: MySQL

Connectivity: JDBC

IDE Used:  IntelliJ IDEA 


📂 Project Structure
QuizApplication/
│-- src/
│   ├── com.quiz.main        # Main class and launcher
│   ├── com.quiz.gui         # GUI classes (Swing)
│   ├── com.quiz.database    # JDBC & Database handling
│-- resources/
│   └── quiz.sql             # MySQL database script
│-- README.md
⚙️ Setup Instructions
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/QuizApplication.git
2️⃣ Setup Database
Open MySQL and create a new database:


CREATE DATABASE quiz_app;
USE quiz_app;
Import the quiz.sql file from the resources folder to create tables and insert sample questions.

3️⃣ Configure Database in Project
Update your JDBC URL, username, and password in the database connection class:

String url = "jdbc:mysql://localhost:3306/quiz_app";
String user = "root";
String password = "your_password";

4️⃣ Run the Application
Open project in your IDE
Compile and run the Main.java file

