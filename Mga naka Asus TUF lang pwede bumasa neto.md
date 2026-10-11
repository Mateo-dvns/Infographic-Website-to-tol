# Pinagawa ko lang 'to kay tito Claude hahaha
# How to Upload Files Using GitHub Desktop (Windows & Mac)

This guide shows you how to add your files to the **Infographic-Website-to-tol** repository using GitHub Desktop. The steps are the same on Windows and Mac. Differences are noted where they exist.

---

## Before You Start

You need:

1. A free GitHub account: https://github.com/signup
2. GitHub Desktop installed: https://desktop.github.com
3. Your files ready on your computer

**Important:** You can only upload directly if the owner (Mateo-dvns) added you as a collaborator. If not, follow **Option B (Fork + Pull Request)** below.

---

## One-Time Setup

1. Open **GitHub Desktop**.
2. Click **Sign in to GitHub.com** and log in with your account.
3. Click **Finish** (the name/email shown is fine).

---

## Option A: You Are a Collaborator (Direct Upload)

### Step 1: Clone the repository

1. In GitHub Desktop, go to **File > Clone repository** (Windows) or **File > Clone Repository...** (Mac).
2. Click the **URL** tab and paste:
   ```
   https://github.com/Mateo-dvns/Infographic-Website-to-tol
   ```
3. Choose where to save it on your computer (the **Local path**).
4. Click **Clone**.

### Step 2: Add your files

1. Open the repository folder on your computer.
   - In GitHub Desktop: **Repository > Show in Explorer** (Windows) or **Repository > Show in Finder** (Mac).
2. Copy or drag your files into the folder.
   - Put them inside the right subfolder (for example `Latest` or `old drafts`) if the owner asked you to.

### Step 3: Commit your changes

1. Go back to GitHub Desktop. Your new files appear in the **Changes** tab on the left.
2. Make sure the checkboxes next to your files are ticked.
3. At the bottom left, type a short message in **Summary** (example: `Added my infographic draft`).
4. Click **Commit to main**.

### Step 4: Push to GitHub

1. Click **Push origin** at the top.
2. Done. Open the repo on github.com and refresh to see your files.

---

## Option B: You Are NOT a Collaborator (Fork + Pull Request)

### Step 1: Fork the repo

1. Go to https://github.com/Mateo-dvns/Infographic-Website-to-tol
2. Click **Fork** (top right), then **Create fork**.

### Step 2: Clone YOUR fork

1. In GitHub Desktop: **File > Clone repository**.
2. Under the **GitHub.com** tab, pick `your-username/Infographic-Website-to-tol`.
3. Click **Clone**. If asked, choose **To contribute to the parent project**.

### Step 3: Make a branch

1. Click **Current Branch** at the top, then **New Branch**.
2. Name it something like `add-my-files` and click **Create Branch**.

### Step 4: Add, commit, push

Follow **Steps 2 to 4 from Option A**, but click **Publish branch** or **Push origin** instead.

### Step 5: Open a Pull Request

1. After pushing, click **Create Pull Request** in GitHub Desktop (or the button on github.com).
2. Add a short description of what you added.
3. Click **Create pull request**. The owner will review and merge it.

---

## Tips

- **Pull before you push** if others are uploading too: click **Fetch origin**, then **Pull origin**, so you don't overwrite their work.
- **Large files:** GitHub blocks single files over 100 MB.
- **File names:** Avoid special characters. Spaces are okay but dashes are safer.
- **Wrong file committed?** Right-click the commit in the **History** tab and choose **Undo commit** (before pushing).
- **No changes showing?** Make sure your files are inside the cloned repository folder, not somewhere else.

---

## Troubleshooting

| Problem | Fix |
|---|---|
| "Permission denied" when pushing | You're not a collaborator. Use Option B. |
| Files don't show in Changes tab | They're in the wrong folder. Move them into the repo folder. |
| Push rejected | Click **Fetch origin**, then **Pull origin**, then push again. |
| Sign-in problems | **File > Options** (Windows) or **GitHub Desktop > Settings** (Mac), then **Accounts** to sign out and back in. |
