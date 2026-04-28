# so_long (École 42)

[English](#english) · [Español](#español)

---

## English

Implementation of the **so_long** project in C as part of the **École 42** curriculum.
The goal is to build a **simple 2D game** using **MiniLibX**, practicing event handling, sprite rendering, map parsing, and game state management.

### Features

- Map loading and validation (`.ber`)
- 2D rendering with **MiniLibX**
- Player movement via keyboard
- Move counter
- Collectibles, exit, and enemies (if applicable in your version/bonus)
- Clean window close and proper resource cleanup

### Requirements

- Linux / macOS
- `make`
- C compiler (gcc/clang)
- **MiniLibX** (depending on your campus version)

### Build

```bash
make
```

Run:

```bash
./so_long maps/map.ber
```

### Map format (.ber)

- `1` walls
- `0` empty space
- `P` player
- `C` collectible
- `E` exit
- `X` enemy (bonus, if present)

Typical rules:

- Map must be rectangular
- Must be surrounded by walls
- Must contain at least 1 `P`, 1 `E`, and 1 `C`
- There must be a valid path to collect everything and reach `E`

### Project structure

> Adjust based on your repository

- `src/` source code
- `includes/` headers
- `maps/` sample maps
- `textures/` sprites / assets
- `Makefile`

---

## Español

Implementación del proyecto **so_long** en C como parte del currículo de **École 42**.
El objetivo es desarrollar un **juego 2D simple** utilizando **MiniLibX**, practicando manejo de eventos, renderizado de sprites, parsing de mapas y control del estado del juego.

### Features

- Lectura y validación de mapas (`.ber`)
- Renderizado 2D con **MiniLibX**
- Movimiento del jugador con teclado
- Conteo de movimientos
- Coleccionables, salida y enemigos (si aplica en tu versión/bonus)
- Cierre limpio de la ventana y liberación de recursos

### Requisitos

- Linux / macOS
- `make`
- Compilador C (gcc/clang)
- **MiniLibX** (según la versión de tu campus)

### Instalación / Build

```bash
make
```

Ejecutar:

```bash
./so_long maps/map.ber
```

### Formato del mapa (.ber)

- `1` paredes
- `0` espacio vacío
- `P` jugador
- `C` coleccionable
- `E` salida
- `X` enemigo (bonus, si existe)

Reglas típicas:

- El mapa debe ser rectangular
- Debe estar cerrado por paredes
- Debe contener al menos 1 `P`, 1 `E` y 1 `C`
- Debe existir un camino válido para recolectar todo y llegar a `E`

### Estructura del proyecto

> Ajustar según tu repo

- `src/` código fuente
- `includes/` headers
- `maps/` mapas de ejemplo
- `textures/` sprites / assets
- `Makefile`

## Author

- brturcio (École 42)
