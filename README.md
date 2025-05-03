# AluraStore

## Descripción del Proyecto
Este proyecto tiene el objetivo de analizar 4 tiendas para la posterior venta de una de ellas, dicho analisis se hará con herramientas de python y se aplicaran visualizaciones graficas para facilitar la interpretacion de los resultados.
Los aspectos que evaluaremos serán:
1. Facturación total por tienda.
2. Ventas por categoria
3. Calificacion promedio
4. Productos más y menos vendidos por tienda.
5. Costo promedio de envio por tienda.

La tienda con el menor desempeño fue seleccionada para su posible venta, mientras que a las demas se le hicieron observaciones para un mejor desempeño.
Este analisis facilita la toma de decisiones comerciales importantes y como base para planes de mejora continua enfocados en la experiencia y satisfaccion del cliente.

## Estado del proyecto
Proyecto concluido el 3 de mayo de 2025. 
Este analisis fue desarrollado como ejercicio practico para aplicar conocimientos adquiridos basico sobre python y google colan.

## Demostración de funciones y aplicaciones
Este analisis cuenta con funciones que permiten analizar el rendimiento de las 4 tiendas, tanto en conjunto como de manera individual.
- filtradoCantidadCategorias(tiendaJuan):
Esta funcion fue definida con el objetivo de que recorriera y analizará cuántas veces aparecia una categoria en cada tienda, de ahi agruparlas y mostrar una cantidad de ventas por categoria.
- filtradoProoductosVentidos(tiendaJuan):
Esta funcion fue definida con el objetivo de que recorriera y analizara cuantas veces aparecia un producto en la lista de cada tienda, de ahi se usaria max() y min() para que nos devolviera los productos más y menos vendidos.

## Acceso al Proyecto
Este proyecto está desarrollado en google colab, por lo cual solo requiere una cuenta google activa para poder usar colab.
Lo primero que haremos será abrir el documento llamado ALuraStoreLatam.ipynb: 

![Abrir Proyecto](imagenesAluraStore/Captura%20de%20pantalla%202025-05-03%20125909.png)

Seguidamente vamos a abrir el google colab, dando click en open in colab: 

![Abrir el colab](imagenesAluraStore/Captura%20de%20pantalla%202025-05-03%20125423.png)

Algo muy importante, ya que hayamos abierto colab e iniciado sesion deberemos conectarnos al documento para facilitar la experiencia del usuario:

![Conectarnos al colab](imagenesAluraStore/Captura%20de%20pantalla%202025-05-03%20125508.png)

Finalmente, para que todo se ejecute de manera correcta vamos a darle click en ejecutar todo, todo esta ordenado de manera lineal entonces al ejecutar todo junto no nos arrojara ningun error.

![Ejecutar todo](imagenesAluraStore/Captura%20de%20pantalla%202025-05-03%20125518.png)

## Tecnologías utilizadas

- python 3.10 como el lenguaje principal
- google colab como entorno de desarrollo.
- pandas como ciclioteca para manipulacion y analisis de datos
- matplotlib para la realizacion de las graficas
  
## Personas Contribuyentes
-Profesor Álvaro Hernando Camacho Diaz: Encargado de enseñarnos la base del lenguaje python

-Profesor Wilfredo Antonio Rojas Camejo: facilito el proyecto y explico la logica detras del analisis de las tiendas

## Personas Desarrolladoras del Proyecto
-Laila Zoe Castillo Rangel: Desarrollo, analisis de datos y documentacion del proyecto y presentacion en github.
