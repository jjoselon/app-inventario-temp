## Ejecutar el proyecto.

### Requisitos
1. MySQL 5.7
2. Java 11

## Paso a paso
1. Crear una base de datos MySQL llamada `inventario` version 5.7 si es posible. Debe estar disponible en localhost puerto 3306. El string de conexión esta en el archivo `application.properties`
2. Clonar este proyecto
3. Descomprimir este proyecto
4. En la raiz del proyecto ejecutar `./mvnw package` y luego `java -jar target/app-inventario-0.0.1-SNAPSHOT.jar`
5. Acceder a localhost:8080 (Si se requiere cambiar el puerto se debe ir al archivo `application.properties` agregando lo siguiente al final o inicio del archivo: `server.port=8081`
6. Probar la aplicación
7. Disfrutar
