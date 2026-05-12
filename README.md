📊 Análisis de Ventas Minoristas (2009–2010)
📌 Descripción del proyecto

Este proyecto tiene como objetivo analizar datos `de transacciones de comercio electrónico correspondientes a los años 2009–2010.

Se realiza un proceso completo de:

Limpieza y transformación de datos

Análisis descriptivo y estadístico

Creación de métricas clave de negocio

Desarrollo de un dashboard interactivo en Power BI

🛠 Herramientas utilizadas

Python (Pandas, NumPy)

Jupyter Notebook

Power BI

GitHub

📂 Fuentes de datos

Se utilizaron dos conjuntos de datos en bruto:

Dataset de transacciones retail (Excel)

Dataset de ventas (CSV)

Ambos fueron integrados para generar un dataset final unificado.

🧹 Preparación de los datos

Se realizaron las siguientes transformaciones:

Eliminación de valores nulos

Corrección de tipos de datos

Creación de variables derivadas

Cálculo de Total_Amount = Quantity × Price

Cálculo de ventas netas tras descuento

Creación de variables temporales (Year, Month)

Agrupación geográfica por región

Dataset final:

400.916 transacciones

Más de 20 columnas

📊 Indicadores principales (KPIs)

Número de Transacciones

Ventas Totales

Ventas Netas

Ticket Promedio

% de Descuento

📈 Principales conclusiones

Fuerte estacionalidad en el último trimestre del año.

Alta concentración de ventas en la región West.

Ticket promedio aproximado de 22 €.

Impacto medio del descuento del 15%.

Concentración de ingresos en productos clave.

📂 Estructura del repositorio

data/raw/ → Datos en bruto

data/processed/ → Dataset final

notebooks/ → Limpieza y análisis en Python

dashboard/ → Archivo Power BI

reports/ → Informe del análisis


## 📦 Dataset procesado

El archivo `dataset_final.csv` no se incluye en el repositorio debido a su tamaño (60 MB).

Puede generarse ejecutando el notebook:

notebooks/dataset_final.ipynb

El notebook realiza:

-Limpieza de datos
-Transformaciones
-Creación de variables derivadas
-Exportación del dataset final
-📄 Archivo original en formato XLSX

El archivo original utilizado en el proyecto puede descargarse desde el siguiente enlace de Google Drive:

https://docs.google.com/spreadsheets/d/1qZpzxAusVBjJ0b8NlVRaKfE2xlz1TvZi/edit?usp=sharing

📂 Dataset procesado

El archivo procesado utilizado en el proyecto puede descargarse desde el siguiente enlace de Google Drive:

https://drive.google.com/file/d/18e7iWe-HPM1W7p2PL2F5RcowyVaY3DsF/view?usp=drive_link

👤 Autora

Cristina Ales Sanchez

