Example repository for M-theta Technology Solutions.

Demonstrating of Branching

First Commit to main / Production Branch

Steps:
git init
git add .
git commit -m "Committing first and opening main"
git branch -M main
git remote add origin https://github.com/simplilearn-chl/BranchingExample.git
git push -u origin main

## Third Commit
Adding the Integration Branch

### Steps
git checkout -b IntegrationBranch
emacs README.md
git add . 
git commit -m "Third commit adding IntegrationBranch"
git push --set-upstream origin IntegrationBranch


## Fourth Commit
Adding the first Feature Branch Feature1

### Steps

git checkout -b Feature1
emacs README.md
touch feature1.txt
git add .
git commit -m "Fourth Commit: Starting Feature 1"
git push --set-upstream origin Feature1

