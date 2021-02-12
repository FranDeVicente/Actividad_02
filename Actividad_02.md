![portada](imagenes/portada.png)


**Requerimiento 1:**

Queremos preparar nuestro servidor Linux para poder desplegar una aplicación web. Para ello, tenemos que verificar que están instalados:

1. Java
2. Apache
3. Tomcat
4. openSSH
5. MariaDB

# 01.- Java 

Java es muy funcional para crear aplicaciones y procesos o programas. Nos permite además ejecutar dichas aplicaciones después, en diversos Sistemas Operativos. 

Para instalar Java en un servidor de Linux, lo primero que tenemos que hacer es abrir nuestro terminal.

	- Podemos comprobar si ya tenemos instalado escribiendo el comando "java -version"
	
![comando1](imagenes/comando1.png) 

El propio terminal nos informa que no ha encontrado ninguna versión y además, nos dice cómo poder instalarla. Para ello, como muestra en la imagen, tenemos que hacer el siguiente comando:

	- sudo apt install default-jre

**Nota** Nos puede pasar que, como en mi caso, nos solicite antes una actualización para poder usar apt-get y simplemente, acutualizamos como muestro en la siguiente imagen
![comando2](imagenes/comando2.png)

Hecha la actualización, procedemos a instalar java
![comando3](imagenes/comando3.png) 

**Nota:** Si queremos saber qué versión de java nos ha instalado, volvemos a ejecutar el primer comando (java -version) y nos aparecerá en la consola
![comando4](imagenes/comando4.png)

# 02.- Apache

Ahora que ya tenemos java instalado en nuestra máquina virtual, vamos a proceder a instalar Apache. 

Apache es servidor web de protocolo HTTP. Además de ser multiplataforma, tiene fuente o código abierto, y permite que los propietarios de sitios web, puedan servir contenido a los usuarios de sus páginas, a través de sus peticiones. 

Para instalar Apache en un servidor Linux, debemos usar el siguiente comando:

	- sudo apt install apache2




