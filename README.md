# 📊 VISUALIZACIÓN DE DATOS: EXPLORANDO CON SEABORN

[![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://www.python.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)  
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)  
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=matplotlib&logoColor=white)](https://matplotlib.org/)  
[![Seaborn](https://img.shields.io/badge/Seaborn-0099CC?style=flat&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)

Este proyecto es una exploración profunda de las capacidades de **Seaborn**, una biblioteca de Python construida sobre Matplotlib, especializada en la creación de **gráficos estadísticos atractivos e informativos**. Se enfoca en la visualización de datos de tarjetas de crédito para el análisis exploratorio (*Exploratory Data Analysis - EDA*).

---

## 🧠 Contenido del Proyecto

### 1️⃣ Carga y Preparación de Datos
- **Carga de Datos:** Se utiliza el dataset `credit_card.csv` para el análisis.
- **Análisis Inicial:** Se realiza un `datos.head()` para inspeccionar las primeras filas, asegurando que la carga sea correcta y observando las columnas y los tipos de datos.

### 2️⃣ Visualización con Seaborn
- **Ventajas de Seaborn:** Se destaca que Seaborn proporciona una interfaz de alto nivel para dibujar **gráficos estadísticos atractivos e informativos**.
- **Tipos de Gráficos:** El proyecto explora y crea varios gráficos para el EDA:
    * **Gráfico de Barras (Bar Plot):** Se utiliza para visualizar la distribución de una variable categórica.
    * **Gráfico de Dispersión (Scatter Plot):** Se emplea para mostrar la relación entre dos variables numéricas, revelando correlaciones o patrones.
    * **Histograma (Histogram):** Para visualizar la distribución de una sola variable numérica (inferido por ser fundamental en EDA).

### 3️⃣ Generación de Insights
- **Interpretación Visual:** A través de los gráficos, se pueden identificar patrones clave en los datos de tarjetas de crédito, como la distribución de los saldos (`Balance`) o la relación entre diferentes límites y gastos.

---

## 🛠️ Librerías Utilizadas

| Librería       | Uso principal                               |
|----------------|---------------------------------------------|
| **Seaborn**    | Creación de visualizaciones estadísticas de alto nivel (el foco del proyecto)|
| **Pandas**     | Carga y manipulación de datos (`pd.read_csv`, `datos.head()`)|
| **Matplotlib** | Biblioteca base de la cual Seaborn extiende sus funcionalidades|
| **NumPy**      | Operaciones numéricas y manejo de *arrays*|

---

## 🎯 Objetivo del Proyecto
Dominar las funcionalidades de la librería **Seaborn** para realizar un **Análisis Exploratorio de Datos (EDA)** eficiente. Se busca generar visualizaciones claras que permitan a un analista o científico de datos comprender rápidamente las distribuciones y relaciones presentes en el conjunto de datos de tarjetas de crédito.

---

## 📈 Resultados Clave
- Se demuestra la **capacidad de Seaborn** para generar diversos tipos de gráficos (Barras, Dispersión) con un código conciso.
- El proyecto proporciona una base sólida para la **exploración visual de datos**, esencial antes de aplicar cualquier modelo de Machine Learning.

