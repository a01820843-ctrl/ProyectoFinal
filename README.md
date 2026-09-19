# Proyecto final: Pacman

Proyecto de Semana Tec basado en Pacman de la biblioteca `freegames`. El juego se ejecuta con Python y dibuja el tablero mediante `turtle`. El objetivo es recoger el alimento sin tocar a los fantasmas.

## Integrantes y aportaciones

- Víctor Joel Cortés Sánchez — A01820843: modificó la velocidad de los fantasmas.
- Santiago Manzano Doniz — A01715488: modificó los pasillos del tablero y cambió el alimento a rombos naranjas.

## Cómo ejecutar el juego

Se necesita Python con soporte para `turtle` y la biblioteca `freegames`. Desde la carpeta del proyecto:

```bash
python3 -m pip install freegames
python3 pacman.py
```

Usa las flechas del teclado para mover a Pacman.

## Cambios realizados

1. **Versión original:** se guardó una copia del juego en `originales/A01715488_pacman.py` antes de modificar el tablero y el alimento.
2. **Tablero:** se cambiaron celdas de pared a pasillo en la lista `tiles`, creando nuevas rutas transitables.
3. **Alimento:** se agregó una función que dibuja rombos naranjas en las casillas con alimento. Recogerlos sigue aumentando la puntuación.
4. **Fantasmas:** se incrementó su velocidad de movimiento.

## Proceso y verificación

Cada modificación se registró en un commit individual en la rama correspondiente. Se comprobó que `pacman.py` compila y que el juego abre con el tablero modificado, los rombos naranjas y los fantasmas en movimiento.
