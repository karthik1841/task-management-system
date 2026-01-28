# Task Management System (MERN Stack)

A full-stack **Task Management System** built using the **MERN stack (MongoDB, Express.js, React, Node.js)**.  
This application helps teams and individuals **create, assign, track, and manage tasks** efficiently with real-time updates and role-based access.

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

📸 Screenshots
<img width="1920" height="971" alt="Screenshot 2025-09-02 120012" src="https://github.com/user-attachments/assets/cae10025-aea3-4ffb-a49c-293450124825" />
<img width="1908" height="971" alt="Screenshot 2025-09-02 105208" src="https://github.com/user-attachments/assets/31455537-51d6-48eb-804b-924216645fe9" />
<img width="1920" height="974" alt="Screenshot 2025-09-02 104834" src="https://github.com/user-attachments/assets/92721f0c-87a4-44a8-8771-c7881d4f7cd0" />
<img width="1909" height="978" alt="Screenshot 2025-09-01 135840" src="https://github.com/user-attachments/assets/45918cf7-fdcd-4915-83de-0d470232a79a" />
<img width="1920" height="973" alt="Screenshot 2025-09-01 135810" src="https://github.com/user-attachments/assets/6066e2b0-34c8-447c-b07b-b50d0157c286" />
<img width="1117" height="544" alt="Screenshot 2025-09-01 135749" src="https://github.com/user-attachments/assets/ad847af2-ccb6-4ce8-b12b-37565171ab88" />
<img width="1907" height="975" alt="Screenshot 2025-09-01 135734" src="https://github.com/user-attachments/assets/63d2e763-ab9c-49e5-8f55-6e5a91db9615" />
<img width="1904" height="976" alt="Screenshot 2025-09-01 135718" src="https://github.com/user-attachments/assets/92c3d73d-cf48-4d78-86d6-ee75e52c3f80" />
<img width="1905" height="974" alt="Screenshot 2025-09-01 135658" src="https://github.com/user-attachments/assets/d550114b-f4db-4d23-93e2-d18837f52fd3" />
<img width="1905" height="975" alt="Screenshot 2025-09-01 135640" src="https://github.com/user-attachments/assets/1d5a01f8-1743-4734-b5d5-a4002b50f920" />
<img width="1905" height="972" alt="Screenshot 2025-09-01 135616" src="https://github.com/user-attachments/assets/564f64b8-e04e-47ed-9851-ee115370fcda" />
<img width="1903" height="974" alt="Screenshot 2025-09-01 135554" src="https://github.com/user-attachments/assets/81075569-662f-42d6-833e-4b561578d4c8" />
<img width="1906" height="974" alt="Screenshot 2025-09-01 135518" src="https://github.com/user-attachments/assets/36688001-8b3a-4d26-8555-5bdb1a9c1883" />
<img width="1907" height="978" alt="Screenshot 2025-09-01 135330" src="https://github.com/user-attachments/assets/f9052eaa-a866-41d0-b053-73354ceeb0e7" />
<img width="1902" height="973" alt="Screenshot 2025-09-01 135244" src="https://github.com/user-attachments/assets/d8dd11d4-179e-4beb-99ae-54e5ff4ce0c8" />
<img width="1908" height="972" alt="Screenshot 2025-09-01 135221" src="https://github.com/user-attachments/assets/247b8e4f-88a2-4bc5-8e8b-abe882525aba" />
<img width="1904" height="971" alt="Screenshot 2025-09-01 135158" src="https://github.com/user-attachments/assets/b4e2a96c-fc71-4b08-bec6-9ee9190e2604" />
<img width="1905" height="974" alt="Screenshot 2025-09-01 135125" src="https://github.com/user-attachments/assets/b13e8214-910f-4c4c-9ed2-c863a8735733" />
<img width="1907" height="973" alt="Screenshot 2025-09-01 135102" src="https://github.com/user-attachments/assets/75e77060-3319-46ea-b667-5aa7de89bfc7" />
<img width="1904" height="973" alt="Screenshot 2025-09-01 135041" src="https://github.com/user-attachments/assets/8444c4e6-5021-4d8f-a7ca-d30df8bdaf99" />
<img width="1901" height="973" alt="Screenshot 2025-09-01 135004" src="https://github.com/user-attachments/assets/50d7e78f-3042-48c0-bca7-ee2cf3ecffad" />
<img width="1904" height="971" alt="Screenshot 2025-09-01 134920" src="https://github.com/user-attachments/assets/1c5aa795-1e6e-4b92-81f7-0b0fef81a0a1" />
<img width="1918" height="972" alt="Screenshot 2025-09-01 134902" src="https://github.com/user-attachments/assets/80fee385-968c-4ab5-8bc2-3baf2d3135e6" />
<img width="1919" height="975" alt="Screenshot 2025-09-01 134810" src="https://github.com/user-attachments/assets/0832df4e-6f65-446e-85fc-0404a9b056b0" />
<img width="1920" height="973" alt="Screenshot 2025-09-01 134739" src="https://github.com/user-attachments/assets/974b18bb-e65a-4114-bca0-033bcc7667a6" />
<img width="1904" height="971" alt="Screenshot 2025-09-01 134707" src="https://github.com/user-attachments/assets/16afcb42-924e-4a03-9bb9-fc841bc54e27" />
<img width="1900" height="973" alt="Screenshot 2025-09-02 120136" src="https://github.com/user-attachments/assets/fd843fcb-7dda-4e11-b430-eb0a90b24a6d" />
<img width="1908" height="971" alt="Screenshot 2025-09-02 120115" src="https://github.com/user-attachments/assets/ae481703-2332-4bc3-aef5-a25976247cd0" />
<img width="1919" height="970" alt="Screenshot 2025-09-02 120027" src="https://github.com/user-attachments/assets/334b047c-e5b5-4a8c-849c-262b60db8886" />


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

