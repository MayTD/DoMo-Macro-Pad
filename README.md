# DoMo Macro Pad
![PCB render](PCB/DoMo-pcb-render-front.jpg)
![PCB render](PCB/DoMo-pcb-render-back.jpg)

DoMo is a 3x3 macro pad with a rotary encoder and OLED display. It's a straightforward design with a straightforward idea. I originally designed this for myself to provide quick access to most commonly used keys especially for programming. That means the top priority were to include shortcuts for copy and paste! However this can also be used just as any other macro pads for media controls to help improve workflow.

QMK: https://github.com/MayTD/qmk_firmware/tree/master/keyboards/domo

## Features

- QMK Firmware Support
- MX Hot Swap
- OLED Screen
- Rotary Encoder
- LEDS

## Assembly 
Note that source files only covers the PCB. Components must be assembled in order for the board to be functional or completed.
| Number of Parts | Component | Description |
| ------------- | ------------- | ------------- |
| 1 | USB Cable  | Depends on choice of microcontrollers |
| 1 | Pro Micro or Equivalent | Microcontroller that features USB connectivity on-board |
| 1 | Reset Switch | Switch to enter bootloader mode |
| 10 | Diodes | standard switching signal diode | 
| 9 | Kailh MX Sockets | Hot Swapping Sockets which can support MX switches |
| 9 | MX switches | PCB supports PCB Mounted switches | 
| 1 | Rotary Encoder | EC11, 5Pin, 6mm |
| 9 | Keycaps | Any keycaps of choice |
| 1 | Bottom Plate | PCB includes 4 mounting holes that could fit M2 screws | 
| 4 | LEDS | Individual WS2812B 5050 RGB LEDs|
| 4 | 1x4 Connector | 4 pin male header|
| 1 | OLED Display | 0.91 128×32 Display Module|
