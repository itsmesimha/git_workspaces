# git_workspaces
Creating a git-work-flow 

#Listing all the useful commands and  thier usage in git

#shows installed git version
git --version

#creates user and  email for git
git config --global user.name "<username>"
git config --global user.email "<emailid>"

#lists the userinformations
git config --list

#cloning the git files
git clone <https://Github.com/itsmesimha/git_workspaces/blob/test/index.html>"

#cloning private repo
git clone ssh://git@github.com/[username]/[repository-name].git

#removing files from repo 
git rm -r [file-name.txt]


#establishing connection with github
git clone https://tokenhere@github.com/user_name/reponame.git

#creating branches in git
git branch             #shows list of branches
git branch dev         #created branch dev
git checkout -b dev    #check into branch dev

#merging branch in git
git merge <branch_name>

#delete branch
git branch -d <branch_name>

#deleting remote branch
git push origin --delete [branch name]

#rename local branch
git branch -m [old branch name] [new branch name]


#adding repo in github
git remote add origin <https://github.com/username/repository.git>

#list all remote repo
git remote -v

#git pull branch
git pull origin <branch_name>

#pushing branches into remote repo
git push origin [branch name]

#Push changes to remote repository (and remember the branch
git push -u origin main
git push -u origin test
git push -u origin dev

#push to remmembered branch
git push 

#fetch changes made to file
git fetch origin

#check git histry
git log

#create a tag
git tag tag_name

#list tags
git tag

#create annotated tag
git tag -a tag_name -m "Tag message"

#push tags 
git push origin --tags

#revert from specific commit 
git revert commit_hash

#reset to previous commit
git reset --hard commit_hash

#pushing file sand branches into github
git status                       #shows status of git whether any files needs to be commit
git add <filename>               #add file to commit
git commit -m "comment"          #commits the changes made to file
git push origin <branch name>    #pushes the file to branch

#creating new repo in git
git init

#remove the file in git
git rm <filename>

#rename old files
git mv <old_filename> <new_filename>







