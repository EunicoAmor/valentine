# Valentine Envelope — Static Site

This is a small static site (single `index.html`) designed to be deployed to Vercel.

Deployment options

1. Quick — from your local machine using the Vercel CLI:

```bash
npm i -g vercel
vercel login
vercel    # follow prompts to deploy (use `vercel --prod` for production)
```

2. Git-based — push this repository to GitHub/GitLab/Bitbucket and import into Vercel:

- Go to https://vercel.com/new
- Import your repo and select the project
- Vercel will auto-detect a static site and deploy

Notes

- Ensure the `images/` folder (used by `index.html`) is committed to the repository so Vercel can serve those assets.
- If you want pretty URLs or different routing, edit `vercel.json`.

Files added for deployment:

- `vercel.json` — Vercel configuration
- `README.md` — this file

That's it — once deployed, your `index.html` will be served at your Vercel URL.
