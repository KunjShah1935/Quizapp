# QuizIQ 🎯

QuizIQ is a full-stack quiz management application that allows teachers to create quizzes and students to attempt them through a clean, interactive web interface. The platform provides secure user authentication, quiz creation, question management, and response tracking with persistent storage.

The system is designed with a modular backend and a structured frontend, making it scalable and easy to maintain.

---

## Live Demo

https://quiziq-mxd5.onrender.com/

---

## Features

* User registration and login
* Separate interfaces for teachers and students
* Create, manage, and attempt quizzes
* Add and organize questions
* Store and retrieve responses
* Persistent data storage
* Responsive and structured frontend
* Cloud deployment ready

---

## Tech Stack

Frontend
HTML, CSS, JavaScript

Backend
Node.js, Express.js

Database
SQLite

Deployment
Render

---

## Project Structure

```id="k5prfi"
quizapp-main
│
├── backend
│   ├── routes
│   ├── middleware
│   ├── data
│   ├── index.js
│   └── package.json
│
├── frontend
│   ├── assets
│   ├── css
│   ├── js
│   ├── student
│   ├── teacher
│   ├── index.html
│   ├── login.html
│   └── signup.html
│
└── README.md
```

---

## Installation and Setup

Clone the repository

```id="j72r2u"
git clone https://github.com/yourusername/quiziq.git
```

Navigate to backend

```id="c0fpfr"
cd backend
```

Install dependencies

```id="hrsg67"
npm install
```

Run the server

```id="jz9ckf"
node index.js
```

The application will run on

```id="93y96n"
http://localhost:4000
```

---

## Application Modules

Teacher Module
Create quizzes
Add questions
Manage quizzes

Student Module
Login and attempt quizzes
Submit responses

Authentication
User registration
User login

---

## Deployment

The application is deployed using Render.

---

## Author

Kunj Shah

GitHub
https://github.com/yourusername

---

## Future Improvements

Leaderboard system
Timer-based quizzes
Analytics dashboard
Enhanced UI

---

## Support

If you found this project useful, please consider giving it a star on GitHub.

---
