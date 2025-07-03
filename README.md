
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
# 🎬 AI-Powered Movie Ticket Booking System (BookMyShow Clone)

An intelligent, full-stack movie ticket booking system built with **Next.js**, **Node.js**, **Flask**, and **OpenAI GPT-4**, inspired by the functionality of BookMyShow.

---

## 🚀 Features

- 🎦 Browse and book movies with real-time seat selection
- 🧠 **ML-powered Recommender System** (Collaborative Filtering)
- 📈 **Seat Demand Predictor** using XGBoost
- 🔐 **Fraud Detection Agent** for secure bookings
- 🤖 **GPT-4 Chatbot Assistant** for conversational booking
- 💳 **Razorpay Sandbox Payment Integration**
- 🧪 **Postman Collection** for API testing
- 🌐 **Deployed on Vercel + Render**

---

## 🧩 Tech Stack

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

## 🧠 AI Agents

| Agent Name              | Type              | Function                                 |
|------------------------|-------------------|------------------------------------------|
| 🎬 Movie Recommender   | Learning Agent    | Suggests movies using user preferences   |
| 📊 Seat Demand Predictor | Predictive Agent | Forecasts seat availability for shows    |
| 🔐 Fraud Detection Bot | Reflex Agent      | Flags risky payment behavior             |
| 🤖 GPT Booking Chatbot | NLP Agent         | Books tickets via OpenAI GPT interaction |

---

## 📁 Project Structure

/client # Next.js frontend

/server # Node.js backend API

/ml-services # Python Flask APIs (ML models)

├── recommender.py

├── seat_predictor.py

└── fraud_detector.py

/postman_collection # Test suite for all APIs

.env.example # Example environment variables

README.md # This file


---

## 📦 How to Run Locally

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
