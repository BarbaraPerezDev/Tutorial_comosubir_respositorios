# Tutorial sobre como subir proyectos a Github desde git
La forma más facíl de subir repositoros a Github desde git.

(Recuerda que debe estar configurado el gitbash con tu identidad git config user.name "nombreUsuario" //agrega nombre de usuario y git user.email "nombreUsuariogmail.com" //agrega nuestro email)

1. **git init** (es para inicializar la carpeta del repositorio local)
2. **git remote add origin "URL repo" (Este copiarlo desde e github)** (le asigna el respositorio remoto)
![Imagen1 0](https://user-images.githubusercontent.com/115905949/220139833-e5443ce1-3211-402d-8bf2-df13eb97ad1c.jpg)  
3. **git status** (verficar que se haya subido y el estado del mismo)

4. **git fetch origin main** 

5.  **git pull origin main** ( actualiza al instante el repositorio local para reflejar ese contenido)

6.  **git status**

7. **git add .** (añade un cambio del directorio de trabajo en el entorno de ensayo)

8. **git status**

9. **git commit -m "Fist Commit"**

10.  **git push -u origin main** (se usa para subir  un nuevo repertorio GIT)


Recuerda que los commits permmiten hacer un seguimiento de los cambios que se hacen en el repositorio, son un historial de cambios.
