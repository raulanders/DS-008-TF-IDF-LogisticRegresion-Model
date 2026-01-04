# 📘 TF-IDF + Regresión Logística para Análisis de Sentimientos
## 📌 Descripción

Este repositorio contiene un notebook en Python (model-tf-idf-logreg.ipynb) que implementa un modelo de análisis de sentimientos utilizando TF-IDF como técnica de vectorización de texto y Regresión Logística como clasificador.

El notebook cubre todo el flujo básico de un proyecto de NLP supervisado: desde el preprocesamiento del texto hasta la evaluación del modelo mediante métricas y matrices de confusión.

## 📂 Archivo principal

`model-tf-idf-logreg.ipynb`

Notebook que incluye:
- Carga del dataset
- Limpieza y preparación del texto
- Vectorización con TF-IDF
- Entrenamiento del modelo de Regresión Logística
- Evaluación del desempeño del modelo

## 🧠 Metodología aplicada
1. Preprocesamiento del texto
    - Limpieza de caracteres no relevantes
    - Normalización del texto
    - Preparación para vectorización
2. Vectorización
    - Uso de TF-IDF (Term Frequency – Inverse Document Frequency) para transformar texto en representaciones numéricas que capturan la importancia relativa de las palabras.
3. Modelo
    - Regresión Logística como clasificador supervisado para predecir el sentimiento del texto.
    - Adecuado para problemas de clasificación multiclase (negativo, neutro, positivo).
4. Evaluación
    - Métricas de desempeño (accuracy, precision, recall, F1-score)
    - Matriz de confusión para analizar aciertos y errores por clase

## 📊 Resultados esperados

El notebook permite observar:
  - Qué tan bien el modelo distingue entre sentimientos
  - En qué clases se producen más errores
  - La efectividad del enfoque TF-IDF + Regresión Logística como línea base para análisis de sentimientos

## 🛠️ Tecnologías utilizadas
  - Python
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib / Seaborn
  - Jupyter Notebook / Google Colab

## 🚀 Ejecución

1. Abrir el archivo model-tf-idf-logreg.ipynb en Jupyter o Google Colab.
2. Ejecutar las celdas en orden para reproducir el entrenamiento y evaluación del modelo.

## 📌 Estado

✅ Notebook funcional
🔧 Susceptible de mejoras como:
  - Optimización de hiperparámetros
  - Comparación con otros modelos
  - Uso de embeddings o modelos más avanzados
