# Critter World

## (CS 2112 - Cornell University) Object-Oriented Design and Data Structures (Honors) Final Project

*Unfortunately, the academic integrity policies at Cornell University prohibit making source code from course projects publically available. However, we have received permission from the instructor to share the repository with individual employers. Feel free to contact me, if you find this project interesting and wish to view the source code!*

Critter World is a project that simulates a world of small agents–critters–with the goal to survive. These critters can move, eat, attack each other and even mate with other willing critters. Critters are also able to sense the nearest piece of food with a “smell” command, implemented with a modified version of Dijkstra's shortest path algorithm. 

Each critter behaves according to a “Critter Program” unique to each critter. This program is written in the “Critter Language”—a context-free grammar—defined by the course staff which can be found in the detailed project spec below. 

As part of the project, I wrote the fault injection to make random, small mutations to critters' genes when they reproduce, as well as the path-finding algorithm for critters to sense locations of food in their proximity.

![alt text](/img/0.png)
![alt text](/img/1.png)
![alt text](/img/2.png)
![alt text](/img/3.png)
![alt text](/img/4.png)

More detailed project spec can be found [here](https://www.cs.cornell.edu/courses/cs2112/2020fa/project/project.pdf?1606926715). 
