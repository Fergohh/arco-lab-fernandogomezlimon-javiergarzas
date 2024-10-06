  # Comparación de Resultados del Analisis

  ## Introducción 

  En este informe se compara los resultados obtenidos con la herramienta
  advisor del mismo ejecutble compilado con compiladores diferentes

  ## Resultados

  ##1. Tiempo de Ejecución

	
  -**Versión con compilador icpx**: 
   Eclapsed time: 0.01s
   CPU time: 0.01s
   Time in scalar code 0.01s
  -**Version con compilador g++**:
   Eclapsed time: 0.10s
   CPU time: 0.09s
   Time in scalar code 0.09s		

  ## 2. Rendimiento

  -**compilador g++**:
  Instrucciones de Memorias: 17
  Instrucciones de computo: 10
  Instrucciones mezcladas: 1
  Otras Instrucciones: 10

 -**compilador icpx**
  Instrucciones de Memorias: 14
  Instrucciones de computo: 11
  Instrucciones mezcladas: 0
  Otras Instrucciones: 1


  ## 3. Uso de Memoria
 
  -**compilador g++**:
  45% de las instrucciones son de memoria

  -**compilador icpx**:
  54% de las instrucciones son de memoria
  ## Conclusiones

  En resumen, el compilador icpx no solo es más rápida, sino que también consume menos memoria y
  proporciona un mejor rendimiento en general. 
  Esto sugiere que las optimizaciones implementadas han sido efectivas.

	