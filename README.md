# 7-Day Rubrik System Design Plan

An interactive, single-page study plan for Rubrik's system design + system
coding interviews. Check off tasks and your progress bar fills up — progress
and theme choice are saved in your browser's `localStorage`.

No build step. No dependencies. Just static HTML + Google Fonts.

## Deploy to Vercel

### Option A — drag & drop (easiest)
1. Go to <https://vercel.com/new>.
2. Drag this folder (unzipped) onto the page.
3. Click **Deploy**. You'll get a live URL in seconds.

When asked for a framework preset, choose **Other**:
- Build command: *(leave empty)*
- Output directory: *(leave empty / `.`)*

### Option B — Vercel CLI
```bash
npm i -g vercel     # once
cd sd-plan-site
vercel              # preview URL
vercel --prod       # production
```

### Option C — Git
Push this folder to a GitHub/GitLab/Bitbucket repo, import it in Vercel,
and every push auto-deploys.

## Run locally
```bash
npx serve .
# or
python3 -m http.server 3000
```
Or just open `index.html` in a browser.
