# Heber-base-de-datos-challenge1-latam
# 📊 Análisis de Datos de Ventas - Alura Store LATAM

Este repositorio contiene el proyecto desarrollado para el **Challenge de Data Science de Alura Latam**. El objetivo es realizar un análisis exploratorio de datos de ventas de diferentes tiendas para obtener información clave sobre su rendimiento, facturación y tendencias.

El análisis está documentado en el Jupyter Notebook `AluraStoreLatamHeber.ipynb`, donde se detalla cada paso del proceso, desde la carga de datos hasta la visualización de los resultados.

---

### 💻 Herramientas y Tecnologías

El proyecto fue desarrollado en Python utilizando las siguientes librerías:

* **Pandas**: Para la manipulación y el análisis de datos.
* **Matplotlib y Seaborn**: Para la visualización de datos.

---

### 📚 Explicación del Código en el Notebook

El archivo `AluraStoreLatamHeber.ipynb` está estructurado de manera lógica para un análisis de datos completo. A continuación, se explican las secciones principales y el propósito del código en cada una:

#### 1. Carga y Consolidación de Datos
* **Código clave:** `pd.read_csv()`, `pd.concat()`
* **Propósito:** Esta sección se encarga de importar las bases de datos de cada una de las cuatro tiendas (`tienda_1.csv` a `tienda_4.csv`) en un `DataFrame` de Pandas. Luego, todas las bases de datos se combinan en un solo `DataFrame` para que el análisis pueda realizarse sobre el conjunto total de ventas. Esto garantiza que se trabaje con toda la información de manera unificada.

#### 2. Limpieza y Preprocesamiento de Datos
* **Código clave:** `.info()`, `.isnull().sum()`, `df['columna'].astype()`
* **Propósito:** Aquí se realiza una inspección inicial de los datos para identificar y corregir posibles problemas. Se verifica la información de cada columna, se revisa si hay valores nulos y se asegura de que los tipos de datos sean correctos (por ejemplo, que las columnas numéricas sean de tipo numérico). Este paso es fundamental para asegurar la calidad y exactitud del análisis posterior.

#### 3. Análisis Exploratorio de Datos (EDA)
* **Código clave:** `df.groupby()`, `.sum()`, `.sort_values()`
* **Propósito:** En esta sección, el código se enfoca en responder preguntas de negocio específicas. Se agrupan los datos por tienda (`groupby()`) para calcular métricas clave como la **facturación total por tienda**, el **número de transacciones** y la **cantidad de ítems vendidos**. Esto permite identificar rápidamente el rendimiento de cada una y cuáles son las que más contribuyen a las ventas.

#### 4. Visualización de Resultados
* **Código clave:** `plt.bar()`, `sns.barplot()`, `plt.show()`
* **Propósito:** Una vez que se obtienen las métricas, el código utiliza `Matplotlib` y `Seaborn` para crear **gráficos de barras** que muestran de forma visual y clara los resultados del análisis. Se generan visualizaciones para comparar la facturación total y el número de transacciones por tienda, lo que facilita la comprensión de las conclusiones del análisis.

---

### 🚀 Cómo Replicar el Análisis

Si deseas ejecutar este proyecto en tu entorno local, sigue estos sencillos pasos:

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/HeberBernal/Heber-base-de-datos-challenge1-latam.git](https://github.com/HeberBernal/Heber-base-de-datos-challenge1-latam.git)
    ```

2.  **Instala las librerías necesarias:**
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```

3.  **Abre el notebook:**
    Navega hasta la carpeta del proyecto y ejecuta el siguiente comando para abrir Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
    Luego, haz clic en el archivo `AluraStoreLatamHeber.ipynb` para abrirlo.

4.  **Ejecuta las celdas:**
    Ejecuta cada celda del notebook en orden para ver el análisis completo.

---

### 📧 Contacto

Si tienes alguna pregunta o sugerencia sobre el proyecto, no dudes en contactarme a través de mi perfil de GitHub.

* [Heber Bernal](https://github.com/HeberBernal)
