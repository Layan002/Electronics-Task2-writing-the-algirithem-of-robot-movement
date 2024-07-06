# Algorithem

1- first, there are restriction I've noticed on the lower part of human body:

- thigh moves forward 180 degrees, but it can't move backward.
- knee moves backward and it is impossible to move forward, unless it will be broken 
- feet moves 90 degreees forward. 

Thigh Movement:

- The thigh can move forward up to about 180 degrees.
- The thigh cannot move backward (human can do it but for robot I wont do).

Knee Movement:

- The knee can move backward about 180 degrees.
- The knee cannot move forward (doing so would result in damage or breakage).

--------------------------------------------------------------------------------------------------

Foot Movement:
The foot can move forward up to about 90 degrees.
> the thighs' position are intialized at 20. <br>
> the foot position are intialized at 45. <br>
> the knees position are intialized at 0. <br>

So now; we will talk about moveing one step forward: 

1- move up the right thigh by changing the degrees positively to around 50. The right knee moves backward around 30 degrees, the foot initally on the position of 45 degrees, now it is gonna be Zero.

2- Along side, the left leg will change the thigh from 20 to Zero (moveing backward to make the push of the body forward), the knee moves backward almost 15 degrees, and the left feet at its initialized position degrees of 45. 

3- now for the right leg, we will loops in the opposit side of the angles' degrees to return them to their initilized positions and same for the left leg. This will cause the Robot to return to the standing stright position. 

4- To move another step, we will switch between the two legs in step 1 and 2.   


