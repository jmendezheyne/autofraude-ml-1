# autofraude-ml

ml-capstone-project/
│
├── README.md                     # Descripción general del proyecto
├── requirements.txt              # Lista de dependencias
├── environment.yml               # Alternativa para conda
├── .gitignore                    # Ignora carpetas como __pycache__, modelos, etc.
│
├── data/                         # Datos utilizados en el proyecto
│   ├── raw/                      # Datos originales sin procesar
│   ├── processed/                # Datos limpios/listos para modelar
│   └── external/                 # Datos de fuentes externas
│
├── notebooks/                    # Notebooks Jupyter para exploración y modelado
│   ├── 01_EDA.ipynb
│   ├── 02_FeatureEngineering.ipynb
│   └── 03_ModelTraining.ipynb
│
├── src/                          # Código fuente del proyecto
│   ├── __init__.py
│   ├── data_preprocessing.py     # Funciones de limpieza y transformación
│   ├── feature_engineering.py    # Funciones para crear o transformar features
│   ├── model_training.py         # Entrenamiento y validación
│   └── evaluate.py               # Métricas y visualizaciones de evaluación
│
├── models/                       # Modelos entrenados serializados (pickle, joblib)
│   └── final_model.pkl
│
├── outputs/                      # Resultados del modelo, reportes, gráficos
│   ├── figures/
│   └── metrics/
│
├── app/                          # (opcional) Código de despliegue (API, UI)
│   ├── main.py                   # Ejemplo: Flask o FastAPI
│   └── model_utils.py
│
└── reports/                      # Documentación, informes PDF, presentaciones
    ├── capstone_report.pdf
    └── slides.pptx
