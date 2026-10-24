# Análisis del reciclaje de residuos municipales por grupo de ingreso económico

## Descripción del proyecto

Este proyecto analiza las diferencias en el porcentaje de residuos municipales tratados mediante reciclaje entre países de distintos grupos de ingreso económico, utilizando datos de la base *What a Waste 3.0* del Banco Mundial.

## Pregunta de investigación

¿Existen diferencias estadísticamente significativas en el porcentaje de residuos municipales tratados mediante reciclaje entre países de distintos grupos de ingreso económico?

## Datos

Se utilizó el conjunto de datos de países de *What a Waste 3.0*. Después de la limpieza y selección de las variables relevantes, el análisis incluyó 130 países con datos válidos.

## Herramientas utilizadas

- Python
- Pandas para la manipulación y limpieza de datos
- Matplotlib para las visualizaciones estáticas
- Plotly para la visualización interactiva
- SciPy para la prueba estadística de Kruskal-Wallis
- Google Colab para la ejecución del análisis

## Metodología

1. Exploración inicial del conjunto de datos.
2. Limpieza y selección de variables.
3. Análisis exploratorio mediante visualizaciones.
4. Comparación estadística entre los grupos de ingreso económico mediante Kruskal-Wallis.
5. Interpretación de resultados y elaboración de conclusiones.

## Resultados principales

El grupo de ingresos altos (HIC) presentó un promedio de reciclaje del 24,29 %, mientras que el grupo de ingresos bajos (LIC) registró un 5,81 %.

La prueba de Kruskal-Wallis obtuvo un estadístico de 43,0226 y un valor p aproximado de 2,434 × 10⁻⁹, lo que evidencia diferencias estadísticamente significativas entre las distribuciones de los grupos analizados.

## Archivo del proyecto

El repositorio contiene el notebook de Jupyter (`.ipynb`) con el código y las visualizaciones del análisis.

## Fuente de datos

Banco Mundial, conjunto de datos *What a Waste 3.0*.
