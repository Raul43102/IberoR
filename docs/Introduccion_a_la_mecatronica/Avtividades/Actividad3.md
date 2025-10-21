# **Actividad 3: Encendido y apagado de un LED**

**Objetivo**
Comprender el funcionamiento básico de la placa ESP32 mediante el control de un diodo LED, aplicando conceptos de programación en Arduino IDE y el uso de componentes electrónicos como la resistencia y el protoboard.

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