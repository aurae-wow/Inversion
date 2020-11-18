# Battle for Azeroth Resources

### World Boss Rotation
* Warbringer Yenajz
* Dunegorger Kraulok
* Azurethos
* Ji'arak
* Hailstone Construct
* T'zane

---

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

---

### Conquest sources outside of instanced PvP:
Daily Supply Chest in Kul Tiras/Zandalar: 50 conquest  
Daily Supply Chest in Nazjatar: 75 conquest  
Battle for Nazjatar: 50 conquest every win  
Battle for Nazjatar weekly quest: 100 conquest  
Call to Arms Kul Tiras/Zandalar zones: 50 conquest  
Call to Arms Nazjatar/Mechagon: 75 conquest  
Call to Arms Uldum/Vale of Eternal Blossoms: 100 conquest  
Against Overwhelming Odds: 50 conquest  
Incursion WQs: 60 conquest (10x3, 15x2)  
