# **Actividad 3: Encendido y apagado de un LED**

**Objetivo**
Comprender el funcionamiento básico de la placa ESP32 mediante el control de un diodo LED, aplicando conceptos de programación en Arduino IDE y el uso de componentes electrónicos como la resistencia y el protoboard.

*Introducción*
El LED (Light Emitting Diode) es un componente electrónico que emite luz cuando una corriente eléctrica pasa a través de él. Para evitar que el LED se queme por exceso de corriente, se utiliza una resistencia que limita el paso de electricidad.

La ESP32 es una placa de desarrollo basada en un microcontrolador que incluye WiFi y Bluetooth. Puede programarse con Arduino IDE, utilizando código en lenguaje C/C++. Uno de los primeros ejercicios al aprender a usar una placa microcontroladora es hacer parpadear un LED, lo que permite comprobar la correcta configuración del entorno de desarrollo y la comprensión de las funciones básicas:

pinMode(pin, OUTPUT) define un pin como salida.
digitalWrite(pin, HIGH/LOW) envía una señal de encendido o apagado.
delay(tiempo) pausa la ejecución del programa por un tiempo determinado (en milisegundos).

*Metodologia*
La metodología consistió en la implementación de un circuito físico (LED, resistencia y protoboard conectados a la ESP32) y la programación desde el Arduino IDE. Se escribió y cargó un código para alternar el estado del LED (encendido/apagado) cada segundo, sirviendo como demostración del funcionamiento de las salidas digitales del microcontrolador.

*Procedimiento*
Se conectó la ESP32 a la computadora mediante el cable USB.
Se abrió Arduino IDE y se configuró la placa “DOIT ESP32 DEVKIT V1”.
En el protoboard, se conectó el ánodo del LED al pin 13 de la ESP32 mediante una resistencia, y el cátodo al GND.
Se escribió y cargó el siguiente código:
```cpp
const int led = 13;

void setup() {
  Serial.begin(115200);
  pinMode(led, OUTPUT);
}

void loop() {
  digitalWrite(led, 1);
  delay(1000);
  digitalWrite(led, 0);
  delay(1000);
}
```
*Resultados*
