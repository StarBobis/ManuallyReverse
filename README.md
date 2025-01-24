# ManuallyReverse

Manually reverse a game mod to .ib .vb .fmt model that blender can import with python scripts.

Used to Fix Old Broken mods.

# Supported Game
- GI
- HSR
- HI3
- ZZZ

# Usage
- Clone this repository and open it with VSCode, or just edit the reverse_mod_manually.py with notepad.
- Edit reverse_mod_manually.py and follow the comment to fill your mod's folder path and filename.
- Fill the GameName and ConfigFolderPath in GlobalConfig() 
- Then run reverse_mod_manually.py and you will see a Reverse folder in your mod folder.

# D3D11GameType

Mod reverse is rely on D3D11GameType to work, it defines how data organized in buffer files, you can manually add a new json config if all of them can't solve your problem, and welcome to commit back new D3D11GameType json config to this repo,it's in "configs" folder and seperated by game name.

# Ask For Help
https://discord.gg/sMdsGAptss

Notice: Reverse can only talk in our #drama-talk channel.

# Hide In Drak
- The reason you reverse a mod is: Fix Broken Mod (if it not works as you wish in any point,it's broken)
- Most of the mod author won't be happy if you publicly reverse and rip their model from their mod, don't ask why, people just don't get happy.
- You should always ask mod author to try to get the model, that is the easiest way (in most case), if they don't agree, then you will use this scripts in secret (yes, who cares).

# Why
- A question: Why you allow yourself to extract and modify game's model into a mod,but at the same time don't allow other people extract your mod's model to make another mod? 
