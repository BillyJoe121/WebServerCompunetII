# WebServerCompunetII
#Instructivo para correr el server en su pc:
Una vez clonado el repositorio en su pc deberá compilarlo con el codigo javac ServidorWeb.java
Luego de compilarlo correrlo con el codigo java ServidorWeb
O puede compilar y correr directamente con el botón de play de su IDE.
Luego podrá acceder a su navegador web y acceder a los archivos almacenados en el proyecto de la siguiente forma:
localhost:6789  Cargará el mensaje base para cuando no se asigna un nombre de archivo: "Server Multihilos"
localhost:6789/index.html    Tambien cargará el mensaje base: "Server Multihilos"
localhost:6789/index2.html   Cargará un segundo archivo html con el mensaje: "Server Multihilos 2"
localhost:6789/cat.gif     Cargará un archivo gif con un gato 
localhost:6789/imagen.jpg   Cargará un archivo de imagen de un paisaje con un lago

Un problema que fue recurrente fue el acceder a los archivos, en caso de que se esté apuntando correctamente y aun así 
aparezca el error 404 recomiendo ajustar en la configuracion del Run la ruta a la que accede para ejecutar
