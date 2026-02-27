# 💳 Offline Pay Backend

Backend service for an Offline Digital Payment System inspired by UPI Lite.

This system allows users to generate cryptographically signed offline vouchers for QR-based merchant payments and securely sync transactions to the cloud once internet connectivity is restored.

---

## 🚀 Features

- 🔐 JWT-based Authentication (User & Merchant)
- 📱 Indian Phone Number Validation (10-digit format)
- 💰 Wallet Balance Management
- 🧾 Offline Voucher Generation
- 🛡 Digital Signature Verification
- 🚫 Double-Spend Protection
- 📊 Transaction History Tracking
- ☁ MongoDB Atlas Cloud Database
- 🌍 Deployed on Render

---

## 🏗 Architecture Overview

User App (React Native)  
        ↓  
Backend API (Node.js + Express)  
        ↓  
MongoDB Atlas (Cloud Database)

Offline vouchers are signed on-device and verified by the backend during settlement.

---

## 🔐 Security Model

- Private/Public key cryptography
- Voucher integrity verification
- Unique voucher ID validation
- Server-side double-spend prevention
- Secure password hashing
- Token-based authentication

---

## 🛠 Tech Stack

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT
- bcrypt
- Render (Cloud Deployment)

---

## 📦 Installation (Local Development)

```bash
git clone https://github.com/YOUR_USERNAME/offline-pay-backend.git
cd offline-pay-backend
npm install
