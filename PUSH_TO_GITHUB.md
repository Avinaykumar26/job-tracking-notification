# Push this project to GitHub

Follow these steps to get your Job Notification Tracker on GitHub.

---

## 1. Install Git (if needed)

- Download: https://git-scm.com/download/win  
- Run the installer and use default options.  
- **Restart your terminal or Cursor** after installing so `git` is recognized.

---

## 2. Create a new repository on GitHub

1. Go to https://github.com/new  
2. Set **Repository name** (e.g. `job-notification-tracker`).  
3. Choose **Public**.  
4. **Do not** add a README, .gitignore, or license (this project already has files).  
5. Click **Create repository**.

---

## 3. Run these commands in your project folder

Open a terminal in this folder (e.g. in Cursor: **Terminal → New Terminal**), then run:

```powershell
# Go to project folder
cd "d:\a KODNEST\projects\THE COMPLETE PLACEMENT SUITE\JOB NOTIFICATION TRACKER"

# Initialize git (only first time)
git init

# Add all files
git add .

# First commit
git commit -m "Initial commit: Job Notification Tracker"

# Add your GitHub repo (replace YOUR_USERNAME and YOUR_REPO with your actual repo name)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git

# Push to GitHub (main branch)
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username and `YOUR_REPO` with the repository name you created (e.g. `job-notification-tracker`).

---

## 4. If GitHub asks for login

- **HTTPS:** GitHub will open a browser or ask for a **Personal Access Token** instead of your password.  
  Create one: GitHub → Settings → Developer settings → Personal access tokens.  
- **SSH:** If you use SSH, use:  
  `git remote add origin git@github.com:YOUR_USERNAME/YOUR_REPO.git`  
  and ensure your SSH key is added to your GitHub account.

---

After `git push -u origin main` succeeds, your code will be on GitHub.
