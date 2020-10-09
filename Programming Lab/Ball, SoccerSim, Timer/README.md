Ball, SoccerSim, Timer
============

Ball: creates a "ball" with each instance of the object creation
~ Ball is initialized with a x,y location and x,y velocity
~ Ball can move (update location)
~ Ball can change speed (update velocity)
~ check if it is in motion
~ check if it is in bounds

SoccerSim: creates a field of balls all with their own behavior
~ makes sure all ball positions are valid
~ creates a list of balls to check locations for each
~ checks if a ball has "hit a pole" which are randomly located on the field
~ checks the distance between two balls

Timer: provides a time-based function which can be used to update velocity (since time is needed) and keep track of total time passed.
