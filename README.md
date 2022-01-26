Write a program where two users can play Pig dice against each other. Don't forget to write plain English specifications with example inputs and outputs before you begin coding!

What will happen when a user clicks "Play"?
  –Start a new game
  -Clear old game- set scores to zero
What objects will you need?
  -Player 1 and Player 2 Objects that hold Total score
  -Player 1 and Player 2 Objects that hold value of die that's been rolled

What key-value pairs will each object need to contain in order for the game to work?
  -Total score: this.score = score;
  -Die rolled: score = score + roll;

What functions?
  -Start new game, clear old scores
  -Roll math.random
  -Add new roll to running score
  -Add running score total score
  -Change players
  
How will these be triggered throughout the gameplay?
  -Button to start new game/clear scores
  -Button to roll die
  -If roll != 1, add running score to total, else set running score to 0
  -Button to end turn and add running score to total, trigger change players

How will information be collected from the user? How will it be displayed?
  -Click roll button, display results on a die, field for running score, field for total score

When you have a broad overview of how you want to build your game, identify the simplest behavior, and perhaps what behaviors to tackle after that. Remember to start simple and work one step at a time.

-----------------------------------------------------------------------------------------------------------------

Describe: Roll()

Test1: "It should display a random number between 1 and 6."
Code: roll(6) + 1
Expected Output: 1, 2, 3, 4, 6, or 6.
