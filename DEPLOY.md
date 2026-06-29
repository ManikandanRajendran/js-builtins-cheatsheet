# Deploy to GitHub Pages — Step-by-step

This guide takes you from zero to a live public URL in under 5 minutes.

---

## Step 1 — Create the GitHub repository

1. Go to [github.com/new](https://github.com/new)
2. Set **Repository name** to: `js-builtins-cheatsheet`
3. Set visibility to **Public** (required for free GitHub Pages)
4. Leave "Add a README" **unchecked** (we already have one)
5. Click **Create repository**

---

## Step 2 — Push the project files

Open your terminal and run:

```bash
# Clone or navigate into the project folder
cd js-builtins-cheatsheet

# Initialise git (skip if already done)
git init

# Add all files
git add .

# First commit
git commit -m "Initial commit — JS builtins cheatsheet"

# Connect to your GitHub repo
git remote add origin https://github.com/ManikandanRajendran/js-builtins-cheatsheet.git

# Push to main branch
git branch -M main
git push -u origin main
```

---

## Step 3 — Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top tab)
3. In the left sidebar, click **Pages**
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

GitHub will show a banner: *"Your site is being published"*

---

## Step 4 — Your live URL

After ~60 seconds, your site will be live at:

```
https://ManikandanRajendran.github.io/js-builtins-cheatsheet/
```

> **Tip:** GitHub Pages can take up to 2 minutes on first deploy. Refresh if you see a 404.

---

## Updating the site

Any push to the `main` branch automatically re-deploys:

```bash
# Make your changes to index.html, then:
git add .
git commit -m "Your update message"
git push
```

GitHub Pages will rebuild and update within ~60 seconds.

---

## Custom domain (optional)

If you own a domain (e.g. `manikandan.dev`):

1. In **Settings → Pages**, enter your domain under **Custom domain**
2. Create a `CNAME` file in the repo root containing your domain:
   ```
   manikandan.dev
   ```
3. Update your DNS provider to point to GitHub Pages IPs

---

## Troubleshooting

| Problem | Fix |
|---|---|
| 404 on the live URL | Wait 2 min, check the Pages source is set to `main / root` |
| Changes not showing | Hard-refresh (Ctrl+Shift+R), check the Actions tab for build errors |
| Blank page | Open browser console, check for JS errors |
| CSS not loading | Ensure `index.html` is in the root, not a subfolder |
