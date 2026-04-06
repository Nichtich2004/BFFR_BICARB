# BFFR — Bicarb Pouches Website

A single-page pitch website for the BFFR business plan competition entry.

## 🚀 Publishing to GitHub Pages

Follow these steps to get your site live — it takes about 5 minutes.

---

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click the **"+"** button in the top right → **"New repository"**
3. Name it: `bffr` (or anything you want)
4. Set it to **Public**
5. Click **"Create repository"**

---

### Step 2: Upload Your Files

**Option A — Upload via GitHub website (easiest):**
1. On your new repo page, click **"uploading an existing file"**
2. Drag and drop the `index.html` file into the upload area
3. Scroll down and click **"Commit changes"**

**Option B — Using Git (if you have it installed):**
```bash
git init
git add index.html
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/bffr.git
git push -u origin main
```

---

### Step 3: Enable GitHub Pages

1. In your repo, click **"Settings"** (top menu)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select **"Deploy from a branch"**
4. Set Branch to **"main"** and folder to **"/ (root)"**
5. Click **"Save"**

---

### Step 4: Your Site is Live! 🎉

After about 1–2 minutes, your site will be available at:

```
https://YOUR_USERNAME.github.io/bffr/
```

GitHub will show you the exact URL in the Pages settings.

---

## 📁 File Structure

```
bffr-website/
└── index.html    ← The entire website (single file, no dependencies)
```

Everything is self-contained in `index.html` — fonts load from Google Fonts CDN, no other files needed.

---

## ✏️ Customizing

All content is in `index.html`. Key things you might want to update:

- **Team photos**: Replace the letter initials in `.team-initial` with `<img>` tags
- **Colors**: Edit the CSS variables at the top (`:root` block)
- **Content**: All text is editable directly in the HTML

---

Good luck at the Middleton Business Plan Competition! 🏆
