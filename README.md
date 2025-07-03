# 🌿 Predicción de Emisiones de CO₂ con Modelos de Machine Learning

Este proyecto aborda la predicción de emisiones de dióxido de carbono (CO₂) en vehículos utilizando diversos modelos de regresión. Desde una regresión lineal simple hasta Random Forest, se aplicaron técnicas avanzadas de preprocesamiento, ingeniería de variables, limpieza y validación cruzada.

---

## 🎯 Objetivos del Proyecto

- 🔢 Aplicar **regresión lineal múltiple** como base comparativa.
- 🚀 Entrenar modelos avanzados: **regresión polinómica, árboles de decisión y Random Forest**.
- 🧹 Tratar valores atípicos con el método del **rango intercuartílico (IQR)**.
- 🧬 Codificar variables categóricas vía **One-Hot Encoding**.
- 🧮 Escalar características con **StandardScaler**.
- 🧪 Evaluar modelos con R², MAE, MSE, RMSE + **validación cruzada**.

---

## 📁 Dataset

- Fuente: *FuelConsumptionCO2.csv* — [Gobierno de Canadá](https://www.canada.ca/en/environment-climate-change/services/managing-pollution/energy-production/fuel-consumption-guide.html)
- Año modelo: 2014
- 🔍 Variables como: tamaño del motor, clase del vehículo, tipo de transmisión, consumo de combustible, tipo de combustible, emisiones de CO₂

---

## ⚙️ Modelos y Resultados

| 🧠 Modelo                      | 🎯 R²     | 📉 MAE | 📏 MSE | 📐 RMSE | 🔁 Validación Cruzada (R²) |
|------------------------------|----------|--------|--------|---------|-----------------------------|
| Regresión Lineal Múltiple    | 0.9947   | 1.80   | 19.33  | 4.40    | 0.9942                      |
| Regresión Polinómica         | 0.9975   | 0.92   | 9.32   | 3.05    | 0.9942                      |
| Árbol de Decisión            | **0.9992** | **0.39** | **2.87** | **1.69**  | 0.9806                      |
| Random Forest                | 0.9979   | 0.93   | 7.86   | 2.80    | **0.9857**                  |

---

## 📊 Visualizaciones Clave

- 🔥 Matriz de correlación
- 🔍 Pairplot de variables clave
- 📦 Boxplots para detectar outliers
- 📊 Gráfico de barras comparativas
- 🕸️ Gráfico de radar con métricas normalizadas

---

## 📌 Conclusiones

- ✅ **Random Forest**: Mejor equilibrio entre precisión y generalización.
- ⚠️ **Árbol de Decisión**: Mayor precisión en test pero posible sobreajuste.
- 📈 **Regresión Polinómica**: Alta mejora frente al modelo lineal base.
- 🧩 **Regresión Lineal**: Útil como punto de partida y muy rápida.

---

## 🔮 Posibles Mejoras

- 🎯 Ajuste de hiperparámetros con `GridSearchCV`
- 🧠 Modelos adicionales como **XGBoost** o redes neuronales
- 🧰 Reducción de dimensionalidad con **PCA**
- 📊 Interpretabilidad con **SHAP** o **Permutation Importance**
- 🤖 Automatización del flujo con **Bash o scripts**
- 🖥️ Publicar resultados en una interfaz con **Streamlit** o **Dash**

---

## ▶️ Cómo Usar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/Prediccion_CO2_Modelos_Machine_Learning.git
