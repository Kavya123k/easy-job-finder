💼 Easy Job Finder

Easy Job Finder is a full-stack web application that helps users search, apply, and manage job opportunities easily. It provides separate dashboards for Job Seekers and Employers/Admin, making the hiring process simple and efficient.

🚀 Features
👤 Job Seeker

🔐 User Registration & Login

🔍 Search Jobs (by title, company, location, skills)

📄 View Job Details

📝 Apply for Jobs

📌 Save/Bookmark Jobs

📊 Track Application Status

👤 Profile Management (resume upload, skills, experience)

🏢 Employer / Admin

🔐 Secure Login

➕ Post New Jobs

✏️ Edit/Delete Job Listings

📂 View Applicants

✅ Approve/Reject Applications

📊 Dashboard Overview

🛠️ Tech Stack

Frontend:

React.js

HTML5

CSS3 / Tailwind CSS

Axios

Backend:

Node.js

Express.js

Database:

MongoDB

Authentication:

JWT (JSON Web Token)

📂 Project Structure
easy-job-finder/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── App.js
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
│
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/easy-job-finder.git
cd easy-job-finder

2️⃣ Backend Setup
cd backend
npm install
npm start


Create a .env file in backend folder:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

3️⃣ Frontend Setup
cd frontend
npm install
npm start


Frontend runs on:

http://localhost:3000


Backend runs on:

http://localhost:5000

🔑 Environment Variables
Variable	Description
PORT	Server port number
MONGO_URI	MongoDB connection string
JWT_SECRET	Secret key for JWT authenticatio
