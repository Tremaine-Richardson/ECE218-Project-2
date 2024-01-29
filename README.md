# ECE218-Project-2
Members:
Chiharu Mamiya & Tremaine Richardson

Description of System:
This system prototypes an automatic headlight system for a car. We make use of a driver seat occupancy sensor as a button, an ignition button, a light sensor,
3 LEDs, one for indicating the engine state and the others for the headlights, and a potentiometer to select the mode for the headlights. The system initializes
with all LEDs being off, meaning the engine is off and the headlights are off. While the engine is off, the headlights will always be off. To start the engine,
the driver seat sensor must be activated by pressing the button, and then the ignition button must be pressed and released. Once the engine is on, the driver
can leave the seat, or by letting go of the button, and the engine will remain on. Once the engine is on, the headlight system can be activated. There are
three headlight modes, ON, OFF, and AUTO. If ON is selected, the two headlight LEDs simply turn on. If OFF is selected. the two headlight LEDs will turn off.
If AUTO is selected, we use the light sensor to determine what should happen. If the light sensor determines that it is dark and the headlight LEDs are off,
they will automatically turn on after 1 second. If it is bright and a lot of light on the sensor and the LEDs are on, they will turn off after 2 seconds. If
it senses that the light level is somewhere in between, then the headlights will stay in whatever state they were in previously. And then to turn off the engine,
the ignition button just needs to be pressed and released again. 

Starting Repository:
https://github.com/Tremaine-Richardson/example_4-1-new

Test Results:

![image](https://github.com/Tremaine-Richardson/ECE218-Project-2/assets/155551490/d8866030-ee50-4b04-a931-d5f7524404f7)
