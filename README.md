# BibleProject Trivia Web App — GitHub Pages Deployment Guide

This folder contains the self-contained static files to host the **BibleProject Trivia Web App** on **GitHub Pages** (`https://<your-username>.github.io/<repo-name>`).

---

## 🚀 Quick Deployment (3 Steps)

### Step 1: Initialize Git Repository
In your terminal, navigate to this folder and commit the files:

```bash
cd /usr/local/google/home/spencerkim/.gemini/jetski/brain/fc19e7da-244e-48c4-a294-92d690b44bf7/gh_pages_package
git init
git add .
git commit -m "Deploy BibleProject Trivia Web App"
```

### Step 2: Push to GitHub
Create a new public repository on GitHub (e.g. `bibleproject-trivia`) and run:

```bash
git branch -M main
git remote add origin git@github.com:<YOUR-GITHUB-USERNAME>/bibleproject-trivia.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your GitHub repository on github.com: `https://github.com/<YOUR-GITHUB-USERNAME>/bibleproject-trivia`.
2. Click **Settings** $\rightarrow$ **Pages** (in the left sidebar).
3. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main` / `/(root)`
4. Click **Save**.

---

### 🎉 Your Live URL
Within 1–2 minutes, your website will be live at:
`https://<YOUR-GITHUB-USERNAME>.github.io/bibleproject-trivia/`
