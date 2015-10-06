git help

git config

git config --global user.name "Sergio Monsalve"
git config --global user.email sergio@monsalve.xyz
git config --global color.ui true

git init
git clone direccion.git nombre_carpeta

git add 
git add file.txt
git add .
git add --all

git commit 
git commit -m "Agregando archivo file.txt"

git status

git log
git diff
git diff --staged

git reset HEAD file.txt

git checkout branch

git merge branch

git checkout -b otro_branch

git reset  --soft HEAD^

git commit --amend -m "modificando file.txt y agregando otro.txt"

git reset  --hard HEAD^

git push -u origin master
git pull -u origin master

git remote -v 

git rm archivo.txt

git remote add nombre direccion.git
git remote rm  nombre 

git remote show nombre 
git remote prune remote 

git branch -d nombre_branch

git tag -a V0.1 -m "Version 0.1"

git push --tags 

git bisect
git fetch
git rebase


http://chris.beams.io/posts/git-commit/

http://pcottle.github.io/learnGitBranching/?demo

http://gitref.org/

https://www.youtube.com/user/github/videos

https://github.com/blog/1124-how-we-use-pull-requests-to-build-github

https://guides.github.com/

https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf

http://www.git-tower.com/learn/

http://www.git-tower.com/learn/cheat-sheets/cli

http://gitimmersion.com/

https://www.atlassian.com/git/

https://git-scm.com/book/en/v2/Getting-Started-Git-Basics