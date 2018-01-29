# Indoor Garden
The purpose of this repo is to place code regarding an automated indoor garden. Besides that, I feel like documenting everything so that one can simply buy the materials, clone this repo and build an awesome garden him/herself. The goal for now is to get myself acquainted with GIT, build a system which helps plants to actually NOT die in my home (souterrains don't get much natural light which is great for nerds like me but not for plants) and hopefully create a solid concept for people to help them grow their own food in a sustainable way.

So, what do you need to build this system yourself?
Bill of Materials (BOM):

1. Arduino or ESP8266 to control the lot
2. Moisture sensor like an FC-28
3. Valve to control water dispenser (materials to be determined)
4. Tubes to connect the water dispensing unit to the planter
5. Water reservoir (anything waterproof will do) to connect to the valve
6. Liquid level controller for the water reservoir
7. Growing lights (SMD5050 LED grow strips)

The choice for the Arduino or ESP8266 depends on the ammount of moisture sensors you need to connect. Since the FC-28 is not quite accurate in digital mode (too basic), you want to read the sensor in analogue mode. An ESP8266 has a limited set of analogue connectors. If you want to connect more than 6 sensors, you might want to use the Arduino Mega as it has 12 analogue connectors. Oh, and if you want a simple system and WiFi from the start, the ESP8266 is the way to go.

Because right now I don't have any materials to work with, this README will be continued later on. Oh, and I bought a bonzai ficus tree. Let's hope the lights get here fast; those trees seem to die fast so this is a serious case of life or death...
