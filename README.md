### Iniciar un proyecto Git

```shell
git init
```

### Preparar los archivos

```shell
git add <name>
```
```shell
git add -A
```

```shell
git add .
```

```shell
git add *
```

### Guardar cambios en el repositorio local

```shell
git commit -m "los cambios realizados"
```

### Ver informacion del o los repositorios remotos

```shell
git remote -v
```

### Añadir repositorio remote 

```shell
git remote add <name> <url>
```

### Enviar cambios al repositorio remote

```shell
git push <name> <branch>
```

### Bajar cambios al repositorio local desde el repositorio remoto

```shell
git pull <name> <branch>
```

### Generar una nueva rama (branch)

```shell
git branch <name>
```

```shell
git checkout -b <name>
```
### Cambiar de rama (branch) o activar

```shell
git checkout <name>
```

### Unir ramas (branch) nota: une los cambios a la rama activa actualmente

```shell
git merge <branch>
```

### Eliminar una rama (branch)

```shell
git branch -D <name>
```

### Deshacer cambios guardados (commit)

Mantengo los cambios:
```shell
git reset --soft HEAD~1
```

Elimino los cambios:
```shell
git reset --hard HEAD~1
```

```shell
git checkout <name>
```