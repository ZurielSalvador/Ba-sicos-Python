# Basicos-Python
Este repositorio contiene ejercicios básicos de Python


## Ejercicio mas relevante: Bibliotecas para manejo de sensores

Como primera parte tenemos que considerar lo siguiente


Objetivos a lograr:



Habilitar la comunicación I2C
- Instalar las bibliotecas faltantes
- Realizar el circuito
- Cargar el programa


Una vez que inicialicemos aplicamos el siguiente comando:


-sudo raspi-config  

Selecciona la opción interfaces y después activa la opción I2C.


Ahora se instala el módulo que permite la comunicación entre la tarjeta y el sensor con el siguiente comando:

-pip3 install PyMLX90614


Para comprobar dicha comunicación se utilizan los comando en la terminal de la Raspberry Pi4:

-ls /dev/*i2c* 
-i2cdetect -y 1


Finalmente se carga el Programa el cual se encuentra en el mismo repositorio en la carpeta bibliotecas, llamado mlx9.py.


## Evidencias


Circuito en físico:

[![circuit-en-fisico-bibliotecas-de-manejor-de-sensores.jpg](https://i.postimg.cc/pLB0jVMB/circuit-en-fisico-bibliotecas-de-manejor-de-sensores.jpg)](https://postimg.cc/PCPzsjxL)


Terminal con lecturas de temperatura:

[![cambio-de-temperatura-desde-la-raspberry-pi4.png](https://i.postimg.cc/x1gRCsLx/cambio-de-temperatura-desde-la-raspberry-pi4.png)](https://postimg.cc/v4g92tqf)


### Video

En el siguiente link veras un video con una breve explicación:

https://youtu.be/COXxNdWHGVk



