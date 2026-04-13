# # Predicción del riesgo de insolvencia en PYMES del sector servicios español

## Descripción

Proyecto de fin de grado (TFG) de Business Analytics. Desarrolla un modelo predictivo 
del número de concursos de acreedores en España a partir de variables macroeconómicas 
públicas, combinando precisión predictiva con interpretabilidad de resultados.

## Estructura del repositorio

├── notebook/
│   ├── 01_exploracion_datos.ipynb   # Ingeniería del dato: ETL, limpieza y EDA
│   └── 02_analisis_dato.ipynb       # Modelado: entrenamiento, evaluación e interpretación
├── data/
│   ├── raw/                         # Datos en bruto descargados de las fuentes oficiales
│   └── processed/                   # Dataset final procesado (frecuencia trimestral)
└── README.md

## Modelos implementados

- Regresión Lineal Múltiple (baseline)
- Random Forest
- XGBoost

## Fuentes de datos

| Fuente | Datos |
|--------|-------|
| INE | Concursos de acreedores, EPA, IPC, IPRI, PIB, coste laboral |
| Banco de España | Tasa de morosidad |
| OMIE | Precio de la electricidad |
| Investing.com | Euríbor, precio del petróleo |

## Período de análisis

2011Q3 – 2025Q4 (58 trimestres)

## Tecnologías

Python 3.12 · pandas · scikit-learn · XGBoost · matplotlib · seaborn