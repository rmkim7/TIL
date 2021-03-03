# git start제

## Done

### shell command

### vim command

### what is git?

### why do you need git?

### How to use git?

Blob/Tree/Commit

git add : working directory to staging area
git commit : staging area to localrepo
git push : local repo to remoterepo

git configuration
$ git config --global user.name " "
$ git config --global user.email " "
$ git config --global core.editor "vim"
$ git config --global core.pager "cat"

$ git config --list

#### Start project with git init

git init
git status
git remote
git remote add origin 'address'
touch 'file.확장자'
git status
git add 'file.확장자'
git status
git commit
vim에서 내용 작성

#### Start project with git clone

git clone 'address'
git status
git status - uall

git clone 이후 git init하면 안 됨
만약 했으면 rm -rf .git으로 삭
