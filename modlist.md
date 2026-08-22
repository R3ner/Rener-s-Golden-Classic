<a name="top"></a>

# Rener's Golden: Classic — Mod List

> **Status:** Release Phase  
> **Minecraft Version:** 1.12.2  
> **Total JAR Files:** 237

This document contains the complete mod list for **Rener's Golden: Classic**. It is organized by purpose rather than alphabetically, making it easier to understand what each mod contributes to the pack.

## Overview

| Category | Mods |
| --- | ---: |
| Core, Libraries & APIs | 40 |
| Performance & Optimization | 22 |
| World Generation & Dimensions | 18 |
| Magic, Technology & Mechanics | 21 |
| Mobs, Bosses & Creatures | 22 |
| Combat, Equipment & Curios | 24 |
| Building, Farming & Food | 28 |
| UI, Quality of Life (QoL) & Visuals | 62 |

---

## Contents

- [Core, Libraries & APIs](#core-libraries-apis)
- [Performance & Optimization](#performance-optimization)
- [World Generation & Dimensions](#world-generation-dimensions)
- [Magic, Technology & Mechanics](#magic-technology-mechanics)
- [Mobs, Bosses & Creatures](#mobs-bosses-creatures)
- [Combat, Equipment & Curios](#combat-equipment-curios)
- [Building, Farming & Food](#building-farming-food)
- [UI, Quality of Life (QoL) & Visuals](#ui-quality-of-life-qol-visuals)

## Notes

- The JAR filenames below are kept exactly as they appear in the pack.
- Some entries are libraries or compatibility frameworks rather than player-facing mods.
- Descriptions are short functional summaries; the included version is the one currently used by this pack.

---

## 1. Core, Libraries & APIs

*Frameworks, APIs and dependency libraries required by the rest of the pack.*

- **FermiumBooter** — `FermiumBooter-1.5.0.jar`  
  Bootstrapping and compatibility utility used by several optimization and core mods.
- **!CrashAssistant** — `!CrashAssistant-forge-1.12.2-1.11.12.jar`  
  Adds better crash handling and diagnostics to make modded crash reports easier to understand.
- **!mixinbooter** — `!mixinbooter-11.14.jar`  
  Mixin bootstrap and compatibility layer required by mods that inject code into Minecraft.
- **!Red-Core-MC** — `!Red-Core-MC-1.8-1.12-0.7.1.jar`  
  Core library providing shared functionality for mods that depend on Red Core.
- **_MixinBootstrap** — `_MixinBootstrap-1.1.0.jar`  
  Early-loading Mixin bootstrap layer used by dependent mods.
- **_supermartijn642corelib** — `_supermartijn642corelib-1.1.24a-forge-mc1.12.jar`  
  Shared utility library used by SuperMartijn642 mods and related integrations.
- **___MixinCompat___** — `[___MixinCompat-1.1-1.12.2___].jar`  
  Mixin compatibility bridge that helps different Mixin-based mods work together.
- **Atlas-Lib** — `Atlas-Lib-1.12.2-1.1.11.jar`  
  Shared library required by mods from the same developer.
- **AutoRegLib** — `AutoRegLib-1.3-32.jar`  
  Registration and utility library used by Quark and other mods.
- **CarbonConfig** — `CarbonConfig-1.12.2-2.0.2.1.jar`  
  Configuration framework used by mods that expose CarbonConfig settings.
- **Chameleon** — `Chameleon-1.12-4.1.3.jar`  
  Shared rendering and block-color library used by dependent mods.
- **CodeChickenLib** — `CodeChickenLib-1.12.2-3.2.3.358-universal.jar`  
  Core library providing rendering, networking, inventory and utility APIs for CodeChicken-based mods.
- **Collective** — `collective-1.12.2-3.0.jar`  
  Shared code library used by a number of lightweight utility and gameplay mods.
- **CommonCapabilities** — `CommonCapabilities-1.12.2-2.4.8.jar`  
  Capability API library for exposing and sharing common modded data.
- **CoroUtil** — `coroutil-1.12.1-1.2.37.jar`  
  Shared library used by Corosus mods and their entity/world systems.
- **CreativeCore** — `CreativeCore_v1.10.71_mc1.12.2.jar`  
  Core framework and utility library used by CreativeMD mods.
- **CTM** — `CTM-MC1.12.2-1.0.2.31.jar`  
  Connected-textures framework for advanced block and texture connections.
- **Cucumber Library** — `Cucumber-1.12.2-1.1.3.jar`  
  Shared library used by Mystical Agriculture and related mods.
- **CyclopsCore** — `CyclopsCore-1.12.2-1.6.7.jar`  
  Shared code library used by Cyclops mods.
- **EnderCore** — `EnderCore-1.12.2-0.5.78.jar`  
  Core dependency for Ender IO and related Ender components.
- **Forgelin** — `Forgelin-1.8.4.jar`  
  Kotlin support library required by several Forge 1.12.2 mods.
- **FTBLib** — `FTBLib-5.4.7.2.jar`  
  Core library for FTB Utilities and related FTB integrations.
- **FTB Utilities: Xaero Compat** — `ftbuxaerocompat-1.1.1.jar`  
  Compatibility layer connecting FTB Utilities features with Xaero's map mods.
- **GottschCore** — `GottschCore-mc1.12.2-f14.23.5.2859-v1.15.1.jar`  
  Shared library used by Gottsch's structure and dungeon mods.
- **iChunUtil** — `iChunUtil-1.12.2-7.2.2.jar`  
  Core utility library used by iChun's mods.
- **IronCore** — `IronCore1.12.2-V1.2.jar`  
  Shared core library for mods in the same ecosystem.
- **Konkrete** — `konkrete_forge_1.6.1_MC_1.12-1.12.2.jar`  
  Shared utility framework used by mods that depend on Konkrete.
- **LibraryEx** — `LibraryEx-1.12.2-1.2.2.jar`  
  Common library providing shared APIs for dependent mods.
- **LLibrary** — `llibrary-1.7.20-1.12.2.jar`  
  Animation, AI and utility framework used by several advanced entity and content mods.
- **Mantle** — `Mantle-1.12-1.3.3.55.jar`  
  Core library for Tinkers' Construct and related mods.
- **MysticalLib** — `mysticallib-1.12.2-1.13.0.jar`  
  Shared library for Mystical-themed mods.
- **Nether-API** — `Nether-API-v1.4.5-mc1.12.2.jar`  
  API layer for mods that add or modify Nether content.
- **OreLib** — `OreLib-1.12.2-3.6.0.1.jar`  
  Shared library used by tech, ore and utility mods.
- **Patchouli** — `Patchouli-1.0-23.6.jar`  
  In-game documentation and guidebook framework used by many content mods.
- **Placebo** — `Placebo-1.12.2-1.6.1.jar`  
  Shared utility library required by several popular Forge mods.
- **PTRLib** — `PTRLib-1.0.5.jar`  
  Shared library used by mods that depend on PTRLib functionality.
- **RenderLib** — `RenderLib-1.12.2-1.4.5.jar`  
  Rendering utility library for dependent mods.
- **SuperMartijn642's Config Lib** — `supermartijn642configlib-1.1.8-forge-mc1.12.jar`  
  Configuration library for SuperMartijn642 mods.
- **SynLib** — `synlib-4.0.jar`  
  Shared library used by mods from the same ecosystem.
- **XaeroLib** — `xaerolib-forge-1.12.2-1.7.1.jar`  
  Core library shared by Xaero's minimap/world map and related integrations.

[↑ Back to top](#top)

---

## 2. Performance & Optimization

*Client and server-side optimizations focused on FPS, memory usage, tick stability and world generation.*

- **AI Improvements** — `AIImprovements-1.12-0.0.1b3.jar`  
  Optimizes entity AI processing to reduce unnecessary CPU load.
- **AttributeFix** — `AttributeFix-Forge-1.12.2-1.0.12.jar`  
  Raises Minecraft's restrictive attribute limits so mods can safely use larger values.
- **Chunk-Pregenerator** — `Chunk-Pregenerator-1.12.2-4.4.9.2.jar`  
  Pre-generates world chunks to reduce exploration-time generation spikes and server lag.
- **Clumps** — `Clumps-3.1.2.jar`  
  Combines nearby experience orbs into larger stacks, reducing entity count.
- **Dynamic View Distance** — `dynviewdist-1.12-1.3.jar`  
  Dynamically adjusts view distance to help balance visibility and server performance.
- **Entity Culling** — `entityculling-1.12.2-1.6.3.jar`  
  Stops rendering entities that are fully hidden from the camera.
- **ExperienceBugFix** — `ExperienceBugFix-1.12.2-1.0.0.0.jar`  
  Fixes experience-related issues present in the 1.12.2 base game.
- **Farsight** — `farsight-1.6.jar`  
  Lets clients retain distant terrain information beyond normal server view-distance limits.
- **FastFurnace** — `FastFurnace-1.12.2-1.3.1.jar`  
  Optimizes furnace updates and recipe checks.
- **FastLeafDecay** — `FastLeafDecay-v14.jar`  
  Speeds up leaf decay after trees are cut down.
- **Get It Together Drops** — `getittogetherdrops-1.12.2-v1.0.2.jar`  
  Groups nearby item drops together to reduce clutter and entity overhead.
- **GPUTape** — `GPUTape-1.12.2-1.0.4.jar`  
  Improves rendering behavior and GPU-side handling for better client performance.
- **LoliASM** — `loliasm-5.33.jar`  
  Low-level performance framework focused on optimizing Minecraft internals.
- **NetherPortalFix** — `NetherPortalFix_1.12.1-5.3.17.jar`  
  Keeps Nether portal destinations consistent and reduces unwanted portal misrouting.
- **NoiseThreader** — `NoiseThreader-1.1.3.jar`  
  Moves selected world-generation noise work off the main thread where possible.
- **Nothirium** — `Nothirium-1.12.2-0.4.9-beta.jar`  
  High-performance rendering backend aimed at improving FPS and chunk rendering.
- **Particle Culling** — `particleculling-1.12.2-v1.4.3.jar`  
  Avoids rendering particles that are not visible to the player.
- **RamGuard** — `RamGuard-1.12.2-1.0.0.jar`  
  Adds RAM-related safeguards and warnings for modded Minecraft instances.
- **RoughlyEnoughIDs** — `RoughlyEnoughIDs-2.3.1.jar`  
  Expands Minecraft's limited numeric ID space to support large modpacks.
- **Spark** — `spark-forge1122.jar`  
  Performance profiler for diagnosing CPU, memory, tick and server performance issues.
- **STG (SwingThroughGrass)** — `stg-1.12.2-1.2.3.jar`  
  Allows melee swings to pass through grass and similar foliage without hitting it.
- **VintageFix** — `vintagefix-0.7.0.jar`  
  Large-scale client performance and memory optimization suite for Minecraft 1.12.2.

[↑ Back to top](#top)

---

## 3. World Generation & Dimensions

*New dimensions, biomes, structures, terrain features and exploration-focused content.*

- **AbyssalCraft** — `AbyssalCraft-1.12.2-1.11.3.jar`  
  Adds dark-themed dimensions, biomes, structures, mobs, progression and eldritch content.
- **Alfheim (Botania Expansion)** — `Alfheim-1.6.jar`  
  Adds Alfheim-themed content that expands the Botania progression and endgame.
- **Basic Nether Ores** — `BasicNetherOres-1.12.2-1.0.5.0.jar`  
  Adds additional overworld-style ores to the Nether.
- **BetterEnd (Unofficial Port)** — `BetterEndForge-Unofficial-GBPort-1.12.2-1.3.9.jar`  
  Unofficial 1.12.2 port bringing expanded End biomes and environmental content.
- **BetterNether** — `betternether-0.1.8.6.jar`  
  Overhauls the Nether with new biomes, plants, terrain features and resources.
- **Better Strongholds** — `BetterStronghold -0.1.jar`  
  Improves vanilla strongholds with more variety and exploration-focused layouts.
- **Blue Skies** — `blue_skies-1.12.2-v1.1.3.jar`  
  Adds two large dimensions with new biomes, structures, mobs, bosses and progression.
- **Doomlike Dungeons** — `dldungeonsjbg-1.14.17-MC1.12.2.jar`  
  Generates dense, multi-room dungeons inspired by classic dungeon-crawler layouts.
- **Lost Aether Content** — `lost-aether-content-1.12.2-1.0.2.jar`  
  Adds additional content for the Aether ecosystem.
- **NetherEx** — `NetherEx-1.12.2-2.2.5.jar`  
  Expands and overhauls Nether terrain, biomes, structures and resources.
- **Novam Terram** — `NovamTerram-7.3.6.3.jar`  
  Adds a broad set of world-generation features, terrain, biomes and exploration content.
- **Oceanic Expanse** — `OceanicExpanse-1.2.2.jar`  
  Expands ocean exploration with new aquatic terrain and content.
- **Rex's Additional Structures** — `Rex's-AdditionalStructures-1.12.x(v.2.5.0).jar`  
  Adds additional structures to discover throughout the overworld.
- **Roguelike Dungeons - Fnar Edition** — `RoguelikeDungeonsFnarEdition-1.12.2-2.4.6.jar`  
  Generates large roguelike-style dungeon complexes filled with rooms and loot.
- **The Aether** — `aether-1.12.2-v1.5.4.1.jar`  
  Adds the Aether dimension, with floating islands, unique mobs, dungeons and progression.
- **The Twilight Forest** — `twilightforest-1.12.2-3.11.1021-universal.jar`  
  Adds a large adventure dimension centered around bosses, dungeons, exploration and unique biomes.
- **Unseen's Nether Backport** — `unseens-nether-backport-0.7.jar`  
  Backports selected Nether features and mechanics from newer Minecraft versions.
- **Wesley's Roguelike Dungeons** — `Wesley's Roguelike Dungeons V0.8.1.jar`  
  Adds another set of procedural roguelike dungeon structures for exploration.

[↑ Back to top](#top)

---

## 4. Magic, Technology & Mechanics

*Large progression systems covering technology, automation, magic, storage and custom mechanics.*

- **Applied Energistics 2: Extended Life** — `ae2-uel-v0.56.6.jar`  
  Extended Life fork of Applied Energistics 2, providing advanced digital storage, automation and item processing.
- **Astral Sorcery** — `astralsorcery-1.12.2-1.10.27.jar`  
  Starlight-based magic system focused on rituals, constellations, exploration and powerful celestial abilities.
- **Botania** — `Botania r1.10-364.4.jar`  
  Tech-like magical mod centered around natural mana, flowers, automation and magical devices.
- **BuildCraft** — `buildcraft-all-8.0.0.jar`  
  Classic technology mod featuring pipes, engines, power, quarrying and automated resource handling.
- **CraftTweaker2** — `CraftTweaker2-1.12-4.1.20.715.jar`  
  Lets pack creators script and customize recipes, loot and other game mechanics.
- **Ender IO** — `EnderIO-1.12.2-5.3.72.jar`  
  Technology suite offering conduits, machines, power generation, automation and compact processing.
- **Ender Storage** — `EnderStorage-1.12.2-2.4.6.137-universal.jar`  
  Adds color-coded ender-linked storage containers and backpacks.
- **Energy Converters** — `energyconverters_1.12.2-1.3.7.30.jar`  
  Converts between different modded energy systems for cross-mod compatibility.
- **Extra Utilities 2** — `extrautils2-1.12-1.9.9.jar`  
  Adds a wide range of utility blocks, machines, generators, transport tools and gameplay features.
- **Galacticraft** — `Galacticraft-1.12.2-4.0.7.jar`  
  Adds space travel, planets, rockets, oxygen systems and space-survival gameplay.
- **IndustrialCraft 2** — `industrialcraft-2-2.8.170-ex112.jar`  
  Classic industrial technology mod featuring generators, machines, power networks and resource processing.
- **OpenBlocks Reopened** — `OpenBlocksReopened-1.12.2-1.8.3.1.jar`  
  Reopened continuation of OpenBlocks-style utility and automation content.
- **Quark** — `Quark-r1.6-179.jar`  
  Large collection of vanilla-friendly building, utility, world and quality-of-life improvements.
- **SecurityCraft** — `[1.12.2] SecurityCraft v1.10.1.jar`  
  Adds security systems such as cameras, reinforced blocks, alarms and access-control tools.
- **Storage Drawers** — `StorageDrawers-1.12.2-5.5.3.jar`  
  Compact storage system centered around high-capacity drawers and visual item storage.
- **Thaumcraft 6** — `Thaumcraft-1.12.2-6.1.BETA26.jar`  
  Deep magical progression based on research, essentia, alchemy, wands, exploration and eldritch knowledge.
- **Tinkers' Construct** — `TConstruct-1.12.2-2.13.0.183.jar`  
  Modular tool and weapon crafting system with customizable materials, parts and modifiers.
- **Tinkers' Tool Leveling** — `TinkerToolLeveling-1.12.2-1.1.0.jar`  
  Adds experience-based leveling and additional modifiers for Tinkers' Construct tools.
- **Witchery** — `witchery-1.7.10-0.24.1.jar`  
  Dark fantasy magic system featuring rituals, potions, curses, transformations and supernatural mechanics.
- **Witchery Companion** — `witcherycompanion-0.36.2-beta.jar`  
  Additional integration and supporting content for Witchery.
- **Witchery: Resurrected** — `WitcheryResurrected-1.12.2-0.5.2.4-forge-all.jar`  
  Community continuation of Witchery with restored and expanded supernatural gameplay.

[↑ Back to top](#top)

---

## 5. Mobs, Bosses & Creatures

*New creatures, enemy variants, companions, bosses and wildlife.*

- **Beast Slayer** — `beastslayer-not.2.0.03.release.jar`  
  Adds hostile creatures and combat-focused encounters for more dangerous exploration.
- **Champions** — `champions-1.12.2-1.0.11.10.jar`  
  Creates enhanced elite mobs with affixes, stronger stats and special abilities.
- **ChocoCraft Plus** — `ChocoCraftPlus-1.12.2-4.5.10.jar`  
  Adds chocobo creatures that can be found, tamed, bred and used for travel.
- **Doggy Talents** — `DoggyTalents-1.12.2-1.15.1.6.jar`  
  Expands wolves into trainable companions with many configurable talents and utility roles.
- **Dragon Mounts 2** — `DragonMounts2-1.12.2-2.1.2.jar`  
  Adds breedable and rideable dragons with multiple elemental variants.
- **Eyes in the Darkness** — `EyesInTheDarkness-0.1.0.jar`  
  Introduces a mysterious hostile creature that lurks in dark areas.
- **Fish's Undead Rising** — `Fish's Undead Rising-1.6.2.jar`  
  Adds new undead enemies and combat encounters.
- **Fossils and Archaeology Revival** — `fossilsarcheology-8.0.6.jar`  
  Adds fossils, archaeology, prehistoric creatures, relics and restoration mechanics.
- **Frozen Fiend** — `Frozen-Fiend-1.5.3.jar`  
  Adds an icy-themed hostile creature and related encounters.
- **Ice and Fire: Dragons** — `iceandfire-1.9.1-1.12.2.jar`  
  Adds dragons and other mythical creatures, structures, items and boss-like encounters.
- **Illagers+** — `IllagersPlus-1.12.2-1.1.3.jar`  
  Adds new illager variants, equipment and encounters to expand hostile village-raider gameplay.
- **Magma Monsters** — `MagmaMonsters-0.3.0.jar`  
  Introduces magma-themed hostile mobs and related combat content.
- **Mo' Creatures** — `mocreatures-12.5.1.jar`  
  Adds a large variety of passive, neutral and hostile animals and monsters.
- **Mowzie's Mobs** — `mowziesmobs-1.5.8.jar`  
  Adds high-quality custom mobs with unique AI, animations and challenging combat mechanics.
- **MultiMob** — `multimob-1.0.5.jar`  
  Provides additional mobs and creature-related gameplay content.
- **Mystical World** — `mysticalworld-1.12.2-1.11.0.jar`  
  Adds extra animals, monsters, blocks and resources while staying close to vanilla style.
- **Primitive Mobs** — `primitivemobs-1.2.3a.jar`  
  Expands the hostile and passive mob roster with new creatures and utility mechanics.
- **Rats** — `rats-3.2.14-1.12.2.jar`  
  Adds rats, taming, breeding, automation and a large set of rat-based mechanics and items.
- **Simply Cats** — `simplycats-1.12.2-0.2.2.jar`  
  Adds tameable cats and extra feline variants and interactions.
- **Spiders 2.0** — `spiders-2.0-1.12.2-1.0.3.jar`  
  Improves spiders with new movement behavior and additional spider variants.
- **Straw Golem Reborn** — `strawgolem-1.4.2.ED.jar`  
  Adds small straw golems that help with simple farming tasks.
- **Wither Skeleton Tweaks** — `WitherSkeletonTweaks-1.12.2-2.6.3.jar`  
  Expands and adjusts wither skeleton behavior and related combat mechanics.

[↑ Back to top](#top)

---

## 6. Combat, Equipment & Curios

*Weapons, shields, accessories, mobility equipment and combat-focused mechanics.*

- **Armored Arms** — `ArmoredArms-v1.5.3-1.12.2-release.jar`  
  Adds additional combat-focused arm and weapon mechanics.
- **Artifacts** — `artifacts-1.12.2-1.2.4.jar`  
  Adds rare exploration loot with powerful wearable artifacts and unique bonuses.
- **Baubles** — `Baubles-1.12-1.5.2.jar`  
  Adds an accessory slot system for wearable trinkets and equipment.
- **Bountiful Baubles** — `Bountiful Baubles-1.12.2-0.1.8.jar`  
  Adds additional baubles, curios and utility accessories with configurable effects.
- **Colytra** — `colytra-1.12.2-1.2.0.4.jar`  
  Allows elytra flight while wearing compatible chest armor.
- **Cosmetic Armor Reworked** — `CosmeticArmorReworked-1.12.2-v5a.jar`  
  Separates cosmetic armor appearance from the armor that provides your actual stats.
- **Crossbows Backport** — `Crossbows-Backport-1.12.2-1.1.1.jar`  
  Backports crossbow mechanics and related content to 1.12.2.
- **Easy Anvils** — `easyanvils-1.1.0.jar`  
  Adds quality-of-life improvements to anvil use and configuration.
- **Easy Elytra Takeoff** — `easyelytratakeoff_1.12.2-2.1.jar`  
  Makes taking off with an elytra quicker and more convenient.
- **Easy Magic** — `easymagic-1.2.4.jar`  
  Improves enchanting-table interaction and makes enchantment setup more convenient.
- **Forgiving Void** — `ForgivingVoid_1.12.2-1.1.0.jar`  
  Prevents some accidental deaths from falling into the void by applying a configurable recovery behavior.
- **Grappling Hook Mod** — `grappling_hook_mod-1.12.2-v13.jar`  
  Adds grappling hooks for fast traversal, mobility and creative movement.
- **Hammers** — `hammers-2.1.5-1.12.2-forge.jar`  
  Adds multi-block mining hammers for clearing larger areas of blocks.
- **Improved Backpacks** — `ImprovedBackpacks-1.12.2-1.5.0.0.jar`  
  Provides upgraded backpacks with larger storage and additional features.
- **Iron Jetpacks** — `IronJetpacks-1.12-2-1.1.0.jar`  
  Adds tiered jetpacks powered by modded energy systems.
- **Paraglider** — `Paraglider-1.12.2-1.0.1.5.jar`  
  Adds stamina-based gliding and traversal mechanics inspired by modern adventure games.
- **Parry** — `parry-1.0-hotfix.jar`  
  Adds timed parrying mechanics to make blocking more active and skill-based.
- **Responsive Shields** — `responsiveshields-2.3-mc1.12.x.jar`  
  Improves shield response and blocking behavior.
- **Spartan Shields** — `SpartanShields-1.12.2-1.5.5.jar`  
  Adds a broader selection of shields with different materials and stats.
- **Spartan Twilight** — `spartantwilight-1.12.2-1.2.0.jar`  
  Adds shield and weapon compatibility content for Twilight Forest progression.
- **Spartan Weaponry** — `SpartanWeaponry-1.12.2-1.6.1.jar`  
  Expands the weapon roster with spears, pikes, daggers, longswords and more.
- **The Aether Baubles** — `TheAetherBaubles-2.0.1.jar`  
  Adds accessory integration between Aether content and the Baubles system.
- **Weapon Master** — `weaponmaster_ydm-forge-1.12.2-4.2.3.jar`  
  Adds configurable weapon switching and hotbar combat utilities.
- **XP Tome** — `xptome-1.12.2-v2.0.1.jar`  
  Adds a portable item for storing and retrieving accumulated experience.

[↑ Back to top](#top)

---

## 7. Building, Farming & Food

*Building utilities, storage, farming, cooking, decorative blocks and food systems.*

- **Aquaculture** — `Aquaculture-1.12.2-1.6.8.jar`  
  Expands fishing with new fish, fishing rods, loot and aquatic content.
- **Better Builder's Wands** — `BetterBuildersWands-1.12-0.11.1.245+69d0d70.jar`  
  Provides upgraded building wands for placing large numbers of blocks quickly.
- **Bountiful** — `Bountiful-2.2.2.jar`  
  Adds bounties, contracts and reward-driven tasks for exploration and progression.
- **Comforts** — `comforts-1.12.2-1.4.1.3.jar`  
  Adds sleeping bags and hammocks for portable sleeping without permanently changing spawn.
- **Culinary Construct** — `culinaryconstruct-1.3.4.jar`  
  Adds a food container system for combining ingredients into customizable meals.
- **Ender Crop** — `endercrop-1.12.2-1.6.0.jar`  
  Adds an ender-themed crop that produces materials associated with the End dimension.
- **End's Delight Legacy** — `ends-delight-legacy-1.0.3.jar`  
  Adds End-themed food, ingredients and culinary content.
- **Farmer's Delight Legacy** — `FarmersDelightLegacy-1.1.6.jar`  
  Backports Farmer's Delight-style cooking and food systems to 1.12.2.
- **Future MC** — `Future-MC-0.2.21.jar`  
  Backports selected features and items from newer Minecraft versions.
- **Gnetum** — `gnetum-1.4.3.jar`  
  Adds additional plants, resources and utility-focused content.
- **Healing Bed** — `HealingBed 1.12.2 forge.jar`  
  Adds a bed variant that provides enhanced healing effects while resting.
- **Iron Barrels** — `IronBarrels1.12.2-V2.0.jar`  
  Adds high-capacity barrels for compact item storage.
- **Iron Chests** — `ironchest-1.12.2-7.0.72.847.jar`  
  Adds upgradeable chests with significantly larger storage capacities.
- **Iron Furnaces** — `ironfurnaces-1.3.5.jar`  
  Adds faster furnace tiers for more efficient smelting.
- **KleeSlabs** — `KleeSlabs_1.12.2-5.4.12.jar`  
  Allows safer slab placement and easier slab manipulation, especially for building.
- **Lootr** — `lootr-1.12.2-0.6.2.jar`  
  Makes loot containers unique per player, reducing multiplayer competition for generated loot.
- **Macaw's Bridges** — `mcw-bridges-1.0.6b-mc1.12.2.jar`  
  Adds decorative and functional bridge blocks and variants.
- **Macaw's Doors** — `mcw-doors-1.0.3-mc1.12.2.jar`  
  Adds many decorative door styles and variants for builders.
- **Macaw's Fences** — `mcw-fences-1.0.0-mc1.12.2.jar`  
  Adds additional fence and railing styles for detailed builds.
- **Macaw's Windows** — `mcw-windows-1.0.0-mc1.12.2.jar`  
  Adds decorative windows, panes and frames in multiple styles.
- **MmmMmmMmmMmm (Target Dummy)** — `MmmMmmMmmMmm-1.12-2.0.7.jar`  
  Adds a target dummy for testing weapons, damage and combat setups.
- **Ne-Carpenters-Blocks** — `Ne-Carpenters-Blocks-0.1.4-fix.jar`  
  Adds configurable decorative blocks inspired by the classic Carpenter's Blocks concept.
- **Nether's Delight Legacy** — `nethers-delight-legacy-1.0.7.jar`  
  Adds Nether-themed cooking ingredients, foods and culinary recipes.
- **Sulfur & Potassium** — `sulfur-potassium-1.12-1.1.jar`  
  Adds additional sulfur/potassium resources and related crafting content.
- **Torchmaster** — `torchmaster_1.12.2-1.8.5.0.jar`  
  Adds special lighting blocks that prevent hostile mob spawning in selected areas.
- **TreeChop** — `TreeChop-1.12.2-0.14.7.jar`  
  Lets players chop whole trees more conveniently while retaining tool and durability rules.
- **Twilight Delight Legacy** — `TwilightDelightLegacy-1.2.0.jar`  
  Adds food and cooking content themed around Twilight Forest resources.
- **YARCF** — `YARCF-0.14(1.12.2).jar`  
  Adds additional food and resource-focused crafting content.

[↑ Back to top](#top)

---

## 8. UI, Quality of Life (QoL) & Visuals

*Interface improvements, HUD information, maps, audio, visuals and everyday quality-of-life tools.*

- **3D Skin Layers** — `3dSkinLayers-forge-mc1.12.2-1.2.0.jar`  
  Renders the second skin layer in 3D for a more detailed player appearance.
- **Ambient Environment** — `AmbientEnvironment-1.0.2.jar`  
  Adds subtle environmental visual effects to make biomes feel more alive.
- **AmbientSounds** — `AmbientSounds_v3.1.7_mc1.12.2.jar`  
  Overhauls environmental audio with biome- and location-aware soundscapes.
- **AppleSkin** — `AppleSkin-mc1.12-1.0.14.jar`  
  Shows useful food and saturation information directly in the HUD.
- **Aqua Acrobatics** — `AquaAcrobatics-1.15.4.jar`  
  Improves underwater movement, swimming and aquatic traversal.
- **Armor Sound Tweak** — `ArmorSoundTweak-2.1.0.jar`  
  Adjusts and improves armor-related sound effects.
- **Better Advancements** — `BetterAdvancements-1.12.2-0.1.0.77.jar`  
  Provides a more usable and readable advancements interface.
- **Better Chat** — `betterchat-1.4.jar`  
  Improves chat presentation and readability with additional customization.
- **Better Third Person** — `BetterThirdPerson-Forge-1.12.2-1.9.0.jar`  
  Adds a more flexible third-person camera with improved positioning and control.
- **Biome Info** — `biomeinfo-1.12.2-v1.2.5.jar`  
  Displays biome-related information directly to the player.
- **Colorful Health Bar** — `colorfulhealthbar-0.0.4a.jar`  
  Adds more informative and customizable health-bar visuals.
- **Controlling** — `Controlling-3.0.12.4.jar`  
  Adds search and management tools for keybindings.
- **Corpse** — `corpse-1.12.2-1.0.8.jar`  
  Creates a persistent corpse container when a player dies, keeping their inventory together.
- **Custom Cursor Mod** — `CustomCursorMod-1.2.2.jar`  
  Allows the mouse cursor used by the game UI to be customized.
- **Custom Skin Loader** — `CustomSkinLoader_Universal-15.0.1.jar`  
  Provides alternate/custom skin loading support on older Minecraft versions.
- **Deeper Depths** — `Deeper-Depths-1.12.2-1.1.1a.jar`  
  Expands underground exploration with deeper terrain and subterranean content.
- **Default Options** — `DefaultOptions_1.12.2-9.2.8.jar`  
  Lets modpack authors ship default client settings with the pack.
- **Durability Tooltip** — `durabilitytooltip-1.1.6-forge-mc1.12.jar`  
  Displays item durability directly in tooltips.
- **Dynamic Surroundings** — `DynamicSurroundings-1.12.2-3.6.1.0.jar`  
  Improves environmental audio and adds immersive atmosphere and effects.
- **Enchantment Descriptions** — `EnchantmentDescriptions-1.12.2-1.1.15.jar`  
  Shows readable descriptions for enchantments in item tooltips.
- **Falling Leaves** — `fallingleaves-2.1.2.2.jar`  
  Adds decorative falling-leaf particles around trees.
- **FancyMenu** — `fancymenu_forge_2.14.9_MC_1.12-1.12.2.jar`  
  Provides highly customizable main menus, overlays and in-game UI screens.
- **Forced Resource Packs** — `forcedresourcepacks-1.1.jar`  
  Helps enforce required resource packs on clients.
- **Friendly Fire** — `FriendlyFire-1.12.2-1.5.10.jar`  
  Adds control over whether players can damage allies, pets or teammates.
- **FTB Utilities** — `FTBUtilities-5.4.1.131.jar`  
  Provides utilities such as claims, teams, waypoints, teleportation and server tools.
- **Good Skeletons Don't Strafe** — `GoodSkeletonsDontStrafe-v1.1.1-1.12.2.jar`  
  Changes skeleton movement so their ranged combat feels more straightforward.
- **Googly Eyes** — `GooglyEyes-1.12.2-7.1.1.jar`  
  Adds a playful visual effect that gives entities googly eyes.
- **Highlighter** — `Highlighter-1.12.2-forge-1.1.7.jar`  
  Highlights items and blocks under the cursor for better visibility.
- **Hwyla** — `Hwyla-1.8.26-B41_1.12.2.jar`  
  Displays information about the block or entity you are looking at.
- **Instant Skin** — `InstantSkin.jar`  
  Speeds up or simplifies skin retrieval and display on supported setups.
- **Inventory Totem** — `inventorytotem_1.12.2-1.3.jar`  
  Shows totem-related inventory information more clearly and conveniently.
- **Inventory Tweaks** — `InventoryTweaks-1.63.jar`  
  Adds extensive inventory sorting and management shortcuts.
- **Item Borders** — `ItemBorders-1.12.2-forge-1.2.0.jar`  
  Adds colored borders around inventory items based on item rarity.
- **Item Scroller** — `itemscroller-1.12.2-0.12.0.jar`  
  Enables fast mouse-based item transfers and scrolling through inventories.
- **Jade** — `Jade-0.1.0.jar`  
  Adds an on-screen information overlay for blocks, entities and containers.
- **JEI (Just Enough Items)** — `jei_1.12.2-4.16.1.301.jar`  
  Recipe and item browser for viewing crafting, smelting and usage information.
- **Just Enough Botania** — `Just-Enough-Botania-1.12.2-v0.2.jar`  
  Adds JEI-style recipe and information support for Botania content.
- **Just Enough Resources (JER)** — `JustEnoughResources-1.12.2-0.9.2.60.jar`  
  Extends JEI with information about ores, drops and world-generation resources.
- **Map Tooltip** — `maptooltip-1.12.2-1.0.jar`  
  Shows extra map-related information through item tooltips.
- **MCEF (Minecraft Chromium Embedded Framework)** — `mcef-1.12.2-1.11.jar`  
  Embeds Chromium-based web content inside Minecraft for mods and interfaces that need it.
- **Mouse Tweaks** — `MouseTweaks-2.10-mc1.12.2.jar`  
  Improves inventory interaction with faster dragging, clicking and item movement.
- **My Server Is Compatible** — `MyServerIsCompatible-1.12.2-1.0.jar`  
  Helps communicate modpack/server compatibility information to players.
- **Name Pain** — `namepain-1.5.0 forge-1.12.x.jar`  
  Improves the rendering and handling of long or problematic name tags.
- **Nimble** — `Nimble-0.0.2.jar`  
  Adds small client-side movement and interaction quality-of-life improvements.
- **Obscure Tooltips** — `obscure_tooltips-forge-1.12.2-3.10.2.jar`  
  Improves item tooltips with additional context and readability.
- **Overloaded Armor Bar** — `overloadedarmorbar-1.0.4g.jar`  
  Allows armor and related HUD values to display beyond vanilla limits.
- **Pickup Notifier** — `PickUpNotifier-v1.1.5-1.12.2.jar`  
  Displays a visual notification when items are picked up.
- **Raids Backport** — `Raids-Backport-1.12.2-1.1.5b.jar`  
  Backports raid gameplay and related mechanics to Minecraft 1.12.2.
- **Server Tab Info** — `ServerTabInfo-1.12.2-1.2.6.jar`  
  Adds more server and player information to the tab list.
- **Smart Particles** — `smart_particles+mc1.12.2-12.02.9-Forge.jar`  
  Reduces unnecessary particle rendering to improve visual performance.
- **Sound Filters** — `SoundFilters-0.12.1_for_1.12.jar`  
  Adds environmental sound filtering such as muffled audio behind walls.
- **Spiritual Comeback** — `SpiritualComeBack-1.12.2-1.0.0.jar`  
  Lets players return after death in spirit form to recover their items or interact with death-related mechanics.
- **ToroHealth Damage Indicators** — `torohealth-1.12.2-11.jar`  
  Displays enemy health and damage information in a compact HUD.
- **Toughness Bar** — `toughnessbar-2.4.jar`  
  Adds a visible armor-toughness indicator to the HUD.
- **TrashSlot** — `TrashSlot_1.12.2-8.4.10.jar`  
  Adds a dedicated trash slot for quickly deleting unwanted items.
- **VisualOres** — `visualores-0.2.8.jar`  
  Adds visual highlights and effects to ores for easier identification underground.
- **WAILA Harvestability** — `WailaHarvestability-mc1.12-1.1.12.jar`  
  Shows whether a targeted block can be harvested with your current tool.
- **Waystones** — `Waystones_1.12.2-4.1.0.jar`  
  Adds craftable waystones for fast travel and linked teleportation.
- **WI Zoom** — `wi-zoom-v1.1-MC1.12.2-release.jar`  
  Adds a zoom function similar to a camera zoom key.
- **WTS (What's That Slot)** — `WTS-1.1.0.jar`  
  Identifies inventory slots and explains what items can be placed there.
- **Xaero's Minimap** — `xaerominimap-forge-1.12.2-26.4.2.jar`  
  Adds a detailed minimap with waypoints, entity markers and configurable overlays.
- **Xaero's World Map** — `xaeroworldmap-forge-1.12.2-1.44.2.jar`  
  Adds a full-screen world map with exploration data and waypoint support.

[↑ Back to top](#top)

---
