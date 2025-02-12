# 🎓 Educational Platform for Deaf and Mute Community

## 📌 Project Overview
The **Educational Platform for the Deaf and Mute Community** is an **AI-powered interactive learning system** that utilizes **real-time sign language recognition** to facilitate communication and education. The platform integrates **Mediapipe and LSTM models** for gesture recognition, enabling users to interact, take quizzes, and learn through an accessible digital experience.

## 🎯 Features
- **Real-time Sign Language Recognition** using **Mediapipe & LSTM**
- **ML-powered Interactive Quizzes**, where users sign answers and get evaluated
- **Text-to-Sign & Sign-to-Text Conversion**
- **Lesson Modules with Video & Gesture Tutorials**
- **FastAPI Backend & React.js/Streamlit Frontend** for seamless performance
- **User Progress Tracking & Performance Reports**

## 🛠️ Tech Stack
### **Machine Learning:**
- Mediapipe (Hand Tracking & Feature Extraction)
- LSTM (Deep Learning Model for Gesture Recognition)
- TensorFlow/Keras (Model Training & Optimization)
- OpenCV (Image Processing)

### **Backend:**
- FastAPI (Python framework for API development)
- MongoDB (Database for user data & progress tracking)

### **Frontend:**
- React.js / Streamlit (Interactive UI for user engagement)
- Tailwind CSS / Bootstrap (Responsive design)

## 📂 Project Structure
```
📦 signlearn
├── 📂 frontend
│   ├── public
│   ├── src
│   ├── App.js
│   ├── Quiz.js
│   ├── styles.css
│
├── 📂 backend
│   ├── main.py  # FastAPI main application
│   ├── models.py  # Database models
│   ├── routes.py  # API routes for quizzes & sign recognition
│   ├── database.py  # MongoDB connection
│   ├── sign_model.py  # LSTM Model Implementation
│
├── 📂 ml_model
│   ├── preprocess.py  # Data preprocessing for sign recognition
│   ├── train.py  # Model training script
│   ├── predict.py  # Gesture prediction API
│
├── requirements.txt
├── README.md
```

## 🚀 Installation & Setup
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/signlearn.git
cd signlearn
```

### **2️⃣ Set Up the Backend**
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

### **3️⃣ Set Up the Frontend**
```bash
cd frontend
npm install
npm start
```

## 📡 API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/auth/signup` | Register a new user |
| POST | `/auth/login` | Authenticate user & get token |
| GET | `/quiz/questions` | Fetch interactive sign-based quiz questions |
| POST | `/quiz/submit` | Submit sign-based quiz response |
| POST | `/predict/sign` | Recognize sign language gesture |

## 🏗️ Future Enhancements
- Add **Live Sign Language Tutoring Feature**
- Introduce **Speech-to-Sign AI Assistant**
- Improve **Gesture Recognition Model Accuracy**

## 🤝 Contribution
Feel free to **fork, raise issues, or contribute** to this project!

## 📜 License
This project is licensed under the **MIT License**.

---
### 🎉 Let's Make Learning More Accessible! 🤟
