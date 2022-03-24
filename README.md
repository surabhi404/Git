# Basic Git Commands:
 Clone- Bring a repository that is hosted somewhere like Github into a folder on your local machine.
 
 Add- Track files and changes in git
 
 Commit- save file in git: git commit -m "message1" -m "message2"
 
 Push- upload git commands to a remote repo
 
 Pull- dowload changes from remote repo to your local machine
 
 git --version- To check if git is already installed or not
 
 git status-To check the status of modified or committed files
 
 git reset- To undo last change
 
 git reset --hard "ssh"- To not only unstage changes but completely remve it
 
 git reset HEAD ~1- To undo last to last change

 git log -p -1- To know all changes in last commit 
 
 git init- initialize empty git repository
 
 git remote set -url origin "link"- for connecting to github account
 
 git remote -v
 
 git push -u origin filename- for first time pushing
 
 git push- uses default file to push to
 
# Git commands for branching 
 
 git branch- To check current branch
 
 git branch branchname- To create a new branch
 
 git checkout branchname- To switch to a specific branch
 
 git checkout -b branchname - To switch to a specific branch and create it as well
 
 git diff- To check the difference in the contents of two branches
 
 git merge- To merge the two branches and if conflict arises then manually sort it
 
 git branch -d localBranch- To delete local branch

 git push origin --delete remoteBranch- To delet remote branch
 
 Github:Wrote code->Commit changes-> Pull request
 
 Local Git Workflow: Code-> Stage Changes->Commit changes->Push changes->Pull request
# Git Bash commands
 git config --global user.name- set username 
 
 git config --global user.email- set mail
 
 code. - open vs code editor
# For ssh
 1.ssh -keygen -t rsa -b 4096 -C "email" -f path/.ssh/id_rsa

 2.name->password->password
 
 3.eval "$(ssh-agent -s)"
 
 4.ssh-add ~/.ssh/id_rsa
 
 password
 
 5.ls -al ~/.ssh
 
 6.clip<~/.ssh/id_rsa.pub
 
 7. paste in github add key option (add a title and submit)
 
 
 
 
