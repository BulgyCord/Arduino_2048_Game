# Arduino_2048_Game

 ## _Description_

A 2048 inspired game implemented using Arduino, playable on a LCD screen. The purpose of the game is to merge two of the same numbered tiles in order to create the sum of those tiles into a new tile with the end goal being to have a high score in a limited time.

 ## _Components_

- LCD 128x128

- 2x Breadboard

- Arduino Uno/ATmega328P

- 2x Buttons

- 3x Resistors (2x 1 kΩ, 1x 200 Ω)

- 1x Joystick  

- Wires

 ## _Flow_

When powered on the LCD shows a menu that has 2 options to select New Game and High Scores.
When selecting "New Game" the player starts a game of 2048 that lasts 2 minutes. 
The game acts like a normal 2048 game. 
The player starts with a number of tiles labeled with the number 2, they have to combine said tiles in order to make a greater number, the start case being a tile with the label 4, and so on. The player has 4 buttons each representing a direction: up, down, left or right. Each move made moves all the tiles already on the board in the specified direction and creates after it a tile where the space allows it, players have to calculate each move in order not to mistakenly fill up their space.
When the player adds 2 tiles, depending on the sum of the tiles, a number of seconds are incremented back into the timer and a score is added to the total score of that round. 
The game ends when the timer hits 0 or when there is no space left for the tiles to spawn. 
At the end of a round, the total score is shown and the player can add a username made of 3 letters. In the "High Scores" menu players can see the usernames that they or others have created at the end of a round with the total score.

## _Technical Details_

The LCD is the screen that shows all the menus including the game itself.

The 2 buttons are used to interact with the menu screen. The first button acts like a select button, while the other as a "go back" button.

The joystick is used to navigate through the menu, it is also used to make moves in the game.

## _Wokwi Configuration_

![image](https://github.com/user-attachments/assets/14e4e799-74eb-43ba-939d-1cee6f50aa8e)

## _Physical Configuration_

![image](https://github.com/user-attachments/assets/d67913d4-beec-43e4-bc14-5a71c7178163)

## _Code_


