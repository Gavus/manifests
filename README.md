# Manifests

## Install repo
```
mkdir -p ~/.local/bin
curl https://storage.googleapis.com/git-repo-downloads/repo > ~/.local/bin/repo
chmod a+x ~/.local/bin/repo
```

## Setup
```
git config --global user.email "gustavsj@outlook.com"
git config --global user.name "Gustav Johansson"
repo init git@github.com:Gavus/manifests.git
repo sync
```
