# Battle for Azeroth Resources

**__World Boss Rotation__**<br/>
Warbringer Yenajz >> Dunegorger Kraulok >> Azurethos >> Ji'arak >> Hailstone Construct >> T'zane

Orgrimmar Vision Guide: <https://www.wowhead.com/guides/horrific-vision-of-orgrimmar-strategy-guide><br/>
Stormwind Vision Guide: <https://www.wowhead.com/guides/horrific-vision-of-stormwind-strategy-guide>

Essence Drops<br/>
<https://questionablyepic.com/essence-drop-locations/>

Friendly Alpaca progress check<br/>
`/script print(GetQuestObjectiveInfo(58881, 0, false))`

Script to check if you have various mission table troops unlocked on a certain character:
```lua
/run for k,v in pairs({Ankoan_Tidehunters=55969;Ramkahen_Lancers=58906;Rajani_Sparkcallers=58907})do print(format("%s: %s",k,IsQuestFlaggedCompleted(v) and "\124cff00ff00Unlocked\124r" or "\124cffff0000Locked\124r"))end
```
