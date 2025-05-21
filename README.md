

# 🎓 Voting System Using Face Recognition for Campus Election

A secure and user-friendly **Campus Election Voting System** that uses **Face Recognition** for authentication, developed using **Flask (Python)** as the backend, **SQLite** for database management, and **HTML/CSS/JavaScript** for the frontend.

## 📌 Project Description

This web application ensures a fair and transparent election process in college campuses by allowing students to vote using **facial recognition**. It restricts multiple voting attempts and provides a real-time result tally for admins.

---

## ✅ Features

- 🔐 **Facial Recognition Login**  
  Authenticates students using live webcam feed before allowing to vote.

- 🧑‍🎓 **Student Registration**  
  Admin can register new voters by capturing their face data and storing it.

- 🗳️ **Vote Casting Interface**  
  Verified students can select and vote for their desired candidate.

- 📊 **Admin Dashboard**  
  Manage candidates, view voting stats, and monitor election integrity.

- 💾 **SQLite Database**  
  Lightweight and easy-to-manage local database for storing user, vote, and candidate data.

---

## 💻 Tech Stack

| Layer      | Technology           |
|------------|----------------------|
| Frontend   | HTML, CSS, JavaScript |
| Backend    | Python (Flask)       |
| Face Auth  | OpenCV, face_recognition |
| Database   | SQLite               |
| Hosting    | Localhost via Flask  |

Install Required Packages
pip install -r requirements.txt
