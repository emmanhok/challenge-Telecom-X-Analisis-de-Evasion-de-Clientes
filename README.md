# 📊 Análisis del Abandono de Clientes (Churn) de Telecomunicaciones

## 📖 Tabla de Contenidos
- [Objetivo del Proyecto](#objetivo-del-proyecto)
- [Estructura del Repositorio](#estructura-del-repositorio)
- [Metodología de Análisis](#metodologia-de-analisis)
- [Hallazgos y Conclusiones Clave](#hallazgos-y-conclusiones-clave)
- [Tecnologías Utilizadas](#tecnologias-utilizadas)
- [Cómo Usar el Proyecto](#como-usar-el-proyecto)

## 🎯 Objetivo del Proyecto
El objetivo principal de este proyecto fue identificar los factores clave que contribuyen al abandono de clientes (Churn) en una empresa de telecomunicaciones. Mediante un análisis de datos exploratorio (EDA), se buscó comprender los patrones de comportamiento de los clientes que cancelan su servicio para, posteriormente, proponer recomendaciones estratégicas que ayuden a la empresa a mejorar su tasa de retención.

## 📁 Estructura del Repositorio
El repositorio contiene los siguientes archivos principales:
- `README.md`: Este archivo, que proporciona una visión general del proyecto.
- `TelecomX_LATAM.ipynb`: El notebook de Colab que contiene todo el código del proyecto, desde la limpieza de datos hasta el análisis y la generación del informe final.

## 🧠 Metodología de Análisis
El análisis se realizó siguiendo un enfoque estructurado para asegurar la calidad y validez de los hallazgos:
1.  **Limpieza y Preprocesamiento de Datos:**
    - Se normalizaron y aplanaron los datos anidados para facilitar el análisis.
    - Se manejaron valores faltantes e inconsistencias, como la conversión de una columna de texto (`object`) a numérica.
2.  **Análisis Exploratorio de Datos (EDA):**
    - Se realizó un análisis descriptivo para comprender la distribución de las variables numéricas.
    - Se visualizaron las relaciones entre la variable `Churn` y variables categóricas (género, tipo de contrato, etc.) y numéricas (cargos mensuales, tiempo de contrato, etc.) para identificar patrones de comportamiento.

## 📊 Hallazgos y Conclusiones Clave
Los principales hallazgos del análisis son los siguientes:
-   **Tasa de Churn:** El problema del Churn es significativo, afectando aproximadamente al 26% de los clientes en el dataset.
-   **Contrato y Antigüedad:** Los clientes con **contratos mensuales** y los **nuevos clientes** (con menos de un año de antigüedad) son los más vulnerables al Churn.
-   **Cargos Mensuales:** Existe una correlación positiva entre los cargos mensuales y la probabilidad de Churn; los clientes que pagan más son más propensos a irse.
-   **Servicios:** Los clientes que utilizan el servicio de **Fibra Óptica** también muestran una mayor tendencia al abandono.

## 🛠️ Tecnologías Utilizadas
- Python
- Google Colab
- Pandas: Para la manipulación y análisis de datos.
- NumPy: Para operaciones numéricas.
- Matplotlib, Seaborn y Plotly: Para la visualización de datos y la creación de gráficos informativos.

## 🚀 Cómo Usar el Proyecto
Para replicar y explorar este proyecto, sigue estos pasos:
1.  **Clona el Repositorio:**
    ```bash
    git clone https://github.com/emmanhok/challenge-Telecom-X-Analisis-de-Evasion-de-Clientes.git
    ```
2.  **Instala las Dependencias:** Asegúrate de tener instaladas las librerías mencionadas. Puedes instalarlas con pip:
    ```bash
    pip install pandas numpy matplotlib seaborn plotly
    ```
3.  **Ejecuta el Notebook:** Abre el archivo `.ipynb` en Google Colab o VS Code y ejecuta cada celda de forma secuencial.

---
