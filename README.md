# bucker.io


[![state: en desarrollo](https://img.shields.io/badge/state-en%20desarrollo-yellow)](README.md)

![Logo bucker.io](assets/logo.png)

Repo para el hackatón de IV 2025-26

## TL;DR

bucker.io es una herramienta que mejora la gestión y facilita la búsqueda de elementos de la bibliografía de las asignaturas de la universidad de Granada. Estudiantes, bibliotecarios y otros usuarios de la universidad podrán ahorrar tiempo, facilitando el acceso a los recursos académicos.

## Formulación del problema

**Cliente**: Estudiante de Ingeniería, Ciencias o Humanidades de la Universidad de Granada.

**Contexto**: Con el objetivo de superar con éxito las asignaturas de su grado, los estudiantes deben consultar la bibliografía recomendada. Esta se divide en fundamental y complementaria y está disponible en un apartado de la guía docente de cada asignatura (en PDF y en versión web).

Dado que quieren minimizar su tiempo y coste empleado en lo relativo a los libros, los estudiantes se encuentran con los siguientes problemas:

* **Identificación de ejemplares**: El estudiante quiere poder identificar de forma inequívoca los ejemplares para comprarlos o tomarlos en préstamo.
* **Verificación de disponibilidad**: El estudiante quiere saber cuando está disponible un libro en la biblioteca de la universidad. Está acostumbrado a localizarlo mediante un enlace al catálogo de la biblioteca.
* **Distinción de la bibliografía esencial**: El exceso de bibliografía (incluso fundamental) supone un problema para la gestión del tiempo de estudio del cliente o incluso un problema económico si es necesario comprar algunos libros.
* **Libros en diferentes idiomas**: Una bibliografía que contiene libros cuyo idioma no entienden los estudiantes dificulta la búsqueda de información para la asignatura.

En la [Guía Docente](https://www.ugr.es/estudiantes/grados/grado-ingenieria-informatica/computacubicua-inteligambiental-etecnolinf/guia-docente) de la asignatura de Computación Ubicua e Inteligencia Ambiental del Grado en Informática, notamos como:

- Toda la bibliografía está en inglés.
- 2 de los 6 libros recomendados (Pervasive systems and ubiquitous computing y Ambient Intelligence) no están disponibles en la biblioteca de la universidad.
- En particular, el primer libro tiene un precio de 138€.

## Decisiones sobre la arquitectura (ADR)
Pueden consultarse los Architecture Decision Record en la [Wiki](https://github.com/JJ/bucker.io/wiki). Existe una [Plantilla para la creción de ADR](https://github.com/JJ/bucker.io/wiki/PLANTILLA-PARA-LOS-%E2%80%90--%5BADR%5D-Architecture-Decision-Record.) que debe ser estándar para la creación de otros nuevos.
