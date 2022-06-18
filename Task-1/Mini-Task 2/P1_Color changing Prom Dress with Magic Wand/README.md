# Color-Changing Prom Dress With Magic Wand
	
## Problem Statement
Prototype and design a wand that could scan the color off of any object and light up the dress that same color.

## Illustration
![My Remote Image](https://content.instructables.com/ORIG/FMR/Q9FT/L49W2OUQ/FMRQ9FTL49W2OUQ.jpg?auto=webp&frame=1&fit=bounds&md=6985c9c1b9feda465e68b26f513f07ba)
![My Remote Image](https://content.instructables.com/ORIG/FTO/ZW5Q/L4CQY9O3/FTOZW5QL4CQY9O3.jpg?auto=webp&frame=1&width=1024&height=1024&fit=bounds&md=bc4e37ce5b36441a457a3748afb9b9f8)

## A short Description
This project is about designing a prom dress that has the magic feature of changing its color based on the input color to it through a wand. Basically, there is a swnsor module in the wand that detects the color off an object, encodes it into color values and transmits it to the receiver that is present in the dress, which then sets the Neopixel dot lights to the color corresponding to the color values received. The microcontroller used here is Adafruit's Feather M0 RFM69 Packet radio, with a built-in 868/915 MHz radio module.

## Schematics of the wand (transmitter)
![My Remote Image](https://content.instructables.com/ORIG/FAB/9T32/L47DLNMH/FAB9T32L47DLNMH.jpg?auto=webp&frame=1&width=1024&fit=bounds&md=2bbc478337ff10280d9320412de7cbd4)

## Schematics of the dress (receiver)
![My Remote Image](https://content.instructables.com/ORIG/FPS/RKL6/L49W4A5A/FPSRKL6L49W4A5A.jpg?auto=webp&frame=1&height=1024&fit=bounds&md=5c5237b6bb11f0e3da9543c3e8c367a4)

## Code
The code corresponding to the micro controllers in the dress and wand are included as links below.
Code link for Color changing wand: https://github.com/dstockto/color_changing_wand
Code link for Dress: https://github.com/dstockto/color_changing_dress
