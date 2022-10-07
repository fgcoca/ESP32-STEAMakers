# <FONT COLOR=#8B008B>Sensor infrarrojo para evitar obstáculos</font>

## <FONT COLOR=#007575>Enunciado</font>
Realizaremos un detector básico de obstáculos conectando el sensor a cualquiera de los conectores digitales libres, que son D3 y D5.

## <FONT COLOR=#007575>Teoría</font>
Se trata de un sensor digital que entrega una lectura de nivel TTL. El sensor está equipado con función de ajuste de distancia con una gran adaptabilidad a la luz ambiental y es de alta precisión. Tiene un diodo de transmisión y un fototransistor de recepción de infrarrojos. Cuando el rayo infrarrojo lanzado por el LED transmisor encuentra un obstáculo el rayo se refleja y el fototransistor lo recibe, siendo esto procesado por un circuito comparador que detectará el obstáculo y el LED indicador de la placa se iluminará. Cuando se usa para detectar líneas básicamente el rayo emitido se refleja si el color es blanco y no hay reflexión si el color es negro pudiendo así detectar estos colores de línea. Se puede ajustar la distancia de detección con las dos resistencias variables de que está equipado en un rango efectivo entre 2 y 40 cm.

Sus principales especificaciones son:

* Alimentación: 3,3 V o 5 V
* Consumo: ≥20mA
* Temperatura de trabajo: -10 ℃ a ＋50 ℃
* Distancia de detección: 2-40 cm
* Interfaz IO: 4 pines (-/+/S/EN)
* Señal de salida: voltaje TTL

Básicamente se puede utilizar para evitar obstáculos y para robots seguidores de línea bien en color blanco o bien en color negro. Su aspecto lo vemos en la figura siguiente:

<center>

![Aspecto del sensor](../img/img/evita-obtaculos/aspecto.png)

*Aspecto del sensor*

</center>

## <FONT COLOR=#007575>Programando la actividad</font>
Vamos a realizar un detector muy básico de obstáculos que nos muestre en la LCD el texto ¿Obstaculo? Y el mensaje SI o NO en función de que exista o no dicho obstáculo dentro del rango de detección del sensor. El programa de la imagen siguiente esta disponible como [ESP32-SM-obstaculos-inicial]().

<center>

![Actividad inicial con el detector de obstáculos](../img/img/evita-obtaculos/Actividad-inicial.png)

*Actividad inicial con el detector de obstáculos*

</center>
