# World-View
World View is a wall-mounted LED map built from one controller and 45 identical display tiles.

## Hardware (KiCad 10)

- [Controller project](hardware/controller/WorldView%20Controller.kicad_pro): Pico W, rotary encoder inputs, and five buffered row outputs.
- [Tile project](hardware/tile/WorldView%20Tile.kicad_pro): one 8 × 8 LED board, repeated nine times per row across five rows.
- [Shared symbols](hardware/shared/MapParts.kicad_sym): the project-local library used by both projects.

Open the `.kicad_pro` for the board you want, then launch its schematic or PCB editor from the KiCad project manager.
