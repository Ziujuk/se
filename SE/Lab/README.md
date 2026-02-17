
# 🎬 Online Movie Rental Management Platform

This is a full-stack web application that allows users to rent movies online. Users can register, browse a catalog of movies and series, rent titles via one-time payments or monthly subscriptions, and stream content across various devices.

## 🚀 Features

- User registration and login
- Browse and filter movies by genre, rating, and release date
- One-time rentals and subscription-based access
- Intelligent recommendation engine
- Secure online payments (Stripe/PayPal)
- High-quality video streaming
- Responsive design for desktop, tablet, and mobile

## 🛠️ Technologies

### Frontend:
- React.js
- Tailwind CSS
- Axios

### Backend:
- Node.js
- Express.js
- PostgreSQL
- JWT for authentication

## 📂 Project Structure

```
MovieRentalSystem/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── .env.example
├── frontend/
│   ├── public/
│   ├── src/
│   └── package.json
├── README.md
```

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/Ziujuk/se.git
cd movie-rental-system
```

2. Set up the backend:
```bash
cd backend
npm install
cp .env.example .env
# Fill in DB connection and JWT secret in .env
npm start
```

3. Set up the frontend:
```bash
cd frontend
npm install
npm run dev
```

## 🧪 Testing

- Backend: Jest + Supertest
- Frontend: React Testing Library + Cypress (for E2E)

## 👤 Author

Jakub Juziuk

## 📃 License

This project is for educational purposes only.
