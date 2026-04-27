# LearnSphere AI

## AI-Powered Personalized Learning Ecosystem

LearnSphere AI is a full-stack educational web application designed to improve the student learning experience through AI-assisted study modules, adaptive quizzes, progress tracking, and analytics. Instead of only giving direct answers, the platform encourages understanding, thinking, and continuous improvement.

---

## Project Vision

Students often use multiple disconnected tools for learning, doubt solving, quizzes, and progress tracking. LearnSphere AI combines these into one smart platform where students and lecturers can monitor growth in a structured way.

---

## Core Features

### Student Features

* Secure login and registration
* Personalized learning modules
* Topic-based study workspace
* Ask AI / free AI assistance
* Adaptive quizzes
* Progress dashboard
* Weakness detection through quiz scores
* Performance analytics

### Lecturer Features

* Create classes
* Share class codes
* Monitor enrolled students
* Track progress and quiz results
* Review class analytics

### AI Features

* Rule-based AI response engine
* Topic-based explanations
* Guided learning instead of answer dumping
* Quiz generation by topic
* Memory/history for workspace interactions

---

## Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* Reusable UI components

### Backend

* Node.js
* Express.js

### Database / Storage

* Supabase
* In-memory fallback storage for development mode

### Security

* bcryptjs password hashing
* CORS enabled APIs
* Environment variable configuration

---

## Project Structure

```text
backend/
  controllers/
  models/
  routes/
  config/
  server.js
  aiEngine.js

frontend/
  index.html
  login.html
  student-dashboard.html
  lecturer-dashboard.html
  learning-module.html
  quiz.html
  analytics.html
  app/
  styles/
```

---

## Main Modules

### 1. Learn Module

Students select subjects and topics to create learning modules.

### 2. Ask AI Module

General AI chat support for doubts and concept help.

### 3. Quiz Module

Generates quizzes based on topics and records scores.

### 4. Progress Dashboard

Displays completion status, scores, and improvement trends.

### 5. Analytics Module

Provides insights for lecturers and students.

---

## API Highlights

### Authentication

* `POST /api/register`
* `POST /api/login`

### Modules

* `POST /api/modules`
* `GET /api/modules`
* `GET /api/modules/:id`

### Quiz

* `POST /api/submit-quiz`
* `POST /quiz`

### AI Chat

* `POST /chat`

### Health

* `GET /health`

---

## Installation & Setup

### 1. Clone Project

```bash
git clone <repo-url>
cd learnsphere-ai
```

### 2. Backend Setup

```bash
cd backend
npm install
npm run dev
```

### 3. Configure Environment Variables

Create `.env` inside `backend/`

```env
PORT=5000
SUPABASE_URL=your_url
SUPABASE_KEY=your_key
```

### 4. Open Frontend

Open frontend HTML files in browser or serve using Live Server.

---

## Why This Project Matters

* Encourages deep understanding
* Reduces dependence on multiple platforms
* Helps identify weak topics early
* Improves self-learning habits
* Supports lecturers with real progress data

---

## Future Enhancements

* Real LLM integration (OpenAI / Gemini)
* Voice assistant learning mode
* Multilingual support
* Smart recommendations
* Mobile app version
* Gamification and streaks
* Advanced analytics dashboard

---

## Team Project

Built as an academic prototype under the Education / Software category.

---

## License

For academic and learning purposes.
