<img width="1024" height="247" alt="reners_golde_classic" src="https://github.com/user-attachments/assets/73442643-ea24-4f04-847e-4fb19dd4b7ea" />

# Rener's Golden: Classic — Modlist

> [!WARNING]
> *Last change: 08/08/2026 - WIP - Optimization phase - subject to change.*

Welcome to the official modlist for **Rener's Golden: Classic**, a curated 1.12.2 Minecraft modpack designed to blend nostalgic classic gameplay with modern enhancements, performance stability, and content depth.

---

## Table of Contents
1. [Core, Engine & Libraries](#core-engine--libraries)
2. [Performance & Optimization](#performance--optimization)
3. [User Interface & Client Enhancements](#user-interface--client-enhancements)
4. [Magic & Tech Systems](#magic--tech-systems)
5. [Dimensions & World Generation](#dimensions--world-generation)
6. [Mobs, Creatures & Bosses](#mobs-creatures--bosses)
7. [Structures, Dungeons & Loot](#structures-dungeons--loot)
8. [Equipment, Combat & Mechanics](#equipment-combat--mechanics)
9. [Farming, Food & Building](#farming-food--building)
10. [Utilities & Audio-Visuals](#utilities--audio-visuals)

---

## Core, Engine & Libraries

Essential core loaders, mixin bootstraps, and dependency libraries required for modpack stability and cross-mod functionality.

| Mod Name | File Name | Category / Description |
| :--- | :--- | :--- |
| **CrashAssistant** | `!!!CrashAssistant-forge-1.12.2-1.11.11.jar` | Diagnostic / Crash handling helper |
| **MixinBooter** | `!mixinbooter-11.13.jar` | Core Mixin loading library for 1.12.2 |
| **Red Core** | `!Red-Core-MC-1.8-1.12-0.7.1.jar` | Low-level core mod library |
| **MixinCompat** | `[___MixinCompat-1.1-1.12.2___].jar` | Mixin compatibility layer |
| **MixinBootstrap** | `_MixinBootstrap-1.1.0.jar` | Mixin initialization library |
| **SuperMartijn642's Core Lib** | `_supermartijn642corelib-1.1.22-forge-mc1.12.jar` | Dependency library for SuperMartijn642's mods |
| **Atlas Lib** | `Atlas-Lib-1.12.2-1.1.11.jar` | Dependency library for animation & UI rendering |
| **AutoRegLib** | `AutoRegLib-1.3-32.jar` | Automated registry library for Vazkii's mods |
| **Baubles** | `Baubles-1.12-1.5.2.jar` | Essential accessory slot framework |
| **CarbonConfig** | `CarbonConfig-1.12.2-2.0.2.1.jar` | Configuration management library |
| **Citadel** | `citadel-1.12.2-1.1.0.jar` | Advanced entity animation & modeling library |
| **Collective** | `collective-1.12.2-3.0.jar` | Shared code library for Serilum's mods |
| **Common Capabilities** | `CommonCapabilities-1.12.2-2.4.8.jar` | Cross-mod capability integration |
| **CoroUtil** | `coroutil-1.12.1-1.2.37.jar` | Dependency engine for weather/monster mods |
| **CreativeCore** | `CreativeCore_v1.10.71_mc1.12.2.jar` | Core library for CreativeMD mods |
| **Cucumber Library** | `Cucumber-1.12.2-1.1.3.jar` | Shared code library for BlakeBr0 mods |
| **Cyclops Core** | `CyclopsCore-1.12.2-1.6.7.jar` | Base library for Kroeser's mods |
| **Forgelin** | `Forgelin-1.8.4.jar` | Kotlin language adapter for Forge |
| **GottschCore** | `GottschCore-mc1.12.2-f14.23.5.2859-v1.15.1.jar` | Core library for Gottsch's mods |
| **iChunUtil** | `iChunUtil-1.12.2-7.2.2.jar` | Core framework for iChun's mods |
| **LLibrary** | `llibrary-1.7.20-1.12.2.jar` | Advanced animation API for mob mods |
| **LibraryEx** | `LibraryEx-1.12.2-1.2.2.jar` | Base library for LogicTechCorp mods |
| **Mantle** | `Mantle-1.12-1.3.3.55.jar` | Shared foundation library for SlimeKnights mods |
| **MultiMob Library** | `multimob-1.0.5.jar` | Entity spawning control framework |
| **MysticalLib** | `mysticallib-1.12.2-1.13.0.jar` | Core library for Roots / Mystical World |
| **Nether API** | `Nether-API-v1.4.5-mc1.12.2.jar` | Compatibility layer for Nether biomes |
| **OreLib** | `OreLib-1.12.2-3.6.0.1.jar` | Math & rendering engine dependency |
| **Placebo** | `Placebo-1.12.2-1.6.1.jar` | Shared library for Shadows_of_Fire mods |
| **PTRLib** | `PTRLib-1.0.5.jar` | Model parsing and rendering framework |
| **RenderLib** | `RenderLib-1.12.2-1.4.5.jar` | Rendering system helper library |
| **SuperMartijn642's Config Lib** | `supermartijn642configlib-1.1.8-forge-mc1.12.jar` | Configuration reader library |
| **SynLib** | `synlib-4.0.jar` | Auxiliary framework library |
| **XaeroLib** | `xaerolib-forge-1.12.2-1.7.1.jar` | Essential core engine for Xaero's map mods |

---

## Performance & Optimization

Performance fixes, memory optimization, entity culling, multi-threading, and FPS enhancement mods.

| Mod Name | File Name | Category / Description |
| :--- | :--- | :--- |
| **Async Logger** | `asynclogger-2.2.1+1.12.2-forge.jar` | Asynchronous log writing to prevent I/O lag |
| **AttributeFix** | `AttributeFix-Forge-1.12.2-1.0.12.jar` | Removes hardcoded vanilla attribute caps |
| **BetterFps** | `BetterFps-1.4.8.jar` | Core performance engine and algorithm tuner |
| **Chunk-Pregenerator** | `Chunk-Pregenerator-1.12.2-4.4.9.2.jar` | World pre-generation utility to stop chunk lag |
| **Clumps** | `Clumps-3.1.2.jar` | Groups experience orbs together to reduce lag |
| **Dynamic View Distance** | `dynviewdist-1.12-1.3.jar` | Dynamic render distance tuner based on server load |
| **Entity Culling** | `entityculling-1.12.2-1.6.3.jar` | Asynchronous raytracing to skip rendering hidden entities |
| **ExperienceBugFix** | `ExperienceBugFix-1.12.2-1.0.0.0.jar` | Resolves XP orb jitter and desync issues |
| **Farsight** | `farsight-1.6.jar` | Client-side chunk caching for high render distances |
| **FastFurnace** | `FastFurnace-1.12.2-1.3.1.jar` | Furnace tile entity tick performance overhaul |
| **FastLeafDecay** | `FastLeafDecay-v14.jar` | Accelerates leaf decay upon wood destruction |
| **FoamFix** | `foamfix-0.10.15-1.12.2.jar` | Massive Java heap memory usage optimization |
| **Get It Together Drops** | `getittogetherdrops-1.12.2-v1.0.2.jar` | Aggregates item drops into single stacks |
| **GPU Tape** | `GPUTape-1.12.2-1.0.4.jar` | GPU memory optimization and tick synchronization |
| **Let Me Despawn** | `letmedespawn-1.12.2-forge-1.0.2.jar` | Enforces despawning rules on persistence-budgeted mobs |
| **LolASM** | `loliasm-5.33.jar` | On-demand chunk loading and ASM optimizations |
| **Nothirium** | `Nothirium-1.12.2-0.4.9-beta.jar` | Modernized OpenGL chunk renderer |
| **Particle Culling** | `particleculling-1.12.2-v1.4.3.jar` | Skips rendering occluded particles |
| **Performant** | `performant-1.11.jar` | General entity AI and event system optimization |
| **Roughly Enough IDs** | `RoughlyEnoughIDs-2.3.1.jar` | Expands block, item, and blockstate limits |
| **Spark** | `spark-forge1122.jar` | High-performance CPU and memory profiler tool |
| **Tiquality** | `Tiquality-FAT-1.12.2-GAMMA-1.8.1-124.jar` | Server tick rate stabilizer and chunk allocator |

---

## User Interface & Client Enhancements

Visual HUD updates, inventory controls, map interfaces, tooltips, and customizable menus.

| Mod Name | File Name | Category / Description |
| :--- | :--- | :--- |
| **3D Skin Layers** | `3dSkinLayers-forge-mc1.12.2-1.2.0.jar` | Replaces flat player skin overlays with 3D models |
| **AppleSkin** | `AppleSkin-mc1.12-1.0.14.jar` | Displays accurate saturation and exhaustion HUD values |
| **Better Advancements** | `BetterAdvancements-1.12.2-0.1.0.77.jar` | Fullscreen advancement UI overhaul |
| **BetterChat** | `betterchat-1.4.jar` | Enhanced chat box with tabs, styling, and history |
| **Better Third Person** | `BetterThirdPerson-Forge-1.12.2-1.9.0.jar` | 360-degree rotation in third-person camera mode |
| **Biome Info** | `biomeinfo-1.12.2-v1.2.5.jar` | On-screen current biome notification display |
| **Controlling** | `Controlling-3.0.12.4.jar` | Searchable keybinding configuration menu |
| **Custom Cursor Mod** | `CustomCursorMod-1.2.2.jar` | Custom hardware mouse cursor support |
| **Default Options** | `DefaultOptions_1.12.2-9.2.8.jar` | Forces modpack default keybinds and settings |
| **Durability Tooltip** | `durabilitytooltip-1.1.6-forge-mc1.12.jar` | Shows numerical durability on item mouseover |
| **Enchantment Descriptions** | `EnchantmentDescriptions-1.12.2-1.1.15.jar` | Adds descriptive tooltips to enchanted books |
| **FancyMenu** | `fancymenu_forge_2.14.9_MC_1.12-1.12.2.jar` | Custom main menu layout engine |
| **Forced Resource Packs** | `forcedresourcepacks-1.1.jar` | Enforces modpack client-side resource packs |
| **Highlighter** | `Highlighter-1.12.2-forge-1.1.7.jar` | Highlights newly acquired items in inventory |
| **Hwyla** | `Hwyla-1.8.26-B41_1.12.2.jar` | What-Am-I-Looking-At block and entity information overlay |
| **Item Borders** | `ItemBorders-1.12.2-forge-1.2.0.jar` | Renders rarity color borders around item slots |
| **Item Scroller** | `itemscroller-1.12.2-0.12.0.jar` | Fast inventory item movement with mouse scroll |
| **Jade** | `Jade-0.1.0.jar` | Alternative overlay element display framework |
| **Just Enough Items (JEI)** | `jei_1.12.2-4.16.1.301.jar` | Core recipe and item search index engine |
| **Just Enough Botania** | `Just-Enough-Botania-1.12.2-v0.2.jar` | JEI integration plugin for Botania recipes |
| **Just Enough Resources (JER)** | `JustEnoughResources-1.12.2-0.9.2.60.jar` | World generation drop rates and mob loot for JEI |
| **Konkrete** | `konkrete_forge_1.6.1_MC_1.12-1.12.2.jar` | UI interface library required by FancyMenu |
| **Loading Progress Bar** | `Loading-Progress-Bar-v1.0-mc[1.8-1.12.2].jar` | Custom game launch loading screen bar |
| **Map Tooltip** | `maptooltip-1.12.2-1.0.jar` | Renders map preview directly from inventory slot |
| **Mouse Tweaks** | `MouseTweaks-2.10-mc1.12.2.jar` | Enhanced drag-and-click inventory management |
| **Name Pain** | `namepain-1.5.0 forge-1.12.x.jar` | Recolors player nametags dynamically by health |
| **Nimble** | `Nimble-0.0.2.jar` | Automatic third-person camera during Elytra flights |
| **Obscure Tooltips** | `obscure_tooltips-forge-1.12.2-3.10.2.jar` | Visual overhaul for item tooltip cards |
| **Overloaded Armor Bar** | `overloadedarmorbar-1.0.4g.jar` | Renders high armor points with multi-tier colors |
| **PickUp Notifier** | `PickUpNotifier-v1.1.5-1.12.2.jar` | On-screen toast notifications for acquired items |
| **Tips** | `Tips-1.12.2-1.0.9.jar` | Configurable loading screen tip system |
| **ToroHealth Damage Indicators** | `torohealth-1.12.2-11.jar` | Entity health bar and damage number overlays |
| **WI Zoom** | `wi-zoom-v1.1-MC1.12.2-release.jar` | Ultra-smooth adjustable zoom keybind |
| **Xaero's Minimap** | `xaerominimap-forge-1.12.2-26.4.2.jar` | On-screen minimap HUD with waypoints |
| **Xaero's World Map** | `xaeroworldmap-forge-1.12.2-1.44.2.jar` | Fullscreen interactive world map engine |

---

## Magic & Tech Systems

Magical arts, technological automation, energy grids, and specialized crafting machinery.

| Mod Name | File Name | Category / Description |
| :--- | :--- | :--- |
| **Applied Energistics 2** | `appliedenergistics2-rv6-stable-7.jar` | Matter-to-energy digital storage and auto-crafting |
| **Astral Sorcery** | `astralsorcery-1.12.2-1.10.27.jar` | Starlight-driven magic, starlight altars, and constellations |
| **Bewitchment** | `bewitchment-1.12.2-0.0.22.65.jar` | Spiritual continuation of Witchery; rituals, curses, and voodoo |
| **Botania** | `Botania r1.10-364.4.jar` | Mana-based natural tech and magic mod |
| **Energy Converters** | `energyconverters_1.12.2-1.3.7.30.jar` | Converts energy between EU, FE, RF, and MJ systems |
| **IndustrialCraft 2 (IC2 Classic/Exp)** | `industrialcraft-2-2.8.170-ex112.jar` | Classic tech mod with nuclear reactors and machines |
| **Integrated Dynamics** | `IntegratedDynamics-1.12.2-1.1.11.jar` | Complex logic networks and data automation |
| **Integrated Terminals** | `IntegratedTerminals-1.12.2-1.0.14.jar` | Centralized terminal interface for Integrated Dynamics |
| **Integrated Tunnels** | `IntegratedTunnels-1.12.2-1.6.14.jar` | Item, fluid, and energy transport for Integrated networks |
| **Patchouli** | `Patchouli-1.0-23.6.jar` | In-game documentation and tutorial manual framework |
| **Thaumcraft 6** | `Thaumcraft-1.12.2-6.1.BETA26.jar` | Essential magical research, vis manipulation, and alchemy |

---

## Dimensions & World Generation

New dimensions, biome overhauls, underground world gen, and terrain expansions.

| Mod Name | File Name | Category / Description |
| :--- | :--- | :--- |
| **The Aether** | `aether-1.12.2-v1.5.4.1.jar` | Legendary cloud paradise dimension |
| **Alfheim** | `Alfheim-1.6.jar` | Botania endgame dimension extension |
| **Basic Nether Ores** | `BasicNetherOres-1.12.2-1.0.5.0.jar` | Adds vanilla ore variants to the Nether |
| **BetterEnd Forge Unofficial** | `BetterEndForge-Unofficial-GBPort-1.12.2-1.3.9.jar` | Port of Modern End dimension biomes and structures |
| **Better Nether** | `betternether-0.1.8.6.jar` | Overhauls Nether dimension with flora, biomes, and blocks |
| **Lost Aether Content** | `lost-aether-content-1.12.2-1.0.2.jar` | Restores cut features and items to The Aether |
| **NetherEx** | `NetherEx-1.12.2-2.2.5.jar` | Comprehensive Nether re-exploration and sub-biomes |
| **Novam Terram** | `NovamTerram-7.3.6.3.jar` | Terrain and biome generation extension |
| **Oceanic Expanse** | `OceanicExpanse-1.2.2.jar` | Backports Modern 1.13 aquatic ocean updates |
| **Rare Ice** | `rare-ice-0.1.1.jar` | Adds rare ice variants to cold biomes |
| **The Twilight Forest** | `twilightforest-1.12.2-3.11.1021-universal.jar` | Mystical realm dimension filled with dungeons and bosses |
| **Unseen's Nether Backport** | `unseens-nether-backport-0.7.jar` | Backports 1.16+ Nether features and blocks to 1.12.2 |

---

## Mobs, Creatures & Bosses

Enemies, mythical beasts, ambient wildlife, companion mobs, and boss mechanics.

| Mod Name | File Name | Category / Description |
| :--- | :--- | :--- |
| **Beast Slayer** | `beastslayer-not.2.0.03.release.jar` | Adds aggressive fantasy creatures and mini-bosses |
| **Champions** | `champions-1.12.2-1.0.11.10.jar` | Affix-based champion mob scaling framework |
| **ChocoCraft Plus** | `ChocoCraftPlus-1.12.2-4.5.10.jar` | Chocobo breeding, riding, and armor mechanics |
| **Doggy Talents** | `DoggyTalents-1.12.2-1.15.1.6.jar` | Deep leveling, skill trees, and care for dogs |
| **Dragon Mounts 2** | `DragonMounts2-1.12.2-2.1.2.jar` | Hatch, raise, and ride various Ender Dragon strains |
| **Fish's Undead Rising** | `Fish's Undead Rising-1.6.2.jar` | Undead and mythical aquatic/land monster system |
| **Frozen Fiend** | `Frozen-Fiend-1.5.3.jar` | Arctic hostile mob encounter expansion |
| **Good Skeletons Don't Strafe** | `GoodSkeletonsDontStrafe-v1.1.1-1.12.2.jar` | Removes annoying skeleton strafing movement AI |
| **Hunter Illager** | `hunterillager-1.12.2-1.2.jar` | Adds forest-dwelling hunter illager cabin encounters |
| **Ice and Fire: Dragons** | `iceandfire-1.9.1-1.12.2.jar` | Mythological dragons, gorgons, sea serpents, and bosses |
| **Illagers+** | `IllagersPlus-1.12.2-1.1.3.jar` | Expands illager variants and fortification spawns |
| **Koopa's Critters** | `Koopa's Critters 1.12 II V1.3.jar` | Diverse peaceful and aggressive wildlife additions |
| **Magma Monsters** | `MagmaMonsters-0.3.0.jar` | Fire-based lava creatures |
| **Mowzie's Mobs** | `mowziesmobs-1.5.8.jar` | High-quality animated custom boss encounters |
| **Primitive Mobs** | `primitivemobs-1.2.3a.jar` | Classic style utility and hostile creatures |
| **Rats** | `rats-3.2.14-1.12.2.jar` | Tameable utility rat companions and rat boss fights |
| **Simply Cats** | `simplycats-1.12.2-0.2.2.jar` | Detailed cat breeding and genetics system |
| **Slimy Boyos** | `SlimyBoyos-1.0.0.jar` | Unique slime variants and pet interactions |
| **Scape and Run: Parasites** | `SRParasites-1.12.2v1.9.21.jar` | Evolving parasitic invasion force system |
| **Straw Golem Rebaland** | `strawgolem-1.4.2.ED.jar` | Helpful crop-harvesting straw golems |
| **Wyrms of Nyrus** | `wyrmsofnyrus-0.9.3.jar` | Alien subterranean worms and monstrous creatures |

---

## Structures, Dungeons & Loot

Generated structures, roguelike dungeons, treasure chests, and loot table additions.

| Mod Name | File Name | Category / Description |
| :--- | :--- | :--- |
| **Battle Towers** | `BattleTower-1.12.2.jar` | Classic multi-floor tower dungeons capped with boss fights |
| **Better Strongholds** | `BetterStronghold -0.1.jar` | Complete architectural revamp of End Strongholds |
| **Bountiful** | `Bountiful-2.2.2.jar` | Town bounty boards with quest rewards |
| **Doomlike Dungeons** | `dldungeonsjbg-1.14.17-MC1.12.2.jar` | Procedural maze-like dungeon generator |
| **Lootr** | `lootr-1.12.2-0.6.2.jar` | Per-player instantiated loot chests for multiplayer |
| **Rex's Additional Structures** | `Rex's-AdditionalStructures-1.12.x(v.2.5.0).jar` | Spawns small natural ruins and world details |
| **Roguelike Dungeons (Fnar Edition)** | `RoguelikeDungeonsFnarEdition-1.12.2-2.4.6.jar` | Deep underground procedural dungeon complexes |
| **ToroQuest** | `toroquest-1.12.2-5.3.jar` | Civilization rep, village kingdoms, and quests |
| **Wesley's Roguelike Dungeons** | `Wesley's Roguelike Dungeons V0.8.1.jar` | Massive multi-theme rogue dungeon dungeons |

---

## Equipment, Combat & Mechanics

Weapons, armors, accessories, combat mechanics, and player balance tweaks.

| Mod Name | File Name | Category / Description |
| :--- | :--- | :--- |
| **Aqua Acrobatics** | `AquaAcrobatics-1.15.4.jar` | Backports Modern 1.13 swimming/crawling animations |
| **Artifacts** | `artifacts-1.12.2-1.2.4.jar` | Powerful uncraftable Bauble accessories found in loot |
| **Bountiful Baubles** | `Bountiful Baubles-1.12.2-0.1.8.jar` | Terraria-inspired accessories and bauble items |
| **Colytra** | `colytra-1.12.2-1.2.0.4.jar` | Combines Elytra wings directly onto chestplates |
| **Cosmetic Armor Reworked** | `CosmeticArmorReworked-1.12.2-v5a.jar` | Secondary armor slots for visual appearance without stat loss |
| **Easy Anvils** | `easyanvils-1.1.0.jar` | Modernized anvil mechanics; keeps items on interface |
| **Easy Elytra Takeoff** | `easyeletratakeoff_1.12.2-2.1.jar` | Launch with fireworks from stationary standing position |
| **Easy Magic** | `easymagic-1.2.4.jar` | Modern enchanting table mechanics; retains floating items |
| **Forgiving Void** | `ForgivingVoid_1.12.2-1.1.0.jar` | Falling into the void teleports players to the sky |
| **Grappling Hook Mod** | `grappling_hook_mod-1.12.2-v13.jar` | Physics-based grappling hooks and movement tools |
| **Hammers** | `hammers-2.1.5-1.12.2-forge.jar` | 3x3 mining hammer tools |
| **Iron Jetpacks** | `IronJetpacks-1.12-2-1.1.0.jar` | Tiered power-based jetpacks |
| **MmmMmmMmmMmm** | `MmmMmmMmmMmm-1.12-2.0.7.jar` | Target dummy for DPS and damage testing |
| **Paraglider** | `Paraglider-1.12.2-1.0.1.5.jar` | Zelda-style stamina-draining paraglider |
| **Parry** | `parry-1.0-hotfix.jar` | Sword timing-based parry mechanic |
| **Responsive Shields** | `responsiveshields-2.3-mc1.12.x.jar` | Eliminates shield block activation delays |
| **Spartan Bewitchment** | `spartanbewitchment-1.0.jar` | Bewitchment material compatibility for Spartan Weaponry |
| **Spartan Shields** | `SpartanShields-1.12.2-1.5.5.jar` | Multi-tier specialized shields |
| **Spartan Twilight** | `spartantwilight-1.12.2-1.2.0.jar` | Twilight Forest materials for Spartan weapons |
| **Spartan Weaponry** | `SpartanWeaponry-1.12.2-1.6.1.jar` | Expanded weapon arsenal (halberds, rapiers, longswords) |
| **Tinkers' Construct** | `TConstruct-1.12.2-2.13.0.183.jar` | Custom tool forging with smelteries and unique traits |
| **The Aether Baubles** | `TheAetherBaubles-2.0.1.jar` | Integrates Aether accessory equipment into Baubles |
| **Tombstone** | `tombstone-1.12.2-4.7.6.jar` | Player graves on death with soul magic system |
| **Traveler's Backpack** | `TravelersBackpack-1.12.2-1.0.35.jar` | Portable backpacks with built-in fluid tanks and sleeping bag |
| **Weapon Master** | `weaponmaster_ydm-forge-1.12.2-4.2.3.jar` | Visually renders unequipped weapons on player body |
| **Wither Skeleton Tweaks** | `WitherSkeletonTweaks-1.12.2-2.6.3.jar` | Drops skull fragments and balances wither spawning |
| **XP Tome** | `xptome-1.12.2-v2.0.1.jar` | Storage books for player experience levels |

---

## Farming, Food & Building

Culinary arts, expanded farming, decorative blocks, and building tools.

| Mod Name | File Name | Category / Description |
| :--- | :--- | :--- |
| **Aquaculture 2** | `Aquaculture-1.12.2-1.6.8.jar` | Expanded fishing engine, rare catches, and tackle box |
| **Cherry On Top** | `Cherry_on-1.12.2-1.3.35.jar` | Aesthetic treats and dessert items |
| **Comforts** | `comforts-1.12.2-1.4.1.3.jar` | Sleeping bags and hammocks for day/night passing |
| **Culinary Construct** | `culinaryconstruct-1.3.4.jar` | Custom modular sandwich and burger creation |
| **Decocraft** | `Decocraft-2.6.3.7_1.12.2.jar` | Massive 3D props and furniture decoration library |
| **End's Delight Legacy** | `ends-delight-legacy-1.0.3.jar` | Farmer's Delight expansion for End dimension ingredients |
| **Farmer's Delight Legacy** | `FarmersDelightLegacy-1.1.3-fix1.jar` | Culinary farming, cooking pot, and soil overhaul |
| **Future MC** | `Future-MC-0.2.21.jar` | Backports 1.14+ building blocks, barrels, and lanterns |
| **Iron Barrels** | `IronBarrels1.12.2-V2.0.jar` | Tiered high-capacity barrels |
| **Iron Chests** | `ironchest-1.12.2-7.0.72.847.jar` | Tiered high-capacity metal chests |
| **Iron Core** | `IronCore1.12.2-V1.2.jar` | Shared chest/barrel/furnace logic library |
| **Iron Furnaces** | `ironfurnaces-1.3.5.jar` | Fast, high-tier smelters |
| **KleeSlabs** | `KleeSlabs_1.12.2-5.4.12.jar` | Break individual half-slabs without breaking both |
| **Macaw's Bridges** | `mcw-bridges-1.0.6b-mc1.12.2.jar` | Modular rope and stone bridge construction |
| **Macaw's Doors** | `mcw-doors-1.0.3-mc1.12.2.jar` | Wooden and metal door varieties |
| **Macaw's Fences and Walls** | `mcw-fences-1.0.0-mc1.12.2.jar` | Diverse fencing and wall designs |
| **Macaw's Windows** | `mcw-windows-1.0.0-mc1.12.2.jar` | Architectural window panes and shutters |
| **Nether's Delight Legacy** | `nethers-delight-legacy-1.0.7.jar` | Nether food cooking expansion |
| **Quark** | `Quark-r1.6-179.jar` | Modular vanilla overhaul: building, automation, tweak features |
| **Saplanting** | `saplanting-forge-1.12.2-0.2.jar` | Dropped saplings automatically replant themselves |
| **TreeChop** | `TreeChop-1.12.2-0.14.7.jar` | Dynamic tree chopping and falling animations |
| **Twilight Delight Legacy** | `TwilightDelightLegacy-1.2.0.jar` | Farmer's Delight cooking with Twilight Forest ingredients |

---

## Utilities & Audio-Visuals

Atmospheric soundscapes, dynamic lighting, utility tweaks, and server compatibility tools.

| Mod Name | File Name | Category / Description |
| :--- | :--- | :--- |
| **AmbientSounds 3** | `AmbientSounds_v3.1.7_mc1.12.2.jar` | Immersive spatial biome audio engine |
| **Armor Sound Tweak** | `ArmorSoundTweak-2.1.0.jar` | Realistic gear equipped/unequipped sound effects |
| **Celeritas Dynamic Lights** | `celeritasdynamiclights-1.2.10.jar` | Handheld and dropped dynamic light sources |
| **CTM (Connected Textures Mod)** | `CTM-MC1.12.2-1.0.2.31.jar` | Connected block texture rendering framework |
| **Dynamic Surroundings** | `DynamicSurroundings-1.12.2-3.6.1.0.jar` | Dynamic weather visuals, footstep audio, and visual FX |
| **Friendly Fire** | `FriendlyFire-1.12.2-1.5.10.jar` | Prevents accidentally hitting tamed pets |
| **Galacticraft** | `Galacticraft-1.12.2-4.0.7.jar` | Space exploration, rockets, and celestial bodies |
| **Gnetum** | `gnetum-1.4.3.jar` | World utility and tweak helper |
| **Hats** | `Hats-1.12.2-7.1.1.jar` | Collectible cosmetic headwear for entities |
| **Healing Bed** | `HealingBed 1.12.2 forge.jar` | Slowly restores player health while resting in bed |
| **Lumen** | `lumen-Beta 0.4.1.jar` | Ambient firefly and glowing organism effects |
| **My Server Is Compatible** | `MyServerIsCompatible-1.12.2-1.0.jar` | Protocol handshake fix for client-server connection |
| **NetherPortalFix** | `NetherPortalFix_1.12.1-5.3.17.jar` | Corrects Nether portal destination pairing errors |
| **Smart Particles** | `smart_particles+mc1.12.2-12.02.9-Forge.jar` | Optimized collision-aware particle mechanics |
| **Sound Filters** | `SoundFilters-0.12.1_for_1.12.jar` | Acoustic reverb and muffled audio behind walls |
| **Sulfur & Potassium** | `sulfur-potassium-1.12-1.1.jar` | Alternative ingredients for crafting gunpowder |
| **Swap To Garbage (STG)** | `stg-1.12.2-1.2.3.jar` | Swaps broken tools with matching replacement from inventory |
| **Torchmaster** | `torchmaster_1.12.2-1.8.5.0.jar` | Mega torches to prevent mob spawning in large areas |
| **TrashSlot** | `TrashSlot_1.12.2-8.4.10.jar` | Dedicated trash deletion slot in player inventory |
| **Two Players One Horse** | `twoplayersonehorse-1.12.2-1.0.3.jar` | Allows two players to ride the same horse simultaneously |
| **Waystones** | `Waystones_1.12.2-4.1.0.jar` | Fast travel waystone teleporters |
| **WTS (What's That Song)** | `WTS-1.1.0.jar` | HUD display showing currently playing background music |
| **YARCF** | `YARCF-0.14(1.12.2).jar` | Yet Another Recipe Conflict Fixer utility |
