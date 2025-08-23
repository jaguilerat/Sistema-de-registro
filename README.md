<h1>Sistema de Registros</h1>

- Estado del proyecto: En construcción.
  
Para ejecutar el sistema, debes poner:

``` npm install react ```

Sistema de Registros 2 : 

``` git pull ```
El comando sirva para poder descargar la información desde el repositorio, es para verificar los ultimos cambios


``` git status ```

Muestra el estado actual de los cambios que tenemos en la carpeta local


``` git add . ```
Con el caracter . se actualizan atomaticamente todos los archivos con cambios realizados.


``` git commit ```

Comando para generar commit en github

``` git commit  -m ```
Este comando deja un comentario al comit que se esta haciendo


``` git push ```

Este comando sube los cambios a github

``` git log --oneline ```

Podemos ver una version a restaurar dentro del proyecto


``` git restore --source  315059c ```

con el comando git restore -- source Hash, se puede restaurar una versión anterior de un archivo

``` git branch ```

Me muestra las ramas que tiene el proyecto o los entornos de trabajo que tenemos dentro del github


``` git checkout -b desarrollo ```

Crea un entorno nuevo el cual sera destinado para generar un ambiente de desarrollo


``` git restore switch main ```

Comando que sirve para cambiar de ambiente dentro de la consola en github
``` git checkout -b nombre_rama ```

comando que crea una nueva rama en github


``` git push origin desarrollo  ```
