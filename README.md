# 🧠 Análisis de salud mental y depresión

Proyecto final del curso **Herramientas básicas para el análisis de datos**. Análisis de salud mental y depresión mediante Python y Power BI.

**👤 Autor:** Victoria Estefanía Cardoso  
**📚 Curso:** Herramientas básicas para el análisis de datos  
**💻 Modalidad:** Trabajo individual

## 🎯 Objetivo

El objetivo de este proyecto es analizar un conjunto de datos sobre salud mental y explorar posibles relaciones entre la depresión, la ansiedad, determinados hábitos cotidianos y características sociodemográficas. Se plantearon tres preguntas de investigación:

1. ¿Cómo varía la proporción de personas con depresión severa entre países con distinta cantidad promedio de días soleados?
2. ¿Cómo varía el nivel de ansiedad según el tiempo diario dedicado al consumo de noticias y al uso de redes sociales?
3. ¿Qué características sociodemográficas (edad, género y situación laboral) predominan entre las personas con distintos niveles de severidad de la depresión?

## 📊 Dataset

Se utilizó el dataset **Global Mental Health & Lifestyle**, disponible en [Kaggle](https://www.kaggle.com/datasets/farshaddavoodifard/global-mental-health-and-lifestyle-5k-records). El archivo contiene 5000 registros y variables relacionadas con características sociodemográficas, salud mental y hábitos cotidianos.

El [dataset original](data/raw/synthetic_depression_dataset_v2_5000.csv) se incorporó al repositorio dentro de la carpeta [`data/raw/`](data/raw/).

El [archivo de datos procesados](data/processed/dataset_powerbi.xlsx) se incorporó al repositorio dentro de la carpeta [`data/processed/`](data/processed/) y contiene los datos preparados y modificados durante el análisis en Google Colab para su posterior utilización en Power BI.

## 🔍 Preparación y análisis de datos

El trabajo se desarrolló en **Python mediante Google Colab**. El [notebook de análisis](notebooks/analisis_salud_mental.ipynb), que contiene el desarrollo y análisis realizado, se encuentra dentro de la carpeta [`notebooks/`](notebooks/) del repositorio.

En una primera etapa, se realizaron exploraciones estructurales y estadísticas sobre los datos crudos. Luego, durante la etapa de preparación, se llevó a cabo un diagnóstico de los datos, verificando los formatos, valores nulos, inconsistencias, columnas sin utilidad y rangos anómalos. A partir de los hallazgos, se realizó la limpieza de los datos, aplicando las correcciones necesarias para obtener un conjunto de datos limpio.

Posteriormente, se realizó un análisis exploratorio (**EDA**) de variables cualitativas y cuantitativas de interés. Se elaboraron gráficos para analizar la relación entre los días soleados y la depresión severa; el nivel de ansiedad y el consumo de noticias y redes sociales; y las características sociodemográficas según el nivel de severidad de la depresión.

Para el procesamiento, análisis y visualización de los datos se utilizaron **Pandas, NumPy, Matplotlib y Seaborn**.

Finalmente, los resultados obtenidos se utilizaron para construir un **dashboard en Power BI**, compuesto por cinco visualizaciones, tres KPIs y un panel de filtros. El [dashboard en Power BI](dashboard/analisis_salud_mental_powerbi.pbix) se encuentra dentro de la carpeta [`dashboard/`](dashboard/) del repositorio.

## 📌 Principales resultados

- ☀️ Los países con menor promedio de días soleados presentan una mayor proporción de personas con depresión severa.
- 📱 No se identifica un patrón claro entre el nivel de ansiedad y la combinación del tiempo dedicado al consumo de noticias y al uso de redes sociales.
- 👥 Respecto de las características sociodemográficas, la edad y el género muestran distribuciones similares entre los distintos niveles de severidad de la depresión, mientras que el desempleo es más frecuente entre las personas con depresión severa.

> ⚠️ Estos resultados describen las relaciones observadas en el dataset analizado y no permiten establecer relaciones causales entre las variables.

## 📁 Archivos del proyecto

- 🗃️ [Dataset original](data/raw/synthetic_depression_dataset_v2_5000.csv)
- 🛠️ [Datos procesados para Power BI](data/processed/)
- 📓 [Notebook de análisis exploratorio](notebooks/analisis_salud_mental.ipynb)
- 📊 [Dashboard de Power BI](dashboard/analisis_salud_mental_powerbi.pbix)

## 🧰 Herramientas utilizadas

- 🐍 Python
- ☁️ Google Colab
- 🐼 Pandas
- 🔢 NumPy
- 📈 Matplotlib
- 📊 Seaborn
- 📉 Power BI

## 🔗 Fuente

- [Kaggle – Global Mental Health & Lifestyle](https://www.kaggle.com/datasets/farshaddavoodifard/global-mental-health-and-lifestyle-5k-records)
