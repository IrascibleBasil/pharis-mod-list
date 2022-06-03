# Before We Start

This list is for OpenMW but with few exceptions it will work fine on the original engine. For the original engine there are also many very impressive MWSE mods that obviously will not be featured on this list. Lastly, this is not a tutorial for installing OpenMW or for MO2; I will gladly help as best I can on Discord(Pharis#2588) but there are great resources with that information readily available so it would seem redundant to repeat here.

## My System
For reference this is what I am currently using to play OpenMW: 
System | My Specs
------------ | -------------
OS | Windows 11 Pro 64-bit
CPU | Intel Core i5 12600k
RAM | 16GB DDR4
GPU | EVGA 2080 Super Black
SSD | Crucial P5 Plus NVME SSD 500GB
Monitor | Dell s2721dgf

With this mod list my FPS is always above 60(even in Old Eboheart) with 25 cell view distance. 
Click here for my my full settings.cfg file 

# Utilities

These are programs that are either necessary for this mod list or very helpful in modding and troubleshoooting in general. Personally I have MO2 in my Modding Folder and the rest in a Modding Tools directory within the same folder.

## Mod Organizer 2([MO2](https://www.nexusmods.com/skyrimspecialedition/mods/6194?tab=files), [OpenMW Plugin](https://www.nexusmods.com/morrowind/mods/45642?tab=files))

For modding OpenMW I use Mod Organizer 2 with the ModOrganizer-to-OpenMW plugin graciously provided by AnyOldName3. This is the method I recommend beecause it is the simplest and allows the user to more easily tweak their mod list as well as run third party programs crucial to a functioning load order. 

## [Mlox](https://github.com/rfuzzo/mlox) ([Latest Rules](https://github.com/DanaePlays/mlox-rules/tree/main))

This is for sorting your load order. Download mlox, add it to your executables in MO2, and run it once. This will have generated the mlox_base file in local/appdata/mlox/mlox 

## [tes3merge](https://www.nexusmods.com/morrowind/mods/46870) ([.NET 6 Runtime](https://dotnet.microsoft.com/en-us/download))

tes3merge is for merging objects to automatically solve mod conflicts and it will be run near the end of the installation process.

## [Wrye Mash Polemos Fork](https://www.nexusmods.com/morrowind/mods/45439)

Wrye Mash is a mod manager specifically for Morrowind but we won't be using it to manage mods with this list, instead it will be used to merge levelled lists.

## [Enxhanted Editor](https://mw.modhistory.com/download-95-1662)

Enchanted Editor is a powerful tool that can allow you remove and tweak records in plugins.

## [TESPCD](https://mw.modhistory.com/download-95-5283)

TESPCD is for detecting conflicts between plugins, such as when two mods edit the same cell.

## [Nifskope](https://github.com/niftools/nifskope/releases/download/v2.0.dev7/NifSkope_2_0_2018-02-22-x64.7z) ([VC++ 2015 Redistributable](https://www.microsoft.com/en-us/download/details.aspx?id=52685))

# Preamble

Before moving on to the mod installation be sure to get all of the utilities installed and added to your executables list in MO2. 

The mods are in order and organized by separator.

# Assets

These are just assets that are used for many other mods such as Tamriel Rebuilt, SHOTN, BCOM, etc.

## [Tamriel Data HD](https://www.nexusmods.com/morrowind/mods/44537?tab=description)

## [OAAB Data](https://www.nexusmods.com/morrowind/mods/49042)

## [An Addendum to Tamrielic Lore Data](https://www.nexusmods.com/morrowind/mods/50647)

# Fixes

## [Patch for Purists](https://www.nexusmods.com/morrowind/mods/45096)

## [Unofficial Morrowind Plugins Patched](https://www.nexusmods.com/morrowind/mods/43931)

## [Expansion Delay](https://www.nexusmods.com/morrowind/mods/47588)

## [Dubdilla Location Fix](https://www.nexusmods.com/morrowind/mods/46720)

## [Divayth Fyr Puzzle Fixed](https://www.nexusmods.com/morrowind/mods/45155)

## [Adamantium Ore Fix(PFP Edit)]()

# UI

## [Kezyma's UI Remastered](https://www.nexusmods.com/morrowind/mods/48987)

## [Morrowind Enhanced Textures - UI](https://www.nexusmods.com/morrowind/mods/46221)

## [De-outlandered main menu and Daedric UI textures](https://www.nexusmods.com/morrowind/mods/46805)

## [RFD's Splash Screens](nexusmods.com/morrowind/mods/47400)

## [Faithful HD Cursors](https://www.nexusmods.com/morrowind/mods/50764)

## [Better Morrowind Crosshair](https://www.nexusmods.com/morrowind/mods/50873)

## [Big Icons](https://www.nexusmods.com/morrowind/mods/49662)

## [Magic Icons(Sigourn Edit)](https://www.nexusmods.com/morrowind/mods/50223)

# Lua

## [Attend Me](https://www.nexusmods.com/morrowind/mods/51232)

## [Protective Guards(OpenMW)](https://www.nexusmods.com/morrowind/mods/46992)

## [Pursuit(OpenMW)](https://www.nexusmods.com/morrowind/mods/50271)

# Audio

## [Aura 3.0 - Replacer](https://www.nexusmods.com/morrowind/mods/48255)
Be sure to only get the replacer file under optional.

## [Haunted Barrows](https://www.nexusmods.com/morrowind/mods/46826)

## [Cave Drip](https://www.nexusmods.com/morrowind/mods/43488)

## [Disable Player Hit Voice](https://www.nexusmods.com/morrowind/mods/46437)
Replaces all hit voices with silence. Entirely up to personal taste but I personally just find them annoying.

## [Immersive Combat Sounds](https://www.nexusmods.com/morrowind/mods/50254)

## [Spell Sounds Enhanced](https://www.nexusmods.com/morrowind/mods/46338)

## [Nifty Elemental Magic Sounds](https://www.nexusmods.com/morrowind/mods/50240)

## [Shut the Fuck up Cliff Racers](https://www.nexusmods.com/morrowind/mods/46588)

## [Less Annoying Shalk Sounds](https://www.nexusmods.com/morrowind/mods/48683)

## [Daggerfall Skeleton Sounds](https://www.nexusmods.com/morrowind/mods/45838)
Makes skeletons much spookier

## [REPLACER - Ambient Howl Replacer](https://www.nexusmods.com/morrowind/mods/45988)
De-sheeps Vvardenfell

# Landmasses

## [Tamriel Rebuilt](https://www.nexusmods.com/morrowind/mods/42145)

## [Skyrim Home of the Nords](https://www.nexusmods.com/morrowind/mods/44921)

## [Solstheim - Tomb of the Snow Prince](https://www.nexusmods.com/morrowind/mods/46810)

## [Landscape Overhaul for The White Wolf of Lokken Mountain](https://www.nexusmods.com/morrowind/mods/48862)

## [Legend of Chemua](https://www.nexusmods.com/morrowind/mods/45253) ([Moved](http://abitoftaste.altervista.org/morrowind/index.php?option=downloads&task=info&id=93&Itemid=50&-Legend-of-Chemua-Moved))
Only use the moved plugin or you will get two islands.

# Cell Edits & Overhauls

## [Beautiful Cities of Morrowind](https://www.nexusmods.com/morrowind/mods/49231)

## [Glass Domes of Vivec - Moonrain Edition](https://www.nexusmods.com/morrowind/mods/48946)
Install the core assets and one of the Glow in the Dahrk patches

## [Concept Art Palace(Vivec City](https://www.nexusmods.com/morrowind/mods/48136)
Install whatever configuration you want just be sure to get the Glow in the Dahrk patch

## [Baar Dau](https://www.nexusmods.com/morrowind/mods/49456)

## [Passage of Prayers - High Fane Corridor Overhaul](https://www.nexusmods.com/morrowind/mods/46786)

## [Guar Stables of Vivec](https://www.nexusmods.com/morrowind/mods/50118)

## [Concept Art Plantations](https://www.nexusmods.com/morrowind/mods/50020)
Only the assets are needed, use the plugin from BCOM patches

## [Beautiful Cities of Morrowind - Project Atlas and GITD Patches](https://www.nexusmods.com/morrowind/mods/49231)
Install:
Project Atlas Patch
GITD + Atlas
Balmora Bridges with bigger arch - Atlas
Stav MGO - GITD + Atlas
RR Ghostgate Fortress - GITD
Vanilla Style Ghostfence Pillars

## [Skar Face(Ald-Ruhn)](https://www.nexusmods.com/morrowind/mods/49510)
Make sure you get the BCOM patch.

## [Immersive Mournhold](https://www.nexusmods.com/morrowind/mods/49353)

## [Nordic Dagon Fel](https://www.nexusmods.com/morrowind/mods/49603)

## [Dagon Fel Mill Redux](https://www.nexusmods.com/morrowind/mods/50067)

## [Telvanni Council House Lounge Room](https://www.nexusmods.com/morrowind/mods/49285)

## [OAAB Tel Mora](https://www.nexusmods.com/morrowind/mods/46177)
Get the arachnophobia friendly patch if you don't like spiders.

## [OAAB Grazelands](https://www.nexusmods.com/morrowind/mods/49075)
If you plan on using groundcover get the Remiros' Groundcover GL Patch.

## [OAAB - The Ashen Divide](https://www.nexusmods.com/morrowind/mods/49047)

## [OAAB - Tombs and Towers](https://www.nexusmods.com/morrowind/mods/49131)

## [OAAB Dwemer Pavements](https://www.nexusmods.com/morrowind/mods/50237)

## [Foyada Mamaea Overhaul](https://www.nexusmods.com/morrowind/mods/46424)
Only the assets are needed, use the plugin from BCOM Patches

## [Redaynia Restored](https://www.nexusmods.com/morrowind/mods/47646) ([Desquirmified]())
Since the hanging slaughterfish squirm around in OpenMW I have provided an edited version that replaces them with the slaughterfish from OAAB Data. Use the edited plugin with the original mod's assets.

## [Justice for Khartag(J.F.K.)](https://www.nexusmods.com/morrowind/mods/49832)

## [The Cottage](https://www.nexusmods.com/morrowind/mods/49660)
Only the assets are needed, use the plugin from BCOM Patches

## [Dark Brotherhood Headquarters](https://www.nexusmods.com/morrowind/mods/43022)

## [Serandas Family Hearth](https://www.nexusmods.com/morrowind/mods/48056)

## [OAAB Shipwrecks](https://www.nexusmods.com/morrowind/mods/51364)

## [Darknut's Greater Dwemer Ruins. Greater Dwemer Interiors](https://www.nexusmods.com/morrowind/mods/45331)

# Mesh & Texture Replacers

## [Weapon Sheathing](https://www.nexusmods.com/morrowind/mods/46069)

## [Weapon Sheathing Additions](https://www.nexusmods.com/morrowind/mods/49616)

## [Correct Meshes](https://www.nexusmods.com/morrowind/mods/39348)

## [Simply Walking(Remastered)](https://www.nexusmods.com/morrowind/mods/49785)
Get the Weapon Sheathing Edition

## [MCAR](https://www.nexusmods.com/morrowind/mods/48628)

## [Dwemer Mesh Improvement](https://www.nexusmods.com/morrowind/mods/43101)

## [Telvanni Mesh Improvement](https://www.nexusmods.com/morrowind/mods/42343)

## [Telvanni Exterior UV Fix](https://www.nexusmods.com/morrowind/mods/23233)

## [Telvanni Door Handle](https://www.nexusmods.com/morrowind/mods/43528?tab=files)

## [Morrowind Optimization Patch](https://www.nexusmods.com/morrowind/mods/45384)
Install only the Core Files and Weapon Sheathing Patch
## [Mistify](https://www.nexusmods.com/morrowind/mods/48112)
Used only as a replacer for the vanilla mist so don't use the plugin.
## [RR Mod Series - Better Meshes](https://www.nexusmods.com/morrowind/mods/43266) ([fix]())

## RR - Better Crates and Barrels V1.1

## RR - Better Crystals 1.0

## [Properly Smoothed Meshes](https://www.nexusmods.com/morrowind/mods/46747) ([flask fix]())
Install:
Core
Beaker, Flasks - clear glass
Inkwell - cut glass

## [Graphic Herbalism - MWSE and OpenMW Edition](https://www.nexusmods.com/morrowind/mods/46599) ([Graphic Herbalism- Ash Yam Collision Switch](https://www.nexusmods.com/morrowind/mods/49154))
Install the smoothed meshes.

## [Morrowind Enhanced Textures](https://www.nexusmods.com/morrowind/mods/46221)

## [Glow in the Dahrk](https://www.nexusmods.com/morrowind/mods/45886)
Install:
Nord Glass Windows
Raven Rock Windows

## [DN Lighted Dwemer Towers](https://www.nexusmods.com/morrowind/mods/51358)

## [Solstheim Graphical Replacer](https://www.nexusmods.com/morrowind/mods/46810)
Install:
- Solstheim - HD Worldspace Graphical Replacer
- Skyrim-Like Trees

Optionally also get the Remiros' Groundcover patch if you want groundcover on Solstheim.

## [Project Atlas](https://www.nexusmods.com/morrowind/mods/45399)
Install:
- Core
- Urns - Smoothed
- Redware - Smoothed
- Emperor Parasols - Smoothed
- Glow in the Dahrk Patch
- Graphic Herbalism Patch

Also download the hotfix and the Textures - MET files.

## Textures - MET


## [My Atlas Texture Collection]()
Some mods have outdated texture atlases or no atlas at all so I have provided atlases I generated with the Project Atlas bat files.

## [Vanilla Land]() ([tx_ma_crackedearth fix](https://www.nexusmods.com/morrowind/mods/47266?tab=description))

## [Lore-Friendly Balmora Suran and Caldera Ground Textures]()
I prefer these over the versions in Vanilla Land.

## [No Scum]()
I don't like the scum so I replaced them with empty nifs

## [Swamp Rocks](https://www.nexusmods.com/morrowind/mods/45673)
Get the 2k version under Old Files
## [SM Re-textures Rock and Cave](https://www.nexusmods.com/morrowind/mods/48856)

## [HD Cavern of the Incarnate](https://www.nexusmods.com/morrowind/mods/46101)

## [I Lava Good Mesh Replacer](https://www.nexusmods.com/morrowind/mods/49605)

## [Bitter Coast Redux II - Trees and Flora](https://www.nexusmods.com/morrowind/mods/45762)

## [SM Bitter Coast Tree Replacer](https://www.nexusmods.com/morrowind/mods/49883)

## [Vanilla-friendly West Gash Tree Replacer](nexusmods.com/morrowind/mods/44173)
Pick the no billboard leaves option so the leaves don't follow you.
## [Melchior's Excellent Grazelands Acacia](https://www.nexusmods.com/morrowind/mods/51058)

## [Remiros' Ascadian Isles Trees 2](https://www.nexusmods.com/morrowind/mods/45779)

## [Pherim Comberry Bush 2.4](https://www.nexusmods.com/morrowind/mods/42586)

## [Pherim's Fire Fern - Plant and Ingredient](https://www.nexusmods.com/morrowind/mods/43568)

## [Improved Kwama Eggs and Egg Sacs](https://www.nexusmods.com/morrowind/mods/43555)

## [Hackle-lo Fixed](https://www.nexusmods.com/morrowind/mods/42784)

## [Epic Plants - Modular](https://www.nexusmods.com/morrowind/mods/46180)

## [GH Patches and Replacers](https://www.nexusmods.com/morrowind/mods/46599)
Install:
- Correct UV Ore + README
- Pherim's Replacers
- Pherim Pulsing Kwama
- Less Epic Plants

The Project Atlas patch is outdated, skip it.

## [Ingredients Mesh Replacer](https://www.nexusmods.com/morrowind/mods/44067)

## [Anumaril's Bowled Ingredients](https://www.nexusmods.com/morrowind/mods/48291)

## [Daedric Intervention - Ingredients](https://www.nexusmods.com/morrowind/mods/46044)

## [R-Zero's Throbbing Meat - a Corprus Meat Replacer](https://www.nexusmods.com/morrowind/mods/45339)

## [Imperial Houses and Forts Retexture - Ordo Arkitektora](https://www.nexusmods.com/morrowind/mods/43940)

## [Lysol's Imperial Forts Normal Mapped for OpenMW - NOT ATLASED](https://www.nexusmods.com/morrowind/mods/46413) ([Atlas]())
I don't use the normal maps from this mod.

## [Hidden Imperial Door Fix](https://www.nexusmods.com/morrowind/mods/43528?tab=files)

## [Imperial Door Fixes](https://www.nexusmods.com/morrowind/mods/47266?tab=description)

## [Dry Stone Walls Revamped](https://www.nexusmods.com/morrowind/mods/49069)
Install the UV fixes and smoother - rockless walls option.

## [Dragon Statue Revisited](https://www.nexusmods.com/morrowind/mods/50561)
Use the Imperial base if you want, I personally don't.

## [Shacks Docks and Ships - Arkitektora of Vvardenfell](https://www.nexusmods.com/morrowind/mods/43520)

## [HD Flags and Banners](https://www.nexusmods.com/morrowind/mods/48853)

## [Hlaalu - Arkitektora Vol.2](https://www.nexusmods.com/morrowind/mods/46246)

## [Vivec and Velothi - Arkitektora Vol.2](https://www.nexusmods.com/morrowind/mods/46266)
The texture atlas is outdated, a newer is in My Atlas Texture Collection.

## [One True Faith - Saints and Frescoes Retexture](https://www.nexusmods.com/morrowind/mods/43810)

## [Ghastly Glowyfence](https://www.nexusmods.com/morrowind/mods/47982)

## [RR Mod Series - Morrowind Statues Replacer](https://www.nexusmods.com/morrowind/mods/43348)

## [Sewers - Arkitektora of Vvardenfell](https://www.nexusmods.com/morrowind/mods/43144)

## [Redoran - Arkitektora Vol.2](https://www.nexusmods.com/morrowind/mods/46235)
One of the atlases is outdated, new ones are in My Atlas Texture Collection.

## [Telvanni Retexture](https://www.nexusmods.com/morrowind/mods/45516)

## [Aesthesia - Stronghold textures](https://www.nexusmods.com/morrowind/mods/46445)

## [Articus Old Stucco 2K Retexture](https://www.nexusmods.com/morrowind/mods/45880)

## [Articus Mournhold 2K Retexture](https://www.nexusmods.com/morrowind/mods/46011)

## [Articus Old Mournhold and Sewers Retexture 2K](https://www.nexusmods.com/morrowind/mods/45769)

## [Articus Clockwork City of Sotha Sil 2K Retexture](https://www.nexusmods.com/morrowind/mods/46149)

## [Ruins - Daedric Intervention](https://www.nexusmods.com/morrowind/mods/46044)

## [Articus 6th House Dagoth - HD Nightmare Retexture 2K](https://www.nexusmods.com/morrowind/mods/48319)
Atlas provided in My Atlas Texture Collection.

## [6th House - Glowing Things](https://www.nexusmods.com/morrowind/mods/48764)

## [Full Dwemer Retexture](https://www.nexusmods.com/morrowind/mods/44264)

## [Swappable Texture Signposts](https://www.nexusmods.com/morrowind/mods/46804)

## [Swayland](https://www.nexusmods.com/morrowind/mods/48854)

## [Better Waterfalls](https://www.nexusmods.com/morrowind/mods/45424)
Install:
Core
Tamriel Rebuilt Water

## [Crystal Soul Gems](https://www.nexusmods.com/morrowind/mods/48300)

## [Ket's Potions and Beverages Retexture](https://www.nexusmods.com/morrowind/mods/44781)

## [All Books Color-Coded and Designed](https://www.nexusmods.com/morrowind/mods/50536)

## [Melchior's Magnificent Manuscripts](https://www.nexusmods.com/morrowind/mods/45626)
Install the ABCD patch.
## [Old Dwemer Books](https://www.nexusmods.com/morrowind/mods/43339)

## [Dwemer Plans and Schematics]()

## [Pete's Scroll With Daedric Alphabet](https://www.nexusmods.com/morrowind/mods/47863)

## [HD Forge](https://www.nexusmods.com/morrowind/mods/46738)
Install:
Data Files
Optional Animated Bellows
Optional Texture for Glowing Ash

Also download the HD Bloodmoon Forge file

## [Dunmer Lanterns Replacer](https://www.nexusmods.com/morrowind/mods/43219)
Install:


## [Apel's Fire Retexture Patched](https://www.nexusmods.com/morrowind/mods/50092)

## [Subtle Smoke](https://www.nexusmods.com/morrowind/mods/47341)

## [Mist Retexture](https://www.nexusmods.com/morrowind/mods/44322)

## [Qwerty's Various Graphics - Blood](https://www.nexusmods.com/morrowind/mods/46026)

## [Skeleton and Metal Sparks blood retexture](https://www.nexusmods.com/morrowind/mods/43359)

## [Magic VFX Retexture by Articus](https://www.nexusmods.com/morrowind/mods/47702)

## [Bound Spells Reforged](https://www.nexusmods.com/morrowind/mods/48750)

## [Spells Reforged - Elemental Shields](https://www.nexusmods.com/morrowind/mods/50073)

## [Spells Reforged - purple Shield](https://www.nexusmods.com/morrowind/mods/50905)

## [Pluginless NoGlow Lite](https://www.nexusmods.com/morrowind/mods/43795)

# Body & Head Replacers

## [Better Bodies ZW](https://www.nexusmods.com/morrowind/mods/42395) ([Fixed Meshes]())

## [Better Bodies - Hand Fixes](https://www.nexusmods.com/morrowind/mods/47521)

## [Westly's Faces Refurbished](https://www.nexusmods.com/morrowind/mods/51214)

## [Color Tweaked Westly's BB Textures]()

## [New Beast Bodies by Liztail](https://www.nexusmods.com/morrowind/mods/47678)

## [Improved Argonians](https://www.nexusmods.com/morrowind/mods/45918)

## [Pluginless Khajiit Head Pack](https://www.nexusmods.com/morrowind/mods/43110)

## [Pluginless Khajiit Head Pack - Vampires](https://www.nexusmods.com/morrowind/mods/43795)

# Creatures

## [Divine Dagoths](https://www.nexusmods.com/morrowind/mods/45536)

## [Divine Vivec](https://www.nexusmods.com/morrowind/mods/46342)

## [Better Almalexia](https://www.nexusmods.com/morrowind/mods/23388)

## [By Azura](https://www.nexusmods.com/morrowind/mods/50567)

## [Vanilla friendly creatures and undeads expansion](https://www.nexusmods.com/morrowind/mods/48818)

## [Daedric Intervention - Creatures]()

## [4thUnknowns Creatures Morrowind Edition](https://www.nexusmods.com/morrowind/mods/50137)

## [Atronachs Textures](https://www.nexusmods.com/morrowind/mods/46026)

## [Clannfear Replacer](https://www.nexusmods.com/morrowind/mods/45173)

## [Scamp Replacer - Glowing Eyes](https://www.nexusmods.com/morrowind/mods/44314)

## [Creeper the Scamp](https://www.nexusmods.com/morrowind/mods/47823)

## [Spriggans Glow](https://www.nexusmods.com/morrowind/mods/43350)

## [Corprus Natives](https://www.nexusmods.com/morrowind/mods/45674)

## [SM Bonewalker Replacer](https://www.nexusmods.com/morrowind/mods/51030)

## [Silt Strider](https://www.nexusmods.com/morrowind/mods/48664)

## [Silt Strider Animation Restored](https://www.nexusmods.com/morrowind/mods/44150)

## [Guars replacer - Aendemika of Vvardenfell](https://www.nexusmods.com/morrowind/mods/42521)

## [CRAG - color replacer for Aendemika Guar](https://www.nexusmods.com/morrowind/mods/48966)

## [Alit replacer - Aendemika of Vvardenfell](https://www.nexusmods.com/morrowind/mods/42520)

## [Kagouti replacer - Aendemika of Vvardenfell](https://www.nexusmods.com/morrowind/mods/42523)

## [PB Cliff Racer Replacer 2.0](https://www.nexusmods.com/morrowind/mods/48978)

## [Improved Better Skulls](https://www.nexusmods.com/morrowind/mods/46012)

## [Nix-Hound Replacer 1.0](https://www.nexusmods.com/morrowind/mods/43620)

## [REPLACER - Scrib Mesh Tweak](https://www.nexusmods.com/morrowind/mods/45988)

## [Pluginless rat replacer](https://www.nexusmods.com/morrowind/mods/43795)

# Apparel & Weapon Replacers

## [Better Clothes Complete](https://www.nexusmods.com/morrowind/mods/47549)

## [Articus Mournhold Clothes](https://www.nexusmods.com/morrowind/mods/45773)

## [Articus Solstheim Clothes](https://www.nexusmods.com/morrowind/mods/45786)

## [Common Shoe Pack](https://www.nexusmods.com/morrowind/mods/46815)

## [Better Clothes Retextured](https://www.nexusmods.com/morrowind/mods/47851)

## [Unique Finery Replacer UFR - No Robe](https://www.nexusmods.com/morrowind/mods/25725)

## [Tweaked and Optimized Jewelry Meshes](https://www.nexusmods.com/morrowind/mods/48861)

## [Unique Jewelry Redone](https://www.nexusmods.com/morrowind/mods/46151)

## [Necromancer's Amulet - Modern lore style](https://www.nexusmods.com/morrowind/mods/50030)

## [Better Robes](https://www.nexusmods.com/morrowind/mods/42773)

## [Better Robes Tamriel Data Patch]()

## [Robe Overhaul](https://www.nexusmods.com/morrowind/mods/43748)

## [Blank Glow Maps for Robe Overhaul](https://www.nexusmods.com/morrowind/mods/43795)

## [Better Morrowind Armor](https://www.nexusmods.com/morrowind/mods/42509)

## [Better Morrowind Armor Fixes](https://www.nexusmods.com/morrowind/mods/47920?tab=files)

## [HiRez Armors - Native Styles V2 Fixed and Optimized](https://www.nexusmods.com/morrowind/mods/47919)

## [Improved Pauldron Meshes (Vanilla - Better Morrowind Armor)](https://www.nexusmods.com/morrowind/mods/47920?tab=files)

## [N'wah's Work Pauldrons](https://www.nexusmods.com/morrowind/mods/49103)

## [Armors Retexture - Outlander Styles](https://www.nexusmods.com/morrowind/mods/44210)

## [RR Mod Series - Better Telvanni Cephalopod Armor](https://www.nexusmods.com/morrowind/mods/44837) ([No Back Shell](https://www.nexusmods.com/morrowind/mods/49334))

## [Orcish retexture](https://www.nexusmods.com/morrowind/mods/43502)

## [Improved Nordic Iron Helm 1.0](https://www.nexusmods.com/morrowind/mods/43816)

## [Ebony Mail Replacer](https://www.nexusmods.com/morrowind/mods/45183)

## [Restyled Helmet Replacer](https://www.nexusmods.com/morrowind/mods/51049)

## [Improved Templar Helmet](https://www.nexusmods.com/morrowind/mods/47920?tab=files)

## [Trollbone Helm Replacer](https://www.nexusmods.com/morrowind/mods/45322)

## [Improved Shield Meshes](https://www.nexusmods.com/morrowind/mods/47931)

## [Imperial Legion Shields](https://www.nexusmods.com/morrowind/mods/45041)

## [Improved Weapon Meshes - Organic](https://www.nexusmods.com/morrowind/mods/47892)

## [Oriental Mesh Improvements](https://www.nexusmods.com/morrowind/mods/29906)

## [Silver Mesh Improvements](https://www.nexusmods.com/morrowind/mods/46787)

## [Nordic Mesh Improvements](https://www.nexusmods.com/morrowind/mods/46792)

## [Smooth Glass Weapons](https://www.nexusmods.com/morrowind/mods/46778)

## [Smooth Orcish Weapons](https://www.nexusmods.com/morrowind/mods/46779)

## [Improved Weapon Meshes - Ebony](https://www.nexusmods.com/morrowind/mods/43484)

## [Improved Weapon Meshes - Steel](https://www.nexusmods.com/morrowind/mods/43120)

## [Iron Mesh Improvements - Uniques](https://www.nexusmods.com/morrowind/mods/34863)

## [Real Reflective Weapons - Iron](https://www.nexusmods.com/morrowind/mods/43077)

## [Chitin Weapons retexture](https://www.nexusmods.com/morrowind/mods/47932)

## [Improved Thrown Weapon Projectiles]()

## [Adamantium Axe Replacer](https://www.nexusmods.com/morrowind/mods/46791)

## [Adamantium Claymore Replacer](https://www.nexusmods.com/morrowind/mods/46790)

## [Bonemold Bow Replacer](https://www.nexusmods.com/morrowind/mods/45156) ([Weapon Sheating Patch](https://www.nexusmods.com/morrowind/mods/48891))

## [Crossbows Enhanced](https://www.nexusmods.com/morrowind/mods/48586)

## [PikachunoTMs Mesh Artifact Improvements and Replacers](https://www.nexusmods.com/morrowind/mods/45631)

## [Unique Eltonbrand for Fallen One's Goldbrand](https://www.nexusmods.com/morrowind/mods/43528)

## [Remiros' Uniques](https://www.nexusmods.com/morrowind/mods/49674)

## [Animated Staff of Magnus](https://www.nexusmods.com/morrowind/mods/51402)

## [The Tools of Kagrenac](https://www.nexusmods.com/morrowind/mods/44500)

## [Unique Weapon - Mephala's Teacher](https://www.nexusmods.com/morrowind/mods/43528?tab=files)

# NPCs & Companions

## [Kolka the Wolf](https://www.nexusmods.com/morrowind/mods/49765)

## [Paxon the Pack Rat](https://www.nexusmods.com/morrowind/mods/45669)

## [War Kagouti Companion - Mausi](https://www.nexusmods.com/morrowind/mods/45169)

## [Stripes the Cat](https://www.nexusmods.com/morrowind/mods/51086) ([Required](https://mw.modhistory.com/download-24-15599))

## [Services Restored](https://www.nexusmods.com/morrowind/mods/47068)

# Dialogue

## [Greetings for No Lore](https://www.nexusmods.com/morrowind/mods/46063)

## [Djangos Dialogue 1.4](https://www.nexusmods.com/morrowind/mods/47253)

## [Djangos Dialogue - Patch for Purists](https://www.nexusmods.com/morrowind/mods/48955)

## [FMI - Sane Ordinators](https://www.nexusmods.com/morrowind/mods/47381)

## [FMI - NotAllDunmer](https://www.nexusmods.com/morrowind/mods/47569)

## [FMBP - Michael Michael Michael](https://www.nexusmods.com/morrowind/mods/48598)

## [FMBP - Greet Service](https://www.nexusmods.com/morrowind/mods/50937)

## [Idle Talk](https://www.nexusmods.com/morrowind/mods/46948)

# Levelled Lists

## [Wares](https://www.nexusmods.com/morrowind/mods/49205)

## [OAAB Integrations](https://www.nexusmods.com/morrowind/mods/49045)

## [Expansions Integrated](https://www.nexusmods.com/morrowind/mods/47861)

## [Area Effect Arrows Integrated](https://www.nexusmods.com/morrowind/mods/47745)

# Gameplay

## [Mage Robes](https://www.nexusmods.com/morrowind/mods/45739)

## [Umbra- Blademaster](https://www.nexusmods.com/morrowind/mods/43275)

## [Concept Art Daedric Helmets](https://www.nexusmods.com/morrowind/mods/49534)

## [Indoril Ronin](https://www.nexusmods.com/morrowind/mods/50689)

## [Walkers of Morrowind](https://www.nexusmods.com/morrowind/mods/49889)

## [Quick Char (Necro Edit)](https://www.nexusmods.com/morrowind/mods/47706)

## [Companion Friendly Lava](https://www.nexusmods.com/morrowind/mods/50890)

## [Dynamic Distant Details](https://www.nexusmods.com/morrowind/mods/51236)

## [Lord's Mail and Morningstars](https://www.nexusmods.com/morrowind/mods/49878)

# Rebalance

## [Beware the Sixth House (Sixth House Overhaul)](https://www.nexusmods.com/morrowind/mods/46036)

## [Tribunal Rebalance](https://www.nexusmods.com/morrowind/mods/45713)

## [Bloodmoon Rebalance](https://www.nexusmods.com/morrowind/mods/45714)

## [Beware the Sixth House Tweaks](https://www.nexusmods.com/morrowind/mods/49232)

# Quests

## [ABCs for Outlanders](https://www.nexusmods.com/morrowind/mods/46692)

## [A Conjurer's Calling](https://www.nexusmods.com/morrowind/mods/51070)

## [A Hermits Request](https://www.nexusmods.com/morrowind/mods/23714)

## [A Merchant's Whim](https://www.nexusmods.com/morrowind/mods/51068)

## [Ancient Foes](https://www.nexusmods.com/morrowind/mods/44705)

## [Apothecary's Demise](https://www.nexusmods.com/morrowind/mods/44331)

## [Aspect of Azura](https://www.nexusmods.com/morrowind/mods/51079)

## [Astrologian's Guild](https://www.nexusmods.com/morrowind/mods/51216)

## [Berandas Overhaul](https://www.nexusmods.com/morrowind/mods/48236)

## [Blackthorn Barrow](https://www.nexusmods.com/morrowind/mods/45280) ([TotSP ESP Replacer](https://www.nexusmods.com/morrowind/mods/49232))

## [Early Transport to Mournhold](https://www.nexusmods.com/morrowind/mods/47985)

## [Ebonheart Underworks](https://www.nexusmods.com/morrowind/mods/47272)

## [Even More Mysterious Killings in Vivec](https://www.nexusmods.com/morrowind/mods/49661)

## [Fighters Guild Improved](https://www.nexusmods.com/morrowind/mods/51409)

## [FMI - Caius Big Package](https://www.nexusmods.com/morrowind/mods/47580)

## [FMI - Hospitality Papers Expanded](https://www.nexusmods.com/morrowind/mods/46107)

## [Frozen in Time](https://www.nexusmods.com/morrowind/mods/50077)

## [God of Worms](https://www.nexusmods.com/morrowind/mods/48028)

## [Legacy of Odiil 1.3](https://www.nexusmods.com/morrowind/mods/44670)

## [Library of Vivec Overhaul - Full](https://www.nexusmods.com/morrowind/mods/49916)

## [Love in the Time of Daedra](https://www.nexusmods.com/morrowind/mods/43635) ([TR Version](https://www.nexusmods.com/morrowind/mods/48683))

## [Magical Missions](https://www.nexusmods.com/morrowind/mods/38773)

## [Maren's Misfit Mabrigash](https://www.nexusmods.com/morrowind/mods/48709)

## [Master of Puppets](https://www.nexusmods.com/morrowind/mods/51393)

## [New Ilunibi](https://www.nexusmods.com/morrowind/mods/50393)

## [OAAB Brother Junipers Twin Lamps](https://www.nexusmods.com/morrowind/mods/51424)

## [Of Eggs and Dwarves - Gnisis Eggmine and Bethamez Overhaul](https://www.nexusmods.com/morrowind/mods/51171)

## [Official Plugins Naturalized](https://www.nexusmods.com/morrowind/mods/51107)

## [Of Justice and Innocence](https://www.nexusmods.com/morrowind/mods/34046)

## [Scrolls of The Nine Barriers](https://www.nexusmods.com/morrowind/mods/45831)

## [Silent Island](https://www.nexusmods.com/morrowind/mods/50274)

## [Sorcerer of Alteration](https://www.nexusmods.com/morrowind/mods/51224)

## [Tales from the Ashlands - The Great Hive Baan Binif](https://www.nexusmods.com/morrowind/mods/51419)

## [The Dream is the Door](https://www.nexusmods.com/morrowind/mods/47423)

## [The Stolen Sweetrolls ( OAAB required )](https://www.nexusmods.com/morrowind/mods/51288)

## [The Vestige of Bethaleft](https://www.nexusmods.com/morrowind/mods/50663)

# Grass

## [Remiros' Groundcover](https://www.nexusmods.com/morrowind/mods/46733)

## [Beautiful Cities of Morrowind - Grass Patches](https://www.nexusmods.com/morrowind/mods/49231)
