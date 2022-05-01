# Cuadernillo de Elementos de Programación y Lógica

## Universidad Nacional de Quilmes
### Licenciatura en Informática - Tecnicatura Universitaria en Programación Informática - Bioinformática

Este cuadernillo tiene por intención complementar las clases teóricas
de los y las estudiantes de las carreras Licenciatura en Informática, Tecnicatura Universitaria en Programación Informática y Bioinformática
de la Universidad Nacional de Quilmes, en el transcurso de sus clases en
la materia de Ciclo Introductorio Elementos de Programación y Lógica.

El contenido se encuentra distribuido bajo una licencia CC-BY-NC-SA.

Si encuentra errores en el contenido, faltas de ortografía u otros,
por favor repórtelos como un _issue_ en el repositorio de GitHub del
proyecto en [https://github.com/alanrodas/epyl-cuadernillo/issues](https://github.com/alanrodas/epyl-cuadernillo/issues)

### Versionado

La versión actual es la **0.6.0**.

La versión sigue un esquema major.minor.revision.

* major permanecerá en cero hasta que se considere que el libro ha alcanzado un estado de madurez suficiente como para ser el material de estudio principal de la materia.
* minor se incrementará de momento cada vez que haya cambios sustanciales a los contenidos del cuadernillo.
* revision se incrementa cuando hay cambios menores al contenido, como
correcciones ortográficas o gramaticales.

### Requerimientos

Este documento se encuentra escrito en LaTeX y debería poder ser compilado
por cualquier distribución completa de [LaTeX](https://www.latex-project.org/get/).

El proyecto se compila utilizando [Arara](https://github.com/cereda/arara).

Para el desarrollo se utiliza [Visual Studio Code](https://code.visualstudio.com) con la extensión [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)

### Compilando el documento

Utilizando Arara:

```
arara cuadernillo
```

Ante algún error puede correr el comando en modo _verbose_ para obtener más
información:

```sh
arara cuadernillo -v
```