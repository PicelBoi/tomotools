# Formulas

This goes over the formulas made to convert well-knnown units (e.g hertz for pitch, wpm for voice speed) to their eqivalent Tomodachi Life units.
Please note that some aren't based on reverse engineering and rather my own measurements - this is not completely accurate to the game's code, but should be accurate enough to be close to it (hopefully).

## Voice

### Pitch

Formula to convert hz to Tomodachi Life pitch value (0-50, 24.5hz to 588.0 hz (exponential!))
$x=24.63041387*1.065517299^y$
(x is Tomodachi Life pitch value (SHOULD BE ROUNDED TO NEAREST NUMBER), y is hertz)

### Speed

Formula to convert wpm (words per minute) to Tomodachi Life speeds value (0-50, 87.692 wpm to 162.857 wpm (exponential!))
$x=84.53367414*1.012174232^y$
(x is Tomodachi Life speed value (SHOULD BE ROUNDED TO NEAREST NUMBER), y is wpm)
