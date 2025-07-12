Proyecto: Análisis de Churn de Clientes en Telecom X
Descripción del Proyecto
Este proyecto tiene como objetivo principal analizar el comportamiento de los clientes de la empresa Telecom X para identificar los factores que influyen en la tasa de cancelación de servicios (churn). A través de la exploración y visualización de datos, buscamos comprender por qué los clientes se van y proponer estrategias basadas en datos para mejorar la retención de clientes.

Los datos utilizados provienen de una base de datos de clientes de Telecom X en formato JSON, conteniendo información demográfica, servicios contratados y estado de churn.

Estructura del Proyecto
El proyecto está organizado en un cuaderno de Google Colab que sigue un flujo de trabajo típico de análisis de datos:

Extracción de Datos: Carga inicial de los datos desde la fuente JSON.
Conocimiento del Conjunto de Datos: Exploración inicial de la estructura, tipos de datos y valores únicos.
Limpieza y Tratamiento de Datos: Normalización de columnas anidadas, manejo de valores faltantes y duplicados, corrección de tipos de datos y estandarización de nombres.
Análisis Exploratorio de Datos (EDA): Realización de análisis descriptivos y visualizaciones (gráficos de distribución, tasas de churn por categoría) para identificar patrones y relaciones.
Informe Final: Resumen de los hallazgos clave, conclusiones e insights, y recomendaciones estratégicas.
Datos
El conjunto de datos utilizado para este análisis se encuentra en formato JSON y está disponible en el siguiente enlace:

https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/main/TelecomX_Data.json

Se incluye un diccionario de datos en formato Markdown en el siguiente enlace:

https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/main/TelecomX_diccionario.md

Cómo Ejecutar el Cuaderno
Para ejecutar este análisis, sigue los siguientes pasos:

Abre el cuaderno en Google Colab.
Asegúrate de tener una conexión a internet para descargar los datos.
Ejecuta cada celda de código secuencialmente. El cuaderno contiene comentarios y texto explicativo para guiarte a través del proceso.
Dependencias
El cuaderno utiliza las siguientes bibliotecas de Python:

pandas: Para manipulación y análisis de datos.
matplotlib: Para la creación de visualizaciones estáticas.
seaborn: Para la creación de visualizaciones estadísticas atractivas.
requests: Para descargar el diccionario de datos desde una URL.
Estas bibliotecas están preinstaladas en el entorno de Google Colab.

Hallazgos Clave
(Esta sección debe ser completada después de ejecutar el análisis y revisar el informe final. Puedes resumir los principales hallazgos sobre qué factores están más relacionados con el churn).

Recomendaciones
(Esta sección debe ser completada después de revisar las recomendaciones en el informe final. Puedes listar las sugerencias estratégicas para reducir el churn).
