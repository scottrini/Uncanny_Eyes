# Teensy3.1_Eyes

'Uncanny eyes' for Adafruit 1.5" OLED (product #1431) or 1.44" TFT LCD (#2088).  Works on PJRC Teensy 3.x and on Adafruit M0 and M4 boards (Feather, Metro, etc.).  This code uses features specific to these boards and WILL NOT work on normal Arduino or other boards! For Teensy 3.x: Use 72 MHz board speed -- OLED does not work at 96 MHz.

How-to guide with parts list and 3D models is here:
https://learn.adafruit.com/animated-electronic-eyes-using-teensy-3-1/overview

Directory 'uncannyEyes' contains Arduino sketch for PJRC Teensy 3.1 & Adafruit M0 & M4. 'uncannyEyes.ino' is the code, 'eyeData.h' is a set of arrays containing eye bitmaps, etc.

Folder 'convert' contains Python sketch for generating eyeData.h. Requires Python Imaging Library. Example images are also in this directory.
