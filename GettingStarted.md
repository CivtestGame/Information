# Civtest Starter Guide


	     Welcome to Civtest!
           A Starter Guide
           
	    By ComradeRick & R3KoN


Civtest is a Minetest-based sandbox where players must band together, in whichever way they see fit, to conquer a lawless and unforgiving wilderness.

## Quickstart

1. Download and install Minetest 5.1.1 (5.1 is also compatible) from [here](http://www.minetest.net/downloads/).

2. (Optional) review 'Settings' tab.

3. Click 'Join Game' and enter `civtest.org` as the Address (Port is `30000`) Choose a username and password (this is hashed + salted serverside). Re-enter your password when prompted.

4. You should be in-game. Hit `Esc` to see the menu -- review and change your keybindings.

**Important Things**

Hold `E`(aka 'Special') to sprint. Be warned that this uses a lot of Satiation.

Hit `F9` to see the minimap and radar. Configure zoom with additional `F9` hits. 

If your sensitivity in-game is too high, go to the 'Settings' tab in the main menu, hit 'All Settings' and search for "sensitivity", and adjust.

If you don't like the entity selection box, you can disable it in 'All Settings' (search: selectionbox).

FPS is limited to 60fps by default. Change in 'All Settings' (search: fps).

Nights are really dark -- no, there isn't a setting to change this. Make torches.

Shift-clicking generally works the same as in Minecraft. Middle-mouse-button is capable of crafting 10 items at a time.

There is a chat radius of 1000 blocks. CombatTag is 30s.

WorldBorder is a 5000 block radius from 0,0. You cannot reinforce blocks for the last 50 blocks before the border. Random spawning occurs in a 2500-radius.

Bedrock is at y=-250. You cannot build beyond y=250.

CombatTag is configured to **kill** you if you've been tagged and logout/disconnect. Tag on-login is 5s, tag in combat is 30s. 

## Core Game Mechanics

### Ores and Materials

As you go on through the game, you can obtain stronger materials with which to make blocks, tools, weapons, armor, and more.

Many materials can be found by scouring the world and its oceans. The world made of many large regions, and can house their own unique resources. 

Ores are usually found underground in sparsely distributed veins. While veins are uncommon, they are large and compact, and it's common for a single vein to contain thousands of ore. It is common for veins to appear within hills and cliffs, too.

These ores can be refined and smelted into more useful forms, and may become armor, coinage, or a component of a factory or railroad.

### Reinforcement

Reinforcement is the process making of blocks harder to break. To reinforce blocks, you must first create a named group via the command: `/group create <name>`. You can add people to your group via `/group add <player>`, and remove them with `/group remove <player>`.

Now that you have your group, you can protect your buildings and chests by typing `/ctr <group name>` and hitting the block with the reinforcement material. Typing `/ctf <group name>` while holding a reinforcement material causes newly placed blocks to reinforce automatically.

The cheapest reinforcement material is (smooth) stone. Copper, tin, and steel ingots can be used as stronger alternatives.

If a block is reinforced, you can see detailed information by typing `/cti` and punching the block.

*PlayerManager and Citadella are the main plugins involved here. See `/group` and `/help` for more information.*

### Defense and Protection

#### Imprisonment

*(This is likely to change in future versions.)*

Players can be imprisoned by other players when killed, as long as the killer has a Prison Pearl in their hotbar.

Prison Pearls are crafted by surrounding a Sand block with four Cobblestone, in a configuration resembling a cross. 

"Pearled" players are kicked from the server and unable to join. They can only know the current location of their Prison Pearl.

Other players can access the location of a pearled player by using `/pplocate`. This command is universal, so if you intend to keep your prisoner, you should take precautions. Prison Pearls are best secured in reinforced containers in reinforced structures.

#### Recorders and Notifiers

Want to see who messed with your crops? Notifiers and Recorders are your friend.

Notifiers are triggered when a player enters and exits their proximity. When this happens, Notifiers alert everyone in their group about the event.

Recorders, on the other hand, keep logs of movement, block breaks, and other activity in an area, but they do not notify.

Notifiers and Recorders can be used together for greatly improved security.


### Productivity  

#### Agriculture

Civtest’s agriculture is tweaked to better balance the game. Crops have a varying set of conditions needed for optimal growth. These include temperature, lighting, among others.

Crop growth is persisted, so don't worry about babysitting your crops. They will grow even if you're nowhere near them.

Crops often take a while to grow. You can right-click the crop with a Hoe for more information about the crop's expected growth time.

You can also right-click the air with a hoe to find the current biome conditions.

Seeds can be obtained by breaking grasses in grasslands and plains.

#### Food and Starvation

Foods generally follow a quality system. Foraged foods, while capable of sustaining a person, are not a long term solution for satiation.

Processed/cooked foods are better, but obviously require a time or resource investment to obtain. Agriculture is a good, sustainable way to feed a population.

Wild animals can also serve as a source of food. Rabbits are uncommon, but serve as a good supplement to food stocks.

Tameable animals are rare in this world, but they can serve as a great source of food when tamed and properly looked after. Cows are particularly suited to producing large amounts of food, but they are scarce, and may attract unwanted attention from other players. 

#### Factories

To allow for mass production of goods, factories are a prominent mechanic. They create a large tech tree with output and price increasing as you progress. 

The simplest factory is a Burner, which efficiently burns various materials for use elsewhere. The recipe for a burner is the same as a furnace (8 cobble around the edges), but with a torch in the middle of the grid.

To see factory recipes, right click your Burner and click the "Show Guide" button. You will see a recipe for a Basic Smelter, which is the next factory up from the Burner.
