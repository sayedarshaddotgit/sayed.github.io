# Sayed Arshad Khan — Portfolio Website

A minimal, clean economist portfolio built with pure HTML & CSS. No frameworks, no build tools — just one file.

---

## 🗂 Files

```
index.html   ← The entire website (one file!)
README.md    ← This file
```

---

## 🚀 How to Deploy on GitHub Pages (Free Hosting)

### Step 1 — Create a GitHub Account
Go to [github.com](https://github.com) and sign up if you don't have an account.

### Step 2 — Create a New Repository
1. Click the **"+"** icon (top right) → **New repository**
2. Name it exactly: `your-username.github.io`  
   *(Replace `your-username` with your actual GitHub username)*  
   Example: `sayedarshad.github.io`
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload Your Files
1. In the new repository, click **"uploading an existing file"**
2. Drag and drop `index.html` into the upload area
3. Scroll down, click **"Commit changes"**

### Step 4 — Enable GitHub Pages
1. Go to your repository → **Settings** tab
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **main** branch → **/ (root)**
4. Click **Save**

### Step 5 — Visit Your Website 🎉
After 1–2 minutes, your site will be live at:
```
https://your-username.github.io
```

---

## ✏️ How to Edit Your Website

Open `index.html` in any text editor (Notepad, VS Code, etc.)

### Change your contact info
Search for `sayedahaa@gmail.com` and update with yours.  
Search for `+971 509 545 369` and update.  
Search for `LinkedIn ↗` and update the `href` link.

### Change colors
At the top of the file, find the `:root { }` block:
```css
:root {
  --bg: #f5f2ec;       /* page background */
  --ink: #1a1a18;      /* main text color */
  --muted: #6b6b62;    /* secondary text */
  --accent: #2b4a2f;   /* green accent color */
  --line: #d4cfc5;     /* border/line color */
}
```
Replace the color codes to change the theme instantly.

### Update content
All text content is in plain HTML. Look for sections like:
```html
<section id="experience">
<section id="education">
```
Edit the text between the tags.

---

## 📤 How to Update the Live Site

After editing `index.html`:
1. Go to your GitHub repository
2. Click `index.html` → click the **pencil icon** (Edit)
3. Paste your updated code
4. Click **Commit changes**

Or you can re-upload the file (drag & drop again).

---

## 💡 Tips for Later
- To add a **profile photo**, drop an image in the repo and add `<img>` in the header section
- To add **vibrant colors**, just swap the hex values in `:root`
- You can preview locally by just opening `index.html` in your browser — no server needed
