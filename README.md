# JUST TIME
![image](https://github.com/IbonB/Just-Time/assets/151823683/5a9c1c14-a34c-4c15-9666-19cf0e1ff517)

---------
JUST TIME
---------
Hemos creado el juego Just Time. Para llevar acabo este proyecto hemos usado un FPGA, para programar el juego mediante el uso de puertas lógicas.

----------------------
EXPLICACIÓN DEL JUEGO
----------------------

Lo primero, con una ruleta se fijara un tiempo, despues se tendrá que pulsar un boton con el que empezara el contage y para acabar, mediante el mismo
pulsador se tendrá que adivinar cuando habrá llegado al tiempo prefijado y se encenderan los displays donde se mostrara el tiempo logrado. 
En caso de haber acertado se encendera un led. Para volver a jugar tendremos que pulsar otro pulsador para reiniciar el juego.

-----------
COMPONENTES
-----------
- Leds
- Knitter-switch/Encoding switch (Decimal -> BCD)
- Displays de 7 segmentos
- Resistencias (Para los displays 8 de 220Ω y para los pull down del encoder 4 de 1KΩ)
- Cable de conexión (USB -> Micro USB)
- Placa de desarrollo Alhambra 2

------------
-Alhambra 2
------------
![image](https://github.com/IbonB/Just-Time/assets/151823683/162319a9-bb91-49eb-93ab-df41c4b833fe)

----------------
Programas usados
----------------
- [Multisim](https://www.ni.com/es/support/downloads/software-products/download.multisim.html#452133)
- [ICEstudio](https://icestudio.io/#lk-download)

  ---------
  Librerías
  ---------
  - [ICEstudio (Librería de Obijuan)](https://github.com/FPGAwars/Collection-Jedi)
  - [GitHub Obijuan](https://github.com/Obijuan/digital-electronics-with-open-FPGAs-tutorial/wiki)

