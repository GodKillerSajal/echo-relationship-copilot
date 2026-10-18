# ECHO — Relationship Context & Communication Assistant

ECHO is an intelligent contact management and interaction assistant designed to organize relationship context, notes, communication history, and proactive follow-ups in a unified workspace.

## Core Features

- **Relationship Directory**: Rich contact profiles categorized by relationship tier, context tags, and interaction history.
- **Context & Memory Aggregation**: Threaded notes, conversation summaries, and saved meeting/discussion context.
- **Intelligent Interaction Prompts**: AI-assisted reply drafting, tone adaptation, and timely reconnect reminders.
- **Local Fallback Mode**: Built-in mock responders ensuring full UI functionality even when no API credentials are configured.

The app uses browser `localStorage` for responsive demo persistence and includes sample interaction scenarios.

## Tech Stack

- **Frontend**: React, TypeScript, TanStack Router/Start, Vite, Tailwind CSS, Lucide Icons
- **AI Integration**: Google Gemini API via server-side endpoints

## Getting Started

### Prerequisites
- Node.js (v18+) and npm/bun

### Installation & Run

```bash
npm install
npm run dev
```

To enable live Gemini-assisted responses, copy `.env.example` to `.env` and set your `GEMINI_API_KEY`:

```bash
cp .env.example .env
```

Open the development server URL in your browser.

## Roadmap & Architecture Notes

This repository represents an interactive prototype exploring contextual relationship intelligence and conversational summarization. Planned roadmap items include multi-user authentication, encrypted cloud sync, and calendar/messaging integrations.
