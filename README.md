# AI Interview Prep (MERN Stack)

An AI-powered mock interview platform built with the **MERN stack (MongoDB, Express.js, React, Node.js)** that helps users practice technical and HR interviews using intelligent question generation and real-time feedback.

---

## 🚀 Features

- **AI-Powered Question Generation** – Dynamic interview questions based on selected topics.
- **Real-Time Feedback** – Get instant evaluation and improvement tips.
- **Multiple Interview Modes** – HR, Technical, and Behavioral.
- **Voice & Text Support** – Interact with the AI using speech or text.
- **Progress Tracking** – View past sessions and performance analytics.
- **Authentication & User Profiles** – Secure login/signup with personalized dashboards.

---

## 🛠️ Tech Stack

**Frontend:**
- React.js (with Hooks & Context API)
- Tailwind CSS / Material UI

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication

**AI Integration:**
- OpenAI API (or Gemini API)

**Other:**
- REST APIs
- Deployment: Vercel (frontend) & Render/Heroku (backend)

---

## 📂 Folder Structure

```bash
ai-interview-prep/
│
├── client/             # React frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/             # Node.js backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── config/
│   └── server.js
│
├── .env
├── package.json
└── README.md
⚡ Installation & Setup
1. Clone the repository:
git clone https://github.com/<your-username>/ai-interview-prep.git
cd ai-interview-prep





# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
