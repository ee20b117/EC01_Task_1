# DIY Home Automation System 

## Problem Statement
To build a simple DIY Home Automation System using a NodeMCU to monitor energy usage, security system, etc

## Ideation and Planning 
Smartphone application (Blynk)>>Wi-Fi>>Microcontroller (NodeMCU)>>Devices (Fans, Lights, etc.)

### Part of pipeline to break
|Part pipeline | Feasibilty      | Advantages    | Disadvantages  |
|--------------------|------------------|---------------|----------------|
|Smartphone app | App already exists | Easy to download and install | Security threats; Phone needs to have connectivity|
|Wi-Fi transmission | Easily accessible | Fast action, easy to set up | Consumes power|
|NodeMCU | Has on-board Wi-Fi and built-in flash | Easily programmable using Arduino IDE | Running on Wi-Fi, it has greater power consumption|
|Devices | Swiches can be connected easily to the board | A lot of power is saved as they are put to sleep whenever not in use | Sometimes, they work too good; might switch between ON and OFF states even if someone is not in the room for a few seconds |

## Choosing a pipeline
Since we need remote control over the devices, bluetooth or such short range connection technologies can't be utilised and we need to resort to Wi-Fi based systems like ESP.

Here, we have chosen _NodeMCU_, which is based on _ESP8226_ Wi-Fi chip. It is programmable using Arduino IDE and can be accessed by the _Blynk_ app via _Auth_Token_. For this to work, we also require the Blynk Library to be installed in our IDE. 

## Prototyping Phase
This phase is where we assemble the circuit on the breadboard. In case one wishes to have a PCB for the project, the corresponding Gerber file can be downloaded from ![here]()

