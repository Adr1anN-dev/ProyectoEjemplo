# ProyectoEjemplo
Mi primer repositorio de Github
Autor: Adrian Ruiz
/* COMANDOS PARA GIT */
// git --help --> ayuda en git.
// git config --list --show-origin --> muestra la configuracion de git.
// git config --global user.name "username" --> agrega el usuario de git.
// git config --global user.email "micorreo@hotmail.com" --> agrega el email de git.
// ssh-keygen -t rsa -b 4096 -C "micorreo@hotmail.com" --> crea la llave para conectar git con github.
// clip < ~/.ssh/id_rsa.pub --> copia la llave en el portapapeles.
// mkdir ejemplo --> crea directorio en la ruta origen.
// cd ejemplo --> entra en una carpeta.
// git clone git@github.com:nombredeusuarioengithub/ProyectoEjemplo.git --> clona el proyecto de github en git con la sentencia copiada del repositorio de github desde el boton de code.
// ls --> similar a dir en windows, muestra el contenido de la carpeta.
// git status --> verifica el estatus del repositorio.
// git commit -am "Agregar autor de archivo" --> guarda los cambios en git local.
// git push origin main --> sube los cambios a github.
// git add index.html --> agrega un archivo nuevo a git local luego hay que hacer commit y push para actualizar.
// git fetch --> actualiza la metadata del repositorio local.
// git pull origin main --> actualiza el repositorio local.
// git clone <repo> --> clonar repositorio de github.
// git branch Dev1 --> crear una nueva rama de desarrollo.
// git checkout Dev1 --> cambiar a la rama creada.
// git checkout -B Dev2 --> crear una nueva rama de desarrollo y entrar en ella.
// git merge main Dev2 --> agregar la rama principal a la Dev 2.
// git reset --hard --> devolver el proyecto local de git al ultimo commit funcional.
// git checkout HEAD -- README.md --> devolver un archivo en especifico al ultimo commit funcional.
// git log --> historial de commits en git. ("q" para salir).
// git log --oneline --> historial de commits en git. (reducido) ("q" para salir).
git log --oneline --graph --> historial de commits en git. (reducido) (graficado) ("q" para salir).
git checkout 49ad27b --> regresar al commit indicado por el indice sacado del historial.
git reset --hard HEAD-1 --> devolver al ultimo commit.
git checkout HEAD-1 --> regresar al ultimo commit sin restaurarlo.
git checkout -B issue_1 --> cuando hay issues (disfuncionalidades en el proyecto) crear un branch por cada issue.

# Documentacion 2 (Dev2)
// Documentacion del desarrollador 2
# Documentacion 1 (Dev1)
// git commit -am "doc dev1" --> guardar los cambios en git local.
// git push origin Dev1 --> subir los cambios a la rama creada.
// git checkout main --> cambiar a la rama main.
