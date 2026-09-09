🩺 CuraMind

AI-Powered Foot Injury Assessment & Care Guidance

CuraMind is a health-focused web application designed to help users assess foot and ankle injuries using the Ottawa Ankle Rules (OAR). The application provides an easy-to-use interface where users can submit their symptoms and responses through a chatbot and receive guidance about the appropriate level of care.

CuraMind classifies injury situations into three categories:

🔴 Red — Critical: Requires urgent medical attention
🟡 Yellow — Minor: May require monitoring or medical consultation
🟢 Green — Safe: Lower-risk condition with basic care guidance

The system is built with a Python Flask backend and a React frontend, providing an interactive and responsive experience for users.

✨ Features
🩺 Foot & Ankle Injury Assessment
📋 Ottawa Ankle Rules (OAR) Based Analysis
🤖 Interactive Chatbot Interface
🚦 Three-Level Injury Classification
🔴 Red — Critical
🟡 Yellow — Minor
🟢 Green — Safe
💡 Personalized Care Guidance
👨‍⚕️ Doctor Communication
⚡ Real-Time Communication with Doctor
📱 Responsive User Interface
🔐 Secure Flask Backend
💻 Interactive React Frontend
🗄️ Database Support
🚀 Fast and Lightweight Architecture
🛡️ Injury Classification

CuraMind uses the Ottawa Ankle Rules and user-provided information to help categorize potential injuries.

🔴 Red — Critical

Indicates a potentially serious injury that may require urgent medical evaluation.

🟡 Yellow — Minor

Indicates a lower-severity condition where the user may need to monitor symptoms or consult a healthcare professional.

🟢 Green — Safe

Indicates a lower-risk situation where the application can provide basic care and monitoring guidance.

⚠️ CuraMind is intended as a guidance and screening tool. It does not replace professional medical diagnosis or emergency medical care.

🔄 System Workflow
User
  ↓
CuraMind React Interface
  ↓
Chatbot / Injury Questionnaire
  ↓
User Symptoms & Responses
  ↓
Flask Backend
  ↓
Ottawa Ankle Rules Analysis
  ↓
Injury Classification
  ↓
┌───────────────┬───────────────┬───────────────┐
│ 🔴 Critical   │ 🟡 Minor      │ 🟢 Safe       │
│ Urgent Care   │ Monitor/Care  │ Basic Care    │
└───────────────┴───────────────┴───────────────┘
  ↓
Care Guidance
  ↓
Doctor Communication (if required)
  ↓
User

🏗️ System Architecture

CuraMind follows a client-server architecture consisting of a React frontend, Flask application layer, and database layer.

┌──────────────────────────────┐
│       Client Layer           │
│        React Frontend        │
│                              │
│ Chatbot Interface            │
│ Injury Questionnaire         │
│ Results & Guidance           │
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
│ Classification Engine        │
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
│ Conversation Data            │
└──────────────────────────────┘

🛠️ Tech Stack
Frontend
React
JavaScript
CSS
Vite
Backend
Python
Flask
REST API
Database
SQLite
PostgreSQL
Medical Assessment
Ottawa Ankle Rules (OAR)
🚀 Installation & Setup
1. Clone the Repository
git clone https://github.com/yourusername/CuraMind.git
cd CuraMind

2. Backend Setup

Navigate to the backend directory:

cd backend


Create a Python virtual environment:

python -m venv venv


Activate the virtual environment:

.\venv\Scripts\Activate.ps1


Install the required backend dependencies:

pip install -r requirements.txt

3. Start the Backend

From the backend directory, run:

python app.py


The Flask backend will start running locally.

4. Frontend Setup

Open a new terminal while keeping the backend running.

Navigate to the frontend:

cd frontend


Install the frontend dependencies:

npm i


Start the React development server:

npm run dev

▶️ Running the Complete Project

Both the backend and frontend should be running at the same time.

Terminal 1 — Backend
cd CuraMind\backend
.\venv\Scripts\Activate.ps1
pip install -r requirements.txt
python app.py

Terminal 2 — Frontend
cd CuraMind\frontend
npm i
npm run dev

📁 Project Structure
CuraMind/
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   ├── venv/
│   └── ...
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── .gitignore
└── README.md

💬 How CuraMind Works
👤 The user opens the CuraMind web application.
💬 The user interacts with the chatbot or provides injury-related responses.
🩺 CuraMind analyzes the provided information according to the Ottawa Ankle Rules.
🔎 The system evaluates the injury risk.
🚦 The injury is classified as Red, Yellow, or Green.
💡 CuraMind provides appropriate care guidance.
👨‍⚕️ If required, the user can communicate with a doctor.
🎯 Purpose

The primary goal of CuraMind is to make preliminary foot and ankle injury guidance simple, accessible, and easy to understand.

Instead of requiring users to interpret medical guidelines themselves, CuraMind presents the assessment through a conversational interface and provides a clear risk classification.

⚠️ Medical Disclaimer

CuraMind is an educational and preliminary screening application. It is not a substitute for professional medical diagnosis, examination, or treatment.

If an injury appears severe, symptoms are worsening, or there is an emergency, users should seek appropriate medical care immediately.

👨‍💻 Development

CuraMind is developed using a separate frontend and backend architecture:

React Frontend
      ↓
Flask REST API
      ↓
OAR Assessment Logic
      ↓
Database


This structure makes the application easier to maintain, test, and extend with additional healthcare features in the future.

🌟 Future Enhancements
🤖 Improved AI-based symptom analysis
🩻 Medical image analysis
👨‍⚕️ Advanced doctor consultation
📱 Mobile application
📊 Patient assessment history
🔔 Medical reminders and notifications
🌐 Multi-language support
🔐 Enhanced authentication and privacy controls
🩺 CuraMind

Understand → Assess → Classify → Guide → Connect

CuraMind aims to make preliminary injury assessment more accessible while helping users understand when professional medical care may be needed.
