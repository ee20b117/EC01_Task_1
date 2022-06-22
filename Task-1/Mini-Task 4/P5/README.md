# Water Leakage Detection System

## Debugging/Troubleshooting
The architecture or the basic skeleton of the system is as follows: 

BoardNucleo-F446ZE <--MQTT-SN--> Mosquitto RSMB <--MQTT--> MQTT Transparent bridge <--MQTT--> AWS <--REST API--> Front-end

Any problem in the functioning of the prototype is usually present within one of the three process/equipment-interfaces.

## Faulty component?
As a part of any testing process, the first thing we look at is if the power supply is proper and the equipment is turned ON. In case a component does not light up, it needs to be re-connected/replaced appropriately.

Hardware components used here are PIR sensor, water flow sensor, LED, Buzzer and the BoardNucleo-F446ZE.
These components can be put to a Hardware test by simply powering them to see if they light-up/sense the correspoding motion. 
If there is not any hardware issues, we proceed with those concerning the software and interfacing.

## Software/interface issues 
F446ZE collects data from the sensors and sends them to Mosquitto RSMB via MQTT (Message Queing Telemetry Transport)-SN (Sensors Network) protocol.

Mosquitto RSMB: Act as a MQTT-SN broker, its role is to forward the incoming MQTT-SN messgaes to Mosquitto MQTT broker through MQTT protocol.

MQTT-SN/MQTT Transparent bridge: Act as a bridge between Mosquitto rsmb and AWS MQTT broker. All the messages handled by the transparent bridge are MQTT messages.

AWS: This is the cloud part of the system. Here the messages containing the data collected by the sensors are received, the data are stored in a dynamoDB table and they are available through REST API calls.

Front-End: Very simple web-dashboard showing the 15 most recent data that are presented in a table and also plotted in charts.

So, the debugging routine invloves testing each of the interfaces individually.

The data that is detected by the sensors must get to the F446ZE board.

It then must go unchnged to the AWS (Amazon Web Services) and must be forwarded appropriately using REST API calls to the Font-end application. 

