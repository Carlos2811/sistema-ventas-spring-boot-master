# Sistema-ventas-spring-boot
 Un sistema de ventas usando Java, Spring MVC, MySQL y Bootstrap


## Descargar código del sistema de ventas Spring Boot y compilar
Lo que se tiene que hacer para que funcione el proyecto es instalar gradle, MySQL y Java.

Después se ejecuta el programa con:

`gradlew bootRun`

Y crea el jar usando:

`gradlew build`



La url de funcionamiento es _http://localhost:8080/productos/mostrar_.


## Esquema de base de datos
No es necesario proporcionar el esquema de la base de datos pues la migración se hace automáticamente al ejecutar el proyecto; sin embargo
se puede encontrar un esquema en src/main/resources/

