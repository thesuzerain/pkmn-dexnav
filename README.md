# pkmn-dexnav
Implements the popular "dexnav" functionality from newer Pokemon games.



### What is it?

The DexNav function is loosely inspired by this:

<https://bulbapedia.bulbagarden.net/wiki/DexNav>

In game, it looks like the below imgur picture. It has several features: a pokemon hunter, a region map, online connectivity, and a "memory chamber" (allowing for random battles).

https://imgur.com/Nsp7nyo

### How do I use it?

1. Navigate to the scripts section of RPG Maker XP and insert a new script above "Main".

2. Copy and paste the contents from "Dexnav.rb" into that script.

3. Add the Graphics included in the repository to your graphics (in the same file locations).

4. In the overworld, run *one* of the two following commands (it will render the scene overtop of the overworked)

5. ```
   $scene = Scene_DexNav.new
   
   pbLoadRpgxpScene(Scene_DexNav.new)
   ```
