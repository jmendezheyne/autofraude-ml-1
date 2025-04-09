# 🤖 autofraude-ml

Proyecto capstone de Machine Learning orientado a la detección de fraude. Este repositorio contiene el desarrollo completo del modelo, desde la exploración de datos hasta el despliegue.

---

## 📚 Tabla de Contenidos  
<!-- markdownlint-disable MD033 -->
[TOC]

---

## 🚀 Objetivo del proyecto

Desarrollar un sistema capaz de detectar patrones de comportamiento asociados a fraude, utilizando modelos de machine learning entrenados con datos históricos de comportamiento de clientes.

---

## 🧱 Estructura del proyecto

```bash
ml-capstone-project/
│
├── README.md                   # Descripción general del proyecto
├── requirements.txt            # Lista de dependencias (pip)
├── environment.yml             # Alternativa de entorno con Conda
├── .gitignore                  # Archivos/carpetas excluidos del control de versiones
│
├── data/                       # Datos utilizados en el proyecto
│   ├── raw/                    # Datos originales sin procesar
│   ├── processed/              # Datos limpios y listos para modelar
│   └── external/               # Datos de fuentes externas
│
├── notebooks/                  # Notebooks Jupyter para exploración y modelado
│   ├── 01_EDA.ipynb
│   ├── 02_FeatureEngineering.ipynb
│   └── 03_ModelTraining.ipynb
│
├── src/                        # Código fuente del proyecto
│   ├── __init__.py
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   └── evaluate.py
│
├── models/                     # Modelos entrenados y serializados
│   └── final_model.pkl
│
├── outputs/                    # Resultados, gráficos y métricas
│   ├── figures/
│   └── metrics/
│
├── app/                        # (Opcional) Código de despliegue
│   ├── main.py
│   └── model_utils.py
│
└── reports/                    # Informes y presentaciones
    ├── capstone_report.pdf
    └── slides.pptx
