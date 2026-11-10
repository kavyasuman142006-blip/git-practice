# Git Practice

Learning Git and GitHub step by step.

git init, initialize folder
git status, checks the status 
New-item name.py or .md etc -ItemType File,  creates a file of given name with attached extension
until now the files are not tracked, so checking status will show it in red calling untracked
now git add full file name, adds the file for git tracking
to add all the file git add.  .
git restore file_name.extension, changes the newly non staged changes to last commited one
git reset file_name.extension, changes staged status from file but keeps the changes
git remote add origin github_repo_url , connects git to github remotely
git push -u origin main/master, used to connect the changes into github repo
git push
