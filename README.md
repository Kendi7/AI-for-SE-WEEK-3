# 🚀 First Alternative: Weekly GitHub Collaboration Guide

Welcome team! 👋 This guide will help each of you contribute effectively to this week's project tasks using GitHub. Since each member is working on an independent task/file, please follow the steps below carefully to ensure smooth collaboration.

---

## ✅ Step 1: Work on Your Assigned Task

* Complete your weekly task **independently**.
* Preferably use **Google Colab** or **Jupyter Notebook** to write your code.
* Once done, **download your notebook(s) or related files/folders** to your local machine.

---

## 📂 Step 2: Add Your Work to the Git Repository

1. **Locate the cloned GitHub repository directory** on your machine.

2. Move your file(s)/folder(s) into the repository directory.

   Example (from your Downloads):

   ```bash
   cp ~/Downloads/my_notebook.ipynb ~/Documents/project-repo/
   ```

3. Open a terminal and navigate to the project directory:

   ```bash
   cd ~/Documents/project-repo
   ```

---

## 🌱 Step 3: Create a New Branch

* Always work on your **own branch** to keep work clean and organized.
* Name your branch according to your task or name. Examples:

  * `ken_week2_analysis`
  * `alice_data_cleaning`

```bash
git checkout -b your_branch_name
```

---

## 🔄 Step 4: Pull the Latest Changes

Before pushing your work, always **sync with the main branch** to avoid conflicts:

```bash
git pull origin main
```

---

## ✅ Step 5: Add, Commit & Push Your Work

1. Stage your changes:

   ```bash
   git add your_file_or_folder
   ```
2. Commit your changes:

   ```bash
   git commit -m "Added Week 2 notebook for data preprocessing"
   ```
3. Push to your branch:

   ```bash
   git push origin your_branch_name
   ```

---

## 🔁 Step 6: Create a Pull Request (PR)

* Go to the GitHub repository on the web.
* You will see a message to **"Compare & Pull Request"**. Click it.
* Add a short description of what your code does.
* **Request at least one team member for a review**.

---

## 📌 Final Notes:

* Avoid pushing directly to `main` branch.
* Communicate any major changes to the team.
* Check for `.gitignore` – don’t push large or unnecessary files.
* Always pull before you start your next task.

---

Happy coding & collaborating! 🚀

> *"Alone we can do so little; together we can do so much." – Helen Keller*

---

# 🚀 Second Alternative: Full Collaboration Guide – Please Read Before Contributing!

## Hey Team! 👋

Welcome to our project! I've put together this guide to help everyone collaborate smoothly on our GitHub repository. Please take a few minutes to read through this - it'll save us all time and prevent headaches down the road.

## What You'll Need Before Starting

* Git installed on your machine (if you don't have it, grab it from [git-scm.com](https://git-scm.com))
* Access to our GitHub repository (let me know if you need an invite)
* Basic Git knowledge (don't worry, I'll walk you through everything)
* **Python and Jupyter Notebook** installed. You can install using:

```bash
pip install notebook
```

---

## Working With Jupyter Notebooks (Without VS Code)

Since we’re using **Jupyter Notebooks** in this project, here’s how you can work with them directly from your terminal or command prompt (no need for VS Code):

### ✅ After Cloning the Repository:

1. **Navigate into the project folder:**

```bash
cd repository-name
```

2. **Check if the Jupyter notebook is present:**

```bash
ls *.ipynb  # On Linux/Mac
# or
dir *.ipynb  # On Windows
```

If it’s missing or not listed, let the team know.

3. **Launch the Jupyter Notebook interface:**

```bash
jupyter notebook
```

This will open a new browser tab showing the notebook dashboard.

4. **Open the `.ipynb` file:**

   * Click on the notebook file to open it in your browser.
   * Make your changes carefully and test your cells.

5. **Save your work:**

   * Click `File > Save and Checkpoint`, or simply press `Ctrl + S`

6. **Close the notebook and stop the server:**

   * Once done, close the notebook tab.
   * Stop the Jupyter server by pressing `Ctrl + C` in your terminal.

7. **Stage and commit your changes:**

```bash
git add filename.ipynb
git commit -m "Update notebook with [your changes]"
```

8. **Push your branch to GitHub:**

```bash
git push origin your-branch-name
```

> ✅ **Avoid merge conflicts:**
>
> * Don’t edit the same notebook cell as someone else.
> * Always pull from `main` before editing.

---

## Our Team Workflow - Please Follow These Steps!

### Step 1: Get the Repository on Your Machine (First Time Only)

```bash
git clone https://github.com/your-username/repository-name.git
cd repository-name
```

### Step 2: ALWAYS Update Main First! (This is Super Important!)

```bash
git checkout main
git pull origin main
```

### Step 3: Create Your Own Branch

```bash
git checkout -b feature/your-awesome-feature
```

**Branch naming tips:**

* `feature/description`
* `bugfix/what-you-fixed`
* `hotfix/urgent-fix`
* `docs/what-you-updated`

### Step 4: Do Your Magic! ✨

* Edit your `.ipynb` file or Python code.
* Run cells to test and make sure everything works.

### Step 5: Save Your Work

```bash
git status
git add .
git commit -m "Add amazing feature that does X and Y"
```

### Step 6: Push Your Branch

```bash
git push origin feature/your-awesome-feature
```

### Step 7: Ask for a Code Review (Pull Request)

* Use GitHub to open a Pull Request.
* Fill in title, description, screenshots, and testing steps.

### Step 8: Work With Me on Reviews

```bash
git add .
git commit -m "Fix review changes"
git push origin feature/your-awesome-feature
```

### Step 9: Celebrate and Clean Up 🎉

```bash
git checkout main
git pull origin main
git branch -d feature/your-awesome-feature
git push origin --delete feature/your-awesome-feature
```

---

## Team Rules - Please Respect These!

### ❌ DON'T:

* Push directly to `main`
* Use `--force` on shared branches
* Commit secrets
* Upload huge files without asking

### ✅ DO:

* Work on branches
* Pull main before edits
* Write clear commits
* Test code
* Keep PRs focused

---

## Useful Git Commands:

```bash
git status
git branch -a
git checkout branch-name
git log --oneline
git reset --soft HEAD~1
```

### Merge Conflict Help:

```bash
git checkout main
git pull origin main
git checkout your-branch
git merge main
# Fix conflicts, then:
git add .
git commit -m "Resolve merge conflicts"
git push origin your-branch
```

### If Using a Fork:

```bash
git remote add upstream https://github.com/original-owner/repository-name.git
git checkout main
git fetch upstream
git merge upstream/main
git push origin main
```

---

## Quick Git + Notebook Cheat Sheet

```bash
git checkout main
git pull origin main
git checkout -b feature/new-thing
# Launch Jupyter Notebook, edit your .ipynb
jupyter notebook
# Save and exit notebook
# Then:
git add your-notebook.ipynb
git commit -m "What you did"
git push origin feature/new-thing
```

## Need Help? Just Ask!

* Ping me directly
* Create a GitHub issue
* Ask in the group chat

## Final Thoughts

Thanks for reading this! Let’s keep things clean, simple, and helpful. Follow the workflow, support each other, and let's build something awesome 🚀

> *If you know how to push code from Google Colab or Anaconda directly to GitHub, feel free to use that approach too!*


Happy coding & collaborating! 🚀

> *"Alone we can do so little; together we can do so much." – Helen Keller*
