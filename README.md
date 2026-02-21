<div align="center">

# 🎓 EduHub — Learning Management System
### *Revolutionizing Digital Education with the MERN Stack*

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)](https://socket.io/)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)

**EduHub** is a production-grade LMS designed for modern virtual classrooms. Featuring real-time collaboration, role-based dashboards, and automated analytics.

[Explore Live Demo](https://eduhubx.vercel.app) · [Report Bug](https://github.com/kvedant-04/EduHub/issues) · [Request Feature](https://github.com/kvedant-04/EduHub/issues)

</div>

---

## 🌐 Live Deployment

| Component | Provider | URL | Status |
| :--- | :--- | :--- | :--- |
| **Frontend** | Vercel | [eduhubx.vercel.app](https://eduhubx.vercel.app) | ![Active](https://img.shields.io/badge/Active-brightgreen?style=flat-square) |
| **Backend API** | Render | [eduhub-lms-api.onrender.com](https://eduhub-lms-api.onrender.com) | ![Active](https://img.shields.io/badge/Active-brightgreen?style=flat-square) |
| **Database** | MongoDB Atlas | Cloud-hosted Cluster | ![Active](https://img.shields.io/badge/Active-brightgreen?style=flat-square) |

> [!IMPORTANT]
> The backend uses Render's free tier; the initial request may take 30-60 seconds to "spin up" if the service is asleep.

---

## 🎯 Project Objectives

- **Scalability:** Built to handle multiple virtual classrooms simultaneously.
- **Interactivity:** Real-time engagement through WebSockets.
- **Data-Driven:** Comprehensive analytics for both students and educators.
- **Full-Cycle:** A complete demonstration of the MERN stack in a production environment.

---

## ✨ Core Features

### 🔐 Security & Access
* **JWT Authentication:** Secure stateless session management.
* **RBAC:** Role-Based Access Control for **Students**, **Teachers**, and **Admins**.
* **Protected Routes:** Granular control over UI elements based on user clearance.

### 🎥 Virtual Classroom
* **Live Meetings:** Real-time communication powered by **Socket.io**.
* **Moderation:** Host controls for waiting rooms, chat management, and participant status.
* **Engagement:** Instant reactions, hand-raises, and real-time chat.

### 📚 Learning Tools
* **Class Management:** Dynamic enrollment via unique class codes.
* **Assignments:** Full lifecycle—creation, submission, and grading.
* **Gamification:** XP and Level-based progress system to boost student engagement.
* **Attendance:** Automated tracking for all live sessions.

---

## 🛠 Tech Stack

### **Frontend**
| Tool | Purpose |
| :--- | :--- |
| **React 18** | UI Library |
| **Vite** | Fast Build Tool |
| **Tailwind CSS** | Utility-first Styling |
| **Framer Motion** | Smooth UI Animations |
| **Axios** | API Communication |

### **Backend**
| Tool | Purpose |
| :--- | :--- |
| **Node.js** | Runtime Environment |
| **Express.js** | Backend Framework |
| **MongoDB** | NoSQL Database |
| **Socket.io** | Real-time Engine |
| **Bcrypt.js** | Password Hashing |

---

## 📁 Project Structure

```bash
EduHub/
├── 📱 client/                # Frontend (Vite + React)
│   ├── src/
│   │   ├── components/       # Reusable UI parts
│   │   ├── context/          # State management
│   │   ├── pages/            # Full page views
│   │   └── utils/            # Helper functions
│   └── package.json
│
└── ⚙️ server/                # Backend (Node + Express)
    ├── controllers/          # Business logic
    ├── models/               # Mongoose schemas
    ├── routes/               # API Endpoints
    ├── socket/               # WebSocket logic
    └── server.js             # Entry point
⚙️ Local Setup & Installation
1️⃣ Clone the Repository
Bash
git clone https://github.com/kvedant-04/EduHub
cd EduHub
2️⃣ Backend Configuration
Bash
cd server
npm install
Create a .env file in the server directory:

Code snippet
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=7d
NODE_ENV=development
CLIENT_URL=http://localhost:5173
npm run dev

3️⃣ Frontend Configuration
Bash
cd ../client
npm install
Create a .env file in the client directory:

Code snippet
VITE_API_URL=http://localhost:5000
npm run dev

🚀 Usage Guide
For Students
Join classes using Class Codes.

View performance via XP and Level progress bars.

Submit assignments and attend live meetings directly from the dashboard.

For Teachers
Create classes and generate unique Invite Codes.

Host meetings with moderator controls.

Grade assignments and monitor Class Analytics.

For Admins
High-level overview of system statistics.

Verify teacher accounts and manage user permissions.

🎨 UI / UX Excellence
Responsive Design: Optimized for Mobile, Tablet, and Desktop.

Theme Support: Native Dark and Light mode options.

Interactive Feedback: Toast notifications and loading skeletons for a seamless feel.

👨‍💻 Author
Vedant Kolhe
Third-year Computer Engineering student

📄 License
This project is licensed under the MIT License.

[!NOTE]

EduHub was built as a full-cycle MERN project, covering everything from system design and authentication to real-time communication and cloud deployment.