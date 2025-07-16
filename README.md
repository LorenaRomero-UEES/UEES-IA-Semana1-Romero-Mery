# UEES-IA-Semana1-Grupo 5
Laboratorio práctico de Inteligencia Artificial con Python: 4 notebooks explorando NumPy, Pandas, visualización de datos, Machine Learning y Deep Learning usando el dataset Titanic. Proyecto para UEES - Maestría en Inteligencia de Negocios y Ciencia de Datos.

## Dataset Utilizado

**Dataset**: Titanic Survival Dataset
**Fuente**: Seaborn library datasets
**Descripción**: Datos de pasajeros del RMS Titanic incluyendo información demográfica, clase de boleto, ubicación y estado de supervivencia.

**Características principales**:
- 891 registros de pasajeros
- 12 variables (demográficas, socioeconómicas, ubicación)
- Variable objetivo: supervivencia (binaria)

## Contenido de los Notebooks

### Notebook 1: Fundamentos NumPy y Pandas
- Configuración del entorno de trabajo en Google Colab
- Ejercicios de manipulación de arrays con NumPy
- Carga, limpieza y transformación de datos con Pandas
- Análisis exploratorio de datos básico
- Estadísticas descriptivas y agrupaciones

### Notebook 2: Visualización de Datos
- Implementación de gráficos básicos con Matplotlib
- Visualizaciones estadísticas avanzadas con Seaborn
- Desarrollo de gráficos interactivos con Plotly
- Análisis visual de patrones de supervivencia
- Exportación y gestión de imágenes generadas

### Notebook 3: Machine Learning Básico
- Preparación y preprocesamiento de datos para ML
- Implementación de múltiples algoritmos de clasificación
- Evaluación y comparación de modelos tradicionales
- Análisis de importancia de características
- Métricas de rendimiento y validación

### Notebook 4: Introducción a Deep Learning
- Diseño de arquitectura de red neuronal artificial
- Implementación con TensorFlow/Keras
- Configuración de entrenamiento y regularización
- Visualización del proceso de aprendizaje
- Comparación con enfoques tradicionales de ML

## Instalación y Configuración

### Prerrequisitos
- Python 3.7 o superior
- Google Colab (recomendado) o Jupyter Notebook
- Acceso a internet para descarga de datasets

### Instalación de Dependencias
requirements.txt

## Configuración en Google Colab

1. Abrir Google Colab (https://colab.research.google.com/)
2. Cargar cada notebook desde el repositorio de GitHub
3. Ejecutar la celda de configuración inicial en cada notebook
4. Las dependencias se instalarán automáticamente

## Uso

### Ejecución Secuencial

1. Ejecutar Notebook 1 para familiarizarse con el dataset
2. Continuar con Notebook 2 para análisis visual
3. Proceder con Notebook 3 para modelos tradicionales
4. Finalizar con Notebook 4 para deep learning

### Ejecución Independiente

Cada notebook puede ejecutarse de forma independiente ya que incluye:

- Configuración completa del entorno
- Carga independiente del dataset
- Importaciones necesarias

## Resultados Principales

### Rendimiento de Modelos

- **Random Forest**: 82.68% de precisión (mejor modelo tradicional)
- **Red Neuronal**: 80.45% de precisión
- **Regresión Logística**: 79.89% de precisión

### Variables Más Importantes

1. Género del pasajero (sex)
2. Clase del boleto (pclass)
3. Edad del pasajero (age)
4. Tarifa pagada (fare)
5. Puerto de embarque (embarked)

### Insights del Análisis

- Las mujeres tuvieron mayor tasa de supervivencia que los hombres
- Los pasajeros de primera clase tuvieron mejores probabilidades de supervivencia
- La edad y la tarifa pagada correlacionan positivamente con la supervivencia
- Los modelos tradicionales de ML son competitivos para este dataset tabular

## Tecnologías Utilizadas

### Manipulación de Datos

- **NumPy**: Operaciones numéricas y manejo de arrays
- **Pandas**: Análisis y manipulación de datos estructurados

### Visualización

- **Matplotlib**: Gráficos básicos y personalizados
- **Seaborn**: Visualizaciones estadísticas avanzadas
- **Plotly**: Gráficos interactivos y dashboards

### Machine Learning

- **Scikit-learn**: Algoritmos de ML tradicionales y métricas
- **TensorFlow/Keras**: Implementación de redes neuronales
- **StandardScaler**: Normalización de datos

### Entorno de Desarrollo

- **Google Colab**: Plataforma de notebooks en la nube
- **Jupyter**: Entorno de desarrollo interactivo
- **Git/GitHub**: Control de versiones y colaboración

## Metodología

### Enfoque de Desarrollo

1. **Análisis Exploratorio**: Comprensión inicial del dataset
2. **Visualización**: Identificación de patrones mediante gráficos
3. **Modelado Tradicional**: Implementación de algoritmos clásicos
4. **Deep Learning**: Desarrollo de modelo neuronal
5. **Comparación**: Evaluación integral de enfoques

### Métricas de Evaluación

- Precisión (Accuracy)
- Matriz de Confusión
- Reporte de Clasificación
- Importancia de Características
- Curvas de Aprendizaje

## Contribuciones y Mejoras Futuras

### Posibles Extensiones

- Implementación de modelos ensemble más sofisticados
- Experimentación con arquitecturas de deep learning más complejas
- Análisis de interpretabilidad de modelos
- Optimización de hiperparámetros mediante grid search
- Validación cruzada estratificada

### Limitaciones Actuales

- Dataset relativamente pequeño para deep learning
- Ausencia de validación cruzada en algunos modelos
- Preprocesamiento básico de datos faltantes

## Autores

**Nombre**: Mery Romero, José Navarro, Jennifer Lainez, Karina Cali, Ruben Acebo  
**Email**: mery.romero@uees.edu.ec - jose.navarro@uees.edu.ec - jenniffer.lainez@uees.edu.ec - karina.cali@uees.edu.ec - racebo@uees.edu.ec

**Institución**: Universidad Espíritu Santo (UEES)  
**Programa**: Maestría en Inteligencia de Negocios y Ciencia de Datos  
**Curso**: Inteligencia Artificial

## Información Académica

**Institución**: Universidad Espíritu Santo (UEES)  
**Facultad**: Postgrado  
**Programa**: Maestría en Inteligencia de Negocios y Ciencia de Datos  
**Asignatura**: Inteligencia Artificial (MINCD 500)  
**Profesor**: PhD(c) Gladys Villegas Rugel  
**Período**: Julio 2025  
**Modalidad**: En línea

## Licencia

Este proyecto es desarrollado con fines académicos como parte del programa de maestría en la Universidad Espíritu Santo (UEES).
