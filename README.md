# Manifests

## Install repo
```
mkdir -p ~/bin
curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
chmod a+x ~/bin/repo
```

## Setup
```
git config --global user.email "gustavsj@outlook.com"
git config --global user.name "Gustav Johansson"
repo init git@github.com:Gavus/manifests.git
repo sync
```
