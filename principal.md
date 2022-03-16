# Principal

## Local

Este e o ficheiro principal

**Comando 1**
> git init
> git config --global user.email "xxxx@email.com"
> git config --global user.name "nomeusuuario"

**Comando 2**
> git add principal.md
> git commit -m "ficheiro principal.md"


**Comando 3** 
> echo "*.bak">>.gitignore


**Comando 4**
> git add .
> git commit -m "cambios"

## Subir a nube

- Ligazón do repo :

>git@github.com:pbelay/RepoCursoDia02.git

- Comando

> git remote add origin git@github.com:pbelay/RepoCursoDia02.git
> git branch -M main
> git push -u origin main

-Subir contido

>git add .
>git commit -m "actualizado"
>git push -u origin main

