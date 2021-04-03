# SpiralKnightsSceneArchive
The Spiral Knights client only downloads scenes (levels) from the server as they are needed, and some (procedural levels) are normally not saved to the local cache at all. Should the servers ever shut down said content would be lost, this archive aims to fix that by preserving them.


"scenesmain.log" contains a log of when each scene was downloaded as well as info about it, "scenesmaini18n.log" is the same but with the scene names translated to their human readable level names as seen in the game itself.


Scenes with ID's greater than 1073741823 are procedurally generated levels, these are often overwritten so be sure to checkout the appropriate commit for the mission/level type you want. Ideally for future server development these should be broken back down into their procedural chunks and used as examples only. (Edit: This is no longer the case as new commits are renamed with a time stamp, I might go back and split/rename the old ones at some point if I can be arsed.)

Scenes below 1073741823, with the exception of Guild Halls which follow their own rules, are static and only changed when updated manually by the dev team.

Titanium contains scenes collected from the now dead Chinese bootleg "Titanium Warrior" by "PlayN", a game which for some reason used the Spiral Knights engine and assets to make a MOBA.

In order to do anything useful with these you will need the Tudey Scene Editor, this is part of Clyde which can be found here: [https://github.com/threerings/clyde](https://github.com/threerings/clyde)


# Contributing
Cached scenes can be found in the "scenes" folder of any Spiral Knights install, if you have any to contribute, especially from an older install of the game, simply open a Pull Request here. Please create a new folder to keep them separate from the main archive, your GitHub username is a suitable folder name if in doubt.


If you are not a GitHub user, or do not know how to open a Pull Request, feel free to PM me directly to contribute. The best place to reach me is Twitter: [https://twitter.com/sinkillerj](https://twitter.com/sinkillerj)
