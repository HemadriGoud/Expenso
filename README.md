
Expenso

A modern and intuitive expense tracking application built with React, TypeScript, and Vite. Expenso helps users manage their finances efficiently through expense tracking, data visualization, and AI-powered insights.

Features
📊 Expense Tracking
📈 Financial Data Visualization
🤖 Gemini AI Integration
⚡ Fast React + Vite Development Environment
🎨 Modern UI with Tailwind CSS
📅 Date Management with Date-fns
📉 Interactive Charts using Recharts
Tech Stack
Frontend
React 19
TypeScript
Vite
Tailwind CSS
Lucide React Icons
Motion Animations
Backend & Utilities
Express.js
Dotenv
Google Gemini AI SDK
Data Visualization
Recharts
Project Structure
project-root/
│
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── utils/
│   └── main.tsx
│
├── .env.local
├── package.json
├── vite.config.ts
├── tsconfig.json
└── README.md
Installation
Prerequisites
Node.js (v18 or higher recommended)
npm
Clone Repository
git clone <repository-url>
cd expenso
Install Dependencies
npm install
Environment Variables

Create a .env.local file in the root directory and add your Gemini API key:

GEMINI_API_KEY=your_api_key_here

The application uses the Gemini API for AI-powered features.

Running the Application

Start the development server:

npm run dev

The application will run at:

http://localhost:3000

Available Scripts
Start Development Server
npm run dev
Build for Production
npm run build
Preview Production Build
npm run preview
Type Checking
npm run lint

Dependencies

Major packages used:

React
TypeScript
Vite
Tailwind CSS
Recharts
Express
Google GenAI SDK
Date-fns
Lucide React

Build and Deployment

Generate a production build:

npm run build

Preview the build locally:

npm run preview
Security

Environment files are ignored by Git to protect sensitive API keys:

.env*
!.env.example

Application Information

Name: Expenso

Description: A refined financial companion for tracking expenses with ease and clarity.

Capabilities:

Finance Tracking
Data Visualization
