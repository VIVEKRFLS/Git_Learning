First thing 

Pre-requistics
git.exe should be installed in your machine


Step 1: How to tell to monitor or track my changes in a folder or files
git init

git status - tell us the LIVE status of the local repo

Step 2: how to stage files in git 
git add .

Step 3: how reset or restage unwanted files or folders
git restore --staged <filename> 

Step 4: how to commit in git
git commit -m "any text"


Step 5: how to create a branch
git branch -M <branch name>


Step 6: how to add origin/remote repository , before that a repo should be crated in github,gitlab etc
git remote add  origin <githb_url>

Step 7: how to push changes
git push -u origin <branch_name>


Step 8: how pull changes from remote to local
git pull origin <branch name>

Commands:
Swithc b/w branches
git checkout <branch_name>
git merge <branch_name>