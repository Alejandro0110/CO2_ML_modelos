🌱 Predicción de Emisiones de CO₂ con Modelos de Machine Learning
Este proyecto explora distintas técnicas de regresión — desde modelos lineales básicos hasta algoritmos no lineales más sofisticados — para predecir las emisiones de CO₂ en vehículos, utilizando un enfoque completo de ingeniería de datos, limpieza, escalado y evaluación de modelos.

🎯 Objetivos
- Aplicar regresión lineal múltiple como modelo base.
- Explorar modelos avanzados: regresión polinómica, árbol de decisión y Random Forest.
- Realizar limpieza de datos y tratamiento de outliers.
- Codificar variables categóricas con One-Hot Encoding.
- Normalizar variables numéricas con StandardScaler.
- Evaluar todos los modelos con métricas robustas (R², MAE, MSE, RMSE).
- Usar validación cruzada para probar capacidad de generalización.

🧠 Dataset
- Fuente: FuelConsumptionCO2.csv
- 1067 registros de vehículos modelo 2014 con características como:
- Tamaño del motor, número de cilindros, clase del vehículo, tipo de transmisión, tipo de combustible
- Consumos de combustible en ciudad, carretera y combinado
- Emisiones de CO₂

📊 Modelos Implementados
| Modelo | R² Score | MAE | MSE | RMSE | Validación Cruzada (R²) | 
| Regresión Lineal Múltiple | 0.9947 | 1.80 | 19.33 | 4.40 | 0.9942 | 
| Regresión Polinómica | 0.9975 | 0.92 | 9.32 | 3.05 | 0.9942 | 
| Árbol de Decisión | 0.9992 | 0.39 | 2.87 | 1.69 | 0.9806 | 
| Random Forest | 0.9979 | 0.93 | 7.86 | 2.80 | 0.9857 | 



📌 Principales Conclusiones
- Random Forest ofrece el mejor equilibrio entre precisión y generalización: ideal para producción.
- Árbol de decisión fue el más preciso, pero mostró señales de sobreajuste.
- Regresión polinómica mejoró sustancialmente frente a la versión lineal.
- Regresión lineal sigue siendo una excelente referencia por su simplicidad.

📎 Visualizaciones destacadas
- Matriz de correlación
- Pairplots para relaciones clave
- Gráficos de caja para detección de outliers
- Comparación de métricas con barras agrupadas
- Radar chart para visualización multivariada normalizada

🚀 Cómo reproducir este proyecto
- Clona este repositorio.
- Abre el notebook .ipynb en Colab o Jupyter.
- Asegúrate de tener pandas, sklearn, matplotlib, seaborn, numpy instalados.
- Ejecuta las celdas en orden.


