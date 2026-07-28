# 🚀 AssessOrch – AI-Powered Coding Assessment Platform

AssessOrch is an intelligent coding assessment platform built to simplify the technical hiring process. It enables recruiters to create customised programming tests while providing candidates with a smooth, secure, and interactive coding experience.

---

# ✨ Key Features

## 👨‍💼 For Recruiters

- **AI-Assisted Question Generation:** Create coding challenges and interview questions based on required skills and job roles.
- **Custom Assessment Builder:** Design coding, multiple-choice, and technical assessments with flexible configurations.
- **Candidate Dashboard:** View submissions, monitor progress, and analyse candidate performance.
- **Question Repository:** Maintain a reusable collection of interview questions and coding problems.

## 👨‍🎓 For Candidates

- **Built-in Code Editor:** Solve programming challenges using a clean editor with support for multiple programming languages.
- **Progress Tracking:** Monitor completed assessments, scores, and performance history.
- **Instant Feedback:** Receive automated evaluation and detailed score reports after submission.
- **Modern User Interface:** Responsive, distraction-free interface for an improved assessment experience.

---

# 🛠 Tech Stack

- **Framework:** Next.js 14 (App Router, Server Components)
- **Styling:** Tailwind CSS & Shadcn UI
- **Database:** Firebase Firestore
- **Authentication:** Custom Session-based Auth (Mocked for easy demo, extensible to Firebase Auth)
- **AI Engine:** OpenAI GPT-4 Integrated API
- **Icons:** Lucide React

---

# 📁 Project Structure

```text
── app/                  # Next.js App Router (Pages & API)
│   ├── api/              # Backend API routes (Firestore & AI Logic)
│   ├── recruiter/        # Recruiter-facing dashboard & test creation
│   └── student/          # Candidate-facing assessment hub
├── components/           # Reusable UI components
│   ├── assessment/       # Core assessment engine (Editor, Timer, etc.)
│   └── dashboard/        # Layout and nav components
├── lib/                  # Helper utilities (Firebase init, shared types)
├── public/               # Static assets & images
└── styles/               # Global CSS & Tailwind configuration
```

---

# 🚀 Getting Started

## Prerequisites

- Node.js 18+
- npm or yarn

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/pailameghana/AssessOrch.git
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env.local` file.

```env
OPENAI_API_KEY=your_api_key

# Firebase config is already initialized in lib/firebase.ts for the demo
```

### 4. Start the development server

```bash
npm run dev
```

Open:

```
assessorch.vercel.app
```

---

# 🔒 Proctoring & Security

AssessOrch is built with integrity in mind, featuring:

- Tab-switching detection
- Full-screen enforcement
- Copy-paste monitoring (configurable per test)
- Real-time time management tracking

---

# 📄 License

This project is licensed under the MIT License-see the LICENSE file for details.

---

## ❤️ Developed By

**Paila Meghana**

