# World of Warcraft - Addons - Mists of Panderia (5.4.8 compatible or lower)

[Browse Addons by Category](https://github.com/fondlez/wow-addons-mop/wiki#browse-by-category)

[Browse Addons by Name](https://github.com/fondlez/wow-addons-mop/wiki#browse-by-name)

### Other repositories:

* aglarcz - https://github.com/aglarcz?tab=repositories&q=MoP

### Other addons:

* Ability Team Tracker(ATT): https://github.com/SushiWoW/MoP-ATT
* All The Things: https://github.com/Maczuga/AllTheThings-MoP
* BigDebuffs: https://github.com/ManneN1/BigDebuffs-MoP
* Details: https://github.com/SushiWoW/MoP-Details
* ElvUI - https://github.com/ElvUI-MoP/ElvUI-5.4.8
* Immersion: https://github.com/SushiWoW/MoP-Immersion
* Masque Skins: https://github.com/SFX-WoW/Masque/wiki/Skin-List
* OmniBar: https://github.com/ManneN1/OmniBar-MoP
* Simulation Craft addon: https://github.com/kennipj/SimulationCraft-Addon-5.4.8
* Skada for MoP Revisited: https://github.com/bkader/Skada-MoP/
* WeakAuras2: https://github.com/Maczuga/WeakAuras2-MoP

### Other resources:

* Shared weakauras (WAs) and ElvUI profiles: https://wa.stormforge.gg/
* Simulation Craft app: https://github.com/kennipj/simulationcraft-MoP/releases

## How to install a WoW addon ##

1. If you never launched WoW, double click WoW.exe or otherwise launch WoW.
2. Log in with one of your characters.
3. After login, exit the game completely. In future, to add new addons you will still need to exit the game to see them.
4. Download the addon that you want.
5. Extract it into the WoW `Interface\AddOns` folder, e.g. C:\GAMES\World of Warcraft\Interface\AddOns
6. Double click WoW.exe or otherwise launch WoW.
7. At the Character Select screen, look in the lower left corner for the "AddOns" button.
8. If button is there, click it and make sure all the addons you installed are listed and make sure "Load out of date AddOns" is checked.
9. If the button is NOT there, this means you did not install any addons properly.

Common issue: if you downloaded your addon from a Github site, then you may need to rename the extracted folder and remove "-master" from it.

## Have you installed an addon and it is not showing up in WoW? ##

**Rule 1:** Make sure that in each folder immediately below `Interface\AddOns`, there is a `.toc` file in it. This is the addon folder.  
**Rule 2:** Make sure that this addon folder matches the name of the `.toc` file.

<ins>Example</ins>
* GOOD :white_check_mark: : `Interface\AddOns\LunaUnitFrames\LunaUnitFrames.toc`
* BAD :x: : `Interface\AddOns\LunaUnitFrames-master\LunaUnitFrames\LunaUnitFrames.toc`
