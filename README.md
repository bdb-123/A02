# A02 Git, Webstorm, and Github: step-by-step tutorial
The goal is to create a GitHub repistory named A02 to learn how to use Git, Webstorm, and Github.

# Git, WebStorm, and GitHub Tutorial

This guide explains how to set up WebStorm with Git and GitHub, and walks you through the basic workflow of creating, committing, and pushing projects. It is designed for beginners and students who are learning professional software practices.

---

# Git, WebStorm, and GitHub — Step-by-Step Tutorial

This guide walks a new developer through installing the tools, connecting **WebStorm** to **Git** and **GitHub**, and making their first commit and push — plus a glossary at the end.

---

## Part 1 — Directions on Using WebStorm with Git & GitHub

### Prerequisites
- A **GitHub account**: https://github.com  
- Installed software:
  - **WebStorm** (IDE) — download: https://www.jetbrains.com/webstorm/download/  
  - (Optional) **JetBrains Toolbox App** (easier installs/updates) — https://www.jetbrains.com/toolbox-app/  
  - **Git** (version control) — https://git-scm.com/downloads  
  - (Optional) **Node.js (LTS)** for JS/TS projects — https://nodejs.org/en/download  

---

### 1) Install the software

**A. WebStorm**
- Option 1 (recommended): Install via **JetBrains Toolbox App** (lets you manage IDE updates easily).  
- Option 2: Download WebStorm directly for Windows/macOS/Linux, run the installer, and launch WebStorm.

**B. Git**
- Install Git for your OS from the link above.  
- Verify Git is available:
  ```bash
  git --version
  ```
### 2. Create a GitHub Account
- Go to [https://github.com](https://github.com)  
- Click **Sign up** and follow the prompts.  
- Verify your email to activate the account.  

---

### 3. Create a New Repository
1. Once logged in, click the + icon in the top right corner and select **New repository**.  
2. In the **Repository name** field, type:
3. Add a short description (optional).  
4. Choose **Public** so your instructor can view it.  
5. Check **Add a README file**.  
6. Click **Create repository**.  

---

### 4. Add Required Information to `README.md`
- Inside your repository, open the `README.md` file.  
- Add the following information:
- Your name.  
- The assignment number (A02).  
- A short explanation of what this repo is for (example: *“This repo is for learning how to use GitHub and submit assignments.”*).  
- (Optional) Any screenshots or notes about the process.

## Part 2 — Glossary of Terms
- **Branch** — A separate line of development in a repository that allows you to work on changes without affecting the main code until merged.
- **Clone** — A copy of a remote repository downloaded to your local computer using git clone.
- **Commit** — A snapshot of changes saved in the repository with a message describing the update.
- **Fetch** — A command that downloads the latest changes from a remote repository but does not merge them into your local branch.
- **Git** — A distributed version control system that tracks changes in source code over time.
- **GitHub** — A cloud-based hosting service for Git repositories that adds collaboration tools like issues, pull requests, and Actions.
- **Merge** — The process of combining changes from one branch into another.
- **Merge Conflict** — A situation that occurs when Git cannot automatically merge changes, requiring the developer to manually resolve differences.
- **Push** — Sending your local commits to a remote repository like GitHub.
- **Pull** — Fetching and merging changes from a remote repository into your local branch.
- **Remote** — A reference to a version of the repository stored online (such as GitHub). The default remote is usually named origin.
- **Repository** — A project tracked by Git, containing files, commits, branches, and history.

### Works Cited
- Chacon, Scott, and Ben Straub. Pro Git (2nd Edition). Apress, 2014. Available online: https://git-scm.com/book/en/v2
- GitHub Docs — About repositories. https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories
- GitHub Docs — About branches. https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches
- GitHub Docs — About commits. https://docs.github.com/en/get-started/using-git/about-commits
- GitHub Docs — About merge conflicts. https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts
- GitHub Docs — Managing remote repositories. https://docs.github.com/en/get-started/getting-started-with-git/managing-remote-repositories

