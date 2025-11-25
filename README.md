<<<<<<< HEAD
# Murf-AI-Voice-Agent
=======
# ten-days-of-voice-agents-2025Day4
>>>>>>> da1fb685b462d850a55ff7da8f040e2585fa38a4

🧠 Day 4 — Teach-the-Tutor: Active Recall Voice Coach
Built for Murf AI Voice Agent Challenge 2025
Powered by Murf Falcon (Fastest TTS API) + LiveKit Agents
🚀 Overview

This project implements the Teach-the-Tutor: Active Recall Coach for Day 4 of the Murf AI Voice Agent Challenge.

The agent helps users learn better by using Active Recall, where the user must teach the concept back to the agent.

The system includes three learning modes:

🎓 Learning Modes
1️⃣ Learn Mode (Voice: Matthew)

The agent explains a concept using the JSON content file.

2️⃣ Quiz Mode (Voice: Alicia)

The agent asks a question related to the concept.

3️⃣ Teach-Back Mode (Voice: Ken)

The agent asks the user to explain the concept back and gives basic feedback.

These modes can be switched anytime during the conversation.




The agent uses this file for:

Explanations (Learn Mode)

Asking questions (Quiz Mode)

Teach-back prompts (Teach-Back Mode)

✅ Features Completed (Day-4 Requirements)

✔ Agent greets and asks for learning mode
✔ Learn, Quiz, and Teach-Back modes implemented
✔ User can switch modes anytime
✔ JSON-driven content for all modes
✔ Murf Falcon voices (Matthew, Alicia, Ken)
✔ Backend + frontend working together
✔ Real-time voice via LiveKit
✔ Ready for LinkedIn submission

🛠 Tech Stack

LiveKit Agents (real-time audio interaction)

Murf Falcon TTS API (multi-voice synthesis)

Next.js (frontend UI)

Python (backend logic)

WebSockets / Streaming Audio

▶ How to Run the Project Locally
1️⃣ Install Dependencies
Backend
pip install -r requirements.txt

Frontend
npm install
# or
pnpm install

2️⃣ Create .env File
MURF_API_KEY=your_murf_falcon_api_key
LIVEKIT_API_KEY=your_livekit_key
LIVEKIT_API_SECRET=your_livekit_secret

3️⃣ Start the Application
./start_app.sh

4️⃣ Open in Browser
http://localhost:3000


Allow microphone access and try all 3 learning modes.



#MurfAIVoiceAgentsChallenge
#10DaysofAIVoiceAgents

Built with
🔥 Murf Falcon — The Fastest TTS API
🎧 LiveKit — Real-time Voice Agents
