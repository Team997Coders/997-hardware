# 997-Hardware
Repository for FRC 997's custom PCB projects, made in KiCad.

Documentation for each project can be found in their individual directories.

### Installation
This project uses `kicad-cli` and `pcbdraw` in its commit hook script. `kicad-cli` is distributed with the broader KiCad package, and `pcbdraw` can be installed using [these instructions](https://github.com/yaqwsx/PcbDraw/blob/master/doc/installation.md).[^1]

### Licensing
Hardware source files licensed under the GPL v3.0. Some redistributed files may be under different licenses.

[^1]: `pcbdraw` depends on the `mistune` library. `pcbdraw` version 1.1.2 does not depend on the correct version of `mistune` and for some users manually running `pip install mistune==2.0.5` may be required.