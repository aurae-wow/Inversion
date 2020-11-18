# Legion Resources

### Hidden Artifact Appearance Additional Tints Progress Tracking

Run this script to check progress towards unlocking extra skins for your hidden artifact.
```Lua
/run local q,x,_,a,b = GetAchievementCriteriaInfo,0 for i=1,11 do _,_,_,a,b = q(11152,i) x=x+a end local _,_,_,c,d = q(11153,1) local _,_,_,e,f = q(11154,1) print("Dungeons: "..x.."/"..b) print("WQs: "..c.."/"..d) print("Kills: "..e.."/"..f)
```

_Alternatively_, you can use the following WeakAura to create a text display on your screen.
<https://wago.io/41Tvw7OaW>

_Alternative to that_, you can add the following to your achievement tracker.
```
/run AddTrackedAchievement(11152)
/run AddTrackedAchievement(11153)
/run AddTrackedAchievement(11154)
```

And another script for good measure.
```Lua
/run local g,s,p,d=GetAchievementCriteriaInfo,select,print,0 for i=1,GetAchievementNumCriteria(11152) do d=d+s(4,g(11152,i))end p("Dungeons: "..d.." / "..s(5,g(11152,1)))p("WQs: "..s(9,g(11153,1)))p("HKs: "..s(9,g(11154,1)))
```

---

### Can Someone Explain How to Fill the Armor Stands in Class Halls?
1) All pieces of the same type (cannot mix Healer/DPS/Tank versions of the same teir).
2) Lowest item level version (10-mans, non-heroic, etc).
3) You need to wait for the refund timer to expire, after it expires you might need to relog.
4) You might need to recollect them if you don't remember what pieces, type, or ilvl you had when they were entered into your transmog wardrobe.

For everyone but DKs, DHs, and Monks - tier 1-10

* Tier 1 - 8 pieces
  Molten Core (waist and wrists come from trash mobs!)
* Tier 2 - 8 pieces
  Molten Core (legs), Black Wing Lair (head, shoulders, chest, legs, feet, waist, hands)
* Tier 2.5 - 5 pieces
  Temple of Ahn'Qiraj (AQ40) (quest rewards from dragons right after the first boss)
* Tier 4 - 5 pieces
  Karazhan (head, gloves), Gruul's Lair (shoulders, legs), Magtheridon's Lair (chest)
* Tier 5 - 5 pieces
  Tempest Keep (chest, shoulders), Serpentshrine Cavern(head, hands, legs)
* Tier 6 - 8 pieces*?
  Hyjal Summit (head, hands), Black Temple (legs, chest), Sunwell Plateau (wrist, waist, and feet)
* Tier 7 - 5 pieces (ilvl 200)
  Naxxramas 10-man (head, shoulders, chest, legs), Obsidian Sanctum 10-man (hands)
* Tier 8 - 5 pieces (ilvl 219)
  Ulduar 10-man
* Tier 9 - 5 pieces (ilvl 232)
  Crusaders' Coliseum (Vendor)
* Tier 10 - 5 pieces (ilvl 251)
  Icecrown Citadel (Vendor)

---

**Withered Army Training Scenario**<br/>
<http://www.mmo-champion.com/threads/2064610-Withered-Army-Training?p=42226469&viewfull=1#post42226469>

**Order Hall Champion stuff**<br/>
(New Google Doc) <https://docs.google.com/spreadsheets/d/1eWRWdgQX0_bn3fRqrBwQvGsCUh9LMWOSD74KBzvjuaM/edit#gid=935577117><br/>
(Old Reddit post) <https://www.reddit.com/r/wow/comments/519b0t/what_orderhall_champions_to_deactivate_all/d7a7a1z/>

---

### Hidden Hunter Quest - Trueshot Lodge
1) Purchase 13 `Black Rose` from *Death Hunter Moorgoth*.
2) Speak with *Dark Ranger Velonara*.
3) Speak with *Death Hunter Moorgoth*.
4) Quest pops from *Dark Ranger Velonara*.
5) Adds new item to his vendor window.

---

### World Boss Rotation
* Nithogg
* Soultakers
* Humongris
* Shar'thos
* Flotsam
* Drugon
* Calamir
* Withered J'im
* Levantus
* Na'zak the Fiend
* Ana-Mouz
