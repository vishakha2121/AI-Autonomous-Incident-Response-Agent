# 🚀 AI Autonomous Incident Response Agent

<div align="center">

![Status](https://img.shields.io/badge/status-active-success.svg)
![Python](https://img.shields.io/badge/python-3.10+-blue.svg)
![FastAPI](https://img.shields.io/badge/FastAPI-0.109-009688.svg)
![React](https://img.shields.io/badge/React-18-61DAFB.svg)
![Gemini](https://img.shields.io/badge/Gemini-AI-4285F4.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

**Detect. Diagnose. Resolve. Automatically.**

An AI-powered autonomous SRE agent that detects operational incidents, investigates root causes using Google Gemini LLM, recommends remediation steps, and coordinates response workflows across teams — reducing MTTR from hours to minutes.

[Features](#-features) • [Architecture](#-architecture) • [Tech Stack](#-tech-stack) • [Setup](#-installation--setup) • [Screenshots](#-screenshots) • [API Docs](#-api-endpoints)

</div>

---

## 🎯 Problem Statement

Modern enterprises generate **millions of log lines per hour** across microservices, servers, and applications. When something breaks, engineers waste precious time:

- 🔍 Manually scanning logs to find the root cause
- 📞 Coordinating across multiple teams (DevOps, SRE, Dev, Security)
- 📋 Deciding remediation steps under pressure
- 📊 Documenting incidents for post-mortems

**Result:** Slow incident response, customer impact, and engineer burnout.

---

## 💡 Solution

The **AI Autonomous Incident Response Agent** acts as a 24/7 digital SRE that:

1. **📥 Ingests logs** from multiple sources (nginx, Apache, syslog, application logs)
2. **🔍 Detects incidents** using rule-based pattern matching + anomaly detection
3. **🧠 Investigates root causes** using Google Gemini LLM with multi-step reasoning
4. **🛠️ Recommends remediation** — exact commands, rollback steps, config fixes
5. **🔄 Coordinates response** — auto-assigns teams, escalates, notifies stakeholders
6. **📊 Tracks everything** — dashboard with MTTR, severity trends, recurring patterns

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎯 **Auto Incident Detection** | Scans logs, detects errors, creates incidents automatically |
| 🧠 **AI Root Cause Analysis** | Gemini-powered investigation with confidence scores |
| 🛠️ **Smart Remediation** | Step-by-step fix commands with risk assessment |
| 🔄 **Workflow Automation** | Auto-assign, escalate, notify across teams |
| 📊 **Real-time Dashboard** | Live incident feed, MTTR charts, severity breakdown |
| 🔍 **Log Search & Filter** | Fast full-text search across millions of log lines |
| 👥 **Team Coordination** | Assignment, escalation, notification feeds |
| 📈 **Analytics** | Trends, recurring patterns, service health scores |
| 🌙 **Dark Mode** | Beautiful dark/light theme toggle |
| 📱 **Responsive UI** | Works on desktop, tablet, and mobile |

---

## 🏗️ Architecture



---

## 🛠️ Tech Stack

### **Backend**
- **Python 3.10+** — Core language
- **FastAPI** — Modern async web framework
- **SQLAlchemy** — ORM for database
- **SQLite** — Lightweight database (production: PostgreSQL)
- **Pydantic** — Data validation
- **Uvicorn** — ASGI server
- **Google Gemini API** — LLM for AI analysis

### **Frontend**
- **React 18** — UI library
- **Vite** — Fast build tool
- **TailwindCSS** — Utility-first styling
- **Recharts** — Beautiful charts
- **Axios** — HTTP client
- **React Router** — Navigation
- **Framer Motion** — Smooth animations
- **Lucide React** — Modern icons

### **AI / LLM**
- **Google Gemini 1.5 Flash** — Root cause + remediation
- **Custom Prompt Engineering** — Structured JSON outputs
- **Multi-step Reasoning Chains** — Complex incident analysis

### **Observability**
- Custom log parsers (nginx / apache / syslog / app)
- Regex-based pattern matching
- Rule-based incident detection
- Anomaly detection algorithms

---

## 📂 Project Structure



---

## 🚀 Installation & Setup

### **Prerequisites**

Make sure you have these installed:

- ✅ **Python 3.10+** — [Download](https://www.python.org/downloads/)
- ✅ **Node.js 18+** — [Download](https://nodejs.org/)
- ✅ **Git** — [Download](https://git-scm.com/)
- ✅ **Google Gemini API Key** — [Get Free Key](https://aistudio.google.com/app/apikey)

---

### **🔧 Backend Setup**

**1. Clone the repository**

```bash
git clone https://github.com/vishakha2121/AI-Autonomous-Incident-Response-Agent.git
cd AI-Autonomous-Incident-Response-Agent/backend

# Windows
python -m venv venv
venv\Scripts\activate

# Mac / Linux
python3 -m venv venv
source venv/bin/activate

pip install -r requirements.txt

pip install -r requirements.txt