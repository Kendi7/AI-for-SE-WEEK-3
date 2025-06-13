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
