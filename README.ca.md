# BSQ

**Trobar el quadrat més gran sense obstacles en un mapa: el projecte final de la Piscina de 42.**

[English](README.md) · **Català** · [Español](README.es.md)

`Part del Common Core de 42 Barcelona` · `Rang Piscine` · `C`

---

## Descripció

BSQ ("Biggest SQuare") és l'últim projecte de la Piscina, el mes de selecció abans del Common Core. El programa llegeix un mapa amb caselles buides i obstacles i dibuixa el quadrat més gran possible que no toqui cap obstacle.

## Què ensenya

- Llegir un fitxer i guardar-lo en una matriu 2D.
- Recórrer una graella de manera eficient i tractar els casos límit.
- Treballar en equip amb poc temps.

## Com funciona

Per a cada casella del mapa, el programa intenta fer créixer un quadrat des d'aquella posició, una mida cada vegada, fins que troba un obstacle. Guarda el quadrat més gran trobat (la mida i la cantonada superior esquerra) i al final l'omple amb un caràcter marcador.

És una versió inicial de la Piscina que treballa sobre una graella de mida fixa. `matrix_explicacion.txt` descriu en detall cada variable i funció.

## Compilar i executar

```bash
git clone https://github.com/acarranz-dev/BSQ.git
cd BSQ
cc main.c -o bsq
./bsq
```

## Estructura del projecte

```
BSQ/
├── main.c, matrix.c, matrix2.c, array.c   # search and drawing of the square
├── map.txt, bsq_maps/                      # example maps
├── generator                               # map generator
└── matrix_explicacion.txt                  # explanation of the variables and functions (Spanish)
```

---

[Més projectes al meu perfil](https://github.com/acarranz-dev)
