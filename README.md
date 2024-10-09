# Linear Models - Regression

Este repositorio contiene implementaciones de varios algoritmos de regresión lineal, así como de técnicas avanzadas que incluyen regularización y enfoques bayesianos.

## Descripción

El objetivo de este proyecto es explorar y comparar diferentes técnicas de regresión lineal para entender sus características, ventajas y limitaciones. Cada uno de los algoritmos implementados se describe a continuación:

- **Regresión Lineal**: Método base para modelar la relación entre variables dependientes e independientes utilizando la ecuación lineal estándar.
- **Lasso**: Regresión lineal con regularización L1 que permite la selección de variables y la reducción de coeficientes a cero.
- **Ridge**: Regresión lineal con regularización L2 que reduce la magnitud de los coeficientes para evitar el sobreajuste.
- **Elastic Net**: Combina las propiedades de Lasso y Ridge, ajustando tanto la selección de características como la reducción de la magnitud de los coeficientes.
- **Bayesian Regression**: Extiende la regresión lineal utilizando principios bayesianos, permitiendo una cuantificación explícita de la incertidumbre de los parámetros.

## Estructura del Proyecto

El repositorio está organizado en las siguientes carpetas:

- `notebooks/`: Contiene notebooks de Jupyter con ejemplos y visualizaciones.
- `scripts/`: Implementaciones de los algoritmos y utilidades para preprocesamiento de datos.
- `data/`: Archivos de datos utilizados para los experimentos.
- `results/`: Resultados generados por cada uno de los modelos, incluyendo métricas y visualizaciones.

## Requisitos

Los siguientes paquetes de Python son necesarios para ejecutar los scripts y notebooks:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
