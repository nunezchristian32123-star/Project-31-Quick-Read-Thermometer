# GRADEME_Project-31-Quick-Read-Thermometer
Quick read thermometer
TFT screen and its pins are first defined. 
Function called getTemp with variables voltage and current for equations along with a sensor variable for later calcions and tempArray with 120 elements for the x axis values. Lines 39-43 are used to conver the sensore value to mV then Celsius and later current. For loop is implemented to put values into tempArray for the x axis. 
Draw screen void function is sused to setup the grpah with values along the y axis and lines along the left and bottome sides. A for loop is used in this function to plot all the numbers to their respective y axis values.
Setup is used to being and see if tft screen is initailized with a time variable also being set up to see how much time has elapsed since the program has started with prints to the tft screen to say "Begin temp sensor". 
Loop starts with function get temp then draw screen doing the described actions above, For loop starts with the purpose of delaying the loop to allow time for temp change.
