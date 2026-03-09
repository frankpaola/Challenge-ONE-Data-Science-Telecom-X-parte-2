# 📡 Telecom X - Análisis y Predicción de Evasión de Clientes (Churn)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-150458.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-Machine_Learning-F7931E.svg)
![Status](https://img.shields.io/badge/Status-Completado-success.svg)

## 📋 Descripción del Proyecto
Este proyecto fue desarrollado para **Telecom X**, una empresa de telecomunicaciones que enfrenta una alta tasa de cancelaciones de servicios. El objetivo principal es analizar los datos históricos de los clientes, identificar los factores clave que impulsan la evasión (Churn) y construir modelos predictivos de Machine Learning para anticipar qué clientes tienen mayor probabilidad de abandonar la empresa.

## 🎯 Objetivos
1. **ETL y Limpieza:** Extraer datos desde un formato JSON anidado, limpiarlos y estructurarlos para el análisis.
2. **Análisis Exploratorio (EDA):** Identificar visual y matemáticamente los patrones de comportamiento de los clientes.
3. **Machine Learning:** Preprocesar los datos (One-Hot Encoding, SMOTE, Estandarización) y entrenar modelos de clasificación (Regresión Logística y Random Forest).
4. **Estrategia de Negocio:** Traducir los hallazgos matemáticos en recomendaciones accionables para la retención de clientes.

## 🛠️ Tecnologías y Herramientas Utilizadas
- **Lenguaje:** Python
- **Manipulación de Datos:** Pandas, NumPy
- **Visualización:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn, Imbalanced-Learn (SMOTE)
- **Entorno:** Google Colab / Jupyter Notebooks

## 📂 Estructura del Repositorio
```text
telecom-x-churn-prediction/
│
├── data/
│   ├── base_de_datos.txt         # Datos crudos originales (JSON anidado)
│   └── telecom_churn_clean.csv   # Dataset procesado y limpio
│
├── notebooks/
│   ├── 01_ETL_y_EDA.ipynb        # Extracción, limpieza y análisis exploratorio
│   └── 02_Machine_Learning.ipynb # Preprocesamiento, modelado y evaluación
│
├── README.md                     # Documentación del proyecto
└── requirements.txt              # Dependencias del proyecto
