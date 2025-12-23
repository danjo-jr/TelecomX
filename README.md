# 📞 Telecom X - Churn Analysis

## 📌 Descripción del proyecto

Este proyecto corresponde al Challenge Telecom X del curso de Data Science.
El objetivo principal es realizar un proceso completo de ETL (Extract, Transform, Load) y un Análisis Exploratorio de Datos (EDA) para comprender los factores que influyen en la evasión de clientes (Churn) dentro de la empresa Telecom X.

A través del análisis de datos demográficos, tipos de servicios contratados y variables de facturación, se buscan patrones y relaciones que ayuden a identificar comportamientos asociados a la cancelación del servicio y a proponer recomendaciones estratégicas de retención.

## 🎯 Objetivo

- Extraer datos desde una fuente externa en formato JSON.
- Limpiar, transformar y preparar los datos para el análisis.
- Realizar un análisis exploratorio apoyado en estadísticas descriptivas y visualizaciones.
- Analizar la evasión de clientes (churn) según variables categóricas y numéricas.
- Explorar correlaciones entre variables relevantes.
- Generar insights y recomendaciones basadas en datos.

## 🗂️ Estructura del proyecto

├── TelecomX_Data.json       # Dataset original en formato JSON
├── TelecomX_diccionario.md  # Diccionario de datos
├── TelecomX_Analysis.ipynb  # Notebook con todo el análisis
└── README.md                # Documentación del proyecto

## 🛠️ Tecnologías y librerías utilizadas

- Python 3
- Google Colab / Jupyter Notebook
- Pandas – Manipulación y análisis de datos
- NumPy – Operaciones numéricas
- Matplotlib – Visualización de datos

## ▶️ Ejecución del proyecto

1. Abre el archivo TelecomX_Analysis.ipynb en Google Colab o Jupyter Notebook.
2. Ejecuta las celdas en orden secuencial.
3. El notebook incluye:
- Extracción de datos desde la fuente JSON
- Limpieza y transformación
- Análisis exploratorio
- Visualizaciones
- Conclusiones y recomendaciones

## 🔍 Etapas del análisis

1️⃣ Extracción de datos

- Carga de datos desde un archivo JSON alojado en GitHub.
- Conversión a DataFrame de Pandas.

2️⃣ Limpieza y tratamiento

- Normalización de estructuras anidadas.
- Manejo de valores nulos e inconsistencias.
- Corrección de tipos de datos.
- Estandarización de variables categóricas.
- Creación de nuevas variables como cargo diario.

3️⃣ Análisis Exploratorio de Datos (EDA)

- Estadísticas descriptivas.
- Análisis de la distribución del churn.
- Comparación de churn por variables categóricas.
- Análisis de variables numéricas según evasión.
- Visualizaciones con gráficos de barras, boxplots e histogramas.

4️⃣ Análisis de correlación

- Evaluación de la relación entre variables numéricas y churn.
- Análisis del impacto del número de servicios contratados.
- Identificación de variables relevantes para futuros modelos predictivos.

##  📈 Principales conclusiones

- Los clientes con menor antigüedad presentan mayor probabilidad de churn.
- Un cargo mensual o diario más elevado se asocia con mayor evasión.
- Los clientes con mayor cantidad de servicios contratados tienden a ser más fieles.
- La antigüedad y la diversificación de servicios son factores clave para la retención.

## 💡 Recomendaciones estratégicas

- Implementar estrategias de retención temprana para clientes nuevos.
- Revisar políticas de precios para clientes con cargos elevados.
- Incentivar la contratación de servicios adicionales para aumentar la fidelización.
- Utilizar estas variables como base para modelos predictivos de churn.

## 📌 Próximos pasos

- Desarrollo de un modelo predictivo de churn.
- Evaluación de la importancia de variables.
- Segmentación de clientes para campañas personalizadas.

## 👦 Autor
Proyecto desarrollado por **Danilo Alvarez**
