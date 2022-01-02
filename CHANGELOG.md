# Changelog
This file will document changes to this project.

Unfortunately, [Semantic Versioning](https://semver.org/) is not compatible with Dwarf Fortress raw mods because most changes would be `MAJOR` save incompatible changes, so this project uses a custom versioning convention instead; for a given version number `MAJOR.MINOR.PATCH`, increment the:
- `MAJOR` version for a large overhaul of many existing objects, or the addition of a new class of features/objects that were previously impossible. This would usually correspond with new major DF releases, and therefore is likely not compatible with existing saves, or even previous DF versions.
- `MINOR` version for new objects being added or large changes to existing objects; likely not save compatible.
- `PATCH` version for bug fixes, _small_ edits to objects, code cleanups, or documentation changes. Almost always compatible with previous saves.

The "Unreleased" heading is for changes that are in the repo but not in any published version (they are probably not ready yet).

The meaning of each subcategory of change is as follows:
- Added: A new file, section in a file, or object was created, or a feature added to an object. If a creature ID exists but is unimplemented/has `[DOES_NOT_EXIST]` and cannot be spawned even in the testing arena, this doesn't count as being added.
- Changed: An existing file or object/property has been edited/changed. Changes that will not be recorded include most code comments inside files, updates to `CHANGELOG.md` that are simply recording other changes, or `README.md` updating the mod version or promoting something from "planned content" to "content".
- Removed: An object, property, or section of a non-raw file was deleted.
- Fixed: A bug/error or a typo was fixed. If it's a fix, it will not be recorded under any of the above headings.

## [Unreleased]

### Added
- Gave ice dragons sounds (roaring, growls and a snapping bite)

### Changed
- Updated the readme file to reflect that the DF RAW LS is out of alpha now

### Removed

### Fixed

## [v1.0.0] - 2021-12-25
The initial release, for Christmas! It contains the following:
- Raposa race; basically humans with long ears and fur
- A basic raposa entity/civilization based off the original raposa village; similar to humans, but with more mellow ethics and different religious spheres
- A raposa entity/civilization based off of "Lavasteam" from the DS sequel. Like the normal rapo civ, but based off dwarves instead (and slightly more ethically dubious than regular raposa), and these ones are playable!
- Ice dragons; semi-megabeasts based off the Frostwind boss from the first game
- Banya crop; similar to wheat, though right now it has no special connection to raposa civs, it's just another crop in the world
- Banya crystals; semi-opaque and blue crystals that grow in clusters, they are quite valuable, and... Edible?

<!--Links-->
[Unreleased]: https://github.com/Crabman-DF-Mods/rapo-fortress/compare/v1.0.0...HEAD
[v1.0.0]: https://github.com/Crabman-DF-Mods/rapo-fortress/releases/tag/v1.0.0