# Sreevathsan S — Portfolio

A stunning, minimal portfolio website built with pure HTML/CSS/JS.

## 🚀 Hosting on GitHub Pages

### Step 1 — Create the repo
1. Go to [github.com](https://github.com) → **New Repository**
2. Name it exactly: `<your-username>.github.io`  
   *(e.g. `sreevathsan2510.github.io`)*
3. Set it to **Public**
4. Click **Create Repository**

### Step 2 — Upload your portfolio
**Option A — Drag & Drop (easiest)**
1. Open your new repo on GitHub
2. Click **"uploading an existing file"**
3. Drag and drop `index.html` into the upload area
4. Scroll down → click **Commit changes**

**Option B — Git CLI**
```bash
git init
git add index.html
git commit -m "initial portfolio"
git branch -M main
git remote add origin https://github.com/<username>/<username>.github.io.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to repo **Settings** → **Pages** (left sidebar)
2. Under **Source**, select `Deploy from a branch`
3. Branch: `main` / `root` → click **Save**

### Step 4 — Live! 🎉
Your site will be live at:
```
https://<your-username>.github.io
```
*(Takes 1–2 minutes to deploy)*

---

## ✏️ Customizing
- Update the GitHub/LinkedIn links in `index.html` (search for `sreevathsan2510`)
- Replace the email `sreevathsan2510@gmail.com` if needed
- Add your real project GitHub URLs

## 🎨 Themes
The portfolio includes 3 built-in themes:
- **Dark** — Deep charcoal with amber/gold accents
- **Light** — Warm parchment tones with crimson accents  
- **Terminal** — Matrix-green on pure black

Theme preference is saved in localStorage and persists across visits.
