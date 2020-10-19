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

git checkout -b IntegrationBranch
emacs README.md
git add . 
git commit -m "Third commit adding IntegrationBranch"
git push --set-upstream origin IntegrationBranch