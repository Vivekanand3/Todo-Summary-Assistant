# 📝 Todo Summary Assistant

A full-stack Todo application that allows users to manage tasks and summarizes todo content using AI. This project was built as part of the Leucine.io evaluation process.

---

## 📌 Candidate Info

- **Name**: Vivekanand  
- **College/Vendor**: RGUKT RkValley  
- **Submission Role**: Fullstack  
- **GitHub Repo**: [https://github.com/Vivekanand3]

---

## 🚀 Features

- ✅ Add, update, and delete todos
- ✅ Mark todos as complete/incomplete
- ✅ Generate summary of todos (AI-assisted)
- ✅ API integration with OpenRouter/OpenAI
- ✅ Slack notifications for updates
- ✅ Robust MongoDB backend with retry logic
- ✅ Environment variable configuration via `.env`

---

## 🧱 Tech Stack

### Backend
- Node.js + Express.js
- MongoDB + Mongoose
- dotenv, CORS, OpenAI API

### Frontend (in `client/`)
- React (TypeScript or JavaScript)
- Material UI (MUI)
- Axios for HTTP requests

---

## 📁 Folder Structure

todo-summary-assistant/
│
├── server.js # Entry point of backend

├── .env # Environment variables

├── package.json # Node project info


├── /server/  


│ └── routes/ 

│ └── todos.routes.js # API routes 

│
├── /client/ # React frontend (if present) 

│ └── src/

│ └── components/

│ └── App.js

│
└── README.md




yaml

---

## ⚙️ Environment Setup

Create a `.env` file in the root and add:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
OPENROUTER_API_KEY=your_openrouter_key
SITE_URL=http://localhost:3000
SITE_NAME=Todo Summary Assistant
SLACK_WEBHOOK_URL=https://hooks.slack.com/services/xxx/yyy/zzz
SLACK_DEFAULT_CHANNEL=#general
SLACK_BOT_NAME=TODO App Bot
⚠️ Don't share .env publicly. This file is for local configuration only.

🛠️ How to Run Locally
Clone the repository

bash

git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
Install backend dependencies

bash


npm install
Start backend server

bash

npm run server
(Optional) If you have a client/ frontend, open new terminal:

bash



cd client
npm install
npm start

Visit in browser
http://localhost:3000


API Endpoints
Method	Endpoint	Description
GET	/api/todos	Get all todos
POST	/api/todos	Create a new todo
PUT	/api/todos/:id	Update todo completion
DELETE	/api/todos/:id	Delete a todo


License
Submitted solely for evaluation by Leucine.io. All rights reserved by the author.

yaml


---





## ✅ How to Push Your Project to GitHub

### 🔧 1. Create a GitHub Repo
- Go to [GitHub](https://github.com/)
- Click **+ → New Repository**
- Set:
  - **Repo name**: `todo-summary-assistant`
  - Visibility: `Public`
  - **Do not add README**

---




### 🖥️ 2. Push Local Code to GitHub

Open terminal in your project folder:

```bash
git init
git add .
git commit -m "Initial commit - Leucine Assignment"
git remote add origin https://github.com/YOUR_USERNAME/todo-summary-assistant.git
git branch -M main
git push -u origin main

