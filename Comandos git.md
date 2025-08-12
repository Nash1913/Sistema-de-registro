     Comandos git

git clone [url] = Crea el repositorio remoto en el disco local.
git status = Para ver el estado de los archivos en tu proyecto.
git pull = Para descargar los cambios del repositorio remoto.
git push = Para subir los cambios al repositorio remoto.git status = verificar el estado actual del proyecto.
git add . = Agregar los cambios realizados.
git commit -m = Para confirmar los cambios con un mensaje descriptivo.
git log --oneline = Se utiliza para ver todos los commit realizados.
git branch = Este comando se utiliza para listar las ramas existentes en tu repositorio.
git checkout -b <nombre_de_la_rama> = Este comando crea una nueva rama y cambia a ella inmediatamente.
git switch <nombre_de_la_rama> = Este comando se utiliza para cambiar entre diferentes ramas.
git push origin <nombre_de_la_rama> = Este comando se utiliza para subir (push) los cambios de una rama específica a un repositorio remoto (origin).
git restore --source <hash-del-commit> <archivo> = Se utiliza para restaurar una versión anterior del archivo.
git diff = Verificar en la consola los cambios realizados dentro de un archivo.
git branch <nombre_de_la_rama> = Este comando crea una nueva rama sin cambiar a ella directamente.
git merge = Este comando se utiliza para fusionar una rama con otra.
git init = Este comando se utiliza para inicializar un nuevo repositorio Git en un directorio.
git remote add = Este comando se utiliza para crear una conexión entre un repositorio local y un repositorio remoto, como un repositorio en GitHub.
git remote -v = Lista las conexiones remotas configuradas para el repositorio local.
git push -u origin main = Utiliza este comando para enviar los commits desde su rama local "main" a la rama remota "main" en el repositorio "origin" (que es el nombre que le dio a la conexión con el repositorio remoto en GitHub). La opción -u establece la relación de seguimiento, lo que significa que en el futuro, simplemente podrá usar git push para enviar los cambios desde su rama local "main" a la rama remota "main".
git remote add origin <URL_del_repositorio> = Utiliza este comando para establecer la conexión entre su repositorio local y el repositorio remoto en GitHub. <URL_del_repositorio> es la URL que GitHub proporciona para tu repositorio.
