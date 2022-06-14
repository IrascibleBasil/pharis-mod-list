[<<	Back to Preamble](preamble.md)

# Jump to Separator
- [**Assets**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#assets)
- [**Fixes**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#fixes)
- [**UI**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#ui)
- [**OpenMW Lua**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#openmw-lua) 
- [**MWSE**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#mwse) 
- [**Audio**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#audio)
- [**Landmasses**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#landmasses)
- [**Cell Edits & Overhauls**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#cell-edits--overhauls)
- [**Mesh & Texture Replacers**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#mesh--texture-replacers)
- [**Body & Head Replacers**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#body--head-replacers)
- [**Creatures**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#creatures)
- [**Apparel & Weapons**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#apparel--weapons)
- [**NPCs & Companions**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#npcs--companions)
- [**Dialogue**](modlist.md#dialogue)
- [**Levelled Lists**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#levelled-lists)
- [**Gameplay**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#gameplay)
- [**Rebalance**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#rebalance)
- [**Quests**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#quests)
- [**Grass**](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#grass)

----


The mods below are in order and organized by **MO2** separator. Unless stated otherwise the installation process is the same regardless of engine. 
To return to the top click the '**⭡**' next to any separator.

# Assets	[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

These are assets that are used for many mods such as Tamriel Rebuilt, SHOTN, BCOM, etc.

### [Tamriel Data HD](https://www.nexusmods.com/morrowind/mods/44537?tab=description)
Joint asset repository for Tamriel Rebult and Project Tamriel.

Download:
- **Tamriel Data (HD)**
	- [x] Core

If the devs of these projects got a nickel for every time someone forgot to register their BSAs they would have bought Bethesda and made Elder Scrolls VII by now. 

**[OpenMW]** Add the following lines to your `openmw.cfg`
```
fallback-archive=PT_Data.bsa
fallback-archive=TR_Data.bsa
```
**[Original Engine]**  Add the following lines to your **MO2** profile's `Morrowind.ini`
```
[Archives]
Archive 3=PT_Data.bsa
Archive 4=TR_Data.bsa
```

### [OAAB Data](https://www.nexusmods.com/morrowind/mods/49042)
A free-to-use asset repository for the Morrowind Community that adheres to a charming vanilla+ aesthetic.

Download:
- **OAAB_Data**
	- [x] Core
	- [x] Epic Plants Patch
	- [x] SM_Bitter Coast Trees Patch

### [An Addendum to Tamrielic Lore Data](https://www.nexusmods.com/morrowind/mods/50647)
Asset repository for **PikacunoTM**'s An Addendum to Tamrielic Lore mod project. 

Download:
- **AATL_Data**
	- [x] Core
	- [x] High Res Textures

# Fixes		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

### [Patch for Purists](https://www.nexusmods.com/morrowind/mods/45096)
Unofficial patch mod that takes a conservative approach to what is considered a bug, in contrast with some past(and [current](https://www.nexusmods.com/skyrimspecialedition/mods/266)) community patch projects that introduced unnecessary gameplay alterations. If you use only one mod, pick this one.

**Disclaimer: Do not clean this mod with tes3cmd.**

### [Unofficial Morrowind Plugins Patched](https://www.nexusmods.com/morrowind/mods/43931)
An attempt to fix the many issues present in Bethesda's original Official Plugins. Includes fixes for all of the Official Plugins, and offers merged and compatibility options as well.

Download:
- **Main File**
	- [x] adamantium armor compatibility

If you want to use the Siege at Firemoth official plugin use the one from **BCOM - Patches**.

### [Expansion Delay](https://www.nexusmods.com/morrowind/mods/47588)
Fixes Bethesda's scuffed expansion integration, that assumed you had already completed the main quest as soon as you took a nap in Seyda Neen, by appropriately delaying the Dark Brotherhood attacks (for Tribunal) and limiting intrustive dialogue topics to a few NPCs (Bloodmoon).

### [Dubdilla Location Fix](https://www.nexusmods.com/morrowind/mods/46720)
Relocates Dubdilla to where it was most likely originally intended to go and where the voiced dialogue sends you.

### [Divayth Fyr Puzzle Fixed](https://www.nexusmods.com/morrowind/mods/45155)
Fixes multiple issues with the Corprusarium puzzle.

Download:
- **Main File**
	- [x] PfP

### [Adamantium Ore Fix(PFP Edit)](https://github.com/Sigourn/morrowindsharp/blob/master/mods/Adamantium%20Ore%20Fix%20(PfP%20Edit).7z)
Fixes the adamantium ore in Tribunal by allowing the player to find the exact amount of Adamantium Ore needed (45) in the existing twenty Raw Adamantium rocks.

Mod originally made by [**Half11**](https://www.nexusmods.com/morrowind/mods/47068), **Patch for Purists** changes forwarded by **Sigourn**.

### [Quest Skill Reward Fix](https://www.nexusmods.com/morrowind/mods/48269)	**[*Original Engine Only*]**
This mod makes the game treat skill increases from quests as if there were raised via normal means.

# UI	[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

### [TrueType Fonts for OpenMW](https://www.nexusmods.com/morrowind/mods/46854)	**[*OpenMW Only*]**
This will make the text in-game much sharper and easier on the eyes, installed outside of **MO2**.

Place everything from the ```Fonts``` folder into ```"C:\"your OpenMW directory"\resources\mygui"```

### [Better Readable Beauty Font](https://www.nexusmods.com/morrowind/mods/49201?tab=description) **[*Original Engine Only*]**
Texture edit of Hrnchamd's Better Dialogue Font, completely reworking the Morrowind vanilla letters.

### [Better Daedric Font](https://www.nexusmods.com/morrowind/mods/44540)	**[*Original Engine Only*]**
A high resolution replacement for the Daedric font used in scrolls.

Incorrectly packaged, take ```daedric_font.fnt``` and ```daedric_font_obw.tex```, put them in a folder named ```Fonts```, and install.

### [Kezyma's UI Remastered](https://www.nexusmods.com/morrowind/mods/48987)

<details>	<summary>Alternatives</summary>

- [Morrowind UI Revamped](https://www.nexusmods.com/morrowind/mods/43922)
- [Skyrim UI Overhaul for Morrowind](https://www.nexusmods.com/morrowind/mods/43039)

</details>

### [Morrowind Enhanced Textures - UI](https://www.nexusmods.com/morrowind/mods/46221)
HD UI textures, recommended for high DPI displays.

### [De-outlandered main menu and Daedric UI textures](https://www.nexusmods.com/morrowind/mods/46805)
High quality main menu replacer.

### [RFD's Splash Screens](https://www.nexusmods.com/morrowind/mods/47400)
Well made, minimalist splash screens. (thanks **RFD**)

<details>	<summary>Alternatives</summary>

- [Lovely Loading Screens](https://www.nexusmods.com/morrowind/mods/42313)
- [HD Concept-art splash screen and main menu](https://www.nexusmods.com/morrowind/mods/43081?tab=posts)
- [Morrowind Screens Redone](https://www.nexusmods.com/morrowind/mods/46259)

</details>

### [Faithful HD Cursors](https://www.nexusmods.com/morrowind/mods/50764)
Vanilla-style HD Cursor, recommended for high DPI displays.

<details>	<summary>Alternatives</summary>

- [The Kagrenac's cursors](https://www.nexusmods.com/morrowind/mods/48627)

</details>

### [Better Morrowind Crosshair](https://www.nexusmods.com/morrowind/mods/50873)
What the title says.

### [Big Icons](https://www.nexusmods.com/morrowind/mods/49662)
High resolution Icon replacer that makes icons look much sharper, recommended for high DPI displays.

### [Magic Icons(Sigourn Edit)](https://www.nexusmods.com/morrowind/mods/50223)
Replaces the magic icon used for enchanted items in your inventory.

# OpenMW Lua		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)	**[*OpenMW Only*]**

**Disclaimer: Lua is currently only available on 0.48 Dev builds and breaking changes are a possibilty**

### [Attend Me](https://www.nexusmods.com/morrowind/mods/51232)
Follower HUD and automatic teleportation.

### [Protective Guards(OpenMW)](https://www.nexusmods.com/morrowind/mods/46992)
Makes guards protect the player from hostile NPCs.

### [Pursuit(OpenMW)](https://www.nexusmods.com/morrowind/mods/50271)
Allows enemies to follow the player through load doors.

# MWSE	[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)	**[*Original Engine Only*]**

### [Actually Unlimited Skeleton Key]()
Makes the Skeleton Key actually have unlimited uses.

### [Alchemical Knowledge](https://www.nexusmods.com/morrowind/mods/49036)
MWSE-lua mod, which fixes gameplay and interface inconsistencies in alchemy menu, provides it with built-in effect filter and implements Skyrim-like system for remembering ingredient effects.

### [Assetless No Glow](https://www.nexusmods.com/morrowind/mods/47925)
Pluginless *and* assetless no-glow. Use less memory, get some frames back, and be more compatible!

### [Better Buoyancy](https://www.nexusmods.com/morrowind/mods/48929)
Adds new controls for swimming and levitating. Use the jump key to float upwards, and the sneak key to sink downwards.

### [Better Questlist](https://www.nexusmods.com/morrowind/mods/48272)
Allows highlighting and hiding quests in the Journal questlist. Shift-Click on a quest to highlight it, Shift-Click again to hide and Shift-Click a third time to return to normal.

### [Book Pickup](https://www.nexusmods.com/morrowind/mods/46625)
Enables picking up books by default, instead of opening them. This can be disabled by holding shift. The behavior can be inverted using the mod config menu.

### [Caius Gives You a Cover Story](https://www.nexusmods.com/morrowind/mods/50732)
Ever feel like you don't have any direction on what to do with your character before you're ready to tackle the main quest? With this mod, Caius will recommend you factions to join based on your skills the first time you ask about orders.

### [Cheat Menu](https://www.nexusmods.com/morrowind/mods/47143)
Cheat menu in MCM. 

For testing not cheating, you n'wah.

### [Class-Conscious Character Progression (CCCP)](https://www.nexusmods.com/morrowind/mods/48110)
An MWSE leveling mod that implements most features of Galsiah's Character Development.

<details>	<summary>Alternatives</summary>

- [MULE - Mort's Ultimate Leveling Experience](https://www.nexusmods.com/morrowind/mods/47452)

</details>

### [Companion Health Bars MWSE Lua Script](https://www.nexusmods.com/morrowind/mods/46136)
Adds health bars for your companions and summoned creatures to the HUD.

### [Companion Stop](https://www.nexusmods.com/morrowind/mods/50061)
Stops all player followers with a single keypress.

### [Continue](https://www.nexusmods.com/morrowind/mods/45952)
Adds a continue button to the main menu, to instantly load your most recent save.

### [Controlled Consumption (Greatness7 - Sigourn - Necro Edit) 1.3.2](https://www.nexusmods.com/morrowind/mods/49232?tab=description)
Adds a 5 second cooldown for potion and ingredient consumption. Includes Necrolesian's Vanilla NPC Style module tweak, which fixes a problem with the module's use of an in-game timer.

### [Creeping Blight](https://www.nexusmods.com/morrowind/mods/47904)
Changes weather chances, including an increasing chance of blight throughout Vvardenfell before the Main Quest is complete.

Download:
- **Creeping Blight - MWSE Version**

### [Doors Anti Stuck](https://www.nexusmods.com/morrowind/mods/50931)
Avoid actors getting stuck while opening doors.

### [Dwemer Lightning Rods](https://www.nexusmods.com/morrowind/mods/50236)
With this mod, if you visit a dwemer ruin during a thunderstorm, you'll be greeted by blinding flashes as lightning strikes the steamstack lightning rods from the vanilla game. But be careful not to get too close lest you be shocked!

### [Easy Escort](https://www.nexusmods.com/morrowind/mods/45712)
Ensures that your followers get warped to you if they get too far away. Compatible with any follower from any mod, without any special script attached to that NPC. Absolutely essential mod.

### [Enchant Capacity Rebalance](https://www.nexusmods.com/morrowind/mods/48742)
Adjusts the enchant capacities of weapons, armor and clothing for balance and consistency.

### [Expeditious Exit](https://www.nexusmods.com/morrowind/mods/45634)
This mod is for people who seem to have issues crashing or losing mouse control on exit. By hijacking the exit buttons, this mod will force the game to exit.

### [Fortify MAX](https://www.nexusmods.com/morrowind/mods/49825)
Causes Fortify Magicka and Fortify Fatigue to affect the maximum as well as the current stat.

### [Give or Take](https://www.nexusmods.com/morrowind/mods/50716)
Adds "Give" and "Take" buttons to any suitable actor/container, so you can easily move (all/all filtered) things in and out with Lua speed.

### [GMST Menu](https://www.nexusmods.com/morrowind/mods/46428)
Edit literally every GMST in the game, while you're in the game!

### [Hotkeys Extended](https://www.nexusmods.com/morrowind/mods/48055)
Expands the vanilla Quick Menu by adding different hotkeys for holding or double tapping a button and/or when holding a specific button. All hotkeys use the same keys as in vanilla. In total there can now be 81 different hotkeyed items/spells.

### [Hot Quests](https://www.nexusmods.com/morrowind/mods/48976)
Hotkeys for journal Quests and Topics.

### [HUD Weapon Charge](https://www.nexusmods.com/morrowind/mods/47962)
Adds a fillbar that shows the currently equipped weapons charge under the weapon condition bar on the HUD.

### [Just Drop It](https://www.nexusmods.com/morrowind/mods/49557)
Dropped items and corpses are automatically positioned and oriented to align with the ground.

### [Kill Command](https://www.nexusmods.com/morrowind/mods/46723)
Adds a configurable hotkey that will send all companions to attack whatever you are currently looking at.

### [Less Lame Leveled Spawns](https://www.nexusmods.com/morrowind/mods/51059)
This mod aims to fix some inconsistencies with how leveled creatures are spawned.

### [Loading Doors Lock Tune](https://www.nexusmods.com/morrowind/mods/46094)
Automatically synchronizes linked doors locked/unlocked state on activate, lock/unlock by spell, unlock by lockpick, key. Makes loading doors play close sound a short time after opening.

### [Magicka Based Skill Progression -- MWSE-Lua Edition](https://www.nexusmods.com/morrowind/mods/48330)
Spell casting skills advance based on the amount of Magicka spent, rather than the number of spell casts.

### [Magicka Expanded](https://www.nexusmods.com/morrowind/mods/47111?tab=description)
A lua-based framework for creating new, fully functional magic effects. Currently adds 109 new magic effects.

Download:
- **Main File**
	- [x] Framework
	- [x] Rescource Pack
	- [x] Lore Friendly Pack

### [Matching Manuscripts](https://www.nexusmods.com/morrowind/mods/51132)
Dynamically changes the book menu to make the book cover match the actual book being read.

### [Menus Hider on Item Select - MWSE](https://www.nexusmods.com/morrowind/mods/50974)
n OpenMW, when you select an item in your inventory, the Magic, Stats and Map menus automatically hide when your mouse hovers them to not obstruct your view when placing said item into the game world.

This MWSE mod allows that functionality to be used with the Vanilla exe.

### [MM - Enhanced Detection](https://www.nexusmods.com/morrowind/mods/47480)
The third entry in the Magic Mechanics series, this mod adds new Oblivion-inspired visual effects and mechanics for the vanilla detection magic effects, as well as adds 7 new magic effects.

### [MM - Enhanced Invisibility]()
The 5th entry in the Magic Mechanics series. Using invisibility now changes the way you view the world. Instead of only becoming transparent, you see through an ethereal lens that warps and twists the environment around you. Also, under the effect of invisibility, Daedra and undead creatures will seem... different.

### [MM - Enhanced Light](https://www.nexusmods.com/morrowind/mods/47672)
The 6th entry in the Magic Mechanics series. The light magic effect has been replaced with a Skyrim-style magelight effect. Using the new magelight effect creates an orb of light that will follow and float around you and other NPCs. Casting the magelight on a target location will create an orb of light at the location for the duration of the spell.

Download:
- **Enhanced Light**
	- [x] Core
	- [x] Optional FPS

### [MM - Enhanced Reflection](https://www.nexusmods.com/morrowind/mods/48956)
This mod adds reflection mechanics to the Reflect, Shield, Fire Shield, Shock Shield, and Frost Shield magic effects for both the Player and NPCs.

### [MultiEnchant](https://www.nexusmods.com/morrowind/mods/51022)
Multi-enchantments will no longer unfairly increase capacity consumption.

### [MWSE Compare Tooltips](https://www.nexusmods.com/morrowind/mods/51087)
This mod adds compare tooltips for looked-at or equipped items against the equipped item of the same category. The mod has multiple MCM options to configure the comparison style.

### [MWSE Hide the Skooma](https://www.nexusmods.com/morrowind/mods/48454)
Automatically hides your drugs so you don't have to dump them on the floor in order to trade.

### [No More Friendly Fire](https://www.nexusmods.com/morrowind/mods/48801)
Stop friendly fire. Player companions can't damage the player, the player can't damage companions, and companions can't damage each other.

### [No Thank You](https://www.nexusmods.com/morrowind/mods/49681)
Adds a cancel button to Temple shrines and Imperial Cult altars.

### [OAAB Dark Temptations](https://www.nexusmods.com/morrowind/mods/49045)
Adds a "Summon Dark Seducer" spell as an additional quest reward for the Sheogorath quest. You will receive the spell upon completion of the quest.

Download:
- **OAAB Scroll Qualities**
	- [x] Icons

### [OAAB Scroll Qualities](https://www.nexusmods.com/morrowind/mods/49045)
Uses the new scroll models in OAAB_Data to automatically replace the models and icons of the enchanted scrolls in the game based on their value using MWSE Lua code.

Download:
- **OAAB Scroll Qualities**
	- [x] Icons

### [Peaceful Pets](https://www.nexusmods.com/morrowind/mods/47956)
Pacifies pets (Tribunal and mod-added) that are not meant to fight.

### [Perfect Placement](https://www.nexusmods.com/morrowind/mods/46562)
Adds interactive placement, rotation and wall mounting of items. Arrange gear, books and anything else you can pick up.

### [Pincushion](https://www.nexusmods.com/morrowind/mods/46862)
The life of a marksman is one of advantage. Distance, time, initiative. But, when it's all over there is no trace of your work. Wouldn't it be satisfying to see your arrows, bolts and darts sticking into men, mer, tavern doors, and signposts alike? This mod is for you. Place an arrow right between their eyes.

### [Poison Crafting](https://www.nexusmods.com/morrowind/mods/45729)
Opens up an entire new facet of gameplay by granting the ability to use potions offensively, as poisons applied to your weapons. Supports all potions, including those added by other mods or crafted by the player. Additionally includes new HUD elements and various other improvements to the alchemy system as a whole.
<!--
### [Putting Power in Willpower (Necro Edit)]()
-->

### [Quick Equip](https://www.nexusmods.com/morrowind/mods/48341)
Holding down a hotkey (default left shift) while clicking an item in your inventory will equip that item instead of picking it up.

### [Rational Names](https://www.nexusmods.com/morrowind/mods/50000)
Makes various changes to item names for more convenient inventory sorting, and enables names to exceed Morrowind's limit of 31 characters.

### [Realistic Archery](https://www.nexusmods.com/morrowind/mods/51473?tab=description)
Arrows and thrown weapons always do damage when they hit a target, but projectiles are less accurate at lower marksman levels, and damage is reduced at close range.

### [Realistic Movement Speeds](https://www.nexusmods.com/morrowind/mods/46248)
Using MWSE Lua, modifies movement speeds when strafing or backpedalling so that they are more realistic. NPCs and player alike will no longer be able to fire volleys of arrows while running backwards to safety. Movement direction is now tactically important.

### [Right Click Menu Exit](https://www.nexusmods.com/morrowind/mods/48458)
This mod provides one simple feature: any menu can be exited by right clicking. This includes dialog and barter menus, any service menus, as well as the main menu, save/load menu etc.

### [Security Enhanced](https://www.nexusmods.com/morrowind/mods/47038)
Using MWSE Lua, adds hotkeys for lockpicks and probes, as well as hotkey cycling options, ordering options, and auto-equip options for activating locked or trapped objects.

### [Selection Details](https://www.nexusmods.com/morrowind/mods/51095)
Displays an additional menu when the console is open, showing information about the currently selected reference. By default, this menu only shows up if you control+clicked on the reference, though this behavior can be changed in the MCM.

### [Seph's HUD Customizer](https://www.nexusmods.com/morrowind/mods/50588)
A MWSE mod that makes almost every element of the HUD customizable to a certain degree.

### [Seph's Inventory Decorator](https://www.nexusmods.com/morrowind/mods/50582)
A simple MWSE mod that adds more information and decorations to inventory item tiles for quicker item management and discovery.

### [Seph's NPC Soul Trapping](https://www.nexusmods.com/morrowind/mods/50744)
A MWSE mod that lets you soul trap NPCs.

### [Shrine Tooltips](https://www.nexusmods.com/morrowind/mods/48275)
Adds tooltips to shrines on hovering over the different options, describing the effects a blessing has.
Includes descriptions for shrines from Tamriel_Data.

### [Silver Tongue](https://www.nexusmods.com/morrowind/mods/49086)
Enhances speechcraft skill via new gameplay mechanics and UI elements.

### [Skills Module](https://www.nexusmods.com/morrowind/mods/46034)
Skills Module is a framework for MWSE+Lua mods that allows you to easily create new skills in Morrowind with just a few lines of code.

### [Smart Intervention](https://www.nexusmods.com/morrowind/mods/50752)
Gives you two ways you can know the closest Intervention spell destination. First one is to remember the destination once you have already visited the place by intervention spells (suggested), second one is to have high enough Mysticism skill to automatically feel the possible destination.

### [Smart Journal](https://www.nexusmods.com/morrowind/mods/47492)
Several new options for journal pages and quests list

### [Smarter Soultrap](https://www.nexusmods.com/morrowind/mods/49121)
Allows soultrap to make more intelligent use of available soul gems, including soul displacement and relocation. Includes optional leveling requirements.

### [Smarter Strike Sounds](https://www.nexusmods.com/morrowind/mods/51084)
This mod improves the logic for selecting an enchantment failure sound. It enables selecting a random effect fail sound, and preventing the same enchantment from playing a sound twice (or more) in a row. As a result, enchantment strike sounds become a lot less spammy, and can provide some variety.

### [Sophisticated Save System](https://www.nexusmods.com/morrowind/mods/45608)
This mod changes how saves are handled by Morrowind. The goal of the mod is to provide more types of autosaves, as well as a rotating list of quicksaves/autosaves so that the player always has a save to go back to.

### [Torch Hotkey](https://www.nexusmods.com/morrowind/mods/45747)
Uses MWSE to create an intelligent hotkey for light sources.

### [Travel Tooltips](https://www.nexusmods.com/morrowind/mods/48306)
Adds tooltips with location descriptions and maps to travel menu.

### [UI Expansion](https://www.nexusmods.com/morrowind/mods/46071)
Expands UI functionality with searching, filtering, and more visual feedback.

### [Useful Bound Armor](https://www.nexusmods.com/morrowind/mods/49829)
Bound armor now uses the normal armor rating formula, taking light armor skill into account, instead of just providing the base rating regardless of skill.


# Audio		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)
<!--
### [Aura]()

### [MUSE]()

### [MUSE Music Expansion - Tomb]()

### [MUSE Music Expansion - Dwemer]()

### [MUSE Music Expansion - Ashlander]()

### [MUSE Music Expansion - Sixth House]()
-->
### [Aura 3.0 - Replacer](https://www.nexusmods.com/morrowind/mods/48255)
Download:
- **Aura 3.0 - Replacer**
	- [x] All Modules

### [Haunted Barrows](https://www.nexusmods.com/morrowind/mods/46826)
Gives Solstheim barrows a unique sound effect to use instead of reusing the "haunted whispers" sound used in vanilla ancestral tombs.

### [Cave Drip](https://www.nexusmods.com/morrowind/mods/43488)
Adds a visual effect to all vanilla cave drip sound emitters.

### [Disable Player Hit Voice](https://www.nexusmods.com/morrowind/mods/46437)
Replaces all hit voices with silence. Entirely up to personal taste but I personally just find them annoying.

### [Immersive Combat Sounds](https://www.nexusmods.com/morrowind/mods/50254)
High quality and realistic sound replacer for weapons and other combat related sounds.

Download:
- **Immersive Combat Sounds - Vanilla**

### [Spell Sounds Enhanced](https://www.nexusmods.com/morrowind/mods/46338)
Vanilla-friendly spell sounds replacer.

### [Nifty Elemental Magic Sounds](https://www.nexusmods.com/morrowind/mods/50240)
Replaces sounds for elemental magic with more distinct, nifty sounds.

### [Shut the Fuck up Cliff Racers](https://www.nexusmods.com/morrowind/mods/46588)
Drastically reduces the frequency of idle Cliff Racer screeches, by editing the kf file of the cliff racer mesh.

### [Less Annoying Shalk Sounds](https://www.nexusmods.com/morrowind/mods/48683)
Pluginless replacer that makes the shalk sound more like a beetle and less like a mad horse.

Download:
- **Less annoying shalk sounds**

### [REPLACER - Ambient Howl Replacer](https://www.nexusmods.com/morrowind/mods/45988)
De-sheeps Vvardenfell. Replaces howl5, howl6, and howl7 (sheep) ambient sounds.

Download:
- **REPLACER - Ambient Howl Replacer**

# Landmasses		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

### [Tamriel Rebuilt](https://www.nexusmods.com/morrowind/mods/42145)
**Tamriel Rebuilt** is a large fan project that aims to complete the developers' original goal of including the full province of Morrowind. 

Download:
- **Tamriel Rebuilt**
	- [x] Core
	- [x] Faction Integration
	- [x] Preview Content
	- [x] Travel Network for Core, Preview, and Vvardenfell
- **Tamriel Rebuilt 21.01 hotfix 1**
	- [x] Core
	- [x] Faction Integration

### [Skyrim Home of the Nords](https://www.nexusmods.com/morrowind/mods/44921)
A project that is working on bringing Skyrim to Morrowind as it was depicted in pre-TES:V sources.

### [Solstheim - Tomb of the Snow Prince](https://www.nexusmods.com/morrowind/mods/46810)
A comprehensive overhaul of Solstheim that aims to improve the graphical fidelity, environmental design, and gameplay of the Bloodmoon DLC to a level that is consistent with modern TES:3 mod projects, such as Tamriel Rebuilt and Project Tamriel.

Download:
- **Main File**
	- [x] Core
	- [x] Solstheim - Tomb of the Snow Prince
	- [x] TOTSP Patches
	- [x] Missing Snow Armor Pieces
	- [x] Fierce Wolf Helms
	- [x] Hide-Like Animal Pelts

Use only one **TOTSP TD Content Integration** plugin, spiders or no spiders.

Hide or Delete:
```
TOTSP_abotBoats.esp
```
### [Landscape Overhaul for The White Wolf of Lokken Mountain](https://www.nexusmods.com/morrowind/mods/48862)
Landscape facelift for an old classic mod, [The White Wolf of Lokken Mountain](https://lovkullen.net/Emma/lokken.htm), that also adds compatibility for **Solstheim - Tomb of the Snow Prince**.

**Important Note: Use only the esm version or you will get doubles.**

Download:
- **Main File**
	- [x] Core
	- [x] Remiros Groundcover addon
	- [x] Bloodmoon Rebalance patch

Hide or Delete:
```
BT_Whitewolf_2_0_HOTV.esp
```
### [Legend of Chemua](https://www.nexusmods.com/morrowind/mods/45253) ([Moved](http://abitoftaste.altervista.org/morrowind/index.php?option=downloads&task=info&id=93&Itemid=50&-Legend-of-Chemua-Moved))
Long ago, there existed a Nord named CHEMUA, who belched blight and made Velothi's glorious clouds excrete bile. His helmet still remains, and Dagoth Ur's minions have found it.

Use the moved version of the plugin linked above for **Tamriel Rebuilt** compatibility.

**Important: Use only the moved plugin or you will get two islands.**

# Cell Edits & Overhauls	[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

### [Guar Stables of Vivec](https://www.nexusmods.com/morrowind/mods/50118)
Adds a guar stables outside Vivec, near the Foreign Quarter.

### [Concept Art Plantations](https://www.nexusmods.com/morrowind/mods/50020)
A concept art-based overhaul of the Arvel and Dren plantations made by the very talented **Duo Dynamico**(**RandomPal** & **Vegetto88**)

Only the assets are needed, use the plugin from **BCOM - Patches**.

Hide or Delete:
```
Concept Art Plantations.esp
```

### [Beautiful Cities of Morrowind](https://www.nexusmods.com/morrowind/mods/49231)
Best city mod there is, I only wish I could endorse it twice. For more information read the Nexus description(challenge: Impossible) and refer to the [linked google doc](https://docs.google.com/document/d/1mO75n7f6X6EH1SmmQ-CmPHvdPbH30Q3OWyn-PDSCnys/edit?usp=sharing) that explains the patches.

Download:
- **Beautiful Cities of Morrowind - BCOM Core**
	- [x] Core
	- [x] Hlaalu Council Hall Plaza - Izy Style
	- [x] Riverside - Stone Dock
	- [x] **[OpenMW]** Plaza Weather Mechanics (MWSE) - Required 
	- [x] **[Original Engine]** Weather Mechanics for (OpenMW) - Required
	- [x] Suran dock expansion & clutter addon
	- [x] White Suran
	- [x] Stav's Mages Guilds
	- [x] Taller Lighthouse
	- [x] Expanded Sadrith Mora Dock
	- [x] Vanilla Style Ghostfence Pillars
- **BCOM - Patches**
	- [x] Patch for Purists Patch
	- [x] Foyada Mamaea Overhaul
	- [x] Improved Inns Expanded
	- [x] Scrolls of the Nine Barriers
	- [x] Concept Art Plantations
	- [x] TR_Travels (Mainland and Preview)
	- [x] Skyrim Home of the Nords Patch
	- [x] Ebonheart Underworks
	- [x] Yet Another Guard Diveresity - RR Cephalopod Armor
	- [x] Bounty Hunter Assignments
	- [x] Ashlander Traders Remastered
	- [x] Ghastly Glowfence Patch
	- [x] Guild of Vampire Hunters
	- [x] Dura_Gra-Bols_House_Reclaimed
	- [x] Glass Domes
	- [x] The Cottage
	- [x] OAAB Pomegranates Patch
- **Beautiful Cities of Morrowind - Project Atlas and GITD Patches**
	- [x] Project Atlas Patch
	- [x] GITD + Atlas
	- [x] Balmora Bridges with bigger arch - Atlas
	- [x] Stav MGO - GITD + Atlas
	- [x] RR Ghostgate Fortress - GITD
	- [x] RR Statue for Shrine of Mount Assarnibibi
	- [x] RR Statue for Holamayan Monastery
- **Beautiful Cities of Morrowind - HD Textures**

### [Glass Domes of Vivec - Moonrain Edition](https://www.nexusmods.com/morrowind/mods/48946)
Download:
- **Main File**
	- [x] Core Visual Assets
	- [x] Glow in the Dahrk Patch - flickering

### [Concept Art Palace(Vivec City)](https://www.nexusmods.com/morrowind/mods/48136)
Makes the palace of Vivec worthy of a god.

Install whatever configuration you want just be sure to get the Glow in the Dahrk patch. I personally dislike the planets floating above the palace so I replaced the mesh with an empty nif, which can be downloaded [**here**](mods/CAP%20-%20Planets%20remover).

### [Baar Dau](https://www.nexusmods.com/morrowind/mods/49456)
Replaces the prison moon with a model made by qwertyasdfgh for Morroblivion, also moves it to a higher position.

<details>	<summary>Alternatives</summary>

- [Prerelease Prisonmoon](https://www.nexusmods.com/morrowind/mods/49627)
- [Meteorite Ministry](https://www.nexusmods.com/morrowind/mods/45506)
- [Baar Dau - Ministry of Truth](https://www.nexusmods.com/morrowind/mods/50877)

</details>

### [Passage of Prayers - High Fane Corridor Overhaul](https://www.nexusmods.com/morrowind/mods/46786)
This mod makes the previously empty high fane corridor a more interesting location.

Download:
- **Main File**
	- [x] Core
	- [x] No dialogue and book edits version

### [Skar Face(Ald-Ruhn)](https://www.nexusmods.com/morrowind/mods/49510)
A full facelift for Skar and Ald'ruhn-Under-Skar.

Download:
- **Main File**
	- [x] Core
	- [x] BCOM Patch

### [Immersive Mournhold](https://www.nexusmods.com/morrowind/mods/49353)
Mournhold Overhaul, includes Distant Mournhold.

### [Nordic Dagon Fel](https://www.nexusmods.com/morrowind/mods/49603)
Lightweight overhaul of Dagon Fel to make it appropriately Nordic in appearance.

### [Dagon Fel Mill Redux](https://www.nexusmods.com/morrowind/mods/50067)
Wonderful revival of [an old mod](https://www.nexusmods.com/morrowind/mods/42981) by **RandomPal**.

### [Telvanni Council House Lounge Room](https://www.nexusmods.com/morrowind/mods/49285)
Adds a new room in the Telvanni Council House where the player, and the other npcs, can relax, sleep and eat.

### [OAAB Tel Mora](https://www.nexusmods.com/morrowind/mods/46177)
OAAB Tel Mora enhances the city of Tel Mora by adding new buildings, new quests, detailing the landscape, and more. It accomplishes all this while staying lore friendly and without (in my opinion) going over the top by making the city too big.

Download:
- **Main File**
	- [x] Core
	- [x] Female Guards

Get the **Arachnophobia Friendly Patch** if you don't like creepy crawlies.

### [OAAB Grazelands](https://www.nexusmods.com/morrowind/mods/49075)
Overhaul of Vos and Tel Vos, the land surrounding them, and the two nearby egg mines, covering a large portion of the northern Grazelands. Additionally includes 16+ new quests with approximately 18,000 words of dialogue.

Download:
- **Main File**
	- [x] Core
	- [x] Remiros Groundcover GL Patch

### [OAAB - The Ashen Divide](https://www.nexusmods.com/morrowind/mods/49047)
Transforms the Ashlands pass between Seyda Neen and Balmora.

### [OAAB - Tombs and Towers](https://www.nexusmods.com/morrowind/mods/49131)
A remake of tombs and velothi towers.

### [Samarys Ancestral Tomb Expanded](https://www.nexusmods.com/morrowind/mods/45612)
An ancient burial lies in ruins outside of Seyda Neen – the few who know of the secrets it holds guard them closely, and the tomb lays all but forgotten.

### [OAAB Dwemer Pavements](https://www.nexusmods.com/morrowind/mods/50237)
Replaces the cobblestone textures outside of all Vvardenfell-based dwemer ruins with a new texture.

Download:
- **OAAB Dwemer Pavements**
	- [x] Core

### [Foyada Mamaea Overhaul](https://www.nexusmods.com/morrowind/mods/46424)
Completely overhauls Foyada Mamaea.

Only the assets are needed, use the plugin from **BCOM - Patches**

Hide or Delete:
```
Foyada Mamaea Overhaul.esp
```
### [Redaynia Restored](https://www.nexusmods.com/morrowind/mods/47646) ([Desquirmified](mods/Redaynia%20Restored%20-%20Desquirmified.7z))
Restores the missing village at Ald Redaynia that is mentioned in dialogue.

Since the hanging slaughterfish squirm around in OpenMW I have provided an edited version that replaces them with the slaughterfish from **OAAB_Data**. Use the edited plugin with the original mod's assets.

The original mod was made by **R-Zero**, all credit goes to them, I just rotated some fish.

### [Justice for Khartag(J.F.K.)](https://www.nexusmods.com/morrowind/mods/49832)
Changes Khartag Point making it the high peak described in the in-game dialogue.

### [The Cottage](https://www.nexusmods.com/morrowind/mods/49660)
This mod adds a cozy little cottage on the outskirts of Gnisis.

Only the assets are needed, use the plugin from **BCOM - Patches**.

Hide or Delete:
```
The Cottage.esp
```
### [Dark Brotherhood Headquarters](https://www.nexusmods.com/morrowind/mods/43022)
This mod redecorates Dark Brotherhoods lair in Old Mournhold.

### [Serandas Family Hearth](https://www.nexusmods.com/morrowind/mods/48056)
Overhauls the interior of Ienis Sarandas' house into an estate more befitting a once-wealthy family.

### [OAAB Shipwrecks](https://www.nexusmods.com/morrowind/mods/51364)
Overhauls all shipwrecks in the base game and moves them to exterior cells so you can drown without being bothered by pesky load doors.

Download:
- **OAAB Shipwrecks**
	- [x] Core

### [Darknut's Greater Dwemer Ruins. Greater Dwemer Interiors](https://www.nexusmods.com/morrowind/mods/45331)
Overhauls the vanilla Dwemer tileset and adds new pieces.

### [Berandas Overhaul](https://www.nexusmods.com/morrowind/mods/48236)
This mod overhauls and slightly expands Berandas, the old Dunmer fortress near Gnisis.

# Mesh & Texture Replacers		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

### [Weapon Sheathing](https://www.nexusmods.com/morrowind/mods/46069)
Makes unreadied weapons appear on the character's hip or back.

**[OpenMW]** Download:
- **WeaponSheathing1.6-OpenMW**
	- [x] Data Files

**[Original Engine]** Download:
- **WeaponSheathing1.6-MWSE**
	- [x] Data Files

### [Weapon Sheathing Additions](https://www.nexusmods.com/morrowind/mods/49616)
A few unique sheaths for weapons that were lacking them.

### [Correct Meshes](https://www.nexusmods.com/morrowind/mods/39348)
Fixes many vanilla meshes.

### [Simply Walking(Remastered)](https://www.nexusmods.com/morrowind/mods/49785)
Improvements to walk and run animations with integrated [Weapon Sheathing Back Position Edit](https://www.nexusmods.com/morrowind/mods/48945?tab=files).

Download:
- **Simply Walking Weapon Sheathing Edition**

### [MCAR](https://www.nexusmods.com/morrowind/mods/48628)
High quality first person animation replacer.

Download:
- **MCAR plus swim animation**
	- [x] Melee combat
	- [x] MCAR (LtR swing (one-handed weapon))

### [Dwemer Mesh Improvement](https://www.nexusmods.com/morrowind/mods/43101)
Replaces models in the Dwemer set.

### [Telvanni Mesh Improvement](https://www.nexusmods.com/morrowind/mods/42343)
Replaces 43 models for the Telvanni set.

### [Telvanni Exterior UV Fix](https://www.nexusmods.com/morrowind/mods/23233)
Corrects the UV mapping on Telvanni exterior models.

### [Telvanni Door Handle](https://www.nexusmods.com/morrowind/mods/43528?tab=files)
Replaces a certain pesky door handle.

### [Imperial Door Fixes](https://www.nexusmods.com/morrowind/mods/47266?tab=description)
UV, vertex color, and texture fixes for several Imperial door meshes. Also includes two optional fixes for modded textures.

Download:
- **Imperial Door Fixes**
	- [x] Core
	- [x] Arkitektora Fix

### [Morrowind Optimization Patch](https://www.nexusmods.com/morrowind/mods/45384)
Fixes tons of mesh errors and improves performance, if you don't have this mod you're doing it wrong.

Download:
- **Main File**
	- [x] Core
	- [x] Weapon Sheathing Patch

### [Mistify](https://www.nexusmods.com/morrowind/mods/48112)
Used only as a replacer for the vanilla mist.

Download:
- **Mistify**
	- [x] Vanilla Mist Replacer

### [RR Mod Series - Better Meshes](https://www.nexusmods.com/morrowind/mods/43266) ([fix](https://www.nexusmods.com/morrowind/mods/46026?tab=description))
Smooth meshes.

Download:
- **RR - Better Meshes V1.4**
	- [x] Main Files
	- [x] Optional - Smaller 0.5 Potions
- **RR - Better Crates and Barrels V1.1**

Install fix linked above.

### [Properly Smoothed Meshes](https://www.nexusmods.com/morrowind/mods/46747) ([flask fix](https://www.nexusmods.com/morrowind/mods/46026?tab=description))
Smooth meshes.

Download:
- **Main File**
	- [x] Core
	- [x] Beaker, Flasks - clear glass
	- [x] Inkwell - cut glass

Install fix linked above.

### [Graphic Herbalism - MWSE and OpenMW Edition](https://www.nexusmods.com/morrowind/mods/46599) ([Graphic Herbalism- Ash Yam Collision Switch](https://www.nexusmods.com/morrowind/mods/49154))
Allows harvesting of organic containers without opening the GUI and getting carpal tunnel playing as an alchemist.

Download:
- **Graphic Herbalism MWSE - OpenMW**
	- [x] Core + Vanilla Meshes
	- [x] Optional - Smoothed Meshes

Install fix linked above.

### [Morrowind Enhanced Textures](https://www.nexusmods.com/morrowind/mods/46221)
High quality upscaled texture replacer, a solid base to add other retextures on top of.

<details> <summary>Alternatives</summary>

- [Intelligent Textures](https://www.nexusmods.com/morrowind/mods/47469)

</details>

### [Glow in the Dahrk](https://www.nexusmods.com/morrowind/mods/45886)
Makes windows glow at night and adds interior sunrays.

Download:
- **Main File**
	- [x] Nord Glass Windows
	- [x] Raven Rock Windows

### [DN Lighted Dwemer Towers](https://www.nexusmods.com/morrowind/mods/51358)
**Glow in the Dahrk** brought to a Dwemer ruin near you! Everyone say "Thanks, Darknut!"

### [Solstheim Graphical Replacer](https://www.nexusmods.com/morrowind/mods/46810)
Download:
- **Solstheim Graphical Replacer**
	- [x] Solstheim - HD Worldspace Graphical Replacer
	- [x] Skyrim-Like Trees
	- [x] Remiros' Groundcover for TOTSP

### [Project Atlas](https://www.nexusmods.com/morrowind/mods/45399)
Replaces many vanilla meshes with atlased ones to reduce draw calls and increase performance in the hardest hitting areas of the game. This mod does not automatically work with all texture replacers but all atlases needed for this mod list are either in **Textures - MET** or **My Atlas Texture Collection**, both of which are just below.

Download:
- **Project Atlas**
	- [x] Core
	- [x] Urns - Smoothed
	- [x] Redware - Smoothed
	- [x] Emperor Parasols - Smoothed
	- [x] Glow in the Dahrk Patch
	- [x] Graphic Herbalism Patch
- **Hotfix 0.7.2**
- **Textures - MET**

### [My Atlas Texture Collection](mods/My%20Atlas%20Texture%20Collection.7z)
Some mods have outdated texture atlases or no atlas at all so I have provided atlases I generated with the Project Atlas BAT files.

### [Vanilla Land](https://www.nexusmods.com/morrowind/mods/45953) ([tx_ma_crackedearth fix](https://www.nexusmods.com/morrowind/mods/47266?tab=description))
2k retexture of all regions in the style of the original game.

<details>	<summary>Alternatives</summary>

- [Landscape Retexture](https://www.nexusmods.com/morrowind/mods/42575#)
- [Tyddy's Landscape retexture](https://www.fullrest.ru/files/tyd_landscape-texture_compilation_1/files?fid=4453)

</details>

### [Lore-Friendly Balmora Suran and Caldera Ground Textures 2k](https://www.nexusmods.com/morrowind/mods/43680)
I prefer these over the versions in Vanilla Land.

### [No Scum](mods/No%20Scum.7z)
I don't like the scum so I replaced them with empty nifs.

### [Swamp Rocks](https://www.nexusmods.com/morrowind/mods/45673)
A highly-detailed rock replacement texture for the one rock used over 3000 times in the Bitter Coast region.

Download:
- Swamp Rocks - Default

### [SM Re-textures Rock and Cave](https://www.nexusmods.com/morrowind/mods/48856)
Retexture the four main types of caves in the game.

### [HD Cavern of the Incarnate](https://www.nexusmods.com/morrowind/mods/46101)
Cavern of the Incarnate retexture.

### [I Lava Good Mesh Replacer](https://www.nexusmods.com/morrowind/mods/49605)
I lava this mod.

### [SM Bitter Coast Tree Replacer](https://www.nexusmods.com/morrowind/mods/49883)
Pluginless replacer for the eight main trees on the Bitter Coast.

### [Vanilla-friendly West Gash Tree Replacer](nexusmods.com/morrowind/mods/44173)
Pick the no billboard leaves option so the leaves don't follow you.

### [Melchior's Excellent Grazelands Acacia](https://www.nexusmods.com/morrowind/mods/51058)
A pluginless replacer for the Grazelands trees inspired by the umbrella thorn acacia species.

### [Remiros' Ascadian Isles Trees 2](https://www.nexusmods.com/morrowind/mods/45779)
Replaces all of the trees in the Ascadian Isles region.

### [Pherim Comberry Bush 2.4](https://www.nexusmods.com/morrowind/mods/42586)
Kills those ugly leaf planes the vanilla comberry plants have.

Download:
- **Main File**
	- [x] Data Files
	- [x] Vanilla Style Textures

### [Pherim's Fire Fern - Plant and Ingredient](https://www.nexusmods.com/morrowind/mods/43568)
A mesh and textures replacer for the Fire Fern plant and the Fire Petal ingredient.

Download:
- **Main File**
	- [x] Default Red

### [Improved Kwama Eggs and Egg Sacs](https://www.nexusmods.com/morrowind/mods/43555)
A mesh and texture replacer for the kwama eggs and egg sacs.

Download:
- **Main File**
	- [x] Data Files
	- [x] Pulsing Animation

### [Epic Plants - Modular](https://www.nexusmods.com/morrowind/mods/46180)
Replaces textures and models of various flora with HQ quality.

Download:
- **Epic Plants - Modular**
	- [x] Ascadian Isles - Grass
	- [x] Ashland - Grass
	- [x] Ashland - Scathecraw
	- [x] Ashland - Trama Root
	- [x] Bitter Coast - 2D Moss
	- [x] Bitter Coast - Grass
	- [x] Bitter Coast - Lily Pad
	- [x] Grazelands - Marshmerrow
	- [x] MWSE and OpenMW GH Patch - Marshmerrow
	- [x] MWSE and OpenMW GH Patch - Scathecraw
	- [x] MWSE and OpenMW GH Patch - Trama Root

### [GH Patches and Replacers](https://www.nexusmods.com/morrowind/mods/46599)
Graphic Herbalism patches.

Download:
- **GH Patches and Replacers**
	- [x] Correct UV Ore + README
	- [x] Pherim's Replacers
	- [x] Pherim Pulsing Kwama
	- [x] Less Epic Plants

The **Project Atlas** patch is outdated, skip it.

Hide or Delete:
```
correctUV Ore Replacer_respawning.esp
```

### [Thickle-Lo - The Succulent Hackle-Lo Mod](https://www.nexusmods.com/morrowind/mods/47502?tab=description)
Hackle-lo leaves are described as "a tasty edible succulent leaf of the Grazelands..." And yet the leaves appear to be flat and not reminiscent of a succulent. This mod edits the plants and ingredients to be thicker.

### [Ingredients Mesh Replacer](https://www.nexusmods.com/morrowind/mods/44067)
Replaces the meshes of some ingredients in the game.

### [Anumaril's Bowled Ingredients](https://www.nexusmods.com/morrowind/mods/48291)
Replaces powder, liquid, and other forms of ingredients that might be difficult to manage with meshes that have them placed in simple wooden bowls.

Download:
- **Bowled Ingredients**
	- [x] Core
	- [x] Optional Ingredients

### [Daedric Intervention - Ingredients](https://www.nexusmods.com/morrowind/mods/46044)
Mesh and texture replacer for Daedric ingredients.

Download:
- **Daedric Intervention - Ingredients**

### [R-Zero's Throbbing Meat - a Corprus Meat Replacer](https://www.nexusmods.com/morrowind/mods/45339)
Replaces corprus meat models with animated, twitching ones ones.

Disgusting, I love it.

### [Imperial Houses and Forts Retexture - Ordo Arkitektora](https://www.nexusmods.com/morrowind/mods/43940)
Retexture for Imperial architecture.

Atlas provided in **My Atlas Texture Collection**.

### [Lysol's Imperial Forts Normal Mapped for OpenMW](https://www.nexusmods.com/morrowind/mods/46413)
High resolution (2K) retexture of the Imperial forts that stays true to the original color palette.

Atlas provided in **My Atlas Texture Collection**.

### [Dry Stone Walls Revamped](https://www.nexusmods.com/morrowind/mods/49069)
Improves dry stone walls by fixing the UVs and getting rid of the ugly rocks.

Download:
- **Main File**
	- [x] UV fixes and smoother - rockless walls

### [Dragon Statue Revisited](https://www.nexusmods.com/morrowind/mods/50561)
Replaces the dragon statue in Ebonheart.

### [Shacks Docks and Ships - Arkitektora of Vvardenfell](https://www.nexusmods.com/morrowind/mods/43520)
New textures for wooden shacks, docks and ships (including rowboats and gondolas).

Atlas provided in **My Atlas Texture Collection**.

### [HD Flags and Banners](https://www.nexusmods.com/morrowind/mods/48853)
HD textures for banners and flags.

### [Hlaalu - Arkitektora Vol.2](https://www.nexusmods.com/morrowind/mods/46246)
Retexture of Hlaalu architecture.

Atlas provided in **My Atlas Texture Collection**.

### [Vivec and Velothi - Arkitektora Vol.2](https://www.nexusmods.com/morrowind/mods/46266)
Retexture of Vivec and Velothi architecture.

The texture atlas is outdated, a new one can be found in **My Atlas Texture Collection**.

<details>	<summary>Alternatives</summary>

- [Vivec Normal Mapped for OpenMW](https://www.nexusmods.com/morrowind/mods/44259)
- [Vivec-Velothi Retextured V3](https://www.nexusmods.com/morrowind/mods/32886)
- [Velothi Retexture](https://www.nexusmods.com/morrowind/mods/45446)

</details>

### [One True Faith - Saints and Frescoes Retexture](https://www.nexusmods.com/morrowind/mods/43810)
Retexture of Tribunal Temple shrines and frescoes.

Download:
- **Saints and Tribunal Frescoes HQ**

### [Ghastly Glowyfence](https://www.nexusmods.com/morrowind/mods/47982)
Parallax mapped and animated ghost fence.

### [RR Mod Series - Morrowind Statues Replacer](https://www.nexusmods.com/morrowind/mods/43348)
Pluginless replacer for Azura and Vivec statues.

Download:
- **Azura Marble**
- **Vivec Statues**

### [Sewers - Arkitektora of Vvardenfell](https://www.nexusmods.com/morrowind/mods/43144)
Retexture of the Vivec sewers.

### [Redoran - Arkitektora Vol.2](https://www.nexusmods.com/morrowind/mods/46235)
Retexture of Redoran architecture.

One of the atlases is outdated, new ones can be found in **My Atlas Texture Collection**.

### [Telvanni Retexture](https://www.nexusmods.com/morrowind/mods/45516)
Retexture of Telvanni architecture.

<details>	<summary>Alternatives</summary>

- [Telvanni - Arkitektora of Vvardenfell](https://www.nexusmods.com/morrowind/mods/43530)

</details>

### [Better Telvanni Crystal](https://www.nexusmods.com/morrowind/mods/50818)
This is a replacer for crystals you can find in Telvanni buildings and some caves.

### [Aesthesia - Stronghold textures](https://www.nexusmods.com/morrowind/mods/46445)
Retexture of Dunmer stronghold architecture.

<details>	<summary>Alternatives</summary>

- [Beyonder's 40K Texture Pack - Ultimate Dunmer Strongholds](https://www.nexusmods.com/morrowind/mods/45830)

</details>

### [Articus Old Stucco 2K Retexture](https://www.nexusmods.com/morrowind/mods/45880)
Retexture of old Dunmer ruins and dwellings.

### [Articus Mournhold 2K Retexture](https://www.nexusmods.com/morrowind/mods/46011)
Retexture of Mournhold architecture.

### [Articus Old Mournhold and Sewers Retexture 2K](https://www.nexusmods.com/morrowind/mods/45769)
Retexture of Old Mournhold and the Mournhold sewers.

### [Articus Clockwork City of Sotha Sil 2K Retexture](https://www.nexusmods.com/morrowind/mods/46149)
Retexture of the Clockwork City.

### [Ruins - Daedric Intervention](https://www.nexusmods.com/morrowind/mods/46044)
Retexture of Daedric ruins.

### [Articus 6th House Dagoth - HD Nightmare Retexture 2K](https://www.nexusmods.com/morrowind/mods/48319)
Sixth House has never been so scary and realistic! This mod adds high quality (2048) textures for House Dagoth. All textures are fully reworked and lore friendly.

Atlas provided in **My Atlas Texture Collection**.

### [6th House - Glowing Things](https://www.nexusmods.com/morrowind/mods/48764)
Adds a glow effect to various Sixth House objects.

### [Full Dwemer Retexture](https://www.nexusmods.com/morrowind/mods/44264)
Full retexture of Dwemeri set - architecture, armor and weapon, robots, including content from Tribunal Expansion, in lore-friendly vanilla-like style.

### [Swappable Texture Signposts](https://www.nexusmods.com/morrowind/mods/46804)
Designed to be the most moddable signpost replacer, these meshes utilize detail and decal textures so different wood, details, and text can be applied with a simple texture swap.

Download:
- **Main File**
	- [x] 1a Simple Signs
	- [x] Tyddy Style Simple Signs

### [Swayland](https://www.nexusmods.com/morrowind/mods/48854)
Pluginless rope bridge replacer with subtle swaying animations. Collision issue prevents dropped items from being picked up near the rope bridges on the original engine, works fine otherwise.

### [Better Waterfalls](https://www.nexusmods.com/morrowind/mods/45424)
New effects and textures for waterfalls.

Download:
- **Main File**
	- [x] Core
	- [x] Tamriel Rebuilt Water
<!--
### [Waterfalls Tweaks](https://www.nexusmods.com/morrowind/mods/46271?tab=posts)
Download:
- **Waterfalls resize only**
-->
### [Crystal Soul Gems](https://www.nexusmods.com/morrowind/mods/48300)
Adds transparency, glowing effect and reflection to soul gems.

Download:
- **Crystal Soul Gems**
	- [x] Data Files
	- [x] Static Glow

<details>	<summary>Alternatives</summary>

- [Soulgem Replacer](https://www.nexusmods.com/morrowind/mods/44117)

</details>

### [Ket's Potions and Beverages Retexture](https://www.nexusmods.com/morrowind/mods/44781)
Vanilla-style texture replacer for potions and beverages.

### [All Books Color-Coded and Designed](https://www.nexusmods.com/morrowind/mods/50536)
Gives books their own unique, customized design and color-codes them by subject.

### [Melchior's Magnificent Manuscripts](https://www.nexusmods.com/morrowind/mods/45626)
Model replacer for all of the vanilla books.

Download:
- **Main File**
	- [x] Core
	- [x] ABCD Patch

### [Old Dwemer Books](https://www.nexusmods.com/morrowind/mods/43339)
Replaces textual descriptions in old Dwemer books from Bamz-Amschend with actual images.

Hide or Delete:
```
Old_dwemer_books_Better_typography.esp
```
<!--
### [Dwemer Plans and Schematics]()
-->
### [Pete's Scroll With Daedric Alphabet](https://www.nexusmods.com/morrowind/mods/47863)
Replacement for the scroll texture, with optional daedric alphabet.

Download:
- **Pete's Scroll**
	- [x] Scroll - 2K
	- [x] Daedric Alphabet Scroll

### [FMI - Caius Big Package](https://www.nexusmods.com/morrowind/mods/47580)
Give Caius Cosades a package worthy of the Grand Spymaster of Vvardenfell.

Not as horny as it sounds.

### [HD Forge](https://www.nexusmods.com/morrowind/mods/46738)
Download:
- **Main File**
	- [x] Data Files
	- [x] Optional Animated Bellows
	- [x] Optional Texture for Glowing Ash
- **HD Bloodmoon Forge**

### [Improved Lights for All Shaders](https://www.nexusmods.com/morrowind/mods/51463)
Adjusts every vanilla light mesh to enhance the effects of other shader and lighting mods.

What would we do without **Hemaris**?

### [Dunmer Lanterns Replacer](https://www.nexusmods.com/morrowind/mods/43219)
- Glow Effect ->  No
- Ashlander Lantern Style ->  More Detailed
- Ashlander Lantern Textures ->  Use my own
- Tamriel_Data ->  Yes

### [Subtle Smoke](https://www.nexusmods.com/morrowind/mods/47341)
Makes it so many smoke effects are much more laid back and easier on the eyes.

### [Remiros' Minor Retextures - Mist Retexture](https://www.nexusmods.com/morrowind/mods/44322)
Improves the texture for the mist used in Ancestral Tombs. The mist is now much smoother and more detailed, as well as less opaque and flat. 

### [Qwerty's Various Graphics - Blood](https://www.nexusmods.com/morrowind/mods/46026)
Realistic blood splatter in high resolution.

### [Skeleton and Metal Sparks blood retexture](https://www.nexusmods.com/morrowind/mods/43359)
Retexture for the two other blood types - Skeleton (white) and Metal Sparks (gold).

### [Magic VFX Retexture by Articus](https://www.nexusmods.com/morrowind/mods/47702)
This mod adds High Quality (512) animated textures for magic effects.

<details>	<summary>Alternatives</summary>

- [Magic Diversity -COMPLETE-](https://www.nexusmods.com/morrowind/mods/43380)
- [FIMs Better Spell Effects](https://www.nexusmods.com/morrowind/mods/37072)

</details>

### [Bound Spells Reforged](https://www.nexusmods.com/morrowind/mods/48750)
Visual overhaul of Bound Spells, aiming at a dark daedric look.

**[OpenMW]** Download:
- **BoundSpellsReforged_OpenMW_v1.03**

**[Original Engine]** Download:
- **BoundSpellsReforged_original_v1.03**

### [Spells Reforged - Elemental Shields](https://www.nexusmods.com/morrowind/mods/50073)
Visual overhaul of Elemental Shield spells, with additional on-hit effects.

### [Spells Reforged - Shield](https://www.nexusmods.com/morrowind/mods/50905)
Replaces Shield spell visual effect.

**[OpenMW]** Download:
- **Shield spell - openMW**

**[Original Engine]** Download:
- **Shield spell - vanilla MW**

### [Pluginless NoGlow Lite](https://www.nexusmods.com/morrowind/mods/43795)
Replaces the horrid plastic wrap enchanted glow with a 4x4 transparent texture.

# Body & Head Replacers		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

### [Better Bodies ZW](https://www.nexusmods.com/morrowind/mods/42395)
Replaces bodies of non-beast races with seamless versions, updated by **ZWolol**.

### [Better Bodies - Hand Fixes](https://www.nexusmods.com/morrowind/mods/47521)
This mod fixes the weird hand hand animations in better bodies.

### [Westly's Faces Refurbished](https://www.nexusmods.com/morrowind/mods/51214)
Westly's wonderful head replacer touched up and brought more in line with vanilla. Coverage for **Tamriel Rebuilt** is currently being worked on.

Download:
- **Westly's Faces Refurbished**
- **Westly's Faces Refurbished - TR_Data**

### [Color Tweaked Westly's BB Textures](mods/Color%20Tweaked%20Westly's%20BB%20Textures.7z)
Full credit goes to Westly for creating these textures, I simply tweaked the color of a few of them to match **Westly's Faces Refurbished**.

### [New Beast Bodies by Liztail](https://www.nexusmods.com/morrowind/mods/47678)
Replaces bodies of beast races with seamless versions. For this list we'll only be using the Khajiits from this mod.

Hide or Delete:
```
New Argonian Bodies - Clean.esp
```

### [Improved Argonians](https://www.nexusmods.com/morrowind/mods/45918)
Mesh and texture replacer for Argonians. Compatible with Tamriel Rebuilt.

### [Pluginless Khajiit Head Pack](https://www.nexusmods.com/morrowind/mods/43110)
Pluginless replacer of vanilla Khajiit heads.

Download:
- **Pluginless Khajiit Head Pack - Whiskers Version**

### [Pluginless Khajiit Head Pack - Vampires](https://www.nexusmods.com/morrowind/mods/43795)
Vampire heads from **Ashiraniir**'s full Khajiit Head Pack that were omitted from the pluginless version for some reason.

# Creatures		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

### [Divine Dagoths](https://www.nexusmods.com/morrowind/mods/45536)
Pluginless replacer for Dagoth Ur and his brothers, with tweaked body proportions and shadow meshes, new HD particles, and corpse models.

Download:
- **Divine Dagoths**
	- [x] Core Files
	- [x] No Halo Glow
	- [x] No Halo Sigils

Hide or Delete:
```
Bob's Diverse Dagoths - DNGDR - Hostile Gilvoth.esp
Bob's Diverse Dagoths - DNGDR.esp
Bob's Diverse Dagoths - Hostile Gilvoth.esp
Bob's Diverse Dagoths.esp
Unique Dagoth Brandy & Amulet.ESP
```

### [Divine Vivec](https://www.nexusmods.com/morrowind/mods/46342)
Pluginless replacer for Lord Vivec.

Download:
- **Divine Vivec - Blank Flame and Spark Textures**
- **Floating Vivec**

<details>	<summary>Alternatives</summary>

- [Vivec Remade](https://www.nexusmods.com/morrowind/mods/50317)

</details>

### [Better Almalexia](https://www.nexusmods.com/morrowind/mods/23388)
An improved Almalexia model using Better Bodies.

This mod comes with a few splash screens that,while they fit well with vanilla, stand out when used alongside high-resolution modded splashes, for this reason I recommend deleting the ```Splash``` folder.

### [By Azura](https://www.nexusmods.com/morrowind/mods/50567)
An overhaul to the appearance and animations of Azura, Prince of Moonshadow.

Download:
- **Main File**
	- [x] Core
	- [x] High Res Textures
	- [x] Raw Animation Frames

<details>	<summary>Alternatives</summary>

- [Azura Prince of Moonshadow - fixed](https://www.nexusmods.com/morrowind/mods/45379?tab=posts)

</details>

### [Vanilla friendly creatures and undeads expansion](https://www.nexusmods.com/morrowind/mods/48818)
Download:
- **Main File**
	- [x] Core
	- [x] Glowing Netch and Netch Betty
	- [x] Daedric creatures use bound weapons

### [Daedric Intervention - Creatures](https://www.nexusmods.com/morrowind/mods/46044?tab=files)
This mod is poorly packaged so you will have to take the meshes and textures files from each subfolder and combine them.

### [4thUnknowns Creatures Morrowind Edition](https://www.nexusmods.com/morrowind/mods/50137)
Download:
- **CreaturesMeshes**
- **CreaturesTextures**

### [Qwerty's Various Graphics - Atronachs Textures](https://www.nexusmods.com/morrowind/mods/46026)
New high resolution particles for Atronachs.

Download:
- **Atronachs Textures**

### [Clannfear Replacer](https://www.nexusmods.com/morrowind/mods/45173)
Download:
- Clannfear Replacer - OpenMW
- Glowing Eyes

### [Scamp Replacer - Glowing Eyes](https://www.nexusmods.com/morrowind/mods/44314)
Download:
- **Glowing Eyes**

### [Spriggans Glow](https://www.nexusmods.com/morrowind/mods/43350)
Download:
- **Main File**
	- [x] MD Replacer

### [Corprus Natives](https://www.nexusmods.com/morrowind/mods/45674)
Replaces Corprus creatures with native versions so they no longer look like outlanders.

### [SM Bonewalker Replacer](https://www.nexusmods.com/morrowind/mods/51030)
Lore\Vanilla-friendly replacer for bonewalkers.

Download:
- **SM Bonewalker Replacer (Vanilla)**

### [Silt Strider](https://www.nexusmods.com/morrowind/mods/48664)
Silt strider replacer.

Download:
- **Silt Strider with new textures without bump**

### [Silt Strider Animation Restored](https://www.nexusmods.com/morrowind/mods/44150)
Restores previously unused Silt Strider animation.

### [Guars replacer - Aendemika of Vvardenfell](https://www.nexusmods.com/morrowind/mods/42521)
Texture replacer for guars.

### [CRAG - color replacer for Aendemika Guar](https://www.nexusmods.com/morrowind/mods/48966)
Guar color replacer for Aendemika of Vvardenfell.

### [Alit replacer - Aendemika of Vvardenfell](https://www.nexusmods.com/morrowind/mods/42520)
Replacer and retexture of alit, using **Hedgehog-12** mesh and **Tyddy's** texture.

### [Kagouti replacer - Aendemika of Vvardenfell](https://www.nexusmods.com/morrowind/mods/42523)
Replacer and retexture of alit, using **Hedgehog-12** mesh and **Tyddy's** texture.

### [PB Cliff Racer Replacer 2.0](https://www.nexusmods.com/morrowind/mods/48978)
This is a mesh and texture replacer for the Cliff Racer.

### [Improved Better Skulls](https://www.nexusmods.com/morrowind/mods/46012)
Download:
- **Main File**
	- [x] Data Files

### [Nix-Hound Replacer 1.0](https://www.nexusmods.com/morrowind/mods/43620)
This is a mesh and texture replacer for the Nix-Hound creature.

### [REPLACER - Scrib Mesh Tweak](https://www.nexusmods.com/morrowind/mods/45988)
Removes the black spots on scrib heads.

### [Pluginless rat replacer](https://www.nexusmods.com/morrowind/mods/43795)
Pluginless replacer of rat model from **HedgeHog12**'s Symphony, with reflect, normals, and detail maps removed.

# Apparel & Weapons		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

### [Better Clothes Complete](https://www.nexusmods.com/morrowind/mods/47549)
A collection of Better Clothes and it's fixes (Tribunal and Bloodmoon included.

Download:
- **Main File**
	- [x] #Data Files

The HD textures will be covered in another mod.

### [Common Shoe Pack](https://www.nexusmods.com/morrowind/mods/46815)
Replacer for 5 of the most commonly used shoes in the game with new models.

### [Better Clothes Retextured](https://www.nexusmods.com/morrowind/mods/47851)
A set of high-res retextures for better clothes. Currently covers all shirts, skirts and pants from the base game - except for the ashlander shirts and pants.

The data files for this mod are one file too deep.

### [Unique Finery Replacer UFR](https://www.nexusmods.com/morrowind/mods/25725)
Gives most special and unique amulets, belts, rings, robes, shoes, and amulets new, unique models.

Use only the no robe plugin, robes will be covered by **Better Robes** and **Robe Overhaul**.

Hide or Delete:
```
UFR_v3dot2.esp
```

### [Tweaked and Optimized Jewelry Meshes](https://www.nexusmods.com/morrowind/mods/48861)
Tweaks and fixes many errors and unoptimized models from **Unique Finery Replacer**, fixes include reducing excessive poly counts, repositioning necklace strings, fixing gaps in the model, and fixing badly stretched textures, among others.

Download:
- **Tweaked and Optimized Jewelry Meshes**
- **Amulet of Arobar fix**

### [Unique Jewelry Redone](https://www.nexusmods.com/morrowind/mods/46151)
Gives all magic rings and amulets in the game a unique model.

### [Necromancer's Amulet - Modern lore style](https://www.nexusmods.com/morrowind/mods/50030)
Replacer for the Necromancer's Amulet modelled after its appearance in the later games.

Download:
- **NecromancersAmulet**

### [Better Robes](https://www.nexusmods.com/morrowind/mods/42773) ([Updated Updated Tamriel Data Patch](mods\Better%20Robes%20-%20Updated%20Updated%20Tamriel%20Rebult%20Patch.7z))
This plugin replaces male robe meshes with smoothed versions (based on NioLiv\'s meshes) and adds female variants.

Download the updated patch for **Tamriel Data** compatibility.

### [Robe Overhaul](https://www.nexusmods.com/morrowind/mods/43748) ([Blank Glow Maps](https://www.nexusmods.com/morrowind/mods/43795))
Replacer for all vanilla robes with new high resolution textures and sometimes tweaked models based on Moranar's work.

Download:
- **Robe Overhaul**

Download the blank glow maps to get rid of the jarring glow effect on some of the robes.

### [Better Morrowind Armor](https://www.nexusmods.com/morrowind/mods/42509)
Download:
- **Better Morrowind Armor ENG basic**

The data files for this mod are one file too deep.

### [Better Morrowind Armor Fixes](https://www.nexusmods.com/morrowind/mods/47920?tab=files)
Download:
- **Main File**
	- [x] Data Files
	- [x] Complete Armor Joints

### [Improved Pauldron Meshes (Vanilla - Better Morrowind Armor)](https://www.nexusmods.com/morrowind/mods/47920?tab=files)
Improved and streamlined meshes for vanilla pauldrons.

### [N'wah's Work Pauldrons](https://www.nexusmods.com/morrowind/mods/49103)
Improved and streamlined meshes for vanilla pauldrons.

### [RR Mod Series - Better Telvanni Cephalopod Armor](https://www.nexusmods.com/morrowind/mods/44837) ([No Back Shell](https://www.nexusmods.com/morrowind/mods/49334))
Only the Assets are needed.

Download:
- **Main File**
	- [x] Main Files

### [Orcish retexture](https://www.nexusmods.com/morrowind/mods/43502)
A retexture of the Orcish armor and tower shield.

### [Improved Nordic Iron Helm Mesh](https://www.nexusmods.com/morrowind/mods/43816)
Mesh replacer for the Nordic iron helm that fixes the wonky shape.

Download:
- **Improved Nordic Iron Helm 1.0-alternate**

### [Ebony Mail Replacer](https://www.nexusmods.com/morrowind/mods/45183)
High quality mesh and texture replacer for the Ebony Mail.

### [Restyled Helmet Replacer](https://www.nexusmods.com/morrowind/mods/51049)
Replaces several vanilla helmet meshes with restyled alternatives.

Download:
- **Restyled Helmets Pick and choose**
	- [x] 

### [Improved Templar Helmet](https://www.nexusmods.com/morrowind/mods/47920?tab=files)
Improved mesh and texture for the templar helmet.

Download:
- **Improved Templar Helmet**
	- [x] Improved Mesh

### [Trollbone Helm Replacer](https://www.nexusmods.com/morrowind/mods/45322)
High quality mesh and texture replacer for the trollbone helm.

### [Improved Shield Meshes](https://www.nexusmods.com/morrowind/mods/47931)
Improved meshes for vanilla shields.

Download:
- **Improved Shield Meshes**
	- [x] Data Files

### [Imperial Legion Shields](https://www.nexusmods.com/morrowind/mods/45041)
High quality mesh and texture replacer for Imperial Legion shields.

### [Iron Mesh Improvements - Uniques](https://www.nexusmods.com/morrowind/mods/34863)
Improved meshes for unique iron weapons.

Hide or Delete:
```
Psy_IronMeshImprove_Uniques_BME.esp
Psy_IronMeshImprove_Uniques_I.esp
Psy_IronMeshImprove_Uniques_E.esp
```

### [Improved Weapon Mesh Compilation](https://www.nexusmods.com/morrowind/mods/50886)
A compilation of many weapon mesh replacers.

Download:
- **Improved Weapon Meshes Compilation**
	- [x] Core
	- [x] Weapon Sheathing Patch
	- [x] Correct Iron Warhammer
	- [x] Patch for Psymon's Iron Mesh Improvements - Uniques
	- [x] Alternative Longsword and Dagger
	- [x] Claymore Wooden Sheath

Thank you to **1Mac** both for putting this together and for telling me about it on Discord. All credit for the included assets of course goes to the original authors(links on Nexus page).

### [Oriental Mesh Improvements](https://www.nexusmods.com/morrowind/mods/29906)
Improved meshes for katanas, tantos, etc.

### [Chitin Weapons retexture](https://www.nexusmods.com/morrowind/mods/47932)
Retexture for chitin weapons.

### [Adamantium Axe Replacer](https://www.nexusmods.com/morrowind/mods/46791)
Mesh replacer for the adamantium axe.

### [Adamantium Claymore Replacer](https://www.nexusmods.com/morrowind/mods/46790)
Mesh replacer for the adamantium claymore.

### [Bonemold Bow Replacer](https://www.nexusmods.com/morrowind/mods/45156) ([Weapon Sheating Patch](https://www.nexusmods.com/morrowind/mods/48891))
Download the patch for **Weapon Sheathing**(link above).

### [Crossbows Enhanced](https://www.nexusmods.com/morrowind/mods/48586)
Used only as a pluginless replacer.

Download:
- **Main File**
	- [x] Core
	- [x] (Optional) Icon Replacer
	- [x] (Patch) Weapon Sheathing

### [PikachunoTMs Mesh Artifact Improvements and Replacers](https://www.nexusmods.com/morrowind/mods/45631)
Replaces a lot of the vanilla (plus Tribunal and Bloodmoon) meshes with scratch-built versions with fixed uvs and better shaping. Includes an optional add-on that provides the Bloodskal Blade with a unique mesh and textures!

Download:
- **Artifact Mesh Improvements 1.1 Update**
- **The Bloodskal Blade**

### [Unique Eltonbrand for Fallen One's Goldbrand](https://www.nexusmods.com/morrowind/mods/43528)
Matches Eltonbrand with **Fallen One**'s Goldbrand replacer, which is bundled in the archive.

Download:
- **Unique Eltonbrand for Fallen One's Goldbrand**
	- [x] Core
	- [x] Eltonbrand
	- [x] Fallen One's Goldbrand Replacer

### [Remiros' Uniques](https://www.nexusmods.com/morrowind/mods/49674)
Gives certain weapons and armors unique models.

### [Animated Staff of Magnus & Iceblade of the Monarch](https://www.nexusmods.com/morrowind/mods/51402)
Download:
- **Animated Staff of Magnus**
- **Iceblade of the Monarch**

### [The Tools of Kagrenac](https://www.nexusmods.com/morrowind/mods/44500)
High quality mesh and texture replacer for Sunder, Keening, and Wraithguard.

### [Unique Weapon - Mephala's Teacher](https://www.nexusmods.com/morrowind/mods/43528?tab=files)

# NPCs & Companions		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)
Feel free to skip the companions if you prefer to travel alone.

### [Kolka the Wolf](https://www.nexusmods.com/morrowind/mods/49765)
Kolka is a trained wolf, found in the Rethan Ancestral Tomb. She's difficult to kill, hard to lose, and can even carry your stuff. She will also fight beside you.

### [Paxon the Pack Rat](https://www.nexusmods.com/morrowind/mods/45669)
This mod adds Paxon the Pack Rat to your game. Paxon will fight by your side and carry your stuff. He can be found at the courtyard of the Census and Excise office, in Seyda Neen.

Download:
- **Paxon the Pack Rat**
	- [x] Paxon the Pack Rat
	- [x] Pack Rat Anti-Swish

### [War Kagouti Companion - Mausi](https://www.nexusmods.com/morrowind/mods/45169)
Take an armored kagouti into battle with you as a companion. Change out her armor to give her different abilities. Send her hunting for rats. Make a friend.

Download:
- **War Kagouti Companion**
	- [x] Core
	- [x] The Ashlanders & Finding the Erabenimsun Patch
	- [x] Tyddy's Kagouti Replacer Aendemika of Vvardenfell

### [Stripes the Cat](https://www.nexusmods.com/morrowind/mods/51086) ([Required](https://mw.modhistory.com/download-24-15599))
An adorable little companion in Caldera that makes cute noises and casts spells.

***You are legally required to download this mod.***

[**Click Me**](https://www.youtube.com/watch?v=5jKZ9KGtee0&ab_channel=CavinWeber)

### [Services Restored](https://www.nexusmods.com/morrowind/mods/47068)
Restores Cinia Urtius, cut master trainer for Medium Armor, and allows Hecerinde to sell Secret Master lockpicks and probes just as he did in the unpatched version of the game.

# Dialogue		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

### [Greetings for No Lore](https://www.nexusmods.com/morrowind/mods/46063)
Replaces the three standard No Lore greetings with over sixty new ones.

### [Djangos Dialogue 1.4](https://www.nexusmods.com/morrowind/mods/47253)
Hundreds of new lines of text dialogue for all NPCs, which helps to remedy the repetition and dialogue fatigue that came with the original game.

### [Djangos Dialogue - Patch for Purists](https://www.nexusmods.com/morrowind/mods/48955)
Forwards **Patch for Purists** fixes to **Django's Dialogue**, patch made by **Alvazir**.

### [FMI - Sane Ordinators](https://www.nexusmods.com/morrowind/mods/47381)
Makes it so Ordinators will not kill you for wearing Indoril armor once you have been named Nerevarine by Vivec, or if you are Master or Patriarch of the Temple.

### [FMI - NotAllDunmer](https://www.nexusmods.com/morrowind/mods/47569)
Not all Dunmer are slavers. Not all Argonians are slaves. Idle dialogue filtering has been improved to reflect this.

### [FMI - Hospitality Papers Expanded](https://www.nexusmods.com/morrowind/mods/46107)
Implements hospitality papers mechanic for Sadrith Mora that is mentioned in dialogue but is not actually present in the vanilla game.

### [FMBP - Michael Michael Michael](https://www.nexusmods.com/morrowind/mods/48598)
Fixes Michael Mack's misreadings of the word "Dunmer" as "Dumbner".

### [FMBP - Greet Service](https://www.nexusmods.com/morrowind/mods/50937)
Uses unused voice dialogue shipped with the game to make service NPCs greet you as though they are really shop keepers, publicans, etc.

### [Idle Talk](https://www.nexusmods.com/morrowind/mods/46948)
Adds over 200 new voice entries for NPCs, mostly using edited original voice files.

# Levelled Lists		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

### [Wares](https://www.nexusmods.com/morrowind/mods/49205)
Wares gives traders more Wares (duh). Includes Wares from other mods (such as **Tamriel Rebuilt**)**. Includes traders in the Mainland.

Download:
- **Main File**
	- [x] Master file
	- [x] TR
- **OAAB Wares**
- **BCOM Wares**
- **Wares for Lokken**

### [OAAB Integrations](https://www.nexusmods.com/morrowind/mods/49045)
Minor mods that integrate assets from **OAAB_Data** into the game.

Download:
- **OAAB Creature Loot**
- **OAAB Levelled Creatures**
- **OAAB Levelled Lists**

### [Expansions Integrated](https://www.nexusmods.com/morrowind/mods/47861)
Integrates much of the content of the Tribunal and Bloodmoon expansions within the rest of the game world.

Use only the **Expansions Integrated - Fewer BM Creatures** plugin.

Hide or Delete:
```
Expansions Integrated.esp
Tribunal Integrated.esp
```

### [Area Effect Arrows Integrated](https://www.nexusmods.com/morrowind/mods/47745)
Integrates the projectiles from the Area Effect Arrows official plugin into vanilla levelled lists.

Hide or Delete:
```
Area Effect Projectiles Integrated (PAR Edit).esp
Area Effect Projectiles Integrated.esp
```

### [Alternate Helmets](https://www.nexusmods.com/morrowind/mods/50713?tab=description)
Adds some shiny new helmets to add visual variation to armour.

# Gameplay		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

### [Mage Robes](https://www.nexusmods.com/morrowind/mods/45739)
**[OpenMW]** Download:
- **Main File**
	- [x] Core
	- [x] Static Add-Ons (OpenMW)

Hide or Delete:
```
Mage Robes - Caldera MG Expanded.ESP
Mage Robes - Dagon Fel Mages Guild.ESP
Mage Robes - Starfires NPC Additions.ESP
Mage Robes - The Hostiles.ESP
Mage Robes - Vivec Guild of Mages Expansion.ESP
```

**[Original Engine]** Download:
- **Main File**
	- [x] Core
	- [x] Automatic Add-Ons (MWSE)



### [Umbra- Blademaster](https://www.nexusmods.com/morrowind/mods/43275)
Overhauls everyone's favorite, death-seeking Orsimer into a truly challenging opponent with scripted behavior and new equipment.

### [Concept Art Daedric Helmets](https://www.nexusmods.com/morrowind/mods/49534)
Adds the missing Daedric Faces from M.K.'s concept art to various Daedric ruins around Vvardenfell.

### [Indoril Ronin](https://www.nexusmods.com/morrowind/mods/50689)
What would happen if an Ordinator found the messages hidden in The Thirty-Six Lessons of Vivec? Would they reject the Tribunal and venerate Indoril Nerevar? Would they believe themselves to be the Nerevarine? This mod currently adds the equipment of an Ordinator that discovered the Foul Murder of the first Hortator.

Download:
- **Indoril Ronin Set**

### [Walkers of Morrowind](https://www.nexusmods.com/morrowind/mods/49889)
Adds pathgrids to roads throughout Vvardenfell so that NPCs with an AIWander package will wander within their cell.

### [Quick Char (Necro Edit)](https://www.nexusmods.com/morrowind/mods/47706)
Quick start mod. One plugin changes your timescale to 6 and the other leaves it at the default, use only one.

### [Companion Friendly Lava](https://www.nexusmods.com/morrowind/mods/50890)
Tweaks vanilla lava script so that lava hurts only the player and not their companions that are not smart enough to avoid it.

### [Dynamic Distant Details](https://www.nexusmods.com/morrowind/mods/51236) **[*OpenMW Only*]**
Makes distant land more responsive to quest progress. No more lingering Ghostfence segments or vanishing player strongholds.

Use only the three stronghold plugins as the Ghostfence one conflicts with **BCOM**.

Hide or Delete:
```
HM_DDD_Ghostfence_v1.0.esp
```

### [Lord's Mail and Morningstars](https://www.nexusmods.com/morrowind/mods/49878)
Fixes two inconsistencies in the game: one concerning the enchantment of Lord's Mail and another concerning the lack of morningstars in the game.

### [Fireflies](https://www.nexusmods.com/morrowind/mods/51443?tab=description)
Adds fireflies around the Bitter Coast and the Ascadian Isles.

# Rebalance		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)
These mods rebalance the expansions as if they shipped with the game on release and makes the Sixth House, properly, the most difficult content in the game. If this sounds unappealing to you simply skip this separator.

**Important Note: Each of these rebalance mods has multiple modular plugins and one full plugin, use only the full version.**

### [Beware the Sixth House (Sixth House Overhaul)](https://www.nexusmods.com/morrowind/mods/46036)
This makes Dagoth Ur, the Ash Vampires, all Dagoths, all ash slaves, corprus beasts, ascended sleepers and every other corprus beast to be incredibly difficult. They have lots of health. They do lots of damage. Their spells hurt, and some even regenerate health.

### [Tribunal Rebalance](https://www.nexusmods.com/morrowind/mods/45713)
This mod rebalances Tribunal as if it shipped with Morrowind.

### [Bloodmoon Rebalance](https://www.nexusmods.com/morrowind/mods/45714)
This mod rebalances Bloodmoon as if it shipped with Morrowind.

### [Beware the Sixth House Tweaks](https://www.nexusmods.com/morrowind/mods/49232)
Fixes a number of inconsistencies with creature edits in **Beware the Sixth House**.

# Quests		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

### [ABCs for Outlanders](https://www.nexusmods.com/morrowind/mods/46692)
Adds a new book "The Ayembedt for Outlanders" to the game and a quest to acquire a copy.

### [A Conjurer's Calling](https://www.nexusmods.com/morrowind/mods/51070)
Follow a short questline to discover the nature of a recluse conjurer's mysterious research and gain magical rewards. Start by stumbling into in his lair on an island in the Azura's Coast region, north of the Grazelands. 

### [A Hermits Request](https://www.nexusmods.com/morrowind/mods/23714)
To the west of Seyda Neen, along the bitter coast, there lives a hermit by the name of Thexn Akaasul. It would seem that Thexn has a series of tasks for any adventurous soul willing to seek him out, though they deal mostly with the necessities of life rather than adventures of the grandiose sort.

### [A Merchant's Whim](https://www.nexusmods.com/morrowind/mods/51068)
A merchant has set up shop outside of Vivec. Talk with him, and after some time he will ask you for some help with a personal matter from his past.

Download:
- **Main File**
	- [x] Core

### [Ancient Foes](https://www.nexusmods.com/morrowind/mods/44705)
To the west and slightly north of Dagon Fel, you'll find a small cottage along the shores of the Sheogorad, where a young Nord spends his days longing for home. Will you help him find what he seeks? Or will you be the instrument of his destruction?

### [Apothecary's Demise](https://www.nexusmods.com/morrowind/mods/44331)
Apothecary's Demise is a quest mod about choice, that starts in the quaint abode in the Ascadian Isles. Upon entering this nice Apothecary's Abode, you are greeted with a dead apothecary, and a note that reads: "Don't go in the cellar, under any circumstance!"

### [Aspect of Azura](https://www.nexusmods.com/morrowind/mods/51079)
Adds a Daedric helm bearing the aspect of Azura which you can acquire through a new quest which starts at the Holamayan Monastery near the Shrine of Azura.

### [Astrologian's Guild](https://www.nexusmods.com/morrowind/mods/51216)
Join a fully playable guild and gain ranks to the top. Included are several dungeons, some new and others extensions of existing ones.

Replace the icons with the ones in the ```OpenMW Icons``` folder

### [Bethesda Official Plugins Naturalized](https://www.nexusmods.com/morrowind/mods/51107)
Slightly improved implementation of Bethesda's Official Plugins, using **UMOPP** as a base.

Download:
- **UMOPP Naturalized**
	- [x] Helm of Tohan Naturalized
	- [x] Master Index Naturalized

### [Blackthorn Barrow](https://www.nexusmods.com/morrowind/mods/45280) ([TotSP ESP Replacer](https://www.nexusmods.com/morrowind/mods/49232))
Follow the clues of a doomed expedition to find the source behind an ancient Nordic relic.

Use only the TOTSP plugin(link above).

Hide or Delete:
```
Clean__Blackthorn Barrow.ESP
```

### [Early Transport to Mournhold](https://www.nexusmods.com/morrowind/mods/47985)
Allows travel to Mournhold before the Dark Brotherhood attacks begin.

### [Ebonheart Underworks](https://www.nexusmods.com/morrowind/mods/47272)
Ebonheart now has its own sewage system. With filth, rats, people and quests.

Only the assets are needed, use the plugin from **BCOM - Patches**.

Hide or Delete:
```
Ebonheart_Underworks.esp
```

### [Even More Mysterious Killings in Vivec](https://www.nexusmods.com/morrowind/mods/49661)
The Mysterious Killings in Vivec quest now has a new reward and some more flavour for the murderer.

### [Expedition to Mzelthuand](https://www.nexusmods.com/morrowind/mods/45229) **[*Original Engine Only*]**
Off the shoreline of the Bitter Coast region, a Dwemer Ruin has appeared. Take up your spells and delve into the deepest and darkest of Dwemer mysteries within an enigmatic study facility that holds far more than it lets on.

Download:
- **Expedition to Mzelthuand**
- **Expedition to Mzelthuand - Cleaned Melchior Dahrk**

The main file is packaged incorrectly, right click on the **Expedition to Mzelthuand** folder and select **Set as \<data files> directory**

### [Fighters Guild Improved](https://www.nexusmods.com/morrowind/mods/51409)
Overhauls the Fighters Guild questline by improving the background and narrative side of most of its quests, as well as adding more variety and available choices to them.

### [Frozen in Time](https://www.nexusmods.com/morrowind/mods/50077)
This quest will bring you back in time, to solve a mystery untouched for hundreds of years. 

### [Galerion's Tools](https://www.nexusmods.com/morrowind/mods/47901) **[*Original Engine Only*]**
Visit an old but familiar face to embark on a quest to discover an ancient enchanting tool, created by Galerion the Mystic, and unlock an entirely new enchanting mechanic.

### [God of Worms](https://www.nexusmods.com/morrowind/mods/48028)
Introduces five new quests to investigate the Order of the Black Worm's presence in Vvardenfell.

### [Love in the Time of Daedra](https://www.nexusmods.com/morrowind/mods/43635) ([Moved](https://www.nexusmods.com/morrowind/mods/48683))
An open ended quest mod about love, death, Daedra, vengeance, and whiney Bosmer conmen.

Use the moved version of the plugin linked above for **Tamriel Rebuilt** compatibility.

**Important Note: Use only the moved version or you will get two islands.**

### [Magical Missions](https://www.nexusmods.com/morrowind/mods/38773)
Adds five new duties for members of the Mages Guild to Master Wizard Folms Mirel, in Caldera.

### [Maren's Misfit Mabrigash](https://www.nexusmods.com/morrowind/mods/48709)
A dungeon overhaul and quest mod that overhauls and expands the Maren Ancestral Tomb into a hideout befitting of an ashlander, and adds a new quest to complete in the dungeon.

### [Master of Puppets](https://www.nexusmods.com/morrowind/mods/51393)
Recover a stolen arcane tome from a renegade wizard and his magically animated puppet servants.

### [New Ilunibi](https://www.nexusmods.com/morrowind/mods/50393)
Rebuilds the mainquest dungeon Ilunibi from scratch to make it larger, more imposing and more interesting to explore. It also adds four new quests for you to discover and embark upon.

### [OAAB Brother Junipers Twin Lamps](https://www.nexusmods.com/morrowind/mods/51424)
Update of **Brother Juniper**'s classic quest mod. Join the Twin Lamps and fight against slavery through ~20 new quests.

### [Of Eggs and Dwarves - Gnisis Eggmine and Bethamez Overhaul](https://www.nexusmods.com/morrowind/mods/51171)
Rebuilds and expands the Gnisis Eggmine complex from scratch. It also adds a quest, which asks the player to investigate the origins of the tremors that have been plaguing the eggmine. 

Features actual earthquakes!

**[OpenMW]** Download:
- **Of Eggs and Dwarves_OpenMW**
	- [x] Core
	- [x] BCOM Patch

**[Original Engine]** Download:
- **Of Eggs and Dwarves_MWSE**
	- [x] Core
	- [x] BCOM Patch

### [Of Justice and Innocence](https://www.nexusmods.com/morrowind/mods/34046)
In the village of Dagon Fel there lives a woman by the name of Rinida Honwyer. She claims her poor, sweet, innocent brother has been kidnapped by smugglers and she now fears for his life.

Hide or Delete:
```
Of Justice and Innocence.esp
```

### [Pimp My Shrine - The Daedric Legend of Vernaccus](https://www.nexusmods.com/morrowind/mods/49173) **[*Original Engine Only*]**
A lore-friendly quest mod based on an in-game book brought to life, with dungeons, mind-bending puzzles, quests, Daedra, and the power to summon items from oblivion.

### [ReadMe - Library of Vivec Overhaul](https://www.nexusmods.com/morrowind/mods/49916)
Redesigns the Library of Vivec from scratch. There are also new NPCs for you to interact with, and two new quests that set you on the hunt for a unique book.

Download:
- **Library of Vivec Overhaul - Full**

### [Scrolls of The Nine Barriers](https://www.nexusmods.com/morrowind/mods/45831)
This mod adds the missing 7th and 8th barrier scrolls, adds a quest to find the (now rare) 9th barrier scroll, adds new lore surrounding The Nine Barriers, and much more!

### [Silent Island](https://www.nexusmods.com/morrowind/mods/50274)
This is a horror themed mod, with pirates, Sixth House, and romance. Though this mod plays fairly different than most, as many tough enemies can be killed by the environment.

Replace the icons with the ones in the ```OpenMW Icons``` folder.

### [Sorcerer of Alteration](https://www.nexusmods.com/morrowind/mods/51224)
Journey through this quest mod to improve your alteration magic.

### [Tales from the Ashlands - The Great Hive Baan Binif](https://www.nexusmods.com/morrowind/mods/51419)
Adds an imposing landmark, known as "Baan Binif", to the Ashlands, and three new quests designed to flesh out the background of this mysterious structure.

### [The Dream is the Door](https://www.nexusmods.com/morrowind/mods/47423)
To align with what the in game dialogue suggests, the entrance to the Cavern of the Incarnate will now only be visible during the magical hours of twilight.

### [The Sanguine Rose](https://www.nexusmods.com/morrowind/mods/46214) **[*Original Engine Only*]**
The Sanguine Rose adds a fully featured Daedric Quest for Sanguine, the prince of hedonistic revelry, debauchery, and passionate indulgences of darker natures. An Ordinator has been sniffing out Sanguine's shrine and he wants you to take care of the nosy do-gooder in an unconventional way.

Download:
- **The Sanguine Rose**
	- [x] Core
	- [x] MWSE ME Patch 

### [The Stolen Sweetrolls ( OAAB required )](https://www.nexusmods.com/morrowind/mods/51288)
Somebody in Seyda Neen has stolen Pullia's Sweetrolls, can you find out who did it?

Download:
- **The Stolen Sweetrolls**
- **Stolen Sweetrolls Telvanni Mesh Improvement and Ashen Divide Patch**
- **Stolen Sweetrolls Guard Fix**

### [The Vestige of Bethaleft](https://www.nexusmods.com/morrowind/mods/50663)
Discover the remnants of a failed Telvanni expedition and explore the depths of Bethaleft, a Dwemer citadel that served as a testing ground for the Tools of Kagrenac.

### [The Wabbajack](https://www.nexusmods.com/morrowind/mods/44653) **[*Original Engine Only*]**
Adds the legendary Wabbajack artifact!

# Grass		[<sub><sup>⭡</sup></sub>](https://github.com/PharisMods/pharis-mod-list/blob/main/modlist.md#jump-to-separator)

### [Remiros' Groundcover](https://www.nexusmods.com/morrowind/mods/46733)
**[OpenMW]** Download:
- **Main File**
	- [x] Core OpenMW
	- [x] TR Plugins
	- [x] TR Preview Plugins
	- [x] Legend of Chemua Moved

**[Original Engine]** Download:
- **Main File**
	- [x] Core MGE XE
	- [x] TR Plugins
	- [x] TR Preview Plugins
	- [x] Legend of Chemua Moved

Hide or Delete:
```
Rem_GL.esp
Rem_Solstheim.esp
```

### [Beautiful Cities of Morrowind - Grass Patches](https://www.nexusmods.com/morrowind/mods/49231)
Download:
- **BCoM - Grass Patches**
	- [x] Remiros Groundcover

Hide or Delete:
```
REM_AC_No_Sheogorad.ESP
Rem_AL_RMR+Kogoruhn Expanded.esp
Rem_GL_Trackless_GL.esp
Rem_WG - StoneWood Pass.esp
```

# Finishing Up

Click [**here**](finishingup.md) to put the final touches on your mod setup.

up.md) to put the final touches on your mod setup.

