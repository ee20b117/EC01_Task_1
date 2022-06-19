# DIY Home Automation System 

## Problem Statement
To build a simple DIY Home Automation System using a NODEMCU to monitor energy usage, security system, etc

## Ideation and Planning 
Smartphone application (Blynk)>>Wi-Fi>>Microcontroller (NodeMCU)>>Devices (Fans, Lights, etc.)

### Part of pipeline to break
|Part pipeline | Feasibilty      | Advantages    | Disadvantages  |
|--------------------|------------------|---------------|----------------|
|Smartphone app | App already exists | Easy to download and install | Security threats; Phone needs to have connectivity|
|Wi-Fi transmission | Easily accessible | Fast action, easy to set up | Consumes power|
|NodeMCU | Has on-board Wi-Fi and built-in flash | Easily programmable using Arduino IDE | Running on Wi-Fi, it has greater power consumption|
|Devices | Swiches can be connected easily to the board | A lot of power is saved as they are put to sleep whenever not in use | Sometimes, they work too good; might switch between ON and OFF states even if someone is not in the room for a few seconds |

