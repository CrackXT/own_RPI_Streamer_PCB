# Own_RPI_Streamer_PCB

PCB files for RPI Streamer Board

# Description

This is a main board to hold a Raspberry Pi (4) and the Hifyberry Digi2 Pro expansion board. This puts the connections I need (for me) on one side to be able to build my own streamer.

Part 1 of 2, part 2 is Own_RPI_Expansion_PCB.

The internal "power supply" (Pololu S13V30F5) delivers at 5V@3A, sensor and RGB are powered by part 2.

There is a temperature sensor (Sensirion SHT45) and an unregulated fan connector (e.g. Noctua NF-A4x20 5V) under the SoC. In addition there is the possibility to connect a lighting (RGB). Furthermore, the following connections are available... USB-C (power supply), USB-A 3.0 (data, e.g. USB stick with music on it), main switch, QWIIC/StemmaQT (sensor) and an external 5V connector (for part 2).

The board can be produced here (AISLER) with the files (.brd and .sch) or by any other PCB manufacturer. -> https://aisler.net/

# Spec

Vin: 2.8 - 22V<br>
Vout: 5V (typ., min.4,85V, max.5,15V)<br>
Iout: 3A<br>

# Serie

- .pro

# Layout

Top<br>
![Streamer_Top_v1 1](https://github.com/CrackXT/Own_RPI_Streamer_PCB/assets/88975406/b6cbf77f-dbc7-4fc6-ba29-6b3af89b0ecb)

Bottom<br>
![Streamer_Bottom_v1 1](https://github.com/CrackXT/Own_RPI_Streamer_PCB/assets/88975406/e4b04f24-24f0-4713-af31-c0d38cac4d87)

Routing/Dimensions(mm)<br>
![Streamer_v1 1](https://github.com/CrackXT/Own_RPI_Streamer_PCB/assets/88975406/2f41a6f8-b1bd-456d-a5b8-0f88906af48a)

Schematic<br>
Schematic as .pdf at the top of the page.

# License

Open hardware, use it, mod it, whatever you want, feel free...

# Thanks!

Own design and layout.

# Version - Build

v1.1 - 09.07.2023
