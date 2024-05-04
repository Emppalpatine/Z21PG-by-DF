These files are the customisation of the source code for the Z21PG DCC central station (https://sourceforge.net/projects/f944.pgahtow.p/files/Z21_Ethernet_DCC_Zentrale_v498.zip/download) to adapt them to a new developed hardware that can be found at this address (https://oshwlab.com/fiorinid/z21pg-by-df-pro).
Installation step:

1. Unzip the package https://sourceforge.net/projects/f944.pgahtow.p/files/Z21_Ethernet_DCC_Zentrale_v498.zip/download into the /Z21 directory in your PC
2. Take note of the path for the Arduino Libraries in your PC ("Arduino Libraries path")
3. Copy the header file "config.h" for the Z21PG by DF central station overwriting the "\Z21\Z21_Ethernet_DCC_Zentrale_v498\config.h" file
4. Copy the header file "POWER.h" for the Z21PG by DF central station overwriting the "\Z21\Z21_Ethernet_DCC_Zentrale_v498\POWER.h" file
5. Copy the header file "Z21_LAN.h" for the Z21PG by DF central station overwriting the "\Z21\Z21_Ethernet_DCC_Zentrale_v498\Z21_LAN.h" file
6. Copy the source file "Z21_Ethernet_DCC_Zentrale_v498.ino" for the Z21PG by DF central station overwriting the "\Z21\Z21_Ethernet_DCC_Zentrale_v498\Z21_Ethernet_DCC_Zentrale_v498.ino" file
7. Copy the source file "DCCHardware.cpp" for the Z21PG by DF central station overwriting the "Arduino Libraries path\Z21\DCCInterfaceMaster\DCCHardware.cpp" file
8. Copy the header file "DCCHardware_config.h" for the Z21PG by DF central station overwriting the "Arduino Libraries path\Z21\DCCInterfaceMaster\DCCHardware_config.h" file

Compile the sketch and flash it within the ATMEGA2560 microcontroller.     
