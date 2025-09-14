Got it 👍 You want to join that GitHub repo as a collaborator.
Here’s how it works:

---

### 🔑 Important

* Only the **owner of the repo** (`gospelwilbart`) can add collaborators.
* You can’t add yourself – you need the repo owner to grant you access.

---
Perfect! Here’s a **ready-to-copy PowerShell script** that will take your blog project from zero to GitHub in **one go**. It handles spaces in folder names, initializes Git, commits, sets the remote, and pushes.

---

```powershell
# -------------------------------
# PowerShell Script to Push Project to GitHub
# -------------------------------

# 1. Navigate to your project folder (use quotes for spaces)
cd "C:\Users\M I C R O S P A C E\PYTHON\Building a Blog Application"

# 2. Initialize Git repository (if not already initialized)
git init

# 3. Stage all files
git add .

# 4. Commit files
git commit -m "Initial commit"

# 5. Set remote URL (replace with your GitHub repo)
$repoURL = "https://github.com/gospelwilbart/Building-a-Blog-Application.git"

# Check if remote 'origin' exists
$remotes = git remote
if ($remotes -contains "origin") {
    git remote set-url origin $repoURL
} else {
    git remote add origin $repoURL
}

# 6. Rename branch to 'main' for GitHub standard
git branch -M main

# 7. Push to GitHub
git push -u origin main

# -------------------------------
# Done! Your project should now be on GitHub.
# -------------------------------
```

---

### ✅ How to use

1. Copy the script above into **PowerShell** or save as a `.ps1` file.
2. Run it from PowerShell.
3. If Git asks for credentials:

   * **Username:** your GitHub username
   * **Password:** your Personal Access Token (PAT)

After this, your blog project will be fully pushed to GitHub.

---

If you want, I can make a **version that avoids typing credentials every time** by using GitHub **SSH keys** in PowerShell. This way, it’s fully automatic.

Do you want me to do that?


### ✅ Steps the **repo owner** must do:

1. Go to the repo 👉 [Building-a-Blog-Application](https://github.com/gospelwilbart/Building-a-Blog-Application.git)
2. Click **Settings** (gear icon in repo menu).
3. In the left sidebar, go to **Collaborators**.
4. Click **Add collaborator**.
5. Search for your GitHub username (`EliasMwita`? or whichever you use).
6. Click **Add** → You’ll get an invitation.
7. You accept the invite from **your GitHub notifications/email**.

---

### ✅ Once added, you can:

* Clone the repo:

```bash
git clone https://github.com/gospelwilbart/Building-a-Blog-Application.git
cd Building-a-Blog-Application
```

* Create a new branch for your changes:

```bash
git checkout -b feature/my-changes
```

* Push to the repo:

```bash
git push origin feature/my-changes
```

---

👉 Do you want me to draft a **message you can send to `gospelwilbart`** asking them to add you as a collaborator?
