KOLOS is an automation module based on ESP32-S3, designed for remote control of laboratory equipment - AC devices, sensors, indicators. Designed to manage environmental control systems for laboratory greenhouses with higher plants.  

Designed on a 4-layer printed circuit board, has dimensions of 124x95 mm.  
Powered by 5V via USB-C or screw connector, it has built-in surge protection with a self-resetting fuse. ESP32 is powered by a built-in AMS-1117-3.3 stabilizer.  
The board has expansion pins for connecting additional equipment to the controller, as well as screw connectors for connecting sensors using the 1-Wire protocol. The firmware of the controller and communication with the PC is done through the built-in USB-UART converter CP2102N. The board contains four relay channels controlled via an optocoupler and an HDC1080 temperature-humidity sensor.  
Mounting can be done in the housing with M3 screws or on a DIN rail, for which fasteners are provided.  
The firmware is implemented on the basis of the ESP-HOME framework for integrating the product into the Home Assistant environment. The system is configured so that the user can securely access the board remotely, via a Wireguard network, or locally.  

The pcb contains:  
- 4 5v relay module
- buttons for manual switching of the relay state in an emergency situation  
- optocoupler for relay control from the controller
- AMS-1117-3.3.
- USB-UART converter CP2102N.
- USB type-c for power and connection to a PC
- expansion pins for ESP32
- temperature-humidity sensor HDC1080
- expansion pins for connecting sensors via 1-Wire
