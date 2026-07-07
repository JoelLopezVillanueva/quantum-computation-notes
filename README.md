# Computación e Información Cuántica

Este repositorio contiene mi espacio de trabajo, apuntes teóricos y cuadernos de desarrollo práctico en computación cuántica. El proyecto se encuentra en desarrollo activo y se irá completando de forma progresiva a lo largo del curso.

## Estructura y Contenido

### 1. Apuntes Teóricos (LaTeX)
Notas de clase maquetadas en LaTeX basadas en los siguientes programas académicos:
* Undergraduate Quantum Computation** (Carnegie Mellon University) – Prof. Ryan O'Donnell. Enfoque en informática teórica, complejidad computacional y análisis matemático de algoritmos.


### 2. Cuadernos de Laboratorio (Jupyter Notebooks)
Implementaciones prácticas en Python y notas de desarrollo basadas en literatura científica de optimización y aprendizaje automático cuántico (QML):
* **Optimización Cuántica (QUBO/Ising):** Formulación matemática y resolución de problemas NP-difíciles (Max-Cut, Mochila, Coloreado de grafos, TSP) mediante el modelo de Ising. Pruebas con simuladores locales de recocido cuántico (*quantum annealing*).
* **Quantum Machine Learning (QML):** Transición de arquitecturas de redes neuronales clásicas (TensorFlow/Keras) hacia modelos híbridos y de aprendizaje cuántico supervisado (CQ).

## Organización del Repositorio

* `/LaTeX/` - Archivos fuente `.tex` de los apuntes de clase.
* `/PDFs/` - Documentos finales ya compilados listos para lectura.
* `/Notebooks/` - Cuadernos de Jupyter con las simulaciones de optimización y QML.
* `/TikZ/` - Código fuente de los esquemas y circuitos cuánticos vectoriales.

## Tecnologías y Librerías

* **Redacción:** LaTeX (paquetes `amsmath`, `amssymb`, `physics`, `tikz`).
* **Computación Cuántica:** Python (Miniconda) con `pennylane`, `qiskit`, `pennylane-qiskit`, `dimod` y `dwave-neal`.
