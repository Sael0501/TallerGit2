# Taller de GIT

Clonar un repositorio remoto
git clone URL_REPO
git clone https://github.com/jhonynava/TallerGIT.git

Inicializar un repositorio
git init

Stagin (Revisar el estado actual de mis archivos)
git status

Agregar un archivo
git add nombre_archivo

Agregar varios archivos
git add .

Agregar comentario
git commit -m "Comentario X"

Modificar el commit (Hace referencia al último commit realizado)
git commit --amend -m "Mensaje"

Guardar cambios
git push -u nombre_repositorio nombre_rama
git push -u origin main

Agregar un repositorio remoto
git remote add nombre_repositorio URL_REPO
git remote add tallerGIT https://github.com/jhonynava/TallerGIT.git

Visualizar los repositorios remotos que tenemos
git remote -v

Actualizar cambios
git pull nombre_repositorio (Actualizar todos las ramas del repositorio)
git pull nombre_repositorio nombre_rama (Actualizar la rama especificada)
git fetch nombre_repositorio (Actualizar cambios sin fusionar los locales)
git fetch --all --prune (Actualizar el repositorio y borar ramas que ya no existen)

Subir cambios en el repositorio remoto
git push nombre_repositorio nombre_rama

Crear Rama o branch
git branch nombre_rama

Visualizar ramas locales
git branch

Visualizar ramas locales y remotas
git branch -a

Cambiarnos de rama
git checkout nombre_rama

Nota: Antes de realizar el merge te debes cambiar a la rama principal o la quieras fusionar
Realizar Merge
git merge nombre_rama_a_mezclar