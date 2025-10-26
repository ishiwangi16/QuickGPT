# 🤖 ChatBot – Full Stack AI Chatbot  

An end-to-end **AI-powered chatbot application** with a **React + Vite frontend** and an **Express + MongoDB backend**.  
The project demonstrates **conversational AI, real-time communication, authentication, payments, and media handling**.  
Deployed seamlessly on **Vercel**.  

---

## ✨ Features  

### 🌐 Frontend (React + Vite)
- ⚛️ **Modern UI** built with React 19 and TailwindCSS  
- 💬 **Chat interface** with real-time conversation support  
- 📖 **Markdown & Code highlighting** using React Markdown + PrismJS  
- 🔔 **Notifications** with React Hot Toast  
- 🚦 **Routing** powered by React Router  

### ⚡ Backend (Express + MongoDB)
- 👤 **Authentication** – JWT + bcrypt for secure login/signup  
- 💬 **Chat & Message APIs** – REST endpoints for conversations  
- 💳 **Stripe Integration** – credit purchase & webhook handling  
- 🗄️ **MongoDB** – scalable NoSQL database with Mongoose  
- 🖼️ **ImageKit** – media upload and management  
- 🔑 **Environment variables** for secrets (AI, Stripe, DB, etc.)  

---

## 🛠 Tech Stack  

**Frontend**  
- React 19, React Router  
- TailwindCSS 4, PrismJS  
- Axios, Moment.js  
- Vite 7 (build tool)  

**Backend**  
- Node.js, Express.js  
- MongoDB + Mongoose  
- JWT, bcryptjs  
- Stripe API + Webhooks  
- ImageKit  
- Gemini / OpenAI APIs  

**Deployment**  
- Vercel (frontend + backend serverless hosting)  

---

## 📦 Installation & Setup  

### 🔹 Clone Repositories
```bash
# Clone frontend
git clone <your-frontend-repo-url>
cd client
npm install

# Clone backend
git clone <your-backend-repo-url>
cd server
npm install


QuickGPT/
│── client/                # React + Vite frontend
│   ├── src/               # Components, pages, logic
│   ├── index.html         # Frontend entrypoint
│   ├── vite.config.js     # Vite + Tailwind config
│   └── package.json       # Frontend dependencies
│
│── server/                # Express backend
│   ├── configs/           # DB config
│   ├── controllers/       # API controllers (Stripe, etc.)
│   ├── routes/            # User, chat, message, credit routes
│   ├── server.js          # Server entrypoint
│   ├── vercel.json        # Vercel deployment config
│   └── package.json       # Backend dependencies
│
└── README.md              # Documentation
