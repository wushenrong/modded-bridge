# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Calendar Versioning](https://calver.org/).
Versions before 26.1 adheres to a loose version of
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [26.3] - 2026-08-04

Fast tracks changes from Additive versions 26.2 to 26.4.3. Adds support for
Minecraft version 26.2 but expect missing mods and features.

Missing mods on 26.2:

-   Default Mods
    - Fabrishot
    - Fix Keyboard on Linux
    - FlickerFix
    - Just Enough Breeding
    - Tag Tooltips
    - Tag Translations for JEI
    - Torohealth Continued

-   Optional Mods
    - Jump Over Fences

Missing mods on 26.1.2:

-   Default Mods
    - Fix Keyboard on Linux
    - Just Enough Breeding

-   Optional Mods
    - Jump Over Fences

Missing mods on 1.21.1:

-   Default Mods
    - Cull Less Leaves

### Added

- Support for version 26.2.
- Durability Tooltips, Polytone, and Emoji Type for versions 26.1.2 and later
- Async Logger
- Structure Layout Optimizer
- Kerria for version 1.21.1
- Nanite Library for versions 26.2.1 and later

### Changed

- Update mods to their latest versions.
- Enable Sneaky Capes in Cape Provider.
- Raise dynamic fps unfocused target from 2 to 10.
- Swapped Enhanced Block Entities to Better Block Entities for version 1.21.1.
- Swapped Particular and Patches to Particular Reforged for version 1.21.1.
- Fix Squat Grow configuration for version 1.21.1.
- Add default ignored plants to Squat Grow configuration.

### Removed

- owo-lib for version 1.21.1
- Sodium Leaf Culling for version 1.21.1
- Twemoji

## [26.2] - 2026-06-08

Adds beta support for version 26.1.x, but expect missing features/mods:

-   Default Mods
    - Durability Tooltips
    - Fix Keyboard on Linux
    - Just Enough Breeding

-   Optional Mods
    - Jump Over Fences
    - Polytone
    - Emoji Type

Reorganized and marked visual and audio enhancements and multiplayer mods as
optional. See the mod list for mods that were made optional.

### Added

- Crops Love Rain
- Distant Horizons
- Falling Leaves
- Flashback
- Let Me Despawn
- No Chat Restrictions
- No Crop Trample
- Particular Patches for version 1.21.1
- Skin Restorer
- ToroHealth Continued
- Twemoji

### Changed

- Updated all mods to their latest version
- All visual and audio enhancements and multiplayer mods as optional
- Animatica to Animatica Refabricated for versions 1.21.11 and later
- e4mc to e4all
- macOS-Input-Fix to macOS Input Fixes
- More Chat History to Chat Patches
- Random Bone Meal Flowers to Universal Bone Meal

### Removed

- Unnecessary options
- Default keybinds
- Better Compatibility Checker
- Emote Craft
- Gravestones
- Jade Modded Entities
- Load My F***ing Tags

## [26.1] - 2026-04-05

Switched to Calendar Versioning.

### Added

- Gravestones
- Trade Cycling
- Visual Workbench

### Changed

- Updated all mods to their latest version.
- Update and trim the crash assistant configuration.
- Add Continuity to the resource pack list.
- Ignored additional plants that act like grass.

### Removed

- Clumps

## [1.2.1] - 2026-03-28

### Changed

- Unmark mods as optional for 1.21.1.

## [1.2.0] - 2026-03-27

### Added

- Armor Hider
- Bow Infinity Fix
- Bridging Mod
- Collective
- Cut Through
- First-person Model
- Jump Over Fences
- Leaves Be Gone
- Random Bone Meal Flowers
- Squat Grow

### Changed

- Update mods to their latest version.
- Swap Better Advancements for Paginated Advancements & Custom Frames.

### Removed

- Simple Discord RPC

## [1.1.0] - 2026-03-26

### Added

- Mostly parity support for 1.21.1 and configs from Additive.
- Configuration for Better Compatibility Checker.

#### 1.21.1 Mods

- CIT Resewn
- Enhanced Block Entities
- Sodium Leaf Culling
- Bookshelf

#### 1.21.11 Mods

- Auth Me
- Emotecraft
- Enchantment Descriptions
- Particular ✨ Reforged
- Player Animation Library
- Status Effect Bars
- WITS (What Is This Structure?)

### Changed

- Update all mods.
- Swap Pickup Notifications for Pick Up Notifier.
- Change "Simple Chocolate Minecraft" to "Modded Bridge" in Crash Assistant.
- Fix Better Compatibility Checker's configuration.

### Removed

- Distant Horizons and its `options.txt` settings
- Flashback

#### 1.21.1 Mods

- Better Block Entities
- Tag Translations for JEI
- Cull Fewer Leaves

## [1.0.0] - 2026-03-22

Initial Release

### Added

- See the initial dependency list and [config changes](CONFIG_CHANGES.md).
