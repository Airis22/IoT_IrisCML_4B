# IoT_IrisCML_4B
Proyectos de IoT desarrollados por Iris Cecilia alumna de la carrera de Desarrollo de Software Multiplataforma

# Practicas de clase
Documentación de practicas de IoT vistas en clase

# Proyecto: Serie de LEDs con Arduino

Este proyecto implementa un programa en Arduino que controla una serie de LEDs. Los LEDs se encienden y apagan de forma secuencial con un intervalo de 500 ms, creando un efecto visual dinámico.

## Materiales
- 7 LEDs: Uno para cada puerto digital asignado en el código.
- Jumpers: 8 (7 para los LEDs y 1 para conectar al puerto GND de la placa).
- 7 Resistencias de 220 ohmios: Una para cada LED.
- Placa Arduino: Compatible con el IDE de Arduino.
- Laptop o computadora: Para programar y cargar el código en la placa.
- Cable USB: Para conectar la placa Arduino a la computadora.
- IDE de Arduino: Descargable desde [https://www.arduino.cc/](https://www.arduino.cc/).

## Código
El siguiente código configura 7 LEDs conectados a los pines digitales de la placa Arduino y los controla para encenderlos de forma secuencial con un retardo de 500 ms:

## Diagrama
![image](https://github.com/user-attachments/assets/257d1d4e-f7e7-46db-a6a8-9e5329121082)

Conexión de los LEDs:
   - Conecta el cátodo (pata corta) de cada LED al puerto GND de la placa Arduino.
   - Conecta el ánodo (pata larga) al pin digital correspondiente usando resistencias de 220 ohmios.



# Proyecto: Semáforo con Arduino

Este proyecto consiste en la implementación de un semáforo usando una placa Arduino y LEDs. Los colores cambian de forma secuencial, simulando el funcionamiento de un semáforo real, con tiempos específicos configurados para cada luz.

## Materiales
- 3 LEDs (rojo, amarillo y verde): Representan las luces del semáforo.
- 4 Jumpers: Uno más que la cantidad de LEDs para la conexión al puerto GND.
- 3 Resistencias de 220 ohmios: Una para cada LED.
- Placa Arduino: Cualquier modelo compatible con el IDE de Arduino.
- Laptop: Para escribir y cargar el código.
- Cable USB: Para conectar la placa Arduino.
- IDE de Arduino: Descargable desde [https://www.arduino.cc/](https://www.arduino.cc/).

## Configuración del Circuito
Conexión de los LEDs:
   - Conecta el cátodo (pata corta) de cada LED al puerto GND de la placa Arduino.
   - Conecta el ánodo (pata larga) al pin digital correspondiente (ejemplo: pin 13 para rojo, 12 para amarillo, 11 para verde) usando resistencias de 220 ohmios.

## Diagrama
![image](https://acortes.co/wp-content/uploads/2020/11/Pr4_semaforo.jpg)



# Proyecto: Sensor de Luz con LDR y Arduino

Este proyecto utiliza un sensor LDR (Light Dependent Resistor) para medir la intensidad de luz en el ambiente y controlar un LED en función de la cantidad de luz detectada.

## Materiales
- 1 LDR: Para medir la intensidad lumínica.
- 1 Resistencia de 10k ohmios: Para crear un divisor de tensión junto con el LDR.
- 1 LED Azul: Indicador visual que se enciende en condiciones de poca luz.
- 4 Jumpers: Para realizar las conexiones.
- Placa Arduino: Compatible con el IDE de Arduino.
- Laptop o computadora: Para escribir y cargar el código en la placa.
- Cable USB: Para conectar la placa Arduino.
- IDE de Arduino: Descargable desde [https://www.arduino.cc/](https://www.arduino.cc/).

## Código
El siguiente código configura un sensor LDR conectado al pin analógico A5 y un LED conectado al pin digital 2. Si el nivel de luz es inferior al umbral establecido (valor mayor a 300), el LED se enciende:

## Diagrama
![image](![image](https://github.com/user-attachments/assets/6fd3807f-5faf-4fbd-bdad-1d9cb005d232)


# Proyecto: Intensidad Lumínica con LCD y LDR

Este proyecto utiliza un sensor LDR para medir la intensidad lumínica del ambiente y mostrar esos valores en una pantalla LCD. Además, un LED azul se enciende o apaga según el valor de luz medido, proporcionando una retroalimentación visual.

## Materiales
- 1 LCD (LiquidCrystal): Pantalla para mostrar los datos de intensidad lumínica.
- 1 LDR: Sensor para medir la intensidad lumínica del ambiente.
- 1 LED Azul: Indicador visual que se enciende o apaga dependiendo de la cantidad de luz detectada.
- 1 Resistencia de 10k ohmios: Para crear un divisor de tensión con el LDR.
- 2 Jumpers: Para las conexiones a GND y 5V.
- Placa Arduino: Compatible con el IDE de Arduino.
- Laptop o computadora: Para escribir y cargar el código en la placa Arduino.
- Cable USB: Para conectar la placa Arduino.
- IDE de Arduino: Descargable desde [https://www.arduino.cc/](https://www.arduino.cc/).

## Código
El siguiente código configura un sensor LDR conectado al pin analógico A5 y un LED azul conectado al pin digital 10. La intensidad lumínica se lee y se muestra en la pantalla LCD. Si la luz medida es mayor que el umbral de 700, el LED se enciende; de lo contrario, se apaga.

## Diagrama
![image](https://github.com/user-attachments/assets/38b04d97-6f7e-4871-8386-27004b32d94b)

# Proyecto: Sensor Ultrasonido y LEDs

Este proyecto utiliza un sensor de ultrasonido para medir la distancia de un objeto y visualizarla mediante la activación de diferentes LEDs en función de la proximidad del objeto al sensor. A medida que la distancia disminuye, los LEDs se encienden uno por uno, proporcionando una retroalimentación visual.

## Materiales
- 1 Sensor Ultrasonido: Para medir la distancia del objeto en centímetros.
- 5 LEDs (Rojo, Azul, Verde, Amarillo, Blanco): Indicadores visuales que se encienden según la distancia medida.
- Resistencias: Para conectar los LEDs de forma segura.
- Placa Arduino: Compatible con el IDE de Arduino.
- Laptop o computadora: Para escribir y cargar el código en la placa Arduino.
- Cable USB: Para conectar la placa Arduino.
- IDE de Arduino: Descargable desde [https://www.arduino.cc/](https://www.arduino.cc/).
## Código
El siguiente código, configura un sensor Ultrasonico, para que encienda led por led cada 5 centimetros que se acerque.
## Diagrama
![image](https://github.com/user-attachments/assets/9fda1d7c-581a-4a24-91ec-b9d6db925b7a)

# Practica Ultranico+LCD
En este archivo se utilizaron la pantalla LCD y el sensor ultrasónico. Estos componentes sirvieron para mostrar en la pantalla la distancia detectada por el sensor hasta localizar un objeto.
# Ultrasonido + LCD
Este proyecto utiliza un sensor de ultrasonido para medir la distancia a un objeto y visualiza esa distancia en una pantalla LCD. Además, enciende un LED cuando el objeto está a menos de 30 cm de distancia.

## Materiales
- 1 Sensor Ultrasonido : Para medir la distancia entre el sensor y el objeto en centímetros.
- 1 Pantalla LCD : Para mostrar la distancia medida.
- 1 LED: Se enciende cuando la distancia es menor a 30 cm.
- Resistencias: Para conectar el LED de forma segura.
- Placa Arduino: Compatible con el IDE de Arduino.
- Cable USB: Para conectar la placa Arduino.
- IDE de Arduino: Descargable desde [https://www.arduino.cc/](https://www.arduino.cc/).

## Diagrama
![image](https://github.com/user-attachments/assets/e36676bb-dc6d-487c-b5c6-946eb104aa8c)

#Practica RGB LED
En este proyecto, utilizamos un LED RGB, el cual puede generar una amplia gama de colores combinando tres colores básicos: rojo, verde y azul. Cada color se controla mediante un valor de intensidad, que varía entre 0 (apagado) y 255 (máxima intensidad). Este código permite cambiar el color del LED RGB a diferentes tonos según las combinaciones de estos valores.

## Materiales
- 1 LED RGB: Un LED común que tiene tres pines para controlar los colores rojo, verde y azul.
- Placa Arduino: Compatible con el IDE de Arduino.
- Cable USB: Para conectar la placa Arduino.
- Resistencias: Para limitar la corriente que pasa a través de los pines del LED.
- IDE de Arduino: Descargable desde [https://www.arduino.cc/](https://www.arduino.cc/).

## Descripción del Funcionamiento
En este código se configura un LED RGB para proyectar varios colores mediante la combinación de señales en los pines correspondientes al rojo, verde y azul.

- RGB LED:
  - El pin rojo controla el color rojo.
  - El pin verde controla el color verde.
  - El pin azul controla el color azul.

## Diagrama
![image](https://github.com/user-attachments/assets/7d3ad24b-7651-4d09-a16a-d39d6c14de7c)



# Practica DHT-11 Sensor de Temperatura y Humedad

En este proyecto se utiliza el sensor DHT-11 para medir la temperatura y la humedad del ambiente. Los datos obtenidos se visualizan en el monitor serie de Arduino, y un LED se enciende cuando la temperatura alcanza un umbral determinado.

## Materiales

- Sensor DHT-11: Sensor de temperatura y humedad digital.
- LED: Se usa para indicar que la temperatura ha alcanzado un umbral determinado.
- Resistor de 10kΩ: Para conectar el sensor DHT-11.
- Placa Arduino: Compatible con el IDE de Arduino.
- Cable USB: Para conectar la placa Arduino.
- IDE de Arduino: Descargable desde [https://www.arduino.cc/](https://www.arduino.cc/).

## Descripción del Funcionamiento
El código configura el sensor DHT-11 para leer la temperatura y la humedad del ambiente. La temperatura y la humedad se muestran en el monitor serie. Además, un LED se enciende si la temperatura supera los 28°C. El sensor **DHT-11 se conecta al pin digital 3 del Arduino, mientras que el LED se controla desde el pin digital 2.
- DHT-11: Se comunica con el Arduino utilizando la biblioteca **DHT para obtener las mediciones de temperatura y humedad.
- LED: Se enciende cuando la temperatura es igual o mayor a 28°C.

## Diagrama
![image](https://github.com/user-attachments/assets/67bfa5d4-ebc1-4fec-88ae-d7a9ac0d760a)



# Examen: Proyecto LED RGB y Sensor DHT11

El examen consistía en conectar un LED RGB y un sensor DHT11 a la placa Arduino. Si la temperatura detectada era mayor a 28°C, el LED se encendía de color rojo; si era menor a 28°C, se encendía de color azul. 

## Materiales

- Arduino Uno: Placa base para controlar el proyecto.
- LED RGB: LED de tres colores (rojo, verde y azul) que puede mezclar colores para mostrar diversos estados.
- Sensor DHT11: Sensor para medir la temperatura y la humedad del ambiente.
- Resistor de 220Ω: Usado para limitar la corriente al LED.
- Cables de conexión: Para realizar las conexiones entre los componentes y la placa Arduino.
- Placa de protoboard: Para organizar los componentes de forma temporal mientras se realiza el montaje.
- IDE de Arduino: Entorno de desarrollo para programar y cargar el código en la placa Arduino.

## Diagrama
<img src="https://github.com/user-attachments/assets/c831aff2-a7ab-478b-9189-5547171a0521" alt="Imagen ajustada" width="200"/>
<img src="[https://ruta-de-la-imagen.com/imagen.jpg](https://github.com/user-attachments/assets/a26aebae-2f52-45fd-bd5f-38b4ff07e223)" alt="Imagen ajustada" width="200"/>
