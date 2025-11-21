# Guía práctica – Redes neuronales (Heart Disease)

Este repositorio contiene el desarrollo de una guía práctica sobre **entrenamiento de redes neuronales** usando TensorFlow/Keras.  
El objetivo principal es entrenar y comparar una red neuronal simple para el problema de **clasificación binaria de enfermedades cardíacas** (*Heart Disease*), analizando el efecto de distintos **optimizadores** y **tasas de aprendizaje**.

---

## Contenido del repositorio

- `ejercicio_redes_neuronales.ipynb`  
  Notebook principal del ejercicio. Incluye:
  - Carga y exploración del dataset **Heart Disease**.
  - Preprocesamiento (selección de características, partición train/test, normalización).
  - Definición de una red neuronal feedforward en Keras.
  - Entrenamiento con:
    - **SGD** (varios `learning_rate`).
    - **Adam** (varios `learning_rate`).
  - Gráficas de curvas de **loss** y **accuracy**.
  - Sección de análisis y conclusiones.

- `requirements.txt`  
  Lista de dependencias necesarias para ejecutar el notebook.

- `data/heart.csv` *(no se incluye en el repo público)*  
  Archivo con el dataset de enfermedades cardíacas. Debe descargarse manualmente (ver siguiente sección).

- `Guía práctica - Redes neuronales - entrenamiento.pdf` *(opcional)*  
  Documento de apoyo teórico/práctico usado como base para el ejercicio.

---

## Dataset

Se utiliza el dataset clásico de **Heart Disease (clasificación binaria)**, donde la variable objetivo `target` indica:

- `0`: no presenta enfermedad cardíaca.
- `1`: presenta enfermedad cardíaca.

El dataset puede obtenerse, por ejemplo, desde Kaggle u otras fuentes públicas equivalentes.  
Una vez descargado, guárdalo como:

```text
data/heart.csv
