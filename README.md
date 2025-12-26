# Daily-Checklist-Web-App-A-Neon-Command-Center-for-Discipline
#Overview

In the labyrinth of daily life—coding, university, gym, and personal ambitions—I needed a system that truly holds me accountable. This is not a typical to-do list; it’s a discipline enforcement system, designed to track tasks, streaks, and consistency while giving actionable AI feedback, all wrapped in a futuristic neon UI.

#Features

#Main Tasks:
Coding, Studying, Praying, Eating Healthy, No Fap

#Side Tasks:
Gym, Machine Learning Concepts, Deep Learning, Reinforcement Learning, Agentic

#Neon Futuristic UI:
Dark theme with neon highlights for focus and clarity

#Daily Progress & Streaks:
Tracks task completion and consecutive days of consistency

#AI Feedback:
Provides honest insights about missed tasks and patterns

#Weekly Trends:
Visualizes Main vs Side task completion over time

#Time-Restricted Tasks:
Tasks can only be completed within their scheduled time windows

#Tech Stack

#Frontend: HTML, CSS, JavaScript

#Backend: FastAPI + SQLite

#Optional AI: OpenAI API for personalized feedback

#Installation & Setup

Clone the repository

git clone https://github.com/yourusername/daily-checklist-webapp.git
cd daily-checklist-webapp


#Create virtual environment

python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows


#Install dependencies

pip install -r requirements.txt


#Run the backend

uvicorn main:app --reload --host 127.0.0.1 --port 8000


#Run the frontend

python -m http.server 3000

#Usage

Open the frontend URL (http://127.0.0.1:3000)

Tick your daily tasks within their time windows

Watch streaks and AI feedback update in real-time

Review your history page for progress and trends

#Future Enhancements

Gamified streak rewards

Push notifications for missed tasks

Expanded AI analysis with personalized recommendations

Mobile-friendly responsive UI

#Author

Visionary – Passionate about AI, self-improvement, and full-stack development.

License

MIT License – feel free to use, modify, and learn from this project.
