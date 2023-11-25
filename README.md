# esphome-ecoforest
An Esphome implementation for RS485 communication of the Ecoforest heatpumps.

# Currently just the starts of a ESPHome RS485 intergration for Ecoforest heatpumps.

I am using an ESP32 and a MAX3485 for the RS485, Pin 16 Rx, Pin 17 Tx - It connects to the BMS2 port on the heatpump.

The registers I am using are for the ecoAir, The ecoGeo have different registers as far as I know.

This one is currently read only, and My heatpump had an bms2 address set at 26, I changed it to 1 for simplictiy.




