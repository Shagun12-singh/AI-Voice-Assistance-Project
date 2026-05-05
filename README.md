# AI-Voice-Assistance-Project
SISA AI is a sophisticated, secure, and sentiment-aware digital assistant built for my final-year project. Unlike traditional voice assistants, SISA focuses on Voice Biometrics, ensuring that the system only responds to authorized users. It features a modern, decoupled architecture with a high-performance Python backend and a sleek, responsive React.js frontend.
​🚀 Key Features
​Designed and developed a cross-platform voice assistant using React.js for the UI and Python for the backend logic. 
• Integrated Speech-to-Text (STT) and Text-to-Speech (TTS) libraries for real-time human-computer interaction. 
 Implemented SpeechRecognition and connected APIs to handle voice commands for task automation.
 ​🛠️ Technology Stack
​Frontend: React.js (Hooks, Tailwind CSS for Glassmorphism UI)
​Backend: Python, FastAPI (for high-performance asynchronous API calls)
​🏗️ System Architecture
​The project follows a Decoupled Architecture:
​Client Layer: The React.js frontend captures audio and handles the visual state.
​API Layer: FastAPI serves as the bridge, managing requests and ensuring rapid communication between the UI and the AI models.
​Intelligence Layer: Python-based AI models process the voice for identity verification and intent.
​💡 How it Works
​Verification: The user speaks; the system checks the voice print against the stored biometric template.
​Processing: If verified, the audio is converted to text using Whisper.
​Analysis: The text is analyzed for sentiment and intent.
​Action: SISA executes the command and responds via a natural-sounding Text-to-Speech (TTS) engine.
