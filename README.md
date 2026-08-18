<img width="1024" height="217" alt="title_classic" src="https://github.com/user-attachments/assets/813f7b65-2cc9-4dd7-9f8a-00bb5371e217" />

**Rener's Golden: Classic** is a meticulously engineered 1.12.2 Minecraft modpack designed to bridge the golden era of classic modded gameplay with modern performance standards, fluid quality-of-life features, and deep progression systems.

Built on an optimized Forge 1.12.2 backbone using modern mixin loaders, multi-threaded world noise generation, and asynchronous rendering pipelines, **Rener's Golden: Classic** delivers an expansive survival experience without compromising client or server stability.

---

## 📌 Release Status & Details
* **Status:** Release Phase[cite: 7]
* **Target Game Version:** Minecraft 1.12.2[cite: 7]
* **Forge Version:** `14.23.5.2859`+[cite: 7]
* **Total Loaded Mods:** 175 Mods[cite: 7]

---

## Table of Contents
1. [Overview](#overview)
2. [Key Features](#key-features)
3. [Modpack Composition](#modpack-composition)
4. [Installation & Requirements](#installation--requirements)
5. [Configuration & Performance Tips](#configuration--performance-tips)
6. [Modlist & Documentation](#modlist--documentation)
7. [License & Credits](#license--credits)

---

## Overview

Minecraft version 1.12.2 remains one of the most celebrated eras for technical automation, magical mastery, and sandbox depth. **Rener's Golden: Classic** honors this heritage by assembling legendary core mods alongside modernized engine backports and visual enhancements.

Whether you are automating multi-block industrial reactors, mastering starlight and eldritch sorcery, exploring vast custom dimensions, or fighting intricate boss encounters across roguelike dungeons, this modpack provides a balanced, cohesive environment for both solo adventurers and dedicated multiplayer servers.

---

## Key Features

* **Classic & Extended Tech Systems:**
  * Complete digital logistics and auto-crafting via *Applied Energistics 2 (Extended Life)*[cite: 7].
  * Modular multi-conduits and compact automation using *Ender IO*[cite: 7].
  * Classic power generation, quarrying, and processing with *IndustrialCraft 2*, *BuildCraft*, and *Extra Utilities 2*[cite: 7].
  * Security systems and protected logistics with *SecurityCraft*[cite: 7].

* **Deep Magic & Arcane Arts:**
  * Constellation alignment and starlight craft through *Astral Sorcery*[cite: 7].
  * Vis manipulation, alchemy, and research with *Thaumcraft 6*[cite: 7].
  * Mana-based natural tech via *Botania* and its expansion *Alfheim*[cite: 7].
  * Eldritch rituals, covens, and dark dimensions with *AbyssalCraft* and *Witchery: Resurrected*[cite: 7].

* **Dimension & World Exploration:**
  * Celestial and realm exploration with *The Aether*, *The Twilight Forest*, *Blue Skies*, and *Galacticraft*[cite: 7].
  * Complete biome and terrain overhauls in the Nether (*Better Nether*, *NetherEx*, *Unseen's Nether Backport*) and the End (*BetterEnd Forge*)[cite: 7].
  * Backported aquatic ocean updates (*Oceanic Expanse*) and challenging roguelike structures (*Roguelike Dungeons - Fnar Edition*, *Wesley's Roguelike Dungeons*, *Doomlike Dungeons*)[cite: 7].

* **Combat, Bosses & Creatures:**
  * Animated custom boss encounters (*Mowzie's Mobs*, *Ice and Fire: Dragons*, *Fish's Undead Rising*, *Beast Slayer*, *Wyrms of Nyrus*)[cite: 7].
  * Affix-based elite mob scaling (*Champions*) and classic wildlife (*Mo' Creatures*, *Mystical World*, *Primitive Mobs*, *Rats*)[cite: 7].
  * Expanded combat arsenal (*Spartan Weaponry*, *Spartan Shields*, *Parry mechanics*, *Weapon Master*) paired with *Tinkers' Construct*[cite: 7].

* **Farming, Food & Building Overhauls:**
  * Full culinary systems featuring *Farmer's Delight Legacy*, *Nether's Delight Legacy*, *End's Delight Legacy*, and *Twilight Delight Legacy*[cite: 7].
  * Aquaculture expansion, custom sandwiches with *Culinary Construct*, and automated forestry via *TreeChop*[cite: 7].
  * Comprehensive architectural blocks from *Macaw's Bridges/Doors/Fences/Windows* and *Ne-Carpenters-Blocks*[cite: 7].

* **Modern Quality of Life & Backports:**
  * 1.13+ swimming and crawling physics via *Aqua Acrobatics*[cite: 7].
  * Modern inventory management (*Inventory HUD+*, *Storage Drawers*, *Improved Backpacks*, *Lootr*, *Item Scroller*)[cite: 7].
  * Integrated claim management (*FTB Utilities*) integrated directly onto *Xaero's World Map & Minimap*[cite: 7].

* **Engine & Performance Engineering:**
  * Multi-threaded terrain noise generation via *NoiseThreader*[cite: 7].
  * Asynchronous entity and particle culling (*Entity Culling*, *Particle Culling*, *RenderLib*)[cite: 7].
  * Advanced mixin architecture and memory protection driven by *FermiumBooter*, *LoliASM*, *RamGuard*, and *VintageFix*[cite: 7].

---

## Modpack Composition

The modpack consists of **175 total loaded mods**, carefully partitioned to ensure zero recipe conflicts and optimized memory allocation[cite: 7]:

| Category | Count | Primary Focus |
| :--- | :---: | :--- |
| **Content & Mechanics** | **78** | Tech, Magic, Dimensions, Dungeons, Mobs, Combat & Farming[cite: 7] |
| **Quality of Life & Visuals** | **34** | UI Overlays, HUDs, Minimaps, Sound Physics & Particle FX[cite: 7] |
| **Core Libraries & APIs** | **41** | Mixin Loaders, Compatibility Frameworks & Base Libraries[cite: 7] |
| **Performance & Optimization** | **22** | Multi-threading, Culling, Memory Fixes, TPS Stabilization[cite: 7] |
| **Total** | **175** | **Fully integrated release build**[cite: 7] |

---

## Installation & Requirements

### System Requirements
* **Java Version:** Java 8 (JDK / JRE 8u311 or higher recommended, 64-bit mandatory).
* **Allocated RAM:**
  * **Client Minimum:** 5 GB RAM
  * **Client Recommended:** 6 GB - 8 GB RAM
  * **Server Minimum:** 4 GB - 6 GB RAM (for 1 - 6 players)

### Client Installation
1. Install **Minecraft Forge** for version **1.12.2** (Recommended Build `14.23.5.2859` or `14.23.5.2860`)[cite: 7].
2. Download and extract the **Rener's Golden: Classic** release archive.
3. Copy the contents of the `mods`, `config`, and `resources` folders into your local `.minecraft/` directory.
4. Ensure your launcher JVM arguments allocate at least 6 GB of RAM (`-Xmx6G -Xms4G`).
5. Launch the game and enjoy.

---

## Configuration & Performance Tips

* **JVM Arguments:**
  For optimal garbage collection on Java 8 with large mod collections, use the following flags:
  ```text
  -Xms4G -Xmx6G -XX:+UseG1GC -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
  ```
* **Graphics Settings:**
  * Set **Graphics** to `Fancy` or `Fast` based on your GPU capability.
  * Enable **Entity Culling** and **Particle Culling** in their respective configs to maximize FPS in dense bases or mob farms[cite: 7].
  * Tune **Dynamic View Distance** settings to stabilize TPS during heavy world exploration on dedicated servers[cite: 7].

---

## Modlist & Documentation

For a full, itemized breakdown of every mod included in this pack, refer to the documentation files in this repository:

* Full English Modlist: [`modlist.md`](modlist.md)
* Lista de Mods en Español: [`modlist_es.md`](modlist_es.md)

---

## License & Credits

* All credit goes to the respective authors and maintainers of the individual mods contained within this pack.
* Curated and maintained by **Rener**.
