## Adafruit Kinetic_POV

TUTORIAL LINK:
https://learn.adafruit.com/bike-wheel-pov-display/overview

Software related to DotStar LED persistence-of-vision performance items -- initially the Trinket-based "Genesis Poi" and then additional POV projects.

This code was formerly at https://github.com/adafruit/Kinetic_POV - this has now been archived.

If you are looking to make changes/additions, please use the GitHub Issues and Pull Request mechanisms.

Written by Phil Burgess / Paint Your Dragon for Adafruit Industries. MIT license, all text above must be included in any redistribution. See 'LICENSE' file for additional notes.

----------------------------
Notes for the workshop:

* Add the Adafruit Board Support Package

  Paste in https://adafruit.github.io/arduino-board-index/package_adafruit_index.json to the 'Additional Board Manager URLs" in Arduino IDE.

  
Image conversion (optional):

1. Install the Python Image Library (PIL):
  https://www.geeksforgeeks.org/how-to-install-pil-on-macos/

2. Export your image as a GIF file that is exactly 32 pixels high.

3. Use the following command: 

python convert.py [YOUR FILENAME].gif > graphics.h

4. Copy the color palette with the bitmap into your main .ino file.

