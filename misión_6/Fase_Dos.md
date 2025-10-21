## FASE: DOS 
Esta es la fase crítica del procesamiento de la señal, donde se construye la estructura de la señal que modulará la portadora de RF.

Objetivo Específico 2.1: Cargar el archivo de audio estéreo en el entorno de desarrollo (GNU Radio).

Objetivo Específico 2.2: Implementar los bloques o el código necesario para generar los componentes de la señal MPX:

Crear la señal de suma (L+R) para compatibilidad monofónica.

Generar el tono piloto de 19 kHz, que es la referencia de fase para la demodulación estéreo.

Crear la señal de diferencia (L-R) y modularla en una subportadora de 38 kHz mediante AM de Doble Banda Lateral con Portadora Suprimida (AM-DSB-SC).

Objetivo Específico 2.3: Combinar (sumar) las tres señales anteriores para formar la señal MPX final.

Objetivo Específico 2.4: Analizar el espectro de la señal MPX resultante y verificar la correcta ubicación y amplitud relativa de cada uno de sus componentes.

![Texto alternativo](imagen_2025-10-19_200746772.png)

**Desarrollo **

En esta parte de la practica  se diseñó y se  produjo un bloque de programación de radio que incluyó un jingle, combinando la voz del locutor creada con ayuda de IA con la cancion elegida , los cuales fueron grabados, editados y mezclados en Audacity para obtener un archivo estéreo en formato .wav. Luego, en GNU Radio, se generaron las señales L+R, L−R y el tono piloto de 19 kHz, modulando la señal de diferencia en una subportadora de 38 kHz y combinándolas para formar la señal MPX. Posteriormente, se implementó la modulación FM con una desviación de ±75 kHz y se transmitió mediante el USRP. Finalmente, se comprobó con un receptor FM que el audio se recibía con buena calidad y que se activaba el indicador estéreo, cumpliendo así todos los objetivos del laboratorio.

![Texto alternativo](2.2.jpeg)

![Texto alternativo](gnu_2.3.jpeg)

![Texto alternativo](valida.jpeg)
