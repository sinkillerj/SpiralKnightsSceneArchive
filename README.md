# Spiral Knights - Scene Archive
_"one ring to find them"_

The Spiral Knights client only downloads scenes (levels) from the server as they are needed. Some (procedural levels) are normally not saved to the local cache at all, some no longer exist in game, and others would be lost if the game ever shut down. The archive aims to preserve these scenes.


## Folders

**Master** - The revised archive of all preserved Spiral Knights scene revisions. 

**Legacy** - The original version of the archive. Moved here for posterity, but no longer updated.

**Titanium** - Scenes from various versions of "Titanium Warrior", a game made by Chinese studio "PlayN". This is a MOBA style game which uses the Spiral Knights engine and assets. 


## Conventions

Upon entering a master folder you will find subfolders for various scene types. Each contains a master index (README.md) containing parsed info from each scene.

The main scene prioritizes the newest known copy at the time of archive overhaul (May 2023), whereas other copies with hash differences are renamed to add a "_rev" tag with the likely year if known. Given the various sources this year should not be taken as gospel, the parsed version where available is a much better metric of age. 


## Limitations

The master archive does not yet contain procedurally generated scenes, you will need to visit the legacy archive for now. Work is being done to improve the handling of these, such as splitting out shared name files which were overwritten in older legacy commits. This will take some time to complete.

Likewise the legacy archive is better for event viewing at this time.

I am still working on a parser for Titanium scenes so there is no index, stay tuned.


## Technical

Scenes with ID's greater than 1073741823 are procedurally generated at the time of capture, for example clockwork tunnels.

Scenes below 1073741823 are typically static, and only change when they are updated on the server by a developer or guild hall owner.


## Viewing

There is currently no public software available to play these scenes, however you can view them with the official Tudey Scene Editor, this is part of Clyde which can be found here: [https://github.com/threerings/clyde](https://github.com/threerings/clyde)

Alternatively precompiled versions of Tudey can be found in software such as SpiralView: [https://github.com/lucasluqui/spiralview](https://github.com/lucasluqui/spiralview)


# Contributing
Cached scenes can be found in the "scenes" folder of any Spiral Knights install, if you have any to contribute, especially from an older install of the game, please open an issue containing a download link. This is preferred over a pull request, as it allows me to more easily check for duplicates prior to inclusion.

If you are not a GitHub user, feel free to DM me directly to contribute. The best place to reach me is Twitter: [https://twitter.com/sinkillerj](https://twitter.com/sinkillerj)


# Credits
This project has been made possible by several contributors such as:
* SinKillerJ
* bigboypl
* lucasluqui
* Kritzmensch
* Airbeeso
* BukkitBoss
* HotHotFire
* Thyrux
* Arca
* Amine
* Breakfast
* Trace-By
* Florix
* criasus
* Alextronis

(If your name is missing, please reach out.)
