# Demo-repo
this is my demo repo
<br/>
Author Arham Shahbaz
<br/>
<!-- git commands  -->
<!-- config git on system -->
git config --global user.name "username"

git config --global user.email "email"

<!-- cloneing command  -->
git clone path
<!-- files checker command -->
ls
<!-- hiden files checker command -->
ls -a
<!-- git status -->

git status

<!-- add file  -->

git add . /* all file added */
git add file_name

<!-- file commit -->
git commit -m "your message"

<!-- push command -->
git push origin "branch name"


<!-- useful commands -->

cd // means change dir
cd .. // back to pervious dir
mkdir // for create a dir


<!-- local to remote  -->
git init

git remote add origin repo_name
<!-- for check repo -->
git remote -v //
<!-- current branch  -->
git branch
<!-- change branch name -->
git branch -M main

<!-- set origin branch of some time -->
git push origin -u "branch name" //-u use after push

<!-- branch commands -->

<!-- cheak branch  -->
git branch 
<!-- create branch  -->
git checkout -b branch_name

<!-- change branch  -->
git checkout  branch_name


<!-- delete branch  -->
git checkout -d branch_name


<!-- check  difference and merge a branch to another -->
git diff branch-name

get merge branch-name