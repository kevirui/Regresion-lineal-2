# Data Science - Regresión Lineal II

Este proyecto corresponde a la segunda parte del curso de regresión lineal de Alura LATAM. El objetivo es desarrollar un sistema de valuación inmobiliaria utilizando técnicas de regresión lineal aplicadas a un dataset de inmuebles en Rio de Janeiro.

## Descripción del Proyecto

El mercado inmobiliario ha sido objeto de diversos estudios, especialmente debido a la influencia de la economía en las inversiones y ganancias del sector. En este contexto, el proyecto busca predecir el valor de los inmuebles a partir de sus características y ubicación, utilizando modelos de regresión lineal.

## Dataset

El dataset utilizado es una muestra aleatoria de 5000 inmuebles en venta en el municipio de Rio de Janeiro. Las variables incluidas son:

- **Valor**: Precio de oferta del inmueble (US$)
- **Área**: Área del inmueble en m²
- **Dist_Playa**: Distancia a la playa más cercana (km)
- **Dist_Farmacia**: Distancia a la farmacia más cercana (km)

## Estructura del Proyecto

- `Regresión_Lineal_II.ipynb`: Notebook principal con el análisis, visualización y modelado.
- `dataset.csv`: Dataset utilizado para el análisis.
- `README.md`: Este archivo.

## Pasos Principales

1. **Exploración y análisis preliminar de los datos**
2. **Visualización de variables y relaciones**
3. **Transformación de variables (logarítmica)**
4. **División de los datos en entrenamiento y prueba**
5. **Ajuste de modelos de regresión lineal (con `statsmodels` y `scikit-learn`)**
6. **Evaluación del modelo y análisis de residuos**
7. **Interpretación de coeficientes y simulación de predicciones**

## Requisitos

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- statsmodels

Puedes instalar los requisitos ejecutando:

```sh
pip install pandas numpy seaborn matplotlib scikit-learn statsmodels
```

## Ejecución

Abre el archivo `Regresión_Lineal_II.ipynb` en Jupyter Notebook o Visual Studio Code y sigue las celdas en orden para reproducir el análisis.

---

**Autor:** Kevin Agustin Ruiz  
**Curso:** Data Science - Regresión Linea II Alura Latam