# badpico

### Description
We're going to turn a Raspberry Pi Pico into a bad USB that can run Ducky Script commands

### Setup Pico
Download CircuitPython for the Raspberry Pi Pico.  Copy the file to the root directory of the Pico and it will then reconnect as CircuitPython.  
https://circuitpython.org/board/raspberry_pi_pico/  
adafruit-circuitpython-raspberry_pi_pico-en_US-7.3.3.uf2

Download the HID (Human Interface Device) library for the Pico.  Extract it and copy the "lib\adafruit_hid" folder to the "lib" folder of the Pico.  
https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/latest  
adafruit-circuitpython-bundle-7.x-mpy-20230123.zip

The code that runs when plugging in the Pico is "code.py".  We want to allow Ducky Script to be run in Python, so overwrite your Pico's "code.py" with the new copy.
code.py

At this point, the Pico is a Bad USB and can run Rubber Ducky scripts.  Check out:  
https://github.com/hak5darren/USB-Rubber-Ducky







