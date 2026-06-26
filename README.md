# FIN2FUTURE 💰

A full-stack financial literacy platform that helps users improve their financial knowledge through interactive learning modules, quizzes, budgeting tools, analytics, and AI-powered insights.

---

## Features

### Authentication
- Secure User Registration
- User Login
- JWT Authentication
- Password Encryption using bcrypt
- Protected Routes
- Session Management

### Learning Module
- Interactive Financial Courses
- Lesson Progress Tracking
- Quiz System
- XP & Level Progression
- Continue Learning
- Learning Dashboard

### Personal Finance
- Income Tracking
- Expense Tracking
- Savings Overview
- Budget Management
- Category-wise Analytics
- Monthly Spending Insights

### Additional Features
- AI Insights
- Budget Game
- Financial Books
- Responsive User Interface

---

## Tech Stack

### Frontend
- React.js
- Vite
- JavaScript
- CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- JWT
- bcrypt

### Cloud Storage
- Cloudinary

---

## Project Structure

```
client/
    src/

server/
    config/
    controllers/
    middleware/
    models/
    routes/
    services/
    features/
        auth/
    server.js
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/LingalaSaikrushini/your-repository-name.git
```

Install dependencies

Backend

```bash
cd server
npm install
```

Frontend

```bash
cd client
npm install
```

---

## Environment Variables

Create a `.env` file inside the `server` directory.

Example:

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_api_key

CLOUDINARY_API_SECRET=your_api_secret
```

---

## Running the Project

Start Backend

```bash
cd server
npm run dev
```

Start Frontend

```bash
cd client
npm run dev
```

---

## My Contribution

I contributed to the following modules:

### Authentication
- User Registration
- User Login
- JWT Authentication
- Protected Route Implementation
- Password Encryption

### Learning Module
- Learning Dashboard
- Lesson Navigation
- Quiz System
- Progress Tracking
- XP & Level System
- Continue Learning Feature

---

## Future Enhancements

- Real-time Notifications
- Personalized AI Recommendations
- Financial Goal Tracking
- Advanced Analytics Dashboard

---

## License

This project was developed for educational purposes.
