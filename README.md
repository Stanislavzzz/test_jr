https://git-scm.com/install/
mac os
brew install git

linux
sudo apt install git

git --version

git config --global user.name "Stanislav"
git config --global user.email "stanislav@gmail.com"
git config --global --list

git init

.gitignore
https://www.toptal.com/developers/gitignore

git status
git add ./.gitignore
git add ./README.md
git commit -m "Add project"

git add .
git commit -m "Add main.py"

git log
git log --oneline
git log --graph


git checkout 0307cf
git branch
git checkout main


https://github.com/

git commit -am "edit readme"

git remote add origin https://github.com/Stanislav/test_jr.git
git branch -M main
git push -u origin main