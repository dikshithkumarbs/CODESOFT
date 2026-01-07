# GitHub Pages Deployment Guide

## ✅ Code Pushed Successfully!

All three projects have been pushed to: https://github.com/dikshithkumarbs/CODESOFT

---

## 🚀 Enable GitHub Pages

Follow these steps to deploy your projects:

### Step 1: Go to Repository Settings
1. Open https://github.com/dikshithkumarbs/CODESOFT
2. Click on **Settings** tab (top right)

### Step 2: Navigate to Pages
1. In the left sidebar, click **Pages** (under "Code and automation")

### Step 3: Configure Source
1. Under **Source**, select **Deploy from a branch**
2. Under **Branch**, select:
   - Branch: **main**
   - Folder: **/ (root)**
3. Click **Save**

### Step 4: Wait for Deployment
1. GitHub will start deploying (takes 1-2 minutes)
2. Refresh the Settings > Pages page
3. You'll see a green banner with your live URL

---

## 🌐 Your Live URLs (after deployment)

**Main Hub Page:**  
https://dikshithkumarbs.github.io/CODESOFT/

**Individual Projects:**
- Portfolio: https://dikshithkumarbs.github.io/CODESOFT/PORTFOLIO/
- Landing Page: https://dikshithkumarbs.github.io/CODESOFT/LANDING%20PAGE/
- Calculator: https://dikshithkumarbs.github.io/CODESOFT/CALCULATOR/

---

## 📁 Repository Structure

```
CODESOFT/
├── index.html          (Main hub page)
├── README.md
├── PORTFOLIO/
│   ├── index.html
│   └── images...
├── LANDING PAGE/
│   ├── index.html
│   └── images...
└── CALCULATOR/
    └── index.html
```

---

## 🔄 Updating Your Site

Whenever you make changes:

```bash
cd "c:\Users\Dell\Desktop\New folder\CODSOFT"
git add .
git commit -m "Update projects"
git push
```

GitHub Pages will automatically redeploy within 1-2 minutes.

---

## ✨ That's it!

Your projects are now live and accessible to anyone on the internet!
