# 📊 Segmentación de Clientes con SVD, K-Means y Clustering Jerárquico

Este proyecto aplica técnicas de reducción de dimensiones y clustering para segmentar clientes en grupos con características similares, con el objetivo de diseñar estrategias de marketing específicas y personalizadas.

## 🔧 Tecnologías utilizadas
- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib
- Scipy

## 🧠 Proceso del proyecto
1. **Preprocesamiento de datos:** limpieza, normalización y centrado.
2. **Reducción de dimensiones con SVD:** se aplicó `numpy.linalg.svd` para identificar las características más influyentes.
3. **Clustering:**
   - **K-Means** para agrupar clientes.
   - **Clustering Jerárquico** con análisis de dendrograma para validar los grupos.
4. **Visualización de resultados:**

### 📷 Visualizaciones

#### 📌 Gráfico de dispersión con K-Means
![Dispersión K-Means](imagenes/IMG2(2).png)

#### 📌 Dendrograma del Clustering Jerárquico
![Dendrograma](imagenes/IMG2(1).png)

5. **Análisis de clusters:** se interpretaron estadísticamente.
6. **Estrategias de marketing:** se desarrollaron propuestas específicas para cada grupo.

## 🎯 Objetivo
Identificar distintos perfiles de clientes para aplicar estrategias de marketing diferenciadas, optimizando recursos y mejorando la personalización de campañas.

