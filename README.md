# Proyecto1_Sistemas_Embebidos
EL presente proyecto consiste en subir y bajar un pin GPIO con lenguajes (C/C++, Python, Bash) y la adquisición datos de un sensor temperatura (ds18b20) por medio de one-wire en Raspberry Pi.

El proyecto cumple con dos objetivos, el primero es comparar la frecuencia de conmutación de un pin de GPIO de una tarjeta de desarrollo raspberry pi, al programar la activación o desactivación (subida / bajada) del pin en tres lenguajes de programación diferentes( C/C++, Python o Bash) y el segundo es el de utilizar periféricos externos de la tarjeta para medir mediante un sensor one wire la variable de medida del sensor y posteriormente guardar esta información en un archivo .csv cada determinado tiempo.\\

La conexión para el primer objetivo, para realizar la prueba se realiza el montaje con un led, teniendo en cuenta que la tarjeta raspberry Pi 2 Model B V1.1:
                        
![Montajeled](https://user-images.githubusercontent.com/80786325/111538703-01537900-873b-11eb-9fce-9075bfeef7d4.PNG)

La conexión del sensor ds18b20,en la tarjeta raspberry Pi 2 Model B V1.1, es el siguiente:

![ConexionSensor (1)](https://user-images.githubusercontent.com/80786325/111538879-39f35280-873b-11eb-8fee-31c0a53a4f96.PNG)

A continuación, se indica la programación implementada para el primer objetivo:

| Lenguaje      | Programa |
| ------------- | ------------- |
| C/C++, libreria Wiring Pi  | [Wiringpi](https://github.com/Fredycuellar/Proyecto1_Sistemas_Embebidos/blob/94931f9a6c48a0345d5b23ea3d00ba4b70d7f1ef/WiringPi) |
| C/C++, libreria BCM |[BCM] (https://github.com/Fredycuellar/Proyecto1_Sistemas_Embebidos/blob/f9923b92b93e805823808ba6d64ad7ea7321de52/BCM) |
| Python |   |
|bash | Contenido de la celda  |


A continuación, se indica la programación implementada para el segundo objetivo:

| Lenguaje      | Programa |
| ------------- | ------------- |
|Bash  | Contenido de la celda  |

