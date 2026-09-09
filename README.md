🩺 CuraMind

AI-Powered Foot Injury Assessment & Care Guidance

CuraMind is a health-based web application designed to help users identify foot injuries based on the Ottawa Ankle Rules (OAR). It provides a simple and interactive interface where users can submit their injury-related responses through a chatbot and receive guidance for proper care.

The application classifies injuries into three categories:

🔴 Red: Critical
🟡 Yellow: Minor
🟢 Green: Safe

CuraMind is built using Python Flask for the backend and React for the frontend.

✨ Features
🩺 Analyze foot injuries using OAR guidelines
🤖 Interactive chatbot for injury assessment
🚦 Classify injuries into three categories
🔴 Red — Critical
🟡 Yellow — Minor
🟢 Green — Safe
💡 Provide appropriate care guidance
👨‍⚕️ Real-time communication with doctor
📋 Collect and analyze user responses
📱 Responsive and user-friendly interface
⚡ Fast backend using Flask
💻 Interactive frontend using React
🗄️ Database support using SQLite / PostgreSQL
🔐 Secure communication between frontend and backend
🛡️ Injury Classification
🔴 Red — Critical

Indicates a potentially serious injury that may require urgent medical attention.

🟡 Yellow — Minor

Indicates a minor injury that may require monitoring or consultation with a healthcare professional.

🟢 Green — Safe

Indicates a lower-risk condition where basic care and monitoring guidance can be followed.

🔄 System Workflow
User
     ↓
CuraMind React Frontend
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


Activate the virtual environment:

.\venv\Scripts\Activate.ps1


Install all backend dependencies:

pip install -r requirements.txt

3. Start the Backend

From the backend directory, run:

python app.py

4. Frontend Setup

Open a new terminal while keeping the backend running.

Navigate to the frontend:

cd frontend


Install frontend dependencies:

npm i


Start the development server:

npm run dev

▶️ Running the Complete Project

Both the backend and frontend must be running at the same time.

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
User opens the CuraMind web application.
User interacts with the chatbot.
User provides information about their foot injury.
The information is sent to the Flask backend.
The backend evaluates the responses using Ottawa Ankle Rules.
CuraMind determines the injury severity.
The injury is classified as Red, Yellow, or Green.
Appropriate care guidance is displayed.
If required, the user can communicate with a doctor.
👨‍⚕️ Doctor Communication

CuraMind provides a communication feature that allows users to connect with a doctor when professional medical guidance is required.

Users can:

Share injury-related information
Discuss symptoms
Receive professional guidance
Seek further medical evaluation
🎯 Purpose

The main purpose of CuraMind is to provide users with a simple and accessible way to understand the potential severity of a foot injury using the Ottawa Ankle Rules.

The application converts user responses into a clear classification and provides guidance about the next appropriate step.

⚠️ Medical Disclaimer

CuraMind is intended for preliminary assessment and informational purposes only.

It does not replace professional medical diagnosis, physical examination, or treatment. If an injury appears severe, symptoms are worsening, or the user experiences an emergency, professional medical care should be sought immediately.

🔮 Future Enhancements
🤖 Advanced AI-powered symptom analysis
🩻 Medical image analysis
👨‍⚕️ Improved doctor consultation
📱 Mobile application
📊 Patient assessment history
🔔 Medical reminders and notifications
🌐 Multi-language support
🔐 Enhanced authentication and privacy
📈 Health analytics dashboard
🩺 CuraMind

Assess → Classify → Guide → Connect

CuraMind aims to make preliminary foot injury assessment simple, accessible, and easy to understand while helping users identify when professional medical care may be required.
