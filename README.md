# Proyecto de Automatización de Invernadero con Arduino

Este proyecto tiene como objetivo principal aprender a implementar distintos dispositivos de entrada/salida (E/S) en Arduino IDE y simularlos en Proteus. A través de este proyecto, los estudiantes adquirirán conocimientos en programación de microcontroladores y simulación de sistemas embebidos.

## Requisitos Mínimos

Para realizar este proyecto, se simularon los siguientes elementos:

- Computadora con Arduino IDE y Proteus instalados
- Placa Arduino UNO
- Leds (Verde y Rojo)
- Resistencias de 220 Ω
- Relays
- Motor AC
- Pantalla LCD 16x2
- Sensor de temperatura y humedad DHT11

## Conexión de Componentes

Para facilitar el desarrollo de este proyecto, tenemos acceso al archivo "PROYECTO_2.pdsprj", que contiene la simulación en Proteus con las conexiones de los componentes.

## Programación

Al desarrollar la programación para este proyecto, se tuvieron en cuenta los siguientes objetivos:

- Automatizar un invernadero para controlar automáticamente la temperatura y la humedad del entorno.
- Continuamente medir la temperatura y la humedad utilizando el sensor DHT11.
- Si la temperatura alcanza o supera los 25 grados centígrados, encender automáticamente un motor ventilador. Apagarlo cuando la temperatura descienda.
- Si la humedad del entorno es igual o inferior al 40%, activar automáticamente el sistema de riego (bomba de agua) y encender el led verde. Apagar ambos cuando la humedad aumente, y cambiar el led verde por el led rojo.

Este proyecto es una práctica para aprender sobre el control de dispositivos físicos mediante programación de microcontroladores y simulación de sistemas embebidos.
