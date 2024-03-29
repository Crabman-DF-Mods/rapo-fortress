# Changelog
This file will document changes to this project.

Unfortunately, [Semantic Versioning](https://semver.org/) is not suitable for Dwarf Fortress raw mods because too many changes would be `MAJOR` save incompatible changes, so this project uses a custom versioning convention instead; for a given version number `RELEASE.MAJOR.MINOR`, increment the:
- `RELEASE` version for updates that require a new version of DF. Not compatible with existing saves.
- `MAJOR` version for updates that are _not_ save-compatible, and thus require a new world/save file.
- `MINOR` version for updates that _are_ save-compatible, and can be applied to existing worlds/save files.

The "Unreleased" heading is for changes that are in the repo but not in any published version (they are probably not ready yet).

The meaning of each subcategory of change is as follows:
- Added: A new file, section in a file, or object was created, or a feature added to an object. If a creature ID exists but is unimplemented/has `[DOES_NOT_EXIST]` and cannot be spawned even in the testing arena, this doesn't count as being added.
- Changed: An existing file or object/property has been edited/changed. Changes that will not be recorded include most code comments inside files, updates to `CHANGELOG.md` that are simply recording other changes, or `README.md` updating the mod version or promoting something from "planned content" to "content".
- Removed: An object, property, or section of a non-raw file was deleted.
- Fixed: A bug/error or a typo was fixed. If it's a fix, it will not be recorded under any of the above headings.

## [Unreleased]

## Added

## Changed

## Removed

## Fixed

## [v2.0.0] - 2022-12-09

### Added
- Graphics! Absolutely terrible ones that are just ugly edits of vanilla stuff, but graphics nontheless!
- Updated the readme file with a bunch of new info; more links, including a link to the new dependency mod, "Creature Scrapbook"
- The `info.txt` file needed for it to be recognised as an actual mod by DF
- Added the "messenger" position to both rapo civs
- Underwear for the miner rapo civilization
- Added vanilla `50.01`'s `NAME_BUILDING_HOSPITAL` symbol for both rapo civs
- Descriptions for some positions of both rapo civs
- Gave rapo monarchs their gender neutral name (I don't know what this does, but dwarves have this change too in vanilla `50.01`)

### Changed
- Updated `ATTACK_TRIGGER` format for `50.01`
- Updated ages for raposa so they become adults at 18 (to match vanilla `50.01`)
- Updated the code to recognize that cheek whiskers are now actually on the cheeks in `50.01`
- Renamed a bunch of files and file headers
- Updated the object IDs for both raposa civs and the ice dragons

### Removed
- Removed the `b_detail_plan_dtl.txt` file
- For DF `50.01`, removed the entity tokens `UNDEAD_CANDIDATE`, `PERMITTED_JOB:ARCHITECT`, and `LAND_HOLDER_TRIGGER`

### Fixed
- Banya crops can now grow in the tundra and in temperate grasslands (like we see in the game, they can grow in cold places it seems)

## [v1.0.2] - 2022-12-04

### Added
- Added profession names for raposa, eg, "craftsrapo"

### Changed
- Updated the mod's versioning conventions
- Updated `README.md` link to point to my new DFFD user ID
- Edited one of the `README.md` starting paragraphs to reflect that the DF RAW LS is out of beta now

### Removed
- Took out the "TODO" notes/comments, moved them into Github's issue tracker

### Fixed
- Raposa are no longer described anywhere as "dwarves", eg "militia-dwarf"

## [v1.0.1] - 2022-01-02
### Added
- Gave ice dragons sounds (roaring, growls and a snapping bite)

### Changed
- Updated the readme file to reflect that the DF RAW LS is out of alpha now
- Made raposa even smaller; 60% the volume of a human, and I updated their description accordingly

### Fixed
- Typos in `README.md` regarding ice dragons
- Raposa's ASCII `CREATURE_TILE` was the wrong color (cyan), now it's brown

## [v1.0.0] - 2021-12-25
The initial release, for Christmas! It contains the following:
- Raposa race; basically humans with long ears and fur
- A basic raposa entity/civilization based off the original raposa village; similar to humans, but with more mellow ethics and different religious spheres
- A raposa entity/civilization based off of "Lavasteam" from the DS sequel. Like the normal rapo civ, but based off dwarves instead (and slightly more ethically dubious than regular raposa), and these ones are playable!
- Ice dragons; semi-megabeasts based off the Frostwind boss from the first game
- Banya crop; similar to wheat, though right now it has no special connection to raposa civs, it's just another crop in the world
- Banya crystals; semi-opaque and blue crystals that grow in clusters, they are quite valuable, and... Edible?

<!--Links-->
[Unreleased]: https://github.com/Crabman-DF-Mods/rapo-fortress/compare/v2.0.0...HEAD
[v2.0.0]: https://github.com/Crabman-DF-Mods/rapo-fortress/compare/v1.0.2...v2.0.0
[v1.0.2]: https://github.com/Crabman-DF-Mods/rapo-fortress/compare/v1.0.1...v1.0.2
[v1.0.1]: https://github.com/Crabman-DF-Mods/rapo-fortress/compare/v1.0.0...v1.0.1
[v1.0.0]: https://github.com/Crabman-DF-Mods/rapo-fortress/releases/tag/v1.0.0
