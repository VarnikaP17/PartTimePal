# 🚀 PartTimePal

PartTimePal is a full-stack job marketplace platform that connects job seekers and recruiters through intelligent job matching, real-time communication, and machine learning-powered recommendations.

The system integrates a modern React frontend, a scalable Node.js backend, and Python-based ML modules to deliver personalized job discovery.

---

## ✨ Key Features

### 👤 User & Recruiter System
- Secure authentication (JWT-based)
- Profile creation and management
- Role-based access control

### 💼 Job Marketplace
- Recruiters can post and manage jobs
- Job seekers can browse and apply
- Application tracking system

### 💬 Real-Time Communication
- Live chat between job seekers and recruiters
- Instant messaging for faster engagement

### 🤖 Machine Learning & NLP
- ML-based personalized job recommendations
- Natural Language Processing for:
  - Smart job matching
  - Text translation
  - Resume-job similarity analysis

---

## 🏗️ Architecture Overview

```
PathTimePal/
│
├── backend/     → Node.js + Express API
├── frontend/    → React (Vite) client
├── ML/          → Python ML & NLP modules
```

### 🔹 Backend
- Node.js + Express
- MongoDB (Mongoose)
- JWT Authentication
- RESTful API design

### 🔹 Frontend
- React (Vite)
- Context API for state management
- Modular component-based architecture

### 🔹 Machine Learning
- Python
- NLP processing
- Job recommendation engine
- Data preprocessing and similarity modeling

---

## 🛠️ Tech Stack

| Layer      | Technology |
|------------|------------|
| Frontend   | React, Vite |
| Backend    | Node.js, Express |
| Database   | MongoDB |
| ML/NLP     | Python |
| Auth       | JWT |
| Real-Time  | (Socket.io or similar if used) |

---

## ⚙️ Getting Started

### 🔹 1. Backend Setup

```bash
cd backend
npm install
```

Create `.env` file:

```
MONGODB_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

Run server:

```bash
npm start
```

---

### 🔹 2. Frontend Setup

```bash
cd frontend
npm install
```

Create `.env` file:

```
VITE_API_URL=http://localhost:5000/api
VITE_GOOGLE_CLIENT_ID=your_google_client_id
```

Run development server:

```bash
npm run dev
```

---

### 🔹 3. Machine Learning Setup

```bash
cd ML
python -m venv venv
.\venv\Scripts\activate   # Windows
pip install -r requirements.txt
python main.py
```

---

## 📈 Highlights

- Designed modular full-stack architecture
- Integrated ML recommendation pipeline into production workflow
- Implemented real-time communication system
- Built scalable REST APIs
- Applied NLP techniques for intelligent job matching

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss improvements.

---
