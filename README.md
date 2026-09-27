\# 🤖 Smart AI Meeting Assistant



An AI-powered meeting intelligence platform designed to convert meeting conversations into structured and actionable insights.



\## 🚀 Features



\- 🎙️ Meeting audio processing

\- 📝 Speech transcription

\- 👥 Speaker diarization

\- 🧠 AI-powered meeting analysis

\- 📌 Key point extraction

\- ✅ Action item identification

\- 🎯 Decision extraction

\- 😊 Sentiment analysis

\- 📊 Meeting scoring and analytics

\- 📄 Automated PDF report generation

\- 🔐 User authentication

\- 🔄 Real-time processing updates

\- 🌐 React web interface

\- 🔌 FastAPI backend

\- 🐳 Docker support



\## 🏗️ System Architecture



```text

Meeting Audio

&#x20;    │

&#x20;    ▼

Audio Processing

&#x20;    │

&#x20;    ▼

Speech Transcription

&#x20;    │

&#x20;    ▼

Speaker Diarization

&#x20;    │

&#x20;    ▼

Transcript Processing

&#x20;    │

&#x20;    ▼

AI Meeting Analysis

&#x20;    │

&#x20;    ├── Summary

&#x20;    ├── Key Points

&#x20;    ├── Decisions

&#x20;    ├── Action Items

&#x20;    ├── Sentiment

&#x20;    └── Meeting Score

&#x20;    │

&#x20;    ▼

PDF Report \& Insights

```



\## 📂 Project Structure



```text

smart-ai-meeting-assistant/

│

├── backend/

│   ├── app/

│   │   ├── core/

│   │   ├── database/

│   │   ├── routers/

│   │   ├── schemas/

│   │   └── services/

│   ├── reports/

│   ├── requirements.txt

│   └── test\_\*.py

│

├── frontend/

│   ├── public/

│   ├── src/

│   │   ├── components/

│   │   ├── context/

│   │   ├── pages/

│   │   └── services/

│   ├── package.json

│   └── vite.config.js

│

├── docs/

├── docker-compose.yml

├── test\_pipeline.py

├── .gitignore

└── README.md

```



\## ⚙️ Installation



\### 1. Clone the Repository



```bash

git clone https://github.com/vitthalpatidar07-create/smart-ai-meeting-assistant.git

cd smart-ai-meeting-assistant

```



\### 2. Backend Setup



Create a virtual environment:



```bash

python -m venv venv

```



Windows:



```bash

venv\\Scripts\\activate

```



Install dependencies:



```bash

cd backend

pip install -r requirements.txt

```



Start the backend:



```bash

uvicorn app.main:app --reload

```



\### 3. Frontend Setup



Open another terminal:



```bash

cd frontend

npm install

npm run dev

```



\## 🔐 Environment Variables



Create a local `.env` file for required API keys and configuration.



\*\*Never commit API keys, passwords, tokens, or other secrets to GitHub.\*\*



\## 🧪 Testing



Run the main pipeline test:



```bash

python test\_pipeline.py

```



Additional backend tests are available in the `backend` directory.



\## 🎯 Use Cases



\- Corporate meetings

\- Team discussions

\- Project meetings

\- Client meetings

\- Interviews

\- Academic discussions

\- Meeting documentation

\- Post-meeting analysis



\## 🔮 Future Improvements



\- Real-time multilingual transcription

\- Advanced speaker identification

\- Calendar integration

\- Cloud deployment

\- Semantic meeting search

\- Advanced analytics dashboard

\- Email delivery of reports

\- Team collaboration



\## 👨‍💻 Author



\*\*Vitthal Patidar\*\*



B.Tech — Artificial Intelligence \& Machine Learning



Indore, Madhya Pradesh, India



\---

