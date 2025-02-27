# 1) Initialize a Git repository
``` 
git init
```
# 2) Check the status of your repo
```
git status
```

# 3) Stage changes
```
git add <file>     # Stage a specific file
git add .          # Stage all changes
```

# 4) Commit changes
```
git commit -m "Your commit message"
```

# 5) View commit history
```
git log
```

# 6) Compare changes
```
git diff
```

# 7) Create a new branch
```
git branch <branch-name>
```

# 8) Switch to a branch
```
git checkout <branch-name>

# Or create and switch in one step:
git checkout -b <branch-name>
```

# 9) Configure Git user details
```
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

# 10) Generate SSH key (RSA 4096-bit)
```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

# 11) Test SSH connection to GitHub

```
ssh -T git@github.com
```

# 12) Set or add remote repository (SSH URL)
```
git remote add origin git@github.com:username/repo.git
# or
git remote set-url origin git@github.com:username/repo.git
```

# 13) Push local changes to remote
```
git push -u origin main
```

# 14) Pull changes from remote
```
git pull
```

```bash
# 15) Example workflow
#    1. git init or git clone
#    2. Make changes
#    3. git add . 
#    4. git commit -m "message"
#    5. git push -u origin main
#    6. Check logs or diffs as needed
```

---

**Notes from your pages (in plain text within code fences):**

```
1. Git is a version control system.
2. GitHub is used as a web-based hosting platform.
3. SSH key commands:
   - ssh-keygen -t rsa
   - ssh -T git@github.com
4. To push your code:
   - git remote set-url origin SSH link
   - git push -u origin main
5. Common commands:
   - git init (to initialize a repo)
   - git add (to stage changes)
   - git commit (to save changes)
   - git log (to view history)
   - git diff (to see what changed)
   - git pull (to fetch and merge from remote)
   - git push (to send changes to remote)
```
