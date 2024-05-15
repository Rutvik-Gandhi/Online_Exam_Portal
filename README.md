# Online_Exam_Portal

📔 Table of Contents
About the Project
Tech Stack
Features
Environment Variables
Getting Started
Prerequisites
Run Locally
Run with Docker
To-do
Contributing
License
Contact
Acknowledgements
🌟 About the Project
Web Application for online MCQ test usecase

👾 Tech Stack
Frontend
Backend
Database
🎯 Features
Student User
View Tests Details
Register for test
Give Test
Check Result and correct answer and explanation for questions
Teacher User
Create, Update Questions and Question Banks
Create, View Test
Admin User
Create and Manage Teacher users
Create and Manage subjects
🔑 Environment Variables
To run this project, you will need to add the following variables to your backend/config.json file

mongodb.connectionString jwt.secret

🧰 Getting Started
‼️ Prerequisites
This project uses MongoDB as database. please install mongodb server in local environment.

🏃 Run Locally
Clone the project

  git clone 
Go to the project directory

  cd project-directory
Install dependencies

  cd backend
  npm install
  cd ../frontend
  npm install
  cd ../user-portal-frontend
  npm install
Start the backend server

  cd backend
  npm start
Start the frontend client for admin

  cd frontend
  npm start
Start the frontend client for teacher/student

  cd user-portal-frontend
  npm start
Note : admin user is created when backend runs first time. default admin (username, password) details are ("sysadmin","systemadmin"). addAdminIfNotFound() function of backend/services/admin.js file is for this logic. You can check/modify default admin details from this function.

Run With Docker
build docker images

  docker-compose build
Run container and services

  docker-compose up
Use following paths

  Backend server : localhost:5000/
  Admin Frontend : localhost:3100/
  User  Frontend : localhost:3200/
🎶 to-do
add more features
👋 Contributing

Contributions are always welcome!

See contributing.md for ways to get started.

⚠️ License
Distributed under the no License.

💎 Acknowledgements
Following libraries have been used in this projects.

Material UI
Passport JS
Awesome Readme Template
