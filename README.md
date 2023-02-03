# esphome-solis
Based on the work done here: https://sequr.be/blog/2021/08/reading-ginlong-solis-inverter-over-serial-and-importing-in-home-assistant-over-mqtt/ 
I took a long hard look and wondered if I could build a similar system instead using esphome and an Adafruit Feather ESP32 (as i already had Home Assistant Glow running)
Using the documentation on modbus found on the esphome site, with a UART to RS485 converter. I was able to talk to my solis 4g via modbus instead of needing to use the cloud software.

The following yaml if all the boilerplate to upload and run out of the box.
