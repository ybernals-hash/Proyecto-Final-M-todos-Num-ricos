📊 Proyecto Final de Análisis de Datos en Python
Este cuaderno de Google Colab (ProyectoFinal.ipynb) ha sido desarrollado como el proyecto final para el curso de Análisis de Datos. Su objetivo principal es demostrar la capacidad de cargar, manipular y visualizar un conjunto de datos externo utilizando las librerías estándar de Python para ciencia de datos.

🚀 Tecnologías y Dependencias
El proyecto está escrito en Python y requiere las siguientes librerías:

pandas: Esencial para la estructuración y manipulación de los datos (lectura del CSV, limpieza y transformaciones).

numpy: Utilizado para operaciones numéricas y matemáticas complejas sobre los datos.

matplotlib.pyplot: Empleado para la generación de gráficos y la visualización de los resultados del análisis.

⚙️ Cómo Empezar
A. Ejecución en Google Colab (Recomendado)
Abre el archivo ProyectoFinal.ipynb en tu navegador.

Asegúrate de que el entorno de ejecución esté configurado (generalmente Python 3).

Haz clic en "Entorno de ejecución" > "Ejecutar todo" para procesar todas las celdas de forma secuencial.

El cuaderno automáticamente descargará los datos desde la URL fuente.

B. Ejecución Local (Opcional)
Si deseas ejecutar este cuaderno en tu máquina local, debes tener instalado Python y un entorno Jupyter (como Anaconda).

Clona o descarga este repositorio.

Instala las dependencias necesarias a través de pip:

Bash

pip install pandas matplotlib numpy
Ejecuta el cuaderno abriéndolo con tu entorno Jupyter (jupyter notebook ProyectoFinal.ipynb).

💡 Flujo de Trabajo
El análisis dentro del cuaderno se lleva a cabo en los siguientes pasos:

Importación de Librerías: Se importan los módulos numpy, pandas y matplotlib.

Carga de Datos: Los datos se cargan directamente desde una hoja de cálculo pública de Google Sheets utilizando la URL de exportación a CSV:

Python

ruta_archivo = 'https://docs.google.com/spreadsheets/d/e/2PACX-1vSgD3-hMv4X_aCfuJnLRnNVRmoxPCfLk5GlxXGe8lGos7_tgQFpePoez79sHmK5gjtcNAXFGJr4wv2j/pub?output=csv'
df = pd.read_csv(ruta_archivo)
Análisis y Transformación: (Esta sección está lista para que detalles los pasos del análisis, ej: Cálculo de estadísticas descriptivas, agrupación de datos, etc.)

Visualización: Se generan gráficos para interpretar los hallazgos.

👥 Autores
Este proyecto fue desarrollado por:

Juan Fernando Gutierrez Gomez

Yeira Bernal Sierra
