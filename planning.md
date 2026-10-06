A place to write your findings and plans

## Understanding
1. Create a sprite that contains the score. This is an adjustable value that writes in 8X16 font. The score is stored within the vector initialized above. 

2. While true, set keybinds & initialize the player/treasure shapes by the defined rectangle sizes. 

3. If the player's rectangle intersects with the treasure rectangle, use rng based on the size of the screen to relocate the treasure and increment the player's score count. 

4. Then update the score display + rng, and then update the display. This is within a while loop, which means that these checks happen every frame

## Planning required changes
1. Change the player speed - Adjust static speed value

2. Change the backdrop color - Add bn::backdrop::set_color() value before while loop after variable initialization

3. Change the starting pos of the player and dot - Copy `static constexpre int` formatting to create player starting position

4. Check if start has been pressed. If so, revert all settings and reset score. 

5. Set player wraparound to inverse player position if player reaches edges by creating if gates which inverse player x and y coordinates based on criteria

6. Store information: Does the player have speedboost? Does the player have speed boost stocks? How long does the player have speed boost? If so, when the player presses `a`, activate speed boost, remove a stock, and create a timer that decrements  by the framerate. 

## Brainstorming game ideas

## Plan for implementing game

