Quiz Application

This is a web-based quiz application logic and UI built using Java SpringBoot mySQL database and reactJs. It allows users (teachers) to make quizzes, edit them and delete them and also for normal users to take the quizes and be marked.

Full Stack Quiz Application 📌 Project Overview

This is a Full Stack Interactive Quiz Application built with:

Frontend: React

Backend: Spring Boot

Database: MySQL

The app allows users to take quizzes, view scores, and review answers. An admin panel is provided to add/manage questions.

🚀 Features

User authentication (login/register).

Take quizzes with multiple-choice questions.

Automatic score calculation.

View quiz history and results.

Admin panel to add, edit, and delete quiz questions.

Secure API with Spring Boot & JWT authentication.

🛠️ Tech Stack

Frontend: React, Axios, Bootstrap/TailwindCSS

Backend: Spring Boot, Spring Security, JPA/Hibernate

Database: MySQL

Version Control: Git, GitHub

🗄️ Database Schema

Users Table: (id, username, password, role)

Questions Table: (id, question_text, options, correct_answer)

Results Table: (id, user_id, quiz_id, score, date)

⚙️ Installation & Setup 1️⃣ Clone Repository git clone https://github.com//quiz-app.git cd quiz-app

2️⃣ Backend Setup (Spring Boot)

Import project into IntelliJ/Eclipse.

Configure application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/quiz_app spring.datasource.username=root spring.datasource.password=yourpassword spring.jpa.hibernate.ddl-auto=update spring.jpa.show-sql=true

Run the Spring Boot application.

3️⃣ Frontend Setup (React) cd frontend npm install npm start

🔗 API Endpoints

POST /api/auth/login → Login user

POST /api/auth/register → Register user

GET /api/quiz/questions → Fetch quiz questions

POST /api/quiz/submit → Submit answers & get score

POST /api/admin/question → Add new question (Admin only)

🧪 Testing

Use Postman to test backend APIs.

Run npm test in React for frontend testing.

📦 Deployment

Backend: Deploy on AWS / Heroku.

Frontend: Deploy on Netlify / Vercel.

Database: Host MySQL on AWS RDS / Railway.

👨‍💻 Author

Your Name : B.V.Adilakshmi

Email:adilakshmibijjam94@gmail.com
