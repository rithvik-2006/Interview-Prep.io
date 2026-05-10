# 🚀 Syntra — AI Powered Interview Preparation Platform

<div align="center">

<img src="./public/logo.svg" width="140" alt="Syntra Logo" />

<br/>
<br/>

### ✨ Crack Interviews with Real-Time Conversational AI

**Syntra** is a modern AI-powered mock interview platform that helps developers and students practice technical interviews through immersive voice conversations, intelligent feedback systems, and AI-generated assessments.

Built with a cutting-edge stack including **Next.js**, **TypeScript**, **Firebase**, **Vapi AI**, and **Google AI SDK**.

<br/>

![Next JS](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Shadcn UI](https://img.shields.io/badge/Shadcn_UI-black?style=for-the-badge)
![Vapi AI](https://img.shields.io/badge/Vapi-AI-purple?style=for-the-badge)
![Google AI](https://img.shields.io/badge/Google_AI-Gemini-red?style=for-the-badge)

</div>

---

# 🌌 Overview

Syntra is designed to simulate realistic technical interviews using conversational AI.

Instead of static MCQs or generic interview questions, Syntra creates a **human-like interview experience** where users can:

- 🎙️ Talk with AI interviewers in real-time
- 🧠 Receive dynamic follow-up questions
- 📊 Get detailed AI-generated feedback
- 🚀 Improve technical & communication skills
- 🎯 Practice role-specific interviews
- ⚡ Experience an ultra-modern and responsive UI

The platform focuses on creating a highly immersive environment for interview preparation while maintaining scalability, performance, and developer-friendly architecture.

---

# ✨ Key Features

## 🎤 AI Conversational Interviews

Powered by **Vapi.ai**, Syntra enables voice-based interactive mock interviews directly in the browser.

### Features

- Real-time voice conversations
- AI interviewer simulation
- Dynamic contextual questioning
- Live transcript handling
- Conversational memory flow
- AI function calling support
- Natural interaction experience

---

## 🧠 Intelligent Interview Generation

Users can generate personalized interview sessions based on:

- 💼 Job Role
- 📈 Experience Level
- 🛠️ Technology Stack
- 🎯 Interview Category

### Examples

- Frontend React Interviews
- Backend System Design
- DSA Mock Rounds
- Full Stack Interviews
- Behavioral Interviews
- AI/ML Interviews

---

## 📊 AI Feedback & Assessment Engine

After each interview session, Syntra generates comprehensive AI-powered evaluations.

### Evaluation Metrics

- Communication Skills
- Technical Knowledge
- Problem Solving Ability
- Confidence
- Clarity of Explanation
- Depth of Understanding
- System Thinking

### Generated Feedback Includes

- ⭐ Total Score
- 📈 Category-wise Scoring
- 💪 Strengths
- 📉 Areas for Improvement
- 🧠 AI Final Assessment
- 🎯 Personalized Recommendations

---

## 👤 Authentication & User Management

Syntra uses **Firebase Authentication** for secure user management.

### Features

- User Sign Up / Login
- Persistent Sessions
- User Profiles
- Personalized Dashboard
- Interview History Tracking
- Feedback Storage

---

## 🎨 Modern UI/UX Experience

The project uses:

- ✨ Shadcn UI
- 🎨 Tailwind CSS
- ⚡ Framer-like smooth interactions
- 🌙 Clean responsive layouts
- 📱 Mobile-friendly design

The interface is designed to feel modern, minimal, and highly interactive.

---

# 🏗️ Architecture Overview

```bash
┌──────────────────────────┐
│        Frontend          │
│  Next.js + React + TS    │
└────────────┬─────────────┘
             │
             ▼
┌──────────────────────────┐
│      API / Backend       │
│   Next.js Server Routes  │
└────────────┬─────────────┘
             │
 ┌───────────┴───────────┐
 ▼                       ▼
Firebase            AI Services
(Auth + DB)      (Vapi + Gemini)
```

---

# ⚙️ Tech Stack

| Category   | Technologies                 |
| ---------- | ---------------------------- |
| Frontend   | Next.js, React, TypeScript   |
| Styling    | Tailwind CSS, PostCSS        |
| UI Library | Shadcn UI, Radix UI          |
| Backend    | Next.js API Routes           |
| Database   | Firebase                     |
| AI Voice   | Vapi.ai                      |
| AI Models  | Google AI SDK, Vercel AI SDK |
| Validation | Zod                          |
| Forms      | React Hook Form              |
| Utilities  | Day.js, clsx, tailwind-merge |

---

# 📂 Project Structure

```bash
Syntra/
│
├── app/                  # Next.js App Router
├── components/           # Reusable UI Components
├── lib/                  # Utilities & SDK Configurations
├── public/               # Static Assets
├── styles/               # Global Styles
├── types/                # Type Definitions
├── constants/            # App Constants
├── firebase/             # Firebase Configurations
├── hooks/                # Custom Hooks
└── api/                  # API Routes
```

---

# 🔥 Core Technologies Explained

## ⚡ Next.js

Syntra uses Next.js App Router architecture to provide:

- Server Components
- Fast Rendering
- API Routes
- Optimized Performance
- SEO Improvements
- Turbopack Development

---

## 🔥 Firebase

Firebase powers:

- Authentication
- Firestore Database
- Real-time Data
- Session Management
- Potential File Storage

---

## 🎙️ Vapi AI Integration

Vapi enables:

- Real-time AI voice interviews
- Low-latency conversations
- Speech recognition
- Conversational orchestration
- AI function calls

---

## 🤖 Google AI SDK

Google AI powers:

- Interview question generation
- AI analysis
- Feedback generation
- Candidate assessment
- Context-aware evaluations

---

# 🧩 AI Workflow

```bash
User Starts Interview
        │
        ▼
AI Generates Questions
        │
        ▼
Voice Conversation via Vapi
        │
        ▼
Transcript Processing
        │
        ▼
AI Evaluation Engine
        │
        ▼
Detailed Feedback Report
```

---

# 🚀 Getting Started

## 📦 Clone Repository

```bash
git clone https://github.com/yourusername/syntra.git
cd syntra
```

---

## 📥 Install Dependencies

```bash
npm install
```

---

## 🔑 Setup Environment Variables

Create a `.env.local` file:

```env
NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

NEXT_PUBLIC_VAPI_PUBLIC_KEY=
GOOGLE_GENERATIVE_AI_API_KEY=
```

---

## ▶️ Run Development Server

```bash
npm run dev
```

App will be running at:

```bash
http://localhost:3000
```

---

# 🧠 Data Models

## Interview Model

```ts
interface Interview {
  id: string;
  role: string;
  level: string;
  questions: string[];
  techstack: string[];
  userId: string;
  type: string;
  finalized: boolean;
}
```

---

## Feedback Model

```ts
interface Feedback {
  id: string;
  interviewId: string;
  totalScore: number;
  strengths: string[];
  areasForImprovement: string[];
  finalAssessment: string;
  createdAt: string;
}
```

---

# 🎨 UI Highlights

Syntra includes:

- 🌌 Beautiful gradient aesthetics
- 📱 Fully responsive layouts
- ✨ Interactive components
- ⚡ Fast transitions
- 🎯 Focused developer experience
- 🧠 Smart visual feedback systems

---

# 📈 Future Improvements

Planned features include:

- 🧾 Resume Upload & Analysis
- 🎥 Video-based Interviews
- 🌍 Multi-language Support
- 📊 Analytics Dashboard
- 🧠 AI Interview Memory
- 🧑‍🤝‍🧑 Peer-to-peer Mock Interviews
- 🏆 Leaderboards & Gamification
- 📚 Learning Recommendations

---

# 🛡️ Development Tooling

### Included Tooling

- ESLint
- TypeScript Strict Mode
- Turbopack
- Path Aliases
- Zod Validation
- Component Abstractions

---

# 💻 Build Commands

```bash
# Development
npm run dev

# Production Build
npm run build

# Start Production Server
npm run start

# Lint
npm run lint
```

---

# 🌟 Why Syntra?

Syntra is not just another mock interview platform.

It creates a realistic AI-powered interview ecosystem where users can:

- Improve confidence
- Practice communication
- Sharpen technical thinking
- Prepare for real-world interviews
- Receive actionable AI feedback

All inside a beautifully designed modern application.

---

# 🤝 Contributing

Contributions are welcome!

```bash
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request
```

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Built with ❤️ using modern AI technologies.

---

# ⭐ Final Note

If you found this project helpful, consider giving it a ⭐ on GitHub.

It genuinely helps and motivates future development.

---

## 📚 Project Reference

Project architecture and feature details referenced from uploaded project documentation. fileciteturn1file0L1-L260
