# Comandos vistos en el curso

## Inicializar repositorio

### Inicializar repositorio de git
git init

### Cambiar nombre de rama principal a "main"
git branch -M main

### Agregar URL de repositorio en la nube (Github, Gitlab, etc)
git remote add origin <url del repositorio>

### Subir por primera vez al repositorio en la nube
git push -u origin main


## Comandos básicos

### Pasar archivo modificado a preparado para el siguiente commit
git add <nombre de archivo>
git add .

### Crear un commit o punto de restauración de los archivos preparados
git commit -m "<descripción>"

### Volver a un commit anterior
git reset <id del commit>
git reset --hard <id del commit>

### Ver listado de commits
git log
git log --oneline


## Ramas y uniones

### Listar ramas creadas y ver rama actual
git branch

### Crear una rama nueva
git branch <nombre de la rama>

### Cambiar de una rama a otra
git checkout <nombre de la rama>

### Eliminar una rama existente
git branch -d <nombre de la rama>

### Unir ramas
git merge <nombre de la rama>