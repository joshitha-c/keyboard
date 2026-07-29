# Travel keyboard

NomadKeys is a compact mechanical keyboard that I designed for people who need a reliable keyboard while travelling. The idea behind this project was to create something that is small enough to carry in a backpack without giving up the feel of a mechanical keyboard.

The keyboard is built around the Raspberry Pi Pico (RP2040) and uses a standard keyboard matrix with 1N4148 diodes for reliable key scanning. An I²C GPIO expander is used to increase the number of available input pins, and a rotary encoder provides an extra control that can be programmed for different functions.

The hardware was designed in KiCad 8 and can be used with firmware such as QMK or KMK.

---

## Project Goals

The main goals of this project were to:

- Build a compact keyboard that is easy to carry while travelling.
- Reduce the number of GPIO pins required by using a keyboard matrix.
- Prevent ghosting by adding a diode to every switch.
- Include a rotary encoder for additional controls.
- Keep the design simple enough to assemble and modify.

---

## Features

- Raspberry Pi Pico (RP2040)
- Compact layout for travel
- Mechanical switches
- 6 × 20 keyboard matrix
- 1N4148 diode on every switch
- I²C GPIO expander
- Rotary encoder with push button
- USB connectivity

---

## Components

| Component | Quantity |
|----------|---------:|
| Raspberry Pi Pico | 1 |
| I²C GPIO Expander | 1 |
| Rotary Encoder | 1 |
| Mechanical Switches | Depends on layout |
| 1N4148 Diodes | One per switch |
| Custom PCB | 1 |

---


## Future Improvements

There are still a few things I would like to add in future revisions:

- Bluetooth support
- Rechargeable battery
- OLED display
- VIA/Vial compatibility
- RGB lighting

---

## Software

- KiCad
- Fusion 360

## About This Project

This keyboard was developed as a personal hardware project to explore keyboard design using the RP2040. It combines PCB design,cad project into a single project while focusing on creating a compact keyboard that is practical for travelling.
schematics:
<img width="1186" height="822" alt="image" src="https://github.com/user-attachments/assets/51872eed-dc30-43d0-9c14-cb0f9fdb6ac2" />
pcb:
<img width="1148" height="616" alt="image" src="https://github.com/user-attachments/assets/4387a86d-9829-43fa-9adf-31d9e517be97" />
cad file:
<img width="1090" height="476" alt="image" src="https://github.com/user-attachments/assets/88faa492-7d96-41be-9755-5bb2b6f27e7d" />
![Uploading image.png…]()
