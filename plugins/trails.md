# Trails Instructions
*Tutorial will be updated in future*

### Getting started

Put plugin in your plugins folder 
Reload server 
Done 
/trails - to open trails menu 
/trailsid - set specific trails with command 
Premissions can be found on plugin page **ALSO CONFIG WITH EXPLANATIONS THERE**

*Then more options you use then more it load server. Default config maximum optimized!*

### Why SuperTrails? Spigot have a lot of other trail plugins

- You can use any plugin you want, only you decide. I always tell 
  people if you don't like something don't use plugin. SuperTrails not 
  commercial project 
- Plugin have unique features that can't be found in any other trail plugin 
- Plugin exists more than two years at this moment. And if you look at
   plugin history you will see plugin getting better step by step. It was 
     started as the small, simple project that I made after month java 
     learning to test my skills here was only 12 trails and only a few 
     options. Now this plugin uses big networks and some YouTubers on their 
     servers. 
- Unique Trails
- Still in development, it's mean you may suggest any your idea (But only I decide which ideas will be added)
- Actually free. But if you want... you always can donate to dev to support future development ^_^
- 300+ development hours
- Customizable

### How to disable join message?

UseRaw: true **(Set this to false)** # Enable clickable message on join (Shows only if player have trail.allow permission) 
RawMsg: "&c&oNo trails selected !" # Not clickable line 
RawSelect: "&b&nClick here to open trail menu" # Clickable line to open trails menu 

### Why it says 27/25 trails avalibe

This is multiversion plugin. By default it set to 25 
You can change this in config UnlockedParticle: *'&e!Count!/25'*

### Support for Essential vanish\Vanish No Packet?

SuperTrails don't have Essential vanish support **but** you can set InvisHide to true (Detect when player use invis potion) that's works with Essential 
*Vanish no packet* supported! *HideInVanish: true*

### I don't have some trails

As I said above this plugin support few version (1.8,1.9,1.10,1.11) and it automatically disable all unsupported trails

### I want multiple trails!

SuperTrails have an option for multiple trails **additional** support. But some plugin functions **may not work** with that (Mysql for example). I don't plan to update it right now if you here only for multiple trails I don't recommend my plugin.

### Event

Event option in **beta** . It allow to players open boxes to get trails 
How to use: 
Enable event in config 
Reload server, */supertrails reload* don't work with event!
Plugin will create yml file in SuperTrails to configurate\translate event 
In main trails menu will be added 2 new clickable items 
One to open boxes (by default 1 for every one) another to select trails that they won
/supertrails addpoint   - to give player additional box (You can sell it for example in your shop or for wining in minigames)

### Timed Event

Allow to players open some additional boxes when event is enabled 
/supertrails event   - When time will end players won't be able to open additional boxes

*Timer displays only for player who started event !*

### Modes

You have 2 way how to use modes.
First:
You can set mode by default in config (Mode:0) ; 0 - Default, 1 - Circle
 (Like on hypixel), 2 - NN mode (4 position around player X- X+ Z- Z+) 
Secound: 
Enable mode changer in config 
Then reload server 
In particle trails menu you will can open mode changer menu 

*Few permissions requred! trail.modemenu - Allow to see and open mode menu, trail.mode.circle - Allow use circle mode, trail.mode.nn - Allow to use NN mode*

### Remove trail(s) with command

/trailsid none [player]or/trailsid remove [player]

### I want to remove trails automatically if player lose permission on it

Enable permission checker in config 
CheckPermission: false - Enable timer
CheckPeriod: 100 - Timer priod (100\10=every 10sec premissions for all player will be checked)
CheckOnJoin: false - Check permissions when player join (works even if timer is false)

### What ITA\ITD in trail options means?

This text will be added to item lore if player have premission(ITA) or if not (ITD)IfTrailAllow (Default for all trails) + ITA (or ITD;For specific trail)

### Select block\rain trails using command


/trailsid
Block_Rainbow
Block_Flower
Block_Carpet
Block_Redstone
Block_Wheat
Block_Ore
Block_Clay
========
Rain_Tear
Rain_Blood
Rain_Dia
Rain_Wart
Rain_Gold 
