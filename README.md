# flow1-timestamp
Este repositorio contiene el flow 1 de los ejercicios de introducción a NodeRed. 

Este flow simplemente realiza la impresión en consola de un timestamp.

Puedes encontrar el curso de introducción a NodeRed en el siguiente enlace

https://edu.codigoiot.com/course/view.php?id=817

### Requisitos
Para que el código de este repositorio funcione, es necesario contar con lo siguiente:

- Ubuntu 20.04
- NodeRed corriendo de forma local en el puerto 1880

### Guías
Para configurar correctamente NodeRed puedes consultar el siguiente enlace.

https://edu.codigoiot.com/course/view.php?id=817

Este flow usa un nodo insert en modo timestamp que manda datos cada 1 segundo a un nodo debug, el cual muestra el dato recibido en la consola debug.

### Funcionamiento

Para observar el funcionamiento de este proyecto deberás realizar lo siguiente.

1. Cargar el flow haciendo clic en el boton Deploy.
2. Observar los mensajes recibidos en la pestaña debug.

Podrás observar que cada segundo se manda el valor del timestamp del sistema.

Por: [Hugo Vargas](https://github.com/hugoescalpelo)
.

