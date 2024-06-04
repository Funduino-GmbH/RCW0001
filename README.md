
# BitGo V1.0

The library facilitates the integration of the RCW-0001 sensor with both the Calliope mini V3 and the MicroBit platforms, supporting operation under a 5V and 3.3V voltage. This Library is designed to measure distances in centimeters. By default, the trigger pin is set to C8, and the echo pin defaults to C9, aligning with the standard configuration requirements of our Calle Roboter.

## Images

![App Screenshot](https://raw.githubusercontent.com/JEAPI-DEV/GNA/main/images/Schematic.png)


## Installation

How do I add this Library to my project.
In order to do as such, copy the following url.

```
https://github.com/Funduino-GmbH/RCW0001/
```

and when you go to your existing calliope project, or create a new project, and go unter extensions, you will probably see a search bar in there paste the url you copied earlier. And Click on the search result. After that, it should be installed. And you will see our library, on the left side


    
## Documentation

The library is largely self-explanatory and includes a function that returns an integer value. This returned integer can subsequently be processed within an if statement, allowing for comparisons such as determining whether the number is greater than or equal to, or less than, another specified value.