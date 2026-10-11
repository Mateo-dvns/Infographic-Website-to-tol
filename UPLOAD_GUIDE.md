# How to Upload Files to This Repo (GitHub Desktop)

This guide shows how to add files to **Infographic-Website-to-tol** using GitHub Desktop. It works on both **Windows** and **macOS**.

Repo: https://github.com/Mateo-dvns/Infographic-Website-to-tol

---

## Before You Start

1. **Install GitHub Desktop:** https://desktop.github.com
2. **Create a free GitHub account** at https://github.com if you don't have one.
3. **Get access to the repo.** Pick one:
   - **Collaborator (easiest):** Send your GitHub username to the repo owner and ask to be added under *Settings > Collaborators*. Accept the invitation in your email or on GitHub.
   - **Fork + Pull Request:** If you are not added as a collaborator, click **Fork** on the repo page, clone *your fork* instead, and open a Pull Request when you're done (see the last section).

---

## Step 1: Sign In to GitHub Desktop

- **Windows:** *File > Options > Accounts > Sign in*
- **Mac:** *GitHub Desktop > Settings > Accounts > Sign in*

---

## Step 2: Clone the Repo

1. Go to **File > Clone Repository...**
2. Open the **GitHub.com** tab and select `Mateo-dvns/Infographic-Website-to-tol`. (Or use the **URL** tab and paste the repo link.)
3. Choose where to save it on your computer.
4. Click **Clone**.

---

## Step 3: Add Your Files

1. In GitHub Desktop, open the repo folder:
   - **Windows:** *Repository > Show in Explorer*
   - **Mac:** *Repository > Show in Finder*
2. Copy or drag your files into this folder.
   - If your files are inside another folder, copy the **contents** of that folder, not the folder itself, unless the owner asked you to keep the folder.
   - Keep `index.html` at the top level of the repo unless told otherwise.

---

## Step 4: Check Your Changes

Go back to GitHub Desktop. Your new files appear in the **Changes** list on the left.

- Untick any file you do **not** want to upload.
- **Ignore system files** such as `.DS_Store` (Mac) or `Thumbs.db` (Windows). Right-click the file and choose **Ignore file (add to .gitignore)**, or just untick it.
- Files larger than **100 MB** cannot be uploaded to GitHub. Compress or remove them.
- Empty folders are not tracked by Git, so put at least one file inside a folder for it to upload.

---

## Step 5: Commit

1. At the bottom left, write a short summary, for example: `Add infographic images`.
2. Click **Commit to main** (the branch name may be `main` or `master`).

---

## Step 6: Push to GitHub

Click **Push origin** in the top bar.

Open the repo on github.com and refresh. Your files should now be visible.

---

## Updating Later (Always Do This First)

Before adding new files in the future, click **Fetch origin** (or **Pull origin**) at the top of GitHub Desktop. This gets the latest changes from others and avoids conflicts.

---

## If You Forked the Repo (Pull Request)

1. After pushing, click **Create Pull Request** in GitHub Desktop (or go to the repo on github.com and click **Contribute > Open pull request**).
2. Add a short description of what you added.
3. Submit it. The repo owner will review and merge it.

---

## Troubleshooting

| Problem | Fix |
|---|---|
| Files don't show in *Changes* | They may be in `.gitignore`, or you copied them to the wrong folder. Use *Show in Explorer/Finder* to confirm. |
| "Permission denied" or push rejected | You may not be a collaborator. Ask the owner for access, or use the fork method above. |
| Push says you need to pull first | Click **Fetch origin**, then **Pull origin**, then push again. |
| Wrong account signed in | Sign out and sign in again under *Accounts* in settings. |
| File too large | GitHub's limit is 100 MB per file. Compress or host it elsewhere. |

---

## Quick Summary

**Clone > Copy files in > Commit > Push**
