# TF2Configs

This is a back-up and (hopefully) contiously updated version of my TF2 configs and custom files.  I use Mastercomfig Ultra as my main custom config.  Mastercomfig differs to other custom configs in that all configs go into tf/cfg/user directory instead of tf/cfg.  I also use Pazer's TF Bot Kicking Plug-in/mod as well as Andy013's Custom Bot Identifying HUD (this mod in particular is pretty essential in the current state of the game).  I use Lawena and AviRecorder to manage and process demo recordings.  I strongly recommend Notepad++ for editing cfgs and scripts, especially with Valve's pack of VDF user defined language files for Notepad++. 

Modules.cfg - this is a modifier cfg to the base defaults that Mastercomfig sets
Autoexec.cfg - Acts as any other autoexec.cfg but is placed in the user directory.  Autoexec adds my global TF2 preferences 
game_overrides.cfg - This works as a reset cfg that runs my global default keybinds
class configs - each of the nine class configs sets keybinds specific to that class
tauntnchatbinds.cfg - this lists all my chat and taunt keybinds along with associated aliases. This keeps the game_overrides.cfg less cluttered
wotsmybinds.cfg - it can be difficult to remember binds for less common commands.  This cfg echos a list of uncommonly used binds in the console
jump.cfg - Most of the jump practicing scripts out there are a bit of a mess and don't work with Mastercomfig in their default state.  This is my modified jump script that works with Mastercomfig.  NB the teleport portion of the script doesn't work if TF2 is launced with Pazer's mod.  If using this script you will need to open TF2 via Steam Launcher.

tf/custom/SuperSkrullHUD folder contains the following mods (minus Pazer's and Andy013's mods)

tf/custom/SuperSkrullHUD/resources contains a couple of small scripts that enlarge and bold the ingame damage and healing numbers for better visability
tf/custom/SuperSkrullHUD/sounds contains my library of custom hitsounds and killsounds.  Remove the prefix of the selected custom sound to activate that audio in-game.  NB only one file each can exist of hitsounds.wav and killsounds.wav

I tweak and modify these files semi-regularly and I will post updates here.  Credits to script sources are in the files if I know who created the scripts that I use/modify.  Let me know if I have used your script, in part or in whole, and I have omitted credit to you and I will correct that. 
