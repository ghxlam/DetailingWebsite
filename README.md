# Detailing Website E-Commerce Project
Please use github for this project and learn the basic commands
When pushing to the repo, push to a separate branch instead of main/master
 
# Basic Instructions for Git
1. Ensure git is installed on your device
2. Set your username/email
     git config --global user.email "youremail@email.com"
     git config --global user.name "your name"
3. Run "git branch" to see which branch you are in
4. You can always do "git newBranchName" to create a new branch directy from the terminal
5. Change Branches using "git checkout branchName"

# Pushing/Committing
1. "git add ." will add all current files to the Push
2. To commit changes:
   git commit -m "commit message goes here"
   A commit message can be anything simple such as "Updating the SQL query"
3. Then do "git push"
   Ensure you are in the right branch by doing "git branch" before this to make sure you are pushing to the right branch

# Pulling
1. Easiest way to get someone else's push from the github repository to your local machine is by running "git fetch"
   This will add all new commits but won't change the local files
2. Running "git pull" will overwrite local files and make sure you are up to date with the repository
