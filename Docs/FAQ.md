# Ultimate Skyrim FAQ

<!-- TOC -->

- [Ultimate Skyrim FAQ](#ultimate-skyrim-faq)
- [**Install Questions**](#install-questions)
	- [Does this mod pack support SSE?](#does-this-mod-pack-support-sse)
	- [I’m missing master for HighResTexturePack01-03 or My game CTD after Skyrim Logo](#im-missing-master-for-highrestexturepack01-03-or-my-game-ctd-after-skyrim-logo)
	- [Game doesn't boot when launching SKSE, or receiving a d3dx9_43 error](#game-doesnt-boot-when-launching-skse-or-receiving-a-d3dx9_43-error)
	- [Skyrim has failed to allocate memory! _or_ Possibly running out of memory](#skyrim-has-failed-to-allocate-memory-_or_-possibly-running-out-of-memory)
	- [Can someone help with my load order?](#can-someone-help-with-my-load-order)
	- [I’m manually installing and "Fore's New Idles in Skyrim FNIS 7.4.5" is no longer available on nexus?](#im-manually-installing-and-fores-new-idles-in-skyrim-fnis-745-is-no-longer-available-on-nexus)
	- [Mod X has been updated, can I install that?](#mod-x-has-been-updated-can-i-install-that)
	- [Can I remove/disable mod X?](#can-i-removedisable-mod-x)
	- [Does This mod pack Support other languages?](#does-this-mod-pack-support-other-languages)
- [**Reqtificator Questions**](#reqtificator-questions)
	- [There was no consistency file found](#there-was-no-consistency-file-found)
	- [Automatically allocating memory failed](#automatically-allocating-memory-failed)
	- [It says I am using more than 100 plugins](#it-says-i-am-using-more-than-100-plugins)
	- [The Reqtificator won't start. When I press "Run", MO2 locks up, then unlocks and nothing happens; or MO2 returns a "Directory name is invalid" error.](#the-reqtificator-wont-start-when-i-press-run-mo2-locks-up-then-unlocks-and-nothing-happens-or-mo2-returns-a-directory-name-is-invalid-error)
- [**Gameplay Questions**](#gameplay-questions)
	- [I have this really weird red/green/brown/black graphical issue on the bottom half of my screen](#i-have-this-really-weird-redgreenbrownblack-graphical-issue-on-the-bottom-half-of-my-screen)
	- [My rain splashes are purple/pink!](#my-rain-splashes-are-purplepink)
	- [My Compass has disappeared!](#my-compass-has-disappeared)
	- [Why isn’t my compass showing undiscovered locations?](#why-isnt-my-compass-showing-undiscovered-locations)
	- [How do I start the main quest?](#how-do-i-start-the-main-quest)
	- [Why can't I select the first crafting perk?](#why-cant-i-select-the-first-crafting-perk)
	- [Why is my stamina going down for no reason?](#why-is-my-stamina-going-down-for-no-reason)
	- [Error: Incompatible menu fileMap.swf when opening the map.](#error-incompatible-menu-filemapswf-when-opening-the-map)
	- [My vision is all Blurry/Messed up!](#my-vision-is-all-blurrymessed-up)
	- [Why am I not leveling up!](#why-am-i-not-leveling-up)
	- [The screen randomly went dark shortly after I entered &lt;insert name here>.](#the-screen-randomly-went-dark-shortly-after-i-entered-ltinsert-name-here)
	- [My character is invincible - I get to zero health but don't die!](#my-character-is-invincible---i-get-to-zero-health-but-dont-die)
	- [I tried to learn a spell from a Tome - the book disappeared but I still don't know it](#i-tried-to-learn-a-spell-from-a-tome---the-book-disappeared-but-i-still-dont-know-it)
	- [Why does the NPC dialogue cut out when talking to Aela?](#why-does-the-npc-dialogue-cut-out-when-talking-to-aela)
	- [I'm trying to load my template save and it says my character is dead.](#im-trying-to-load-my-template-save-and-it-says-my-character-is-dead)
	- [My Character takes off of his/her clothes off when swimming](#my-character-takes-off-of-hisher-clothes-off-when-swimming)
	- [What does the MCM guide mean about template saves?](#what-does-the-mcm-guide-mean-about-template-saves)
	- [My game has no grass or has very little grass](#my-game-has-no-grass-or-has-very-little-grass)
	- [Why is everything so expensive in shops?](#why-is-everything-so-expensive-in-shops)
	- [I am getting a lot of stutter / CTD?](#i-am-getting-a-lot-of-stutter--ctd)
	- [When I equip my Lantern/Backpack I get a pouch/book holder appearing in my inventory](#when-i-equip-my-lanternbackpack-i-get-a-pouchbook-holder-appearing-in-my-inventory)
	- [When I equip my Belt items it doesn’t ask me which slot I want to put it in](#when-i-equip-my-belt-items-it-doesnt-ask-me-which-slot-i-want-to-put-it-in)
	- [When I drop items on the ground, they sometimes vanish](#when-i-drop-items-on-the-ground-they-sometimes-vanish)
	- [My Lantern/Tent is asking me where I’d like it equipped](#my-lanterntent-is-asking-me-where-id-like-it-equipped)
	- [How do I re-enable menus pausing?](#how-do-i-re-enable-menus-pausing)

<!-- /TOC -->

---

# **Install Questions**

## Does this mod pack support SSE?

Currently, Ultimate Skyrim is only for Skyrim Class Edition w/ All DLC’s, otherwise known as Skyrim Legendary Edition. A port to SSE is in the works, but still a ways off.

You can buy Legendary Edition from one of these places:

[https://www.humblebundle.com/store/the-elder-scrolls-v-skyrim-legendary-edition](https://www.humblebundle.com/store/the-elder-scrolls-v-skyrim-legendary-edition)

[https://uk.gamesplanet.com/game/the-elder-scrolls-v-skyrim-legendary-edition-steam-key--1057-5](https://uk.gamesplanet.com/game/the-elder-scrolls-v-skyrim-legendary-edition-steam-key--1057-5)

---

## I’m missing master for HighResTexturePack01-03 or My game CTD after Skyrim Logo

If you are experiencing a missing master for HighResTexturePack01-03 the simplest fix is to download and enable the High Res DLC from https://store.steampowered.com/app/202485/Skyrim_High_Resolution_Texture_Pack_Free_DLC/

Alternatively, you can re-run the reqtificator to generate a new Requiem For The Indiferent.esp (RFTI) without the High Res DLC as a master. This will be fixed in the next release.

If you have issues viewing the DL, try this work around https://www.reddit.com/r/ultimateskyrim/comments/galfjk/high_res_texture_pack_info/

---

## Game doesn't boot when launching SKSE, or receiving a d3dx9_43 error

Ensure the following:

1. Check that your Antivirus is not flagging SKSE or any Skyrim related files

2. Install DirectX End-User Runtimes from here [https://www.microsoft.com/en-us/download/details.aspx?id=8109](https://www.microsoft.com/en-us/download/details.aspx?id=8109)

---

## Skyrim has failed to allocate memory! _or_ Possibly running out of memory

If your game CTDs with an error from Crash Fixes saying "Skyrim has failed to allocate memory! Possibly running out of memory...", or it crashes during/after the character creation screen, the most likely cause is a bad ENB installation.

1.  Re-do Step 4 from the Getting Started page https://www.ultimateskyrim.com/getting-started#install-enb-binaries. Make sure all 3 ENB files are present: d3d9.dll, enbhost.exe, and enblocal.ini, and confirm both memory settings in enblocal.ini: VideoMemorySize and ReservedMemorySize. You can use the !memsize [RAM][vram] command on Discosrd to confirm your VideoMemorySize.
2.  If using the Snowfall Weathers mod, re-install the custom ENB files from Step 4 on the Finial Steps page https://www.ultimateskyrim.com/final-steps-express#install-snowfall-enb
3.  If the above doesn't help, try changing the settings in enblocal.ini according to this guide https://wiki.step-project.com/ENBoost (this will disable all the ENB visual effects)

---

## Can someone help with my load order?

The Ultimate Skyrim Support Team cannot assist with this issue as there are too many variables. Your load order should be the one specified on here [https://www.ultimateskyrim.com/master-modlist](https://www.ultimateskyrim.com/master-modlist)

Do not use L.O.O.T or rearrange Ultimate Skyrim’s default mods unless a guide from one of us specifically tells you to!

---

## I’m manually installing and "Fore's New Idles in Skyrim (FNIS) 7.4.5" is no longer available on nexus?

Use version 7.6 Instead.

## Mod X has been updated, can I install that?

No, For stability reasons - only the versions listed on the Ultimate Skyrim Manual Install webpage ([https://www.ultimateskyrim.com/manual-install](https://www.ultimateskyrim.com/manual-install)) are supported.

---

## Can I remove/disable mod X?

Many mods have a Mod Configuration Menu (MCM) where they can be turned off. Also, some mods are considered optional, so they can be disabled or uninstalled in Mod Organizer. For a list of optional mods refer to the official mod list page https://www.ultimateskyrim.com/master-modlist. If you remove an optional mod that has an esp plugin, you will need to run the Reqtificator and possibly Automatic Variants patcher. Refer to the manual installation guide for detailed steps.

---

## Does This mod pack Support other languages?

No and if you try then SKSE crashes from Mod Organizer. You will need to install English Skyrim to play this modpack.

---

# **Reqtificator Questions**

## There was no consistency file found

![Image of consistency error](https://cdn.discordapp.com/attachments/348579495537803274/732081869386022942/unknown.png)

Select “Yes, this is a new game.”

---

## Automatically allocating memory failed

![Image of memory error](https://cdn.discordapp.com/attachments/565772668318646272/740336349202087958/unknown.png)

Your binary path for java is wrong. The Reqtificator error message tells you that you're using 32-bit java instead of 64. Check your paths in _Step 5_[ https://requiem.atlassian.net/wiki/spaces/RS/pages/691470460/Installing+Requiem+with+Mod+Organizer+2+version+3.2.0+and+older](https://requiem.atlassian.net/wiki/spaces/RS/pages/691470460/Installing+Requiem+with+Mod+Organizer+2+version+3.2.0+and+older)

---

## It says I am using more than 100 plugins

![Image of more than 100 plugins error](https://media.discordapp.net/attachments/348579495537803274/731601149848977518/unknown.png)

Select ignore from now on

---

## The Reqtificator won't start. When I press "Run", MO2 locks up, then unlocks and nothing happens; or MO2 returns a "Directory name is invalid" error.

In most cases this is due to a typo in the folder path for the Requiem Skyproc patcher. The path should be: **\<path to your Skyrim installation>\Data\SkyProc Patchers\Requiem**. Many users omit the 's' at the end of "SkyProc Patchers" when creating the folder. Also confirm that the "Start in" path in your MO2 Reqtificator configuration matches the path.

---

# **Gameplay Questions**

## I have this really weird red/green/brown/black graphical issue on the bottom half of my screen

![Image of memory error](https://cdn.discordapp.com/attachments/348579495537803274/594565620096434192/unknown.png)

You probably messed up installing the custom INI files. Make sure you are installing Skyrim.ini and SkyrimPrefs.ini in the `\Ultimate Skyrim 4.0.x\profiles\Ultimate Skyrim 4.0.x (Full)` folder!

---

## My rain splashes are purple/pink!

You need a patch! ([US 406 HF2] Fix for purple/pink rain splashes (Wonders of Weather). Install with MO2 and keep at the end of the mod list on the left side (no esp). in #ultsky-bug-submission channel incase link doesn't work).

[https://discordapp.com/channels/344256550640287755/566419501613318154/680786963615186946](https://discordapp.com/channels/344256550640287755/566419501613318154/680786963615186946)

---

## My Compass has disappeared!

This is intentional. Immersive HUD hides this functionality by default. To make the compass _temporarily_ visible again press the delete key.

-   To make it permanently visible, change the MCM setting in Immersive HUD > Compass Activation > Key Press Toggles. Be sure to change the hotkey away from DEL.

---

## Why isn’t my compass showing undiscovered locations?

iCompass hides the locations by default. To restore your compass to vanilla setting, _uninstall by unchecking_ iCompass in MO2 and rerun Reqtificator.

_Please note, installing or uninstalling mods during a playthrough may break your game and is not recommended_

---

## How do I start the main quest?

Kill a dragon. Make sure you’re set as Dragonborn in the Ultimate Skyrim MCM.

---

## Why can't I select the first crafting perk?

You need a book called The Craftsman’s Manual in your inventory. It can be purchased from most blacksmiths. Most of the Requiem crafting perks require their own books, some of which can be bought while others must be found in the world.

---

## Why is my stamina going down for no reason?

Requiem applies a stamina draining effect when you run, and when you wear heavy armor without the first perk in the heavy armor tree. Running is the normal speed you move at if you aren’t sprinting or specifically holding down the “walk” button. To combat this, make sure to buy food with a “Regenerate 1 stamina per second for X seconds” effect and keep that buff up at all times.

---

## Error: Incompatible menu file(Map.swf) when opening the map.

You missed an MCM setting in SkyUI! Open SkyUI MCM Menu > Advanced > uncheck SWF Version Checking

---

## My vision is all Blurry/Messed up!

This can happen if you eat too many alchemy ingredients too quickly. Find and eat a Nirnroot to remove the effect.

---

## Why am I not leveling up!

You only get experience while sleeping - Take a nap!

---

## The screen randomly went dark shortly after I entered &lt;insert name here>.

This is caused by Darker Dungeons. If you would like to disable this option, open up Darker Dungeons MCM > General Configuration > _untick_ Do Fadeout On Dungeon Entry.

---

## My character is invincible - I get to zero health but don't die!

You need a patch! (`[US 406 HF2] Ashes 0.02 patch v0.6.` in #ultsky-bug-submissions incase link does't work).

[https://discordapp.com/channels/344256550640287755/566419501613318154/679539347854327829](https://discordapp.com/channels/344256550640287755/566419501613318154/679539347854327829)

---

## I tried to learn a spell from a Tome - the book disappeared but I still don't know it

You missed loading SV Mods Preset during your Post-Start MCM Setup. To fix navigate to SV’s MCM menu > Save/Load Preset > FISS > Click ‘Load Preset’.

---

## Why does the NPC dialogue cut out when talking to Aela?

Enhanced Skyrim Factions - The Companions Guild adds new conversation options to NPCs that aren’t voiced. Other NPCs have the same behavior.

---

## I'm trying to load my template save and it says my character is dead.

This happens when you name your character the default name "Adventurer" and are killed by permadeath. To fix delete the .dead file in your `steamapps\common\Skyrim` folder and you will be able to load your save.

---

## My Character takes off of his/her clothes off when swimming

To stop this from happening, open Bathing in Skyrim MCM > Player Animations and _untick_ everything in the sections “Undress Before Bathing - Standard” and “Undress Before Bathing - Extended”

---

## What does the MCM guide mean about template saves?

A template save will be the save game you make _before_ clicking on _Start My Adventure_ in the Ultimate Skyrim MCM menu, you will want to do this so next time you start a new character you won’t have to re-configure everything before the Ultimate Skyrim MCM!

Disclaimer

*Certain elements of a game are *baked* into Skyrim the *exact moment* Start New Game is selected. These types of elements are; Locations of certain items*

---

## My game has no grass or has very little grass

Ensure the following:

1. Make sure that skyrim.ini has the settings `bAllowCreateGrass`, `bAllowLoadGrass`, and `bDrawShaderGrass` set to 1

2. Decrease the `iMinGrassSize=` setting, this will increase grass density(default Skyrim has a setting of 20, 60 is the recommended if you are using a plugin like Verdant)

3. Change `iMaxGrassTypesPerTexure=` Default is 5 and max is 15. (note: the misspelling of texture is a mistake on Bethesda's and should be replicated)

---

## Why is everything so expensive in shops?

You’re Naked - Put some clothes on ya filthy animal!

---

## I am getting a lot of stutter / CTD?

Run Bmxfreestyle’s Stability Guide and follow the recommended tweaks (pinned in #ultsky-support).

[https://discordapp.com/channels/344256550640287755/348579495537803274/729035407282667662](https://discordapp.com/channels/344256550640287755/348579495537803274/729035407282667662)

---

## When I equip my Lantern/Backpack I get a pouch/book holder appearing in my inventory

This is a bug - cause unknown. Although there is no permanent fix, you can _possibly_ solve it by either dropping and buying a new item OR by dropping your item and consoling one in.

---

## When I equip my Belt items it doesn’t ask me which slot I want to put it in

Drop the item, and pick it back up then it will ask you where you would like to place it.

---

## When I drop items on the ground, they sometimes vanish

1. This seems to happen occasionally when dropping items in 1st person view. Try switching to 3rd person before dropping them.

2. if the items are related to one of the following mods; Campfire, Wearable Lanterns, or Bandoliers - Bags and Pouches, this is likely due to a corrupted ID(BAD EDITOR ID when you do player.showinventory)

---

## My Lantern/Tent is asking me where I’d like it equipped

This is due to a bad ID, breaking down your lantern and recrafting it in the crafting ledger usually fixes your lantern, if you have the craftsman perk it's advisable to make your own, if you don't just purchase a new tent from any vendor.

---

## How do I re-enable menus pausing?

SkyrimSouls.ini controls which functions pause the game. You can edit the INI file from Mod Organiser. Right click the `Ultimate Skyrim 4.0.6 hf2` mod in the left pane -> Information -> ini files tab.

---
