# Our Dota Bot
This is our Dota 2 bot script.

# Useful Sites
 - [A quick guide](http://ruoyusun.com/2017/01/08/dota2-ai-quickstart.html)
  on setting up and using bot scripts. Instead of copying the `bots_example` folder, create the `bots` folder and put the top level files of this repo into that. This can be done when cloning by adding the name `bots` at the end of your clone command (this names the directory git clones into, instead of git using the repos name). For example, in `dota 2 beta\game\dota\scripts\vscripts` run `git clone https://github.com/OurGroupProjects/OurDotaBot.git bots`
  - [Here](https://developer.valvesoftware.com/wiki/Dota_Bot_Scripting) is the official wiki for writing Dota Bot Scripts
  - [Here](https://github.com/Nostrademous/Dota2-FullOverwrite) is a github repo of someone who is doing a full re-write of all the bot logic.
  - If you want to play against the bot, create a custom lobby, join slot 1 of radiant, and set Radiant bots to "none"

# Where to put actual code?
 Put the files that you want Dota 2 to find and run in the top level (here)

# How to run the bot?
 Place all the root files and directories in a new folder named "bots" located in steamapps/common/dota 2 beta/game/dota/scripts/vscripts
 Launch dota, and create a lobby. Set the game mode to 1v1 mid, host the lobby on localhost, and turn on "Fill empty slots with bots". Select "local dev script" in the dropdown, the difficulty doesn't matter. Move yourself into a coach slot, and start the game. If you wish to observe both team' bots, use to console to set "sv_cheats 1", and then "-allvision" in chat.
