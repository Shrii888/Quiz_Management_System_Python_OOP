# Project 06: Quiz Management System Using Python OOP

## 📌 Project Overview

The Quiz Management System is a Python-based application developed using Object-Oriented Programming (OOP). It allows users to participate in multiple-choice quizzes, calculate scores automatically, and save quiz results for future reference.

The project uses JSON files to store questions and quiz records, ensuring that data remains available between sessions.

## 🎯 Project Objectives

- Develop a quiz application using Python OOP.
- Load quiz questions from a JSON file.
- Display multiple-choice questions and accept user answers.
- Calculate scores and percentages automatically.
- Save quiz results for future reference.
- Retrieve and display previous quiz attempts.

## ✨ Features

- **Question Management:** Store questions, answer options, and correct answers.
- **Persistent Storage:** Save and load questions using `questions.json`.
- **Interactive Quiz:** Display questions and accept user responses.
- **Automatic Scoring:** Calculate marks and percentage scores.
- **Result Management:** Save participant names, scores, percentages, and timestamps.
- **Quiz History:** View previously saved quiz attempts.
- **Input Validation:** Handle invalid answer choices during quiz participation.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- JSON
- Python built-in `json` and `datetime` modules

## 🧠 Python Concepts Applied

- Classes and Objects
- Constructors (`__init__`)
- Instance Attributes and Methods
- Functions and Parameters
- Lists and Dictionaries
- Loops and Conditional Statements
- Exception Handling
- File Handling
- JSON Serialization and Deserialization

## 🏗️ Project Structure

```text
Quiz_Management_System_Python_OOP/
│
├── Project_06_Quiz_Management_System.ipynb
├── questions.json
├── results.json
└── README.md
```

### File Descriptions

- **Project_06_Quiz_Management_System.ipynb:** Contains the Python code, class definitions, and project execution steps.
- **questions.json:** Stores quiz questions, options, and correct answers.
- **results.json:** Stores participant details, scores, percentages, and dates of quiz attempts.
- **README.md:** Provides an overview of the project, features, and instructions.

## ⚙️ How to Run the Project

1. Install Python and Jupyter Notebook.
2. Clone or download this repository.
3. Open `Project_06_Quiz_Management_System.ipynb` in Jupyter Notebook.
4. Run the notebook cells in order, starting with the imports and class definitions.
5. Load the saved questions and create a quiz object.
6. Answer the multiple-choice questions displayed by the program.
7. Save the quiz result using the `ResultManager` class.
8. View previous quiz attempts using the result history method.

Keep `questions.json` and `results.json` in the notebook's working directory so the application can access saved data.

## 💾 Data Storage

This project uses JSON files for persistent storage.

- `questions.json` stores the question bank.
- `results.json` stores quiz results and historical attempts.
- Existing result records are loaded before new records are added, helping preserve previous attempts.

The JSON files must remain available in the correct working directory for the application to retrieve saved information.

## 📚 Learning Outcomes

Through this project, I practised applying Python Object-Oriented Programming to a practical application. I also gained hands-on experience with file handling, JSON data storage, input validation, score calculation, and retrieving historical records.

## 🚀 Future Improvements

- Add quiz categories such as Python, SQL, Excel, and general knowledge.
- Introduce a timer for quiz completion.
- Allow users to select the number of questions.
- Display explanations for correct answers.
- Add options to edit or delete saved questions.
- Develop a graphical user interface.

## 👩‍💻 Author

**Shriya Verma **

Aspiring Data Analyst | Python | SQL | Excel | Power BI

## 📄 License

This project is intended for educational and portfolio purposes. A license file can be added to define the permissions for using, modifying, and distributing the project.
