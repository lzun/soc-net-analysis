# soc-net-analysis

## Características del Proyecto Final
- Utilizar el conjunto de datos sobre el covid-19. Uno ya cuenta con anotaciones, el cual sirve para entrenar un modelo de clasfiicación. El otro es para el etiquetado masivo de polaridad (positivo, negativo y neutro).
- Obtener las métricas de evaluación del modelo entrenado y su matriz de confusión (normalizada).
- Una vez etiquetado el conjunto de datos, realizar un análisis exploratorio: nubes de palabras para cada sentimiento. Explicar qué es lo que se encuentra en cada una de ellas.
- Mediante LDA, realizar modelado de temas para determinar los temas principales que se tratan en ese conjunto de datos.

### Tareas a considerar
- ¿Cómo incorporan el sentimiento anotado y el texto? Recuerden que deben mantenerlos juntos, e.g.

```[(texto_1, sentimiento_1),...,(texto_n, sentimiento_n)]```

- Utilicen una Máquina de Vectores de Soporte para el modelo de clasificación. Recuerden optimizar los parámetros lo más que puedan.
- Para el modelo de lenguaje, utilicen una bolsa de palabras. Ya se encuentra en el código su implementación.

### Tareas adicionales opcionales
- ¿Cómo cambiaría el desempeño del modelo si, en lugar de palabras, consideramos bigramas para hacer la bolsa de palabras?
- Existen diversos modelos de clasificación además de la MVS. ¿Cómo se compara el desempeño entre ellas?
- Realizar modelado de temas para cada polaridad de sentimiento en el conjunto de datos.
