# Hello World

## THIS WILL NOW SHOW UP

## Elements of 2d game stuff
### 2D Game "Code" Research

**Player "Hitbox"**

1. Make a image for the Player/avatar
2. Make a damge hitbox for the Player/avatar

**Player Movement Elements:**

1. Player moves left or right when User presses the left or right arrow key
   
   Steps:
   1. a registering a left and right arrow key
   2. a keyboard event listener
   3. make the avatar move associative with the background
   4. assign a gradual moving speed to the avatar
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

   Steps:
   1. make the game allow left/right and up buttons to be pressed at the same time
   2. make the falling speed and moving speed happen at the same time
   3. make it work on screen

   
**Game Solids Elements:**

1. The background and foreground are not solid, they are at a fixed point, and they do not change nor move

      Steps:
      1. make a background
      2. make a foreground
      3. make it so that the background and foreground don't move
      4. make it work on screen
   (This step is a work in progress)

2. Platforms/walls are solid and can be touched by Player if the User controls the player to do so, but the platforms/walls do not do anything else
      
      Steps:
      1. make an image for the solid
      2. give the solid a non-damage hitbox

4. Solids that eliminate the Player if the User controls the Player into the solid

      Steps:
      1. make an image for the solid
      2. give the solid a damage hitbox
      3. implement a elimination system for the player (This might need its own step)

5. Tiles that are not solid but act like checkpoints when the User controls the Player to touch them

      Steps: 
      1. make an image for the solid
      2. make a respawn system
      3. make it so that the tile is the place where the avatar will respawn at

6. Enemies that are solid and hurt the Player when the User moves the player into the Enemy but die if the player falls on top of it
   
      Steps:
      1. make an image for the enemies
      2. make it so that the enemies move
      3. assign a speed the enemies
      4. give a damage hitbox to the enemies
      5. make a elimination system for the enemies
      6. make it so that if the player falls on top of an enemy it gets eliminated
      7. implement a elimination system for the player

7. "Turrets" that are solid and shoot projectiles that harm the player if the player is hit by one and once the projectile make collision with something it disappears

      Steps:
      1. make an image for the turrets
      2. make an image for the projectile
      3. give the projectiles damage hitboxes
      4. make it so that if the projectile touches something it disappears
      5. make it so that if the player is in a specific range of a turret the turret will start firing the projectiles at the player
      6. make a range for the turret
      7. give a speed for the firing rate
      8. give a speed for the projectile
      9. have the projectiles shoot at nearly all angles
      10. implement a elimination system for the player

**Page layout and interface**

1. Saveing levels

   Steps:
   1. sync the saveing mechanic to the checkpoints (make it so that when the player gets a checkpoint it saves there at the same time the player touches the checkpoint)
   2. make it so that the game has local saveing (if you restart the game it will get rid of saves but if you close the game your saves will be stored)

2. Menu, also when the User presses "M" it sends the User to the menu

   Steps:
   1. make a background for the menu
   2. have a keyboard listener for when "E" is pressed to go to the actual game
   3. have keyboard listener for when the player presses "M"
   





