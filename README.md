Anscombe
Introducción Teórica al Cuarteto de Anscombe

Universidad Politécnica Salesiana
Estudiante: Bryam Jesús Peralta Navarro
Periodo académico: 67
Carrera: Ciencias de la Computacion

El Cuarteto de Anscombe es un conjunto de cuatro grupos de datos diseñados por el estadístico Francis Anscombe en 1973. Cada grupo presenta valores estadísticos prácticamente idénticos, como la media, la varianza, la correlación y la ecuación de la regresión lineal. Sin embargo, cuando se representan gráficamente, los conjuntos revelan patrones totalmente distintos entre sí.

Este trabajo se considera un ejemplo clásico de por qué la visualización de datos es esencial en el análisis estadístico. Aunque los cálculos numéricos puedan sugerir resultados similares, las gráficas muestran comportamientos que los números no revelan: distribuciones no lineales, valores atípicos o relaciones engañosas.

La lección que deja el Cuarteto de Anscombe es que la estadística descriptiva por sí sola no es suficiente para interpretar correctamente los datos. Es fundamental acompañar el análisis numérico con representaciones visuales que permitan comprender la forma, dispersión y tendencia real de la información.

A partir de este conjunto se inspiraron posteriores ejercicios como el Datasaurus Dozen, que sigue el mismo principio: distintos patrones visuales con idénticas estadísticas básicas.

Referencia bibliográfica:
Anscombe, F. J. (1973). Graphs in Statistical Analysis. The American Statistician, 27(1), 17–21.

Visualización representativa del Cuarteto de Anscombe:

<img width="400" height="250" src="https://github.com/user-attachments/assets/290938a5-ca6b-456c-9c87-43ce89583698" alt="Cuarteto de Anscombe">

Estructura del Repositorio

El proyecto está organizado en tres carpetas principales. Cada una cumple una función específica dentro del análisis del Cuarteto de Anscombe y del conjunto Datasaurus.

Carpeta Data

En esta carpeta se guardan los conjuntos de datos utilizados durante la práctica.
Aquí se almacenan los archivos con la información original y limpia que se emplea para generar gráficos y realizar los análisis estadísticos.
Su propósito es centralizar las fuentes de datos de forma ordenada, asegurando que puedan ser reproducidas fácilmente por cualquier usuario que consulte el repositorio.

Carpeta R

Contiene el código en lenguaje R que se utiliza para visualizar, procesar y analizar los datos.
Incluye scripts que muestran los trece conjuntos del Datasaurus Dozen, así como las instrucciones para realizar las gráficas y cálculos necesarios.
Esta carpeta representa la parte técnica del análisis, donde se desarrollan las funciones de lectura, filtrado, graficación y ajuste de modelos.

Carpeta RStudio

Aquí se encuentra el documento creado en R Markdown donde se ejecutó el análisis completo.
Incluye la regresión lineal aplicada al conjunto seleccionado del Datasaurus (en este caso, el dataset v_lines).
