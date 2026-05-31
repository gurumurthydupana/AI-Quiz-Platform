# 🚀 AI Quiz Platform

An AI-powered Quiz Management Platform built using the MERN Stack that enables educators to create, manage, and evaluate quizzes efficiently while providing students with an interactive learning experience.

## 📌 Overview

AI Quiz Platform is designed to simplify quiz creation and assessment processes. Teachers can generate quizzes manually or automatically using AI from uploaded study materials, while students can participate in quizzes, view results, and track their learning progress.

---

## ✨ Features

### 👨‍🏫 Teacher Features
- Secure Registration and Login
- Create and Manage Batches
- Upload Learning Materials
- AI-Powered Quiz Generation
- Manual Quiz Creation
- Manage Published Quizzes
- View Student Performance
- Leaderboard Management
- Dashboard Analytics

### 👨‍🎓 Student Features
- Secure Registration and Login
- Join Batches Using Batch Codes
- Attempt Quizzes
- Instant Result Evaluation
- Performance Tracking
- View Quiz History
- AI-Based Doubt Assistance

### 🤖 AI Features
- Generate MCQ Quizzes from Uploaded Documents
- AI-Based Doubt Resolution
- Intelligent Question Generation
- Automated Learning Assistance

### 🔒 Security Features
- JWT Authentication
- Role-Based Access Control
- Protected Routes
- Secure API Access

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- Axios
- React Router

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### Authentication
- JSON Web Tokens (JWT)

### Additional Tools
- Redis
- Docker
- Docker Compose
- Swagger API Documentation

### AI Integration
- OpenAI API / LLM Integration

---

## 📂 Project Structure

```bash
AI-Quiz-Platform
│
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── context
│   │   └── api
│   └── public
│
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   ├── config
│   └── swagger
│
├── reference
│
├── docker-compose.yml
├── package.json
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/gurumurthydupana/AI-Quiz-Platform.git

cd AI-Quiz-Platform
```

---

## Backend Setup

```bash
cd backend

npm install
```

Create a `.env` file:

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

OPENAI_API_KEY=your_openai_api_key

REDIS_URL=your_redis_url
```

Start Backend:

```bash
npm start
```

---

## Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend:

```text
http://localhost:5173
```

Backend:

```text
http://localhost:5000
```

---

## 🐳 Docker Setup

Run the complete application using Docker:

```bash
docker-compose up --build
```

---

## 📖 API Documentation

Swagger Documentation:

```text
http://localhost:5000/api-docs
```

---

## 🔄 Application Workflow

### Teacher Workflow

1. Register/Login
2. Create Batch
3. Upload Study Material
4. Generate Quiz Using AI
5. Publish Quiz
6. Monitor Student Performance

### Student Workflow

1. Register/Login
2. Join Batch
3. Attempt Quiz
4. View Results
5. Track Progress
6. Ask Questions via AI Assistant

---

## 📊 Key Functionalities

- AI-Based Quiz Generation
- Role-Based Authentication
- Batch Management System
- Quiz Performance Tracking
- Student Result Analytics
- Leaderboard Generation
- Doubt Resolution System
- Secure REST APIs

---

## 🚀 Future Enhancements

- Adaptive Learning Recommendations
- Real-Time Quiz Competitions
- Advanced Analytics Dashboard
- Mobile Application
- Voice-Based Quiz Interaction
- Multi-Language Support

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add feature"
```

4. Push to the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 👨‍💻 Author

### Gurumurthy Dupana

- GitHub: https://github.com/gurumurthydupana
- Email: guruspams0@gmail.com

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

### Built with ❤️ using MERN Stack, Docker, Redis, and AI-Powered Quiz Generation.
