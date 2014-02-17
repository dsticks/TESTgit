Test git repo

cd ~/TESTgit
git init
git status
git add <file> (Need to add file for each commit)
git commit -m "Comments HERE"
git push
git remote add origin https://github.com/dsticks/TESTgit.git
git remote -v (make sure online repo is set up)

git add -u (changes to previously added files)
git add . (add all files in directory, no deletions recorded)
git add -A (change previously added files, add new ones, track deletions)

git pull (pull latest if on different computer)
git checkout master (check out master branch of repo you are not currently inside)

git help

