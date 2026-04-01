# NFTE Landing Page

A persuasive landing page for the **Network for Teaching Entrepreneurship (NFTE)** — featuring the stories of Jane Walsh and Mike Jortberg, and three calls to action: donate, volunteer, and shop.

## Project Structure

```
nfte-landing/
├── index.html      # Main landing page (all assets self-contained)
├── vercel.json     # Vercel static deployment config
├── .gitignore
└── README.md
```

## Deploy to Vercel via GitHub

### 1. Create a GitHub Repository

```bash
git init
git add .
git commit -m "Initial commit — NFTE landing page"
```

Then create a new repo on [github.com](https://github.com/new) and push:

```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```

### 2. Deploy on Vercel

1. Go to [vercel.com](https://vercel.com) and sign in (or sign up free)
2. Click **"Add New Project"**
3. Click **"Import"** next to your GitHub repo
4. On the configuration screen:
   - **Framework Preset:** Other
   - **Root Directory:** `./` (leave as default)
   - **Build Command:** *(leave empty)*
   - **Output Directory:** `./` (leave as default)
5. Click **Deploy**

Vercel will give you a live URL (e.g. `https://your-project.vercel.app`) in about 30 seconds.

### 3. Updating the Site

Any push to the `main` branch automatically triggers a redeployment:

```bash
git add .
git commit -m "Update landing page"
git push
```

## Local Preview

Just open `index.html` directly in your browser — no server needed since all assets are embedded.
