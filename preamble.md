[<< Back to README](README.md)

# Utilities

These are programs that are either necessary for this mod list or very helpful in modding and troubleshooting in general. Personally, I have **MO2** in my `Modding` Folder and the rest in a `Modding Tools` directory within the same folder.

> ![image](images/moddingdirectory.png)

## Necessary

### Mod Organizer 2([MO2](https://www.nexusmods.com/skyrimspecialedition/mods/6194?tab=files), [OpenMW Plugin](https://www.nexusmods.com/morrowind/mods/45642?tab=files))

For modding I use **Mod Organizer 2**, this is the method I recommend because it is the neatest and allows the user to more easily tweak their mod list as well as run third party programs crucial to a functioning load order. 

For OpenMW I use the [**ModOrganizer-to-OpenMW**](https://www.nexusmods.com/morrowind/mods/45642*) plugin made by **AnyOldName3** to export my mod list and load order to `openmw.cfg`. 

For those that are new to Mod Organizer 2 I recommend reading [**this**](mo2basics.md) document before continuing.

*Do not manually install mods, I will be very disappointed in you.*

### [Mlox](https://github.com/rfuzzo/mlox) ([Latest Rules](https://github.com/DanaePlays/mlox-rules/tree/main))

This is for analyzing and sorting your load order using a set of ordering rules.

Add to your **MO2** executables list. When you run **mlox** for the first time it will create an `mlox_base.txt` file in `C:\Users\<your user name>\AppData\Local\mlox\mlox`, this directory is where the latest `mlox_user.txt` (link above) will go. Optionally also add `-n -u` to the 'Arguments' field to stop **mlox** from checking online and opening the GUI. 

### [TES3Merge](https://www.nexusmods.com/morrowind/mods/46870) ([.NET 6 Runtime](https://dotnet.microsoft.com/en-us/download))

A tool for automatically patching conflicts between mods by merging objects and levelled lists. For a more detailed description refer to the Nexus page.

Add to your **MO2** executables list and be sure to add the path to your `Data Files` in the 'Start in' field otherwise **TES3Merge** may not be able to find your plugins.
<!--
### [Wrye Mash Polemos Fork](https://www.nexusmods.com/morrowind/mods/45439) 

**Wrye Mash** is another mod manager, made specifically for Morrowind, but we won't be using it to manage mods with this list, instead it will be used to merge levelled lists. Install location is irrelevant, as you will tell **Wrye Mash** where to find your Morrowind directory during the installation process. Make sure you download the beta 6 version and, if you're on the original engine, enable the 1024 max plugin limit in the advanced settings.

Add to your **MO2** executables list.
-->
## Not Technically Necessary But Still Recommended

### [Enchanted Editor](https://mw.modhistory.com/download-95-1662)
Powerful editor for plugins and saves.

### [TESPCD](https://mw.modhistory.com/download-95-5283)
For detecting conflicts between plugins, such as when two mods edit the same cell.

### [Ordenador](https://www.nexusmods.com/newvegas/mods/46074?tab=description) ([.NET Framework 4.0](http://www.microsoft.com/download/en/details.aspx?id=17718))
Ordenador is for optimizing textures. 

Textures that need optimizing include:
- Uncompressed textures
- Textures lacking mipmaps (note that UI textures do not need mipmaps)
- Textures saved in the wrong compression format (should be DXT1 unless it has transparency, then it should be DXT5, *not* DXT3)

<details> <summary>Ordenador Settings</summary>

> ![ordenadorsettings](images\ordenadorsettings.png)

</details>

### [7-Zip](https://www.7-zip.org/)
For opening archives, or making your own.

### [Notepad++](https://notepad-plus-plus.org/downloads/v7.9.5/)
A very handy plain text editor.

----
Before moving on to the mod installation be sure to get all of the necessary utilities installed and ready.

Click [**here**](modlist.md) to move on to the modlist.
<!--
for the full 300+ mod modlist.

Click [**here**](modlistbareminimum.md) for just the necessities.


# Before We Start... Again


-->