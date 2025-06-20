# 📡 Telecom X 

## 📊 Descripción

Analizaremos el comportamiento de los clientes en Telecom X, una empresa que enfrenta una preocupante tasa de cancelaciones. Utilizaremos una base de datos obtenidas de una API. El objetivo es comprender qué factores influyen en la evasión (churn) y aportar información clave para mejorar la retención de los clientes. El proyecto se desarrolló a través de un proceso de extracción, limpieza y transformación de datos (ETL), seguido de un análisis exploratorio detallado para descubrir patrones, correlaciones e indicadores de abandono.

## 🧰 Tecnologías utilizadas

- **Python** para el procesamiento y análisis y **Jupyter Notebook (Google Colab)** para trabajar ahí.
- Un archivo de datos en formato **JSON** y la biblioteca **Pandas** para manipulación de datos.
- **NumPy** para cálculos numéricos.
- **Matplotlib**, **Seaborn** para visualización gráfica estadística.
- **Plotly** para visualización gráfica interactiva.

## 🗂️ Estructura del proyecto y organización de los análisis
El proyecto está compuesto por distintas etapas bien diferenciadas:

1. Importación de los datos desde una API en formato JSON.
2. Limpieza de datos: eliminación de valores nulos y duplicados.
3. Creación de nuevas variables para el análisis (como cuentas diarias).
4. Estandarización: traducción de etiquetas al español y conversión de tipos de datos.
5. Análisis descriptivo: cálculo de media, mediana, desviación estándar, etc.
6. Visualización de la distribución de churn mediante gráficos circulares.
7. Análisis de churn según variables categóricas mediante gráficos de barras.
8. Análisis de churn según variables numéricas mediante boxplots, violin plots y KDE.
9. Análisis de correlación con matriz de calor y gráficos interactivos.
10. Conclusiones finales y recomendaciones estratégicas.

## Ejemplos de gráficos e insights obtenidos.
- 📊 Gráficos de barras para el análisis de las variables categóricas con 'churn'.
- 🥧 Gráficos de torta para la visualización de la distribución del 'churn'.
- 📦 Gráficos de cajas para el análisis de las variables numéricas con 'churn' al igual que el uso del gráfico de violín 🎻.

## 🚀 Instrucciones para ejecutar el notebook
1. Descarga el archivo `.ipynb` desde este repositorio.
2. Súbelo a tu [Google Drive](https://drive.google.com/)
3. Ábrelo con [Google Colab](https://colab.research.google.com/).
4. Ejecutá las celdas en orden, comenzando por la sección de importación de datos.
5. Asegurate de tener los archivos o links a la API correctamente configurados.

⚠️ Nota: Es necesario tener una cuenta en Google y GitHub. No olvides conectar el entorno de ejecución en Colab con Google Compute Engine y verificar que los archivos de datos estén correctamente cargados así como la correcta importación de las bibliotecas de Python.
