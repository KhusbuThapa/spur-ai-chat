# Spur AI Chat (Demo)

A simple **full-stack AI support chat demo** built as part of a take-home assignment.  
This project demonstrates **frontend–backend communication**, **clean API design**, and **basic AI integration**.

---

## ✨ Features

- Chat-style UI for user messages
- Backend API to handle chat requests
- AI-style responses (demo-ready)
- Clean separation of frontend and backend
- Environment-based configuration

---

## 🛠 Tech Stack

### Frontend
- React (Vite)
- TypeScript
- Fetch API
- Simple responsive UI

### Backend
- Node.js
- Express.js
- TypeScript
- OpenAI SDK (configurable)
- CORS
- dotenv

---

## 📁 Project Structure

spur-ai-chat/
│
├── frontend/ # React frontend
│ ├── src/
│ ├── public/
│ └── package.json
│
├── backend/ # Express backend
│ ├── src/
│ │ └── index.ts
│ ├── package.json
│ └── .env.example
│
└── README.md


---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/KhusbuThapa/spur-ai-chat.git
cd spur-ai-chat

2️⃣ Backend Setup
cd backend
npm install


Create a .env file:

OPENAI_API_KEY=your_api_key_here


Run backend:

npm run dev


Backend runs on:

http://localhost:5000

3️⃣ Frontend Setup
cd frontend
npm install
npm run dev


Frontend runs on:

http://localhost:5173

🔁 API Endpoint
POST /chat/message

Request

{
  "message": "Hello"
}


Response

{
  "reply": "Thanks for your message!",
  "sessionId": "demo-session"
}

🔐 Environment Variables

.env is not committed

Use .env.example as reference

API keys are handled securely

🚀 Notes

This is a demo-focused implementation

Designed for clarity, simplicity, and correctness

Easy to extend with real AI responses, sessions, or database storage

👤 Author

Khusbu Thapa


---

## ✅ What to do now (very important)

1. Open `README.md` in VS Code  
2. **Delete everything**
3. Paste the content above
4. Save
5. Run:

```bash
git add README.md
git commit -m "Improve README documentation"
git push

Final reassurance ❤️

Your project structure is correct

Your repo is clean

This README looks professional

A developer or recruiter will be impressed, especially knowing you’re a fresher

If you want next:

✅ “Make README shorter”

✅ “Make README more startup-style”

✅ “Help me deploy and share link”

Just tell me 💪


---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/KhusbuThapa/spur-ai-chat.git
cd spur-ai-chat

2️⃣ Backend Setup
cd backend
npm install

Create a .env file:

OPENAI_API_KEY=your_api_key_here


Run backend:

npm run dev


Backend runs on:

http://localhost:5000

3️⃣ Frontend Setup
cd frontend
npm install
npm run dev


Frontend runs on:

http://localhost:5173

🔁 API Endpoint
POST /chat/message

Request

{
  "message": "Hello"
}

Response

{
  "reply": "Thanks for your message!",
  "sessionId": "demo-session"
}

🔐 Environment Variables

.env is not committed

Use .env.example as reference

API keys are handled securely

🚀 Notes

This is a demo-focused implementation

Designed for clarity, simplicity, and correctness

Easy to extend with real AI responses, sessions, or database storage

👤 Author

Khusbu Thapa


---

## ✅ What to do now (very important)

1. Open `README.md` in VS Code  
2. **Delete everything**
3. Paste the content above
4. Save
5. Run:

```bash
git add README.md
git commit -m "Improve README documentation"
git push


