# Lever Advisors — Website

**Jus et Ratio, Levāre.**
Right and Reason, to Elevate.

Strategic finance advisory — Fractional CFO, IFRS 17, Finance Transformation.

---

## Deployment to GitHub Pages

### Step 1: Create a GitHub account
- Go to https://github.com and sign up (free)

### Step 2: Create a new repository
- Click the **+** icon → **New repository**
- Repository name: `lever-advisors` (or `lever-advisors.github.io` for username-level site)
- Set to **Public**
- Do NOT initialize with README (we have one)
- Click **Create repository**

### Step 3: Upload files
- On the repository page, click **"uploading an existing file"**
- Drag and drop ALL files from this folder:
  - `index.html`
  - `CNAME`
  - `README.md`
  - `images/` folder (with logo.png, logo-full.png, monogram.jpeg)
- Commit message: "Initial site launch"
- Click **Commit changes**

### Step 4: Enable GitHub Pages
- Go to repository **Settings** → **Pages**
- Source: **Deploy from a branch**
- Branch: **main** / **root**
- Click **Save**
- Your site will be live at: `https://yourusername.github.io/lever-advisors/`

### Step 5: Connect your custom domain
- In repository Settings → Pages → Custom domain
- Enter: `www.lever-advisors.com`
- Check **Enforce HTTPS**

### Step 6: Configure DNS at your domain registrar
- Add these DNS records at GoDaddy/Namecheap:

| Type  | Name | Value                    |
|-------|------|--------------------------|
| A     | @    | 185.199.108.153          |
| A     | @    | 185.199.109.153          |
| A     | @    | 185.199.110.153          |
| A     | @    | 185.199.111.153          |
| CNAME | www  | yourusername.github.io   |

- Replace `yourusername` with your actual GitHub username
- DNS propagation takes 24-48 hours

### Step 7: Verify
- After DNS propagates, visit https://www.lever-advisors.com
- Your site should be live with HTTPS

---

## File Structure

```
lever-advisors/
├── index.html          # Main website (single page)
├── CNAME               # Custom domain config
├── README.md           # This file
└── images/
    ├── logo.png        # JRL monogram + Lever Advisors logo
    ├── logo-full.png   # Full logo lockup
    └── monogram.jpeg   # JRL monogram only
```

---

## Updating Content

- Edit `index.html` directly on GitHub (click the file → pencil icon → edit)
- Or clone locally, edit, and push changes
- Changes deploy automatically within 1-2 minutes

---

© 2026 Lever Advisors. All rights reserved.
