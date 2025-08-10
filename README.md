# Coassemble Chat Embed (Vercel)

A minimal ChatGPT-style interface you can embed inside a Coassemble "Embed" lesson.

## Quick Deploy (Vercel)

1. **Create a new project** in Vercel and import this folder.
2. In **Project → Settings → Environment Variables**, add:
   - `OPENAI_API_KEY` = your key
3. **Deploy**. Your site URL will look like `https://YOUR-PROJECT.vercel.app`

### Test endpoints
- App: `https://YOUR-PROJECT.vercel.app/`
- Health: `https://YOUR-PROJECT.vercel.app/api/health`

## Embed in Coassemble
- In your lesson, choose **Embed** and paste the App URL.
- For a tighter fit, set the embed height to around **650–800px**.

## Local Dev (optional)
```bash
npm i -g vercel
vercel dev
# Visit http://localhost:3000
```