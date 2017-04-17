# Git Cheat Sheet
# calculator
#
# Clone the repo to local machine
# git clone https://github.com/zen4s/calculator.git
#
# Checks status of git - provides unsaved files etc
# git status
#
# Add all new & updated files to repo
# git add -A
#
# Commit with comments all new files added to repo
# git commit -m "Commit new"
#
# push the local code to github.com repository
# git push
#
# Pull new code from github.com
# git pull
# Note : Pull on a daily basis from Master make sure you have the latest code
# Note : Always pull before push and see there are no errors
#
# List of available branches
# git branch
#
# Create a new branch. This creates a new version of Master (or current branch)
# git branch calcController
#
# Switch to new branch calcController
# git checkout calcController
#
# To get master code & merge with branch code and then push the branch code
# so it is latest code with required change
# Step 1: git checkout calcController
# Step 2: make changes to code , add new code files
# step 3: git add -A
# step 4: git commit -m "Add code for calcController Branch"
# step 5: git checkout master
# step 6: git pull
# step 7: git checkout calcController
# step 8: git merge master
#
