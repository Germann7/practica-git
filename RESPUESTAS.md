# Respuestas del reto final

## a) ¿En qué se diferencian git restore y git revert?

`git restore` sirve para descartar cambios de archivos en el directorio de trabajo o en el área de preparación. `git revert` deshace los cambios de un commit creando un nuevo commit, sin borrar el historial anterior.

## b) ¿Por qué password.txt sigue siendo un problema aunque ya no aparezca en la última versión?

Porque el archivo puede seguir apareciendo en el historial de commits de GitHub. Si contiene una contraseña real, alguien podría recuperarla. Por eso hay que cambiar la contraseña y proteger o eliminar las copias históricas.

## c) ¿En qué se diferencian git rm y git rm --cached?

`git rm` elimina el archivo del ordenador y del seguimiento de Git. `git rm --cached` lo quita del seguimiento de Git, pero conserva el archivo en el ordenador.