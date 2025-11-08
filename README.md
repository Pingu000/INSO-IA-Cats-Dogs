# INSO-IA-Cats-Dogs
Project for INSO 3A


1.- Descripción General
El objetivo de este ejercicio es entrenar una red neuronal convolucional (CNN) que sea capaz de distinguir entre imágenes de perros y de gatos.



Deberás implementar dos enfoques complementarios:

Una CNN propia (diseñada y entrenada desde cero).
Un modelo de Transfer Learning, utilizando una arquitectura preentrenada (por ejemplo, VGG16, ResNet50, Xception, EfficientNet, etc.).


Este trabajo tiene un peso de 10 puntos sobre la nota final de la asignatura y debe ser individual y original.

El notebook que entregues debe ser tu propio trabajo, no una copia ni una modificación directa de notebooks ajenos.



Material de apoyo proporcionado
Para facilitar el inicio del trabajo, se entrega junto con este enunciado:

Notebook introductorio (CyD_Intro_CNN.ipynb)
Contiene las celdas necesarias para:
Cargar y preprocesar las imágenes desde el dataset.
Configurar los imports básicos y parámetros iniciales.
Generar el archivo .csv de predicciones finales con el formato exigido.
El notebook está pensado como punto de partida.
Cada estudiante debe ampliarlo, incorporar su propia CNN y el modelo de Transfer Learning.
Dataset comprimido (Cats_Dogs.zip)
Incluye 1000 imágenes de gatos (cat/) y 1000 imágenes de perros (dog/).
Debe descomprimirse en el mismo directorio que el notebook antes de ejecutar.


2.- Objetivo
Entrenar un modelo que, dada una imagen, determine si representa un perro (1) o un gato (0).

El resultado del modelo debe presentarse en formato de predicción binaria.



3.- Formato de Salida
Deberás generar un archivo .csv con las predicciones de tu modelo, siguiendo este formato:

id,label
1,0
2,0
3,1
4,0
5,1
Donde:

id corresponde al identificador de la imagen.
label es 0 para gato y 1 para perro.
Nota: La precisión base (baseline accuracy) de referencia es 0.569 (Esto te servirá como orientación para evaluar si tu modelo supera el rendimiento mínimo esperado).

