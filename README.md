# MIMIC HUD

I frequently hop from source port to source port (mainly Woof and GZDoom).
I never play using the statusbar, preferring a fullscreen viewport.
In doing this I sometimes feel disoriented because each port has its own HUD style.
If you are familiar with a scenario like this, you might end up enjoy this!

Enter... ***MimicHUD***

A little SBARINFO mod which mimics (duh) the hud of some popular ports.
This way you can feel at home by playing in GZDoom and using the HUD of other ports.



## FEATURES 
- 4 main styles: GZDoom, Eternity, Boom, Crispy
- secondary ammo support (for the normal statusbar too!)
- optional level stats counters
- optional mugshot (Crispy style only)
- custom FONTDEFS, TEXTCOLO



## CHANGELOG 
- 2022.10.26: initial release
- 2022.11.02: added option to replace Arms with Mugshot (Crispy only)
- 2022.11.03: added the Eternity style and stats support, reworked various cvars
- 2022.11.07: removed MaxAmmoCap and ArmorDmgAbsorption indicators, various tweaks
- 2022.11.08: tweaks to level stats support
- 2022.11.16: expanded Mugshot/InventoryItem support, tweaks to the CrispyModern style
- 2022.11.30: removed BoomModern and CrispyModern, tweaked the remaining styles
- 2022.12.01: tweaked the Mugshot/InventoryBar appearance
- 2022.12.03: reworked the GZDoom style
- 2022.12.13: tweaked the "Normal" and "AutoMap" drawing routines
- 2022.12.14: revamped Mugshot/InventoryItem/InventoryBar support
- 2023.01.03: added a background gradient for Mugshot and InventoryBar



## WHAT'S MISSING? 
- level time (I usually rely on the port for this)
- ammo tally (supporting gameplay mods would become a nightmare)
- powerup timers (same as above)



## INSTRUCTIONS 
add this mod at THE END of your load order, to override any pwad-provided hud:

    gzdoom.exe -iwad "DOOM2.WAD" -file "D2TWID.WAD" "BDLITE.PK3" "MimicHUD.PK3"



## CREDITS 
- GZdoom/Crispy/Boom devs for the inspiration
- Hellser for his work on the Boom HUD for his mod Project Aurora
- International Doom devs for some gfx resources
- Eternity Engine devs for some gfx resources



## AUTHOR 
- https://forum.zdoom.org/memberlist.php?mode=viewprofile&u=33863
- https://www.doomworld.com/profile/34495/

