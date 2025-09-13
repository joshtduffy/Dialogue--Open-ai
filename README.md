# Dialogue OpenAI Bridge

## Setup
1. Copy `.env.example` to `.env` (but only inside Vercel, not GitHub).
2. Add your keys:
   - `OPENAI_API_KEY` = your OpenAI key
   - `DIALOGUE_API_KEY` = your custom secret

## Usage
POST to `/api/chat` with JSON:
```json
{ "message": "Hello!" }
