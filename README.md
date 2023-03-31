### About

This repository contains mods and tools for Diablo 2 - Lord of Destruction. They're programs and mods that I either use frequently, or that I liked or that interested me enough to store somewhere safe.

These have been tested to work in the v1.13d of the game which is the one that I use.

The credits go to their respective authors.

I will link each official download or forum post related to the download of a mod, and I will also leave here my own copies of each just in case they ever go down.

Most of the mods are text mods. To install those, you just drag-and-drop the data folder into the root folder of Diablo 2 LoD, and make a shortcut to the game's executable file containing the parameters `-direct -txt`.

PlugY has an installer, which I always use and then execute the game directly from my shortcut to PlugY.exe afterward.

D2DX contains a single .dll that you drag-and-drop into the game's root folder.

Certain mods such as Giga Inventory and the Merc Plugin are not fully compatible by default because both modify a same file. This can be addressed very quickly using a text editor though.

BNetEditor 2 triggers false positives, so it may be blocked by AntiVirus programs. Keep that in mind.

### Contents

- **[Balanced Better Drops](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#betterdrops)**: This mod increases the chances of getting Unique and Set items via monster drops or gambling. It actually is kind of excessive, and as a result of the changes you can get infinite money by gambling Paladin Scepters over and over. I'm not using it in my 2023 playthrough, and I'm doing just fine. Got 2 Set items, a Gull dagger and a few other uniques. I'm storing it here for archiving purposes mostly.

- **[Consistent Leveling](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#consistent)**: In the author's own words, it "improves game pacing by making characters level more consistently instead of progressively slower". I'm not using this one either, but that's because I'm using something else.

- **[No Exp. Gain Penalty](https://d2mods.info/forum/viewtopic.php?p=496186#p496186)**: A change that can be performed with a hex editor on the D2Game.dll file. Go to the offset 0x087FFA and replace the 2 bytes right after (74 32) with "EB 0A" to disable a penalty that the game imposes on your character during exp. gain calculation if it's 10 levels higher than the monster they defeated, or more. Normally, when your character kills a monster that is 10 levels lower than the Player or more, the character receives only 5% of the amount of exp. that monster would normally give.

- **[D2DX](https://github.com/bolrog/d2dx/releases)**: A wrapper to enable rendering the game's visuals via the Glide API which in turn allows to use certain features exclusive to it such as 3D Perspective.
  - In order to use this comfortably, I also add the following parameters to the game's shortcut: `-3dfx --dxnologo -dxnoresmod -dxnovsync -dxnocompatmodefix`. **[Documentation for them can be found here](https://github.com/bolrog/d2dx/wiki/CommandLineOptions)**.

- **[Demon Hunter Class](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#demonhunter)**: I'm actually only storing this here for archival purposes and never really used it. It modifies the Amazon class turning it into a bit of a hybrid between the Amazon and Assassin classes with a mild focus on bows and crossbows.

- **Extra Levels**: This is a mod I actually made myself because it was easy enough. It raises the level cap for each character to Lv250. Shoutouts to **[Fabd](https://github.com/fabd)** for providing **[a public repository with clean v1.13 files to modify](https://github.com/fabd/diablo2/)** and **[HellSpawn from The Phrozen Keep](https://d2mods.info/forum/memberlist.php?mode=viewprofile&u=6909)** for writing **[basic instructions to follow](https://d2mods.info/forum/viewtopic.php?p=153518#p153518)**.

- **[Fixed Font](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#fixedfont)**: This mod fixes the Pt of the game's font in order to make the 5 character easier to distinguish from the 6 character.

- **[CPU Fix](https://www.gog.com/forum/general/old_games_not_launching_and_eating_100_of_the_cpu_on_windows_7/post1)**: Ensures that your CPU won't be wasted pointlessly while playing the game. It only affects people who use Windows 7 or an earlier version of Windows, but I still decided to save it here for archiving purposes anyway. [Shoutouts to BaseMod](https://www.moddb.com/mods/basemod) which is how I originally found out about this.

- **[Giga Inventory](https://web.archive.org/web/20210517221747/http://jonripley.com/gaming/Diablo/mods/gigainv.html)**: Expands the size of the inventory, the horadric cube and the stash too.

- **[No Intro](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#nointro)**: Replaces the intro videos with blank files to jump straight into the game's main menu.

- **[PlugY](http://plugy.free.fr/en/index.html)**: This mod provides infinite and shared stashes, automatically changes the number of players in SP, enables the Uber quests, allows to revisit the Cow Level even after killing the Cow King, enables Ladder-exclusive Runewords such as Insight or Fortitute, allows to regenerate a map when you leave for the menu and reload your save, among many other things.

- **[Merc Plugin](https://d2mods.info/forum/viewtopic.php?p=442212#p442212)**: This allows to give your mercenaries a ring, an amulet and a belt. The 2nd ring slot while visible, does not work sadly enough.
