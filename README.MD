# Git and GitHub Learning

git init  | U

git add . | For all | A
git add README.md | One file only | A


git commit -m "This is my first commit"

git branch -M main | Rename the branch

git branch | To see in which branch I'm right now.

____ 
When you are using git or github in you pc

git config --global user.name "First and Last Name"

git config --global user.email "email@gmail.com"
___

git remote add origin https://github.com/HumzaBasharat/Git_GitHub_Learning.git

git remote -v | See fetch and push destiantion 

____

git push -u origin main | is short for --set-upstream

error without this

    PS G:\DASHBORAD\portfolio_projects\Git_GitHub_Learning> git push            
    fatal: The current branch main has no upstream branch.
    To push the current branch and set the remote as upstream, use

        git push --set-upstream origin main

    To have this happen automatically for branches without a tracking
    upstream, see 'push.autoSetupRemote' in 'git help config'.

This makes the remote branch the upstream branch for your local branch.

After this, you can just run:

git push
git pull  
____

Make git ignore file name with .gitignore

then:

choose .gitignore templete: None -> Python

then:

Commit changes...

What is the importance of .gitignore file\

    1. Prevents unnecessary files from being tracked (e.g., *.log for log files).
    2. Protects sensitive information (e.g., .env for secrets).
    3. Improves performance by ignoring large or irrelevant files (e.g., *.bin for binaries).
    4. Enhances collaboration by excluding local environment files (e.g., .DS_Store).
    5. Maintains a clean repository by avoiding clutter from generated files (e.g., *.tmp).