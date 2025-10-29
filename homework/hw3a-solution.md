# HW3A Solution – Git and Version Control

## Part 1: Repository Cloning
I successfully cloned the class repository from  
`https://github.com/olearydj/INSY6500`  
to my local directory:  
`~/insy6500/class_repo`

This allowed me to access all course materials, including assignments, datasets, and example notebooks.

### Key Commands Used
- `git clone <url>` – Create a local copy of a remote repository  
- `git log` – View commit history and author information  
- `git remote -v` – Check connected remote repositories and their URLs  
- `git status` – Display current branch and file tracking status  
- `git pull` – Fetch and merge the latest updates from the remote repository  

---

## Part 2: Portfolio Repository Creation
I created my **personal course repository** named `my_repo` to maintain all of my coursework and projects in a structured and version-controlled manner.

### Repository Features
- **Professional `README.md`** describing the project purpose and structure  
- **Proper `.gitignore` file** to exclude unnecessary files such as temporary Jupyter notebook checkpoints, cache folders, and data logs  
- **Organized directory structure** separating homework, projects, and notes

---


## Part 3: GitHub Publishing

Successfully published repository to GitHub:
- Used `git remote add origin` to connect local repo to GitHub
- Used `git push-u origin main` to upload commits
- Verified all files and commits are visible on GitHub

### The Remote Connection
My local repository is now connected to GitHub:
-`git remote-v` shows the remote URL
-`git push` will send my commits to GitHub
-`git pull` will get updates from GitHub (if changes are made on GitHub)

### Details
 Complete this section with details from your setup:
- Repository URL: https://github.com/khloudalzubi/py4eda-work
- Output of `git remote-v`: 
origin  https://github.com/khloudalzubi/py4eda-work.git (fetch)
origin  https://github.com/khloudalzubi/py4eda-work.git (push)

- The output of `git log--oneline`: 
308d6d5  Add hw3a solution document
4d459fd  Initial commit: Add README and .gitignore

