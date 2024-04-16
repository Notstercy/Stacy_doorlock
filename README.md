# Servo Door Lock Example

## Build and Flash firmware

Follow the ESP RainMaker Documentation [Get Started](https://rainmaker.espressif.com/docs/get-started.html) section to build and flash this firmware. Just note the path of this example.

## What to expect in this example?

- This example just demonstrates how you can control a servo motor SG90 with a contact sensor to function as a door lock.
- To start the project, I assume that you already have the ESP-IDF installed in your machine

  ## Library Installation
- The next step is to: git clone --recursive https://github.com/espressif/esp-rainmaker.git
- Next, git clone https://github.com/espressif/esp-iot-solution.git into Espressif/esp-rainmaker/components folder
- Navigate to Espressif/esp-rainmaker/components/esp-iot-solution/components/motor, move the motor folder to Espressif/esp-rainmaker/components folder

## Example Download
- Finally, git clone this respository into Espressif/esp-rainmaker/examples
- Set the appropriate COM port number and target chip to ESP32C6
- And you are ready to go!


### Reset to Factory

Press and hold the BOOT button for more than 3 seconds to reset the board to factory defaults. You will have to provision the board again to use it.

