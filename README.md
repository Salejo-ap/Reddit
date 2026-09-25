# Reddit Thread Analytics, Predicción de Movimiento Bursátil
Proyecto de análisis de texto y NLP sobre hilos de Reddit (posts + comentarios anidados) para predecir el aumento o disminucion del precio de acciones al día siguiente, usando como señal la actividad del día anterior en subreddits financieros.

**Descripción**
Este repositorio explora la relación entre el discurso generado por usuarios en subreddits financieros de Reddit y el movimiento del precio de acciones cotizadas (S&P 500 y afines).

El objetivo es doble:

Objetivo predictivo: construir un pipeline que, a partir de los hilos creados en el día T, clasifique si el precio de la acción subirá o bajará en T+1.

Objetivo de aprendizaje (NLP sobre hilos): servir como laboratorio para practicar todas las técnicas posibles de análisis de texto aplicadas a conversaciones jerárquicas (post raíz, comentarios, respuestas anidadas).