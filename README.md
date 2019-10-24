
![Latest Release](https://img.shields.io/static/v1?label=release&message=v8.0.0&color=darkred)<a name="top" id="top">
![Platform](https://img.shields.io/static/v1?label=platform&message=windows&color=informational)
![Language](https://img.shields.io/static/v1?label=language&message=English%20%7C%20French%20%7C%20German%20%7C%20Italian%20%7C%20Russian&color=limegreen)

<div align="center"><h1></a>Demon Summoning Ritual - Unholy Gate Opening Ritual Book (WIP)</h1>

<h3>A mod hosted by Spellhold Studios for Baldur's Gate II: Throne of Bhaal (classical and EE games),
Baldur's Gate Trilogy and EET<h3>

</div><br />


**Original Author:** Tin  
**Mod Website and Forum:** <a href="">Spellhold Studios</a><br /><br />


<div align="center">
<a href="#intro">Overview</a> &#x2B25; <a href="#compat">Compatibility</a> &#x2B25; <a href="#installation">Installation</a> &#x2B25; <a href="#components">Components</a> &#x2B25; <a href="#credits">Credits</a> &#x2B25; <a href="#versions">Versions History</a></center></br>
</div>

<hr>


## <a name="intro" id="intro"></a>Overview

This mod adds a demon summoning ritual book, which is in possession of the master wizard Tolgerias (Planar sphere/Slums). You can summon several types of demons (nabassu/glabrezu/cornugon/pit fiend/balor) with the manual, the choice is random.

:warning: For the challenge I made Tolgerias somewhat harder to kill! &#128521;

Note: This item can't be used by good aligned characters. 

Have fun using it, I had some making it!


<hr>


## <a name="compat" id="compat"></a>Compatibility

This mod is designed to work on the following Infinity Engine games: the original Baldur's Gate II (BG2 or just SoA) with the Throne of Bhaal (ToB) expansion, Baldur's Gate II: Enhanced Edition (BG2EE), the conversion projects Baldur's Gate Trilogy (BGT) and Enhanced Edition Trilogy (EET).

This is a WeiDU mod, and therefore should be compatible with all WeiDU mods. If you encounter any bugs, please report them on the forum!<br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Notes

<em>If you've previously installed the mod, remove it before extracting the new version. To do this, run **setup-dsr.exe**, uninstall the previously installed main component and delete the dsr folder.</em>

<em>When installing or uninstalling, **do not close the DOS window** by clicking on the **X** button! Instead, press the **Enter** key whenever instructed to do so.</em>

**Disable any antivirus** or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.

## 

#### Enhanced Editions Note

The Enhanced Editions are actively supported games. Please note that every patch update will wipe your current mod setup! If in the middle of a modded game you might want to delay the patch update (if possible) as even after reinstalling the mods, you might not be able to continue with your old savegames. Alternatively, copy the whole game's folder into a new one that can be modded and will stay untouched by game patches. It is important that you install the mod to the language version you are playing the game in. Otherwise, the dialogues of the mod will not show but give error messages.

## 

#### Windows

Extract the contents of the mod archive into the folder of the game you wish to modify (<em>the folder which contains the "CHITIN.KEY" file</em>), using <a href="http://www.7-zip.org/download.html">7zip</a>, <a href="http://www.rarlab.com/download.htm">WinRAR</a>, or another file compression utility that handles .zip files. On successful extraction, there should be a dsr folder and a setup-dsr.exe file in your game folder. To install, simply double-click **setup-dsr.exe** and follow the instructions on screen.

Run **setup-dsr.exe** in your game folder to reinstall, uninstall or otherwise change the component settings.

## 

#### Note for Complete Uninstallation

In addition to the methods above for removing individual components, you can completely uninstall the mod using **`setup-dsr --uninstall`** at the command line to remove all components without wading through prompts.</br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="components" id="components"></a>Components

The installer includes one single component, the main component.


<hr>


## <a name="credits" id="credits"></a>Credits and Acknowledgements

#### Author: Tin


#### Special Acknowledgements to:

- Gwendolyne: Fixed translations and released version 8.0.0.
- Deratiseur: Provided French translation, the EE compatible version and released version 7.
- Ilot: Provided Italian translation.
- Jarl: Provided German translation.
- aerie.ru team: Provided Russian translation.

If you wish to translate the mod, have a suggestion, or should encounter any bugs, please report them to the maintainers at the <a href="">mod forum</a>.</br>


#### Copyrights Information

###### Unholy Gate Opening Ritual Book is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by Tin, based on material from the game Baldur's Gate II and its expansion.
###### Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal &copy; TSR, Inc. The BioWare Infinity Engine is &copy; BioWare Corp. All other trademarks and copyrights are property of their respective owners.
###### All other trademarks and copyrights are the property of their respective owners.</br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="versions" id="versions"></a>Versions History

##### Version 8.0.0 (, 2019)

- Renamed Setup-dsr.tp2 -> dsr.tp2 to support AL|EN's "Project Infinity".
- Added dsr.ini metadata file to support AL|EN's "Project Infinity".
- Reorganized mod architecture tree: created or renamed folders to sort files according to their types.
- Reorganized component (DESIGNATED number).
- Added REQUIRE_PREDICATE process to avoid installing the mod in inaccurate games.
- Replaced AUTHOR keyword with SUPPORT.
- Updated German, Italian and Russian tra files for compatibility with GW_UPDATE_ITM_DESCRIPTION_TO_EE WeiDU function requirements which automatically removes usability restrictions for EE games.
- Split, updated and renamed readme files to heartwood-readme-%LANGUAGE%.
- Updated French and English translations (Gwendolyne).
- Updated WeiDU installer to v246.

## 

##### Version 7 (10 October 2018)

- Added BG2EE compatibility by Deratiseur.

## 

##### Version 6 (24 October 2009)

- tolger2.cre is patched, now.
- Added German translation by Jarl.
- Changed to README command.
- Updated WeiDU installer to v211.

## 

##### Version 5 (09 April 2009)

- Fixed COMPILE command
- Added VERSION flag
- Updated WeiDU installer to v210

## 

##### Version 4 (17 May 2008)

- Added Italian translation by Ilot (thank you!!!).

## 

##### Version 3 (14 May 2008)

- Added French translation by Deratiseur (thank you!!!).

## 

##### Version 2 (08 January 2007)

- WeiDU-conversion by Badgert.
- Added Russian translation by www.aerie.ru.

## 

##### Version 1

- Initial release.
<div align="right"><a href="#top">Back to top</a></div>
