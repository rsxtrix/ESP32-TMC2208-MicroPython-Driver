# ESP32-TMC2208-MicroPython-Driver
This is a driver I've written in MicroPython for the ESP-WROOM-32 to interface with the TMC2208 v3.0 UART to control a NEMA motor.

To be specific, this is a really basic driver to help anyone move their NEMA motor with this setup. I found drivers written in C for the standard Arduino environment, but I didn't want to use C for my "just for fun" project.

I'm using Thonny as my IDE, and I'm runnning MicroPython 1.19.1, though I don't think I'm doing anything particularly version-specific. It's the newest version as of posting this. I flashed my ESP-DEVKITV1 board (aka ESP32 aka ESP-WROOM-32) with "esp32-20220618-v1.19.1", but there's a tutorial about how to do all that on the MicroPython website.

Upcoming changes:<br>
Be able to change motor current easily<br>
Have a more test functionality available in the "firmware"<br>
Upload a picture of my wiring diagram from Fritzing<br>
