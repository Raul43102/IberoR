# **Encendido y apagado de un LED mediante un botón**

*Objetivo*
Comprender el funcionamiento de una entrada digital mediante un botón y una salida digital mediante un LED, utilizando una placa ESP32. El objetivo específico es lograr que el LED se encienda al presionar el botón y se apague al soltarlo

*INTRODUCCION*
En esta práctica de microcontroladores con una ESP32, se emplea el entorno Arduino IDE para programar la lógica de interacción entre una entrada digital y una salida digital.
Las entradas digitales solo reconocen dos condiciones: alto (HIGH), equivalente al nivel lógico 1, y bajo (LOW), que representa el 0. Un botón pulsador conectado a una entrada se utiliza para generar estos estados al presionarlo, lo que provoca que el circuito se cierre o se abra.
Por su parte, las salidas digitales son empleadas para activar o desactivar componentes externos, tales como LEDs, motores o relés.
La operación clave del ejercicio consiste en que la ESP32, al detectar el estado HIGH (o 1 lógico) del botón pulsador en el pin configurado como entrada, activa inmediatamente el pin configurado como salida, lo que tiene como efecto el encendido de un LED.

*Metodología*
 Un circuito básico de control digital en una protoboard, utilizando una ESP32 como unidad de control. Se programó el comportamiento lógico en Arduino IDE y se verificó su funcionamiento físico conectando los componentes de manera segura y ordenada. El enfoque principal fue comprender la interacción entre hardware (componentes electrónicos) y software (código de control).

