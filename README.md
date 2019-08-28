# Geoff-The-Galacatic-Bot
Interstellar Rift Discord Bot Read Me/ Guide

Installation Link
-----------------
https://discordapp.com/oauth2/authorize?client_id=556225683819331596&permissions=1409674304&scope=bot

Discord Fleet Manager

Default Prefix "??"
--------------------
??prefix [prefix]  --- changes the prefix

Bot Status
----------
??status --- used only by @Spyros and @Duke for bot spam protection
sets the status of the bots "now playing"

Command List
------------
??help ---Help

??h ---Help

??help [command]  ---help with a specific command

??info --- bot information

??say  ---Bot will say something

??echo  ---Bot will say something

??tag loglocation  --- tells you the IsR Log directory

??tag dumplocation   --- tells you the IsR Dump directory

Rep System
----------
??rep ---Check your rep

??rep @user  ---check other users

+rep @user  --- add a rep point

-rep @user  --- remove a rep point

+rep @user -c   ---- reasons for giving rep  --- add a point and why

??show all   --- shows the entire rep list of users

??del_com [id]   --- deletes comments on rep system if needed for toxic comments

Guide System
-------------
??guide  --- pulls up the steam reactor guide link

??nuke   --- alias ??guide

??rods  ---recipies

??turbines  --- recipies

??heatsinks  --- recipies

Loan System
-----------
??balance [member] [amount] (note)  ---  
this will be used to set a "debt" system for personal use, this is private and will DM the users involved. 

??bal [member] [amount] (note)   ---
Give units to a member.

??viewbal (member)   ---  
View your balance with other members. Leave members empty to see everyone's balance with you

Muster Requests
----------------
??muster  ---- used to request services

example:  ??muster [amount] [name] [location]

??request [member] [item] [amount] [location]   ---  
Ask for resources from a specific user. Please but the name in "" if it's more than one words.

??tribute [amount] [name] [location]   --- 
Log your tribute paid to the vault or custom dropbox. Please put the name in "" if it's more than one word

??deliver [amount] [name] [location]   ---   
Log in a channel what you delivered. Please put the name in "" if it's more than one word

Trade System
-------------
??trade [name] [amount] [place] (--vip) (--buy price) (--sell price)

Add a trade to the trade list. Please put the name in "" if it's multiple words. Use the --vip flag at the end to make this a vip only trade.

??del [trade id]

Delete a trade [id is given after trade is posted]
Creator of trade or @merchant

??set [id] [amount] [buy price] [sell price] [location]

Alter the prices and numbers for a trade
@merchants only command

Emoji Manager
-------------
??addres [name] [emoji]   ---   
Add emoji

??remres [name]   --- 
Remove emoji

??None   ---   
Shows all available emojis

Role Manager
------------
??role (role(s)) (member(s))
Set the roles that can use trade, deliver and request. Leave empty to dissable it.

??vip (roles) (member(s))
Set the VIP role(s). (leave roles empty to dissable it.)

??fleet (role(s)) (member(s))
Set the role(s) for the muster command. Leave empty to dissable it

??merchant (role(s)) (member(s))
Set the role(s) for set, del and list hidden commands

??commissioner (role(s)) (member(s))
Set the role(s) that has total control over it. Leave empty to dissable it.

Admin/Moderators
----------------
??masterlog (#channel)
Set the channel that any action that would modify or change how the bot operates will log in.

??botlist
See all the log channels and what roles have what permissions

??whitelist (role(s)) (member(s)) (channel(s))
Remove members, roles or channels from the blacklist.

??blacklist (role(s)) (member(s)) (channel(s))
Block a user/role to use the bot, or the bot from a certain channel.
Leave everything empty to delete the blacklist.
