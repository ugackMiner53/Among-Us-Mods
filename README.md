# Among Us Transparent Game Code Mod
A mod for Among Us which makes the game code in lobbies completely transparent.

# Installation instructions:
1. Download the file named "level2" from the github or the "Releases Page"
2. Navigate to your Among Us files
3. Open "Among Us_Data"
4. Move the file that is already in there called "level2" to a safe location.
5. Move the new "level2" file into the folder
6. The mod is now installed! No game codes will show up!

# Uninstalling instructions:

1. Replace the new "level2" file with the original which you placed in a safe location
2. The mod is now uninstalled! Game codes will show up!


# How to find game files:
If you have the itch.io edition of the game, you don't need to bother. The files are what you use to start the game.
If you are using the Steam version then you must:
1. Go to the Among Us page in Steam, inside your library
2. Click on the "Settings" button
3. Click on "Properties"
4. Click on the tab "Local Files"
5. Click "Browse Local Files"
6. Done! There are your files!

# Building the mod yourself
Download [UABE](https://github.com/DerPopo/UABE) and open up your own "level2" file with it.
When it prompts you for a version, select U.2017.03.0f3
Search for the Gameobject named "GameObject Game Room Name"
Click on it, and select "Export Dump"
Open up the dump file, scroll to the bottom, and change "m_is_active: true" to "m_is_active: false"
Click on it in UABE and select "Import Dump"
Choose your newly edited file
Click save (File -> Save)
Take your new level2 file, and replace the old one with it
Done! You have now done this yourself!
