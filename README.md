# 🚀 InterviewIQ – AI-Powered Interview Preparation Platform

InterviewIQ is a full-stack AI-powered web application that helps users prepare for job interviews by analyzing resumes, identifying skill gaps, and generating personalized interview questions using Generative AI.

---

## 🧠 Key Features

* 🔐 **Authentication System**

  * Secure login/signup using JWT
  * Protected routes & session handling

* 📄 **Resume Analysis**

  * Upload and parse resumes
  * Extract skills, experience, and keywords

* 🤖 **AI-Powered Insights**

  * Skill gap analysis based on job descriptions
  * Personalized interview question generation
  * Resume improvement suggestions

* 📊 **Interview Preparation**

  * Technical + HR questions
  * Structured feedback reports

* 📑 **ATS-Friendly Resume Generator**

  * Generate optimized resumes
  * Export as PDF using Puppeteer

---

## 🏗️ Tech Stack

### Frontend

* React.js
* Context API
* Axios
* React Router

### Backend

* Node.js
* Express.js
* MongoDB (Atlas)

### AI Integration

* Google Gemini API

### Other Tools

* Multer (file upload)
* Puppeteer (PDF generation)
* JWT Authentication

---

## ⚙️ Project Architecture

```
Client (React)
   ↓
API Layer (Express)
   ↓
Controllers → Services → Models
   ↓
Database (MongoDB)
   ↓
AI Layer (Gemini API)
```

---

## 📂 Folder Structure

```
/client        → Frontend (React)
/server        → Backend (Node + Express)
/models        → Database schemas
/controllers   → Route handlers
/services      → Business logic (AI, parsing)
/middleware    → Auth & validation
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/InterviewIQ.git
cd InterviewIQ
```

### 2️⃣ Install dependencies

```bash
# Backend
cd server
npm install

# Frontend
cd ../client
npm install
```

### 3️⃣ Setup environment variables

Create a `.env` file in the server folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_api_key
```

---

### 4️⃣ Run the application

```bash
# Start backend
cd server
npm run dev

# Start frontend
cd client
npm start
```

---

## 📸 Screenshots (Add yours here)

* Dashboard
* Resume Upload
* AI Analysis Output
* Interview Questions

---

## 💡 Future Improvements

* Mock interview with voice interaction
* Performance scoring system
* Dashboard analytics
* Deployment (Docker + CI/CD)

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Acknowledgment

Inspired by modern AI-driven career tools and built as a learning project to explore full-stack + GenAI integration.

---

## 👨‍💻 Author

Developed by *Pranchal katiyar*
Feel free to connect on LinkedIn 🚀
