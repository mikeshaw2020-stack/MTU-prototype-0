# MTU Prototype 0

Tiny static prototype with a home hub and four rooms:
- Explorer
- Builder
- Business
- Recovery

## Quick Preview (Local)

No dependencies required.

### Option 1: Open directly
Double-click `index.html` in your file explorer.

### Option 2: Run a tiny local server (recommended)
From this folder, run:

```bash
python3 -m http.server 4173
```

Then open:

- http://localhost:4173

## Lightweight Deployment

Because this is a static site, you can deploy it with beginner-friendly hosts.

### GitHub Pages
1. Push this repo to GitHub.
2. In your repo, go to **Settings → Pages**.
3. Under **Build and deployment**, choose:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or your default branch), folder `/ (root)`
4. Save and wait for the Pages URL.

### Netlify Drop (fastest)
1. Go to https://app.netlify.com/drop
2. Drag this project folder (or just `index.html`) into the page.
3. Netlify gives you a live URL instantly.

## Project Structure

```text
.
├── index.html   # App UI, styles, and simple room navigation JS
└── README.md    # Preview + deployment instructions
```
