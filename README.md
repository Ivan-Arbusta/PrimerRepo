# PrimerRepo
## Commit inicial
Clone el repo que cree en github (git clone) y luego agregue el README (echo # README.md) despues hice un commit (commit -m "primer commit") y despues subi los cambios (git push origin main)

## Ignorar archivos
Agregue un archivo .gitignore (touch .gitignore) despues agregue el archivo privado.txt (touch privado.txt) y despues agregue la carpeta privada (mkdir privada) una vez hecho todo esto dentro del **.gitignore** agregue el nombre del archivo y la carpeta con una / antes del nombre de la carpeta

## Añadir ficheros y crear rama
Cree un fichero 1.txt (touch 1.txt) despues cree una rama (git branch v0.2) luego me movi a esa rama (git checkout v0.2) y despues cree 2.txt (touch 2.txt)
(git push --set-upstream origin v0.2) para conectar la rama local con la remota

## Hacer un merge
Cambie a la rama principal (git checkout main) y despues hice el merge (git merge)