# Spur AI Chat (Demo)

A simple full-stack AI support chat demo built as part of a take-home assignment.  
This project demonstrates frontend–backend communication, clean API design, and basic AI integration.

---

## ✨ Features

- Simple chat UI (user → AI)
- React frontend built with Vite
- Node.js + Express backend
- REST API communication
- Environment variable–based configuration
- Clean project structure (no secrets committed)

---

## 🛠 Tech Stack

### Frontend
- React (Vite)
- TypeScript
- Fetch API
- Basic responsive UI

### Backend
- Node.js
- Express
- TypeScript
- OpenAI SDK
- dotenv
- CORS

---

## 📁 Project Structure

spur-ai-chat/
│
├── frontend/ # React frontend
│
├── backend/ # Express backend
│ ├── src/
│ │ └── index.ts
│ ├── package.json
│ └── package-lock.json
│
├── .gitignore
└── README.md

---

## 🚀 Getting Started (Local Setup)

### 1️⃣ Clone the repository

```bash
git clone https://github.com/KhusbuThapa/spur-ai-chat.git
cd spur-ai-chat

---

2️⃣ Backend Setup
cd backend
npm install

Create a .env file inside the backend folder:

OPENAI_API_KEY=your_openai_api_key_here
PORT=5000

Create a .env file inside the backend folder:

OPENAI_API_KEY=your_openai_api_key_here
PORT=5000

Start the backend server:

npm run dev

Backend will run on:

http://localhost:5000

3️⃣ Frontend Setup
cd ../frontend
npm install
npm run dev

Frontend will run on:

http://localhost:5173

Frontend will run on:

http://localhost:5173

🔄 API Overview
Health Check

GET /

Returns: "Spur AI Chat Backend Running"

Send Chat Message

POST /chat/message

Request body:

{
  "message": "Hello"
}
Response:

{
  "reply": "AI response text",
  "sessionId": "demo-session"
}

🔐 Environment Variables

.env files are intentionally excluded from the repository

API keys must be provided locally

This follows standard security best practices

👩‍💻 Author

Khusbu Thapa
GitHub: https://github.com/KhusbuThapa


---

## ✅ What to do now (IMPORTANT)

1. Open `README.md`
2. **Replace everything** with the content above
3. Save the file
4. Run:

```bash
git add README.md
git commit -m "Update README with setup and project details"
git push

