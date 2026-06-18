# ECDSA Web App

A simple ECDSA Web App built with **Node.js** and **React (Vite)**, following Alchemy University’s blockchain basics course.  
This project demonstrates how to generate private/public keys, derive Ethereum-style addresses, and manage balances using cryptographic primitives.

---

## 🚀 Features
- Generate random private/public key pairs
- Derive Ethereum-style addresses from public keys
- Store balances on the backend (`index.js`)
- Transfer funds between accounts
- Simple React frontend for wallet and transfers

---

## 🛠️ Dependencies

### Backend (server)
- **Node.js** (v16+ recommended)
- **Express** – lightweight server framework
- **cors** – enable cross-origin requests
- **body-parser** – parse JSON requests
- **ethereum-cryptography** – secp256k1 + keccak256 cryptography

Install with:
```bash
cd server
npm install express cors body-parser ethereum-cryptography

