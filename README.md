# TrafficStopLight
/**
1. Detailed specification of the project
  The Purpose of this project was to create a simulation of a simplified traffic stop light. We had 
to represent 4 stop lights with the slow down signal(yellow light) removed, and no turn signals. 
The system would function by alternating between 2 primary states: the north and south lights 
would be on for 3 seconds, and the east and west lights on for 3 seconds. In addition we had to 
implement a third conditional state where if a button was pressed, all the lights would signal to
stop for 5 seconds.

2. System Design, Architecture and Performance
•Controller design (HLSM, datapath, FSM)

Link to Youtube Video: https://youtu.be/aGv-xJGt204

3. Detailed description of the problems and technical issues encountered especially the ones that
resulted in system re-design and/or modifications
  We got a lot of syntax errors because of the timers and we had a lot logic error for the specific
number we needed for the timers. We initially had like 6 states in our initial FSM, until we revised 
it, to be a bit more manageable, and it luckily solved some of the more obscure errors that the
compiler gave us that we didn’t understand. In addition, structuring the hierarchy of the system 
gave us trouble. It was likely due to the software, as this happened in a previous lab where it 
wouldn’t recognize the main function as the top module. After double checking the names of all the
components, it ended up solving itself. 

4. Conclusions
  The system now works according to the specifications and by using the LED display it looks much cleaner.
We still have some compiler errors, which means we could still streamline and simplify our code,
or perhaps make some of the edge cases more clearly defined. I’m honestly not 100% certain what would
fix them, but it is definitely doabl
**/
