# GIT RAMAS O CONOCIDAS COMO BRANCHES

## CREAMOS REPOSITORIO

```sh
git init
```

## ver status de los archivos

```sh
git status
```

## alias... o git alias 
```sh
git config --global alias.st "status --short"
git config --global alias.a "add"
git config --global alias.c "commit -m"
git config --global alias.l "log --online"    
```
## Ver las diferencias entre el WD y el LR

```sh
git diff
```

## Comando para ver el commit que agregue

```sh
git show <numero de commit que figura en gitlog>
```

# CREAR UNA RAMA

```sh
git branch <nombre/rama>
```

# Comando para pasar de una rama a otra

```sh
git switch <nombre de rama>
```
## Crear una rama

```sh
git branch <nombre-rama> #crear una rama pero nos deja en la rama actual (main)
git switch -c <nombre-rama> # crea una rama y nos mueve a la rama que se creo
```

## Me muevo entre RAMAS

```sh
git switch <nombre-rama>
```
## Comparar entre RAMAS

```sh
git diff <nombre-rama-que-quiero-comparar> # comparo la rama actual contra la rama que indico

git diff dev # ejemplo comparo feature/ramas (rama en la que estoy) con dev

```

## Ver las ramas locales y remotas

```sh
git branch -a # me muestra las ramas locales y remotas
```

## Fusionando Ramas 

```sh
git merge <rama-que-quiero-fusionar> # estando parado en la rama original o sea en la main seria git merge feature/ramas
```
* lo mejor que puede pasar es la fusion -> Fast Forward -> git hace la fusion automaticamente
