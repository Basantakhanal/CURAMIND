# 🩺 CuraMind

CuraMind is a health-focused web application designed to help users assess foot and ankle injuries based on the **Ottawa Ankle Rules (OAR)**. It provides an interactive chatbot interface where users can submit information about their injury and receive guidance for appropriate care.

The application analyzes user responses and classifies injuries into three categories: **Red for Critical, Yellow for Minor, and Green for Safe**. CuraMind also provides care guidance and enables users to communicate with a doctor when professional medical assistance is required.

---

## ✨ Features

- 🩺 Foot and Ankle Injury Assessment
- 🤖 Interactive Injury Assessment Chatbot
- 🔎 Ottawa Ankle Rules (OAR) Based Analysis
- 🚦 Three-Level Injury Classification
  - 🔴 Red — Critical
  - 🟡 Yellow — Minor
  - 🟢 Green — Safe
- 💡 Appropriate Care Guidance
- 👨‍⚕️ Real-Time Communication with Doctor
- 📋 User Response Collection and Analysis
- 📱 Responsive and User-Friendly Interface
- ⚡ Fast Flask Backend
- 💻 Interactive React Web Interface
- 🗄️ SQLite / PostgreSQL Database Support
- 🔐 Secure Frontend and Backend Communication

---

## 🛡️ Injury Classification

### Critical — Red

In Critical mode, the system identifies injury conditions that may require urgent medical attention based on the provided symptoms and OAR assessment.

### Minor — Yellow

In Minor mode, the system identifies lower-severity injuries that may require monitoring, basic care, or consultation with a healthcare professional.

### Safe — Green

In Safe mode, the system identifies lower-risk conditions and provides basic care and monitoring guidance.

---

## 🔄 System Workflow

```text
User Prompt
     ↓
CuraMind React Frontend
     ↓
Injury Chatbot / Questionnaire
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
Final Response
     ↓
User
```

---

# 🏗️ System Architecture

CuraMind follows a modular healthcare web application architecture consisting of three major layers:

``` text
┌──────────────────────────────┐
│       Client Layer           │
│      React Frontend          │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│     Application Layer        │
│       Flask Backend          │
│                              │
│ Injury Assessment            │
│ OAR Rule Processing          │
│ Classification Engine        │
│ Care Guidance                │
│ Chatbot Processing           │
│ Doctor Communication         │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│         Data Layer           │
│    SQLite / PostgreSQL       │
│                              │
│ User Data                    │
│ Assessment Data              │
│ Conversation Data            │
└──────────────┬───────────────┘
               ↓
        Doctor / User
```

---

# 🚀 Installation & Setup


---

## 1. Clone the Repository

```bash
git clone <https://github.com/Basantakhanal/CURAMIND.git>
cd CURAMIND
```

---

# 2. Backend Setup

Navigate to the backend:

```powershell
cd backend
```

Create a Python virtual environment:

```powershell
python -m venv venv
```

Activate the virtual environment:

```powershell
.\venv\Scripts\Activate.ps1
```

Upgrade pip:

```powershell
python -m pip install --upgrade pip
```

Install all backend dependencies:

```powershell
pip install -r requirements.txt
```

---


# 4. Start the Backend

From the `backend` directory, run:

```powershell
python app.py
```


# 5. Frontend Setup

Open a **new terminal** while keeping the backend running.

Navigate to the frontend:

```powershell
cd frontend
```

Install frontend dependencies:

```powershell
npm install
```

Start the development server:

```powershell
npm run dev
```


# ▶️ Running the Complete Project

Both the backend and frontend must be running at the same time.

### Terminal 1 — Backend

```powershell
cd CURAMIND\backend
.\venv\Scripts\Activate.ps1
pytjon app.py
```

### Terminal 2 — Frontend

```powershell
cd CURAMIND\frontend
npm install
npm run dev
```

# 📁 Project Structure

```text
CuraMind/
│
├── backend/
│   ├── app.py
│   │
│   ├── requirements.txt
│   ├── .env
│   └── venv/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── .gitignore
└── README.md
```
## 🩺 CuraMind
**Smart Foot Injury Assessment and Care Guidance System**

> Assess → Classify → Guide → Connect



