Ball, SoccerSim, Timer
============

Ball: creates a "ball" with each instance of the object creation <br />
~ Ball is initialized with a x,y location and x,y velocity <br />
~ Ball can move (update location) <br />
~ Ball can change speed (update velocity) <br />
~ check if it is in motion <br />
~ check if it is in bounds <br />

SoccerSim: creates a field of balls all with their own behavior <br />
~ makes sure all ball positions are valid <br />
~ creates a list of balls to check locations for each <br />
~ checks if a ball has "hit a pole" which are randomly located on the field <br />
~ checks the distance between two balls <br />

Timer: provides a time-based function which can be used to update velocity (since time is needed) and keep track of total time passed.
