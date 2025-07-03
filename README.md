# README - Análisis de Evasión de Clientes (Churn) para TelecomX

## Descripción del Proyecto

Este proyecto tiene como objetivo principal analizar el comportamiento de los clientes de TelecomX para entender los factores asociados a la evasión o cancelación del servicio (conocido como *Churn*). A través del análisis exploratorio de datos y la limpieza de la información, se busca identificar patrones que ayuden a reducir la tasa de cancelaciones y mejorar la retención de clientes.

## Contenidos

* `TelecomX_Data.json`: Dataset original con la información de clientes y servicios.
* `notebook.ipynb`: Notebook de Jupyter/Colab donde se realiza la carga, limpieza, análisis y visualización de datos.
* `graficos/`: Carpeta con imágenes generadas de gráficos relevantes (opcional).
* `README.md`: Documento con la descripción y detalles del proyecto.

## Objetivos del Análisis

* Importar y transformar los datos en un formato adecuado para análisis.
* Detectar y corregir inconsistencias, valores faltantes o duplicados.
* Realizar análisis descriptivos para entender la distribución de variables clave.
* Explorar la relación entre variables categóricas y numéricas con la evasión.
* Visualizar patrones y diferencias entre clientes que permanecen y los que cancelan.
* Generar insights para apoyar decisiones estratégicas orientadas a la retención.

## Metodología

1. **Carga y transformación de datos**: Se importó el JSON y se expandieron las columnas anidadas en un DataFrame plano.
2. **Limpieza de datos**: Se revisaron y corrigieron inconsistencias, estandarizando texto y verificando la integridad de la información.
3. **Análisis exploratorio**:

   * Descripción estadística de variables numéricas.
   * Visualización de la distribución de la variable `Churn`.
   * Estudio de la evasión según variables categóricas relevantes.
   * Comparación de métricas numéricas entre clientes que cancelaron y los que permanecen.
4. **Interpretación y conclusiones**: Se sintetizaron los hallazgos clave para guiar acciones de negocio

## Requisitos

* Python 3.x
* Librerías:

  * pandas
  * matplotlib
  * seaborn
  * json (builtin)

Se recomienda ejecutar el análisis en un entorno como Google Colab para facilitar la carga y visualización.

## Cómo ejecutar

1. Subir el archivo `TelecomX_Data.json` al entorno de trabajo.
2. Ejecutar el notebook paso a paso para:

   * Cargar y limpiar datos.
   * Realizar análisis y visualizar resultados.
3. Interpretar las visualizaciones para entender los patrones de evasión.

## Resultados esperados

* Identificación de variables asociadas a mayor o menor tasa de evasión.
* Visualizaciones claras que permitan comunicar hallazgos a stakeholders.
* Base sólida para desarrollar modelos predictivos o estrategias de retención.

## Autor

Pamela C
