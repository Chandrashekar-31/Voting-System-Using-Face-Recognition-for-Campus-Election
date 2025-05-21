# 🎓 Voting System Using Face Recognition for Campus Election

A secure and user-friendly **Campus Election Voting System** that uses **Face Recognition** for authentication, developed using **Flask (Python)** as the backend, **SQLite** for database management, and **HTML/CSS/JavaScript** for the frontend.

## 📌 Project Description

This web application ensures a fair and transparent election process in college campuses by allowing students to vote using **facial recognition**. It restricts multiple voting attempts and provides a real-time result tally for admins.

---

## ✅ Features

* 🔐 **Facial Recognition Login**
  Authenticates students using a live webcam feed before allowing them to vote.

* 🧑‍🎓 **Student Registration**
  Admin can register new voters by capturing their face data.

* 🗳️ **Vote Casting Interface**
  Verified students can vote for their desired candidate.

* 📊 **Admin Dashboard**
  Manage candidates, view voting statistics, and oversee the election.

* 📀 **SQLite Database**
  Lightweight and easy-to-manage local database for storing user, vote, and candidate data.

---

## 💻 Tech Stack

| Layer     | Technology                |
| --------- | ------------------------- |
| Frontend  | HTML, CSS, JavaScript     |
| Backend   | Python (Flask)            |
| Face Auth | OpenCV, face\_recognition |
| Database  | SQLite                    |
| Hosting   | Localhost via Flask       |




## 🚀 Installation & Usage

### Prerequisites

* Python 3.x
* pip

### 1. Clone the Repository

```bash
git clone https://github.com/Chandrashekar-31/Voting-System-Using-Face-Recognition-for-Campus-Election.git
cd Voting-System-Using-Face-Recognition-for-Campus-Election
```

### 2. Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Application

```bash
python app1.py
```

Then open your browser and go to:
[http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🎯 Workflow

1. **Student Registration**

   * Admin captures student face and stores it.
   * Face encodings are generated.

2. **Voting**

   * Student logs in via face recognition.
   * After verification, they can vote.

3. **Admin**

   * Add/view candidates.
   * View live voting results.

---

## 🛡️ Security

* Prevents multiple votes by the same student using facial uniqueness.
* Face encodings are stored securely.
* Admin access is restricted.

--
