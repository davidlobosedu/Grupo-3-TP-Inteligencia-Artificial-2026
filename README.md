Trabajo Práctico  — Inteligencia Artificial 2026 
Profesor: Lic. Pablo Moreira
Universidad Nacional Guillermo Brown
Clasificación de imágenes con Machine Learning


Grupo 3
Martín Bahl
Guadalupe Wilson
David Lobos

Trabajo práctico de la asignatura Inteligencia Artificial — Universidad Nacional Guillermo Brown (UNaB).
El proyecto aborda la clasificación automática de imágenes utilizando el dataset Kuzushiji-MNIST (KMNIST), aplicando técnicas de Machine Learning y Redes Neuronales.


Objetivo

Desarrollar y evaluar un modelo capaz de clasificar correctamente imágenes de caracteres japoneses escritos a mano, siguiendo un proceso de trabajo basado en:

Exploración y comprensión de los datos.
Preparación y división del dataset.
Construcción de un modelo baseline.
Entrenamiento y evaluación.
Diagnóstico de errores.
Mejora del modelo.
Comparación de resultados.

La estrategia sigue un enfoque iterativo y pragmático: construir una primera solución funcional, medir su desempeño y mejorarla a partir del diagnóstico.


Dataset

Se utilizará Kuzushiji-MNIST (KMNIST).

Características principales:

Imágenes en escala de grises.
Tamaño: 28 × 28 píxeles.
Problema de clasificación multiclase.
Cada imagen pertenece a una de 10 clases.

Fuente:

https://codh.rois.ac.jp/kmnist/index.html.en


Metodología

El desarrollo seguirá las siguientes etapas:

Datos
  ↓
Exploración
  ↓
Preprocesamiento
  ↓
Train / Dev / Test
  ↓
Modelo Baseline
  ↓
Entrenamiento
  ↓
Evaluación
  ↓
Diagnóstico de errores
  ↓
Mejoras
  ↓
Evaluación final

El diagnóstico tendrá en cuenta conceptos como:

Bias / Sesgo
Variance / Varianza
Underfitting
Overfitting
Data Mismatch
Curvas de aprendizaje

Estos conceptos permiten decidir qué modificaciones realizar sobre el modelo en lugar de mejorar mediante prueba y error.


Modelo

Se trabajará con Redes Neuronales, estudiando:

Arquitectura de la red.
Capas de entrada, ocultas y salida.
Funciones de activación.
Forward Pass.
Función de costo.
Backpropagation.
Descenso de gradiente y Mini-Batch SGD.

Para clasificación multiclase, la salida utilizará Softmax, mientras que ReLU será el punto de partida para las capas ocultas.


Evaluación

El modelo será evaluado utilizando métricas apropiadas para clasificación multiclase, incluyendo:

Accuracy.
Matriz de confusión.
Precision.
Recall.
F1-Score.

Además, se analizarán los errores de Train y Dev para determinar si existe sesgo, varianza o algún problema relacionado con la distribución de los datos.


Herramientas

Python
Jupyter Notebook
NumPy
Pandas
Matplotlib
Scikit-learn
TensorFlow / Keras


Referencias
Andrew Ng — Machine Learning Yearning.
Goodfellow, Bengio & Courville — Deep Learning.
Michael Nielsen — Neural Networks and Deep Learning.
Dataset oficial KMNIST.

Los contenidos metodológicos utilizados se basan en los conceptos trabajados durante las clases de Inteligencia Artificial