# Laboratorio 7
## Sección I. - Introducción a JDBC
1. Clonar el proyecto MyBatis_Introduction_VideoRental de GitHub donde se realizará la implementación completa del laboratorio.

  A continuación, clonamos el proyecto MyBatis_Introduction_VideoRental de GitHub de la siguiente forma.
  
  <img  src="https://github.com/JuanMunozD/CVDS7/blob/master/Im%C3%A1genes/Punto1.png">

2. Descargue el archivo JDBCExample.java y agreguelo en el paquete "edu.eci.cvds.sampleprj.jdbc.example".

  Ahora, descargamos el archivo JDBCExample.java y lo agregamos en el paquete "edu.eci.cvds.sampleprj.jdbc.example".
  
  <img  src="https://github.com/JuanMunozD/CVDS7/blob/master/Im%C3%A1genes/Punto2.png">

3. Desde esta clase se realizará una conexión a una base de datos MySQL por medio de JDBC y sus "Prepared Statements".

4. En un motor de base de datos SQL se tiene un esquema con el siguiente modelo de base de datos (para registrar pedidos sobre productos):

  <img  src="https://github.com/JuanMunozD/CVDS7/blob/master/Im%C3%A1genes/Punto4Imagen.PNG">
  
5. Revise la documentación de ‘PreparedStatement’, del API JDBC.

6. En la clase JDBCExample juste los parámetros de conexión a la base de datos con los datos reales:

  ```
  Url: jdbc:mysql://desarrollo.is.escuelaing.edu.co:3306/bdprueba
  Driver: com.mysql.jdbc.Driver
  Usuario: bdprueba
  Contraseña: prueba2019
  ```
  
  Para conectarnos a la base de datos, llenamos los campos de la siguiente forma.
  
  <img  src="https://github.com/JuanMunozD/CVDS7/blob/master/Im%C3%A1genes/Punto6-11.PNG">
  
  Y en el código, realizamos las siguientes modificaciones a **String user** y **String pwd**.
  
  <img  src="https://github.com/JuanMunozD/CVDS7/blob/master/Im%C3%A1genes/Punto6-2.png">

7. Implemente las operaciones faltantes:
  1. nombresProductosPedido
  2. valorTotalPedido - El resultado final lo debe retornar la base de datos, no se deben hacer operaciones en memoria.
  3. registrarNuevoProducto - Use su código de estudiante para evitar colisiones.

8. Verifique por medio de un cliente SQL, que la información retornada por el programa coincide con la que se encuentra almacenada en base de datos.
