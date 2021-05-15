# PACMAN

I have implemented the classic arcade game Pacman on a DE10-Lite Intel FPGA board here. The game had a display logic and could be played on a VGA monitor and using a keyboard, whose driver code is coded here.

The basic features (incorprated in the game) include:
- Displaying the maze outline in blue color
- Displaying the dots that have to be eaten by the player in white color
- As the player goes over these dots or “eats” them, they disappear from the screen and the score increases 
- Displaying the player in yellow and controlling it using the keyboard
- Displaying the four ghosts in red, blue, pink and yellow color
- When a ghost and the player collide, the game is over
- Randomly moving ghosts (AI tool to make the game more competitive)
- Score tracking on the FPGAs hex displays

Some advanced features that I will incorporate and add to this game include:
- Background sound
- Joystick support to move the player
- Multiplayer mode (as described in the overview)
- Make sure each ghosts follows their special powers and move accordingly
- For example, Inky is the smartest out of the 4, but lacks focus on pursuing the player



