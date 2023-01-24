## Tipos de Kernel.
> Kernel Monolitico:
Es el responsable de la gestión de la memoria y de los procesos, de la comunicacion entre procesos y proporciona funciones de soporte de drivers y hardware. Los sistemas Operativos que usan este tipo de kernel son Linux, OS X y Windows. Tambien cabe mencionar que el kernel Monolítico solo define una interfaz de alto nivel sobre el hardware del ordenador. 

>Microkernel o Micronúcleo:
Se basa en ofrecer las funciones básicas de cada dispositivo, administrando todos los componentes que tengan CPU, memoria e IPC. Esto supone un mayor control de dispositivos. Son mas compactos que otro tipo de núcleo, por lo que brinda un conjunto reducido de abstracciones básicas del hardware, lo cual brinda beneficios en cuanto a portabilidad, seguridad y su capacidad para adaptarse.Sin embargo, el rendimiento de la máquina puede verse afectado, especialmente, en lo que respecta a la velocidad de las reacciones del hardware, y los tiempos de espera de los procesos para obtener información o tener acceso a otros. Como ejemplo solo existe el componente Mach de OS X, ya que hasta ahora no hay ningún sistema operativo con microkernel.

>Kernel Híbrido:
El kernel híbrido es una combinación de microkernel y kernel monolítico, este enfoque de núcleo combina la velocidad y el diseño más simple del núcleo monolítico con la modularidad y seguridad de ejecución del microkernel, cabe mencionar que ejecuta algunos servicios en el espacio del núcleo para reducir la sobrecarga de rendimiento de un microkernel tradicional, mientras sigue ejecutando el código del núcleo como servidores en el espacio del usuario. Por ejemplo, un diseño de núcleo híbrido puede mantener el sistema de archivos virtuales y los controladores de bus dentro del núcleo y los controladores del sistema de archivos y los controladores de almacenamiento como programas de modo de usuario fuera del núcleo. El kernel de Microsoft NT es un ejemplo bien conocido de un kernel híbrido que alimenta Windows NT, Windows 2000, Windows XP, Windows Server 2003, Windows Vista, Windows Server 2008 y Windows 7.


## Ventajas y Desventajas de los Tipos de Kernel.