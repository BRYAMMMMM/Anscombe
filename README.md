<h1 align="center" style="color:#1E90FF;">Proyecto Anscombe</h1> <h2 align="center">Introducción Teórica al Cuarteto de Anscombe</h2>

Universidad Politécnica Salesiana
Carrera: Ciencias de la Computación
Estudiante: Bryam Jesús Peralta Navarro
Periodo Académico: 67

Descripción General

El Cuarteto de Anscombe es un conjunto de cuatro grupos de datos creados por el estadístico Francis Anscombe en 1973.
Cada grupo presenta valores estadísticos prácticamente idénticos, como la media, la varianza y la correlación, pero al representarlos gráficamente revelan patrones totalmente diferentes.

Este trabajo demuestra la importancia de la visualización de datos en el análisis estadístico.
Los cálculos numéricos pueden parecer equivalentes, pero las gráficas muestran comportamientos que los números no evidencian, como distribuciones no lineales, valores atípicos o relaciones engañosas.

La principal enseñanza del Cuarteto de Anscombe es que la estadística descriptiva por sí sola no es suficiente.
La visualización permite comprender la forma, la dispersión y la tendencia real de los datos, proporcionando una interpretación más profunda y precisa.

Este conjunto inspiró el Datasaurus Dozen, un experimento que refuerza la idea de que diferentes patrones visuales pueden compartir estadísticas básicas idénticas.
Referencia Bibliográfica

Anscombe, F. J. (1973). Graphs in Statistical Analysis. The American Statistician, 27(1), 17–21.
Visualización Representativa del Cuarteto de Anscombe
<p align="center"> <img width="420" height="260" src="https://github.com/user-attachments/assets/290938a5-ca6b-456c-9c87-43ce89583698" alt="Cuarteto de Anscombe"> </p>
<h2 align="center" style="color:#1E90FF;">Estructura del Repositorio</h2>
El proyecto se organiza en tres carpetas principales, cada una con una función específica dentro del análisis del Cuarteto de Anscombe y del conjunto Datasaurus.
Carpeta Data

Contiene los conjuntos de datos utilizados en la práctica.
Aquí se almacenan los archivos con la información original que se emplea para generar las gráficas y realizar los análisis estadísticos.
Su función es mantener los datos ordenados y disponibles para su reproducción en diferentes entornos de trabajo.

Carpeta R

Incluye el código en lenguaje R utilizado para procesar, analizar y visualizar los datos.
En esta carpeta se encuentran los scripts que muestran los trece conjuntos del Datasaurus Dozen, junto con las instrucciones para realizar los cálculos y las gráficas.
Representa el núcleo técnico del proyecto, donde se desarrollan las operaciones de lectura, filtrado, graficación y modelado.

Carpeta RStudio

Contiene el documento elaborado en R Markdown en el entorno RStudio.
En este archivo se aplicó la regresión lineal al conjunto seleccionado del Datasaurus (v_lines) y se generó el reporte final en formato HTML.
Esta carpeta integra el código, las visualizaciones y la interpretación teórica en un solo documento reproducible.
