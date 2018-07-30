# mike-snake-game
An ES6 Javascript version of the old Nokia Phone game Snake

## Build Instructions: 

First we need to map our playing field on HTML canvas.
1. Set the canvas as a constant in the javascript code. 
2. Next load in images used for playing field and food or hearts in this case.
3. Draw the images and rectangle for snake.
4. Sset unit based onsize of box on background (32px by 32px).
5. Break the game into 4 parts: the snake which is an array, the dirt which is an image, the food, and the score.
6. Create the unit and pull in the images.
7. Create the array for the snake.
8. Create the food/hearts using math .floor and math.random to randomize where the food will appear.
9. Set the score variable.
10. create event listener for keys to move snake.
11. Create a function for hit detection.
12. Create a function to draw everything in canvas

## Gameplay instructions:

1. Press any directional key to begin the snake's movement. Try to guide the snake to the heart.
2. Each heart eaten adds 1 point and a body segment to the snake.
3. The game is over if you hit a wall.
4. You can start a new game by reloading your borwoser.
