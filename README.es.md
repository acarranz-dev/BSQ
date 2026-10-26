# BSQ

**Encontrar el cuadrado más grande sin obstáculos en un mapa: el proyecto final de la Piscina de 42.**

[English](README.md) · [Català](README.ca.md) · **Español**

`Parte del Common Core de 42 Barcelona` · `Rango Piscine` · `C`

---

## Descripción

BSQ ("Biggest SQuare") es el último proyecto de la Piscina, el mes de selección antes del Common Core. El programa lee un mapa con casillas vacías y obstáculos y dibuja el cuadrado más grande posible que no toque ningún obstáculo.

## Qué enseña

- Leer un fichero y guardarlo en una matriz 2D.
- Recorrer una cuadrícula de forma eficiente y tratar los casos límite.
- Trabajar en equipo con poco tiempo.

## Cómo funciona

Para cada casilla del mapa, el programa intenta hacer crecer un cuadrado desde esa posición, un tamaño cada vez, hasta que encuentra un obstáculo. Guarda el cuadrado más grande encontrado (el tamaño y la esquina superior izquierda) y al final lo rellena con un carácter marcador.

Es una versión inicial de la Piscina que trabaja sobre una cuadrícula de tamaño fijo. `matrix_explicacion.txt` describe en detalle cada variable y función.

## Compilar y ejecutar

```bash
git clone https://github.com/acarranz-dev/BSQ.git
cd BSQ
cc main.c -o bsq
./bsq
```

## Estructura del proyecto

```
BSQ/
├── main.c, matrix.c, matrix2.c, array.c   # search and drawing of the square
├── map.txt, bsq_maps/                      # example maps
├── generator                               # map generator
└── matrix_explicacion.txt                  # explanation of the variables and functions (Spanish)
```

---

[Más proyectos en mi perfil](https://github.com/acarranz-dev)
