# AntigravityAI - Premium SaaS Chatbot

A production-ready MERN stack application featuring a modern SaaS UI, secure authentication, and AI-powered chat using Groq (Llama 3.1).

## 🚀 Key Features
- **Frontend**: React 18 (Vite), Tailwind CSS, Framer Motion (for smooth animations).
- **Backend**: Node.js, Express.js, MongoDB (MVC architecture).
- **AI Integration**: Fully functional Groq API integration with llama-3.1-8b-instant.
- **Authentication**: JWT & Bcrypt based secure authentication system.
- **UI/UX**: Premium Glassmorphism design, animated gradients, and mobile-first responsiveness.
- **Database**: Full chat history and user profiles stored in MongoDB.

## 📁 Project Structure
- **/client**: The React application.
- **/server**: The Express API and database models.

## 🛠️ Setup Instructions

### 1. Prerequisites
- Node.js (v18+)
- MongoDB Atlas account (or local MongoDB)
- Groq API Key (Get it from [Groq Console](https://console.groq.com/))

### 2. Backend Setup
1. Open the `/server` directory.
2. The `.env` file should be pre-configured, but you can update the `MONGO_URI` and `GROQ_API_KEY` if needed.
3. Install dependencies:
   ```bash
   cd server
   npm install
   ```
4. Start the server:
   ```bash
   npm start
   ```

### 3. Frontend Setup
1. Open the `/client` directory.
2. Install dependencies:
   ```bash
   cd client
   npm install
   ```
3. Start the Vite dev server:
   ```bash
   npm run dev
   ```

## 🌐 API Endpoints
- **Auth**: `POST /api/auth/register`, `POST /api/auth/login`
- **User**: `GET /api/user/profile`
- **Chat**: `POST /api/chat/message`, `GET /api/chat/history`, `DELETE /api/chat/history`

## 🚀 Deployment Guide
- **Frontend**: Build using `npm run build` and host on Vercel or Netlify.
- **Backend**: Host on Render, Heroku, or a VPS.
- **Database**: Use MongoDB Atlas (Cloud).

## 🎨 UI Highlight
The application uses a **Glassmorphism** design language with **Animated Gradients**. Framer Motion provides a premium feel through smooth page transitions and hover micro-interactions.

---
Developed by **AntigravityAI**
