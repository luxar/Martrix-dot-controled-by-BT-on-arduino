Matrix dot controled by Bluetooth on arduino
============================================
Basado en el proyecto de Mark Ruys, <mark@paracas.nl>, que encuentras en [Aqui][original]

Esta basada en Adafruit, y en principio permitira enviar comandos por bluetooth a traves de una aplicacion en android para poner graficos en las matrices de 8*8 leds controlado por un MAX7219.


Escrito por Lucas Alvarez , <lucasmecanicapando@gmail.com>

Instalacion
-----------

Poner las librerias [Max72xxPanel][download] y [Adafruit_GFX][gfx-download] en `<arduinosketchfolder>/libraries/`.

pin CS-> a un pwm del arduino (10  por ejemplo)
DIN->MOSI(ICSP)
CLK->SCK(ICSP)
V+->5v
grnd->grnd

Uso
---

Revisar el proyecto  de Mark Ruys.



[original]:https://github.com/markruys/arduino-Max72xxPanel
[download]: https://github.com/markruys/arduino-Max72xxPanel/archive/master.zip "Download Max72xxPanel library"
[gfx-download]: https://github.com/adafruit/Adafruit-GFX-Library "Download Adafruit GFX Graphics Library"