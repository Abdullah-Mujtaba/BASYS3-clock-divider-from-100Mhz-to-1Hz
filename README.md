# BASYS3-clock-divider-from-100Mhz-to-1Hz
Implementing a clock divider on basys3 FPGA which takes the clock from 100Mhz to 1hz and blinks an LED on the 1hz clock


Basically 100Mhz is the clock of the basys3 which we have taken as input, and now we know half of that will 50 million half of 100 into 10 pwr 6 is 50 mil.
So I toggle a variable for half of the time and turn it off for half of the time
Now I know 1 cycle takes 10ns so x time will be taken for 50mil cycles which comes out to be 0.5 seconds
so 0.5 + 0.5 = 1 seconds
so F = 1/1 which comes out to be 1Hz.
