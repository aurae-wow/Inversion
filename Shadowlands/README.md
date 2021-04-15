# Shadowlands Resources

### World Boss Rotation
Oranomonos
Nurgash
Valinor
Mortanis

---

Want to keep using your random mount button, but also have a mount you can use in the Maw?
```lua
/run if GetZoneText()=="The Maw" then CastSpellByName("Corridor Creeper") else C_MountJournal.SummonByID(0) end```
Change Maw mount name as appropriate.

---

You can check your Adventure Campaign progress using the following script:
```lua
/script print(C_CurrencyInfo.GetCurrencyInfo(1889).quantity)```
Alternatively, you can use this weakaura by yours truly.
https://wago.io/GUrBD8_8c

---

A bunch of miscellaneous information can be found here:
https://grueslayers.eu/
