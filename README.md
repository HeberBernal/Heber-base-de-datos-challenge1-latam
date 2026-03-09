# Heber-base-de-datos-challenge1-latam
# 📊 Análisis de Datos de Ventas - Alura Store LATAM

Este repositorio contiene el proyecto desarrollado para el **Challenge de Data Science de Alura Latam**. El objetivo es realizar un análisis exploratorio de datos de ventas de diferentes tiendas para obtener información clave sobre su rendimiento, facturación y tendencias.

El análisis está documentado en el Jupyter Notebook `AluraStoreLatamHeber.ipynb`, donde se detalla cada paso del proceso, desde la carga de datos hasta la visualización de los resultados.

---

# **Estrategia de Optimización Comercial: Análisis Multitienda 📊**

Este proyecto aplica un pipeline de **Data Science** para evaluar la rentabilidad y eficiencia de cuatro unidades de negocio, fundamentando decisiones estratégicas de reestructuración basadas en evidencia cuantitativa.

---

## **🛠️ Herramientas y Librerías**
* **Pandas**: Carga, limpieza y manipulación de DataFrames.
* **NumPy**: Cálculos estadísticos y regresión lineal.
* **Matplotlib**: Arquitectura base de las visualizaciones.
* **Seaborn**: Estilización de gráficos estadísticos y paletas de colores.

---

## **🛠️ Pipeline de Análisis**

### **1. Carga y Consolidación de Datos**
* **Código clave:** `pd.read_csv()`, `pd.concat()`, `df['Tienda'] = 'ID'`.
* **Propósito:** Se realiza la **extracción de datos** desde fuentes remotas y se **unifican** los datasets individuales en una estructura única. Este paso permite realizar comparativas directas entre sucursales manteniendo la **trazabilidad** de la información de origen.



### **2. Limpieza y Preprocesamiento de Datos**
* **Código clave:** `.to_numeric()`, `.fillna(0)`, `errors='coerce'`.
* **Propósito:** Aquí se realiza una **inspección e intervención** de los datos para asegurar su calidad. Se convierten columnas críticas (**Precio, Costo de envío**) a tipos numéricos y se gestionan **valores nulos o errores de formato**, garantizando la **exactitud** de los cálculos financieros posteriores.



### **3. Análisis Exploratorio de Datos (EDA)**
* **Código clave:** `.groupby()`, `.mean()`, `.sum()`, `.idxmax()`.
* **Propósito:** Se exploran las variables para extraer **indicadores clave de desempeño (KPIs)**. Se calculan promedios de calificación, **facturación total** por tienda y se identifican los productos líderes y rezagados en ventas para entender el comportamiento de cada mercado.

### **4. Visualización de Resultados**
* **Código clave:** `plt.bar()`, `plt.scatter()`, `np.polyfit()`, `sns.barplot()`.
* **Propósito:** Se transforman los hallazgos en **narrativas visuales** de alto impacto. Se utilizan gráficos de barras apiladas para ver la **carga logística** y diagramas de dispersión con **líneas de tendencia** para identificar qué tiendas se desvían de la **eficiencia operativa** esperada.



---

## **📈 Conclusión Estratégica**
Tras completar el pipeline, el análisis determinó que la **Tienda 1** es el referente de éxito en facturación y eficiencia, mientras que la **Tienda 4** presenta un rendimiento crítico que justifica una recomendación de **cierre o reestructuración** inmediata.

---

**Autor:** Heber Job Bernal Monarrez 

---

## **🚀 Cómo Replicar el Análisis**

Si deseas ejecutar este proyecto en tu entorno local o en tu propio **Jupyter Notebook**, sigue estos sencillos pasos:

### **1. Clona el repositorio**

### **Instala las librerías necesarias:**

pip install pandas matplotlib seaborn jupyter

## **🚀 Cómo Replicar el Análisis**

### **1. Clona el repositorio**
* **Código clave:** `git clone https://github.com/HeberBernal/Heber-base-de-datos-challenge1-latam.git`.
* **Propósito:** Obtener una copia local exacta del proyecto y todos sus archivos de datos para iniciar el entorno de trabajo.

### **2. Instala las librerías necesarias**
* **Código clave:** `pip install pandas matplotlib seaborn jupyter`.
* **Propósito:** Configurar el entorno de Python con las dependencias requeridas para asegurar que el procesamiento de datos y las visualizaciones funcionen correctamente.

### **3. Abre el Notebook**
* **Código clave:** `jupyter notebook`.
* **Propósito:** Iniciar la interfaz interactiva de Jupyter para poder visualizar y editar el código del análisis de forma dinámica.

### **4. Ejecución**
* **Código clave:** `AluraStoreLatamHeber.ipynb`, `Shift + Enter`.
* **Propósito:** Ejecutar secuencialmente las celdas de código para procesar los datos en tiempo real y generar los reportes visuales finales.
