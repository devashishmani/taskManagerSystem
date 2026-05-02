TASK MANAGER PROJECT (MERN STACK)

Project Overview:
This is a full-stack Task Management web application built using the MERN stack (MongoDB, Express, React, Node.js). The system allows admins to create projects, assign tasks, and manage teams, while members can view and update their assigned tasks.

Features:

* User Authentication (Login/Signup using JWT)
* Role-based Access (Admin & Member)
* Admin Dashboard:

  * Create, update, delete projects
  * Assign tasks to members
  * Add/remove team members
* Member Dashboard:

  * View assigned tasks
  * Update task status (Pending / Completed)
* Real-time project/task tracking
* Clean UI using Tailwind CSS

Tech Stack:
Frontend:

* React (Vite)
* Tailwind CSS
* Axios

Backend:

* Node.js
* Express.js
* MongoDB (Atlas)
* JWT Authentication

Deployment:

* Backend: Railway
* Frontend: Netlify 
* Database: MongoDB Atlas

link
deft-salmiakki-23b73a.netlify.app

Installation (Local Setup):

1. Clone Repository:
   git clone <repo-url>

2. Backend Setup:
   cd backend
   npm install

Create .env file:
MONGO_URI=your_mongo_url
JWT_SECRET=your_secret

Run backend:
npm run dev

3. Frontend Setup:
   cd frontend
   npm install
   npm run dev

Future Improvements:

* Notifications system
* Real-time updates using Socket.io
* Charts & analytics dashboard
* Dark mode UI

Author:
Devashish Mani Tripathi
