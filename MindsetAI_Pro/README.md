# Mindset AI — Pro Version

## Folder structure
MindsetAI/
├── index.html
├── package.json
├── backend/
│   ├── server.js
│   └── .env
└── ...

## Setup

1. Copy `index.html` into your main MindsetAI folder.
2. Put `server.js` and `.env` inside `backend`.
3. In VS Code terminal:

```bash
cd backend
npm install
node server.js
```

4. Open `index.html` in your browser.

## Important
Never put your real OpenAI API key inside `index.html`.
Keep it only in `backend/.env`.

The chatbot contains 18 situation-based mindset tools. The AI is instructed to select only the most relevant 1–3 tools rather than listing all tools every time.

If your API account uses a different model name, change `OPENAI_MODEL` in `.env`.
