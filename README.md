# propuesta_CampusParty_Colombia


Descripción de la charla propuesta sobre domótica con IoT y microPython.

# Titulo

Domótica usando asistentes de voz y cloud Services con micropython y microcontroladores ESP

# Elevator pitch

En esta charla voy a mostrar como usar microPython en un microcontrolador ESP32/ESP8266 para conectarse a una plataforma en la nube con MQTT y/o HTTP, con el objetivo de leer sensores, controlar actuadores, luces, y relés. 

También la creación de un dashboard y la integración de asistentes de voz para crear habilidades/comandos con lo cual tener un control amigable y una gestión inteligente y del sistema domótico.

# Nivel de audiencia 

Intermedio

# Descripción

Se abordaran temas de programacion de micontroladores ESP32/8266 con micropython, internet de las cosas, clouds platforms y asistentes de voz.

En esta casi todo esta programado en python desde el micontrolador hasta la aplicacion que enlaza el asistente con el dashboard, ademas el uso uso de micropython y microcontroladores hacen un ecosistema perfercto para la domotica. 

Ademas es importante que esta charla este en el CampusParty_Colombia porque es una tendencia tecnologica y es imporatante que se profundicen estos temas desde el punto de vista teórico y práctico, y de esa forma conozcan el proceso que lleva a cabo la domótica.

Para realizar la charla necesito de WiFi de ser posible, si no puedo hacer hostpod usando datos de mi movil, lo cual seria tambien para demostrar que la conexion es flexible y puede funcionar con pocos datos.

## Proyectos de ejemplo

* En este repositorio esta un ejemplo para controlar luces led usando adafruit IO y Google Assistant
https://github.com/FunPythonEC/Neopixel_-_Google_assistant

* Esta fue una prueba para probar la conexion mqtt con micropython (subscribe y publish) con la plataforma ubidots
https://github.com/FunPythonEC/ubidots_mqtt_upy

## Esquema de la charla con tiempos y breve descripcion de las actividades

## Introducción (5)

Me presentare y se dara una breve introduccion a micropython, microcontroladores esp32 y esp8266, cloud platforms y asistentes de voz

## Desarrollo(25)

Se procedera a programar el microcontrolador para conectarse a internet y posteriormente al servidor en donde enviara o bajara paquetes, que previamente se ha configurado en la nube, para ver certificados de seguridad, credenciales de identificacion, url del servidor, etc.
Una vez establecida la comunicacion, ya se puede hacer un dashboard en donde se muestren las lecturas de los sensores, estados de luces, ademas de configurar botones para controlarlos, luego se creara una habilidad, o comando de voz para controlarlo desde un asistente, como lo son Google Assistant o Alexa.

### secuencia

1. Sensor/actuador/switch
2. Microcontrolador
3. Internet
4. Nube
5. Dashboard/Asistente
6. Realiza acción

## Finalización(5)

Se hara una demo interactiva con los asistentes de voz para enceder luces o cambiar colores de leds, tambien se hara uso de los botones del dashboard y un color picker para cambiar una variedad de colores y proyectarlos en una tira led inteligente. 

## Sesión de Preguntas(10)

# Palabras claves

Iot - microPython

# Videos de ejemplo
## Test de prueba
<figure class="video_container">
  <video controls="true" allowfullscreen="true" poster="https://github.com/jhonpaulo98/propuesta_CampusParty_Colombia/blob/master/media/DRFL4791.mp4">
    <source src="path/to/video.mp4" type="video/mp4">
    <source src="path/to/video.ogg" type="video/ogg">
    <source src="path/to/video.webm" type="video/webm">
  </video>
</figure>

## Color Picker
<figure class="video_container">
  <video controls="true" allowfullscreen="true" poster="https://github.com/jhonpaulo98/propuesta_CampusParty_Colombia/blob/master/media/XNHJ0945.mp4">
    <source src="path/to/video.mp4" type="video/mp4">
    <source src="path/to/video.ogg" type="video/ogg">
    <source src="path/to/video.webm" type="video/webm">
  </video>
</figure>

## Google Assistant
<figure class="video_container">
  <video controls="true" allowfullscreen="true" poster="https://github.com/jhonpaulo98/propuesta_CampusParty_Colombia/blob/master/media/">
    <source src="path/to/video.mp4" type="video/mp4">
    <source src="path/to/video.ogg" type="video/ogg">
    <source src="path/to/video.webm" type="video/webm">
  </video>
</figure>
