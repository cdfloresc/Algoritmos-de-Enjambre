# Actividad 03: Algoritmos de Enjambre

Este repositorio contiene la implementación en Python (Google Colab) de algoritmos de inteligencia de enjambre aplicados a problemas avanzados de Machine Learning.

## Autor: Cristian Darwin Flores Cueva

## Contenido Técnico

El archivo `Algoritmos_de_Enjambre.ipynb` contiene la resolución de 4 retos fundamentales:

1. **Feature Selection con Colonia Artificial de Abejas (ABC):** Reducción de dimensionalidad en un conjunto de datos sintético de 100 características usando representación binaria.
2. **Hyperparameter Tuning con PSO:** Búsqueda en espacios continuos/discretos de los mejores parámetros (`n_estimators`, `max_depth`, `min_samples_split`) para un ensamble Random Forest.
3. **Entrenamiento de Red Neuronal con PSO:** Optimización de una arquitectura MLP (42 dimensiones de pesos y sesgos) sin utilizar Backpropagation ni gradientes, minimizando el Log Loss.
4. **Clustering de Alta Dimensionalidad con PSO:** Búsqueda global de 10 centroides sobre un espacio de 64 dimensiones (Dataset de Dígitos), con reducción dimensional mediante PCA para su visualización.

## Instalación y Ejecución
1. Descargar el archivo `.ipynb` de este repositorio.
2. Subir el archivo a [Google Colab](https://colab.research.google.com/).
3. Ejecutar la primera celda para instalar las dependencias (`!pip install pyswarms`).
4. Ejecutar el resto de las celdas en orden secuencial.
