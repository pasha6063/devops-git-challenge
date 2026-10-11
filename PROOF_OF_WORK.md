# Proof of Work

## 1. Git Commit History

The following command displays the commit history of the repository:

```bash
git log --oneline
```

Paste the actual output of this command below.

[e92005f (HEAD -> main, origin/main) Merge pull request #1 from pasha6063/development
3a62bdf (origin/development, development) fix: resolve deployment script merge conflict
ef94cfc (origin/staging, staging) fix: set deployment environment to staging
98f577e feat: update deployment environment for development
9885743 feat: add deployment script and project documentation
]

## 2. Reflection Questions

##Q1. How does Git differ from GitHub?

Git is software that tracks changes to files and maintains a project's version history. It supports operations such as committing, branching, and merging. GitHub is an online platform used to host Git repositories and facilitate collaboration. It offers features such as Pull Requests, reviews, and remote access to project files.

##Q2. Describe the Working Directory, Staging Area, and Local Repository.

The Working Directory contains the files currently being edited. The Staging Area holds the changes selected for the next commit. The Local Repository stores the committed versions of the project and their history. These stages provide a structured process for reviewing and recording changes.

##Q3. How are git stash pop and git stash apply different?

Both commands restore changes saved by Git stash. The git stash pop command normally removes the saved entry after the changes are successfully restored. The git stash apply command restores the changes but retains the stash entry. Keeping the entry can be useful when the same saved work may be needed again.

##Q4. What is the difference between git fetch and git pull?

The git fetch command downloads information about remote changes without integrating those changes into the current branch. The git pull command fetches remote updates and integrates them into the current branch, usually by merging or rebasing. Fetching is useful for reviewing updates before integration, while pulling is useful for updating local work.


