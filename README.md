
---

## 📊 Segmentación de Clientes con SVD, K-Means y Clustering Jerárquico

Este proyecto aplica técnicas de reducción de dimensiones y clustering para segmentar clientes en grupos con características similares, con el objetivo de diseñar estrategias de marketing específicas y personalizadas.

### 🔧 Tecnologías utilizadas
- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib
- Scipy

### 🧠 Proceso del proyecto
1. **Preprocesamiento de datos:** limpieza, normalización y centrado de los datos.
2. **Reducción de dimensiones con SVD:** se aplicó Singular Value Decomposition (SVD) manualmente con `numpy.linalg.svd` para identificar las características más influyentes.
3. **Clustering:**
   - Se usó **K-Means** para agrupar los clientes en segmentos distintos.
   - Se complementó con **Clustering Jerárquico** y análisis de dendrograma para validar la cantidad de grupos.
4. **Visualización:** gráficos de dispersión para observar la separación de grupos y dendrograma para análisis jerárquico.
5. **Análisis de clusters:** se interpretaron los grupos con estadísticas descriptivas.
6. **Estrategias de marketing:** se desarrollaron propuestas concretas para cada segmento, basadas en sus características demográficas y de comportamiento.

### 🎯 Objetivo
Identificar distintos perfiles de clientes para aplicar estrategias de marketing diferenciadas, optimizando recursos y mejorando la personalización de campañas.

---
