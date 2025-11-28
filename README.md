📘 QuizApp – MERN Quiz Platform

QuizApp is a full-stack MERN-based quiz application where users can test their knowledge across various tech topics like HTML, CSS, MongoDB, React, and Node.js.
It includes a role-based hierarchy with two types of users:

Admin

User

Admins can manage quizzes and users, while users can take quizzes and view results.

🚀 Features
🧑‍💻 User Features

🎯 Take Quizzes: Attempt quizzes on different topics.

📊 View Results: See score, correct answers, and submitted answers.

🔄 Multiple Quizzes: Choose from various categories.

🛠️ Admin Features

👥 Manage Users: View, update, and delete user accounts.

✍️ Add Questions: Create quiz questions for different topics.

📝 Quiz Management: Add, edit, or delete quizzes & questions.

🧩 Tech Stack
Frontend

React

Redux

Tailwind CSS

Backend

Node.js

Express.js

Database

MongoDB

Authentication

JSON Web Tokens (JWT)

Hosting

Frontend: Vercel

Backend: Render

🔐 Admin Credentials

Use the following credentials to log in as an Admin:

Email: admin@example.com
Password: admin123

📦 Setup Instructions
✅ Prerequisites

Make sure you have installed:

Node.js

MongoDB

🔧 Clone Repository
git clone <your-repo-url>
cd QuizApp

🔙 Backend Setup
cd backend
npm install


Create a .env file inside the backend folder:

PORT=3755
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret_key


Start backend server:

npm start

🎨 Frontend Setup
cd ../frontend
npm install
npm start

🌍 Access the Application

Frontend: http://localhost:3000

Backend API: http://localhost:3755

🧪 Testing Instructions
User Testing

Register / Login

Select quiz topic

Attempt quiz

Submit and view results

Admin Testing

Login using admin credentials

Manage Users

Add / Edit / Delete quiz questions

🚀 Deployment

The application is deployed on:

Vercel (Frontend)

Render (Backend)



🛠️ Future Enhancements

⏱️ Timer-based quizzes

🏷️ Quiz categories & difficulty levels

✨ UI animations

🏆 Leaderboard

📈 Advanced analytics

🤝 Contributing
