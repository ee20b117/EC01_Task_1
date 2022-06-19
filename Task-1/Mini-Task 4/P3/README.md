# DIY Home Automation System

## Debugging/Troubleshooting
The project is skeletoned on the three main features in the sequence:
  Blynk>>(Wi-Fi)>>NodeMCU>>Devices

Any problem in the functioning of the prototype is probably present within one of the three process/equipment-interfaces. 

### Faulty component?
As a part of any testing process, the first thing we look at is if the power supply is proper and the equipment is turned ON. In case a component does not light up, it needs to be re-connected/replaced appropriately. For example, if the Blynk app fails to respond, it might be required to refresh/re-install the application. 

### Blynk-NodeMCU interface testing 
In order to check the Blynk-NodeMCU interface, we set up a few operations on the app, send it to the microcontroller and see if the commands are received as they are. The code given below (based on Arduino IDE) can be used for this purpose. This code is a temporary block and hence needs to be uploaded on the MCU for testing. 

    char Incoming_value = 0;                //Variable for storing Incoming_value
    void setup() 
    {
        Serial.begin(9600);         //Sets the data rate in bits per second (baud) for serial data transmission
    }
    void loop()
    {
        if(Serial.available() > 0)  
    {
        Incoming_value = Serial.read();      //Read the incoming data and store it into variable Incoming_value
        Serial.print(Incoming_value);        //Print Value of Incoming_value in Serial monitor
        Serial.print("\n");        //New line 
    }                            
    } 
    
If only a few clicks are recognised, check for lose contacts as it might be due to inadequate power supplies to either of the components.
