# python-quiz-app
A Python Quiz Application built with Flask and SQLite featuring interactive MCQs, score calculation, persistent leaderboard, REST APIs, logging, and automated tests
# 🧠 Python Quiz App

A portfolio-ready **Quiz Application built with Python, Flask, and SQLite**. It provides an interactive multiple-choice quiz, automatic score calculation, persistent leaderboard, REST API endpoints, logging, and automated tests.

## ✨ Features

- 🎯 Interactive multiple-choice quiz
- 📊 Automatic score calculation
- 🏆 Persistent leaderboard using SQLite
- 🔌 REST API endpoints
- 🧩 Modular Flask application structure
- 🛡️ Input validation and exception handling
- 📝 Application logging
- 🧪 Automated tests with Pytest
- 📱 Responsive web interface

## 🛠️ Tech Stack

- **Language:** Python
- **Backend:** Flask
- **Database:** SQLite
- **Frontend:** HTML, CSS, JavaScript
- **Testing:** Pytest
- **API:** REST

## 📂 Project Structure

```text
python-quiz-app/
├── quiz_app/
│   ├── __init__.py
│   ├── db.py
│   ├── routes.py
│   └── templates/
│       └── index.html
├── tests/
│   └── test_app.py
├── requirements.txt
├── run.py
├── .gitignore
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/python-quiz-app.git
cd python-quiz-app
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Run the application

```bash
python run.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## 🔌 API Endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| GET | `/api/questions` | Retrieve quiz questions |
| POST | `/api/submit` | Submit answers and calculate score |
| GET | `/api/leaderboard` | Retrieve leaderboard |

## 🗄️ Database Schema

**Questions**
- Question ID
- Question text
- Answer options
- Correct answer

**Quiz Attempts**
- Attempt ID
- Player name
- Score
- Total questions
- Timestamp

## 🧪 Run Tests

```bash
python -m pytest -q
```

## 🎓 Learning Outcomes

- Building modular Python applications
- Developing web applications using Flask
- Designing and interacting with a SQLite database
- Creating REST APIs
- Handling errors and validating input
- Writing automated tests with Pytest
- Documenting and preparing projects for GitHub

## 🚀 Future Improvements

- User authentication
- Quiz categories and difficulty levels
- Timer-based quizzes
- Randomized questions
- Docker deployment
- Cloud hosting and a live demo

## 👨‍💻 Author

**Kamal Dhaka**  
B.Tech — Artificial Intelligence & Data Science  
Interested in Python, AI, Data Science, and Cybersecurity.

## 📄 License

This project is available for learning and educational purposes under the MIT License, if you choose to add an MIT license file.

---

⭐ If you find this project useful, consider starring the repository!
