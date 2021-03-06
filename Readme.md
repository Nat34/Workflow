# Workflow
Web Application Development

This repository contains a practice file and documentation. These files were created during the setup, creation and development of a local repository, remote GitHub repository and the exploration of web application development work flow.

## Project: 
Setup a basic workflow with a text editor, version control system, and web browser.

## Drivers: 
To gain a thorough understanding of web application development workflow and tools, including various text editors, version control systems and web browsers.

## Technology:  
The technology in use for this project are text editors, version control systems, web browsers and Unix command line.  The primary GUI text editor in use is Sublime Text.  Sublime is a crossplatform text editor used to create and modify code.  Other GUI and terminal text editors to be explored are TextMate, Coda, Emacs, and Vim.  The primary version control tool in use is Git.  Version control is a process that allows one to keep labeled checkpoints in their code so they can always refer back to it (or revert back to it) if this becomes necessary and is an essential tool for collaborating with other developers.  The primary web browser in use is Firefox.  Other web browsers explored are Chrome, Safari, and IE.  Web applications are built to run in a web browser, therefore it is essential to learn how to effectively use a browser as a developer tool.  This is the main focus of these tools.

## Resources:
* [Learning Web App Development](https://github.com/semmypurewal/LearningWebAppDev)
* Computer
* Linux Mint OS
* Terminal
* Sublime text editor
* Git, GitHub
* Unix commands
* Git commands
* HTML
* World Wide Web

Unix commands introduced:
```
cd 
pwd
ls
ls -a
mkdir
touch
```

Git commands introduced:
```
git init
git status
git add
git commit -m
git log
git remote add origin https://github.com/username/repositoryname.git
git remote -v //confirm remote repository
git remote rm origin //remove the origin previously added
git push origin master
git pull origin master
git rm -r one-of-the-directories
git commit -m "Remove duplicated directory"
git push origin <your-git-branch> (typically 'master', but not always
git rm
git checkout readme.md //discard changes in working directory
```
General Workflow:
```
git init  
ls -a 
git status 
git add Example2/app.js
git commit -m "commit message in present tense" 
git push origin master
```
1. Initialize Git to begin using Git commands inside the folder
2. Verify files that Git has created in the directory
3. View untracked files
4. Add untracked files to local Git repository to be tracked
5. -m flag
6. If error, remove the origin previously added* 
7. Confirm Git now know's there's a remote repository
8. "origin master" specifies master branch of repository
9. If subfolder files are staged for commit
