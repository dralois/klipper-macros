# klipper-macros
A collection of g-code macros for use with Klipper on.
Most macros should be re-useable for any 3d printer running klipper but it's best to check for compatibility.

Added in printer.cfg using:

```
[include macros/print/*.cfg]
[include macros/mappings/*.cfg]
[include macros/calibration/*.cfg]

[idle_timeout]
gcode:
  _IDLE_TIMEOUT
```
