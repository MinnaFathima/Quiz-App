# 🧠 Quiz-App
A Java Swing-based quiz app with timer, scoring, and admin question control with real-time results and MySQL backend



A modern, interactive Quiz Application built with **Java Swing GUI** and powered by **MySQL Database**. This application supports both **Student** and **Admin** views – allowing users to take timed quizzes and administrators to manage questions.

---

## ✨ Features

### 🎓 For Students
- 🔐 Secure login & registration
- ⏱️ Timed quiz sessions (with auto-transition on timeout)
- 🧮 Live score tracking
- ❓ Randomized multiple-choice questions
- 📊 Result summary on completion

### 🛠️ For Admins
- ➕ Add new quiz questions
- 🔄 Option randomizer for every quiz session
- 🔒 Secure admin access

---

## 🖼️ UI Screenshots

| Start Screen | Quiz Window | Result Page |
|--------------|-------------|-------------|
| ![start](assets/start.png) | ![quiz](assets/quiz.png) | ![result](assets/result.png) |

> 📁 Add screenshots in `assets/` folder to match these.

---

## 🛠️ Tech Stack

- **Java Swing** – GUI Components  
- **MySQL** – Database for storing questions and results  
- **JDBC** – Java-MySQL database connectivity  
- **NetBeans** – Recommended IDE (form builder supported)

---

## 🧩 Project Structure

```plaintext
📦 src/
├── Start/
│   └── StartFrame.java            # Entry point of the app
├── App/
│   ├── Quiz_Login.java            # Student login screen
│   ├── Quiz_Reg_Form.java         # Student registration
│   ├── Quiz_Menu.java             # Quiz topic selection
│   ├── Quiz_Time.java             # Core quiz logic
│   ├── Quiz_Result.java           # Final score window
│   └── Details.java               # Shared variables (score, question count)
├── Banckend/
│   └── Add_Question.java          # Admin question input GUI
└── mysql.txt                      # SQL dump file (table schema & sample data)
