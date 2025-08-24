# Comienzo del Readme

Hemos comenzado con el repositorio, vemos los comandos aprendidos

* vimos como crear el repositorio en la nube de github
* es importante saber que antes de todo esto se debe tener todos los pasos de ingreso y seguridad
* cuando hablo de seguridad y conectividad se trata de la ssh, es la clave publica y privada
* copiamos el enlace ssh
*  abrimos la terminal de gitbash como adm
* ingreasamos al area de trabajo donde queramos agregar el el repo
* en documents/github

´´´sh
    cd documents
    cd github
    git clone git@github.com:EnzoNavarro36/Prueba-Inicio-Repo.git
    cd prueba-inicio-repo
    git pull origin main
    git fetch
    git branch #veremos que estamos en la rama main por defecto
    touch readme.md #creamos el readme
    git status 
    git add .
    git commit -m "creamos el readme.md"
    git status
    git push origin main
´´´

> ¿como hacemos esto?

ingresamos al repositorio y luego solo presionamos punto<br>

´´´sh
    .
```

ingresamos todo esta informacion y terminamos