// Crear repositorio local
1. Crear la carpeta del repositorio
2. abrir la carpeta
3. Iniciar la consola de git (git bash)
4. git init // Iniciar un repositorio en la carpeta seleccionda 
5. agregar almenos un archivo al repositorio local
6. git add nombre_primer_archivo
7. git commit -m "Initial Commit" //commit inicial

// Crear repositorio github/gitbucket
1. git add remote origin https://github.com/joseplaza98/Repolocal.git  //url deñ repositorio creado
2. git push -u origin master

 // Comandos git
 //verificar estado del repositorio local
 git status
 
 // Agregar cambios
 git add Nombre_Arichivo_Modificado
 
 // Agregar todos los cambios si se tiene un archivo .gitignore 
 git add .
 
 //Para confirmar cambios
 git commit -m "Mensaje descriptivo del commit"
 
 //Sincronizacion de cambios remoto  local 
 git pull origin nombre_rama
 
  //Sincronizacion de cambios local remoto 
 git pull origin nombre_rama
