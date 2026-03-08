# Análisis de evasión de clientes - Telecom X

Este proyecto tiene como objetivo analizar los datos de clientes de Telecom X para entender los factores relacionados con la evasión de clientes (Churn).

El análisis se realizó utilizando Python en Google Colab, aplicando técnicas básicas de limpieza, transformación y exploración de datos.

---

## Objetivo del proyecto

El objetivo principal es explorar el comportamiento de los clientes y detectar posibles patrones relacionados con la cancelación del servicio.

A partir de este análisis se busca identificar variables que puedan estar relacionadas con el churn.

---

## Datos utilizados

Se utilizó un archivo en formato **JSON** que contiene información sobre los clientes de Telecom X, incluyendo:

- información demográfica
- tipo de contrato
- servicios contratados
- cargos mensuales
- cargos totales
- estado de churn

---

## Proceso de análisis

Durante el proyecto se realizaron las siguientes etapas:

### 1. Extracción de datos
Se cargaron los datos desde un archivo JSON utilizando **Pandas**.

### 2. Transformación y limpieza
Se realizaron diferentes procesos para preparar los datos:

- normalización de datos con `json_normalize`
- tratamiento de valores nulos
- conversión de tipos de datos
- creación de nuevas variables
- renombrado de columnas

### 3. Análisis exploratorio
Se realizaron estadísticas descriptivas y algunos gráficos para analizar:

- distribución del churn
- relación entre churn y variables categóricas
- relación entre churn y variables numéricas

---

## Herramientas utilizadas

- Python
- Pandas
- Matplotlib
- Google Colab

---

## Resultados generales

El análisis permitió observar algunos patrones relacionados con la evasión de clientes.  
Por ejemplo, se identificaron diferencias en los cargos mensuales y en el tipo de contrato entre los clientes que permanecen y los que cancelan el servicio.

Estos resultados pueden servir como base para análisis más avanzados.

---

## Autor

Proyecto realizado como parte del proceso de aprendizaje en análisis de datos.
