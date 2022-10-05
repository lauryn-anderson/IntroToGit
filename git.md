Footer: Women in Computer Science Club: Intro to Git
Slidenumbers: true

# [fit] Intro to Git

---

# First, an intro to you all

Answer a few questions on the slido 

![inline 150%](QRcode.png)

---

# Today's presentation

- will highlight patterns and basics of using git
- will give you tools to keep learning and using git
- will *not* teach you all of git

---

## [fit] I am not your prof

so please ask *all* your questions

even if they feel stupid

they're *not* stupid

you're *not* stupid

git is just hard


---

# Why use git?

Used by 96.7% of professional developers[^1]

- version control
- collaboration

[^1]: [Stack Overflow 2022 Developer Survey](https://survey.stackoverflow.co/2022/#version-control-version-control-system-prof)

---

# Why use version control?

Track entire story of project

- no more "logo.jpg", "logo-again.jpg", "logo-for-real-this-time.jpg"
- no more huge blocks of old code stored in comments
- can *check out* any past version of project 

---

# What is Git?

- distributed version control system
- software tool that runs on your computer
- unfriendly
    - *hard* to learn
    - lots of jargon
    - no built-in ui

![right 80%](Git-Icon-White.png)

---

# Key Git terms

Every project has a git *repo* which tracks the history

- just a folder in the project

- copy of repo exists on each developer's machine

---

# Key Git terms

History stored as series of *commits*

- snapshot of project at a specific moment
- "permanent save"
- includes message, author, date/time, & changes

---

# Please note:

# [fit] Git ≠ GitHub

*Git* is an open source software tool that stores data in repos

*GitHub* is a website where repos are **stored** and **shared**

A git repo is uploaded to GitHub like a document is uploaded to Google Drive

---

# What is GitHub?

![right 220%](GitHub-Mark-Light-120px-plus.png)

- cloud-based git repo hosting service
- holds at least 200 million repos
    - open source projects
- owned by Microsoft since 2018
- friendlier than git but not an equivalent

---

## Practice: 
# Using GitHub

- make an account
- make a repo
- make a commit

---

# Collaboration using Git

Projects are not a linear process

- working on multiple changes at once
    - multiple goals under construction
    - experiment with different ideas
- multiple people working at once
    - want to work freely without worrying about others

---

# What is a branch?

- version of a repository which diverges from the main copy
- each branch is associated with a chain of commits
- branches form "tree"
    - trunk is called *main* branch (good copy of repo)
    - other branches merge back into trunk when ready

---

# Branches: under the hood

- commits have unique hash values
- each commit points to previous commit (*linked list*)
- one commit can have multiple others pointing to it
- branch is pointer to a commit

---

### Demo:
## Branching in Git

---

# Merging branches

- Git will automate as much as possible
- when *merge conflict* happens, need to resolve manually
- merging into main is often formalized as a *pull request*
    - "I want to merge this into main"

---

## Practice:
# Using Branches

- make a branch
- make a commit
- make a pull request

---

# Local Git

You don't want to edit projects in GitHub, you want to use IDEs (Visual Studio Code, PyCharm, etc)

Every person working on a project has a *local* copy of the repo, in addition to the shared *remote* copy (stored on GitHub, GitLabs, etc)

Periodically sync local copy with remote copy ("origin") for backup & collaboration

---

# Local Git commands

- *init* to create repo on local machine
- *clone* to get remote repo on local machine
- *fetch* to update knowledge of remote repo
- *pull* to get new changes from remote repo
- *push* to send new changes to remote repo

---

# Local Development

- project is edited in *workspace* (IDE)
    - *check out* branch to update workspace
    - *HEAD* pointer marks checked out branch
- when ready to commit, *stage* changes
    - next commit contains changes in *staging area*
    - *stash* changes that aren't ready to commit

---

# Local Git tools

- command line git
    - easy to install, hard to use
- built-in to IDEs
    - [Visual Studio Code](https://code.visualstudio.com/docs/sourcecontrol/overview), [PyCharm](https://www.jetbrains.com/help/pycharm/version-control-integration.html), [IntelliJ](https://www.jetbrains.com/help/idea/version-control-integration.html), etc
- third-party application
    - [Git Desktop](https://desktop.github.com), [Tower](https://www.git-tower.com/students), etc

---

### Demo:
## Local Git

---

# Good practices

- commit regularly when you reach any milestone, and push to remote repo
- *gitignore* any files that shouldn't be tracked
    - IDE configuration files
    - compiled executables
    - sensitive information (environment variables, etc)

---

# Resources

- Tower cheatsheets available in [shared folder](https://drive.google.com/drive/folders/1yohnRNJlNf7aJU017hSO_cW593No3Rkk?usp=sharing)
- Tower also provides [free book](https://www.git-tower.com/learn/git/ebook/)
- open source Git [website](https://git-scm.com)
    - [download](https://git-scm.com/downloads) Git or GUIs
    - [free book](https://git-scm.com/book/en/) (more advanced than Tower's)
- [dangit, git!?!](https://dangitgit.com) for when things go wrong
