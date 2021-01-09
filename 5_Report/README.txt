Problem Statement:
     	The problem is to design a jewel collecting game which provides the following functionalities:
·  	The person can move in a given direction and while moving, the number of moves are counted.
·  	The jewels must appear randomly in a given boundary.
·  	When all the jewels were collected, the game will be over with showing the number moves a person takes to collect all the jewels.
·  	If a person quits by not collecting all the jewels, the display message has the number of jewels collected and number of moves taken.
·  	 The main functions that can be used are:
1.	Person
2.	Jewels
3.	Boundary
4.             Number Of Moves
5.             Directions



Description:
    	This Mini Project in C jewel collection Game is a simple console application without graphics. In this project, the player is going to collect jewels randomly emerging on screen and must change the direction of the person by pressing left, right, top, down arrows for collecting the jewels.
Jewels are provided at the several coordinates of the screen for the person to collect. Every time the person moves to collect the jewel, the number of moves will be counted.
      	An Additional feature is completion of the game in a number of moves which makes the game addictive and has the ability to mesmerize the player. This is a small & simple C Programming application for game lovers.
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
Test Plan:
     	How can we test a full jewel collecting game, and assuming it passes that stage, how can we playtest that?
The functional requirements that are developed turn almost immediately into a checklist. Let's look at an example. To display the person, the first thing we want to do is to make sure that we can draw the person and move him/her around on the screen. So, our testing for correct function will be:
 
1. Can I display the person on the screen?
2. Will the person move around as I want it to using keyboard control?
3. Is jewels displaying correctly?
4. Is the person moving correctly?
If we identify an error in the moving direction, because it's a function, we will go into the change user location function and fix it there. However, because we've written the jewels and scoreboard as separate functions, whatever we do in the direction function shouldn't break anything in there, unless we accidentally change the code without noticing.
We'd then continue to test the program until we've tested all of the individual elements and their interactions together. One useful test case is to see if everything is being drawn where you expect. Because we aren't using all the screen, it's possible to draw the jewel or the person so that it overlaps the black rectangle that's the boundary.
Has the programmer put the correct limits on the ranges where the person and the jewel can appear? Check weather the number of moves displaying is correct and accurate.
 
 
 
Test Cases:
1.
If the player collects all the jewels present within the boundary.
Game Over.
Number of Moves.
2.
If the player quits the game by not collecting all the jewels.
You Quit.
Number of Jewels collected.
Number of Moves.
 
Expected Results:
1.	If a player completes the game by collecting all the jewels then display with a message called “Game Over” and “Number Of Moves” taken to collect all the jewels.
2.	If a player quit the game by not collecting all the jewels then display with a message called “You Quit”, “Number of Jewels Collected” and “Number of Moves” taken.
 
 
 
