# 🗓️ Day Planner Web App

## 📌 Overview

This is a simple **Day Planner Web Application** built using **HTML, CSS, and JavaScript**.
It allows users to sign in, plan their daily tasks, and save them locally in the browser.

---

## 🌐 Live Demo

👉 https://your-live-link-here.com

---

## 🚀 Features

* 🔐 Simple Sign-In system (using localStorage)
* 📅 Daily schedule planner (6 AM – 10 PM)
* 💾 Saves tasks automatically in browser storage
* 👋 Personalized welcome message
* 📆 Displays current date
* 🚪 Logout functionality
* 🔒 Protected page (cannot access planner without login)

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* Browser LocalStorage

---

## 📂 Project Structure

```
project-folder/
│
├── index.html       # Sign In Page
├── day_planner.html    # Planner Page
└── README.md           # Project Documentation
```

---

## 🔐 How It Works

* User enters email & password
* Email is stored in `localStorage`
* Planner page checks if user is logged in
* If not logged in → redirects to login page
* Tasks are saved using time-based keys

---

## 💡 Future Improvements

* Add real authentication (Firebase / Backend)
* Store tasks per user
* Add task delete/edit options
* Highlight current time slot
* Improve UI/UX (mobile responsive)

---

## 👨‍💻 Author

Yasaswini Samala

---

## 📜 License

This project is for learning purposes.
