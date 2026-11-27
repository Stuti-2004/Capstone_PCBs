# Initial Load Cell Circuit

KiCad project for the capstone load cell PCB. The design is split into hierarchical sheets, one per subsystem.

## Opening the project

1. Install [KiCad](https://www.kicad.org/download/) (version 10 or newer).
2. Clone this repository, or download it as a ZIP.
3. Open `Initial_LoadCell_Circuit.kicad_pro` in KiCad.

## Files

| File | Contents |
|------|----------|
| `Initial_LoadCell_Circuit.kicad_pro` | Project file (open this one) |
| `Initial_LoadCell_Circuit.kicad_sch` | Top-level schematic that links the subsystem sheets |
| `Initial_LoadCell_Circuit.kicad_pcb` | PCB layout |
| `Load Cells.kicad_sch` | Load cell inputs and signal conditioning |
| `Power.kicad_sch` | Power supply and regulation |
| `nRF_Module.kicad_sch` | nRF wireless microcontroller module |
| `Display, RTC, thermistor.kicad_sch` | Display, real-time clock and temperature sensing |
| `Initial_LoadCell_Circuit.kicad_prl` | Local view settings (not part of the design) |
