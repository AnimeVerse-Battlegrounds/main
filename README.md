# main
Will include most important sections for scripts and modules.

#For understanding files and script nesting:
Roblox has a feature where you can nest a script inside of a script. This is a little akward in github so to repersent that there will be certain folders that also have a regular file named after them.

#How Roblox Scripts Work
Roblox has a client-server model when it comes to managing interactions. Different scripts run on each side. 

Server Scripts (Mostly stored in ServerScriptService) run on the server side. These are used to manage the game's core logic, including gameplay mechanics, player data, and secure transactions. Since these scripts run in a controlled environment on the server, they are secure from tampering by players.

Client Scripts (Mostly in StarterPack and StarterPlayer)  handle user interface updates, input processing, animations, and other aspects that need immediate response or are specific to each player. These scripts can only manipulate parts of the game that are local to the player's device, such as the player's own character. 

Lastly remote events are how Client and Server communicate. To communicate this through github, there are certain files with a title, and contents that are just #RemoteEvent# to indicate that they are a remote event.
