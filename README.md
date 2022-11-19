# Git basics

- Manejador de versiones, que se encarga de mantener un registro de todos los cambios dentro de un 
repositorio (Folder)
- Un sistema distribuido
- Repo local != repo remoto

## Git init
Initializes a local git repository

## Git status
Muestra el estado actual de los cambios dentro del repositorio

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
- `git commit -am "Another relevant message"` 
