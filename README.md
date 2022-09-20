Python ST7735 library for 1.8" SPI tft Display interfacing with Rapberry PI
=======================

Python library to control an ST7735 TFT LCD display.  Allows simple drawing on the display without installing a kernel module.

Designed specifically to work with a ST7735 based 128x160 pixel TFT SPI display.

Connections:::::::::::::
=========================
1.  https://raw.githubusercontent.com/VirusHQ/youtube_video_tutorial_codes/master/2.8_LCD_display_on_a_Raspberry_Pi_ft_ILI9341/wiring_diagram.png
2.  https://docs.particle.io/assets/pdfs/raspberry-pi/datasheet.pdf

For all platforms (Raspberry Pi and Beaglebone Black) make sure you have the following dependencies:

````
sudo apt-get update
sudo apt-get install build-essential python-dev python-smbus python-pip python-pil python-numpy
````

For a Raspberry Pi make sure you have the RPi.GPIO and Adafruit GPIO libraries by executing:

````
sudo pip install RPi.GPIO
sudo pip install Adafruit_GPIO
````

For a BeagleBone Black make sure you have the Adafruit_BBIO library by executing:

````
sudo pip install Adafruit_BBIO
````

Install the library by downloading with the download link on the right, unzipping the archive, navigating inside the library's directory and executing:

````
sudo python setup.py install
````

See example of usage in the examples folder.

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Modified from 'Adafruit Python ILI9341' written by Tony DiCola for Adafruit Industries.

MIT license, all text above must be included in any redistribution
