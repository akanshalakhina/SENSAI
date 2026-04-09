🚀 SensAI – AI-Powered Career Assistant

An intelligent full-stack web application that helps users create job-ready content, prepare for interviews, and manage professional profiles using AI.

🌟 Overview

SensAI is designed to simplify the job preparation process by leveraging AI. It enables users to generate personalized cover letters, manage their professional information, and practice interview questions — all in one place.

This project showcases full-stack development, modern UI/UX design, and real-world AI integration, making it highly relevant for software engineering roles.

✨ Features
🤖 AI Cover Letter Generator
Generate tailored, job-specific cover letters instantly using AI
👤 User Profile Management
Store and reuse personal and professional details efficiently
🎯 Interview Preparation Module
Practice commonly asked questions and improve responses
🔐 Authentication System
Secure login/signup using Clerk
⚡ Optimized Performance
Built with Next.js for fast rendering and scalability
📱 Responsive Design
Works seamlessly across desktop and mobile devices
🛠️ Tech Stack

Frontend

Next.js (App Router)
React.js
Tailwind CSS

Backend

Next.js API Routes

Database

Prisma ORM + PostgreSQL

Authentication

Clerk

AI Integration

Gemini API / AI services
📂 Project Structure
SensAI/
│── prisma/              # Database schema & migrations
│── public/              # Static assets
│── src/
│   ├── app/             # Next.js App Router
│   ├── components/      # Reusable UI components
│   ├── lib/             # Utilities & configurations
│── .env                 # Environment variables
│── package.json
│── tailwind.config.ts
⚙️ Getting Started
1. Clone the Repository
git clone https://github.com/akanshalakhina/SENSAI.git
cd SENSAI
2. Install Dependencies
pnpm install
3. Configure Environment Variables

Create a .env file in the root directory:

DATABASE_URL=your_database_url
NEXT_PUBLIC_CLERK_FRONTEND_API=your_clerk_key
CLERK_SECRET_KEY=your_clerk_secret
4. Setup Database
pnpm prisma generate
pnpm prisma migrate dev
5. Run the Application
pnpm dev



💡 Use Cases
Students preparing for placements
Job seekers creating personalized applications
Professionals improving interview skills
Users exploring AI-powered productivity tools
🚀 Future Improvements
AI Resume Analyzer
Job Recommendation System
Interview Performance Feedback
Multi-language Support
Resume Builder with AI Suggestions
