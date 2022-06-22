# Augmented Reality Indoor Tour Guide

## Problem Statement: 
We all must have been frustrated by the long queues and fatigue due to an unguided tour. 
Having an in-person tour guide is not alwaysfeasible concerning the cost getting added to the 
tour and other personal aspects like privacy. Of course, having an electronic device or an 
application on our mobile phones makes it easier much easier to make the best out of the 
tour. This could very well be achieved on a very large scale easily; say we are to pin point to 
places by the existing services of GPS. But what if we want it be on a small scale but a little 
more specific like dealing with one huge tourist spot at a time like a museum? 

## Approach to the Problem:
This can’t be achieved easily using GPS as predicting the exact location is limited to a fewer 
precision. Suppose there are multiple floors in the building. Then we can’t really rely on the 
GPS as it is not feasible to get the floor in with the tourist is right now. So, it is necessary to 
come up with something that rather works locally specific to the spot according to its own 
features. Considering this, we might set up ratio transmitters at various location inside the
museum and by collecting information from good number of sensors, we might to be able to 
identify the exact spot of a person to greater precision and give them a better guide. This 
could somehow be mapped to the nearby features that are yet to be noticed and, in a way,
reduces the hustle. 

## Ideation:
Suppose one such transmitter fails. This might be very problematic as we may not be able to 
get the location of an individual. However, projecting the next location to be queued one after 
the other and displaying it in advance can reduce this to some extent as the person probably 
remembers the next place on the queue. 
Suppose we build our model with PIR (Passive Infrared Sensors). This would not work as 
Infrared Red rays can’t penetrate. Given that a museum is going to be crowded enough, we 
can’t opt for PIR sensors but other forms. One such class of sensors is the Radio Transmitters. 

## Prototyping and Testing:
The first prototype for this model would be to predict the location of a tourist with the help 
of ratio transmitters and gather the nearest feature to be looked at in the museum. This 
nearest computation is going to be simply based on the direct distance without considering 
the fact that it is not possible to go up straight from one point to the other. 
In the second prototype, we may incorporate the layout of the museum and find the actual 
distances that a person needs to take in steps. The implementation might be through matrices 
where we could section the map into rows and columns and get to the closest approximation 
to the nearby places. 

## Taking up the Project Further:
By providing this device or application to most people in the museum, crowd management is 
possible. By properly distributing the tourists among various features of the museum, it is 
possible to make the touring efficient and less tiring. Further, an analytics platform integrated 
with this can help distribute the tourist’s time based on their individual as well as collective 
interests.
