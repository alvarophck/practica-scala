# Práctica de programación básica con Scala

## Autor

Nombre y apellidos: Álvaro García-Quismondo Lizana

## Entorno

- Sistema operativo: Windows 11
- Scala: 2.12.20 *(ver nota sobre la versión más abajo)*
- Java: JDK 17

> **Nota sobre la versión de Scala**: el enunciado pedía Scala 2.12.21 en las tres partes de la práctica. Sin embargo, ni Almond (kernel de Scala para Jupyter) ni el resto de herramientas usadas tienen publicado un compilador/kernel compilado para esa versión exacta en Maven Central; la versión más reciente disponible es la 2.12.20, que es la que se ha usado de forma consistente en toda la práctica. La evidencia de este problema (capturas del error de resolución de dependencias) está documentada en `parte1/entorno1-jupyterlab.md`.

## Estructura del repositorio

```
practica-scala/
│
├── README.md                    (este archivo)
│
├── parte1/                      Entornos de trabajo
│   ├── images/
│   └── parte1/
│       ├── entorno1-jupyterlab.md
│       ├── entorno2-vscode.md
│       ├── entorno3-intellij.md
│       ├── notebook/
│       │   └── entorno-scala.ipynb
│       ├── vscode/
│       └── intellij/
│
├── parte2/                      Ejercicios de programación en JupyterLab
│   ├── parte2-readme.md
│   ├── parte2-scala.ipynb
│   └── images/
│
└── parte3/                      Mini proyectos
    ├── parte3-readme.md
    ├── parte3-1-vscode/
    │   ├── parte3-1-readme.md
    │   ├── images/
    │   └── torneo-twenty-one/
    └── parte3-2-intellij/
        ├── parte3-2-readme.md
        ├── images/
        └── analizador-notas/
```

## Parte 1 — Entornos de trabajo

Preparación de tres entornos de desarrollo distintos para trabajar con Scala 2.12 y JDK 17:

- **Entorno 1**: JupyterLab + Almond Kernel → [Ver documentación](./parte1/parte1/entorno1-jupyterlab.md)
- **Entorno 2**: Visual Studio Code + Metals + sbt → [Ver documentación](./parte1/parte1/entorno2-vscode.md)
- **Entorno 3**: IntelliJ IDEA Community + sbt → [Ver documentación](./parte1/parte1/entorno3-intellij.md)

## Parte 2 — Programación con Scala

15 ejercicios de programación básica (variables, tipos, funciones, arrays, listas, estructuras de control, mutabilidad/inmutabilidad, estilo imperativo/funcional) resueltos en un notebook de JupyterLab con Almond.

Ver [Parte 2](./parte2/parte2-readme.md)

## Parte 3 — Mini proyectos

Dos mini proyectos que integran los conceptos trabajados en las partes anteriores:

- **Parte 3.1**: Clasificador de resultados de un torneo de Twenty-One (Visual Studio Code + Metals + sbt)
- **Parte 3.2**: Analizador de calificaciones de un grupo (IntelliJ IDEA + sbt)

Ver [Parte 3](./parte3/parte3-readme.md)
