# Crazy-Party-Bridge-for-Mac
Crazy Party Bridge provides native speech support for Crazy Party on macOS, using AVSpeechSynthesizer to deliver clean, responsive audio output through a lightweight menu bar app.


# Requirements

macOS 14 or later. Both Crazy Party and Crazy Party Bridge must be in your Applications folder.

# Installation

1. Move both apps to Applications

Select Crazy Party and Crazy Party Bridge, copy with Command C, and move them to your Applications folder with Command Option V.
Note: The game isn't provided here. This is just the bridge. Instructions presume you have the game as well.

2. Remove Crazy Party's quarantine attribute

Open Terminal and run:

xattr -cr /Applications/Crazy\ Party.app

You won't need to do this again unless Crazy Party is updated.

3. Launch

Open Crazy Party Bridge. It appears in your menu bar as CP and installs its components automatically on first launch. Then open Crazy Party. Speech works immediately.

# Voices

CP menu, Voice. All installed English voices are listed. To add more, go to System Settings, Accessibility, Spoken Content, and install from there. Restart the bridge afterwards.

# Speech Rate

CP menu, Speech Rate. Five presets, saves automatically.

# Start at Login

CP menu, Start at Login.

# Save and Deck Backup

CP menu, Export Save and Decks. Choose to export your save file, deck folder, or both, then select a destination. CP menu, Import Save and Decks to restore. You will be asked to confirm before anything is overwritten.

# Troubleshooting

No speech: Quit and relaunch Crazy Party Bridge from your Applications folder. Bridge broken after a game update: CP menu, Reinstall Bridge Files.

# Credits

Crazy Party by Pragma.
Speech bridge by Izzie G
Crazy Party wrapped with Sikarugir
