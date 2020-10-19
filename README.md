Example repository for M-theta Technology Solutions.

# Demonstrating of Branching

## First Commit
Initializing the Repository (main / Production Branch)
This will contain a single README.md (this file)

### Steps
git init
git add .
git commit -m "Committing first and opening main"
git branch -M main
git remote add origin https://github.com/simplilearn-chl/BranchingExample.git
git push -u origin main

## Second Commit
The second commit will create the second branch "Hot Fix Branch"

git checkout -b "HotFixBranch"
git commit -m "Second Commit adding Hot Fix Branch"
git push