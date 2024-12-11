
Clasificador de Niveles de Obesidad

¿Qué hace este proyecto? Este proyecto presenta un modelo de machine learning diseñado para estimar los niveles de obesidad de un individuo en función de sus hábitos alimentarios y condición física, a partir de un cuestionario de 16 preguntas. El modelo utiliza algoritmos de clasificación para procesar la información proporcionada y busca, que al ingresar respuesta a 16 preguntas (variables), el algoritmo le entregue al usuario final la estimación de los niveles de obesidad en función de los hábitos alimentarios y la condición física (diferente al IMC) junto con algunas recomendaciones.

¿Por qué es útil este proyecto? Concientización: Permite a los usuarios tomar conciencia sobre sus hábitos y su posible impacto en su salud. Herramienta educativa: Ofrece información básica sobre los factores relacionados con la obesidad y las posibles medidas preventivas. Primer acercamiento: Puede servir como un primer paso para que las personas busquen orientación profesional sobre su salud. Importante: Este proyecto tiene fines educativos y demostrativos. Las estimaciones y recomendaciones proporcionadas no sustituyen el diagnóstico o tratamiento médico.

¿Cómo comenzar a usar este proyecto? Acceso al código: Preparación del entorno: Asegúrate de tener instaladas las bibliotecas necesarias (están incluídas en el código). Ejecución del modelo: Sigue las instrucciones detalladas en el código para cargar el modelo y realizar predicciones. Ingreso de datos: Responde a las 16 preguntas del cuestionario de acuerdo a tus hábitos y condición física. Obtención de resultados: El modelo te proporcionará una estimación de tu nivel de obesidad y recomendaciones generales.

Consideraciones adicionales:

Base de datos: Puedes consultar la base de datos usada para entrenamiento en https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition

Algoritmo de clasificación empleado: GXBOOTS, ouede utilizarse para predecir una categoría en problemas de clasificación. Es muy eficiente en grandes conjuntos de datos y es capaz de capturar relaciones no lineales entre las variables y manejar características interactivas, lo que lo hace ideal para problemas con datos complejos.

Métricas: precisión, recall, F1-score, matrix de confusión.

Limitaciones: Hay algunas confusiones entre ciertas clases, como la clase 0 y 1 (Normal_Weight y Overweight_Level_I), lo que sugiere que el modelo podría tener dificultades para distinguir entre estas dos categorías. Se requiere más datos de entrenamiento para que el modelo aprenda de estas dos variables.

Guía para uso: 

1. Descargue el archivo modelo, en él encontrará el código del modelo entrenado.
2. Carguélo a un entorno que permita editarlo, como google colab.
3. Cree la carpeta Data para proceder a cargar los datos Obesity_Data.
4. Corra el modelo. 

