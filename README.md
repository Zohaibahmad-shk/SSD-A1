# SSD-A1
# SSD-A1 — Git and GitHub Collaboration Assignment

## Overview

This repository was created for Lab Assignment #1 of Secure Software Design and Development.

The purpose of this assignment was to practice Git and GitHub concepts including repository creation, cloning, commits, branches, pull requests, forking, reverting, resetting, collaboration, and merge conflict resolution.

## Tasks Performed

### 1. Repository Creation
- Created a public GitHub repository.
- Added a README file.
- Added a Python `.gitignore`.

### 2. Repository Cloning
- Cloned the GitHub repository to the local computer using Git.

### 3. Initial Commit
- Created `main.py`.
- Staged the file using `git add`.
- Created a commit.
- Pushed the commit to GitHub.

### 4. Branching
- Created the `feature/new-feature` branch.
- Added a new feature to `main.py`.
- Committed and pushed the branch.

### 5. Pull Request
- Created a pull request from `feature/new-feature` to `main`.
- Successfully merged the pull request.

### 6. Forking and Collaboration
- Forked another public repository.
- Practiced creating a contribution branch.
- Forked a classmate's `team-project` repository.
- Created a documentation contribution.
- Submitted a pull request from the fork to the original repository.
- The pull request was successfully merged.

### 7. Git Revert
- Created a test commit on the `revert-demo` branch.
- Used `git revert` to undo the commit.
- Verified that Git created a new revert commit without removing the original commit.

### 8. Git Reset
- Created two commits on the `reset-demo` branch.
- Used `git reset --hard HEAD~1`.
- Verified that the branch returned to the previous commit and the file returned to Version 1.

### 9. Merge Conflict
- Created a common file on `conflict-base`.
- Created `branch-a` and `branch-b`.
- Modified the same line differently in both branches.
- Merged the branches to intentionally generate a merge conflict.
- Manually resolved the conflict.
- Committed and pushed the resolved version.

## Challenges Faced

### Merge Conflict
A merge conflict was intentionally created by modifying the same line of the same file in two different branches.

The conflict was resolved by reviewing the conflict markers, selecting a final combined version, staging the resolved file, and committing the resolution.

### Git Reset
`git reset --hard` permanently changes the current branch position and working files, so it was demonstrated on a separate branch to avoid affecting the main branch.

### Collaboration
Forks and pull requests were used to simulate collaboration between different GitHub users.

## Conclusion

This assignment provided practical experience with Git and GitHub version control and collaboration workflows. It demonstrated how branches, commits, pull requests, forks, revert, reset, and merge-conflict resolution are used during software development.