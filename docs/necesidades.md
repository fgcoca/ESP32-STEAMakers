# <FONT COLOR=#8B008B>Lo que vamos a necesitar</font>
Relacionamos el equipamiento mínimo que se requiere para comenzar a trabajar y se recomiendan algunas cosas mas.

## <FONT COLOR=#007575>Software</font>
Para llevar a cabo la **programación** de los **retos** es necesario estar registrado en **ArduinoBlocks** y se recomienda hacerlo con un nombre real para posteriormente facilitar la localización si es necesaria y se tiene que hacer con un correo real pues se necesita confirmación para crear la cuenta.

* La tarea es sencilla y está perfectamente descrita en el Free Book (online & updated) que podemos encontrar en los recursos de la plataforma www.arduinoblocks.com.
* Creamos un "nuevo usuario" utilizando para ello una cuenta de correo válida donde vamos a recibir un correo de confirmación para activarla.
* Ya estamos en condiciones de crear nuestros propios proyectos en la plataforma como veremos mas adelante.

<center>

![Crear un nuevo proyecto](./img/img/inicio/nuevo-proyecto.png)

*Crear un nuevo proyecto*

</center>

* Descarga e instala en tu ordenador y para tu sistema operativo la última versión de [ArduinoBlocks - Connector](http://www.arduinoblocks.com/web/site/abconnector5). Este programa vamos a necesitarlo para poder comunicar nuestra placa con la plataforma a través del puerto USB de nuestro ordenador.

El programa debe estar en ejecución, minimizado para que no nos moleste, siempre que queramos grabar un programa y tiene el aspecto que vemos en la figura siguiente:

<center>

![ArduinoBlocks Connector](./img/img/inicio/AB.png)

*ArduinoBlocks Connector*

</center>

### <FONT COLOR=#AA0000>Hardware imprescindible</font>
Una placa Imagina TdR STEAM versión 2.0 como la de la imagen siguiente:

<center>

![Shield TdR-STEAM V2.0](./img/img/inicio/TdR-STEAM.png)

*Shield TdR-STEAM V2.0*

</center>

Una placa ESP32 Plus STEAMakers.

<center>

![ESP32 Plus STEAMakers](./img/img/inicio/ESP32_STEAMakers.png)

*ESP32 Plus STEAMakers*

</center>

### <FONT COLOR=#AA0000>Hardware recomendado</font>
A continuación exponemos el material adicional que vamos a emplear en esta colección de retos que no es otro que el incluido en el [Kit Imagina TdR STEAM](https://shop.innovadidactic.com/es/para-centros-educativos/1445-kit-imagina-tdr-steam-basado-en-arduino.html) comercializado por la empresa [INNOVA DIDACTIC](https://shop.innovadidactic.com/es/).

* Mando de control remoto por infrarojos para utilizar en conjunto con el sensor de infrarojos integrado en la placa TdR-STEAM.

<center>

![Mando a distancia por IR](./img/img/inicio/mando-IR.png)

*Mando a distancia por IR*

</center>

* Pantalla LCD 1602 IIC (I2C) de 2 línea de 16 caracteres. Nos va a permitir mostrar mensajes de texto e irá conectada al conector I2C de la placa TdR-STEAM.

<center>

![LCD 1602 I2C](./img/img/inicio/LCD1602.png)

*LCD 1602 I2C*

</center>

* Sensor de sonido analógico (con potenciometro). Se utiliza básicamente para detectar el nivel sonoro ambiental. El potenciometro permite ajustar el nivel de ganancia.

<center>

![Sensor de sonido analógico](./img/img/inicio/Microfono.png)

*Sensor de sonido analógico*

</center>

## <FONT COLOR=#007575>Caja contenedor imprimible 3D</font>

### <FONT COLOR=#AA0000>Partes</font>
La caja está compuesta de una base, una tapa, tres tornillos y un destornillador. La base con indicación de donde va a ir cada elemento la vemos en la imagen siguiente:

<center>

![Base o caja](../img/img/inicio/caja.png)

*Base o caja*

</center>

El aspecto de la tapa lo tenemos en la imagen siguiente, donde podemos observar el orificio estriado que servirá para colocar el destornillador cuando finalicemos el montaje.

<center>

![Tapa](../img/img/inicio/tapa.png)

*Tapa*

</center>

Finalmente en la imagen siguiente podemos ver el aspecto de los tres tornillos que sujetan la tapa a la caja y el del destornillador.

<center>

![Tornillos y destornillador](../img/img/inicio/tornillo-destornillador.png)

*Tornillos y destornillador*

</center>

## <FONT COLOR=#007575>**Archivos stl listos para descargar e imprimir**</font>
Los archivos de diseño original son los siguientes:

* Archivo STL de la caja: [caja.stl](caja-TdR-STEAM/caja.stl)
* Archivo STL de la tapa: [tapa.stl](caja-TdR-STEAM/tapa.stl)
* Archivo STL del tornillo: [tornillo.stl](caja-TdR-STEAM/tornillo.stl)
* Archivo STL del destornillador: [destornillador.stl](caja-TdR-STEAM/destornillador.stl)
* Todos los archivos en un zip: [caja-TdR-STEAM.zip](caja-TdR-STEAM/caja-TdR-STEAM.zip)

Algunos de los archivos anteriores se han modificado para mejorar el diseño en algunos aspectos y sobre todo para dejar libre un hueco en la base que haga accesible la tarjeta uSD. Los <font color=#FF0000><b>archivos modificados</font color></b> son los siguientes:

* Archivo FreeCAD con las modificaciones: [modificaciones.FCStd](caja-TdR-STEAM/modificada/modificaciones.FCStd)
* Archivo STL de la caja modificada: [caja.stl](./caja-TdR-STEAM/modificada/caja.stl)
* Archivo STL de la tapa: [tapa.stl](./caja-TdR-STEAM/modificada/tapa.stl)
* Archivo STL del tornillo: [tornillo.stl](./caja-TdR-STEAM/modificada/tornillo.stl)
* Archivo STL del destornillador: [destornillador.stl](./caja-TdR-STEAM/modificada/destornillador.stl)
* Todos los archivos en un zip: [caja-TdR-STEAM.zip](./caja-TdR-STEAM/modificada/modificada.zip)

## <FONT COLOR=#007575>**Pasos de montaje**</font>
Las imágenes siguiente se corresponden con el montaje y los elementos originales utilizando una placa tipo UNO pero son perfectamente válidas puesto que son los mismos elementos y la placa TDRSTEAM tiene formato UNO.

* **Paso 1**. Colocamos la TdR STEAM sobre la placa UNO pasando el cable de cuatro hilos entre ambas y colocando el conector JST de 4 pines en la TdR STEAM (este conector solamente entra en una posición) para obtener algo similar a la imagen siguiente:

<center>

![Montaje de la TdR STEAM sobre UNO conectando el I2C](../img/img/inicio/montaje-paso-1.jpeg)

*Montaje de la TdR STEAM sobre UNO conectando el I2C*

</center>

* **Paso 2**. Conectamos la LCD mediante el conector plano de 4 pines asegurando que el cable negro va al pin marcado como GND. Hay que tener precaución con la orientación de este conector pues es reversible. El resultado debe ser similar al siguiente:

<center>

![Montaje de la LCD](../img/img/inicio/montaje-paso-2.jpeg)

*Montaje de la LCD*

</center>

* **Paso 3**. En la imagen siguiente se ven los elementos anteriores colocados en su lugar.

<center>

![Montaje de Shield+UNO y LCD en la base](../img/img/inicio/montaje-paso-3.jpeg)

*Montaje de Shield+UNO y LCD en la base*

</center>

* **Paso 4**. Conectamos un cable de tres hilos al micrófono teniendo en cuenta que el cable negro va al terminal marcado con una G y el otro extremo del cable lo colocamos en el conector JST de 3 pines marcado con A3. Pasamos los cables por debajo de la LCD y el resultado será algo similar a lo siguiente:

<center>

![Montaje de micrófono](../img/img/inicio/montaje-paso-4.jpeg)

*Montaje de micrófono*

</center>

* **Paso 5**. Colocamos el teclado en su lugar.

<center>

![Colocación del mando a distancia](../img/img/inicio/montaje-paso-5.jpeg)

*Colocación del mando a distancia*

</center>

* **Paso 6**. Finalmente colocamos la tapa y atornillamos cada tornillo en su tuerca, los apretamos con ayuda del destornillador y colocamos este en su alojamiento. Tendremos finalizada la colocación de elementos en la caja, tal y como vemos a continuación:

<center>

![Montaje finalizado](../img/img/inicio/montaje-paso-6.png)

*Montaje finalizado*

</center>
