# KlipperTinyRed
This is the repo that started as a place for backing up my configs for Klipper Voron V0.2. It has now become config, and build information repository.  

## About the TinyRed Build

TinyRed is a Voron V0.2.  It's a hybrid printer in the sense that it started out as a kit, but then had most parts replaced with 'upgrades'. So not a kit, but not a complete self source either.  You could find find a listing of high level parts and sourcing notes under the "High Level BOM" section below.  

![Picture of TinyRed](images/IMG_2201.heic)

### Mods
For the most part this v0.2 is not heavily modded.  There is a nevermore filter add on.  I also created my own PCB mount, as I did not like the cable restraint on the existing mounts.  You could find links to any of the mods for this printer here: 

[Picobilical PCB Mount with cable restraint](https://www.printables.com/model/1068141-ldo-v02-picobilical-umbilical-pcb-mount-remix)

[Nano Nevermore](https://www.printables.com/model/500513-voron-v0-tiny-recirculating-carbon-filter-mfnano-r)

[CNC parts](https://www.siboor.com/product/siboor-voron-0-2-aug2023-updated-version-metal-structural-part/)

[Mini-Fridge Door](https://github.com/TheVoronModder/MiniFridge)

[Aux Parts Fan](https://www.siboor.com/product/voron-0-2-12032-parts-fan/)

[Waveshare 2.8 inch DSI Screen](https://www.waveshare.com/2.8inch-dsi-lcd.htm)

### High Level BOM 

| Part    | Brand  | Info  | Sourced From  | Notes  |
| -------- | ------- | ------- | ------- | ------- |
| Heater Bed  | LDO    | LDO polyimide heater and power supply upgrade | Fabreeko | - |
| Build Plate | Honeybadger | dual carbon fiber & P series PEI build plate | Fabreeko | Recently destroyed due to homing error |
| Wiring | LDO | LDO V0.1 Cable kit | Fabreeko | v0.1 and v0.2 have similar wiring requirements |
| Gantry Components | Honeybadger | Honeybadger CNC toolhead carriage | Fabreeko | MGN7 version |
| Gantry Components | LDO | LDO t nut bar set for the rails | Fabreeko | - |
| Electronics | - | V0.1 AC power inlet | Fabreeko | - |
| Tool Head | Honeybadger | 3010 axial and 3010 blower fans | Fabreeko | - |
| Tool Head (HotEnd) | E3D | Revo Voron heatsink | Fabreeko | - |
| Tool Head (HotEnd) | E3D | Revo 0.4 High Flow Nozzle | Filastruder | - |
| Hardware | West3D | Black Stainless Steel Fastener kit | West3D | - |
| Motion | Berserker | MGN7H-150 rails x5 | West3D | The X rail is a little wobbly.  I am going to try and regrease, but I also ordered a couple rails in case i need to replace it. |
| Frame | LDO | LDO V0.2 red frame kit | West3D | - |
| Panels | - | Black ABS Panels - Bottom, Back plates | West3D | - |
| Cooling | GDSTime | 12032 blower fan | West3D | This is for aux fan, which I have not used, as I have not used this machine to print PLA yet. ha. |
| Frame | LDO | Mini-Fridge Click-Clack door - Red | West3D | Love this! |
| Frame | Fysect | V0 1-piece bed frame - Heavy AF edition | West3D | this thing is solid, more rigid then Kirigami, but unfotnately you cant really mount anything to it. |
| - | - | - | West3D | - |
| Panels | KB3D | Darkmode Acrylic panel kit | KB3D | - |
| Panels | KB3D | Darkmode Acrylic panel kit - top hat | KB3D | - |
| Electronics | LDO | LDO Picobillical kit | Amazon | - |
| Electronics | Waveshare | Waveshare | Amazon | KlipperScreen |
| Electronics | - | Matchstick RGB lights | Amazon | - |
| Electronics | LDO | 2pin JST splitter | Amazon | For modded nevermore filter for easy disconnect. |
| Frame | - | Rubber feet | Amazon | - |
| Motion | Moons | X and Y steppers | Formbot | MS14HS5P4150-11 |
| Motion | Moons | Z, stepper | Formbot | LE174S-T0808-200-0-S-065 |
| Electronics | Biqu | BTT Pico | Formbot | - |
| Motion | - | Z cable chain | Formbot | - |
| Motion | - | PTFE tubing | Formbot | - |
| Electronics | Raspberry Pi | Raspberry Pi 4B | Microcenter | - |
| Motion | - | Bearings for motion | - | Unknown, might be from formbot |
| Gantry Components | Siboor | CNC V0 kit | AliExpress | Seem to be missing a piece or two from the kit, but mostly there.  |
| Gantry Components | Fysect | Lightened X gantry | - | - |
| Motion | - | Belts | TH3D | - |
| Tool Head | LDO | Nema 14 Pancake Motor for extruder | - | Extruder motor is from the Orbiter v2 extruder.  TODO: Add model number |
| Panels | Send Cut Send | Custom cut back electronics panel, in ABS. | Send Cut Send | - |
| - | - | PSU | - | TODO: Find out what PSU this thing has in it. |
| - | - | - | - | - |