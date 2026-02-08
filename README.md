# Recognition-and-Classification-of-Emotions-in-Driver-Voice-Data-Streams
Este repositorio contiene el material asociado a una investigación académica orientada al reconocimiento de emociones a partir de flujos de datos de voz en contextos dinámicos. El estudio se centra en el uso de aprendizaje incremental y en la evaluación del algoritmo Adaptive Random Forest (ARF) bajo condiciones cercanas a escenarios reales mediante aprendizaje automático en línea (Online Machine Learning).
## Entorno de Ejecución
El proyecto fue desarrollado y ejecutado principalmente en Google Colab, lo que facilita el trabajo con flujos de datos y el uso de librerías especializadas en stream learning que incluyen comandos de instalación de dependencias mediante pip y utilizan rutas propias del entorno Colab.
No obstante, el proyecto puede ejecutarse en entornos locales configurando adecuadamente las dependencias.
## Objetivo de la investigación
El objetivo principal es analizar la aplicabilidad y el desempeño del algoritmo Adaptive Random Forest en el reconocimiento de emociones a partir de flujos de voz, considerando:

• Aprendizaje incremental.

• Presencia de concept drift.

• Métricas de desempeño clásicas y temporales.

• Viabilidad del enfoque para aplicaciones en tiempo (casi) real.

## Metodología

De forma resumida, la metodología es la siguiente:

1.- Recolección y preparación de datos de voz, organizados como flujos de datos.

2.- Extracción de características relevantes para el reconocimiento emocional.

3.- Entrenamiento incremental utilizando Adaptive Random Forest.

4.- Evaluación continua del modelo, considerando métricas de clasificación y métricas temporales.

5.- Análisis comparativo de resultados frente a estudios previos.

## Algoritmos Utilizados

• Adaptive Random Forest (ARF): Clasificación incremental en flujos de datos con detección y adaptación a cambios conceptuales.

• Métricas de Clasificación (Accuracy,Recall,Precisión,F1-Score): Evalúan el rendimiento de modelos de aprendizaje automático al predecir etiquetas de clase

## Datasets Utilizados

Se realiza recopilación de voces a traves de grabaciones y videos, para la elaboración de un dataset en que representará los flujos continuos de datos emocionales bajo diferentes escenarios experimentales.

Nota: Los datos recopilados tienen fines exclusivamente académicos. En caso de no incluirse directamente en el repositorio, se proporciona su descripción para garantizar la reproducibilidad metodológica.

## Flujo Experimental

El pipeline experimental implementado incluye las siguientes etapas:

1.- Carga y simulación del flujo de datos de voz.

2.- Preprocesamiento y extracción de características relevantes.

3.- Entrenamiento incremental del modelo ARF.

4.- Evaluación continua del desempeño del modelo.
