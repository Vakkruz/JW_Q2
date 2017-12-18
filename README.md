# Bomb Squad: A Quake II mod by Joshua W.

## Gameplay

You are John Quakeman II, a new recruit for bomb disposal. Your job is to carry the bomb, a live grenade, to the end of each level before detonation! 
You can't use or pickup any other weapons or ammo, so you gotta rely on your quick reflexes and navigational skills to survive!

To help you, enemies do slightly less damage on average and you have a few powerups and abilities at your disposal:

* Sneaker [Default Key: **Q**] : Allows you to sneak past goons 100% unnoticed for 20 seconds! **NOTE:** If you use this powerup *after* an enemy has spotted you, you will still be fired at. This is due to a quirk with Quake 2 and the 'notarget' flag.
* Laser [Default Key: **F**] : Very self-explanatory. For those few moments in Quake 2 where you need to actually shoot something to progress.
* Reflector [Default Key: **V**] : Enemy shots get "reflected" right back at them! Doesn't visually reflect it, but the damage gets applied to them instead of you.
* Nuker [Default Key: **E**] : Too many Strogg in your face? Just nuke 'em with the Nuker! Similar to the Reflector, but blasts away anything in your immediate vicinity.
* Jetpack [Default Key: **Hold Ctrl+Space**] : Exactly what it sounds like. Very helpful for skipping huge chunks of a level. Originally based off of [this tutorial](https://www.quakewiki.net/archives/qdevels/quake2/17_1_98.html) from the QDeveLS website with some changes (dramatically lowered thrust velocity/height and added in fuel mechanic)

## Installation

The "Misc Files" folder comes with an autoexec.cfg file, shortcut and compiled .dll file. I have the **GOG** version of Quake 2, not the Steam version, and the install folder for Q2 is on a seperate drive on my computer. This means that the shortcut is pointing to that location. If you want to use the shortcut properly (and assuming you're using the default Steam locations), change the target and "Start In" fields to this:

* Target: "C:\Program Files (x86)\Steam\steamapps\common\Quake II\quake2.exe"
* Start in: "C:\Program Files (x86)\Steam\steamapps\common\Quake II"

Keep the ending parameters (the "+set game") untouched.

When you're all set, create a new folder in the root of your Q2 folder called 'bombsquad' and place the .dll and autoexec file there. Launch the game from your shortcut and you're golden!
