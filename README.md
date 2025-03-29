## Hi there 👋
A summery of Git basics
# GitHub Cheat Sheet

## 📚 **Basic Git Commands**

| Command                  | Description                                   |
|--------------------------|-----------------------------------------------|
| `git init`               | Initialize a new Git repository               |
| `git clone <url>`        | Clone a repository from GitHub                |
| `git status`             | Check the status of your repository           |
| `git add <file>`         | Stage a specific file for commit              |
| `git add .`              | Stage all changes                            |
| `git commit -m "message"`| Commit changes with a message                 |
| `git push`               | Push local commits to a remote repository      |
| `git pull`               | Fetch and merge changes from the remote repo  |
| `git branch`             | List branches                                 |
| `git checkout <branch>`  | Switch to a specific branch                   |
| `git merge <branch>`     | Merge a branch into the current branch        |

---

## 🌱 **Branching and Merging**

- **Create a new branch:**
  ```bash
  git branch <branch-name>
  ```
- **Switch to a branch:**
  ```bash
  git checkout <branch-name>
  ```
- **Create and switch to a new branch:**
  ```bash
  git checkout -b <branch-name>
  ```
- **Merge a branch into the current branch:**
  ```bash
  git merge <branch-name>
  ```

---

## 📦 **Working with Remotes**

| Command                       | Description                                       |
|--------------------------------|---------------------------------------------------|
| `git remote -v`                | List remote connections                          |
| `git remote add origin <url>`  | Add a new remote repository                      |
| `git push -u origin <branch>`  | Push a branch and set upstream                   |
| `git fetch`                    | Download changes from the remote repository       |
| `git pull origin <branch>`     | Pull updates from a specific branch              |
| `git remote remove <name>`     | Remove a remote                                  |

---

## 🛠 **Resolving Merge Conflicts**

1. **When a conflict occurs:**
   - Open the conflicting file and resolve the conflict.
   - Edit the file to keep the desired changes.
2. **Mark conflict as resolved:**
   ```bash
   git add <file>
   ```
3. **Commit the merge:**
   ```bash
   git commit
   ```

---

## 🧹 **Undoing Changes**

| Command                  | Description                                   |
|--------------------------|-----------------------------------------------|
| `git restore <file>`      | Discard changes in a file                    |
| `git reset <commit>`      | Reset to a specific commit                   |
| `git revert <commit>`     | Revert changes introduced by a specific commit|
| `git stash`               | Temporarily save changes                     |
| `git stash apply`         | Reapply stashed changes                      |

---

## 🛡 **Working with Tags**

| Command                  | Description                                   |
|--------------------------|-----------------------------------------------|
| `git tag`                | List all tags                                 |
| `git tag <tag-name>`     | Create a new tag                              |
| `git push origin <tag>`  | Push a tag to the remote repository           |

---

## 🔍 **Viewing History**

| Command                  | Description                                   |
|--------------------------|-----------------------------------------------|
| `git log`                | View commit history                           |
| `git log --oneline`      | View simplified commit history                |
| `git diff`               | Show changes between commits                  |
| `git blame <file>`       | Show who modified each line in a file         |

---

## 🧑‍💻 **Collaborating on GitHub**

1. **Fork a repository:**
   - Go to the repository on GitHub and click the "Fork" button.
2. **Clone your fork:**
   ```bash
   git clone <your-fork-url>
   ```
3. **Make changes and push:**
   - Create a new branch, make your changes, and push to your fork.
4. **Create a Pull Request:**
   - Go to the original repository and click "New Pull Request."

---

## 🔐 **SSH Key Setup**

1. **Generate an SSH key:**
   ```bash
   ssh-keygen -t ed25519 -C "your_email@example.com"
   ```
2. **Add the SSH key to your GitHub account:**
   - Copy the public key:
     ```bash
     cat ~/.ssh/id_ed25519.pub
     ```
   - Go to GitHub Settings > SSH and GPG keys > New SSH key.
3. **Test your SSH connection:**
   ```bash
   ssh -T git@github.com
   ```

---

## 🚀 **Tips for Productivity**

- Use `.gitignore` to exclude files and directories from Git tracking.
- Write clear commit messages to explain what your changes do.
- Regularly pull updates to keep your branch up-to-date.
- Use GitHub Issues to track bugs and feature requests.

---

## 🔗 **Resources**

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com/en)
- [Git Cheat Sheet PDF](https://education.github.com/git-cheat-sheet-education.pdf)



<!--
**RahimDelavar/RahimDelavar** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
