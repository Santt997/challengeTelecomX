# challengeTelecomX

# Análisis de Evasión de Clientes (Churn) en Telecomunicaciones

## 📊 Proyecto de Data Science: TelecomX_LATAM

Este proyecto de análisis de datos explora el fenómeno de la evasión de clientes (Churn) en el sector de las telecomunicaciones, utilizando datos de la iniciativa TelecomX_LATAM. El objetivo principal es identificar patrones, factores clave y desarrollar insights que permitan a las empresas de telecomunicaciones comprender mejor por qué los clientes deciden abandonar el servicio y, en consecuencia, implementar estrategias efectivas para reducir la tasa de Churn.

## ✨ Objetivos del Proyecto

*   **Comprender el Problema del Churn:** Realizar un análisis exploratorio profundo para identificar las características de los clientes que tienden a evadir.
*   **Identificar Factores Clave:** Determinar las variables y comportamientos de los clientes que están más fuertemente correlacionados con la evasión.
*   **Proporcionar Insights Accionables:** Generar conclusiones y recomendaciones basadas en el análisis de datos para informar estrategias de retención de clientes.

## 💻 Tecnologías y Herramientas Utilizadas

*   **Python:** Lenguaje de programación principal para el análisis de datos.
*   **Pandas:** Librería para manipulación y análisis de datos estructurados.
*   **NumPy:** Librería para computación numérica.
*   **Matplotlib:** Librería para la creación de visualizaciones estáticas.
*   **Requests:** Librería para realizar solicitudes HTTP (descarga de datos).
*   **Google Colab:** Entorno de desarrollo basado en la nube para ejecutar el código Python.

## 📁 Estructura del Repositorio

*   `TelecomX_LATAM.ipynb`: Cuaderno de Google Colab que contiene todo el código fuente para la carga de datos, limpieza, análisis exploratorio y visualizaciones.
*   `README.md`: Este archivo, proporcionando una descripción general del proyecto.
*   *(Opcional) Otros archivos de datos o recursos si son necesarios.*

## 🚀 Cómo Ejecutar el Cuaderno

1.  Abre el archivo `TelecomX_LATAM.ipynb` en Google Colab.
2.  Asegúrate de tener las librerías necesarias instaladas. El cuaderno incluye celdas para instalar o actualizar las dependencias (`!pip install pandas==2.2.2`, `!pip install --upgrade requests`).
3.  Ejecuta las celdas del cuaderno secuencialmente para replicar el análisis, desde la carga de datos hasta las visualizaciones y el informe final.

## 🔍 Análisis Realizado

El cuaderno de Colab documenta detalladamente las siguientes etapas:

1.  **Carga de Datos:** Obtención de los datos desde una fuente remota (JSON).
2.  **Limpieza y Preprocesamiento:** Manejo de valores nulos, conversión automática de tipos de datos utilizando la función `autoConvertDtypes` y creación de nuevas características (`Cuentas_Diarias`).
3.  **Análisis Exploratorio de Datos (EDA):**
    *   Análisis de cardinalidad de variables.
    *   Visualización de la distribución de Churn mediante gráficos de pastel.
    *   Exploración de la relación entre variables categóricas y el Churn utilizando gráficos de pastel.
    *   Análisis de la distribución de variables numéricas clave (`account.Charges.Total`, `Cuentas_Diarias`) comparando grupos de Churn y No Churn con histogramas.
4.  **Informe Final:** Un resumen detallado de los hallazgos clave, conclusiones e insights, así como recomendaciones estratégicas para mitigar el Churn.

## 💡 Conclusiones y Recomendaciones

El informe final dentro del cuaderno `TelecomX_LATAM.ipynb` presenta las principales conclusiones derivadas del análisis exploratorio, identificando posibles factores contribuyentes al Churn. Basado en estos hallazgos, se proponen recomendaciones estratégicas para mejorar la retención de clientes.

*(Nota: Para conocer las conclusiones y recomendaciones específicas, por favor, revisa la sección 'Informe Final' en el cuaderno `TelecomX_LATAM.ipynb`).*

## 🤝 Contribuciones

Este proyecto es parte de un desafío de Data Science y es un trabajo en progreso. Si tienes alguna sugerencia o mejora, ¡son bienvenidas!

## 📄 Licencia

*Sin licencia (free and open source)*

## 📧 Contacto

Si tienes alguna pregunta o comentario, no dudes en contactarme a santiago.burastero@gmail.com.

---

*Desarrollado con pasión por la Data Science.*
