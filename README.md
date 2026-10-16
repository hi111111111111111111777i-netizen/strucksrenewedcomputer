# Struck's Renewed Computer V.1 FANTA OS

This is a AI improved mod, if you wish to know what has been fixxed and added, here is what was done.

# Improvement's, and Fixes.

# Bugs:

Mod settings crash: on the Mods page, changing any number setting for another mod always failed with an error. It now saves correctly.
Unsafe startup: the computer screen was set up from a background thread, which Unity doesn’t allow. It now runs on the main thread, with no slowdown.
Double startup: a duplicate copy of the main component could take over and run setup a second time.
Errors leaking into the game: an error in the mod’s virtual stump hook could break the game’s own code. Errors are now caught and logged.
Startup could hang: if the update server didn’t respond, the computer could stay frozen on startup. The check now gives up after 10 seconds.
Wrong numbers on screen: the Color and instrument volume screens could show a value one off from the real one.
Name screen: it was accidentally built on top of the Room screen, so it reacted to room events it had no use for.
Smaller crashes: missing click sounds, an empty page list, or voice chat not being ready yet no longer cause errors.

# Improvements:

The startup screen used to recalculate every frame; now it updates twice a second.
The mod no longer fills your log with a message every second while a warning screen is up.
Fixed a typo (“an public room”) and renamed a couple of joke debug labels.

# How to Install


Go to the latest release and download GorillaComputer.dll v.1

Extract the .zip file into your Gorilla Tag folder, that holds Gorilla Tag.exe 

And Then Launch the game with Utilla

# PS: 

Please Make Sure Beforehand, you have Gorilla Tag installed, Utilla prepared, and a basic understanding of coding/modding.


# Issues

If you find any issues please @FantaLemu in the Gorilla Tag Modding Hub!

# Credits

Struck
Fanta
