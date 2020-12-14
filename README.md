# ParkingSensorHack_8

Arduino sketch that was used in this video about Parking Sensors Hack:
https://youtu.be/_Z1ekKfDxiw

Please note that despite the fact that all cheap parking sensor kits sold on ebay have the same design, 
the internal logic and data packet structure(how they report hata from main unit to the display) may differ.

You address bits may come first(like in this example) or youd data bits may be sent first. 
This really depends on the manufacturer of the particular unit.

This sketch was made simple but it is not universal, you will need to analyze the output of your sensor module
and adjust it accordingly.
