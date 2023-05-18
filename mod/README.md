# Overview

Have you seen the hulking menace of Silfae's "Animated Shark Portraits" mod?  Do you wish that the gameplay elements were up-to-date so that you can play the Deep Tide as it was originally designed?  Then this mod is for you!

There are other mods which contain the same portraits, so why should you choose this one?  Other mods don't include the prebuilt empire or custom system initializer, but this one does!  Please enjoy my translation of Silfae's custom empire into modern Stellaris.

# Changes

All gameplay features from the original mod are upgraded to be fully compatible with Stellaris 3.8 "Gemini," the latest version when this was written.  Updates include:

* Update the namelist to account for all built-in army types, remove obsolete entries; Army names more lore-friendly
* Remove alternate (blank) city graphics - mostly they were to try and get a static diplomacy backdrop but only worked for colonies with city size 4; set the `graphical_culture` to not define a cityset
* Add a static room that combines the migratory flock room with the static backdrop image - this room is now used by the predefined empire by default
* Simply female clothing selector to eliminate duplicate blank choices
* Update custom starting initializer
* Update pre-scripted empire
    * Now has Origin: Prosperous Unification
    * Uses aquatic cities and ships
    * Could already randomly spawn
    * Added the Aquatic trait (thus requires the Aquatic Species Pack to play)
    * Removed Resilient trait in order to afford Aquatic
    * Swapped Wasteful trait to Nonadaptive in order to afford Aquatic (as of Stellaris 3.6)
* You can use Silfae's custom Sharkanian portraits for your own empires without any DLC requirements
* The Sharkanians are part of the Aquatic species class (with the Aquatics Species Pack) or Molluscoid species class (without) (since Stellaris 3.8)
* Support being able to choose a single-gender species (since Stellaris 3.2)

## Compatibility

Compatible with any other mod that does not add the same portraits or art assets.

The Launcher will tell you that some mods are outdated - that is because the dependency is out of date with the game's version number.  This mod overwrites and replaces all incompatible code so that the portrait mod will function as originally designed.  You can safely ignore the out-of-date warning for the dependency mod.

Built for Stellaris version 3.8 "Gemini."  Not compatible with achievements.

### Dependencies

In order for this mod to function, you **must** install the following mod and load it before this one:

[Animated Shark Portraits](https://steamcommunity.com/sharedfiles/filedetails/?id=1098915405) by Silfae

### When to Install

This mod should be added before the game has started.  If you remove it from a game in progress, your game may have graphical problems if any species was using the custom portraits.

## Changelog

* 1.0.0 Initial version
* 1.0.1 Ensure correct `graphical_culture`
* 1.1.0 Update for compatibility with Stellaris version 3.1 "Lem"
    * Add new localisation keys introduced in 3.1
* 2.0.0 Update for compatibility with Stellaris version 3.2 "Herbert"
    * Apply new mono-gender portrait rules
    * Make the pre-scripted empire Aquatic (trait, ships, cities, requires DLC)
    * Improve clothing selector (only females have clothes)
    * Sharkanian species class defaults to molluscoid ships - this is so it doesn't require on the Aquatics DLC
* 2.0.1 Don't break the base game diplomacy rooms - fix is to name the new file to load _before_ the built-in file
* 2.0.2 Small tweaks
    * Portrait selectors based on job category, not pop category - my goal is for the Pop portraits to be based on the job, not the Pop's stratum
    * No longer ignore portrait duplication for the pre-scripted empire
* 2.1.0 Update for compatibility with Stellaris version 3.3 "Libra"
* 3.0.0 Update for Stellaris version 3.4 "Cepheus" - all static text moved to localisation (name lists, species names, prescripted empire)
* 4.0.0 Update for Stellaris version 3.6 "Orion" (and changes from version 3.5 "Fornax")
    * Minor namelist updates
    * Update `hair` to `attachment`
    * Alter prescripted species: remove Wasteful and add Nonadaptive in order to compensate for Aquatic price increase
* 5.0.0 Update for Stellaris version 3.7 "Canis Minor"
    * Add Planetary Diversity compatibility
    * Remove global flag
    * Add compatibility trigger `has_sharkanian_portraits_revisited_active`
* 6.0.0 Update for Stellaris version 3.8 "Gemini"
    * Sharkanians are now part of the Aquatic (with Aquatic Species Pack) or Molluscoid (without) species class (thanks to changes by Paradox, this is no longer mod-unfriendly)
    * Update prescripted empire to use the new prescripted ruler class and trait system

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/sharkanian_portraits_revisited)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.

# Special Thanks

I was inspired to extend the original mod when I saw [Endugu](https://steamcommunity.com/profiles/76561198037630876/myworkshopfiles/)'s [expansion](https://steamcommunity.com/sharedfiles/filedetails/?id=1584824947) of [Silfae](https://steamcommunity.com/profiles/76561198021525667/myworkshopfiles/)'s [Animated Xirmian Portraits](https://steamcommunity.com/workshop/filedetails/?id=881118424).  Modular mods that require downloading the original mod(s) help give credit where credit is due.

An extra special thanks to Silfae for creating and sharing so many detailed, animated portraits for the community.