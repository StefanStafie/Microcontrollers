links:
Digits: https://www.electronicsforu.com/resources/7-segment-display-pinout-understanding
Timer: https://microdigisoft.com/timer1-in-pic-microcontroller/
Interrupt on change: https://www.youtube.com/watch?v=oSfByzzaWfE



------ Sa faci calculele pentru impuls ca sa le intelegi bine
FOR 100km/h
Fosc / 4 = 4 MHz / 4 = 1 Mhz
Prescalar = 1:8
Tick Counter frequency = Prescaler/1 Mhz = 8 / 1 Mhz = 8 us
Delay required = 18 ms
Timer Count = 18ms/ 8 u s =  2250 ticks;
Timer start: 65535 - 2250 = 63285

10km/h
Delay required = 180 ms
Timer should start at 65535 - 22500 = 43035


50km/h
Delay required = 36 ms
Timer start: 65535 - 4500 = 61035