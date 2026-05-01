# Preprocesamiento de datos y modelado predictivo aplicado a datos.
Para ejemplificar la aplicación de un modelo de clasificación se emplea la base pública “Titanic: Machine Learning from Disaster” del sitio web https://www.kaggle.com/, la cual es usada ampliamente por los usuarios de análisis de datos para probar diversas técnicas y algoritmos de predicción.
Dependiendo de las características de las personas como sex(sexo), Age(edad), Clase-socioeconómica entre otras, el objetivo es generar un modelo de clasificación para determinar cuáles personas sobreviven y cuáles fallecen en función de estas variables predictoras.

Se tiene la siguiente estructura:

## Preprocesamiento de datos.
1. Importación de las bases.
2. Exploración preliminar de la información.
3. Tratamiento de datos faltantes.
4. Análisis univariado de la respuesta y análisis bivariado respecto a los predictores.
5. Ingeniería y transformación de variables.
6. Eliminación de algunas variables predictoras.
7. Análisis de datos atípicos.
8. Generación de conjunto de entrenamiento y validación

## Modelos de regresión logística con penalización Ridge y LASSO.
### Modelo Ridge con búsqueda de hiperparámetros.
### Modelo LASSO con búsqueda de hiperparámetros.

## Arboles de decisión.
### Búsqueda con cuadricula
### Optimización Bayesiana

## Bosques aleatorios.
### Búsqueda con cuadricula
### Optimización Bayesiana



## Estructura

- data/: datos_titanic.csv (incluidos)
- notebooks/: análisis
- requirements.txt: dependencias

## Cómo usar

```bash
pip install -r requirements.txt
