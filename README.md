# TPA_Buffalo_IIIsePro38_Software
Microcontroller/Arduino_DUE software for Buffalo III 38 Pro DAS 
Author: Poninski Tomasz
Date: 2019-05-07

Created and compiled in VSCode / Atom + PlatformIO (Arduino DUE)

C++/C scalable software written for Arduino DUE, but adaptable to any microcontroller. 
The software is writte the way its easily scalable, the core of DAC class is based on TwistedPairAudio firmware for ES 9038 Pro DAC. 
It includes proper power up sequence, initialisation and configuration which are almost identical to TPA Firmware. 
The File ES9028_38.h configuration file is 1:1 TPA firmware file.

This software lets you control volume and change inputs, all other setting are read from switches on Buffalo III board (exatly the way TPA is doing it). There are classes prepared for EEPROM, interfaces (remote + touch) and graphics. Those can be replaced with user own classes, so anyone can change, extand or replace the classes of user interface, display, eeprom, or even dac...

The software is free for DIY and private use. If you use this software and make a progress please publish the results. 
