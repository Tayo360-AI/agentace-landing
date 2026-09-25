# AgentAce AI — Landing Page

Waitlist and pricing page for AgentAce AI, the AI-powered study companion for the Salesforce Agentforce Specialist (AI-201) certification.

## Deploy to Vercel

1. Push this folder to a GitHub repo
2. Import the repo at [vercel.com/new](https://vercel.com/new)
3. Framework preset: **Other** (or **None**)
4. Build command: (leave empty)
5. Output directory: `.` (or leave empty)
6. Deploy

Vercel auto-detects it's a static site. No build step needed.

## What's here

- `index.html` — the landing/pricing page
- `favicon.*`, `apple-touch-icon.png`, `android-chrome-*.png` — icons for every device
- `og-image.png` — 1200x630 image for LinkedIn/Twitter/Facebook link unfurls
- `logo.png`, `logo-square.png` — brand assets
- `robots.txt`, `sitemap.xml` — SEO
- `llms.txt` — helps AI assistants (ChatGPT, Claude, Perplexity) recommend AgentAce
- `manifest.webmanifest` — PWA support (install-as-app on mobile)

## Custom domain

Once deployed, connect `agentace.ai` in Vercel → Project → Settings → Domains.
