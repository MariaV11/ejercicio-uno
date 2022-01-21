Concepto Aprendidos

Terminal :conocida tambien como consola, es una pantalla donde mediante comandos ordenamos al sistema realizar acciones concretas.
Comandos:  secuencias de palabras especiales

Linea de Comandos: Es una aplicacion donde podemos escribir y ejecutar comandos para hacer distintas tareas como crear, modificar, eliminar y navegar en los archivos que hay en nuestro computador.

Que es Git:
Es un Sistema de Control de Versiones de codigo abierto, una aplicacion que permite gestionar los cambios que realizan sobre elementos de un proyecto o repositorio guardando asi versiones del mismo en todas sus fases de desarrollo.


Los Comandos mas importantes utilizados en Git.

Como Configurar en nuestra terminal para que nuestros repositorios esten configurados con nuestras credenciales. 

git Config --global user.name "define el nombre que se va a utilizar en los commit de forma global"
git config --global user.email "define el correo que se va utilizar en los commit"
 
Para saber si esta configurado con nuestra credenciales o para verificar utilizamos estos comandos
git config --list "nos muestra toda la configuracion de nuestra terminal"
git config --global -e

git status "Muestra los cambios realizados desde el ultimo commit y los nuevos incluidos en el siguiente commit"
git add "agrega los archivos de manera local"
git commit -m "descripcion de los cambios"
git init "se encarga de crear un repositorio"


