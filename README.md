# Digital Notebook — Gus

Personal engineering portfolio for Engr 2, SCU Fall 2026.

Six Engr 2 project pages (`p1`–`p6`).
The earlier Engr 110 / CORAL work is archived: collapsed under **Archive** in the
sidebar, with its overview page at `archive`.

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
