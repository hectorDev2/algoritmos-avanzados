# Notebooks de Experimentación (`colab/`)

Este directorio contiene los notebooks utilizados para la experimentación y análisis empírico del proyecto **"Comparación de Algoritmos para Caminos Más Cortos: Dijkstra vs. Nuevos Avances en Complejidad Subóptima"**.

## ¿Qué encontrarás aquí?

- **experimentacion.ipynb**: Notebook principal donde se implementan, ejecutan y visualizan los experimentos comparativos entre algoritmos clásicos de caminos más cortos (Dijkstra, Bellman-Ford, BFS, A*), siguiendo la metodología descrita en el paper.

## Descripción del notebook principal

El notebook está estructurado en las siguientes secciones:

1. **Importación de librerías y configuración**: Se cargan las dependencias necesarias (NetworkX, pandas, numpy, matplotlib, etc.) y se fija la semilla para garantizar reproducibilidad.
2. **Generación de datasets**: Se crean grafos de prueba representativos de tres categorías:
	- Redes sociales reales (Karate Club, Familias Florentinas, Davis Southern Women)
	- Mapas sintéticos con coordenadas (grilla 2D, grafo geométrico)
	- Grafos aleatorios sintéticos (Erdős-Rényi, Barabási-Albert, Watts-Strogatz)
3. **Implementación y ejecución de algoritmos**: Se ejecutan Dijkstra, Bellman-Ford, BFS y A* (cuando aplica), midiendo tiempo de ejecución y uso de memoria para cada dataset y algoritmo.
4. **Visualización y análisis de resultados**: Se presentan tablas y gráficos comparativos (barras, escalabilidad, impacto de heurística) para analizar el rendimiento y validar hipótesis del estudio.
5. **Casos especiales y robustez**: Se exploran escenarios con pesos negativos y ciclos negativos para mostrar limitaciones y diferencias prácticas entre algoritmos.

## Requisitos

- Python 3.10+
- Jupyter Notebook o JupyterLab
- networkx
- pandas
- numpy
- matplotlib

Instala los requisitos con:

```
pip install networkx pandas numpy matplotlib
```

## ¿Cómo usar este notebook?

1. Abre `experimentacion.ipynb` en Jupyter Notebook o JupyterLab.
2. Ejecuta las celdas en orden para reproducir los experimentos y visualizar los resultados.
3. Puedes modificar los parámetros de los grafos o el número de repeticiones para explorar otros escenarios.

## Notas y recomendaciones

- Los experimentos usan semillas fijas para garantizar resultados reproducibles.
- Los resultados pueden variar ligeramente según el hardware y la carga del sistema.
- Se recomienda ejecutar los notebooks en un entorno virtual limpio para evitar conflictos de dependencias.
- El código está documentado y alineado con la metodología del paper, facilitando su extensión o adaptación a nuevos algoritmos o datasets.

---

Para más detalles sobre la metodología, hipótesis y objetivos, consulta el README principal del repositorio y el paper en la carpeta `paper/`.
