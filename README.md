
# 🎬 AI-Powered Movie Ticket Booking System (BookMyShow Clone)

<div align="center">
  
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-02042B?style=for-the-badge&logo=razorpay&logoColor=00AEEF)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white)
![Render](https://img.shields.io/badge/Backend-Hosted%20on%20Render-0077CC?style=for-the-badge&logo=render&logoColor=white)
![Vercel](https://img.shields.io/badge/Frontend-Deployed%20on%20Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=for-the-badge&logo=github)

</div>

---

### Project Title: 🎬 AI-Powered Movie Ticket Booking System (BookMyShow Clone)
An intelligent, full-stack movie ticket booking system built with **Next.js**, **Node.js**, **Flask**, and **OpenAI GPT-4**, inspired by the functionality of BookMyShow.

#### URL: github.com/ishita95-harvad/bookmyshow-ai-clone

### Summary:

Developed a full-stack, intelligent movie booking platform integrating AI-driven components like a movie recommender system, seat demand predictor, fraud detection engine, and GPT-4 chatbot assistant. Inspired by BookMyShow, but reimagined with modern AI.

![image](https://github.com/Ishita95-harvad/book-my-show/blob/main/dcb60c8b-843b-430d-8de8-3848577c2997.png)

### Key Contributions:

Developed microservices using Node.js (Express) and Flask (Python)

**Built ML models:** Collaborative Filtering, XGBoost seat prediction, Logistic regression fraud detector

Integrated OpenAI GPT-4 API for conversational ticket booking

Implemented secure, sandboxed Razorpay payment gateway

Deployed frontend on Vercel, backend and ML services on Render

Authored README, Postman suite, and deployment docs for production readiness

**Stack:** Next.js · Node.js · Flask · MongoDB · Razorpay · OpenAI · Python · Vercel · Render

---

### 📁 Project Structure

book-your-show/

**├── client/ (React or Flutter)**

│   ├── pages/

│   ├── components/

│   └── services/ (API calls)

**├── server/**

│   ├── routes/

│   ├── controllers/

│   └── db.json (if using JSON Server)

**├── README.md**

**├── package.json**

**└── .env**


---

### 🚀 Features

- 🎦 Browse and book movies with real-time seat selection
- 🧠 **ML-powered Recommender System** (Collaborative Filtering)
- 📈 **Seat Demand Predictor** using XGBoost
- 🔐 **Fraud Detection Agent** for secure bookings
- 🤖 **GPT-4 Chatbot Assistant** for conversational booking
- 💳 **Razorpay Sandbox Payment Integration**
- 🧪 **Postman Collection** for API testing
- 🌐 **Deployed on Vercel + Render**

---

### 🧩 Tech Stack

| Layer         | Technology             |
|---------------|-------------------------|
| Frontend      | Next.js, Tailwind CSS   |
| Backend       | Node.js (Express.js)    |
| ML Services   | Python (Flask), scikit-learn, XGBoost |
| Chatbot       | OpenAI GPT-4 API        |
| Database      | MongoDB (Atlas)         |
| Payment       | Razorpay (Sandbox)      |
| Deployment    | Vercel, Render          |

---

### 🧠 AI Agents

| Agent Name              | Type              | Function                                 |
|------------------------|-------------------|------------------------------------------|
| 🎬 Movie Recommender   | Learning Agent    | Suggests movies using user preferences   |
| 📊 Seat Demand Predictor | Predictive Agent | Forecasts seat availability for shows    |
| 🔐 Fraud Detection Bot | Reflex Agent      | Flags risky payment behavior             |
| 🤖 GPT Booking Chatbot | NLP Agent         | Books tickets via OpenAI GPT interaction |

---

### 📦 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/your-username/bookmyshow-ai-clone.git
cd bookmyshow-ai-clone

# Start frontend
cd client
npm install
npm run dev

# Start backend
cd ../server
npm install
npm run dev

# Start ML APIs
cd ../ml-services
pip install -r requirements.txt
python app.py
