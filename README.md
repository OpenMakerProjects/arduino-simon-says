# Arduino Simon Says

A four-button, four-LED memory game for Arduino.

## Provenance and licence

- Original source: [`simon-says` in mattiasjahnke/arduino-projects](https://github.com/mattiasjahnke/arduino-projects/tree/master/simon-says)
- Reviewed upstream revision: [`45373bc`](https://github.com/mattiasjahnke/arduino-projects/tree/45373bc41f01b8a12860bd6de89f43958e0c71e9/simon-says)
- Original author and copyright holder: Mattias Jähnke
- Licence: MIT; see [LICENSE](LICENSE)

## Supported boards

- Arduino Uno or another 5 V Arduino-compatible board with at least eight digital I/O pins

## Parts list

- 1 × Arduino-compatible board
- 4 × LEDs in different colours
- 4 × momentary push buttons
- 4 × 100 kΩ resistors
- 4 × 220 Ω current-limiting resistors
- Breadboard and jumper wires

## Pin allocation

- LEDs: D2, D4, D6 and D8
- Buttons: D3, D5, D7 and D9

## Required libraries

No external library is required; the sketch uses the Arduino core only.

## Schematic status

The original project includes a circuit image at [`SimonSays-Circuit.png`](https://github.com/mattiasjahnke/arduino-projects/blob/45373bc41f01b8a12860bd6de89f43958e0c71e9/simon-says/SimonSays-Circuit.png). The archive filtering policy excluded images, so the diagram is linked rather than copied. Its electrical correctness has not been independently verified.

## Review status

Source, provenance and licence were checked for publication. Hardware operation has not been independently reproduced by OpenMakerProjects.
