# cub3D

A raycasting engine in C, in the style of Wolfenstein 3D. Reads a `.cub` map
describing walls, textures and the player start, then renders a first-person view
with MiniLibX. This is the solo version. A 42 Abu Dhabi project.

## Build

```
make        # builds MiniLibX first, then cub3D
make libx   # MiniLibX only
make norm   # norminette check
```

## Run

```
./cub3D maps/map1.cub
```

## Notes

- Built with `-Wall -Wextra -Werror`.
- MiniLibX and zlib are vendored under `minilibx/` and `zlibc/`; no system install
  of either is needed.
- `en.subject.pdf` is the original assignment.
- A version built with teammates lives in
  [unc-cub3d](https://github.com/myousaf64/unc-cub3d).
