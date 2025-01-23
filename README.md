# 25Q1-mcs-training
This repository used for secure code of training content for 25Q1 MCS


# Git Commands

## Add changes to git repo
git add welcome.sh || git add .

## undo the changes of stagged changes
git restore --stagged welcome.sh || git restore --staged .

## Create a new branch and switch to new branch
git checkout -b '<branch-name>' || git branch '<branch-name>'

## Commit the changes added to remote repo
git commit -m "Initial Commit"

## git push changes to repo
git push --set-upstream origin '<branch-name>' || git push -u origin dev

git pull 
git fetch

git config --global user.name "FIRST_NAME LAST_NAME"
git config --global user.email "MY_NAME@example.com"

