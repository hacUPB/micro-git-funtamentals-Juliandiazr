 # CONSOLA
 En este archivo se va a hacer la explicación acerca de la consola que se va a utilizar durante este semestre, donde por medio de la siguiente lista se expondrá el contenido:
 1. ¿Cúal es la consola a utilizar?
 2. Navegacion en la consola
 3. Crear directorios y archivos
## ¿Cúal es la consola a utilizar?

Para este caso vamos a utilizar Git que sirve tanto para los sistemas operativos de Windows y MacOS, pero la apliación es diferente para ambos casos, primeramente para Windows se va a utilizar la aplicacion de Git Bash que se logra ver en la imagen 1.
![Imagen 1 Git Bash Diseño Windows](https://www2.seas.gwu.edu/~simhaweb/gatewaytocs/gitbash/gb1.PNG)
Mientras que para el sistema operativo MacOS se va a utilizar la aplicación de terminal y que por medio de esa app podremos ejecutar Git Hub y los repositorios que tengamos ahí, descargandolo por medio de gestor de un gestor de paquetes como Homebrew viendo el diseño de la aplicación en la imagen 2.
![Imagen 2 Diseño de la app de Terminal en MacOS](https://apple.teveotecno.com.ar/wp-content/uploads/2022/10/Terminal-Command-Window-Mac.png.webp)

## Navegación de la consola
 
Durante esta parte donde explicamos como se puede navegar por la consola, en este caso usando el sistema operativo MacOS y usando la aplicación Terminal, se va a enumerar cada uno de los "comandos" de navegación aprendidos.

1. **Comando PWD**:
El uso de este comando es para lograr identificar la ubicacion del directorio actual.

![Ejemplo comando PWD](https://www.solvetic.com/uploads/monthly_04_2019/tutorials-7463-0-04732000-1554132475.png)

2. **Comando Ls**:
Al usar este comando lo que va a hacer es que nos muestra el contenido de un directorio o "carpeta", añadiendo que si utilizamos el comando **ls -al** lo que va a hacer es mostrar una listas de todos los archivos incluidos los ocultos 

![Ejemplo ls y ls -al](https://cdn-jghdn.nitrocdn.com/WaAKrPwVavvRtmiuchNkiowpZvENVGmM/assets/images/optimized/rev-ae4f639/www.homehost.com.br/blog/wp-content/uploads/2023/09/Captura-de-tela-2023-09-02-135944.png)

3. Cambiar de Directorio 
En este caso para acceder un directorio o archivo que se desea, utilizamos el comando **cd nombre_del_directorio** y nos llevará al directorio solicitado, hay algunas "extensiones" que al ejecutarlas harán diferentes acciones de navegación.

 - **cd ..**: Lo que hace esta extensión es que nos va a devolver al directorio que estabamos antes del actual.

 ![Comando Cd ..](https://cdn-jghdn.nitrocdn.com/WaAKrPwVavvRtmiuchNkiowpZvENVGmM/assets/images/optimized/rev-ae4f639/www.homehost.com.br/blog/wp-content/uploads/2023/09/Captura-de-tela-2023-09-02-133758.png)

 ## Crear directorios y archivos 

 Para lograr crear un nuevo directorio nuevo lo que se va a hacer es que en el directorio actual se ejecute el comando **mkdir nombbre_del_directorio**, donde en la siguiente imagen lo que nos muestra como ejemplo es la ejecución de los comando **ls** visto anteriormente y el nuevo comando **mkdir**.

 ![Comando mkdir](https://interactivechaos.com/sites/default/files/capturas_de_pantalla/bash_command_mkdir_01.png)

Mientras que para lograr crear un archivo con cualquier extension como: .c, .md, .txt , etc... se ejecuta el comando **touch nombre_del_archivo + extensión**, como se logra obsevar en la siguiente imagen:
![Ejemplo de touch](https://josesalazarpantoja.gitbooks.io/comandos-basicos-linux/content/assets/y1.JPG)
En este ejemplo podemos ver la creación de un archivo llamado trabajo 1, con la extensión **.txt**.

Por otro lado, otros comandos importantes como el de renombrar los archivos o directorios, se utiliza el comando **mv nombre_actual nuevo_nombre** y para mover los archivos de un lugar a otro **mv nombre_origen nombre_destino**, y para borrar un archivo se ejecuta **rm nombre_del_archivo** y a continuación se mostrará en cada imagen un ejemplo de cada unos de los comandos.

- **Ejemplo de cambio de nombre**
![Ejemplo de cambio de nombre de archivo](https://www.solvetic.com/uploads/monthly_09_2019/tutorials-7463-0-25085500-1568363977.png)

- **Ejemplo de cambiar ubicaón de archivos**
