# WorkBoard – Agile Task & Team Tracker

A kanban-style task tracking app for agile teams. It supports task management, GitHub commit stats, and CI/CD visibility.

## 🔗 Live Demo
👉 [Click here to view the deployed app](https://workBoard.vercel.app) *(replace with your actual Vercel link)*

## 🚀 Features
- Drag-and-drop kanban board (To Do, In Progress, Done)
- Task creation, editing, and assignment
- GitHub activity integration using GitHub API
- GitHub Actions support for CI/CD tracking
- PostgreSQL-backed data storage
- Dockerized backend for easy deployment

## 🛠️ Tech Stack
- **Frontend:** React, TailwindCSS, react-beautiful-dnd
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL (Supabase or Render)
- **Integrations:** GitHub API, GitHub Actions, Docker

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/DherajK2/workBoard.git
cd workBoard

# Install dependencies
npm install

# Start the app
npm run dev

## 📁 Folder Structure
workBoard/
├── client/         # React frontend
├── server/         # Node.js backend
├── README.md
└── LICENSE

## ⚙️ Environment Variables
GITHUB_TOKEN=your_github_token
DATABASE_URL=your_postgres_connection_url



