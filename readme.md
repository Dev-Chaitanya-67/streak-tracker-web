<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=250&section=header&text=STREAK%20TRACKER&fontSize=55&fontColor=ffffff&animation=twinkling&fontAlignY=40"/>
</p>

<h1 align="center">🚀 Ultimate Productivity Companion Tool</h1>

<p align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=26&duration=2500&pause=1000&color=36BCF7&center=true&vCenter=true&width=700&lines=Track+Your+Habits;Build+Unbreakable+Streaks;Focus+Better+Everyday;Consistency+Creates+Success" />

</p>

---

<p align="center">

<img src="https://img.shields.io/badge/Node.js-%3E%3D18-0d1117?style=for-the-badge&logo=node.js"/>
<img src="https://img.shields.io/badge/React-19.2.0-0d1117?style=for-the-badge&logo=react"/>
<img src="https://img.shields.io/badge/MongoDB-7.0-0d1117?style=for-the-badge&logo=mongodb"/>
<img src="https://img.shields.io/badge/Vite-7-0d1117?style=for-the-badge&logo=vite"/>
<img src="https://img.shields.io/badge/License-MIT-0d1117?style=for-the-badge"/>

</p>

<p align="center">
A modern full-stack productivity platform designed to transform daily habits into powerful streaks.
Built with <b>React, Node.js, MongoDB, and Vite</b> — focused on performance, simplicity, and developer experience.
</p>

---

<img src="https://user-images.githubusercontent.com/74038190/212750102-3c3d8a3c-bb0f-4c6f-a35c-88e42a86a8b2.gif" width="100%">

# 🎥 Live Demo

<p align="center">

<img src="https://user-images.githubusercontent.com/demo/streak-demo.gif" width="900"/>

</p>

---

# ✨ Core Features

| Feature                  | Description                                    |
| ------------------------ | ---------------------------------------------- |
| 🔐 Secure Authentication | JWT authentication with bcrypt hashing         |
| ⏱ Pomodoro Focus Timer   | Deep work sessions with customizable intervals |
| 📊 Habit Tracking        | Maintain daily / weekly productivity streaks   |
| 📝 Digital Journal       | Store reflections and insights                 |
| ✅ Task Manager           | Manage tasks with priority & deadlines         |
| 📈 Live Analytics        | Productivity dashboard with charts             |
| 🎵 Ambient Focus Audio   | Background sounds for deep work                |

---

# 🎨 User Experience

* 🌙 **Dark / Light mode**
* 📱 **Fully responsive UI**
* ⚡ **Real-time data updates**
* 🎯 **Gamification system**
* 📊 **Interactive productivity charts**
* 🔍 **Advanced filtering**

---

<img src="https://user-images.githubusercontent.com/74038190/212744275-89eae0a2-fc90-4e1d-9b4a-10c53c7b7f64.gif" width="100%">

# 🛠 Tech Stack

<p align="center">

<img src="https://skillicons.dev/icons?i=react,nodejs,express,mongodb,tailwind,vite,js,git,github"/>

</p>

### Stack Overview

| Layer    | Technology        |
| -------- | ----------------- |
| Frontend | React 19 + Vite   |
| Backend  | Node.js + Express |
| Database | MongoDB           |
| Styling  | Tailwind CSS      |
| Auth     | JWT               |

---

# 🧠 Architecture

```id="arc1"
streak-tracker
│
├── server
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   └── index.js
│
└── client
    ├── components
    ├── pages
    ├── context
    └── assets
```

---

<img src="https://user-images.githubusercontent.com/74038190/212743909-3c5037bd-34f6-4a6e-bc2f-ec6dfd1c72f3.gif" width="100%">

# 🚀 Getting Started

## Prerequisites

```id="req"
Node.js >= 18
MongoDB
npm / yarn
```

---

## Installation

### Clone the Repository

```bash id="clone"
git clone https://github.com/yourusername/streak-tracker.git
cd streak-tracker
```

---

### Backend Setup

```bash id="backend"
cd server
npm install
cp .env.example .env
npm run dev
```

Backend runs at

```id="api"
http://localhost:5000
```

---

### Frontend Setup

```bash id="frontend"
cd ../streak-tracker
npm install
npm run dev
```

Frontend runs at

```id="web"
http://localhost:5173
```

---

# ⚙ Environment Variables

### Backend

```env id="env1"
PORT=5000
MONGODB_URI=mongodb://localhost:27017/streaktracker
JWT_SECRET=your_secret_key
NODE_ENV=development
```

### Frontend

```env id="env2"
VITE_API_BASE_URL=http://localhost:5000/api
```

---

<img src="https://user-images.githubusercontent.com/74038190/212744275-89eae0a2-fc90-4e1d-9b4a-10c53c7b7f64.gif" width="100%">

# 📡 API Overview

<details>
<summary>Authentication</summary>

```
POST /api/auth/register
POST /api/auth/login
GET /api/auth/profile
PUT /api/auth/profile
```

</details>

<details>
<summary>Habits</summary>

```
GET /api/habits
POST /api/habits
PUT /api/habits/:id
DELETE /api/habits/:id
POST /api/habits/:id/log
```

</details>

<details>
<summary>Focus Sessions</summary>

```
GET /api/focus
POST /api/focus
GET /api/focus/stats
```

</details>

---

# 🧪 Testing

```id="test"
cd streak-tracker
npm run lint

cd ../server
npm test
```

---

# 🚢 Deployment

### Backend

```bash id="deploy1"
cd server
npm start
```

### Frontend

```bash id="deploy2"
cd streak-tracker
npm run build
```

---

<img src="https://user-images.githubusercontent.com/74038190/212744275-89eae0a2-fc90-4e1d-9b4a-10c53c7b7f64.gif" width="100%">

# 📊 Repository Stats

<p align="center">

<img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=tokyonight"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=tokyonight"/>

</p>

---

# 📈 Contribution Activity

<p align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=yourusername&theme=react-dark"/>

</p>

---

# 🤝 Contributing

```bash id="contrib"
git checkout -b feature/new-feature
git commit -m "Add new feature"
git push origin feature/new-feature
```

Open a Pull Request 🚀

---

# ❤️ Author

<p align="center">

Made with ❤️ by **Chaitanya**

⭐ Star this repository if you like the project!

</p>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=120&section=footer"/>
</p>
