# FASE: TRES 

En esta fase final, la señal procesada se lleva al dominio de radio frecuencia para su emisión y se comprueba su correcta recepción.
Objetivo Específico 3.1: Configurar el bloque de modulación FM, utilizando la señal MPX generada como entrada. Se debe ajustar la desviación de frecuencia para cumplir con el estándar de radiodifusión (típicamente ±75 kHz).

Objetivo Específico 3.2: Configurar los parámetros del USRP (frecuencia central de transmisión, ganancia, tasa de muestreo) para emitir la señal en una frecuencia libre dentro de la banda FM comercial (88-108 MHz).

Objetivo Específico 3.3: Iniciar la transmisión y utilizar un receptor de radio FM comercial para sintonizar la señal.

Objetivo Específico 3.4: Validar cualitativamente la calidad del audio recibido y confirmar que el indicador "Stereo" del receptor se activa, lo que prueba la correcta generación y detección del piloto de 19 kHz.

## Desarrollo 
En esta fase final se logró transmitir correctamente la señal FM estéreo generada en GNU Radio. Se configuró el bloque de modulación FM con la señal MPX como entrada y se ajustó la desviación a ±75 kHz, cumpliendo con el estándar de radiodifusión. El USRP se configuró con los parámetros adecuados de frecuencia, ganancia y tasa de muestreo, realizando la transmisión en la frecuencia de 106 MHz, dentro de la banda comercial de FM (88–108 MHz). En el analizador de espectro se observó la portadora principal centrada en 106 MHz, junto con las bandas laterales de audio y el tono piloto de 19 kHz, lo que confirmó la correcta estructura de la señal. Al recibir la transmisión con un radio FM, el audio se escuchó con buena calidad y el indicador “Stereo” se activó, demostrando que el sistema funcionó correctamente y que se cumplieron todos los objetivos propuestos para esta fase.

![Texto alternativo](3.1.jpeg)

[🎬 Ver video en YouTube](https://www.youtube.com/watch?v=uiPDPwrNgUw)


![Texto alternativo](espectro.jpeg)

