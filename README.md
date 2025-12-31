# New Year Static Site

This is a simple static website.

Deployment options:

1) Quick deploy with Vercel CLI:

- Install Node.js (if needed)
- Install Vercel CLI: `npm i -g vercel`
- Login and deploy:

```
vercel login
vercel --prod
```

2) Deploy via GitHub (preferred for continuous deploys):

- Initialize git, commit, push to a GitHub repo (replace URL):

```
git init
git add -A
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo>.git
git push -u origin main
```

- In Vercel dashboard, click "New Project" → import your GitHub repo → Deploy.

Notes:
- For a single-file static site (`index.html`) no build step is required.
- If you want, I can create the Git repo and help push it to GitHub for you (you'll need to provide the GitHub repo URL or grant access).