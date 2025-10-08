## Análisis y Discusión:

Comparación de Resultados: Compare el S11 simulado con el medido. ¿Qué tan cercana fue la frecuencia de resonancia real a la simulada? Proponga hipótesis para explicar las diferencias (tolerancias en la construcción, efecto del conector no modelado, etc.).

Análisis Funcional: Describa lo observado en el analizador de espectro. ¿Fue la antena visiblemente direccional? ¿Cómo confirma esto el patrón de radiación que se simuló?

Análisis del Proceso de Diseño: Explique cómo el ajuste de las dimensiones en MATLAB permitió sintonizar la antena.

### Conclusiones:
Comparación de Resultados:
Comparación entre S11 Simulado y Medido:

S11 Simulado: En la simulación de MATLAB, la antena biquad mostró un coeficiente de reflexión (S11) cercano a 1.05 GHz

S11 Medido: La antena construida resonó a 930 MHz, cercano a los 915 MHz previstos.


Hipótesis para las diferencias:

Tolerancias de construcción: Pequeñas variaciones en las dimensiones físicas durante la fabricación (como el espaciado y la longitud de lado) pueden haber causado una pequeña desviación en la frecuencia de resonancia.

Efectos del conector: El conector SMA no fue modelado en la simulación, lo que podría haber influido en la frecuencia de resonancia al agregar una carga adicional no prevista.

Ajustes en la simulación: El grosor del alambre y la proximidad del reflector también son factores no perfectamente modelados, lo que puede haber afectado los resultados.

Análisis Funcional:
Observación en el Analizador de Espectro:

Frecuencia Central: La frecuencia de resonancia observada fue de aproximadamente 915 MHz.

Direccionalidad: La antena mostró un patrón de radiación direccional, con una mayor potencia cuando se apuntó hacia la dirección correcta, validando su diseño direccional.

Confirmación con el Patrón de Radiación:

El patrón de radiación simulado mostró un lóbulo principal dirigido hacia adelante, lo cual se confirmó durante las pruebas con el analizador de espectro.

Análisis del Proceso de Diseño:
Ajuste de las Dimensiones en MATLAB:

La longitud de onda calculada fue de aproximadamente 0.328 m, lo que llevó a un ajuste de la longitud del lado a 0.082 m y el espaciado a 0.041 m, con el fin de sintonizar la antena en la frecuencia de 915 MHz.

Ajuste Fino: Al iterar sobre las dimensiones, se optimizaron para obtener una resonancia cerca de 915 MHz, logrando una frecuencia más precisa en la construcción.
