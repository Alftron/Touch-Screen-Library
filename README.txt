
This is the 4-wire resistive touch screen firmware for Arduino. Works with all Arduinos and the Mega

 - Completed the the library in the sense that now the library is pinsafe with the LCD. No need to pull LCD pins anymore in sketches.
 - UNO and MEGA library fully port writes so touch screen will be faster.
 - Removed porthandling initializings from getPoint function to speed up the point fetching.
 - Added cleanPins function which is driven on pin affecting functions.
 - Added bool isTouching function for looping pressure where needed.

