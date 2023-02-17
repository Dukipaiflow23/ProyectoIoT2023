# ProyectoIoT2023
GDS0451 - Documentación proyecto IoT 
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
|1|ESP32|El módulo ESP32 es una solución de Wi-Fi/Bluetooth todo en uno, integrada y certificada que proporciona no solo la radio inalámbrica, sino también un procesador integrado con interfaces para conectarse con varios periféricos.|![Aspose Words c0a6ef2d-04fd-41d4-a1ce-ebc52d1e014c 001](https://user-images.githubusercontent.com/107650526/217643833-2a3555c5-2952-46cf-814e-397453742464.jpeg)|1|$220|
|2|Motorreductores|Se conoce como motorreductor a una máquina muy compacta que combina un reductor de velocidad y un motor. Estos van unidos en una sola pieza y se usa para reducir la velocidad de un equipo de forma automática.|![Aspose Words c0a6ef2d-04fd-41d4-a1ce-ebc52d1e014c 002](https://user-images.githubusercontent.com/https://http2.mlstatic.com/D_NQ_NP_8597-MLM20006077875_112013-O.webp)|2|$55|
|3|Regulador de voltaje|Un regulador de tensión o regulador de voltaje es un dispositivo electrónico diseñado para mantener un nivel de tensión constante o regulable, en algunos casos, con un circuito integrado.|![Aspose Words c0a6ef2d-04fd-41d4-a1ce-ebc52d1e014c 003](https://user-images.githubusercontent.com/107650526/217643646-a4d1d4d1-0b68-49a1-bae-3b511004ea9.png)|2|$157|
|4|Servomotor|Un servomotor es un actuador rotativo o motor que permite un control preciso en términos de posición angular, aceleración y velocidad, capacidades que un motor normal no tiene.|![Aspose Words c0a6ef2d-04fd-41d4-a1ce-ebc52d1e014c 004](https://user-images.githubusercontent.com/107650526/217643550-267eca20-f819-4b53-a030-13fddb7b23e9.jpeg)|1|$45|
|5|Raspberry Pi|La Raspberry Pi es una computadora de bajo costo y con un tamaño compacto, del porte de una tarjeta de crédito, puede ser conectada a un monitor de computador o un TV, y usarse con un mouse y teclado estándar.|![Aspose Words c0a6ef2d-04fd-41d4-a1ce-ebc52d1e014c 005](https://user-images.githubusercontent.com/)|1|$3000|
## Epicas del proyecto (Minimo debe de haber una épica por integrante de equipo)
\-	Quiero un dispositivo sea controlado via bluetooth
\-	Quiero que el dispositivo arroje semillas a su paso mediante un algoritmo programado
\-	Que responda a los comandos correctamente
\-	Quiero tener un registro de las zonas donde el vehiculo haya estado
\-  Quiero que tenga movimiento fluido y llegue a zonas muy especificas
## Tabla de historias de usuario
|Id|Historia de usuario|Prioridad|Estimación|Como probarlo|Responsable|
| :-: | :-: | :-: | :-: | :-: | :-: |
|1|Quiero un dispositivo que pueda controlar por medio de bluetooth |Media|3 semanas|Verificando que el dispositivo se conecte mediante bluetooh|Jose Remedios Melendez|
|2|Quiero que el dispositivo vaya arrojando semillas a su paso segun el algoritmo lo indique |Media|3 semanas| Verificando que el dispositivo compile correctamente el codigo mediante arduino IDE |Jose Carlos Duarte Vazquez |
|3|Quiero que el vehiculo sea funcional y responda a todos los comandos que le indique |Media | 3 semanas | Verificando que todos los componentes sean ensamblados correctamente y verificando el codigo compilado | Karla Diaz Moya |
|4|Quiero poder tener registro del trayecto del vehiculo asi como las zonas donde haya arrojadosemillas |Baja|3 semanas|Con la ayuda de Arduino IDE |Fernando Avizu y Juan Antonio Dominguez Rosales|
