# Primer_blog
Es un blog básico para aprender los comandos y usos de git & github

## Branches
para esto utilizamos tenemos herramientas como git branch, checkout, status en nuestro día a día para analizar las distintas ramas

## Github
Al trabajar con diferentes personas de forma remota pero

¿como podemos compartir el codigo de forma precisa eficiente?
como respuesta a esta pregunta nace github

## status, add y commit
dentro de git tenemos varias herramientas para seguir los avances de nuestro proyecto

### git add y commit
como su nombre lo describe en ingles, su función es la de agergar archivos, cambios que se realizaron dentro del proyecto, podemos agregar tanto archivos individuales como carpetas completas con "git commit <archivo>"

### Status diff
es un comando muy simple que compara dos versiones del mismo proyecto, estas pueden ser dos commits incluso entre distintas ramas, para usar esta herramienta basta con escribir el comando "git diff <Archivo 1> <Archivo 2>" donde pequeña nota tomara al primer archivo como punto de comparación,

### checkout
es un comando muy poderoso que nos permite volver a una rama y commits en especifico, esto suele ser muy util para hacer cambios


## rebase
Rebase tiene la función de modificar la historia del repositorio, esto usualmente genera conflictos pero hecho de manera correcta permite unir ramas de
forma limpia

esto solo deberia usarse en repositorios locales para errores puntales y correguir bugs

es importante recordar que esto modifica la historia del repositorio y esto es una muy mala practica 

>**Como podemos hacer esto**
>para esto tenemos que fusionarlo en un orden especifico, empezando por fusionar la principal con la externa y luego la rama externa a la principal
esto puede usarse para comparar las distintas versiones (ramas o más común entre commits) marcando las diferencias señalando las lineas de código y los distintos archivos
