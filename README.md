# GRADEME_Project-31-Quick-Read-Thermometer
Quick read thermometer that display temp on a graph
TFT is first defined along with char tempArray to populate the two axis's.
Function called getTemp reads sensor value and converts it to mV than Celsius.
Function called drawScreen sets up the tft screen drawing onto it.
Setup is used to initalize tft screen and print onto it, this was used for testing and checking values.
The main loop has two function calls for getTemp() to obtain values from sensor and convert to Celsius, drawScreen() draws the TFT screen drawing the values onto the screen. 
A for loop is last in the main loop to add a delay before it loops again.

