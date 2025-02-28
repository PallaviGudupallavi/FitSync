# FitSync AI - Gamified Fitness Web App

## 📌 Overview
FitSync AI is an **AI-powered gamified fitness web app** inspired by **Duolingo**, designed to make workouts engaging and interactive. It provides **AI-generated exercise suggestions, animated exercise demonstrations, personalized meal plans, and a fitness league with XP levels** to track progress.

## 🚀 Features
- ✅ **AI-Powered Daily Exercise Suggestions**
- ✅ **Smart Timer** with beep alerts
- ✅ **Fitness League & Leaderboard** to track progress
- ✅ **Animated Exercise Demonstrations** using **Lottie.js**
- ✅ **AI-Generated Meal Plans** displayed dynamically
- ✅ **Progress Rings & XP Levels** using **Chart.js**
- ✅ **Firebase Integration** for real-time database functionality

## 📸 Screenshots & Videos
### **Homepage**
[Watch Video]("C:\Users\gudup\Downloads\WhatsApp Video 2025-02-28 at 10.22.29 PM.mp4")

### **Nutrition Section**

[Watch Video]("C:\Users\gudup\Videos\Screen Recordings\Screen Recording 2025-02-28 215741.mp4")

### **Training Section**
![Training](screenshots/train.png)


## 🛠️ Tech Stack
Frontend:
✅ Streamlit – For the web-based UI and interactive elements
✅ OpenCV – For capturing and processing video frames
✅ Plotly – For data visualization and analytics

Backend & Computation:
✅ Python – Core programming language
✅ NumPy – For numerical calculations and interpolations
✅ Math Library – For angle calculations using atan2 and degrees

Computer Vision & AI:
✅ PoseDetector (likely using Mediapipe or OpenCV) – For pose estimation and detecting key body points

Hardware & Integrations:
✅ Webcam (via OpenCV) – Capturing real-time exercise data

## 🔧 Setup & Installation
### 1️⃣ Clone the Repository
```sh
 git clone https://github.com/your-username/FitSync-AI.git
 cd FitSync-AI
```

### 2️⃣ Install Dependencies (if required)
```sh
 npm install  # If using additional packages
```

### 3️⃣ Configure Firebase
1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
2. Add Firebase SDK to your project and update `firebase-config.js` with your API keys.

### 4️⃣ Run the Project Locally
Simply open `index.html` in your browser or use a live server extension.

## 🚀 Deployment
### **GitHub Pages**
1. Push your code to GitHub.
2. Go to **Settings → Pages**
3. Set the branch to `main` and save.

### **Firebase Hosting**
1. Install Firebase CLI:
```sh
 npm install -g firebase-tools
```
2. Login and initialize Firebase:
```sh
 firebase login
 firebase init
```
3. Deploy:
```sh
 firebase deploy
```

## 📜 License
This project is licensed under the **MIT License**.

## 📬 Contact
For queries or contributions, reach out to **Pallavi Gudupalli** at [your-email@example.com](mailto:your-email@example.com).
