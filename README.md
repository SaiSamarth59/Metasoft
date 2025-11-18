Feedback Form with Dashboard
Project: Feedback Application (Full-Stack MERN + React Setup)

📌 Overview
This project is a simple full-stack Feedback Application that allows users to submit feedback through a form and view all submitted feedback on a dashboard. The project is divided into two main folders:

frontend/ – React application
backend/ – Node.js + Express server

📁 Project Structure
Project/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── FeedbackForm.jsx
│   │   │   └── Dashboard.jsx
│   │   ├── App.jsx
│   │   ├── index.js
│   │   └── App.css
│   ├── package.json
│   └── ...other React config files
│
└── backend/
    ├── server.js
    ├── routes/
    ├── controllers/
    ├── models/
    ├── config/
    ├── package.json
    └── ...other backend files

⚙️ Features
Frontend
Feedback submission form
Dashboard to display submitted feedback
State management using React hooks
Clean UI with components structure

Backend
API to submit feedback
API to fetch feedback list
Express server
SQLite connection

🚀 How to Run the Project
1. Start Backend
cd backend
npm install
node server.js
Backend will start on default port: http://localhost:4000

3. Start Frontend
cd frontend
npm install
npm run dev
Frontend will start on:  http://localhost:5173/

🔗 API Endpoints (Example)
Method	Endpoint	Description
POST	/api/feedback	Submit feedback
GET	/api/feedback	Get list of feedbacks
🛠 Technologies Used

Frontend
React.js
JavaScript
CSS

Backend
Node.js
Express.js
SQLite

📄 Usage
Open the frontend in browser.
Enter feedback details in the form.
Submit it
View all submitted feedback in the dashboard.

🙌 SaiSamarth

This project was developed as part of full-stack development practice work.
