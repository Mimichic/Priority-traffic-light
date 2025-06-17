# Priority-traffic-light
Verilog implementation of priority-based traffic light made using Xilinx Vivado

## Problem at hand
Here, you have something similar to a crossroads, where one path is a 'main road' (or priority road) and the other is a 'side road'. The main road, on most occasions, has a green light; however, when two cars are on either side of the 'side road', we must ensure the lights on the side road (which are initially red) turn green, allowing these cars to pass after which it goes back to our default state. Added to this, we must employ a 'slow' and a 'fast' clock, wherein the slow clock is used in case of a transition from a yellow signal or red signal while the longer clock is used in case of a green signal.


