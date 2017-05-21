# connect4TivaC
 Components used
    Tiva tm4c123 microcontroller
    Nokia 5110 LCD

Code
    Mapto, getx, which map the 1D array from C code to 2 dimensional array for Nokia screen
            Clean, it clears the current array and adds space in slots
    GetValue, it fetches the column value and returns the actual value in the array
    Winning,  checks the dots coordinates required to win the game.
    Draw_Select  draws the selector 
    Play_position determines the selector position and return the actual array value
  AIManager  determines the best decision to put the move in
  NegaMax determines the win/loss ratio  for each player

