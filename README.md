# ✅ Todo Task Management App - Katomaran Hackathon Submission

This is a full-stack **Todo Task Management App** built as part of the Katomaran Full Stack Hackathon. The app allows users to:
- Create and manage personal todo tasks
- Assign tasks to teams (optional)
- Track status, edit, and delete tasks
- Manage team members

---

## 📦 Setup Instructions

### 🔧 Backend Setup
1. Navigate to the backend folder:
   ```bash
   cd backend
   npm install
   npm start
Create a .env file with your MongoDB URI:


MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
🖥️ Frontend Setup
Navigate to the frontend folder:

cd frontend
npm install
npm start
📽️ Video Demonstration
https://drive.google.com/file/d/1XGYTzqvbso8DJIrUaEVao-Kdsj5Ck4h9/view?usp=drivesdk

📐 Architecture Diagram

App Flow:

React Frontend ↔️ Express Backend ↔️ MongoDB

JWT used for authentication

Protected routes for task and user management

📌 Assumptions Made
User login is handled via JWT tokens.

Tasks are private and associated with authenticated users.

MongoDB Atlas is used for cloud database.

User roles and team management are minimal for MVP.

Responsive UI built with React + TailwindCSS.

App is not deployed but tested locally.

🧾 Final Note
This project is a part of a hackathon run by https://www.katomaran.com

