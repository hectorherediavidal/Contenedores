# Contenedores
Tarea contenedores Docker


# Ejemplo 1
  ![ejemplo1](https://github.com/hectorherediavidal/Contenedores/blob/main/img/ejemplo%201.PNG "")
  <br>
  <br>
  
   Docker pull ubuntu:18.04 es un comando que descarga una imagen de Ubuntu, pero no hace falta usar este comando.
   ### Podemos directamente usar el comando "docker run -it ubuntu:18.04 /bin/bash" que nos descarga la imagen de Ubuntu y entra al usuario root directamente
    docker run -it ubuntu:18.04 /bin/bash
   ![ejemplo1](https://github.com/hectorherediavidal/Contenedores/blob/main/img/1.PNG "")
   
   
 # Ejemplo 2
  ![ejemplo2](https://github.com/hectorherediavidal/Contenedores/blob/main/ejemplo%202.PNG "")
  <br>
  <br>
  
   #### El comando "docker run ubuntu:18.04 ls /" entra a la carpeta donde hemos instalado la imagen de Ubuntu en el ejemplo anterior y hace un "ls", que muestra el contenido de esa carpeta
    docker run ubuntu:18.04 ls /
   ![ejemplo2](https://github.com/hectorherediavidal/Contenedores/blob/main/2.PNG "")
   
   
   
  # Ejemplo 4
  ![ejemplo4](https://github.com/hectorherediavidal/Contenedores/blob/main/ejemplo%204.PNG "")
  <br>
  <br>
  
   #### El comando "docker run -it -w /etc debian:9 ls" descarga una imagen de Debian, hace un "ls" en la carpeta etc de Debian y por ultimo sale de ese contenedor
    docker run -it -w /etc debian:9 ls
   ![ejemplo4](https://github.com/hectorherediavidal/Contenedores/blob/main/4.PNG "")
   
   
   
   # Ejemplo 4.1
  ![ejemplo4](https://github.com/hectorherediavidal/Contenedores/blob/main/ejemplo%205.PNG "")
  <br>
  <br>
  
   #### El comando "docker ps" muestra solo los contenedores que tenemos en ejecución en ese momento
    docker ps
   ![ejemplo4](https://github.com/hectorherediavidal/Contenedores/blob/main/5.PNG "")
   <br>
   <br>
   
   
   
   # Ejemplo 4.2
  ![ejemplo4](https://github.com/hectorherediavidal/Contenedores/blob/main/ejemplo%206.PNG "")
  <br>
  <br>
  
   #### El comando "docker ps -a" muestra todos los contenedores que tengamos, estén en ejecucion o parados
    docker ps -a
   ![ejemplo4](https://github.com/hectorherediavidal/Contenedores/blob/main/6.PNG "")
   <br>
   <br>
   
   
   
   
   
   
