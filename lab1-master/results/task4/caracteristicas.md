 Las carateristicas de mi ordenador son las siguientes:
 tiene una arquitectura x86_64
 tiene 8 nucleos 16 hilos 
 GHz max: 4.4
 GHz min: 0.4
 
 Caches
 
 L1d: 256Kib
 L1i: 256Kib
 L2: 4Mib
 L3: 16 Mib
 
 Memoria Ram: 16gb 
 
 Viendo estas caracteristicas podemos asumir que el compilador icpx atribulle mejor el uso de 
 las caches es evidente cuando vemos los datos del uso de memoria
 g++: 45% de instrucciones de memoria
icpx: 54% de instrucciones de memoria

icpx usa tiene mayor uso de instrucciones de memoria porque usa la memoria de forma mas eficiente
 
