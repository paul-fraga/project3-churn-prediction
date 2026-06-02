# project3-churn-prediction
Modelo predictivo (LightGBM) para identificar riesgo de cancelación de clientes en telecomunicaciones.

# Predicción de Cancelación de Clientes (Churn) - Interconnect

Proyecto de Machine Learning enfocado en la retención de clientes para el sector de telecomunicaciones. El objetivo es identificar usuarios en riesgo de abandono mediante modelos predictivos, permitiendo estrategias de marketing focalizadas.

## 📊 Descripción del Proyecto
Este caso de estudio analiza el comportamiento de más de 7,000 clientes, integrando múltiples fuentes de datos (contratos, demografía y servicios). Se desarrolló una solución capaz de predecir la baja de usuarios con un alto grado de precisión.

## 🛠 Stack Tecnológico
- **Lenguaje:** Python
- **Bibliotecas:** `pandas`, `numpy`, `seaborn`, `matplotlib`
- **Modelado:** `scikit-learn`, `LightGBM`
- **Técnicas:** Ingeniería de variables, balanceo de clases (`class_weight`), validación cruzada.

## 📈 Resultados Clave
- **Modelo seleccionado:** LightGBM Classifier.
- **ROC-AUC Score:** 0.8985 (superando el umbral de 0.88).
- **Insight principal:** Los usuarios con contratos "Month-to-month" presentan la mayor tasa de deserción, siendo el foco principal de las estrategias de retención.

## 📁 Estructura del Repositorio
- `/data`: Contiene los datasets utilizados.
- `/notebooks`: Notebook principal con el análisis exploratorio (EDA) y entrenamiento del modelo.
- `/images`: Gráficas de resultados y visualizaciones de impacto.

---
*Desarrollado como parte del bootcamp de Data Science de TripleTen.*
