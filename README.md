# esp32cam-mqtt-json-no-bloqueante
Este repositorio muestra el ejemplo básico de un programa para el ESP32CAM que se conecta a WiFi y a un Broker MQTT y env con ayuda de logica no bloqueante.

## Introducción

### Descripción
Este repositorio corresponde al taller [Envío de mensajes JSON via MQTT con ESP32CAM](https://edu.codigoiot.com/course/view.php?id=1002) de la plataforma educativa [edu.codigoiot.com](https://edu.codigoiot.com/)

### Alcances
El program de este repositorio es para ESP32CAM y genera un mensaje JSON enviado por MQTT. Los valores enviados son aleatorios. Este ejercicio es una introducción para agregar la lectura del sensor DHT11.

## Requisitos
### Material Necesario

Para realizar este flow necesitas lo siguiente

- [Ubuntu 20.04](https://releases.ubuntu.com/20.04/)
- [Arduino 2.1](https://www.arduino.cc/en/software)
- [Bibliotecas ESP32CAM de Espressif](https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html)

### Material de referencia

En los siguientes enlaces puedes encontrar cursos en la plataforma de edu.codigoiot.com que te permitirán realizar las configuraciones necesarias

- [Instalación de Virutal Box y Ubuntu 20.04](https://edu.codigoiot.com/course/view.php?id=812)
- [Introducción al ESP32CAM](https://edu.codigoiot.com/course/view.php?id=829)
- [Configuración del IDE para ESP32CAM](https://edu.codigoiot.com/course/view.php?id=850)
- [Conecta el ESP32CAM a WiFi](https://edu.codigoiot.com/course/view.php?id=852)
- [Aplicacion multicontenedor de servidor IoT con Docker compose](https://edu.codigoiot.com/mod/lesson/view.php?id=3889&pageid=3804&startlastseen=no)
- [Introducción a MQTT (Broker Mosquitto)](https://edu.codigoiot.com/course/view.php?id=851)

## Instrucciones

### Requisitos previos

Para poder usar este repositorio necesitas lo siguiente:

1. Arduino IDE configurada, puedes guiarte con el curso [Configuración del IDE para ESP32CAM](https://edu.codigoiot.com/course/view.php?id=850) o la [Documentación de Espressif](https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html)
2. Realizar el circuito básico para programar el ESP32CAM
3. Mosquitto MQTT instalado de forma local o via Docker Compose

![]()

4. Instala a biblioteca PubSubClient de Nick O'Leary

### Instrucciones de preparación del entorno

Para cargar el programa necesitas lo siguiente

1. Conecta el ESP32CAM en modo programador y reinicia el micro controlador
2. Selecciona la tarjeta AI-Thinker
3. Selecciona el puerto del ESP32CAM
4. Configura el nombre de red, contraseña y broker MQTT a los que te vas a conectar
5. Carga el programa al ESP32CAM
6. Configura el ESP32CAM en modo peración y reinicia el micro controlador

### Instrucciones de operación

Para comprobar el funcionamiento del programa para ESP32CAM en este repositiro, realiza lo siguiente

1. Suscribete a los temas MQTT señalados en el programa
2. Para prender y apagar el led flash, envía el mensaje true/false al tema señalado en el programa.

## Evidencias

[]()

## FAQ
**P**. ¿Cómo puedo conocer los comandos para MQTT para comprobar el funcionamiento?. **R**. Puedes encontrar todos los detalles en el curso de [edu.codigoiot.com](edu.codigoiot.com)

# Créditos

Desarrollado por Hugo Escalpelo
- [hugoescalpelo.com](https://hugoescalpelo.com/)
- [Página en Facebook](https://www.facebook.com/Hugo-Escalpelo-Profesional-337708683840136)
- [GitHub](https://github.com/hugoescalpelo)