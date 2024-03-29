## DESCRIPTION

Very simple and probably extremely unoptimized rpg game made using pygame (and numpy).

I'm aiming to build a "roguelike dnd" at some point, with randomly selected dungeons and randomly generated encounters, bosses, items, loot, etc. Still very early in development.

## INSTALLATION

1. **Windows**
* Download and extract the _game_win.zip_ file, found within the _Executables_ folder. Run _game.exe_. This was created using pyinstaller on Windows 11, within the Anaconda environment. Windows defender will probably warn you that you're running an app from an unrecognized publisher. I can give you no more than my honest promise that there isn't anything malicious in my game :) If you believe me, click More Info, and then Run Anyway to start the game. At some point I might come back to this and try to make an installer that won't cause this issue with Windows Defender. Note that you do not need python or any of its libraries for this to work.
* Alternatively, clone this repository, and make sure you have python, pygame and numpy installed, alongiside any python IDE (VSCode or whatever). Compile _game.py_ within your IDE and enjoy the game.
2. **Ubuntu-based Linux distros**
* Download and extract the _game_linux.zip_ file, found within the _Executabkes_ folder. This was created using pyinstaller on Pop!-OS, which is a Ubuntu-based distro. This means that it should work on any other Ubuntu-based distro, although I haven't tested it outside pop-os. If you try it out on a different distro, feel free to let me know if it worked or not. Run the _game_ executable.
* Alternatively, make sure you have the latest versions of python, pygame and numpy installed, then clone the entire repository and compile game.py (either directly from terminal using python3, or from an IDE).

Note that the executables will probably be a couple of versions behind the actual code, because I create and update them every couple of updates. If you want to create your own, make sure you have python, pyinstaller, pygame and numpy installed, locate the folder where _game.py_ is in your terminal/powershell, then run `pyinstaller --onefile game.py`. You'll find the executable within the _dist_ folder, make sure that it's moved to the same folder where _Pictures_, _Sounds_ and _Dungeons_ folders are. You can run the executable there, or zip the executable and those three folders, plus the _build_ folder, into a zip file for sharing.

## ROADMAP

1. Add class features for the first five levels
2. Make weapon and spell attack selection more intuitive
3. Expand inventory system to manage prepared spells as well
4. Populate encounters lists
5. Add some more dungeons, develop dungeon chains
6. Add difficulty 2 and 3 encounters
7. Make inventory management less clunky
8. Create a tutorial .txt
9. Implement game saving/loading

## CREDITS:

Game Mechanics:
The basis of this game is currently a slightly modified version of fifth edition rules for Dungeons and Dragons, by Wizards of the Coast. Legally I am obliged to include their Open Gaming License, which you can find in the main repository, named 'SRD-OGL_v5.1.pdf'. I plan to further modify and adapt the basic DnD rules for the purposes of the game in the future.

Dungeon Maps:
All of the dungeon maps that are or will be included in the game were released on [Dyson Logos](https://dysonlogos.blog/maps/commercial-maps/), under a free use license. I've been using this website for my personal DnD games for a long time and highly recommend you check it out!

Music and SFX:
Music during adventure - created by [ZHRØ on Freesound](https://freesound.org/people/ZHR%C3%98/sounds/527321/)
