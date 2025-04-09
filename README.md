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
## 🧱 Estructura de la presentación

```bash
presentacion-capstone/
│
├── explicar el problema        # diferencia fraude vs autofraude, lamina 2 del ppt 3, impacto en la industria. @esteban
├── objetivos/                  # 
│   ├── obj1/                   # objetivo original de detección de autofraude, (obj.2 - presentación final) 
│                               # ------                               
│                               # Predecir transacciones de auto-fraude en reclamos de fraude mediante un modelo de 
│                               # machine learning, complementado con la identificación de patrones de comportamiento
│                               # relevantes y la optimización del punto de corte, con el fin de reducir los casos no 
│                               # detectados y maximizar el beneficio esperado.
│   ├── obj2/                   # Agregar lo q planteamos de NLP -> transformarlo en un objetivo [80%-90%] -> @jaime
│   └── obj3/                   # Modelo multivariable | Segmentación | CLV y decidir demanda o no? (monto$) -> 2da capa
├── alcances/                   # lamina 24 (oculta en canvas) - trabajar en lamina de alcances del proyecto @ulises 
├── metodologia/                # consolidar lamina 8 ppt 3, con lamina 4. @ulises + @esteban
├── revision-bibliografica/     # (stand-by)
├── desarrollo-metodologico/    # 
│   ├── eda/                    # @esteban
│   ├── ingenieria-atributos/   # @jaime
│   ├── analisis-sens-costos/   # lamina 14 p3, automatizar @ulises

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
