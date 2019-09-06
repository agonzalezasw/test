# Evaluacion American School Way Desarrollador Senior

# Prueba Técnica

La presente prueba técnica pretende evaluar sus habilidades y competencias para el cargo de **Desarrollador Senior** de **American School Way** [link](https://www.americanschoolway.edu.co).  
El test consta de 4 problemas los cuales debe resolver y ser entregados el dia Lunes 09/09/2019.

## Cómo responder la prueba técnica?

Para responder la prueba técnica debe realizar un **fork** de este proyecto en su cuenta personal de **Github** siguiendo las siguientes convenciones:

1. Crear una carpeta **src** que contenga las siguientes subcarpetas: **js**, **php**,  **html**, **mysql**
2. Crear los tres ejercicios, con su correspondiente solución en cada una de las subcarpetas según corresponda
3. Realizar un commit y push hacia **su repositorio** con la solución para cada uno de los puntos

### Prueba 1: Javascript
Defina una función llamada `pipeme()` en el objeto `String`. Esta función no debe aceptar argumentos. Al llamar a esta función debe:
1. Transformar cada caracter del string en mayúsculas
2. Insertar entre cada caracter un pipe `|`. Así el resultado sería por ejemplo `"biomedica" -> "B|I|O|M|E|D|I|C|A"`.
3. Crear esta función en un archivo JS que pueda ser ejecutado mediante la consola de **un navegador web**. No debe utilizar dependencias externas para realizar esta tarea.

### Prueba 2: PHP
Utilizando el administrador de dependencias [Composer](https://getcomposer.org/) instale y utilice Gruzzle v6.x para obtener todos los álbumes de `Daft Punk` desde la API de Spotify [link](https://developer.spotify.com/web-api/endpoint-reference/) e imprimir su `nombre` y `fecha de lanzamiento` mediante `echo` separando los datos mediante `;`: `ej: Homework;1997`

1. Cree una clase que encapsule toda la lógica para realizar la llamada a la API
2. Presente cada uno de los álbumes cono una nueva línea.

### Prueba 3: HTML BOOTSTRAP
Para el siguiente ejercicio se requiere maquetar la imagen referenciada haciendo uso de html y framework css bootstrap
https://raw.githubusercontent.com/agonzalezasw/test/master/escuela_cocina.png

### Prueba 3: Mysql
El siguiente ejercicio requiere generar las tablas para recrear el proceso de inscripcion de una matricula estudiantil la cual contendra estudiantes, matricula cursos  tomar en cuenta para dicho modelo las buenas practicas adjuntar archivo sql y modelo entidad relacion adicionalmente crear un store procedure que permite modifcar la fecha de registro de la matricula.
