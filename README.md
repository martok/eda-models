# EDA Models
EDA/ECAD models, symbols, footprints etc.

## LTSpice

### How to add

Go to `Control Panel -> Sym. & Lib Search paths`, add the `LTSpice` subdirectory of this repo. Don't forget to restart LTSpice.

### List

 - `HIP4081A` (source: Intusoft Spice?)

   This model has a buggy HDEL.

 - `ilim` (source: own)

   Configurable current limiter (numerically much more stable than simple switch/diode models)

## KiCad

### How to add

Go to `Preferences -> Manage Symbol/Footprint Libraries`, add the `*.kicad_sym` files or `*.pretty` directories of the `KiCad` subdirectory of this repo.

### Symbols

 - `3.0SMCJ11A`

   Littelfuse 3.0SMCJ - Surface Mount - 3000W - DO-214AB - Vrm 11

 - `APV1121`

   Panasonic Photovoltaic Isolator / MOSFET driver

 - `SMA6J11A-Q`

   Littelfuse SMA6J-Q Transient Voltage Suppressor Diode Series, 11Vrwm, DO-214AC


### Footprints

 - `DBHD15M_CI_A`

   D-SUB 15-pin HD Male connector, mounted on the side of the PCB

 - `PADS_02_L`

   2 large pads

 - `Tab_250_2P_Vert`

   Faston .250" (6.35mm) series Tab, vertical, 2 pads

 - `TO-220-3_Horizontal_TabUp_NoDrill`

   TO-220-3, Horizontal, RM 2.54mm, upside down with no mounting hole
