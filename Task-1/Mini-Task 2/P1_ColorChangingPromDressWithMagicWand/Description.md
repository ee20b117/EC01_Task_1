# Color-Changing Prom Dress With Magic Wand
	
## Problem Statement
Prototype and design a wand that could scan the color off of any object and light up the dress that same color.

## Illustration
![My Remote Image](https://content.instructables.com/ORIG/FMR/Q9FT/L49W2OUQ/FMRQ9FTL49W2OUQ.jpg?auto=webp&frame=1&fit=bounds&md=6985c9c1b9feda465e68b26f513f07ba)
![My Remote Image](https://content.instructables.com/ORIG/FTO/ZW5Q/L4CQY9O3/FTOZW5QL4CQY9O3.jpg?auto=webp&frame=1&width=1024&height=1024&fit=bounds&md=bc4e37ce5b36441a457a3748afb9b9f8)

## Schematics of the wand (transmitter)
![My Remote Image](https://content.instructables.com/ORIG/FAB/9T32/L47DLNMH/FAB9T32L47DLNMH.jpg?auto=webp&frame=1&width=1024&fit=bounds&md=2bbc478337ff10280d9320412de7cbd4)

## Schematics of the dress (receiver)
![My Remote Image](https://content.instructables.com/ORIG/FPS/RKL6/L49W4A5A/FPSRKL6L49W4A5A.jpg?auto=webp&frame=1&height=1024&fit=bounds&md=5c5237b6bb11f0e3da9543c3e8c367a4)

## Code

![image](https://user-images.githubusercontent.com/85028192/124804514-0487a480-df78-11eb-9076-7723c8c8d46c.png)

1. Using pinMode function to configure pin number 9 as OUTPUT in the void setup() function.
```
void setup()
{
  pinMode(9, OUTPUT)
}
```

2. Using digitalWrite() function we set pin number 9 to HIGH or logic 1. Then using the delay() function, we wait for 5 seconds. After the delay, we set the pin to LOW and again wait for 5 seconds. This will be a part of the void loop() functions so it runs in an endless loop till we switch the power OFF.
```
void loop()
{
  digitalWrite(9, HIGH);
  delay(5000); // Wait for 5 seconds
  digitalWrite(9, LOW);
  delay(5000); // Wait for 5 seconds
}
```

## Tinkercad simulation

 https://www.tinkercad.com/things/3mr0w1MXYY7 
