# RPG - Dragon Repeller

This is a simple text-based RPG game called "Dragon Repeller". The game is built using HTML, CSS, and JavaScript. The player's objective is to defeat the dragon that is preventing people from leaving the town. The game provides various actions and choices for the player to navigate through different locations, buy health and weapons, and engage in battles with monsters.

## Getting Started

To play the game, you can open the `index.html` file in a web browser. The game interface will be displayed, showing the player's stats, buttons for different actions, and a text area for game messages.

## Game Mechanics

### Player Stats

The player has the following stats:

- **XP**: Experience points gained from defeating monsters.
- **Health**: Represents the player's health points.
- **Gold**: Currency used for purchasing items.

### Weapons

The game offers different weapons that the player can acquire. Each weapon has a name and power level. The player starts with a "stick" weapon and can buy better weapons from the store.

### Monsters

There are different types of monsters in the game. Each monster has a name, level, and health points. The player can encounter monsters in the cave and fight them.

### Locations

The game has several locations that the player can navigate to. Each location has its own set of available actions and messages. The available locations are:

1. **Town Square**: Starting location. Player can go to the store, the cave, or fight the dragon.
2. **Store**: Player can buy health potions or weapons, or return to the town square.
3. **Cave**: Player can fight different monsters or return to the town square.
4. **Fight**: Player engages in battle with a monster. Player can attack, dodge, or run from the battle.
5. **Kill Monster**: Message displayed after defeating a monster. Player gains experience points and gold.
6. **Lose**: Message displayed when the player loses the game. Player can choose to replay.
7. **Win**: Message displayed when the player defeats the dragon and wins the game. Player can choose to replay.

## Game Controls

The game controls are implemented using buttons in the HTML interface. The buttons are assigned functions based on the current location and available actions. The button controls are as follows:

- **Button 1**: Performs the action associated with button 1 in the current location.
- **Button 2**: Performs the action associated with button 2 in the current location.
- **Button 3**: Performs the action associated with button 3 in the current location.

## Game Script

The game script is implemented in the `script.js` file. It contains functions for updating the game interface, handling button actions, managing player stats and inventory, and simulating battles with monsters.

## Styling

The game's visual appearance is defined using CSS in the `style.css` file. The CSS rules define the background color, text colors, padding, and borders for different sections of the game interface.

Feel free to explore and modify the code to enhance the game or add new features. Have fun playing "Dragon Repeller"!
