# Ejercicios 3

### Ejercicio 1 -  Maquetación de componentes

Para practicar con los componentes de Bootstrap y su integración en el sistema de rejilla se propone la realización de un nuevo sitio web con el siguiente aspecto:

![Alt text](https://raw.githubusercontent.com/sr-jerly/bootstrap-exercise/main/assets/ejercicio-3-1.png)

Esta web está dividida en tres zonas: cabecera, zona de contenido y pie de página. En la zona de contenido se incluye 5 tarjetas (cards) con el mismo diseño. Como se puede ver en el diseño superior, el número de tarjetas por fila cambiará dependiendo del tamaño de la pantalla.r solamente cuando la pantalla sea del tipo xs.

Además, al pulsar sobre el botón de las tarjetas (todas tendrán el mismo enlace), se abrirá la siguiente página:
![Alt text](https://raw.githubusercontent.com/sr-jerly/bootstrap-exercise/main/assets/ejercicio-3-1.1.png)

Esta página tendrá un único diseño: barra superior, zona de contenido y pie de paǵina. En este caso en la barra superior se añadirá un botón para volver a la página anterior. En la zona de contenido tendremos un título, dos párrafos con texto de ejemplo, una imagen y dos botones (en la misma fila). El primer botón nos permitirá volver a la página anterior y el segundo mostrará una lista de acciones. Este segundo botón lo podemos implementar mediante un Dropdown que muestre las opciones: "Guardar favorito", "Exportar a PDF", "Imprimir" y "Compartir".