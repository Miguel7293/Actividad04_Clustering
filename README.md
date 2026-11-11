# Actividad 04 — Clustering

Comparación de K-means, DBSCAN y SpectralClustering sobre Iris, Moons y Circles. Se evalúan los agrupamientos con ARI, V-measure, silueta y Davies-Bouldin. También se usa el método del codo para explorar el número de grupos de K-means.

## Ejecutar el cuaderno

Abre [Actividad_04_Clustering.ipynb](Actividad_04_Clustering.ipynb) en Google Colab o Jupyter y ejecuta todas las celdas. En Jupyter local instala primero `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `scipy` y `jinja2`. Inicia la ejecución desde la raíz del repositorio para que los archivos se guarden en las rutas siguientes.

- `resultados/graficas/` contiene las figuras en PNG.
- `resultados/metricas/` contiene los barridos y el resumen de los experimentos.
- `resultados/tablas/` contiene las tablas consolidadas.

## Informe

[Informe_Actividad_04.pdf](Informe_Actividad_04.pdf) es el archivo de entrega. El fuente [main.tex](main.tex) reutiliza el PDF base en `compilacion/` y permite editar el apartado del enlace. Para generar una copia con LaTeX, ejecuta `tectonic --outdir compilacion main.tex` desde la raíz. El archivo de entrega conserva además la navegación interna del informe original.
