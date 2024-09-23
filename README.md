# Hello World

## THIS WILL NOW SHOW UP

## Elements of 2d game stuff
### 2D Game Movement Code Research

**Player Movement Elements:**

1. Player moves left or right when User presses the left or right arrow key
   
   Steps:
   1. a registering an arrow key
   2. a keyboard event listener
   3. make the "square" move associative with the background
   4. assign speed to the avatar
   5. make it work on the screen
   6. handle obstacle mechanics so the avatar doesn't clip through walls
   
2. Player jumps up and then falls down when User presses the up arrow key
 
   Steps:
   1. registering an up arrow key
   2. keyboard event listener
   3. make the avatar move associative with the background
   4. assign the speed to the the up movement
   5. assign the speed to the falling movement
   6. make a gradual falling speed
   7. make it work on screen

3. Player moves at a curve when both the up arrow key and the left/right arrow key are pressed at the same time
   1. 
4. Player has a certain speed
5. When the User moves the Player the Player’s F.O.V (Field of view) changes

**Game Solids Elements:**

1. Background is not solid but moves with the player’s F.O.V
2. Platforms/walls are solid and can be touched by Player if the User controls the player to do so but don’t do anything
3. Solids that eliminate the Player if the User controls the Player into the solid
4. Tiles that are not solid but act like checkpoints when the user touches them
5. Enemies that are solid and hurt the Player when the User moves the player into the Enemy

**Page layout and interface**

1. Saveing levels 
