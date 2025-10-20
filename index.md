# 🧭 Dispatcher App — CS 499 Capstone Project  

### 🎓 Southern New Hampshire University — Computer Science ePortfolio  
**Student:** Mohamed Aziz Zaghdoudi  
**Course:** CS 499 – Computer Science Capstone  
**Date:** [Oct, 2025]  

---

## 🛫 Project Overview  
The **Dispatcher App** is a full-stack airline scheduling system designed to optimize flight-to-agent task assignments at airport gates.  

It consists of:  
- A **web dashboard** for dispatchers to monitor and assign flights  
- A **mobile-friendly interface** for gate agents to view their assigned tasks in real time  
- A **Node.js / Express backend** connected to **MongoDB** for secure and persistent data management  

This project demonstrates proficiency across all three major areas of computer science:  
1. **Software Design & Engineering**  
2. **Algorithms & Data Structures**  
3. **Databases**

---

## 🧱 Tech Stack  

| Layer | Technology |
|-------|-------------|
| **Frontend** | React + TypeScript + Vite + Tailwind |
| **Routing & Auth** | React Router v6 + Context API (RBAC Guards) |
| **Backend** | Node.js + Express |
| **Database** | MongoDB + Mongoose |
| **API Testing** | Postman |
| **Version Control** | Git & GitHub |
| **Deployment** | GitHub Pages (Portfolio) + Localhost API |

---

## 🧩 Artifact Enhancements  

### 🧠 **Enhancement 1: Software Design & Engineering**
- Migrated the app from **React (JS)** to **React + TypeScript + Vite** for improved performance and maintainability.  
- Implemented **Role-Based Access Control (RBAC)** and guarded routing to manage access between dispatcher and gate agent roles.  
- Designed clean UI flow for both mobile (agents) and desktop (dispatchers).

[📥 Download Enhancement 1 Narrative](https://github.com/Kenycode16/ePortfolio/raw/main/docs/Narrative_one.docx)

---

### ⚙️ **Enhancement 2: Algorithms & Data Structures**
- Developed a **dynamic scheduling algorithm** that automatically assigns available agents to flights based on **ETA/ETD priority**.  
- Utilized efficient data structures such as **maps, queues, and arrays** to manage active flight and assignment data.  
- Optimized fairness and task distribution using sorting and constraint filtering.

[📥 Download Enhancement 2 Narrative](https://github.com/Kenycode16/ePortfolio/raw/main/docs/Narrative_two.docx)

---

### 🗄️ **Enhancement 3: Databases**
- Integrated **MongoDB** for persistent flight, agent, and assignment storage.  
- Created **Mongoose models** and **Express routes** for CRUD operations.  
- Ensured secure communication and scalability between backend and frontend.

[📥 Download Enhancement 3 Narrative](https://github.com/Kenycode16/ePortfolio/raw/main/docs/Narrative_three.docx)

---

## 🧾 Professional Self-Assessment
The self-assessment summarizes my learning journey throughout the Computer Science program and highlights how the Dispatcher App demonstrates my growth as a full-stack developer.

[📥 Professional Self-Assessment](https://github.com/Kenycode16/ePortfolio/raw/main/docs/CS499_Professional_Self_Assessment.docx)

---

## 🎥 Code Review Video  
In this video, I present the architecture, explain each enhancement, and demonstrate how the Dispatcher App integrates software design, algorithms, and databases.  

🎬 **Watch Here:** [YouTube Link](https://youtu.be/nhLiJEXryek)

---

## ⚙️ How to Run the Project  

### **1️⃣ Backend Setup**
```bash
cd server
npm install
npm run dev
```
Create a `.env` file:
```
MONGO_URI=your_mongo_connection_string
PORT=4000
JWT_SECRET=your_secret_key
```

### **2️⃣ Frontend Setup**
```bash
cd frontend
npm install
npm run dev
```

Access the frontend at [http://localhost:5173](http://localhost:5173) and backend API at [http://localhost:4000](http://localhost:4000).

---

## 🌐 GitHub Pages Portfolio
The full ePortfolio containing artifacts, narratives, and documentation is hosted on:  
🔗 [https://github.com/Kenycode16/Dispatcher-app](https://github.com/Kenycode16/Dispatcher-app/tree/category-three-enhancement)

---

## 🧩 Folder Structure
```
Dispatcher-App/
│
├── frontend/           # Vite + React (TypeScript) client
│   ├── src/
│   │   ├── features/
│   │   ├── shared/
│   │   ├── pages/
│   │   └── App.tsx
│   └── vite.config.ts
│
├── server/             # Express backend with MongoDB
│   ├── models/
│   ├── routes/
│   └── server.js
│
├── docs/               # Word narratives + self-assessment
└── README.md
```

---

## 🏁 Course Outcomes Demonstrated
- **Collaborative software design** using modular architecture  
- **Algorithmic thinking** for optimized scheduling  
- **Database integration** ensuring data persistence and scalability  
- **Secure development** through JWT and role-based routing  
- **Professional communication** via technical documentation and portfolio presentation  
