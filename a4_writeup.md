# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
Probably listing the multiple combos and the str because I was not sure if I was doing it in a way that it was going to work. Additionally, I was not sure which direction to go in after I did init, I tried comparing it to the notes which helped a little but it was still confusing.

2. Explain how you would add a computer player to the game.
I would probably have conditionals that would run automatically after the player entered in an answer, it would probably be random places though because I'm not exactly sure how to make it adapt to what the user placed strategically. 

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
You can probably have the computer look through all of the combos that are possible for winning and according to what the player places, to try to be able to win. For example, if the player places their X on pos 2 and 5, the computer can calculate to do either combo [0, 4, 8] or [6, 7, 8]. 