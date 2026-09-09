# 🩺 CuraMind

**AI-Powered Foot Injury Assessment & Care Guidance**

CuraMind is a health-based web application designed to help users identify and assess foot and ankle injuries based on the **Ottawa Ankle Rules (OAR)**. It provides a simple and interactive interface where users can submit their injury-related responses through a chatbot and receive guidance for appropriate care.

The application classifies injuries into three categories:

- 🔴 **Red:** Critical condition requiring urgent medical attention
- 🟡 **Yellow:** Minor condition requiring monitoring or medical consultation
- 🟢 **Green:** Lower-risk condition with basic care guidance

The application is built using **Python Flask** for the backend and **React** for the frontend.

---

## ✨ Features

- 🩺 Analyze foot and ankle injuries using OAR guidelines
- 🤖 Interactive chatbot for injury assessment
- 🚦 Classify injuries into three categories
  - 🔴 Red — Critical
  - 🟡 Yellow — Minor
  - 🟢 Green — Safe
- 💡 Provide appropriate care guidance
- 👨‍⚕️ Real-time communication with doctor
- 📋 Collect and analyze user responses
- 📱 Responsive and user-friendly interface
- ⚡ Fast backend using Flask
- 💻 Interactive frontend using React
- 🗄️ Database support using SQLite / PostgreSQL
- 🔐 Secure communication between frontend and backend

---

## 🛡️ Injury Classification

### 🔴 Red — Critical

Red indicates a potentially serious injury that may require **urgent medical attention**.

### 🟡 Yellow — Minor

Yellow indicates a minor injury where the user may need to **monitor the condition or consult a healthcare professional**.

### 🟢 Green — Safe

Green indicates a lower-risk condition where the user can follow **basic care and monitoring guidance**.

---

## 🔄 System Workflow

```text
User
     ↓
CuraMind React Interface
     ↓
Chatbot / Injury Questionnaire
     ↓
User Responses
     ↓
Flask Backend
     ↓
Ottawa Ankle Rules (OAR)
     ↓
Injury Assessment
     ↓
Injury Classification
     ↓
┌───────────────┬───────────────┬───────────────┐
│ 🔴 Critical   │ 🟡 Minor      │ 🟢 Safe       │
│ Urgent Care   │ Monitor       │ Basic Care    │
└───────────────┴───────────────┴───────────────┘
     ↓
Care Guidance
     ↓
Doctor Communication
     ↓
User

🏗️ System Architecture
CuraMind follows a modular web application architecture consisting of three major layers:
┌──────────────────────────────┐
│       Client Layer           │
│       React Frontend         │
│                              │
│ Chatbot Interface            │
│ Injury Questionnaire         │
│ Injury Results               │
│ Care Guidance                │
│ Doctor Communication         │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│     Application Layer        │
│        Flask Backend         │
│                              │
│ Request Handling             │
│ Injury Assessment            │
│ OAR Rule Processing          │
│ Classification Logic         │
│ Care Guidance                │
│ Doctor Communication         │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│         Data Layer           │
│      SQLite / PostgreSQL     │
│                              │
│ User Data                    │
│ Assessment Data              │
│ Chat Data                    │
└──────────────────────────────┘
🛠️ Tech Stack
Frontend: React, JavaScript, CSS
Backend: Python, Flask
Database: SQLite / PostgreSQL
Medical Assessment: Ottawa Ankle Rules (OAR)
Development Server: Vite / Flask
🚀 Installation & Setup
1. Clone the Repository
git clone https://github.com/yourusername/CuraMind.git
cd CuraMind
2. Backend Setup
Navigate to the backend:
cd backend
Create a Python virtual environment:
python -m venv venv

