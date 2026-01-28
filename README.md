# Task Management System (MERN Stack)

A full-stack **Task Management System** built using the **MERN stack (MongoDB, Express.js, React, Node.js)**.  
This application helps teams and individuals **create, assign, track, and manage tasks** efficiently with real-time updates and role-based access.

📸 Screenshots
<img width="1904" height="971" alt="Screenshot 2025-09-01 134707" src="https://github.com/user-attachments/assets/a4a7f290-ca35-478d-bc67-fefdb522423d" />
<img width="1904" height="971" alt="Screenshot 2025-09-01 134920" src="https://github.com/user-attachments/assets/aab6d61a-f553-446c-9eb0-d69e2943083a" />
<img width="1919" height="975" alt="Screenshot 2025-09-01 134810" src="https://github.com/user-attachments/assets/b7f2d8ed-308e-4d16-80a1-29ec64e895d0" />
<img width="1918" height="972" alt="Screenshot 2025-09-01 134902" src="https://github.com/user-attachments/assets/0114dea8-00f7-4969-be70-1a93b3581115" />
<img width="1901" height="973" alt="Screenshot 2025-09-01 135004" src="https://github.com/user-attachments/assets/7159200f-d44c-4a03-9a02-4694893e1661" />
<img width="1902" height="973" alt="Screenshot 2025-09-01 135244" src="https://github.com/user-attachments/assets/d9095231-a707-4743-b32e-f783cbaa744f" />
<img width="1905" height="972" alt="Screenshot 2025-09-01 135616" src="https://github.com/user-attachments/assets/9dc55856-d1e8-4249-a5ff-de697756c3d2" />
<img width="1906" height="974" alt="Screenshot 2025-09-01 135518" src="https://github.com/user-attachments/assets/b8a78cc4-7367-4dad-9d50-4b9f2b2087c3" />
<img width="1905" height="975" alt="Screenshot 2025-09-01 135640" src="https://github.com/user-attachments/assets/a937dac7-7825-49c3-83e6-23dc752e67a7" />
<img width="1905" height="974" alt="Screenshot 2025-09-01 135658" src="https://github.com/user-attachments/assets/1ced3462-36a9-4370-852c-0b9c8ff71f8d" />
<img width="1907" height="975" alt="Screenshot 2025-09-01 135734" src="https://github.com/user-attachments/assets/706919a9-1bc2-400b-9fe7-eebba875cbd0" />

---

## 🚀 Features

### 👤 User Management
- User authentication (Login / Register)
- JWT-based secure authentication
- Role-based access (Admin / User)

### ✅ Task Management
- Create, update, delete tasks
- Assign tasks to users
- Set priority and due dates
- Track task status (To Do, In Progress, Done)
- Add descriptions and comments

### 📊 Dashboard
- Task summary (total, completed, pending)
- Status-wise task visualization
- User-specific task view

### 🔔 Notifications
- Task assignment alerts
- Status update notifications

### 🔍 Search & Filter
- Search tasks by title
- Filter by status, priority, or user

---

## 🛠 Tech Stack

### Frontend
- React.js
- Redux Toolkit (state management)
- Tailwind CSS / Material UI
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt.js

### Dev Tools
- Nodemon
- Postman
- VS Code

---

## 📁 Project Structure

task-management-system/
│
├── client/ # React frontend
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── redux/
│ │ ├── services/
│ │ └── App.js
│ └── package.json
│
├── server/ # Node + Express backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ ├── config/
│ └── server.js
│
├── .env
├── README.md
└── package.json


---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/task-management-system.git
cd task-management-system
2. Backend Setup
cd server
npm install
Create a .env file in server/:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
Run backend:

npm run dev
3. Frontend Setup
cd client
npm install
npm start
Frontend runs on:

http://localhost:3000
Backend runs on:

http://localhost:5000
🔐 API Endpoints
Auth
Method	Endpoint	Description
POST	/api/auth/register	Register user
POST	/api/auth/login	Login user
Tasks
Method	Endpoint	Description
GET	/api/tasks	Get all tasks
POST	/api/tasks	Create task
PUT	/api/tasks/:id	Update task
DELETE	/api/tasks/:id	Delete task
🧠 Application Workflow
User registers/logs in

JWT token generated and stored

User creates or receives tasks

Tasks move through statuses

Dashboard updates in real time



🌱 Future Enhancements
Real-time updates with Socket.IO

Email notifications

Team & project modules

Kanban board (drag & drop)

File attachments

Activity logs

🧪 Testing
npm test
📄 License
This project is licensed under the MIT License.

🤝 Contributing
Pull requests are welcome.
For major changes, please open an issue first to discuss what you would like to change.

⭐ Support
If you like this project, give it a ⭐ on GitHub!


---

If you want, I can:
- Make this **resume-friendly**
- Add **Docker setup**
- Add **CI/CD section**
- Customize it for **your exact project features**
- Convert it to **Jira-style system README**

Just tell me 👍


