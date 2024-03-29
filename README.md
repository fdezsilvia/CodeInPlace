# My Code in Place Extensions
## Code in Place had been offered online by Stanford University April-May 2020

Completed a 5-week introductory online Python programming course based on material from the first half of Stanford’s introductory programming course, CS106A.

• Offered by Stanford during COVID-19 pandemic, with 10,000 global students chosen from 80,000 and 900 volunteer teachers participating from around the world.

• Development of logical thinking, decomposition, flow control and good code style.

• Projects with karel, images with PIL, Tkinter and databases.

# Beeper Picker - Maze Solver

Karel, in any size maze world, pick up all the beepers and put it down in a pink corner, functioning as a scoreboard.

[![4](https://user-images.githubusercontent.com/66931354/86308061-939d0680-bc18-11ea-85f2-095aea3cc7e8.png)
](https://www.youtube.com/embed/JRAHfXjUEq4?start=2)

# Vertical Maze

Karel moves through holes in columns that are one corner separate, that makes a hall. She pick up the coins (beepers) and put it down at the finish line, that function as a scoreboard.

The finish line is mark in orange with beepers, that Karel can also pick.
The coins are just at the holes. Holes are 1*1.

Inspired in [Flappy Bird Game](https://flappybird.io/)

# Watermelons painter

Karel moves in the world searching black corners. When she finds one, she paints a watermelon if it is separated at least 16 corners in width and 9 in height.
She paints randomly black corners at the beginning to mark possible locations, then paints all watermelons.

Karel's initial position is (1,1) and faces east.

# Automaton Conway's rule 22

Karel is an automaton following Conway's rule 22. The initial state is chose randomly between the simple initial condition(one corner paint in the midpoint of the last street) or multiple painted corners, these are randomly separated.
