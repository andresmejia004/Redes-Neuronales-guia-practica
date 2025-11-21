# Guía Práctica: Entrenamiento y Optimización de Redes Neuronales

Repositorio para desarrollar la práctica de la asignatura **Redes Neuronales Artificiales I** de la Universidad Santiago de Cali. El objetivo es **aplicar y comparar algoritmos de optimización en redes neuronales** usando Python y TensorFlow, observando el impacto de distintos optimizadores y tasas de aprendizaje en el rendimiento del modelo. :contentReference[oaicite:0]{index=0}

---

## Objetivos

- Implementar una **red neuronal simple** en TensorFlow.
- Entrenar el modelo con distintos **optimizadores** (SGD y Adam).
- Probar **diferentes tasas de aprendizaje** y analizar su efecto.
- Comparar:
  - Velocidad de convergencia.
  - Estabilidad del entrenamiento.
  - Rendimiento final en entrenamiento y validación. :contentReference[oaicite:1]{index=1}

---

## Datasets disponibles

Debes seleccionar **uno** de los siguientes conjuntos de datos para la práctica:

- **Titanic** – Supervivencia de pasajeros (*clasificación binaria*).
- **Diabetes** – Diagnóstico de diabetes (*clasificación binaria*).
- **House Prices** – Predicción de precios de viviendas (*regresión*).
- **Heart Disease** – Diagnóstico de enfermedades cardíacas (*clasificación binaria*).
- **Customer Churn** – Predicción de abandono de clientes (*clasificación binaria*). :contentReference[oaicite:2]{index=2}

Puedes incluir el dataset en una carpeta `data/` o cargarlo desde una fuente externa (Kaggle, UCI, etc.), según lo que indique el docente.

---

## Requisitos

- Python 3.9+ (recomendado)
- [TensorFlow](https://www.tensorflow.org/)
- Bibliotecas típicas de ciencia de datos:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn` (para dividir en train/validation, normalización, etc.)

Ejemplo de instalación:

```bash
pip install -r requirements.txt
