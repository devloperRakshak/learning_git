PWD :- print working directory, where are we work

CD :- chandge directory, where can we go

LS :- list showing of any directory

MKDIR :- make a folder

MV [old folder name]/ [new folder name] :- to rename folder name

MV [file name for eg :-"index.html"]./ [folder name]/ :- to move the file in other folder

TOUCH [file name for eg:- index.html style.css script.js] :- to create multiple files in a folder

git init :- to Initialized the repository in a folder; 

git add [file neme "index.html"] :- to send the file in staging area

git add . :- to add or send the all files in staging area

git status :- to check the all file is it in staging area or not

git status -s :- short form to check the status

commits :- when we do some changes in our file, then we tell the repository to save a snap shot in 
your database and send a message to repository what are the changes we made in this file

git commit -m [type message"initial"] :- here we just upload our file to repository with message;

git log :- to check the history of what we update in past;

git checkout [place a id"6563a092bd4fb6"]:- to jump in a previous changed file 

git checkout master :- to undo or go back to current version of file 

git branch [branch name (about)] :- there is a main branch named as "master" but we can create a new 
one also so we can work on it and don't change anything in main branch;

git checkout [branch name (about)] :- to jump at one branch to another branch;

git log --all :- git log only check the same branch history but this can check the whole history
of all branches mean when we create a new branch or whe we update it etc.... and one more thing 
when we want to out from this command then simply press "Q" .

git log --all --oneline :- this is a short form of "git log --all" it just showing relevant 
information of history which is created

git branch --delete "branch name" :- to delete the branch but it can't be delete that branch which
 have commit use means you don't change anything in that branch 

git branch -D "branch name" :- to permanent delete the branch although this have multiple changes done 
(commits)

git merge [branch name] :- to mergre one branch to another branch

git branch -M [new name "main"] :- to rename the exesting branch

git remote show origin :- to check where our reposotry is connect showing URL

git push -u origin [ branch name "about"] :- to push the whole code of a branch on git

git push :- to push the whole code to the online repository [git]

git pull :- to get the code from online repository [git]

git clone [paste the HTTPS link "https://github.com/devloperRakshak/learning_git.git"] :- it download 
adject file or folder from git hub

