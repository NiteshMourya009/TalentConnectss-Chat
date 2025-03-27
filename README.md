# TalentConnectss-Chat
A full-stack real-time chat application built using React.js (frontend) and Node.js with Express (backend). Users can send and receive messages instantly with real-time updates.

🛠️ **Features**
Real-time messaging
User authentication (SIgnup/login/logout)
Online/offline status display
Responsive UI
REST API for message handling

**📂 Project Structure**
TalentConnect-Chat/
├── backend/       # Node.js + Express API + Socket.io
└── frontend/      # React.js (React) UI 

🚀 **Prerequisites**
Ensure you have the following installed:
1. Node.js (v18+ recommended)
2. Git

🧑‍💻 **Setup Instructions**

1. **Clone the Repository**
   https://github.com/NiteshMourya009/TalentConnectss-Chat.git
   
2. 📦**Backend Setup (Node.js + Express)**
   1) cd backend
   2) npm init -y
   3) npm install express
   4) npm install bcryptjs
   5) npm install cors
   6) npm install cookie-parser socket.io nodemon mongoose jsonwebtoken dotenv
   
3. **Frontend Setup (React.js)**
   1) cd frontend
   2) npm create vite@latest 
   3) choose current folder
   4) choose react then javascript
   // Now Tailwind Css setup
   5) run command -> npm install -D tailwindcss@3 postcss autoprefixer
      npx tailwindcss init -p
   6) run command -> npm install axios js-cookie react-hook-form react-hot-toast react- icons react-router-dom socket.io-client zustand daisyui
4. **Environment Setup**
   Create .env files in the backend directories with the required variables.
   📌 **Backend .env**
   MONGODB_URI = mongodb+srv://niteshmourya009:IFlCXHhQ6BugNEL0@cluster0.2tbisgc.mongodb.net/TalentConnect-ChatApp
   
   PORT = 4002
   
   JWT_TOKEN = w6pTUwi6ksHUPqMvOiPU1hto9e2PtVhGLJfsphz1fEw=
