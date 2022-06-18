## Problem Statement
Make an LED chain with multiple patterns using Arduino UNO.

## Description
An LED chain is made by arranging nine LEDs one after ther other and make desired patterns by switching certain LEDs between ON and OFF states using Arduino UNO. Any pattern of choice can be made. However, one such pattern is given here. Using for loops, integer i is set as the pin number, first when i is 0, the pins 0, 1, 2 are set to HIGH and the pin before i is set to LOW ( there aren't any pin before i when i = 0). Then a 25ms delay is given before the loop continues. Another for loop is used  to reverse the pattern. This whole pattern is then repeated 3 times.

## Hardware Requirements
Arduino Uno
Bread Board
Jumper Wires
LED 5mm 5V (Any Color) 9pcs
Resistance 220 Ω
A Working PC

## Snapshot
![MyRemoteImage](https://content.instructables.com/ORIG/FLN/2QWX/L4E6FAOU/FLN2QWXL4E6FAOU.jpg?auto=webp&frame=1&fit=bounds&md=709076995afd25be0a2e4da215637fd9)

The code is attached in the same repositary.

The full project can be viewed at https://www.instructables.com/LED-Patterns-Using-Arduino/

