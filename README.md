README.md 

Student Enrollment Form project using HTML, Bootstrap, JavaScript, and JsonPowerDB:
📘 Student Enrollment Form
This project is a dynamic web-based Student Enrollment Form built using HTML, Bootstrap, JavaScript, and integrated with JsonPowerDB as the backend database. It allows users to add, update, search, and reset student data efficiently through a simple and responsive interface.

🚀 Features
📝 Add new student records with details like Roll No, Full Name, Class, Date of Birth, Address, and Enrollment Date.

🔍 Retrieve student data by Roll Number.

🔄 Update existing student details.

♻️ Reset the form with one click.

✅ Input validation and user-friendly error handling.

🎯 Fully responsive using Bootstrap 5.

⚙️ JsonPowerDB integration for fast, serverless data operations.

🧰 Technologies Used
HTML5

Bootstrap 5.1.1

JavaScript (ES5/ES6)

jQuery

JsonPowerDB (REST API)

🧩 JsonPowerDB Configuration
The project uses a predefined API token and database configuration:
Token NO. 0000000000000000000000
Database: SCHOOL-DB

Relation/Table: STUDENT-TABLE

Base API URL: http://api.login2explore.com:5577

⚠️ Ensure these details are valid for your JsonPowerDB environment before use.

📋 Form Fields
Roll Number (Roll_No)

Full Name (Full_Name)

Class

Date of Birth

Address

Enrollment Date

🧠 Functional Overview
findRoll()
Checks if the student with the given roll number exists in the database.

If yes → Fills the form with existing data and enables the Update button.

If not → Enables the form fields for a new entry.

saveData()
Saves new student data to the database using the PUT command.

updateData()
Updates existing student information using the SET command (with Roll_No as the primary key).

disableAll() / resetForm()
Resets and disables the form fields for better user flow and input control.

💡 How to Run
Clone/download the repository.

Open index.html in a browser.

Start entering data and interacting with the form.

All operations (save/update/fetch) work live with JsonPowerDB.

📂 Project Structure
bash
Copy
Edit
├── index.html         # Main HTML form
├── style.css          # Custom styles (optional)
├── script.js          # All logic for database interactions and validation
🧪 Sample Roll Number Actions
Enter a Roll Number and wait for autofill (if exists).

New roll → form enables for new entry.

Existing roll → form fills and enables update.

🙋‍♂️ Author
Shubham Meena
Fresher Web Developer | MERN Stack Enthusiast
Passionate about building real-world apps using modern technologies.
Portfolio -> https://shubhammeena.netlify.app/

📜 License
This project is given by Login2Explore .

