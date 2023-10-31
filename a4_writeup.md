# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
Thinking about how to write out all of the possible ways a player could win for the  has_won method without having an out of bounds error.
2. Explain how you would add a computer player to the game.
I would create a method that would check if the other player was one away from winning in any of the possibilities and if that method returns true the computer player would put its piece to block it, if it returned false it would work either randomly place a piece if it hasnt placed a piece yet or place a piece that connects with a piece it has already played.
3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it. I cant think of any ideas better that what I already said in question #2.