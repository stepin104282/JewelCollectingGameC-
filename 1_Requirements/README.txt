
Requirements:

      	To create a Jewel collecting game that allows the user to control the movement of a person on a screen, to get jewellery. we want to write a game where a person moves across the screen. When he/she encounters a jewel, it is collected by the person. If all the jewels were collected by the person, then display game over and number of moves taken by the person to collect all the jewels present. In case a player quits by not collecting all the jewels present then we need to display the number of jewels collected and number of moves taken to collect.
 
To write this program we are going to need:
·      A way of representing the person.
·      A way of representing the jewels.
·      A way to display the number of moves taken by the         person.
·      A way for our instructions to reach the person, i.e., to move in a given direction.

random function:
In c program there is a random function which is used to place the jewel at any point on the screen. Thus, use this function to place jewel at any point on the screen.

Changing Direction:

The direction of a person can be changed by using kbhit() function. when you press the character accordingly it will change the direction of the person.

Srand:

if we don't use srand() then every time we compile and run the program we will be getting the same coordinate for jewels hence it is a must to use srand function.
 
Let's look at how a program to run the whole game might look:
1. Draw the playing area with a bounding rectangle, set the number of moves counter to zero.
2. Draw the person in a starting position.
3. Draw the jewels in a random location.
4. On user input, change a person's direction.
5. Continue until all the jewels are collected.
6. If all the jewels are collected, then display with a message called    game over and display the number of moves a user takes to collect all the jewels present within the boundary.
7. If a user quits the game, then display a message called you quit and display number of jewels collected and number of moves he/she took to collect jewels.


 
