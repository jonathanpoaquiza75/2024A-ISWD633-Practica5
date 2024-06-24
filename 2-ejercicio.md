# Ejercicio
Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:
- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a uan red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.
  
# Una vez creado tu archivo .yaml realiza la respectiva prueba 
# LUEGO DE EJECUTAR EL ARCHIVO
![image](https://github.com/jonathanpoaquiza75/2024A-ISWD633-Practica5/assets/109117858/a820d100-1f1d-4305-8db3-7dd20b1f31b3)

# ACCEDER A LOCALHOST:puertoDefinido para ingresar a SonarQube
Por el puerto 9000, que es uno de los puertos específicos para SonarQube
![image](https://github.com/jonathanpoaquiza75/2024A-ISWD633-Practica5/assets/109117858/cf0fad33-9432-410d-a301-20bfb2e0dbcd)
![image](https://github.com/jonathanpoaquiza75/2024A-ISWD633-Practica5/assets/109117858/ac994bc4-32ac-44ce-8e46-cffd353743fc)
