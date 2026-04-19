# Formulas

This goes over the formulas made to convert well-knnown units (e.g hertz for pitch, wpm for voice speed) to their eqivalent Tomodachi Life units.
Please note that some aren't based on reverse engineering and rather my own measurements - this is not completely accurate to the game's code, but should be accurate enough to be close to it (hopefully).

## Voice

### Pitch

Formula to convert hz to Tomodachi Life pitch value (0-50, 24.5hz to 588.0 hz (exponential!))  
$y=\log_{1.065517299} (x/24.63641387)$  
(y is Tomodachi Life pitch value (SHOULD BE ROUNDED TO NEAREST NUMBER), x is hertz)

### Speed

Formula to convert wpm (words per minute) to Tomodachi Life speeds value (0-50, 87.692 wpm to 162.857 wpm (exponential!))  
$y=\log_{1.01145341} (x/12.17202483)$  
(y is Tomodachi Life speed value (SHOULD BE ROUNDED TO NEAREST NUMBER), x is wpm)

### Delivery

Formula to convert base pitch and the highest pitch to Tomodachi Life delivery value (0-25 (for each side), 100% to 300% (linear!))  
$y=\frac{(\frac{a}{b})-.9331843382}{.0839460389}$

(y is Tomodachi Life delivery value (SHOULD BE ROUNDED TO NEAREST NUMBER), a is highest pitch, b is base pitch)
