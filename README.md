# Guia-Git-Git-Hub
Guia basica de Git y Git-Hub
pagina a desplegar




# holanda
## holdanda
###### holanda
- sarasa
```
 aaa
```
> sarasa

# CONCEPTOS Y COMANDOS BÁSICOS
- comandos [ubuntu-terminal](https://github.com/NahuelArn/Guia-Git-Git-Hub/blob/main/README.md#ubuntu-terminal)
- Conceptos generales
- Primeros pasos
- Puntos de partida
- Comandos básicos
- Comandos de consulta

 # CONCEPTOS GENERALES
- ¿QUÉ ES GIT?
  Git es un software de control de versiones diseñado por Linus Torvalds.
  
- ¿PARA QUÉ USAR GIT?
  Git sirve para llevar un control de versiones para tu codigo y trabajar en conjunto entre otras personas

- ¿QUÉ ES UN COMMIT?
  Un commit es una marca de tiempo en un historial, que podes volver a un punto en especial o elimarlo, en un commit se guarda los metadatos de la persona que modico   los archvivos 
  
- REMOTE Y LOCAL
  Forma remota, es tener desplegado un repositorio en una plataforma como GitHub (un respaldo en la nube)
  Forma local, es tener todo en un equipo, limitando las posibilidades de trabajar en conjunto entre varias personas


# Herramientas mas usadas
   ```
 - Para saber que version tengo de git.
   git --version
 
 - Configurar el nombre y mail del que va hacer cambios
   
  Ahora para para poner el mail
   git config --global user.gmail "pones el mail"

  Ahora para para poner el nombre
   git config --global user.name "pones el nombre"

 - Donde estoy parado
   ls
   
 - pushear desde Ubuntu terminal
   git push --set-upstream origin master
 
 - para saber donde estoy parado
   git bracnh
   
 - para crear una nueva rama
   git branch nombredelanuevarama
   
 - para moverme entre ramas y elegir en cual quiero trabajar
   git checkout “ramadondequieroempezarAtrabajar”
   
 - para ver donde estoy parado
   git checkout
 
 - para unir cambios de la rama Develop a la Master
   -git checkout master 
   -git merge develop
 ```

 # Aclaraciones
  si haces git init a una carpeta vacia, te va a tirar algun error, necesitas algun txt
  si tenes 2f2 en github vas a necesitar generar un token para pushear
  
 # Pasos para inicializar un proyecto
      De forma manual
     
     
      De forma mas facil
       - Crear una carpeta "para el proyecto"
       - Click derecho sobre la carpeta y tocar bash here, para inicializar git desde la carpeta
       - Git init  <-- enlazas el proyecto con git 
       - git remote add origin https://github.com/NahuelArn/reposiotiroPrueba.git ⇐ Enlazas el repositorio nuevo
       - Git status   ⇐ lo que esta en rojo no lo esta rastreando git o hay una modificacion
       - git add . ⇐ para que git rastree los elementos en rojo/ esta instruccion va a ir por todos los archivos en rojo
         - si se quiere rastrear un archivo en especifico 
           - git add nombreDelArchivo
       - git status ⇐ ahora todos los archivos van a estar en verde
       - git config --global user.email "you@example.com"  ⇐ mail de la persona que esta trabajando en este proyecto
       - git config --global user.name "Your Name"        ⇐ nombre //
       
       - git commit -m "identificador de commit"   ⇐ nombre del cambio producido o poque se realizo
       
       - git push -u origin master ⇐ subimos los cambios hechos al repositorio (desde windows bash)
       - git git push --set-upstream origin master ⇐ si lo hacemos desde ubuntu/linux terminal
       
       -te va pedir mail y usuario 
         - desde terminal de ubuntu/linux 
           poner mail y de contraseña tenes que generar un token 
         - desde bash windows solo mail y contraseña
         
 
# RAMAS Y RESOLUCIÓN DE CONFLICTOS
- Conceptos básicos de ramas
- Comandos para control de ramas
- Merge
- Pull request
- Variaciones de merge (rebase, fast-forward)
- Squash















--------------------------------------------------------


Qué versión de Git tengo instalada
    git --version
Configurar el nombre que sale en los commits  aparece en todas las modificaciones de repositorios global...
 git config --global user.name barcala
Configurar Email  Un solo repositorio
 git config --global user.email asdasd

todo esto me va a servir desde la terminal de git bash
clear             me limpia la consola

2 maneras de asociarse a un repositorio

fork
te quedas vinculado pero no tanto

clonar el repositorio
quedas vinculado al repositorio

mdkdir nombre            crea carpeta
cd tallergit            no me acuerdo
ls             no me acuerdo pero copia todo de la carpeta

touch archivo.txt             creas el archivo en la carpeta

mv permite renombrar o mover archivos
   $ mv <archivo-actual> <archivo-nuevo> # renombra el archivo
   $ mv <archivo> <ruta-del-directorio> # mueve el archivo dentro del directorio

    mkdir micarpeta
    mv archivo.txt micarpeta/
  pwd     me dice donde estoy parado


 # ubuntu-terminal
 
  ##Comando bash/ ubuntu terminal
   - ls me muestra las carpetas que tengo creadas, donde este parado
    ```
    ls
    ```
  ## Comando para posicionarme en el escritorio
    ```
    cd /mnt/d/Escritorio
    ```
  ## Crear carpetas en el escritorio desde la consola de Ubuntu
    ```
     1) me posiciono en el escritorio (con los camandos de arriba)
      mkdir nuevaCarpetaUbun
    ```
  ## Para moverme a otra carpeta 
    ```
    cd dondeQuieroMoverme
    ```
  ## Para renombrar una carpeta
    ```
    Tener encuenta que tenes que estar fuera de esa carpeta que quieras renombra
    ejemplo Escritorio/carpetaArnombrar… tendiras que estar parado en Escritorio/
 
    sudo mv nameViejo/ name nuevo
    ```
 
   ## Ir a mi directorio codigo
    ```
    cd /mnt/d/Codigo
    ```
   # Crear un archivo txt en una carpeta
    - 1) posicionarse en esa carpeta, donde queremos el txt

    - 2) ponemos pico, que nos va abrir un archivo de texto
 
     pico
   - 3) escribimos lo que queramos

   - 4) ctrl + 0 para Confirmar

   - 5) nombreAlarchivo.txt         Enter            
```
   definimos el nombre del archivo y le ponemos al final .txt si queremos un archivo txt

   si queremos algo para html… algo.html…javascript.js etc.. etc.. tambien se puede dejar sin poner nada en el texto

   6 ctrl + x para cerrar y confirmar
 ```
 
https://highlightjs.org/static/demo/
 
