# Charlie Health Onboarding Agent

Virtual intake flow for Charlie Health, powered by Claude.

## Deploy to Vercel

1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → Add New Project → Import your repo
3. In **Settings → Environment Variables**, add:
   - `ANTHROPIC_API_KEY` → your Anthropic API key
4. Deploy

That's it. Vercel will auto-deploy on every push to main.

## Structure

```
├── index.html       # Frontend chat UI
├── api/
│   └── chat.js      # Serverless proxy (keeps API key server-side)
├── vercel.json      # Routing config
└── README.md
```
