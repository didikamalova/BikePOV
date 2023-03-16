## Adafruit Kinetic_POV

Software related to DotStar LED persistence-of-vision performance items -- initially the Trinket-based "Genesis Poi" and then additional POV projects.

This code was formerly at https://github.com/adafruit/Kinetic_POV - this has now been archived.

If you are looking to make changes/additions, please use the GitHub Issues and Pull Request mechanisms.

Written by Phil Burgess / Paint Your Dragon for Adafruit Industries. MIT license, all text above must be included in any redistribution. See 'LICENSE' file for additional notes.

----------------------------
Notes for the workshop:

* Add the Adafruit Board Support Package

  Paste in https://adafruit.github.io/arduino-board-index/package_adafruit_index.json to the 'Additional Board Manager URLs" in Arduino IDE.
  
* Connections are as follows:

Pro Trinket - (on back) to battery ground

Pro Trinket + (on back) to battery positive

DotStar LED strip G to Pro Trinket G

DotStar LED strip 5V to Pro Trinket BAT+

DotStar LED strip data to Pro Trinket 11

DotStar LED strip clock to Pro Trinket 13

Optional tactile mode selector button between Pro Trinket 3 (TX) and G

Optional vibration sensor between Pro Trinket 2 and G
