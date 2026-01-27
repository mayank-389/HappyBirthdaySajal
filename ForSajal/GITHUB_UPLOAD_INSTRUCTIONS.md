# How to Upload to GitHub

## Option 1: Using GitHub Web Interface (Easiest - No Git Required)

1. **Go to GitHub.com** and sign in (or create an account)

2. **Create a New Repository:**
   - Click the "+" icon in the top right → "New repository"
   - Name it (e.g., `HappyBirthdaySajal` or `SajalBirthdayWebsite`)
   - Choose Public or Private
   - **DO NOT** initialize with README, .gitignore, or license
   - Click "Create repository"

3. **Upload Files:**
   - On the new repository page, click "uploading an existing file"
   - Drag and drop ALL files from your `ForSajal` folder:
     - index.html
     - style.css
     - script.js
     - cause.html
     - cause.css
     - cause.js
     - last.html
     - d1.jpeg
     - d2.mp4
     - d3.jpeg
     - gif1.gif
     - gif2.gif
   - Scroll down and click "Commit changes"
   - Your files are now on GitHub! 🎉

4. **Enable GitHub Pages (Optional - to host your website):**
   - Go to Settings → Pages
   - Under "Source", select "main" branch
   - Click Save
   - Your site will be live at: `https://yourusername.github.io/repository-name`

## Option 2: Using GitHub Desktop (If Installed)

1. **Download GitHub Desktop** from: https://desktop.github.com/

2. **After installing:**
   - File → Add Local Repository
   - Browse to your `ForSajal` folder
   - Click "Create a repository" if needed
   - Click "Publish repository" to upload to GitHub

## Option 3: Using Git Command Line (If Git is Installed)

Open PowerShell or Command Prompt in this folder and run:

```bash
git init
git add .
git commit -m "Initial commit - Happy Birthday Sajal website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual GitHub username and repository name.

---

**Recommended: Use Option 1 (Web Interface) - it's the simplest!**
