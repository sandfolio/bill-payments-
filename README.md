# बिल भुगतान — Interactive Prototype

Single self-contained static HTML file (`index.html`) — no build step, no dependencies to install.

## Deploy to Vercel

**Option A — Dashboard drag & drop (fastest)**
1. Go to https://vercel.com/new
2. Drag this folder (or the extracted zip contents) onto the page
3. Click **Deploy** — done in a few seconds

**Option B — Vercel CLI**
```bash
npm i -g vercel
cd this-folder
vercel --prod
```

**Option C — GitHub**
1. Push this folder's contents to a new GitHub repo
2. Import the repo at https://vercel.com/new
3. Framework preset: **Other** (no build command needed) — deploy

No environment variables, build command, or output directory settings are required — Vercel will serve `index.html` as a static site automatically.
