# Git basics

- Version control manager, it manages all versions for the files inside a repository (a folder)
- Distributed system
- Local repo != remote repo

## [Git init](https://git-scm.com/docs/git-init)
Initializes a local git repository

This will allow you to tell git to start tracking your current folder as a repository

## [Git status](https://git-scm.com/docs/git-status)
Shows the un-commited changes in your repository

## [Git add](https://git-scm.com/docs/git-add)
- Add a file to git: `git add [file-name]` it will start tracking the changes in the file
- Add a group of files based on a pattern: 
  - `git add *.md` Will add all files with the extenssion `.md`
  - `git add folder-name/*` Will add all files under the `folder-name`
  - `git add .` Will track every change and new file to 

## [Git commit](https://git-scm.com/docs/git-commit)
Creates a checkpoint in time with a version of everything that has been added at that point
- `git commit -m "A relevant message to identify your commit"` -> This will generate an identifier that Will
be used to identify your changes at certain point
- `git commit -am "Another relevant message"` This is similar to `git add .` and `git commit -m "message"` 

## [Git remote](https://git-scm.com/docs/git-remote)
Tells your local repository to add a remote location to track your changes when you push them
- `git remote add origin [origin-location]` eg. `git remote add origin git@github.com:ferseg/git-basics.git`

## [Git push](https://git-scm.com/docs/git-push)
Pushes your local changes to the remote
- `git push -u origin [branch-name]` eg. `git push -u origin main`

## [Git branch](https://git-scm.com/docs/git-branch)
Creates a new "workspace", this space will not affect the main branch unless it is merged
- `git branch [branchName]`: Creates a new branch
- `git banch`: Lists all the branches

## [Git merge](https://git-scm.com/docs/git-merge)
Merges the content from another branch into my current branch
- `git merge [branchName]`: Merge the contents from `branchName` into my current branch
