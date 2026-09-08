# 👕 Workit Analytics: Diagnóstico de Demanda B2B, Churn y Forecasting en Vestuario Corporativo

## 📌 Resumen del Proyecto
Este proyecto analiza el comportamiento transaccional de ventas B2B en la industria de ropa de trabajo y vestuario corporativo (*Workit*). A partir de un dataset de **14,839 registros de pedidos** y **10,519 clientes únicos (RUT)**, se evalúa la estacionalidad de la demanda comercial, el riesgo de fuga (*churn*) y el impacto de variables macroeconómicas exógenas en Chile (IMACEC, tipo de cambio, cobre y desempleo).

---

## 🛠️ Stack Tecnológico
* **Lenguaje & Entorno:** Python 3.10+ | VS Code | Jupyter Notebooks
* **Procesamiento de Datos:** Pandas, NumPy, SQL (PostgreSQL / Google BigQuery)
* **Visualización & Data Apps:** Matplotlib, Seaborn, Streamlit, Power BI
* **Machine Learning:** Scikit-learn, XGBoost (Random Forest, Regresión Regularizada)
* **Metodología:** CRISP-DM (*Cross-Industry Standard Process for Data Mining*)

---

## 📐 Estructura de la Metodología (CRISP-DM)

1. **Business Understanding:** Diagnóstico de la caída de pedidos en el segundo semestre ($S_2$) y detección temprana de inactividad de clientes B2B.
2. **Data Understanding & Preparation:** Limpieza de duplicados, homologación de 232 giros comerciales a sectores clave (Minería, Construcción, Logística) y cruce con series macroeconómicas del Banco Central e INE.
3. **Modeling & Evaluation:** Modelos supervisados de regresión y clasificación para la tasa de recompra y pronóstico de volumen.
4. **Deployment:** Dashboard interactivo web construido en **Streamlit** para la simulación de demanda por sector económico.

---

## 📂 Estructura del Repositorio
```text
├── data/               # Datasets limpios (no incluye información sensible)
├── notebooks/          # Exploración e investigación en Jupyter Notebooks (.ipynb)
├── src/                # Scripts modulares de Python (.py)
│   ├── data_cleaning.py
│   ├── feature_engineering.py
│   └── train_model.py
├── app.py              # Aplicación web interactiva con Streamlit
├── requirements.txt    # Librerías y dependencias necesarias
└── README.md           # Documentación ejecutiva del proyecto
