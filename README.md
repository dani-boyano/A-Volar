# A-Volar
En este proyecto trataremos de forma general, aprender sobre la drónica y el uso de drones, así como controlarlos, programarlos o comprenderlos y de forma más concreta, nuestro primer objetivo es marcar un simbolo de infinito rodeando dos postes, programando un dron DJI Tello.
## Descripción del dron DJI Tello
Este ligero dron está enfocado principalmente al ámbito educativo, cuenta con 4 motores interconectados a una respectiva hélice por cada uno de ellos, es decir, es cudricóptero, cada hélice esta protegida con un protector que hace seguro su uso en interiores, este dron contine una batería extraíble cuya duración puede rondar los 7 min, también posee una cámara frontal, además de sensores visuales en la panza del chasis, a parte de otros como lo son el giroscópio. También cuenta con la posibilidad de conectarse a su wifi y contorlarlo por medio remoto.

<br>

<img width="1080" height="10072" alt="Hélice" src="https://github.com/user-attachments/assets/7911ce0f-1064-41d1-bb01-84a954452f8d" />
<sup>Imágen Propiedad Daniel Boyano. Licencia libre. Edición mediante Canva..</sup>

## Normativa Europea de vuelo
La EASA (Agencia Europea de Seguridad Aérea) estipula según el decreto aprobado el 31 de de diciembre de 2020, una división en 7 categorías acerca de las aeronaves no tripuladas.

Clase c0:
| Masa máx. | Velocidad máx. |  
|:----:|--------|
| <250g | 19m/s |

Clase c1:
| Masa máx. | Velocidad máx. |  
|:----:|--------|
| <900g | 19m/s |
+Sistema Geo cosciencia

Clase c2:
| Masa máx. | Velocidad LOW |  
|:----:|--------|
| <4000g | 3m/s |
+Sistema Geo cosciencia

Clase c3:
| Masa máx. | Velocidad LOW |  
|:----:|--------|
| <25000g | 3m/s |
+Sistema Geo cosciencia
+Luces de vuelo nocturno

Clase c4:
| Masa máx. | Altura máx. |  
|:----:|--------|
| <25000g | <120m |
+Sistema Geo cosciencia
+Estabilizadores
+Return to home

Clase c5:
| Masa máx. | Velocidad máx. |  
|:----:|--------|
| <25000g | 5m/s |
+Sistema Geo cosciencia
+Estabilizadores
+Return to home
+Luces de vuelo nocturno

Clase c6:
| Masa máx. | Altura máx.|  
|:----:|--------|
| <25000g | +120m |
+Sistema Geo cosciencia
+Estabilizadores

<br>

## ¿Cómo debemos conectarnos al dron para poder controlarlo?
En primer lugar debemos de abrir la aplicación del dron TELLO, en segundo lugar debemos conectarnos a su misma wifi, tras activarla, nos conectaremos a la red TELLO-XXXXXX con la correspondiente matrícula del dron en cuestión. La conexió se abrá establecido cuando se muestre la visión de la cámara en el dipositivo conectado.

<br>

## Manual básico de programación con DroneBlocks
<img width="246" height="498" alt="descarga" src="https://github.com/user-attachments/assets/db01f341-5070-41ce-8b67-f61ce4dc5c09" />

<sup>Imágen propiedad Daniel Boyano. Licencia libre. Creación con DroneBlocks.</sup>

<br>

En este programa creado con DroneBlocks, observamos una secuencia de 12 bloques, los cuales determinan una acción en concreto por cada uno de ellos, el conjunto forma un programa que trasladado al dron, será trazado un símoblo de infinito en el aire.
Al iniciar este programa con el bloque take off, hacemos al dron despegar y estabilizarse en el aire, tras ello el dron avanzrá 120cm hacia adelante, posteriormente se moverá 240cm hacia la derecha manteniendo la cámara mirando hacia delante, consecutivamente el dron volará 240cm hacia atrás y 180 hacia la izquierda, siempre manteniendo la cámara mirando al frente, tras esto el dron en su misma posición, se moverá 45º hacia la derecha, tras ello avanzará frontalmente 504 cm y volverá a su posición original girando 45º hacia la izquiertda, consecuitivamente el dron avanzara hacia la izquierda 180cm y hacia atrás 260cm para así moverse hacia la derecha 180cm y hacia el frente y la derecha 100cm para posicionarse dentro del área requerida.

<br>

## Aplicaciones de la drónica





<br>

<footer>
    <p>© 2026 · Daniel Boyano Lomas · GitHub Pages</p>
