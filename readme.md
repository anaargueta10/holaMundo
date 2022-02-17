# GIT

## Comandos:

### Comandos Globales:

+ git --version:
    >Me muestra mi versión actual de git.
+ git config --global user.name "usuario de github"
    >Asigna mi usuario a mi computadora.
+ git config --global user.email "correo que corresponde al usuario"
+ git config user.name
    >Nos enseña el usuario actual.
+ git config user.email
    >Nos enseña el correo del usuario actual.
+ Is
    >Nos muestra la lista de archivos en la carpeta que estemos.

### Comandos de repositorio:

+ git init
    >Inicia el repositorio (agrega la palabra master en celeste a la ruta) 
+ git status
    >Nos muestra el estado de todos nuestros archivos con un código de colores.
    + rojo: Untracked 
    + verde: Stage
+ git add 
    >Incluye nombre si solo quiero uno
+ git add . 
    >Agrega a Stage todos los archivos
+ git commit - "descripción"
    >Agrega al repositorio todo lo que esta en Stage con un nombre y marca te tiempo.
+ git log
    >Nos muestra el historial e información de los commit.

### Comandos de repositorio remoto (github):
+ git remote add origin https://github.com/anaargueta10/holaMundo.git
    >Agrega con el nombre origin la ruta remota
+ git push -u origin master
    >Empuja la rama hacía la ruta remota
+ git pull origin 
    >Jala el repositorio desde la ruta remota
    +Al existir conflictos:
    >Primero: Seleccionar el cambio a mantener
    >Segundo: Realizar un git add
    >Tercero: Realizar un commit
    >Esto solucionará el conflicto y me permitirá seguir trabajando