# Ejercicio
Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:
- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a una red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.
   
para poder hacer el compose de sonar cube, h creado una carpeta aparte para no tener conflictos con el archivo compose del primer ejercicio
![Prueba del archivo .yaml](imagenes/c3.PNG)
una vez ejecutado el comando veremos el log de inicio del servidor por lo que si todo esta bien deberiamos poder entrar en el local host de nuestro programa.
![local Host de sonar cube](imagenes/c4.PNG)
