## Ejecutar el proyecto.

### Requisitos
1. MariaDB 10.4.17 (MySQL 5.7)
2. JDK 11
3. Git

## Paso a paso
1. El string de conexión para la base de datos es el siguiente: `jdbc:mysql://localhost:3306/inventario`. Por la misma razón se debe crear una base de datos llamada `inventario` y estar disponible en el puerto puerto 3306 de localhost. Si se requiere modificar el string de conexión esta localizado en el archivo `application.properties` dentro de este mismo proyecto (por si se requiere cambiar el puerto)
2. Clonar este proyecto con `git clone https://github.com/jjoselon/app-inventario-temp.git` (Es importante verificar que no se tenga bloqueado el acceso por politicas de seguridad a repositorios publicos como lo es GitHub)
3. Una vez clonado ejecutamos ´cd app-inventario-temp/´ para ubicarnos en la raiz del proyecto.
4. Una vez estemos dentro de la raiz del proyecto ejecutar `./mvnw package` para construir el proyecto (Nos referimos a 'construir' como el proceso de descargar dependencias, ejecutar pruebas, compilar el código, etc) y enseguida ejecutar `java -jar target/app-inventario-0.0.1-SNAPSHOT.jar` para correr el proyecto construido.
5. Acceder a http://localhost:8080 (Si se requiere cambiar el puerto se debe ir al archivo `application.properties` agregando lo siguiente al final o inicio del archivo: `server.port=8081`
6. Probar la aplicación
7. Disfrutar
