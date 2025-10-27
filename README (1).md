# 🧡 On_Orion - Fitness Social App

**On_Orion** is a modern web-based fitness and wellness platform designed to bring social engagement into personal fitness journeys.  
It allows users to **log workouts**, **upload photos**, **track fitness goals**, and **earn rewards** — all in an interactive, community-driven environment.

---

## 🚀 Features

- 🔐 **Authentication System** (Login/Signup) using Firebase Authentication  
- 📸 **Photo Posts** with real-time image compression and upload progress  
- 💪 **Workout Logging** with optional video proof  
- 🧾 **Social Feed** displaying posts in real-time using Firestore  
- 🧍 **User Profiles** with points, badges, followers, and wallet balance  
- 🌗 **Dark/Light Mode Toggle** with persistent theme  
- ☁️ **Firebase Integration** for:
  - Authentication  
  - Firestore Database  
  - Cloud Storage  

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript (ES Modules)
- **Backend:** Firebase (Auth, Firestore, Storage)
- **Tools/Libraries:**
  - [TailwindCSS CDN](https://cdn.tailwindcss.com)
  - [Firebase JS SDK v11](https://firebase.google.com/)
  - [Browser Image Compression](https://www.npmjs.com/package/browser-image-compression)

---

## 📂 Project Structure

```
fix.html        → Main application file (contains HTML, JS, and Firebase logic)
```

---

## ⚙️ Setup & Run Instructions

Follow these simple steps to run **On_Orion** locally:

### 1️⃣ Prerequisites
Ensure you have the following:
- A modern browser (Chrome, Edge, Firefox)
- Internet connection (for Firebase CDN and Tailwind)
- A valid Firebase project (optional if using the existing configuration)

---

### 2️⃣ Steps to Run

#### Option 1: Run Directly (Recommended)
1. Download or clone this repository.  
2. Open the file **`fix.html`** in your browser (double-click or drag it into a browser window).  
3. The app should load directly, using Firebase hosting and services.

#### Option 2: Serve Locally
If you want to use ES Module imports properly:
```bash
# Using Python HTTP Server
python -m http.server 8000
```
Then open:
```
http://localhost:8000/fix.html
```

---

### 3️⃣ Firebase Setup (if you wish to use your own project)
1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new project and enable:
   - **Authentication (Email/Password)**
   - **Cloud Firestore**
   - **Storage**
3. Replace the configuration in `fix.html`:
   ```js
   const firebaseConfig = {
       apiKey: "YOUR_API_KEY",
       authDomain: "YOUR_PROJECT.firebaseapp.com",
       projectId: "YOUR_PROJECT_ID",
       storageBucket: "YOUR_BUCKET.appspot.com",
       messagingSenderId: "YOUR_SENDER_ID",
       appId: "YOUR_APP_ID"
   };
   ```

---

## 🧩 Future Enhancements

- 🏃 Integration with wearable fitness devices  
- 💰 Wallet-to-reward redemption system  
- 🧑‍🤝‍🧑 College-level community integration  
- 🗓️ Event and leaderboard system  

---

## 🤝 Contribution & Feedback

This project is part of a **college innovation initiative** focused on improving campus health engagement.  
We welcome collaboration, feedback, and support from **administration authorities, mentors, and developers** to enhance this portal’s reach and impact.

---

## 📜 License

This project is developed for educational and demonstration purposes.  
© 2025 On_Orion Team. All rights reserved.
