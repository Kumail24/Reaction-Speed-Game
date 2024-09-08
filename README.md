# Reaction-Speed-Game
Arduino memory game with a full game loop that tests the user's reaction speed for several rounds and returns an average speed at the end. This game includes a green LED which will flash at a random point in time from 1s to 5s, requiring the user to press the push button as fast as they can. This game also includes an LCD which displays a start menu, current round, current round speed, and the user's average speed after the final round.

This game also ensures the user cannot press the pushbutton before the LED flashes by displaying a "try again" screen on the LCD and restarting the LED timer for that specific round.
# Bill Of Materials
- 1x Arduino Uno
- 1x 16x2 LCD
- 2x 1K ohm resistor
- 1x 220 ohm resistor
- 1x pushbutton
- 1x green led
- 1x 10k ohm potentiometer

# Screenshots
Games start menu.
![image](https://github.com/user-attachments/assets/2d59d84e-3fd9-4aa9-a130-1a7e55b19f4b)

Score displaying per round.
![image](https://github.com/user-attachments/assets/fbd3598d-9af5-4bb4-a02e-981242c71d11)

Try again menu, if user presses pushbutton too soon.
![image](https://github.com/user-attachments/assets/8375233b-d2b5-429c-a32c-34dc1fed2b2e)

Average score display at the end of the game.
![image](https://github.com/user-attachments/assets/d284701d-427f-4d2f-a933-24381c7e2b49)
