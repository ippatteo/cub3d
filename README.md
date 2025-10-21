# cub3D

## Project Overview

The main objective of the cub3D project is to create a "realistic" 3D graphical representation of a maze's interior from a first-person perspective, inspired by Wolfenstein 3D.

This is achieved using ray-casting principles, which simulate the way rays of light interact with walls to render a 3D environment from a 2D map. The ray-casting algorithm in this project was entirely implemented by me.

## Key Features
- **Ray-casting engine**: Calculates wall distances and renders the maze in real time.
- **First-person perspective**: Navigate the maze as if you are inside it.
- **MiniLibX graphics**: Handles window creation, colors, and user events (keyboard, mouse).
- **Custom maps**: Easily add and test different maze layouts.
- **Modular code**: Organized into assets, ray, src, lib, and maps folders for clarity and maintainability.

## Learning Goals
- C programming and memory management
- Basic algorithms and data structures
- Graphics programming (window, colors, events)
- Using the miniLibX library

## How to Build

From the project root:
```sh
make
```

## How to Run

```sh
./cub3d maps/map1.cub
```
Replace `map1.cub` with any map file in the `maps/` directory.

## Directory Structure
- `cub3d.c` : Main entry point
- `assets/` : Sprites and textures
- `include/` : Header files
- `lib/` : Custom libraries (libft, ft_printf, get_next_line)
- `maps/` : Example map files
- `mlx_linux/` : MiniLibX library
- `ray/` : Ray-casting logic
- `src/` : Game logic and utilities

## Credits
- Ray-casting engine: fully implemented by me
- Project inspired by Wolfenstein 3D
- Developed for 42 school

---
For more details, see the source code and comments in each module.