# Lipitrex Content Intelligence Platform v4

TikTok content engine for Lipitrex Water Pills by Progressive Health.
ASIN: B08B9SH5XH

## Stack
- React 18 + Vite
- Anthropic Claude API (claude-sonnet-4-20250514)
- FTC-compliant content generation
- 5 buyer personas · dual video/carousel matrix · offset rotation · genome ID tracking

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to vercel.com → New Project → Import from GitHub
3. Framework: Vite (auto-detected)
4. Add environment variable: `VITE_ANTHROPIC_API_KEY` = your Anthropic API key
5. Deploy

## Local Dev

```bash
npm install
npm run dev
```

## Environment Variables

Create `.env.local`:
```
VITE_ANTHROPIC_API_KEY=your_key_here
```
