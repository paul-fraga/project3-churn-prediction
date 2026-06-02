# Predicción de Cancelación de Clientes (Churn) - Interconnect 📉

Proyecto de Machine Learning enfocado en la retención de clientes para el sector de telecomunicaciones. El objetivo es identificar usuarios en riesgo de abandono mediante modelos predictivos, permitiendo aplicar estrategias de marketing focalizadas.

## 📊 Descripción del Proyecto
Este caso de estudio analiza el comportamiento de más de 7,000 clientes, integrando 4 fuentes de datos distintas (contratos, demografía, internet y telefonía). A través de un exhaustivo análisis exploratorio y Feature Engineering, se desarrolló una solución capaz de predecir la baja de usuarios con un alto grado de precisión.

## 🛠 Stack Tecnológico
- **Lenguaje:** Python
- **Manipulación de Datos:** `pandas`, `numpy`, `re`
- **Visualización:** `seaborn`, `matplotlib`
- **Modelado:** `scikit-learn`, `LightGBM`
- **Técnicas implementadas:** Cruce de bases de datos (Merge), limpieza avanzada, Feature Engineering (`tenure_days`), balanceo de clases, validación cruzada.

## 🏆 Resultados Clave y ROI
- **Modelo seleccionado:** LightGBM Classifier.
- **Rendimiento:** **ROC-AUC Score de 0.8985** (superando el umbral de excelencia de 0.88).
- **Insight de Negocio:** La antigüedad del cliente y los contratos "Month-to-month" son los factores más críticos para la deserción. Al focalizar las campañas de retención solo en los usuarios marcados por el modelo, la empresa optimiza su presupuesto de marketing y reduce el CAC.

## 📁 Estructura del Repositorio
- `/images`: Gráficas de resultados (Curva ROC, Feature Importance, Distribución de Clases).
- `project3_churn.ipynb`: Notebook principal con el código completo (Limpieza, EDA y Entrenamiento).
- `/datasets/final_provider`: Datasets originales proporcionados para el estudio.

---
*Proyecto desarrollado y evaluado con éxito como parte del bootcamp de Data Science.*
