# AI-Coach-n8n

An end-to-end **AI Learning Coach** built with **n8n automation**. This workflow turns form submissions into a personalized learning roadmap, emails it to the learner, intelligently schedules study sessions in Google Calendar, creates structured notes in Google Docs, and generates quizzes with scoring to track progress.

---

## ✨ Features

* **Form → Roadmap Generation**
  Automatically generates a beginner-friendly, structured learning roadmap based on topic, level, time commitment, and duration.

* **Email Delivery (Gmail)**
  Sends the roadmap directly to the learner’s inbox.

* **Smart Calendar Scheduling**
  Reads Google Calendar availability and creates or updates study events without overbooking.

* **Context-Aware Reminders**
  Sends alerts only when useful (before heavy topics, projects, or tests).

* **Auto Notes in Google Docs**
  Creates and updates a single study document with weekly summaries, key concepts, and action steps.

* **Tests & Scoring**
  Generates quizzes based on completed topics, evaluates answers, assigns scores, and gives feedback.

* **Adaptive Coaching**
  Adjusts pacing and recommendations based on calendar behavior and test performance.

---

## 🧠 How It Works

1. User submits a form with learning preferences
2. AI generates a personalized roadmap
3. Roadmap is emailed via Gmail
4. AI reads the roadmap from email
5. Calendar is analyzed and study events are scheduled
6. Notes are created/updated in Google Docs
7. Tests are generated, scored, and used to guide next steps

---

## 🛠 Tech Stack

* **n8n** – Workflow orchestration
* **AI Agents** – Roadmap planning & execution
* **Gmail API** – Reading & sending emails
* **Google Calendar API** – Event management
* **Google Docs API** – Notes & documentation

---

## 🎯 Use Cases

* Online coaches & mentors
* Educators & training institutes
* EdTech products & SaaS platforms
* Personal learning assistants

---

## 🚀 Setup

1. Clone this repository
2. Import the workflow into n8n
3. Connect Gmail, Google Calendar, and Google Docs credentials
4. Configure form inputs and AI prompts
5. Activate the workflow

---

## 📌 Notes

* Built for extensibility and customization
* Supports custom logic, tools, and advanced AI agents
* Ideal for production-grade learning automation

---

## 📬 Contact

For customization or integration support, feel free to reach out.
