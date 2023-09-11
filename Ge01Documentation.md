# Guided Exploration 01
## Python
### Virtual Environment
A python virtual environment is a directory in the filesystem that is a self contained package of its own python interpreter and packages. It allows you to work on projects that can be easily portable.

To create and use a python virtual environment you must create it:
    python -m <venv> /path/to/new/virtual/environment

After creating it you must activate it.
Linux: source <venv>/bin/activate
Powershell: PS C:\> <venv>\Scripts|activate.PS1

Install Packages: pip

Create the project specific to the venv and put programs and libraries in it.

### Classes and Objects
https://docs.python.org/3/tutorial/classes.html

### Dictionaries
https://realpython.com/python-dicts/

### Regular Expressions
https://docs.python.org/3/howto/regex.html

## Version Control

### Git/Github
Git: Local
Github: Cloud

To clone from Github to local repo:
git clone <GithubLink> (SSH way)

To push from Local git repo to Github:
git init .
git remote add origin <empty GithubRepo link> (HTTP way)
git branch -m main
git push -u origin main
Above takes local directory and pushes it to the empty github one.
After that
touch .gitignore
git add .gitignore
git commit -m “Added gitignore”
git push

### Branches
git branch (shows branches)
git branch <name> (creates branch)

git checkout <branchname> (switch to branch)

### Merging
From Main branch: git merge <branch to merge into main>
https://git-scm.com/docs/merge-strategies

### Tagging
git tag -a "TagName" -m "Tag Comment if added"


