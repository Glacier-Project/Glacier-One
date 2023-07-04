# T0 Rev. 2
This folder contains schematic & PCB layout files for the Glacier One T0, Revision 2. The files are below:

## File Descriptions
- `Gerber_PCB_glacierone.zip`: Gerber files, for submitting to a PCB fabrication company.
- `PCB_PCB_glacierone_2023-07-03.json`: PCB layout file in EasyEDA format.
- `SCH_glacierone_2023-07-03.json`: Schematic file in EasyEDA format.
- `Schematic_glacierone_2023-07-03.pdf`: PDF schematics.

## Peripherals
This revision expects for external peripherals to be added for the device to function. They are listed below:
- Waveshare RP2040 Plus 4MB - This is to be soldered with the included pin header to the "PI_L" and "PI_R" headers. The USB-C port should be facing the top of the board.
- Nokia 5110 LCD w/ board - This is to be soldered with a pin header to the "DISPLAY" header. Pin 1 goes on the far left. Use the bottom pin header on the board.
- Waveshare SIM7600X 4G HAT - This (or a similar SIM* series board) is to be connected with jumper wires to the "CELLULAR" header. The "3.3v" pin is to be connected to "3V3" on the external board. The "RX" pin is to be connected to "TXD" on the external board. The "TX" pin is to be connected to "RXD" on the external board. The "GND" pin is to be connected to the "GND" pin on the external board. The external board will require additional USB power.

## Expansion Port
This revision includes a 10-pin expansion port. The labels on the pins correspond to the GPIO pin values in software for a standard Raspberry Pi Pico.

## Programming
Revision 2 uses the codename "Codex" in Glacier OS.