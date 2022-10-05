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

Projects are not a linear progress

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

## Demo:
# Branching in Git

---

# Branches: under the hood

- each commit points to previous commit (*linked list*)
- branch is pointer to a commit
- one commit can have multiple others pointing to it

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





