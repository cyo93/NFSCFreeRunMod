README

What's New:
Fixed a critical issue where it's impossible to unlock the free run races for existing profiles when the checkpoint bronze challenge is complete. Existing profiles now need to complete a random encounter instead.

What does this mod do:
In Need for Speed Underground 2, it's possible to free drive around Bayview in Quick Race, meaning that you can use your custom non-career cars and stock cars to free drive around Bayview. However, this option does not exist in Need For Speed Carbon. 
As a result, it's impossible for anyone to test drive their custom non-career cars or stock cars in Quick Race mode or just have a nice time exploring Palmont or San Juan in such cars. This mod adds a special race to the list of Quick Race tracks that has no finish line or barriers. 
However, it does not support online, or other opponents (unless you use NFS Carbon Extra Options by nlgzrgn).

How does it work:
Need for Speed Carbon has a gameplay file that stores every race. This file can be modified to add more races without any other executable modifications such as Unlimiter by nlgzrgn. Unfortunately, the game is hardcoded to not play the EA TRAX when playing races other than checkpoint races.
For this reason, this mod creates an empty checkpoint race with no finish line, checkpoints, barriers, and time limit, allowing anyone to drive freely around Palmont. The empty race is also marked as a Pursuit Race for a possible future update where it may support pursuits.
A script is then used to hook to the function in the game that determines the HUD features and makes it so these races do not show the timer while free driving.

INSTALLATION
1. Make sure your copy of NFS Carbon is Vanilla.
1. Download NFS VLT-Ed, Labrune, and NFS Tex-Ed (1.7 or later).
2. Install the "NFS Carbon Free Run Mod.nfsms" script using NFS VLT-Ed. (Go to the game directory using File->Open, after opening, click on File->Import->Modscript, and choose the modscript in the mod directory.)
3. Install the "Language Patch English.txt" file using Labrune by selecting the "English.bin" found in the LANGUAGES folder using Labrune and clicking on File->Import->Text File. Import the text file in the Mod Directory by selecting it.
4. Using NFS Tex-Ed, open up the Trackmaps.bin file and go to Texture->Add and add the TRACK_MAP_QR_FR.dds, and TRACK_MAP_QR_SJ file to the bin file.
5. Copy the "scripts" folder, and the "dinput8.dll" file (if it doesn't exist in the game directory) to the game directory.
6. If you are using an existing save file, complete a random encounter in Career mode. New users don't need to do this.
7. Enjoy!


KNOWN ISSUES
1. Pursuits do not work properly when using NFS Carbon Extra Options by nlgzrgn. Pursuit breakers and Hiding Spots do not show up on the map, the pursuit information is not shown and the pursuit theme does not properly play.
2. Other languages are not officially supported as of now.
3. For some reason, tracks initially unlocked at the beginning of the game do not get unlocked automatically for existing players.
4. This mod does not support other mods, such as the Battle Royale mod or the Endgame Mod. Support is planned for the future.
5. When enough races are unlocked, the new tracks do not show in "All Available Races". However, they do show up in the "San Juan" category as expected.

WANT TO CONTRIBUTE?
This project is in a BETA stage, and may have some issues, if you can help me solve them, write an asi script to fix them, or report them, please email me at: ladeveloper34@gmail.com.
Make sure to only upload ASI files to patch the executable or modified game files. Unmodified game files are allowed as long as they are files not found in the US version of the game, such as the Japanese language files or voice clips from other languages.
Game executables (even if they are modified) are not accepted.

CREDITS

Injectors - LINK (C) 2012. Used to remove the timer during free run.