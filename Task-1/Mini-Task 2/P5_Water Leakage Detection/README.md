## Problem Statement
Design a system that monitors a tap with the goal to detect wheter there is a leak of water and in case of leak notify it through an acoustic signal.

<img src = "https://hackster.imgix.net/uploads/attachments/1455340/_LTGnAke0sx.blob?auto=compress%2Cformat&w=900&h=675&fit=min" width = "500"/>

## Requirements
### Hardware
    ST STM32L4, STM32F7 Nucleo 144 STM32F7    
    PIR Motion Sensor (generic)		
    Water Flow Sensor	
    Buzzer
    LED (generic)
### Software
    RIOT OS RIOT
    AWS IoT
    
## A brief Description
Water shortage is a major issue nowadays and we can't affort to lose water to a careless and unwanted leakage. 
The system that is to be designed has to monitor the waterflow out of a tap constantly and sense the leakage (a flow of water without any movememnt detected in front of a PIR sensor is recognised as a leakage here) and send an acoustic signal via a buzzer. In order to turn off the buzzer, the tap mmust be closed. 

## Schematics
![](https://hackster.imgix.net/uploads/attachments/1455250/wl-phis-arch_yvDFuRdWec.png?auto=compress%2Cformat&w=740&h=555&fit=max)

## More about the Project 
The whole project explanatory can be found at https://www.hackster.io/fgcrino/water-leakage-detection-system-35ccdb
and the code file is available as [FrancescoCrino / water-leakage-detection-system](https://github.com/FrancescoCrino/water-leakage-detection-system) in GitHub.
