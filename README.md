# Indoor Garden
The purpose of this repo is to place code regarding an automated indoor garden.

So, what do you need to build this system yourself?
BOM:
Arduino or ESP8266 to control the lot
Moisture sensor like an FC-28
Valve to control water dispenser (materials to be determined)
Tubes to connect the water dispensing unit to the planter
Water reservoir (anything waterproof will do) to connect to the valve
Liquid level controller for the water reservoir
Growing lights (SMD5050 LED grow strips)

The choice for the Arduino or ESP8266 depends solely on the ammount of moisture sensors you need to connect. Since the FC-28 is not quite accurate in digital mode (too basic), you want to read the sensor in analogue mode. An ESP8266 has a limited set of analogue connectors. If you want to connect more than 6 sensors, you might want to use the Arduino Mega as it has 12 analogue connectors.


To be continued...
