<img width="1024" height="217" alt="title_classic" src="https://github.com/user-attachments/assets/813f7b65-2cc9-4dd7-9f8a-00bb5371e217" />


**Rener's Golden: Classic** is a meticulously engineered 1.12.2 Minecraft modpack designed to bridge the golden era of classic modded gameplay with modern performance standards, fluid quality-of-life features, and deep progression systems.

Built on an optimized Forge 1.12.2 backbone using modern mixin loaders, multi-threaded world noise generation, and asynchronous rendering pipelines, **Rener's Golden: Classic** delivers an expansive survival experience without compromising client or server stability.

---

## Table of Contents
1. [Overview](#overview)
2. [Key Features](#key-features)
3. [Modpack Composition](#modpack-composition)
4. [Installation & Requirements](#installation--requirements)
5. [Configuration & Performance Tips](#configuration--performance-tips)
6. [Modlist & Documentation](#modlist--documentation)

---

## Overview

Minecraft version 1.12.2 remains one of the most celebrated eras for technical automation, magical mastery, and sandbox depth. **Rener's Golden: Classic** honors this heritage by assembling legendary core mods alongside modernized engine backports and visual enhancements.

Whether you are automating multi-block industrial reactors, mastering starlight and eldritch sorcery, exploring vast custom dimensions, or fighting intricate boss encounters across roguelike dungeons, this modpack provides a balanced, cohesive environment for both solo adventurers and dedicated multiplayer servers.

---

## Key Features

* **Classic & Extended Tech Systems:**
  * Complete digital logistics and auto-crafting via *Applied Energistics 2 (Extended Life)*.
  * Modular multi-conduits and compact automation using *Ender IO*.
  * Classic power generation, quarrying, and processing with *IndustrialCraft 2*, *BuildCraft*, and *Extra Utilities 2*.

* **Deep Magic & Arcane Arts:**
  * Constellation alignment and starlight craft through *Astral Sorcery*.
  * Vis manipulation, alchemy, and research with *Thaumcraft 6*.
  * Mana-based natural tech via *Botania*.
  * Eldritch rituals and dark dimensions with *AbyssalCraft* and *Witchery Resurrected*.

* **Dimension & World Exploration:**
  * Celestial exploration with *The Aether*, *The Twilight Forest*, and *Galacticraft*.
  * Complete biome and terrain overhauls in the Nether (*Better Nether*, *NetherEx*) and the End (*BetterEnd Forge*).
  * Backported aquatic ocean updates (*Oceanic Expanse*) and 1.16+ Nether features.

* **Combat, Bosses & Mobs:**
  * Animated custom boss encounters (*Mowzie's Mobs*, *Ice and Fire: Dragons*, *Fish's Undead Rising*).
  * Affix-based elite mob scaling (*Champions*) and classic wildlife (*Mo' Creatures*, *Mystical World*).
  * Expanded combat arsenal (*Spartan Weaponry*, *Spartan Shields*, *Parry mechanics*) paired with *Tinkers' Construct*.

* **Modern Quality of Life & Backports:**
  * 1.13+ swimming and crawling physics via *Aqua Acrobatics*.
  * Modern inventory management (*Inventory HUD+*, *Storage Drawers*, *Improved Backpacks*).
  * Integrated claim management (*FTB Utilities*) integrated directly onto *Xaero's World Map & Minimap*.

* **Engine & Performance Engineering:**
  * Multi-threaded terrain noise generation via *NoiseThreader*.
  * Asynchronous entity and particle culling (*Entity Culling*, *Particle Culling*).
  * Advanced mixin architecture driven by *FermiumBooter* and *LolASM*.

---

## Modpack Composition

The modpack consists of **138 total loaded mods**, carefully partitioned to ensure zero recipe conflicts and optimized memory allocation:

| Category | Count | Primary Focus |
| :--- | :---: | :--- |
| **Content Mods** | **76** | Tech, Magic, Dimensions, Mobs, Structures, Gear & Farming |
| **User Interface & Client** | **25** | JEI, HUD Overlays, Minimaps, Tooltips & Custom Menus |
| **Performance & Optimization** | **15** | Memory Fixes, Culling, Multi-threading & Profiling |
| **Utilities & Audio-Visuals** | **13** | Spatial Audio, Weather FX, Land Claiming & Server Utilities |
| **Core Libraries & Engine** | **22** | Mixin Loaders, APIs, and Base Frameworks |

---

## Installation & Requirements

### System Requirements
* **Java Version:** Java 8 (JDK / JRE 8u311 or higher recommended, 64-bit mandatory).
* **Allocated RAM:**
  * **Client Minimum:** 5 GB RAM
  * **Client Recommended:** 6 GB - 8 GB RAM
  * **Server Minimum:** 4 GB RAM (for 1 - 4 players)

### Client Installation
1. Install **Minecraft Forge** for version **1.12.2** (Recommended Build `14.23.5.2860` or higher).
2. Download and extract the **Rener's Golden: Classic** release archive.
3. Copy the contents of the `mods` folder into your local `.minecraft/mods` directory.
4. Ensure your launcher JVM arguments allocate at least 6 GB of RAM (`-Xmx6G -Xms4G`).
5. Launch the game and enjoy.

---

## Configuration & Performance Tips

* **JVM Arguments:**
  For optimal garbage collection on Java 8, use the following flags:
  ```text
  -Xms4G -Xmx6G -XX:+UseG1GC -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
  ```
* **Graphics Settings:**
  * Set **Graphics** to `Fancy` or `Fast` based on your GPU capability.
  * Enable **Entity Culling** in the config if encountering performance dips in high-density mob areas.
  * Adjust **Dynamic View Distance** settings to stabilize TPS on dedicated servers.

---

## Modlist & Documentation

For a full, itemized breakdown of every mod included in this pack, refer to the documentation files in this repository:

* Full English Modlist: [`modlist.md`](modlist.md)
* Lista de Mods en Español: [`modlist_es.md`](modlist_es.md)

---

## License & Credits

* All credit goes to the respective authors and maintainers of the individual mods contained within this pack.
* Curated and maintained by **Abiel Rene Rugama Mejia (Rener)**.
