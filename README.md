# Análisis de la salud mental y las redes sociales

## 📌 Descripción
Proyecto de análisis de datos que estudia la relación entre el uso de redes sociales y distintos indicadores de salud mental.

## 🎯 Objetivos
- Analizar patrones de uso de redes sociales
- Identificar posibles impactos en la salud mental
- Visualizar tendencias y conclusiones relevantes

## 🛠️ Herramientas utilizadas
- Python
- Pandas / NumPy
- Power BI
- JupyterLab

## 📊 Metodología
1. Limpieza y preparación de los datos  
2. Análisis exploratorio  
3. Visualización de resultados
4. Modelo de Machine Learning (RandomForest y KMeans) 
5. Extracción de conclusiones

## 📈 Resultados principales
- Relación entre tiempo de uso y niveles de estrés/ansiedad no es contundente. Si en cambio afecta a la productividad.

## 🚀 Conclusiones
Los dos modelos de Random Forest ofrecen resultados coherentes con el planteamiento del proyecto. El primer modelo, que trabaja con los valores originales de estrés, presenta un rendimiento cercano al 50 %, similar a una predicción aleatoria, lo que refleja la complejidad del fenómeno analizado y la ausencia de relaciones claras entre las variables.

El segundo modelo, basado en la binarización de estrés y productividad (alto/bajo), simplifica el problema y permite identificar patrones más definidos, elevando la precisión hasta aproximadamente el 80 %. No obstante, esta mejora se produce a costa de una mayor simplificación de los datos.

En conjunto, los resultados evidencian el equilibrio entre mejorar la capacidad predictiva del modelo y mantener la fidelidad a la naturaleza original de los datos, destacando la importancia de una correcta formulación del problema en proyectos de análisis y machine learning.

---
Proyecto realizado como trabajo final del Bootcamp de Data Analytics.
