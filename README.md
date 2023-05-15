# Arduino Uno temperature controller
This is the code for my school project. It is a temperature controller for a Industrial heating rod embedded into a Aluminum mold (CNC).
## Hardware
* Arduino Uno
* Aluminum mold (STL file included)
* Heating rod - Taken from a old soldering iron (Φ8mm)
* K Thermocouple with converter MAX6675
* Relay

## Usage
* Connect the thermocouple to the MAX6675
* Connect the MAX6675 to the Arduino Uno
* Connect the relay to the Arduino Uno
* Connect the heating rod to the relay
* Open Serial Monitor to see the temperature and the relay state

#The code is based on the example code from the MAX6675 library

## Planned features
* PID controller
* LCD display
* More heat-profiles
    * Ramp up
    * Ramp down
    * Hold Melting point
    * Heat-bed temperature
* Button for control![345857217_718188500105872_2484573851110163995_n](https://github.com/GipsyPotter/ArduinoUno/assets/77058739/61352290-807e-45fd-adb5-598ceeb5eecb)
