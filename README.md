# Basic-Git
## Basic Comands
0. Iniciamos git `git init`
1. Chequeamos el estado con `git status`
2. Agregamos al Staging area con `git add <file>`
3. Hacemos commit con `git commit -m "<mensaje>"`
4. Revisamos el log de commits con `git log`

## Remote
1. `git remote add origin <url>` agregamos un nuevo repositorio remoto
2. `git push -u origin main`
3. `git pull origin main`
4. `git remote -v` verificar origen del repo
5. `git remote set-url origin <https://github.com/USERNAME/REPOSITORY.git>` cambiar origen del repo

## Branches
1. `git fetch origin` otenemos las branches del repo
2. `git branch -a` lista de las branches
3. `git checkout -b <branch> origin/<branch>` cambiamos de branch

## Reset
1. `git reset HEAD~1` Para cancelar un commit que no vamos sincronizar con el remoto, para unix usamos `HEAD^`
