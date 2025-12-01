# SafeGuardAI
SafeGuard AI is an AI-powered multi-agent system designed to assist women in real-time during situations of harassment, threats, or legal disputes. The system provides instant legal guidance, drafts FIRs, and offers emotional support, ensuring that victims take the correct steps immediately while maintaining proper documentation.

Why This Project is Important :
-Millions of women face harassment, stalking, or threats daily. Many victims:
-Panic and are unsure of the right actions to take.
-Struggle to document incidents accurately.
-Lack immediate guidance and emotional support.
-SafeGuard AI addresses these issues by providing a step-by-step actionable workflow, improving safety, legal compliance, and peace of mind.

Core Features

1.Multi-Agent System
Incident Agent: Captures and organizes incident details.
Legal Agent: Provides legal rights information using curated data (Gemini LLM optional for real-time AI guidance).
FIR Agent: Drafts formal FIRs automatically.
Support Agent: Offers helpline info and empathetic guidance.

2.Memory System
Stores past incidents for context-aware advice.

3.Interactive Demo
Judges or users can input incident details and receive instant legal guidance, FIR drafts, and support instructions.

4.Offline-Ready
Fully functional without internet or GPU.
Uses small curated dataset (LRA_submission.json) and memory (memory.json).

5.Future Extensions
Real-time image/video threat detection.
Voice-based input/output.
Cloud deployment with live Gemini LLM integration for advanced legal reasoning.

Technology Stack

Backend: Python + Flask (optional for full deployment).
Frontend: React 3D Dark UI + Tailwind + Framer Motion (UI demo screenshots included).
Agents: Modular Python scripts.
Data: JSON-based legal Q&A dataset and memory storage.
FIR Generator: Python module for automatic report drafting.

Impact
SafeGuard AI demonstrates real-world social impact by empowering women with legal knowledge, immediate action plans, and emotional support during critical situations.

