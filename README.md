# 🏦 Bank Management System

A responsive web-based **Bank Management System** built using **HTML, CSS, JavaScript, Bootstrap**, and **Firebase**. It simulates core banking operations such as account creation, fund transfers, balance inquiry, and transaction tracking using Firebase Realtime Database and Authentication.

## 🌐 Live Demo

👉 [Click here to view the live project](https://sathvik1404.github.io/Bankproject/)

## 🧰 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap
- **Backend/Database**: Firebase (Authentication + Realtime Database)

## 🔐 Features

### 🧑‍💼 User Functionalities
- User Registration and Login (via Firebase Auth)
- Dashboard with account summary
- Deposit and withdrawal operations
- Fund transfer to another account
- Real-time balance updates
- Transaction history tracking

### 🔒 Security
- Firebase Authentication for secure login/signup
- Data storage and rules managed via Firebase Realtime Database
- Basic input validation and error handling


## 🔧 Getting Started

### Prerequisites
- Basic web development environment (browser + code editor)
- Firebase account (for Authentication and Realtime Database)

### Setup

1. Clone the repository:
```bash

git clone https://github.com/Sathvik-Goli/BankProject.git
cd BankProject
Open Firebase console and create a new project.

Set up Firebase:

Enable Authentication > Email/Password

Create a Realtime Database and set rules

Go to Project Settings > General > Firebase SDK snippet, and copy the config

Replace the Firebase config in your js/firebase-config.js file:

js
Copy
Edit
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
  databaseURL: "https://YOUR_PROJECT_ID.firebaseio.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT_ID.appspot.com",
  messagingSenderId: "SENDER_ID",
  appId: "APP_ID"
};
Run the app by opening index.html in your browser (no backend/server needed).
