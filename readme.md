# Assignment: Introduction to Git & GitHub

## Objective
Learn the basics of Git version control and create your first repository on GitHub. By the end of this assignment, you will have initialized a local Git repository, made your first commits, and pushed your project to a remote repository on GitHub.

---

## Instructions

### 1. Initialize Your Local Repository
- Open your terminal and navigate to your project folder (or create a new folder for your webpage).
- Run the following command to initialize a new Git repository:
  ```sh
  git init
  ```

### 2. Add Your Files
- Add your HTML file(s) (and any other files you want to include) to the staging area with:
  ```sh
  git add .
  ```
  or specify individual files, e.g.:
  ```sh
  git add index.html
  ```

### 3. Make Your First Commit
- Save your changes to version control with a commit message:
  ```sh
  git commit -m "Initial commit: Add profile page"
  ```

### 4. Create a GitHub Account (if you don’t have one)
- Go to [github.com](https://github.com/) and sign up for a free account.
- Confirm your email and set up your profile.

### 5. Create a New Repository on GitHub
- Click the "+" icon in the top right and select “New repository.”
- Name your repository (e.g., `profile-page`).
- **Do not** initialize with a README for this assignment.

### 6. Connect Your Local Repository to GitHub
- In your new repo on GitHub, copy the remote URL (choose HTTPS or SSH).
- In your terminal, link your local repo to the remote:
  ```sh
  git remote add origin https://github.com/YOUR-USERNAME/profile-page.git
  ```

### 7. Push Your Code to GitHub
- Push your local commits to your GitHub repository:
  ```sh
  git push -u origin main
  ```

---

## Submission
- Submit your GitHub repository link 
---


### Rubric/Style Guide- [ ] Initialized a local Git repository
- [ ] Added project files and committed changes
- [ ] Created a GitHub account and repository
- [ ] Connected local repo to GitHub and pushed code
- [ ] Submitted the GitHub repo link