<div align="center">

# ₊˚⊹ DevSphere — HacktoberFest 2026 ⊹˚₊

*(づ｡◕‿‿◕｡)づ Welcome to our open-source workshop repo!*

<br>

![Git](https://img.shields.io/badge/git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Hacktoberfest](https://img.shields.io/badge/Hacktoberfest-2026-ff758f?style=for-the-badge&logo=github)

<br>

**[About](#-about)** &nbsp;•&nbsp; **[Quick Start](#-quick-start)** &nbsp;•&nbsp; **[Common Commands](#-common-commands)** &nbsp;•&nbsp; **[Workshop Guidelines](#-workshop-guidelines)**

<br>

> **Tip**: If you've ever saved a `script_final_v2.py` or sent a project folder as a `.zip` over WhatsApp, this workshop is for you.

</div>

---

### ✦ About

A starter repository for the **DevSphere HacktoberFest** live workshop. Used for demonstrating basic Git workflows: cloning, staging, inspecting diffs, committing, and opening pull requests.

---

### ✦ Quick Start

```bash
# 1. Clone this repository
git clone git@github.com:Wired-Navi0x17/HacktoberFest.git
cd HacktoberFest

# 2. Create your feature branch
git checkout -b feature/my-first-edit

# 3. Test running the demo script
python foo.py

# 4. Stage and commit your changes
git add foo.py
git commit -m "feat: update script variables"

# 5. Push to GitHub
git push origin feature/my-first-edit
```

---

### ✦ Common Commands

| Command | Usage |
| :--- | :--- |
| `git status` | Check working tree status and unstaged changes |
| `git diff` | View exact line-by-line modifications |
| `git add <file>` | Stage specific files for commit |
| `git commit -m "..."` | Commit staged changes with a concise message |
| `git log --oneline` | View compact commit history |
| `git push origin <branch>` | Push local branch to remote repository |

---

### ✦ Workshop Guidelines

- **Meaningful branch names**: Use descriptive names like `feature/<topic>`, not `temp-branch`.
- **Atomic commits**: Keep commits focused on specific changes rather than dumping multiple unrelated edits together.
- **Pull before pushing**: Sync with `git pull origin main` to prevent avoidable conflicts.
- **No secrets or credentials**: Never commit API keys, auth tokens, or `.env` files.

<br>

<div align="center">

DevSphere &bull; HacktoberFest 2026

</div>
