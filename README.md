# Polar Anticheat (Beta)
An anti-cheat for minecraft bedrock edition, features include: Nofly, Nospeed, AntiNBT, Nokillaura, and more!
Check out the Wiki for more info and customization! https://github.com/GlitchyTurtle/Polar-Anticheat/wiki/Polar-Anticheat-Home

# Setup:
To install this anti-cheat to your realm/world you need to install the .mcpack and apply it to your world and it should be fully up and running! It is still in the beta stage, so stuff is still being added to it, and this is by no means the finished version (it will have bugs) - if you want to help me in the making of Polar Anticheat, my discord is Glitch#8024.


<div align="center">
  <img src="https://static.wixstatic.com/media/8ffe73_1c3ca87e2ab2409cbc95b447e74d809d~mv2.png/v1/crop/x_1,y_0,w_499,h_500/fill/w_476,h_476,al_c,q_85,usm_0.66_1.00_0.01/pack_icon.webp" width="500" />
<div align="center">
  <img src="https://img.shields.io/github/downloads/glitchyturtle/Polar-Anticheat/total?color=53a8f1&label=Github%20Downloads"
width="250" />
</div>

<div align="left">

# Full List of usable commands

For a full list of usable commands you can check out the polar client [wiki](

# Hack list

Totem:<br />
+ Checks if a player equips a totem while moving<br />

Fly:<br />
+ Checks if the player is flying or jumping without touching the ground first<br />
+ Teleports the player back down if flying<br />

Illegal Items:<br />
+ Clears illegal items from everybody's inventories.<br />

Jesus:<br />
+ Checks if the player is standing on water/lava blocks.<br />

Speed:<br />
+ Detects if the player is moving much faster than normal (speed 5+)<br />
+ Detects if the player is swimming faster than normal<br />

Killaura:<br />
+ Periodically checks for killaura with invis fake players<br />

NBT:<br />
+ Checks and removes enchanted armor if turned on.<br />

Gamemode:<br />
+ Checks and automantically changes non-staff and non-gamemodeFlagsOff to survival if in creative.<br />

# Customization

+ Using a structure block, you can have a specific structure spawn when the player dies. First, the name to put in a structure block is ```gravestone```, then build whatever you want in it (maybe a cool gravestone, or a spike) and whenever a player dies, the structure will spawn on their death spot. You can even get complicated with this, and summon an armour stand for some cool custom death effects (like lightning or a blood burst)!
+ The same as above works for custom kill structures/effects as well, but this time the name to put in a structure block is ```pvpkillspot```. You are even able to make your own special systems with it. Below is an example of a gravestone, and a item, which will appear after a player is killed, like an extra loot drop!
</div>
<div align="center">
  <img src="https://static.wixstatic.com/media/8ffe73_31c6eff99e7d422186197894a95f3388~mv2.png/v1/fill/w_644,h_337,al_c,q_85,usm_0.66_1.00_0.01/Minecraft%202021-11-12%204_42_16%20PM.webp" width="400" />
  <img src="https://static.wixstatic.com/media/8ffe73_ab8578ec20c949d480f952b55411a6a1~mv2.png/v1/fill/w_644,h_337,al_c,q_85,usm_0.66_1.00_0.01/Minecraft%202021-11-12%204_41_43%20PM%20(2).webp" width="400" />
</div>

+ This addon can detect many different player actions, including moving, gliding, left clicking, sprinting, sneaking, is on ground, levitatin, deaths, kills, what armor they are wearing, if their armor is enchanted, and a few smaller ones. You can use all of these for your own systems, like a system to only let people wearing enchanted diamond armor ender an area. The command for that system (just the chesplate) would be: ```/testfor @a[r=10,scores={detect_chest=5,ench_chest=1}]```
</div>
<div align="center">
  <img src="https://static.wixstatic.com/media/8ffe73_893b3a5b2dc84eeba5742cf6751c36c9~mv2.png/v1/fill/w_644,h_337,al_c,q_85,usm_0.66_1.00_0.01/Minecraft%202021-11-12%204_54_56%20PM.webp" width="500" />
</div>

+ Its possible to create your own actionbar message with commands - if you want to use kills, deaths, or time played use this for reference: ```{"score":{"name": "@s","objective": "kills"}}``` ```{"score":{"name": "@s","objective": "deaths"}}``` ```{"score":{"name": "@s","objective": "timeplayeddy"}},{"text":":"},{"score":{"name": "@s","objective": "timeplayedhr"}},{"text":":"},{"score":{"name": "@s","objective": "timeplayedmin"}},{"text":":"},{"score":{"name": "@s","objective": "timeplayedsec"}}```
</div>
<div align="center">
  <img src="https://static.wixstatic.com/media/8ffe73_e318f5e34aae445d87b642dcc52c2cf1~mv2.png/v1/fill/w_818,h_213,al_c,lg_1,q_85/Minecraft%202021-11-12%205_21_38%20PM.webp" width="500" />
</div>
+ 
+ If you own a server with over 10,000 players, you can request a specific version from me on discord: **Glitch#8024** - I'll usually be happy to help customize!

# Why use it
* The goal is to stop all hackers in the server, so if you have or think you will have a hacker problem, you can use this!
* It's not super sensitive, and will not interfere with your gameplay unless you are blatantly hacking.
* You can turn modules off and on for specific players
* You can edit a ton of stuff
* If you are adept with commands, you can add stuff yourself with customization!
* No false positives - a ton of work has gone into making sure it's impossibly hard to trigger one without actually hacking.
* No command blocks
* No ticking areas
* Easy to use
* Why Not?

# Database Project
* Whenever you find a hacker and have reasonable proof of hacks submit their Gamertag here: https://forms.gle/wVnNHi6reGhNVp9t5
* They will be automatically flagged upon joining and will be banned instantly if automod is turned on.

# Exclusive Features
* Custom gravestones and kill markers easily changed by staff (see customization)
* This is the only addon with global toggle settings (like if you turn a setting on, it will stay on even after you leave and new players join, updating automatically)!

# Q&A
**Q1:** Does the AntiCheat auto-ban?<br />
**A1:** It's customizable: ```/function automod/on``` will turn the automod on, which will autoban players after a certain number of violations (fly ban 3+ violations, item ban 5+ violations, killaura ban 2+ violations, speed ban 6+ violations, NBT ban 2+ violations, totem ban 2+ violations). ```/function automod/off``` will turn the automod off.<br />

**Q2:** Is it customizable?<br />
**A2:** Yes! Check customization section!<br />

# License

**You MAY;**<br />
Modify it<br />
Use it (public/private use)<br />
Using its code (with permission)<br />

**YOU MAY NOT;**<br />
Steal code<br />
Claim it as your own<br />
Sell it<br />
Redistribute it without proper credit<br />
