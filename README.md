# Segmentación de Clientes con K-Means  
**Actividad Obligatoria – Clase 8 · Aprendizaje Automático**
**Estudiante:** Nancy Julieta Cassano  
**Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial – CET N° 9 “Malvinas Argentinas”**  
**Año:** 2025  

---

**Descripción del proyecto**
Este proyecto implementa un modelo de **segmentación de clientes** utilizando el algoritmo **K-Means**.  
El objetivo es aplicar los conceptos de **inercia**, **coeficiente de silhouette** y **elección del número óptimo de clusters (K)**, para identificar distintos grupos de comportamiento de compra.

Se parte de un dataset con variables de comportamiento (frecuencia de compra, gasto promedio, tiempo en sitio, sensibilidad al descuento y tasa de devoluciones), al que se añaden columnas de ruido para luego analizarlas y depurarlas.

---

**Objetivos del análisis**
1. Determinar el número óptimo de clusters aplicando los métodos de:
   - El **método del codo (inercia)**.  
   - El **coeficiente de silhouette promedio**.  
2. Visualizar las separaciones de los clusters usando reducción de dimensionalidad (**PCA 2D**).  
3. Analizar cómo cambia la calidad del clustering antes y después de eliminar el ruido.  

---

**Estructura del proyecto (Cookiecutter)**
segmentacion-clientes-kmeans/
├── data/
│ ├── raw/ ← Dataset original (kmeans_3clusters.csv)
│ ├── interim/ ← Transformaciones intermedias
│ └── processed/ ← Datos finales (limpios)
├── notebooks/
│ └── TAREA_OBLIGATORIA_CLASE8_AA_CASSANO_JULIETA.ipynb
├── reports/
│ └── figures/ ← Gráficos de codo, silhouette y PCA
├── src/ ← Scripts de preprocesamiento o modelado
└── README.md
