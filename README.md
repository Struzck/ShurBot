# ShurBot
El shurbot estará controlado por un Arduino y será alimentado por una serie de pilas. Tendrá tres modos de trabajo que podrán ser elegidos mediante un potenciómetro, dependiendo del modo que se elija se encenderá uno de los tres leds que hay al lado de este.
El primer modo corresponde al automático, que consiste en que el shurbot se desplaza y esquiva obstáculos de forma automática. Esto se consigue gracias al sensor HC-SR04, que emite y recoge ultrasonidos; ha sido programado para que el shurbot gire cuando esté a una distancia de un metro o menos del obstáculo. Se baraja la posibilidad de añair un buzzer que vaya pitando conforme se acerca a un obstáculo, aunque puede que sea demasiado molesto por el ruido. 
El segundo modo nos permite controlar el shurbot por radiocontrol, usando un mando que emite señales infrarrojas y que son recogidas por el sensor TL 1838. 
El tercer modo consiste en volver al Shurbot en un robot seguidor de línea. El funcionamiento es el siguiente: al pintar una línea de color negro en una superficie blanca el shurbot seguirá la línea, pudiendo dibujar la ruta que queremos que siga.



## Prototipo

![alt tag](https://raw.githubusercontent.com/Struzck/ShurBot/master/images/Croquis%201.png)

![alt tag](https://raw.githubusercontent.com/Struzck/ShurBot/master/images/croquis%201%20componentes.png)



## Componentes

- x3 LEDS
- Potenciometro
- Sensor TL 1838
- Buzzer*
- x4 CNY70
- x2 Ruedas y sus respectivos motores
- Sensor HC-SR04
- Arduino
- Modulo L298N
- x2 Portapilas
- Cables y breadboards



## Version 0.0

![alt tag](https://raw.githubusercontent.com/Struzck/ShurBot/master/images/SAM_1667.JPG)

![alt tag](https://raw.githubusercontent.com/Struzck/ShurBot/master/images/SAM_1670.JPG)


## Version 0.1

![alt tag](https://raw.githubusercontent.com/Struzck/ShurBot/master/images/SAM_1677.JPG)

![alt tag](https://raw.githubusercontent.com/Struzck/ShurBot/master/images/SAM_1678.JPG)


## Version 0.2

![alt tag](https://raw.githubusercontent.com/Struzck/ShurBot/master/images/SAM_1759.JPG)

![alt tag](https://raw.githubusercontent.com/Struzck/ShurBot/master/images/SAM_1760.JPG)
