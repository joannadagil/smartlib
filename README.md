# smartlib

self-service library

## 🌿 Git Workflow

Setting up repository on your computer:

```bash

# Downloading the repository to your computer
git clone https://github.com/joannadagil/smartlib.git

cd smartlib
dir

git config --global user.name “[firstname lastname]”
git config --global user.email “[valid-email]”

# Create your own branch
git branch
git switch -c [your_branch_name] # '-c' is a flag that creates the branch, if you want to switch to an already existing branch skip it
git branch

git add .
git commit -m "added my branch"
pit push origin [your_branch_name]

```

Below is the standard workflow for working on SmartLib:

```bash

# Pull the latest version
git pull

# make your changes (for example add a .txt file)

# Stage all changes
git add .

# Commit with a clear message
git commit -m "[Describe what you did]"

# Push your branch to GitHub
git push origin [your_branch_name]

# show logs
git log --oneline --decorate

# now a hard one if the changes overlap

git branch main
git merge branch [brnach_name]
