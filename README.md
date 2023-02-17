# ProyectoIoT2023
GDS0453 - Documentación proyecto IoT 
# ProjectsIoT2022
## Integrantes
- Jose Remedios Melendez Morales
- Karla Díaz Moya
- Juan Antonio Dominguez Rosales
- Jose Carlos Duarte Vazquez
- Fernando Arvizu
## Objetivo general
Se pretende elaborar un vehiculo que busque sembrar semillas a su paso, controlado via control remoto con la ayuda de arduino y una conexion bluetooth y ayude a la agricultura
### Objetivos específicos
\- Se requiere poder monitorear el vehiculo mediante control remoto via bluetooth o wifi 
\- Se requiere el control de distribucion de semillas que este arroje
## Tabla de Software utilizado
|Id|Software|Versión|Tipo|
| :-: | :-: | :-: | :-: |
|1|Visual Studio Code|17.2|IDE|
|2|Arduino|2.0.0|IDE|
## Tabla con el hardware utilizado
|Id|Componente|Descripción|Imagen|Cantidad |Costo Total|
| :- | :- | :- | :- | :- | :- |
|1|ESP32|El módulo ESP32 es una solución de Wi-Fi/Bluetooth todo en uno, integrada y certificada que proporciona no solo la radio inalámbrica, sino también un procesador integrado con interfaces para conectarse con varios periféricos.|![HiLetgo ESP-WROOM-32 ESP32 ESP-32S - Placa de Desarrollo de 2,4 GHz de Modo  Dual WiFi + Bluetooth Dual Core Procesador Microcontrolador Integrado con  Antena RF AMP Filtro Ap STA para Arduino IDE :](Aspose.Words.c0a6ef2d-04fd-41d4-a1ce-ebc52d1e014c.001.jpeg)|1|$220|
|1|ESP32|El módulo ESP32 es una solución de Wi-Fi/Bluetooth todo en uno, integrada y certificada que proporciona no solo la radio inalámbrica, sino también un procesador integrado con interfaces para conectarse con varios periféricos.|![Aspose Words c0a6ef2d-04fd-41d4-a1ce-ebc52d1e014c 001](https://user-images.githubusercontent.com/107650526/217643833-2a3555c5-2952-46cf-814e-397453742464.jpeg)|1|$220|
|2|Motorreductores|Se conoce como motorreductor a una máquina muy compacta que combina un reductor de velocidad y un motor. Estos van unidos en una sola pieza y se usa para reducir la velocidad de un equipo de forma automática.|![Aspose Words c0a6ef2d-04fd-41d4-a1ce-ebc52d1e014c 002](https://user-images.githubusercontent.com/107650526/217643056-c386284d-a99a-44d8-85a4-c3543f0ee7f5.png)|2|$55|
|3|Sensor ultrasónico|los sensores ultrasónicos miden la distancia mediante el uso de ondas ultrasónicas. El cabezal emite una onda ultrasónica y recibe la onda reflejada que retorna desde el objeto. Los sensores ultrasónicos miden la distancia al objeto contando el tiempo entre la emisión y la recepción.|![Aspose Words c0a6ef2d-04fd-41d4-a1ce-ebc52d1e014c 003](https://user-images.githubusercontent.com/107650526/217643646-a4d1d4d1-0b68-49a1-ba3e-3b5110804ea9.png)|1|$42|
|4|Servomotor|Un servomotor es un actuador rotativo o motor que permite un control preciso en términos de posición angular, aceleración y velocidad, capacidades que un motor normal no tiene.|![Aspose Words c0a6ef2d-04fd-41d4-a1ce-ebc52d1e014c 004](https://user-images.githubusercontent.com/107650526/217643550-267eca20-f819-4b53-a030-13fddb7b23e9.jpeg)|1|$45|
|5|Raspberry Pi|La Raspberry Pi es una computadora de bajo costo y con un tamaño compacto, del porte de una tarjeta de crédito, puede ser conectada a un monitor de computador o un TV, y usarse con un mouse y teclado estándar.|![Aspose Words c0a6ef2d-04fd-41d4-a1ce-ebc52d1e014c 005](https://user-images.githubusercontent.com/107650526/217643461-162a8340-858d-44ec-846c-71d76e0cf938.jpeg)|1|$3000|
## Epicas del proyecto (Minimo debe de haber una épica por integrante de equipo)
\-	Quiero un dispositivo que alimente a mi mascota en caso de que no me encuentre en casa
\-	Quiero que el dispositivo alimente a mi mascota sin la necesidad de que yo tenga que alimentarlo.
\-	Que a través del dispositivo pueda monitorear la temperatura del agua y la humedad de la comida
\-	Quiero que a través del dispositivo revisar cuantas veces se ha servido comida a mi mascota.
## Tabla de historias de usuario
|Id|Historia de usuario|Prioridad|Estimación|Como probarlo|Responsable|
| :-: | :-: | :-: | :-: | :-: | :-: |
|1|Quiero un dispositivo que pueda controlar por medio de bluetooth |Media|3 semanas|Verificando que el dispositivo se conecte mediante bluetooh|Jose Remedios Melendez|
|2|Quiero que el dispositivo vaya arrojando semillas a su paso segun el algoritmo lo indique |Media|3 semanas| Verificando que el dispositivo compile correctamente el codigo mediante arduino IDE |Jose Carlos Duarte Vazquez |
|3|Quiero que el vehiculo sea funcional y responda a todos los comandos que le indique |Media | 3 semanas | Verificando que todos los componentes sean ensamblados correctamente y verificando el codigo compilado | Karla Diaz Moya |
|4|Quiero poder tener registro del trayecto del vehiculo asi como las zonas donde haya arrojadosemillas |Baja|3 semanas|Con la ayuda de Arduino IDE |Fernando Avizu y Juan Antonio Dominguez Rosales|
