# EduReach - Agentic College Chatbot

Simple overview for project use.

## What this project does
- College website with login/signup
- AI chat assistant for student queries
- AI voice call request feature

## Project parts
- `client/` -> Frontend (React + TypeScript)
- `server/` -> Backend (Node.js + Express + TypeScript)

## Setup (simple)
1. Install dependencies:
```bash
cd server && npm install
cd ../client && npm install
```
2. Create `.env` in `server/` (keep secrets private, never share).
3. Start backend:
```bash
cd server
npm run dev
```
4. Start frontend:
```bash
cd client
npm run dev
```
5. Open `http://localhost:5173`

## Security notes
- Do not commit `.env` to GitHub.
- Do not share API keys, tokens, DB credentials, or phone IDs.
- Rotate keys immediately if leaked.
- Use strong passwords and production network restrictions.

## Development status
- Part 1: Authentication flow completed
- Part 2: AI chat + voice flow integrated
