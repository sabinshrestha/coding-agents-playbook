# Top 1% Coding Agent Productivity Playbook

Context engineering, the dumb zone, and 10 actionable tips from the builders who ship fastest.

> From YC's Light Cone — Calvin French-Owen (Segment, ex-OpenAI Codex) × Gary Tan

## 🚀 Deploy to GitHub Pages

### Option A: Quick Setup (GitHub UI)

1. Create a new repo on GitHub (e.g. `coding-agents-playbook`)
2. Upload `index.html` to the repo
3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch**
5. Pick `main` branch and `/ (root)` folder → **Save**
6. Your site will be live at `https://<your-username>.github.io/coding-agents-playbook/`

### Option B: CLI Setup

```bash
git init coding-agents-playbook
cd coding-agents-playbook
# copy index.html into this folder
git add index.html
git commit -m "Initial commit"
git remote add origin git@github.com:<your-username>/coding-agents-playbook.git
git push -u origin main
```

Then enable Pages in repo Settings as described above.

## 📝 Notes

- Fully self-contained single HTML file — no build step needed
- Fonts load from Google Fonts CDN
- Works on all modern browsers
- Fully responsive on mobile
