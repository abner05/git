GIT 
git init -- Initilize local repository
git status -- Track/Untrack files
git config --global user.name "Rohit K Singh"
git config --global user.email "RohitK@gmail.com"
git add FileName
git config -l | grep -i "USER"
git commit -m "Mesg"
git commit -a -m "Mesg" {Only works on modified files} 
git log -- History of commits
git branch branch_name
git switch branch_name
git branch -l
git checkout -b branch_name
git merge source_branch {switch dest_branch}
git diff branch_name
git reset HEAD^ {--soft -- Just delete not the file...}
git reset --hard HEAD^ {Deletes everything...}
git cherry-pick commit_id {Picks-up sepecfic commits to merge}
git tag tag_name 
git remote -v
git remote add -t master origin url

-------
Stashing -- Placed your uncommited changes in a diff location

git stash 
git stash list
git stash pop stash_name
git stash drop stash_name {Everything is deleted}

--------

VI Editor:

i -- Insert
esc -- To come out from Insert mode
:w -- write 
:q -- quite
:q! -- force quite
:wq -- write and quite
:wq! -- force write and quite

--------

hello.txt
test.html
test.css

git add hello.txt test.html 
git add *.html *.css 
git add .

---------

GIT vs GITHUB/GITLAB/Azure Repos

--------

git clone 
git fetch --> fetch latest, !commit
git pull  --> fetch latest, commit 
git push  --> local commit, sync repository 
git push --tag






