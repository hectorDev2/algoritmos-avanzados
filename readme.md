
# Comparación de Algoritmos para Caminos Más Cortos

Este repositorio contiene el código, experimentos y documentación del proyecto:

**"Comparación de Algoritmos para Caminos Más Cortos: Dijkstra vs. Nuevos Avances en Complejidad Subóptima"**

Autores: Pamela Diaz, Esmaydes Ccori, Hector Barazorda  
Universidad Nacional de San Antonio Abad del Cusco

---

## Resumen
El objetivo de este proyecto es evaluar y comparar el rendimiento práctico de los algoritmos de búsqueda de caminos más cortos (Dijkstra, Bellman-Ford, BFS y A*) en grafos de topología diversa y tamaño moderado, para determinar cuál ofrece el mejor equilibrio entre eficiencia computacional y facilidad de implementación en escenarios reales.

El trabajo surge a raíz de los recientes avances teóricos que han superado la barrera de complejidad clásica de Dijkstra, y busca contrastar estos desarrollos con la eficiencia de los algoritmos tradicionales en aplicaciones prácticas.

## Motivación
Aunque Dijkstra, Bellman-Ford y A* son ampliamente utilizados, existe poca evidencia experimental comparativa sobre su rendimiento real en diferentes tipos de grafos representativos de aplicaciones reales. Además, los nuevos algoritmos que prometen mejoras asintóticas no han sido suficientemente evaluados en implementaciones prácticas.

## Problema de investigación
¿Cuál de los algoritmos Dijkstra, Bellman-Ford, BFS y A* ofrece el mejor rendimiento práctico en diferentes tipos de grafos, y bajo qué condiciones cada uno resulta verdaderamente eficiente?

## Objetivos
- Implementar y comparar los algoritmos clásicos de caminos más cortos en Python usando NetworkX.
- Medir tiempo de ejecución, consumo de memoria y corrección en grafos sociales, geográficos y aleatorios.
- Analizar la influencia de la estructura del grafo y la heurística en el desempeño de cada algoritmo.
- Contrastar la eficiencia empírica de los algoritmos clásicos frente a las expectativas teóricas y los avances recientes.

## Alcance y limitaciones
- Se consideran grafos de hasta 50,000 nodos y 200,000 aristas.
- Solo se implementan algoritmos clásicos y heurísticas estándar.
- El estudio se realiza en Python y hardware personal.
- No se incluyen optimizaciones avanzadas ni grafos dinámicos.

## Estructura del proyecto
- **colab/**: Notebooks de experimentación (por ejemplo, `experimentacion.ipynb`).
- **paper/**: Artículos, reportes y documentación científica.
- **readme.md**: Descripción general y guía del proyecto.

## Cómo contribuir
1. Realiza un fork del repositorio.
2. Crea una rama para tu funcionalidad o experimento.
3. Haz tus cambios y realiza un pull request.

## Contacto
Para dudas o sugerencias, contacta a los autores a través de sus correos institucionales.
