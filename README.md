Spur AI Chat (Demo)

A simple full-stack AI support chat demo built as part of a take-home assignment.
The project demonstrates frontend–backend communication, clean API design, and a basic chat UI.

🔧 Tech Stack
Frontend

React (Vite)

TypeScript

Fetch API

Simple responsive UI

Backend

Node.js

Express

TypeScript

📂Project Structure
spur-ai-chat/
│
├── frontend/        # React frontend (Vite)
│
├── backend/         # Express backend (TypeScript)
│
└── README.md

🚀 Features

Clean chat UI for user messages

Backend API to receive messages

Simulated AI response (demo-friendly)

Clear separation of frontend & backend

Environment-based configuration

⚠️ Note:
The AI response is mocked for demo purposes.
OpenAI integration can be enabled via environment variables if required.

CORS

dotenv

▶️ How to Run the Project Locally
1️⃣ Clone the repository
git clone https://github.com/KhusbuThapa/spur-ai-chat.git
cd spur-ai-chat

2️⃣ Run Backend
cd backend
npm install
npm run dev

Backend runs on:

http://localhost:5000

Health check:

GET /

3️⃣ Run Frontend
cd frontend
npm install
npm run dev


Frontend runs on:

http://localhost:5173

🔐 Environment Variables

Create a .env file inside backend/:

OPENAI_API_KEY=your_api_key_here

.env is not committed to GitHub for security reasons.

📡 API Endpoints
POST /chat/message

Request

{
  "message": "Hello"
}

Response

{
  "reply": "Thanks for your message! This is a demo AI response.",
  "sessionId": "demo-session"
}

📌 Notes

This project focuses on structure, clarity, and functionality

UI is intentionally kept simple

Suitable for demo, evaluation, and further extension

👤 Author

Khusbu Thapa
GitHub: https://github.com/KhusbuThapa

