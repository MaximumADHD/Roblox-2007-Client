# PF94-BLOX CLIENT #

This is a newly discovered build of Roblox, compiled in August of 2007.
To run the client, download this repository as a zip and extract it.

# WARNING: DO NOT USE THIS AS A MULTIPLAYER CLIENT #

This build in its vanilla state is ***EXTREMELY VULNERABLE*** to exploits.
We cannot guarentee your safety connecting to servers running this build, nor will we take any responsibility if anything happens.
You have been warned, be smart and have fun :)!


# Helpful Commands #

* Open uncopylocked places from the website:  
`game:Load("http://www.roblox.com/asset/?ID=PLACEID")`
	
* Reset current place session (unstable)  
`game:ClearContent(true)`

* Create a player:  
`game.Players:CreateLocalPlayer(0)`  

* Load your player's character:  
`game.Players.LocalPlayer:LoadCharacter()`

* Run the game:  
`game:GetService("RunService"):Run()`

# Enabling Bloom and Depth of Field effects #

It was recently discovered that the shader code pertaining to the bloom/dof effects ([that were seen in some mid 2006 screenshots of the game](https://blog.roblox.com/wp-content/uploads/2017/02/Aug20063.png)) are still present in this build, they are just disabled. You can enable them by using a hex editor on the game client exe. I personally use HxD.

Anyway, the offsets for these effects are listed below. You have to go to that offset and set its value from 00 to 01.
* Bloom: `102951`
* Depth of Field: `10295E`

![image](https://devforum.roblox.com/uploads/default/original/3X/0/8/08be34da6f6892b59f4e26db208ce7822d82bdc9.jpg)
