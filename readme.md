# Shadow Warrior and Duke Nukem 3D
###### Based on EDuke32 and JFSW ports

#### Bugs
Crash on game exit. Workaround: use `home` button to exit the game.
Sound is a bit off after wake up from sleep.

#### Compile
To compile eduke32 use command `make PLATFORM=SWITCH` and wait.
To compile voidsw use command `make sw PLATFORM=SWITCH` and wait.
Shadow Warrior compilation will fail at map editor. But at this time, game NRO is already built.

#### Install
Copy built NROs into their own directories on your SD card.
Also copy propper configuration file (platform/Switch directory) there.
Default configuration for Shadow Warrior is a bit off and you wont be able to move. So use one i provided.

#### Configuration
Both games should be pretty much configurable from in-game menus. Even joycon roles and sensitivities.
BEWARE! In order to save your new configuration, you have to exit the game. Exiting the game will crash your switch right now, but configuration will be saved.

#### Shadow Warrior
There are multiple weapons in this game that have alternative functions. Normally these accessed by selecting specific weapon again.
Since Switch does not have enough buttons for that, i have added new button function.
This function is called `Alter_Weapon` and it will switch weapon function, for weapons that have more than one.
