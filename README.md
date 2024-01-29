# Cerradura de Puerta WiFi con ESP32-CAM y Telegram

Este proyecto implementa una cerradura de puerta WiFi con captura de fotos usando ESP32-CAM y la aplicación Telegram. Permite tomar fotos, desbloquear y bloquear la puerta remotamente.

## Funcionalidades Principales
- Captura de fotos cuando alguien toca el timbre.
- Notificación en Telegram con la foto de la persona.
- Control remoto de la cerradura desde la aplicación Telegram.

## Metodología
- Diseño prospectivo y controlado.
- Población objetivo: estudiantes y profesores.
- Entorno de prueba: laboratorio simulado de FIEC.

## Intervenciones
- Técnicas: Implementación de la cerradura inteligente.
- Protocolos: Procedimientos de instalación y uso.
- Sistemas y Programas: Desarrollo del control de acceso remoto.
- Mediciones: Registro de variables y pruebas piloto.

## Componentes Necesarios
- ESP32-CAM
- Cerradura Electrónica 12V
- Pulsador
- Fuente de 12VCC
- Rele 5v de una entrada o tambien se puede adecuar usando estos componentes(Transistor TIP122 NPN, Regulador 7805 5V, Diodo 1N4007, Resistencias de 1k y 10k, Condensador de 100uF 25V)

## Configuración de Telegram
1. Descarga e instala Telegram.
2. Crea un nuevo BOT usando BotFather.
3. Obtén la ID de usuario usando IDBot.

## Programación con Arduino IDE
Utiliza FTDI232 o Arduino UNO para programar la ESP32-CAM. Instala la biblioteca UniversalTelegramBot.
Este proyecto ofrece seguridad y control remoto para el acceso a través de una cerradura de puerta WiFi.


