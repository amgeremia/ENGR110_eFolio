# eFolio — Gus

Personal engineering portfolio for Eng 110, SCU 2026.

## Structure

```
index.html   ← entire site (single-file SPA)
vercel.json  ← Vercel static config
```

## Deploy

Push to GitHub, import the repo in [vercel.com](https://vercel.com), and it deploys automatically.  
Every `git push` to `main` triggers a new deployment.

## Edit with Claude CLI

```bash
# Install Claude CLI if needed
npm install -g @anthropic-ai/claude-code

# In your repo directory
claude
```

Then just describe the change you want ("update the about section", "add a new update entry") and Claude will edit `index.html` directly. Commit and push when happy.
