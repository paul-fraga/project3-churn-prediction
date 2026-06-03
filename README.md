# 📞 Predicción de Cancelación de Clientes (Churn) - Telecomunicaciones

Este proyecto desarrolla un modelo predictivo de Machine Learning para identificar clientes con alto riesgo de abandonar los servicios de la empresa de telecomunicaciones "Interconnect". El objetivo principal es proporcionar una herramienta analítica que permita al equipo de marketing aplicar estrategias proactivas de retención (como códigos promocionales y descuentos especiales).

**📊 <a href="https://paul-fraga.notion.site/Predicci-n-de-Churn-Interconnect-f9fe4ae179d082f5bc5581d8cfa1e47e?pvs=25" target="_blank">Ver el Caso de Estudio Completo en Notion</a>**

### 🛠️ Tecnologías y Herramientas Utilizadas
* **Lenguaje:** Python
* **Manipulación y Limpieza de Datos:** Pandas, NumPy
* **Visualización de Datos:** Matplotlib, Seaborn
* **Modelos de Machine Learning:** LightGBM, Random Forest, Regresión Logística
* **Métricas de Evaluación:** ROC-AUC, Accuracy

### 💡 Metodología y Resultados Clave
1. **Análisis Exploratorio (EDA):** Se unificaron múltiples bases de datos (contratos, uso de internet, telefonía) y se trataron valores nulos.
2. **Ingeniería de Características:** Se crearon nuevas variables, como la duración total del cliente en meses, y se aplicó codificación (One-Hot Encoding) para preparar los datos.
3. **Entrenamiento de Modelos:** Se evaluaron diferentes algoritmos para encontrar el mejor equilibrio entre precisión y velocidad.
4. **Resultado Final:** El modelo basado en **LightGBM** alcanzó la métrica principal con un **ROC-AUC de 0.8985**, superando significativamente la métrica objetivo del negocio.

### 🚀 Cómo visualizar este proyecto
El código completo y el análisis paso a paso se encuentran detallados en el cuaderno Jupyter (`.ipynb`) dentro de este repositorio. Para una lectura estructurada desde la perspectiva de negocio, te invito a visitar el caso de estudio en mi portafolio de Notion.

---
*Proyecto desarrollado y evaluado con éxito como parte del bootcamp de Data Science.*
