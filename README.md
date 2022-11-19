# Git basics

- Control version manager for a repository
- Distributed system
- Local repo != remote repo

## Git init
Initializes a local git repository

## Git status
Shows the un-commited changes in your repository

## Git add
- Add a file to git: `git add [file-name]` it will start tracking the changes in the file
- Add a group of files based on a pattern: 
  - `git add *.md` Will add all files with the extenssion `.md`
  - `git add folder-name/*` Will add all files under the `folder-name`
  - `git add .` Will track every change and new file to 

## Git commit
Creates a checkpoint in time with a version of your file
- `git commit -m "A relevant message to identify your commit"` -> This will generate an identifier that Will
be used to identify your changes at certain point
- `git commit -am "Another relevant message"` This is similar to `git add .` and `git commit -m "message"` 

## Git remote
Tells your local repository to add a remote location to track your changes when you push them
- `git remote add origin [origin-location]` eg. `git remote add origin git@github.com:ferseg/git-basics.git`

## Git push
Pushes your local changes to the remote
- `git push -u origin [branch-name]` eg. `git push -u origin main`


