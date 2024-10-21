# PracticalExam
Step 1: Initialize Git
git init

Step 2: Configure Git
git config --global user.name "Your Name" git config --global user.email "your.email@example.com"

Step 3: Check Git status
git status

Step 4: Stage and commit files
git add . git commit -m "Initial commit"

Step 5: Add a remote repository
git remote add origin https://github.com/yourusername/repositoryname.git

Step 6: Push to the remote repository
git push -u origin master/main

Step 7: Check git log for commit history
git log

Step 8: Create and switch to a new branch
git checkout -b new-branch-name

Step 9: Pull changes from remote
git pull origin master/main # Use the correct branch if not 'master'

Step 10: Push to remote from a different branch
git push -u origin new-branch-name

Step 11: List branches
git branch



auth token url http://localhost:8080/buildByToken/buildWithParameters?token=1234&job=h&whoami=pranit&filename=test.txt

fork commands
git clone https://github.com/Darshanrane123/Python-Game-Arcade.git                   fork and our url
cd Python-Game-Arcade
git remote add upstream https://github.com/Sujay-85/Python-Game-Arcade.git
 git fetch upstream
 git merge upstream/main
fetch after changes $ git fetch upstream
merge changes$  git merge upstream/main

git push origin main

