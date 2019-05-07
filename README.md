# TPA_Buffalo_IIIsePro38_Software
Microcontroller/Arduino_DUE software for Buffalo III 38 Pro DAS 
Author: Poninski Tomasz
Date: 2019-05-07

Created and compiled in Atom + PlatformIO (Arduino DUE)

C++/C scalable software written for Arduino DUE, but adaptable to any microcontroller. 
The software is writte the way its easily scalable, the core of DAC class is based on TwistedPairAudio firmware for ES 9038 Pro DAC. 
It includes proper power up sequence, initialisation and configuration which are almost identical with TPA Firmware. 
The File ES9028_38.h configuration file is 1:1 TPA firmware file.

This software lets you control volume and change inputs, all other setting are read from switches on Buffalo III board (exatly the way TPA is doing it). There are classes prepared for EEPROM, interfaces (remote + touch) and graphics. Those can be replaced with own classes, so anyone can add on user interface, display, or save sattings to eeprom.

The software is free for DIY and private use. If you make any progress please public the changes/software. 
