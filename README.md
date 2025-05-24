# DL--VISION-COMPUTACIONAL


Objetivo del proyecto:

Aplicar técnicas de aprendizaje automático profundo 'deep learning' para resolver un problema de visión computacional para identificar imagenes de perros y gatos
implementar una arquitectura neuronal adecuada como CNN, RNN o Transformers, y evaluar el modelo con métricas de clasificación adecuadas como F1-score o accuracy y registrar de manera sistemática los resultados, métricas y artefactos generados durante el proceso utilizando la plataforma de seguimiento de experimentos MLflow.

========================================================
Descripción del dataset:

Dataset: Cat and Dog

Fuente: Kaggle ----> https://www.kaggle.com/datasets/tongpython/cat-and-dog

Se accede al dataset descomprimiendo un archivo .zip llamado desde la nube

  Acerca del conjunto de datos
  
Conjunto de datos detallados almacenados en una estructura de portafolios donde se dividen en 4mil datos de entrenamiento para gatos y 4mil para perros, y mil datos de prueba para gatos y mil para perros.

=======================================================================

Decisiones tomadas en el modelado: 

Se usaron unicamente 1500 datos de entrenamiento y 500 de prueba
Se cargan los dataset desde archivos .zip en la nube
Se usó un modelo clásico de CNN para clasificación binaria de imagenes
Se usaron capas de pooling (MaxPool2D), BatchNormalization y Dropout para acelerar el proceso y evitar el sobreajuste y capas densas para la clasificación.
No disminuí las epocas ni las capas por obtener un mejor accuracy.


=======================================================================
Resultados y métricas principales:
tiempo de espera de ejecución: entre 30 y 40 minutos en total
Promedio Accuracy: 0.6225
Promedio F1-score: 0.2768
![image](https://github.com/user-attachments/assets/3c757e0d-6f2a-487c-833e-790d5b203020)


Se puede ejecutar en el siguiente notebook de google colab, no incluí la ejecución secuencial en github:
https://colab.research.google.com/drive/1cUm09vMRHYhPax6YeE2nLgg_R2D2ax3e?usp=sharing

