# git
git

## checkout single branch with depth

git clone -b jenkins --single-branch --depth 1  git@github.com:xiangliangliang/test.git

## checkout one commit 

https://www.cnblogs.com/foohack/p/7199127.html

### make a new blank repository in the current directory
git init

### add a remote
git remote add [nick_name] [url://to/source/repository]

### fetch a commit (or branch or tag) of interest
### Note: the full history of this commit will be retrieved
git fetch [nick_name] <sha1-of-commit-of-interest>

### reset this repository's master branch to the commit of interest
git reset --hard FETCH_HEAD
