[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MCJunYEq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23644849&assignment_repo_type=AssignmentRepo)
# Lab06: Comunicación UART con PIC18F45K22

## Integrantes
* [Joused Danilo Forero Rodriguez](https://github.com/jouseddanilo)
* [Laura Ximena Rojas Pachon](https://github.com/LauXRS)
## INTRODUCCION
La práctica realizada se centra en la configuración y uso del módulo UART (Universal Asynchronous Receiver/Transmitter) en el microcontrolador PIC18F45K22. El objetivo principal es establecer una comunicación serial asíncrona entre el microcontrolador y un terminal conectado a través de un conversor USB-UART, permitiendo la transmisión y recepción de datos.
## MATERIALES
* Microcontrolador PIC18F45K22
* Programador/debugger PICkit 3/4.
* Fuente de alimentación (o PICkit 3/4).
* Conversor USB a serial UART.
## Objetivos
* Configurar el módulo UART en un microcontrolador PIC para permitir la comunicación serial.
* Transmitir datos a través del UART desde el PIC hacia un terminal serial.
* Implementar funciones de transmisión y recepción de datos a través de UART.
* Visualizar los datos recibidos en el terminal y comprender el proceso de transmisión asíncrona.
## PROCEDIMIENTO
Para verificar la adecuada comunicación, se utilizaron diferentes herramientas
1. PuTTY: Conexión a través del puerto serial configurado a 9600 baudios.
2. Script de Python: Para visualizar datos en tiempo real utilizando la libreria matplotlib.
## Evidencias de implementación
<img width="779" height="568" alt="WhatsApp Image 2026-05-15 at 19 34 14" src="https://github.com/user-attachments/assets/df606fbb-21e6-46cb-902a-965451db5903" />

## RESULTADOS
Durante la práctica, se logró establecer una comunicación exitosa entre el PIC y el terminal. Los datos enviados desde el microcontrolador fueron visualizados correctamente en el software de terminal, confirmando el funcionamiento del módulo UART.
## CONCLUSIONES
La práctica permitió comprender el funcionamiento del módulo UART en un microcontrolador PIC, así como la importancia de la configuración adecuada de sus parámetros para lograr una comunicación efectiva. La implementación de funciones para la transmisión y recepción de datos facilita la interacción entre dispositivos, siendo fundamental en aplicaciones de sistemas embebidos.

