# Cheat Sheet for Git

# generate ssh key
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

# config
git config --global user.email "you@example.com
git config --global user.name "Your Name

# remote url
git remote -v # view remote url
git remote set-url origin https://github.com/USERNAME/REPOSITORY.git # change remote url

# pull all changes in the repo including changes in the submodules
git pull --recurse-submodules

# pull all changes for the submodules
git submodule update --remote
