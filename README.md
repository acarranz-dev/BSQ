# BSQ

**Finding the biggest square without obstacles in a map: the final project of the 42 Piscine.**

**English** · [Català](README.ca.md) · [Español](README.es.md)

`Part of the 42 Barcelona Common Core` · `Rank Piscine` · `C`

---

## Description

BSQ ("Biggest SQuare") is the last project of the Piscine, the selection month before the Common Core. The program reads a map made of empty cells and obstacles and draws the largest possible square that does not touch any obstacle.

## What it teaches

- Reading a file and storing it in a 2D array.
- Searching a grid efficiently and handling the edge cases.
- Working in a team under time pressure.

## How it works

For each cell of the map, the program tries to grow a square from that position, one size at a time, until it finds an obstacle. It keeps the biggest square found (its size and its top-left corner) and finally fills it with a marker character.

This is an early Piscine version that works on a fixed-size grid. `matrix_explicacion.txt` describes every variable and function in detail.

## Build and run

```bash
git clone https://github.com/acarranz-dev/BSQ.git
cd BSQ
cc main.c -o bsq
./bsq
```

## Project structure

```
BSQ/
├── main.c, matrix.c, matrix2.c, array.c   # search and drawing of the square
├── map.txt, bsq_maps/                      # example maps
├── generator                               # map generator
└── matrix_explicacion.txt                  # explanation of the variables and functions (Spanish)
```

---

[More projects on my profile](https://github.com/acarranz-dev)
