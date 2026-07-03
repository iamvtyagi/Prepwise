# Prepwise

A basic AI-powered mock interview application built with Next.js. The app lets users sign in, create interview sessions, practice with an AI voice interviewer, and receive feedback after each session.

## Features

- User authentication with Firebase
- Create and manage mock interviews
- AI-generated interview questions
- Voice-based interview experience with Vapi
- AI feedback and scoring after interviews
- Responsive UI built with Next.js and Tailwind CSS

## Tech Stack

- Next.js
- React
- TypeScript
- Tailwind CSS
- Firebase
- Vapi AI
- Google Generative AI
- shadcn/ui

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

```bash
git clone <https://github.com/iamvtyagi/Ai_Mock_interview>
cd ai_mock_interviews
npm install
```

### Environment Variables

Create a `.env.local` file in the project root and add the required values:

```env
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
GOOGLE_GENERATIVE_AI_API_KEY=
NEXT_PUBLIC_BASE_URL=
NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=
FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

### Run the app

```bash
npm run dev
```

Open http://localhost:3000 to view it in the browser.

## Project Structure

- `app/` - Pages and route handlers
- `components/` - UI components
- `lib/` - App logic and helpers
- `firebase/` - Firebase client and admin setup
- `constants/` - Shared app constants
