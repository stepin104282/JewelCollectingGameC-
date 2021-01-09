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
 
 
 
