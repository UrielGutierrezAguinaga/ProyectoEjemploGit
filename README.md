# Practica de Git: Introducción a Git
## Descripción 
Esta práctica consiste en crear un repositorio en GitHub y gestionarlo desde un repositorio local utilizando Git.
El programa principal, 'HolaMundo.py', muestra un mensaje en la terminal de "Hola Mundo". el objetivo de la pŕáctica es aprender a usar Git para el control
de versiones ( un primer acercacmiento ), incluyendo cómo crear y conectar repositoprios locales y remotos, hacer commits, y gestinar archivos ignorados mediante '.gitignore'.

## Instrucciones de Uso
1. Clonar el repositorio a tu máquina local:
2.  '''bash
3.   git clone <URL_DEL_REPOSITORIO>
4.  Ya que se clono el repositorio si tiene algún entorno de desarrollo se puede ejecutar en el, de lo contrario si cuenta con alguna distribución de Linux pued ejecutarlo en la temrinal
5.  o en windows instalando la variable de entorno correspondiente desde el simbolo de sistema puede realizar la compilación del mismo, durante la realización de esta práctica
6.  se utilizo Visual Studio Code.

## Comandos Utilizados
1. git init -> Inicializa un nuevo repositorio Git en el directorio actula.
2. git add <archivo> ->Añade archivos al área de preparación(staging).
3. git commit -m "mensaje" -> Realiza un commit con un mensaje descriptivo.
4. git -M branch main -> Cambia el nombre de la rama actual a main.
5. git remote add origin <URL_de_mi_repo> ->Conecta el repositorio local con el remoto en Github.
6. git push -u origin main -> Sube los cambios de la rama main al repositorio remoto.
7. git status -> Verifica el estado del repositorio y los archivos rastreados/no rastreados.
8. ssh-keygen -t rsa -b 4096 -C "urielgtzagn@gmail.com" -> Genera clave ssh para la autenticación en Github

##Notas sobre el archivo .gitignore
1. El archivo .gitignore se crea para identificar que archivos debes ser ignorados por Git al realizar un seguimiento de cambios del repositorio
2. Archivos ignorados  .log: Este archivo tiene registros de actividad, mensajes de depuración o errores generados durante la ejecución del programa. 
