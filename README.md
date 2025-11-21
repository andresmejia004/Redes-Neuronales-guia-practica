# Guía Práctica: Entrenamiento y Optimización de Redes Neuronales

Repositorio para desarrollar la práctica de la asignatura **Redes Neuronales Artificiales I** de la Universidad Santiago de Cali. El objetivo es **aplicar y comparar algoritmos de optimización en redes neuronales** usando Python y TensorFlow, observando el impacto de distintos optimizadores y tasas de aprendizaje en el rendimiento del modelo. 

---

## Objetivos

- Implementar una **red neuronal simple** en TensorFlow.
- Entrenar el modelo con distintos **optimizadores** (SGD y Adam).
- Probar **diferentes tasas de aprendizaje** y analizar su efecto.
- Comparar:
  - Velocidad de convergencia.
  - Estabilidad del entrenamiento.
  - Rendimiento final en entrenamiento y validación. 

---

## Datasets disponibles

Debes seleccionar **uno** de los siguientes conjuntos de datos para la práctica:

- **Titanic** – Supervivencia de pasajeros (*clasificación binaria*).
- **Diabetes** – Diagnóstico de diabetes (*clasificación binaria*).
- **House Prices** – Predicción de precios de viviendas (*regresión*).
- **Heart Disease** – Diagnóstico de enfermedades cardíacas (*clasificación binaria*).
- **Customer Churn** – Predicción de abandono de clientes (*clasificación binaria*). 

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
