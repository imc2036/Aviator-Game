# Aviator Crash Game

This is a full-stack Aviator-style crash game built using React (frontend) and Node.js + Express + MongoDB (backend).

## Features

- User authentication (register/login)
- Deposit and withdraw system
- Real-time crash engine
- Betting and payout logic
- View last 10 bets
- Responsive UI with time and round tracking

## Project Structure

- `frontend/` – React frontend with real-time crash game UI
- `backend/` – Node.js API server and MongoDB integration

## Getting Started

### Backend

```bash
cd backend
npm install
# Add a .env file with your MongoDB URI and JWT_SECRET
node server.js
