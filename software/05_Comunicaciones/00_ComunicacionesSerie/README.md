# Comunicaciones. Puerto serie (USB)
El puerto serie de Arduino se usa para transmitir y recibir datos de otros dispositivos como un PC, teléfono móvil, tablet o microcontrolador.

El puerto serie del Arduino Uno usa los pins 0(RX) y 1(TX). Estos están conectados al controlador FTDI (ATmega 16u2) que es el que permite la traducción del formato serie TTL a USB. Estos pins no pueden ser utilizados mientras se usa la comunicación serie.
Más información del [puerto serie](http://diymakers.es/usando-el-puerto-serie-del-arduino/), la tabla de códigos ASCII se encuentra en la información.

<a href="" target="_blank"><img width="400" height="141" border="0" align="center" src="img/comunicaciones.jpg"/></a>

Los programas para aprender el funcionamiento de las comunicaciones por el puerto serie. Son el mismo programa peero con diferente
estructura de control.
- prog11_serie01.bly
- prog11_serie01b.bly

# Actividad
- Añadid las instrucciones necesarias para controlar todos los leds por el puerto serie.
