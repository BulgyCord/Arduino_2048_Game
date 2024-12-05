# Arduino_2048_Game

 ## _Description_

A 2048 inspired game implemented using arduino, playable on a LCD screen. The purpose of the game is to merge two of the same numbered tiles in order to create the sum of those tiles into a new tile with the end goal being to have a high score in a limited time.

 ## _Components_

- LCD 128x128

- Breadboard

- Arduino Uno/ATmega328P

- 4x Buttons

- 4x Resistors

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

## _TinkerCAD Configuration_

## _Physical Configuration_

## _Code_


