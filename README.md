# AS3935_MOD-1016
A modified AS3935 library to be used with Embedded Adventure's MOD-1016.

To use this library with MOD-1016 please make the following changes to the board:
1) Default board configuration is for I2C, remove the jumper from I2C and solder the jumper for SPI connection.
2) Remove the solder from CS-GND.

Based on the excellent AS3935 libraty by raivisr https://github.com/raivisr/AS3935-Arduino-Library.

Modifications made according to Erci's blog: http://www.erickenny.com/blog/?p=318.

Use the example project to test you MOD-1016. In the example a LED is triggered when a lightning strike is detected. This is a modified example from raivir's library.

Tested successfully using Arduino UNO.
