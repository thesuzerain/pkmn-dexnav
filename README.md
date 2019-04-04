# pkmn-dexnav
Implements the popular "dexnav" functionality from newer Pokemon games.



### What is it?

The DexNav function is loosely inspired by this:

<https://bulbapedia.bulbagarden.net/wiki/DexNav>

![Screen Shot 2019-04-04 at 1.24.48 AM](/Users/wyattverchere/Desktop/Screen Shot 2019-04-04 at 1.24.48 AM.png)

In game, it looks like the above. It has several features: a pokemon hunter, a region map, online connectivity, and a "memory chamber" (allowing for random battles).

### How do I use it?

1. Navigate to the scripts section of RPG Maker XP and insert a new script above "Main".

2. Copy and paste the contents from "Dexnav.rb" into that script.

3. Add the Graphics included in the repository to your graphics (in the same file locations).

4. In the overworld, run the command 

5. ```
   $scene = Scene_DexNav.new
   ```

   or

   1. ```
      pbLoadRpgxpScene(Scene_DexNav.new)
      ```

      which will load the scene and render it overtop

5. Some pieces of code are marked off if different button functionality is desired.