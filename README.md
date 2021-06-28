# gitTaylorCourse-gl
2021 Juan Fonseca. 
Repository for uploading the assignments of the course https://gorillalogic.udemy.com/course/git-going-fast

# Commands:
* List all GIT commands: `git help`
* Help for a specific GIT command: `git help <specific command>` 

# Repository initialization

Specify who you are:
```
git config --global user.name "Juan Fonseca"
git config --global user.email "juan.fonsecasolis@myAwesomeDomain.com"
git config --global --list
```

Initialize an empty the repository with `git init <projectName>` (this creates a .git folder)
 
# Add/commit changes
* Add already existing files: `git commit -am "<comment here>"`
* Add new files recursively: `git add .`
* Add single files: `git <file here>`

# Revert/unstage changes
* Revert changes on a file: `git restore <filename>` 
* Remove file from a commit: `git reset HEAD <fileToBeReverted>`

# Logs
* See commits made to origin `git log` 
* See logs in a simplified way `git log --oneline --graph --decorate --color`



