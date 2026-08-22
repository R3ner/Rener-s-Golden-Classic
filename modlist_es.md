<a name="top"></a>

# Rener's Golden: Classic — Lista de mods

> **Estado:** Release Phase  
> **Versión de Minecraft:** 1.12.2  
> **Archivos JAR totales:** 237

Este documento contiene la lista completa de mods de **Rener's Golden: Classic**. Está organizada por función en lugar de orden alfabético, para que sea más fácil entender qué aporta cada mod al pack.

## Resumen

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

## Contenido

- [Core, Libraries & APIs](#core-libraries-apis)
- [Performance & Optimization](#performance-optimization)
- [World Generation & Dimensions](#world-generation-dimensions)
- [Magic, Technology & Mechanics](#magic-technology-mechanics)
- [Mobs, Bosses & Creatures](#mobs-bosses-creatures)
- [Combat, Equipment & Curios](#combat-equipment-curios)
- [Building, Farming & Food](#building-farming-food)
- [UI, Quality of Life (QoL) & Visuals](#ui-quality-of-life-qol-visuals)

## Notas

- Los nombres de los archivos JAR se mantienen exactamente como aparecen en el modpack.
- Algunas entradas son bibliotecas o frameworks de compatibilidad y no mods visibles para el jugador.
- Las descripciones son resúmenes funcionales y la versión indicada corresponde a la utilizada actualmente por el pack.

---

## 1. Core, Bibliotecas y APIs

*Frameworks, APIs y bibliotecas de dependencias necesarias para el resto del pack.*

- **FermiumBooter** — `FermiumBooter-1.5.0.jar`  
  Utilidad de arranque y compatibilidad utilizada por varios mods de optimización y de núcleo.
- **!CrashAssistant** — `!CrashAssistant-forge-1.12.2-1.11.12.jar`  
  Mejora la gestión de errores y los diagnósticos para que los informes de fallos de los modpacks sean más fáciles de interpretar.
- **!mixinbooter** — `!mixinbooter-11.14.jar`  
  Capa de arranque y compatibilidad de Mixin necesaria para mods que inyectan código en Minecraft.
- **!Red-Core-MC** — `!Red-Core-MC-1.8-1.12-0.7.1.jar`  
  Biblioteca de núcleo que proporciona funciones compartidas a los mods que dependen de Red Core.
- **_MixinBootstrap** — `_MixinBootstrap-1.1.0.jar`  
  Capa de arranque de Mixin cargada tempranamente y utilizada por los mods dependientes.
- **_supermartijn642corelib** — `_supermartijn642corelib-1.1.24a-forge-mc1.12.jar`  
  Biblioteca de utilidades compartida por los mods de SuperMartijn642 y sus integraciones.
- **___MixinCompat___** — `[___MixinCompat-1.1-1.12.2___].jar`  
  Puente de compatibilidad de Mixin que ayuda a que distintos mods basados en Mixin funcionen juntos.
- **Atlas-Lib** — `Atlas-Lib-1.12.2-1.1.11.jar`  
  Biblioteca compartida necesaria para mods del mismo desarrollador.
- **AutoRegLib** — `AutoRegLib-1.3-32.jar`  
  Biblioteca de registro y utilidades utilizada por Quark y otros mods.
- **CarbonConfig** — `CarbonConfig-1.12.2-2.0.2.1.jar`  
  Framework de configuración utilizado por los mods que exponen ajustes mediante CarbonConfig.
- **Chameleon** — `Chameleon-1.12-4.1.3.jar`  
  Biblioteca compartida de renderizado y color de bloques utilizada por los mods dependientes.
- **CodeChickenLib** — `CodeChickenLib-1.12.2-3.2.3.358-universal.jar`  
  Biblioteca de núcleo que proporciona APIs de renderizado, red, inventario y utilidades para los mods basados en CodeChicken.
- **Collective** — `collective-1.12.2-3.0.jar`  
  Biblioteca de código compartida por diversos mods ligeros de utilidades y jugabilidad.
- **CommonCapabilities** — `CommonCapabilities-1.12.2-2.4.8.jar`  
  Biblioteca de API de capacidades para exponer y compartir datos moddeados comunes.
- **CoroUtil** — `coroutil-1.12.1-1.2.37.jar`  
  Biblioteca compartida utilizada por los mods de Corosus y sus sistemas de entidades y mundo.
- **CreativeCore** — `CreativeCore_v1.10.71_mc1.12.2.jar`  
  Framework de núcleo y biblioteca de utilidades utilizada por los mods de CreativeMD.
- **CTM** — `CTM-MC1.12.2-1.0.2.31.jar`  
  Framework de texturas conectadas para crear conexiones avanzadas entre bloques y texturas.
- **Cucumber Library** — `Cucumber-1.12.2-1.1.3.jar`  
  Biblioteca compartida utilizada por Mystical Agriculture y mods relacionados.
- **CyclopsCore** — `CyclopsCore-1.12.2-1.6.7.jar`  
  Biblioteca de código compartida por los mods de Cyclops.
- **EnderCore** — `EnderCore-1.12.2-0.5.78.jar`  
  Dependencia principal de Ender IO y otros componentes de la familia Ender.
- **Forgelin** — `Forgelin-1.8.4.jar`  
  Biblioteca de soporte para Kotlin necesaria para varios mods de Forge 1.12.2.
- **FTBLib** — `FTBLib-5.4.7.2.jar`  
  Biblioteca principal para FTB Utilities y sus integraciones relacionadas.
- **FTB Utilities: Xaero Compat** — `ftbuxaerocompat-1.1.1.jar`  
  Capa de compatibilidad que conecta las funciones de FTB Utilities con los mods de mapas de Xaero.
- **GottschCore** — `GottschCore-mc1.12.2-f14.23.5.2859-v1.15.1.jar`  
  Biblioteca compartida utilizada por los mods de estructuras y mazmorras de Gottsch.
- **iChunUtil** — `iChunUtil-1.12.2-7.2.2.jar`  
  Biblioteca de utilidades principal utilizada por los mods de iChun.
- **IronCore** — `IronCore1.12.2-V1.2.jar`  
  Biblioteca de núcleo compartida por mods del mismo ecosistema.
- **Konkrete** — `konkrete_forge_1.6.1_MC_1.12-1.12.2.jar`  
  Framework de utilidades compartido por los mods que dependen de Konkrete.
- **LibraryEx** — `LibraryEx-1.12.2-1.2.2.jar`  
  Biblioteca común que proporciona APIs compartidas para los mods dependientes.
- **LLibrary** — `llibrary-1.7.20-1.12.2.jar`  
  Framework de animación, IA y utilidades utilizado por varios mods avanzados de entidades y contenido.
- **Mantle** — `Mantle-1.12-1.3.3.55.jar`  
  Biblioteca principal para Tinkers' Construct y mods relacionados.
- **MysticalLib** — `mysticallib-1.12.2-1.13.0.jar`  
  Biblioteca compartida para mods del ecosistema Mystical.
- **Nether-API** — `Nether-API-v1.4.5-mc1.12.2.jar`  
  Capa de API para mods que añaden o modifican contenido del Nether.
- **OreLib** — `OreLib-1.12.2-3.6.0.1.jar`  
  Biblioteca compartida utilizada por mods de tecnología, minerales y utilidades.
- **Patchouli** — `Patchouli-1.0-23.6.jar`  
  Framework de documentación y libros-guía dentro del juego utilizado por muchos mods de contenido.
- **Placebo** — `Placebo-1.12.2-1.6.1.jar`  
  Biblioteca de utilidades compartida necesaria para varios mods populares de Forge.
- **PTRLib** — `PTRLib-1.0.5.jar`  
  Biblioteca compartida utilizada por mods que dependen de las funciones de PTRLib.
- **RenderLib** — `RenderLib-1.12.2-1.4.5.jar`  
  Biblioteca de utilidades de renderizado para mods dependientes.
- **SuperMartijn642's Config Lib** — `supermartijn642configlib-1.1.8-forge-mc1.12.jar`  
  Biblioteca de configuración para los mods de SuperMartijn642.
- **SynLib** — `synlib-4.0.jar`  
  Biblioteca compartida utilizada por mods del mismo ecosistema.
- **XaeroLib** — `xaerolib-forge-1.12.2-1.7.1.jar`  
  Biblioteca principal compartida por el minimapa, el mapa mundial de Xaero y sus integraciones.

[↑ Volver arriba](#top)

---

## 2. Rendimiento y Optimización

*Optimizaciones de cliente y servidor centradas en FPS, memoria, estabilidad de ticks y generación del mundo.*

- **AI Improvements** — `AIImprovements-1.12-0.0.1b3.jar`  
  Optimiza el procesamiento de la IA de las entidades para reducir carga innecesaria de CPU.
- **AttributeFix** — `AttributeFix-Forge-1.12.2-1.0.12.jar`  
  Aumenta los límites restrictivos de atributos de Minecraft para que los mods puedan utilizar valores mayores.
- **Chunk-Pregenerator** — `Chunk-Pregenerator-1.12.2-4.4.9.2.jar`  
  Pre-genera chunks del mundo para reducir picos de generación durante la exploración y el lag del servidor.
- **Clumps** — `Clumps-3.1.2.jar`  
  Agrupa orbes de experiencia cercanos en acumulaciones mayores, reduciendo la cantidad de entidades.
- **Dynamic View Distance** — `dynviewdist-1.12-1.3.jar`  
  Ajusta dinámicamente la distancia de visión para equilibrar visibilidad y rendimiento del servidor.
- **Entity Culling** — `entityculling-1.12.2-1.6.3.jar`  
  Evita renderizar entidades completamente ocultas para la cámara.
- **ExperienceBugFix** — `ExperienceBugFix-1.12.2-1.0.0.0.jar`  
  Corrige problemas relacionados con la experiencia presentes en el juego base 1.12.2.
- **Farsight** — `farsight-1.6.jar`  
  Permite al cliente conservar información de terreno lejano más allá de la distancia de visión normal del servidor.
- **FastFurnace** — `FastFurnace-1.12.2-1.3.1.jar`  
  Optimiza las actualizaciones de los hornos y las comprobaciones de recetas.
- **FastLeafDecay** — `FastLeafDecay-v14.jar`  
  Acelera la desaparición de las hojas después de talar árboles.
- **Get It Together Drops** — `getittogetherdrops-1.12.2-v1.0.2.jar`  
  Agrupa objetos recogibles cercanos para reducir el desorden y la carga de entidades.
- **GPUTape** — `GPUTape-1.12.2-1.0.4.jar`  
  Mejora el comportamiento del renderizado y la gestión a nivel de GPU para un mejor rendimiento del cliente.
- **LoliASM** — `loliasm-5.33.jar`  
  Framework de rendimiento de bajo nivel centrado en optimizar los componentes internos de Minecraft.
- **NetherPortalFix** — `NetherPortalFix_1.12.1-5.3.17.jar`  
  Mantiene coherentes los destinos de los portales del Nether y reduce desvíos no deseados.
- **NoiseThreader** — `NoiseThreader-1.1.3.jar`  
  Mueve fuera del hilo principal parte del cálculo de ruido de generación del mundo cuando es posible.
- **Nothirium** — `Nothirium-1.12.2-0.4.9-beta.jar`  
  Backend de renderizado de alto rendimiento orientado a mejorar los FPS y el renderizado de chunks.
- **Particle Culling** — `particleculling-1.12.2-v1.4.3.jar`  
  Evita renderizar partículas que no son visibles para el jugador.
- **RamGuard** — `RamGuard-1.12.2-1.0.0.jar`  
  Añade protecciones y avisos relacionados con la RAM para instancias moddeadas de Minecraft.
- **RoughlyEnoughIDs** — `RoughlyEnoughIDs-2.3.1.jar`  
  Amplía el limitado espacio de IDs numéricos de Minecraft para admitir modpacks grandes.
- **Spark** — `spark-forge1122.jar`  
  Profiler de rendimiento para diagnosticar problemas de CPU, memoria, ticks y rendimiento del servidor.
- **STG (SwingThroughGrass)** — `stg-1.12.2-1.2.3.jar`  
  Permite que los ataques cuerpo a cuerpo atraviesen hierba y vegetación similar sin golpearla.
- **VintageFix** — `vintagefix-0.7.0.jar`  
  Suite de optimización de rendimiento y memoria a gran escala para el cliente de Minecraft 1.12.2.

[↑ Volver arriba](#top)

---

## 3. Generación del Mundo y Dimensiones

*Nuevas dimensiones, biomas, estructuras, características del terreno y contenido centrado en la exploración.*

- **AbyssalCraft** — `AbyssalCraft-1.12.2-1.11.3.jar`  
  Añade dimensiones, biomas, estructuras, criaturas, progresión y contenido de temática oscura y sobrenatural.
- **Alfheim (Botania Expansion)** — `Alfheim-1.6.jar`  
  Añade contenido inspirado en Alfheim que amplía la progresión y el endgame de Botania.
- **Basic Nether Ores** — `BasicNetherOres-1.12.2-1.0.5.0.jar`  
  Añade al Nether minerales adicionales de estilo similar a los del Overworld.
- **BetterEnd (Unofficial Port)** — `BetterEndForge-Unofficial-GBPort-1.12.2-1.3.9.jar`  
  Port no oficial para 1.12.2 que amplía los biomas y el contenido ambiental del End.
- **BetterNether** — `betternether-0.1.8.6.jar`  
  Reestructura el Nether con nuevos biomas, plantas, características del terreno y recursos.
- **Better Strongholds** — `BetterStronghold -0.1.jar`  
  Mejora las fortalezas de vanilla con más variedad y diseños centrados en la exploración.
- **Blue Skies** — `blue_skies-1.12.2-v1.1.3.jar`  
  Añade dos grandes dimensiones con nuevos biomas, estructuras, criaturas, jefes y progresión.
- **Doomlike Dungeons** — `dldungeonsjbg-1.14.17-MC1.12.2.jar`  
  Genera mazmorras densas y con múltiples salas inspiradas en los dungeon crawlers clásicos.
- **Lost Aether Content** — `lost-aether-content-1.12.2-1.0.2.jar`  
  Añade contenido adicional para el ecosistema de The Aether.
- **NetherEx** — `NetherEx-1.12.2-2.2.5.jar`  
  Amplía y transforma el terreno, biomas, estructuras y recursos del Nether.
- **Novam Terram** — `NovamTerram-7.3.6.3.jar`  
  Añade una amplia variedad de funciones de generación del mundo, terreno, biomas y contenido de exploración.
- **Oceanic Expanse** — `OceanicExpanse-1.2.2.jar`  
  Amplía la exploración oceánica con nuevo terreno acuático y contenido.
- **Rex's Additional Structures** — `Rex's-AdditionalStructures-1.12.x(v.2.5.0).jar`  
  Añade estructuras adicionales para descubrir por el Overworld.
- **Roguelike Dungeons - Fnar Edition** — `RoguelikeDungeonsFnarEdition-1.12.2-2.4.6.jar`  
  Genera grandes complejos de mazmorras estilo roguelike llenos de salas y botín.
- **The Aether** — `aether-1.12.2-v1.5.4.1.jar`  
  Añade la dimensión Aether, con islas flotantes, criaturas únicas, mazmorras y progresión.
- **The Twilight Forest** — `twilightforest-1.12.2-3.11.1021-universal.jar`  
  Añade una gran dimensión de aventura centrada en jefes, mazmorras, exploración y biomas únicos.
- **Unseen's Nether Backport** — `unseens-nether-backport-0.7.jar`  
  Trae de vuelta determinadas funciones y mecánicas del Nether de versiones más nuevas de Minecraft.
- **Wesley's Roguelike Dungeons** — `Wesley's Roguelike Dungeons V0.8.1.jar`  
  Añade otro conjunto de estructuras de mazmorras roguelike generadas proceduralmente para explorar.

[↑ Volver arriba](#top)

---

## 4. Magia, Tecnología y Mecánicas

*Grandes sistemas de progresión que cubren tecnología, automatización, magia, almacenamiento y mecánicas personalizadas.*

- **Applied Energistics 2: Extended Life** — `ae2-uel-v0.56.6.jar`  
  Fork Extended Life de Applied Energistics 2 que aporta almacenamiento digital avanzado, automatización y procesamiento de objetos.
- **Astral Sorcery** — `astralsorcery-1.12.2-1.10.27.jar`  
  Sistema de magia basado en la luz estelar, con rituales, constelaciones, exploración y poderosas habilidades celestiales.
- **Botania** — `Botania r1.10-364.4.jar`  
  Mod de magia con enfoque tecnológico basado en el maná natural, flores, automatización y dispositivos mágicos.
- **BuildCraft** — `buildcraft-all-8.0.0.jar`  
  Clásico mod tecnológico con tuberías, motores, energía, canteras y gestión automatizada de recursos.
- **CraftTweaker2** — `CraftTweaker2-1.12-4.1.20.715.jar`  
  Permite a los creadores del modpack programar y personalizar recetas, botín y otras mecánicas del juego.
- **Ender IO** — `EnderIO-1.12.2-5.3.72.jar`  
  Suite tecnológica con conductos, máquinas, generación de energía, automatización y procesamiento compacto.
- **Ender Storage** — `EnderStorage-1.12.2-2.4.6.137-universal.jar`  
  Añade contenedores de almacenamiento y mochilas enlazados mediante Ender y diferenciados por colores.
- **Energy Converters** — `energyconverters_1.12.2-1.3.7.30.jar`  
  Convierte entre distintos sistemas de energía moddeados para mejorar la compatibilidad entre mods.
- **Extra Utilities 2** — `extrautils2-1.12-1.9.9.jar`  
  Añade una amplia variedad de bloques de utilidad, máquinas, generadores, herramientas de transporte y funciones de jugabilidad.
- **Galacticraft** — `Galacticraft-1.12.2-4.0.7.jar`  
  Añade viajes espaciales, planetas, cohetes, sistemas de oxígeno y supervivencia en el espacio.
- **IndustrialCraft 2** — `industrialcraft-2-2.8.170-ex112.jar`  
  Clásico mod de tecnología industrial con generadores, máquinas, redes eléctricas y procesamiento de recursos.
- **OpenBlocks Reopened** — `OpenBlocksReopened-1.12.2-1.8.3.1.jar`  
  Continuación reabierta del contenido de utilidades y automatización al estilo de OpenBlocks.
- **Quark** — `Quark-r1.6-179.jar`  
  Gran colección de mejoras de construcción, utilidades, mundo y calidad de vida que mantienen el estilo vanilla.
- **SecurityCraft** — `[1.12.2] SecurityCraft v1.10.1.jar`  
  Añade sistemas de seguridad como cámaras, bloques reforzados, alarmas y herramientas de control de acceso.
- **Storage Drawers** — `StorageDrawers-1.12.2-5.5.3.jar`  
  Sistema de almacenamiento compacto basado en cajones de gran capacidad y almacenamiento visual de objetos.
- **Thaumcraft 6** — `Thaumcraft-1.12.2-6.1.BETA26.jar`  
  Sistema de progresión mágica profundo basado en investigación, essentia, alquimia, varitas, exploración y conocimientos sobrenaturales.
- **Tinkers' Construct** — `TConstruct-1.12.2-2.13.0.183.jar`  
  Sistema modular de creación de herramientas y armas con materiales, piezas y modificadores personalizables.
- **Tinkers' Tool Leveling** — `TinkerToolLeveling-1.12.2-1.1.0.jar`  
  Añade niveles basados en experiencia y modificadores adicionales para las herramientas de Tinkers' Construct.
- **Witchery** — `witchery-1.7.10-0.24.1.jar`  
  Sistema de magia de fantasía oscura con rituales, pociones, maldiciones, transformaciones y mecánicas sobrenaturales.
- **Witchery Companion** — `witcherycompanion-0.36.2-beta.jar`  
  Añade contenido de apoyo e integración adicional para Witchery.
- **Witchery: Resurrected** — `WitcheryResurrected-1.12.2-0.5.2.4-forge-all.jar`  
  Continuación comunitaria de Witchery con contenido sobrenatural restaurado y ampliado.

[↑ Volver arriba](#top)

---

## 5. Mobs, Jefes y Criaturas

*Nuevas criaturas, variantes de enemigos, compañeros, jefes y fauna.*

- **Beast Slayer** — `beastslayer-not.2.0.03.release.jar`  
  Añade criaturas hostiles y encuentros centrados en el combate para hacer la exploración más peligrosa.
- **Champions** — `champions-1.12.2-1.0.11.10.jar`  
  Convierte ciertos mobs en élites con afijos, estadísticas mejoradas y habilidades especiales.
- **ChocoCraft Plus** — `ChocoCraftPlus-1.12.2-4.5.10.jar`  
  Añade chocobos que pueden encontrarse, domesticarse, criarse y utilizarse como monturas.
- **Doggy Talents** — `DoggyTalents-1.12.2-1.15.1.6.jar`  
  Convierte a los lobos en compañeros entrenables con numerosos talentos configurables y funciones útiles.
- **Dragon Mounts 2** — `DragonMounts2-1.12.2-2.1.2.jar`  
  Añade dragones que pueden criarse y montarse, con varias variantes elementales.
- **Eyes in the Darkness** — `EyesInTheDarkness-0.1.0.jar`  
  Introduce una misteriosa criatura hostil que acecha en zonas oscuras.
- **Fish's Undead Rising** — `Fish's Undead Rising-1.6.2.jar`  
  Añade nuevos enemigos no muertos y encuentros de combate.
- **Fossils and Archaeology Revival** — `fossilsarcheology-8.0.6.jar`  
  Añade fósiles, arqueología, criaturas prehistóricas, reliquias y mecánicas de restauración.
- **Frozen Fiend** — `Frozen-Fiend-1.5.3.jar`  
  Añade una criatura hostil de temática helada y encuentros relacionados.
- **Ice and Fire: Dragons** — `iceandfire-1.9.1-1.12.2.jar`  
  Añade dragones y otras criaturas míticas, estructuras, objetos y encuentros similares a jefes.
- **Illagers+** — `IllagersPlus-1.12.2-1.1.3.jar`  
  Añade nuevas variantes de illagers, equipamiento y encuentros para ampliar el contenido de invasores hostiles.
- **Magma Monsters** — `MagmaMonsters-0.3.0.jar`  
  Introduce mobs hostiles de temática magmática y contenido de combate relacionado.
- **Mo' Creatures** — `mocreatures-12.5.1.jar`  
  Añade una gran variedad de animales y monstruos pasivos, neutrales y hostiles.
- **Mowzie's Mobs** — `mowziesmobs-1.5.8.jar`  
  Añade mobs personalizados de gran calidad con IA, animaciones y mecánicas de combate desafiantes.
- **MultiMob** — `multimob-1.0.5.jar`  
  Proporciona mobs adicionales y contenido de jugabilidad relacionado con criaturas.
- **Mystical World** — `mysticalworld-1.12.2-1.11.0.jar`  
  Añade animales, monstruos, bloques y recursos adicionales manteniendo un estilo cercano a vanilla.
- **Primitive Mobs** — `primitivemobs-1.2.3a.jar`  
  Amplía el conjunto de mobs hostiles y pasivos con nuevas criaturas y mecánicas de utilidad.
- **Rats** — `rats-3.2.14-1.12.2.jar`  
  Añade ratas, domesticación, cría, automatización y un amplio conjunto de mecánicas y objetos relacionados con ellas.
- **Simply Cats** — `simplycats-1.12.2-0.2.2.jar`  
  Añade gatos domesticables, nuevas variantes felinas e interacciones adicionales.
- **Spiders 2.0** — `spiders-2.0-1.12.2-1.0.3.jar`  
  Mejora las arañas con nuevos comportamientos de movimiento y variantes adicionales.
- **Straw Golem Reborn** — `strawgolem-1.4.2.ED.jar`  
  Añade pequeños gólems de paja que ayudan con tareas agrícolas sencillas.
- **Wither Skeleton Tweaks** — `WitherSkeletonTweaks-1.12.2-2.6.3.jar`  
  Amplía y ajusta el comportamiento de los wither skeletons y sus mecánicas de combate relacionadas.

[↑ Volver arriba](#top)

---

## 6. Combate, Equipamiento y Accesorios

*Armas, escudos, accesorios, equipamiento de movilidad y mecánicas centradas en el combate.*

- **Armored Arms** — `ArmoredArms-v1.5.3-1.12.2-release.jar`  
  Añade mecánicas adicionales de brazos y armas centradas en el combate.
- **Artifacts** — `artifacts-1.12.2-1.2.4.jar`  
  Añade botín raro de exploración con artefactos equipables y bonificaciones únicas.
- **Baubles** — `Baubles-1.12-1.5.2.jar`  
  Añade un sistema de ranuras de accesorios para amuletos, abalorios y equipamiento.
- **Bountiful Baubles** — `Bountiful Baubles-1.12.2-0.1.8.jar`  
  Añade más baubles, abalorios y accesorios de utilidad con efectos configurables.
- **Colytra** — `colytra-1.12.2-1.2.0.4.jar`  
  Permite usar el vuelo de las élitras mientras llevas una pieza de armadura de pecho compatible.
- **Cosmetic Armor Reworked** — `CosmeticArmorReworked-1.12.2-v5a.jar`  
  Separa la apariencia cosmética de la armadura de las piezas que proporcionan las estadísticas reales.
- **Crossbows Backport** — `Crossbows-Backport-1.12.2-1.1.1.jar`  
  Añade a 1.12.2 las mecánicas de ballestas y contenido relacionado de versiones posteriores.
- **Easy Anvils** — `easyanvils-1.1.0.jar`  
  Añade mejoras de calidad de vida al uso y configuración del yunque.
- **Easy Elytra Takeoff** — `easyelytratakeoff_1.12.2-2.1.jar`  
  Hace que despegar con una élitra sea más rápido y cómodo.
- **Easy Magic** — `easymagic-1.2.4.jar`  
  Mejora la interacción con la mesa de encantamientos y facilita la preparación de encantamientos.
- **Forgiving Void** — `ForgivingVoid_1.12.2-1.1.0.jar`  
  Evita algunas muertes accidentales al caer al vacío mediante un comportamiento de recuperación configurable.
- **Grappling Hook Mod** — `grappling_hook_mod-1.12.2-v13.jar`  
  Añade ganchos para desplazarse rápidamente y mejorar la movilidad.
- **Hammers** — `hammers-2.1.5-1.12.2-forge.jar`  
  Añade martillos de minería multibloque para despejar grandes áreas de bloques.
- **Improved Backpacks** — `ImprovedBackpacks-1.12.2-1.5.0.0.jar`  
  Proporciona mochilas mejoradas con más almacenamiento y funciones adicionales.
- **Iron Jetpacks** — `IronJetpacks-1.12-2-1.1.0.jar`  
  Añade mochilas propulsoras por niveles alimentadas por sistemas de energía moddeados.
- **Paraglider** — `Paraglider-1.12.2-1.0.1.5.jar`  
  Añade mecánicas de planeo y desplazamiento basadas en resistencia, inspiradas en juegos modernos de aventura.
- **Parry** — `parry-1.0-hotfix.jar`  
  Añade una mecánica de parry basada en el tiempo para hacer el bloqueo más activo y dependiente de la habilidad.
- **Responsive Shields** — `responsiveshields-2.3-mc1.12.x.jar`  
  Mejora la respuesta de los escudos y el comportamiento del bloqueo.
- **Spartan Shields** — `SpartanShields-1.12.2-1.5.5.jar`  
  Añade una selección más amplia de escudos con distintos materiales y estadísticas.
- **Spartan Twilight** — `spartantwilight-1.12.2-1.2.0.jar`  
  Añade contenido de compatibilidad de escudos y armas para la progresión de Twilight Forest.
- **Spartan Weaponry** — `SpartanWeaponry-1.12.2-1.6.1.jar`  
  Amplía el arsenal con lanzas, picas, dagas, espadas largas y mucho más.
- **The Aether Baubles** — `TheAetherBaubles-2.0.1.jar`  
  Integra el contenido de Aether con el sistema de accesorios de Baubles.
- **Weapon Master** — `weaponmaster_ydm-forge-1.12.2-4.2.3.jar`  
  Añade cambio de armas configurable y utilidades de combate para la barra rápida.
- **XP Tome** — `xptome-1.12.2-v2.0.1.jar`  
  Añade un objeto portátil para almacenar y recuperar la experiencia acumulada.

[↑ Volver arriba](#top)

---

## 7. Construcción, Agricultura y Comida

*Utilidades de construcción, almacenamiento, agricultura, cocina, bloques decorativos y sistemas de comida.*

- **Aquaculture** — `Aquaculture-1.12.2-1.6.8.jar`  
  Amplía la pesca con nuevos peces, cañas, botín y contenido acuático.
- **Better Builder's Wands** — `BetterBuildersWands-1.12-0.11.1.245+69d0d70.jar`  
  Proporciona varitas de construcción mejoradas para colocar grandes cantidades de bloques rápidamente.
- **Bountiful** — `Bountiful-2.2.2.jar`  
  Añade recompensas, contratos y tareas con premios orientadas a la exploración y la progresión.
- **Comforts** — `comforts-1.12.2-1.4.1.3.jar`  
  Añade sacos de dormir y hamacas para dormir de forma portátil sin cambiar permanentemente el punto de aparición.
- **Culinary Construct** — `culinaryconstruct-1.3.4.jar`  
  Añade un sistema de recipientes de comida para combinar ingredientes y crear comidas personalizables.
- **Ender Crop** — `endercrop-1.12.2-1.6.0.jar`  
  Añade un cultivo de temática End que produce materiales asociados a esa dimensión.
- **End's Delight Legacy** — `ends-delight-legacy-1.0.3.jar`  
  Añade comida, ingredientes y contenido culinario de temática End.
- **Farmer's Delight Legacy** — `FarmersDelightLegacy-1.1.6.jar`  
  Añade a 1.12.2 un sistema de cocina y comida inspirado en Farmer's Delight.
- **Future MC** — `Future-MC-0.2.21.jar`  
  Añade a 1.12.2 determinadas funciones y objetos de versiones más nuevas de Minecraft.
- **Gnetum** — `gnetum-1.4.3.jar`  
  Añade plantas, recursos y contenido adicional centrado en utilidades.
- **Healing Bed** — `HealingBed 1.12.2 forge.jar`  
  Añade una variante de cama que proporciona efectos de curación mejorados al descansar.
- **Iron Barrels** — `IronBarrels1.12.2-V2.0.jar`  
  Añade barriles de gran capacidad para almacenar objetos de forma compacta.
- **Iron Chests** — `ironchest-1.12.2-7.0.72.847.jar`  
  Añade cofres mejorables con una capacidad de almacenamiento muy superior.
- **Iron Furnaces** — `ironfurnaces-1.3.5.jar`  
  Añade niveles de hornos más rápidos para fundir recursos con mayor eficiencia.
- **KleeSlabs** — `KleeSlabs_1.12.2-5.4.12.jar`  
  Permite colocar y manipular losas con mayor facilidad y seguridad, especialmente al construir.
- **Lootr** — `lootr-1.12.2-0.6.2.jar`  
  Hace que los contenedores de botín sean únicos para cada jugador, reduciendo la competencia por el loot generado en multijugador.
- **Macaw's Bridges** — `mcw-bridges-1.0.6b-mc1.12.2.jar`  
  Añade bloques y variantes de puentes decorativos y funcionales.
- **Macaw's Doors** — `mcw-doors-1.0.3-mc1.12.2.jar`  
  Añade muchos estilos y variantes decorativas de puertas para construcción.
- **Macaw's Fences** — `mcw-fences-1.0.0-mc1.12.2.jar`  
  Añade estilos adicionales de vallas y barandillas para construcciones detalladas.
- **Macaw's Windows** — `mcw-windows-1.0.0-mc1.12.2.jar`  
  Añade ventanas, cristales y marcos decorativos en múltiples estilos.
- **MmmMmmMmmMmm (Target Dummy)** — `MmmMmmMmmMmm-1.12-2.0.7.jar`  
  Añade un muñeco de entrenamiento para probar armas, daño y configuraciones de combate.
- **Ne-Carpenters-Blocks** — `Ne-Carpenters-Blocks-0.1.4-fix.jar`  
  Añade bloques decorativos configurables inspirados en el concepto clásico de Carpenter's Blocks.
- **Nether's Delight Legacy** — `nethers-delight-legacy-1.0.7.jar`  
  Añade ingredientes, alimentos y recetas culinarias de temática Nether.
- **Sulfur & Potassium** — `sulfur-potassium-1.12-1.1.jar`  
  Añade recursos adicionales de azufre y potasio, junto con contenido de crafteo relacionado.
- **Torchmaster** — `torchmaster_1.12.2-1.8.5.0.jar`  
  Añade bloques de iluminación especiales que evitan la aparición de mobs hostiles en zonas seleccionadas.
- **TreeChop** — `TreeChop-1.12.2-0.14.7.jar`  
  Permite talar árboles completos de forma más cómoda manteniendo las reglas de herramientas y durabilidad.
- **Twilight Delight Legacy** — `TwilightDelightLegacy-1.2.0.jar`  
  Añade comida y contenido culinario basado en recursos de Twilight Forest.
- **YARCF** — `YARCF-0.14(1.12.2).jar`  
  Añade contenido adicional de comida y crafteo centrado en recursos.

[↑ Volver arriba](#top)

---

## 8. Interfaz, Calidad de Vida (QoL) y Visuales

*Mejoras de interfaz, información del HUD, mapas, audio, visuales y herramientas de calidad de vida.*

- **3D Skin Layers** — `3dSkinLayers-forge-mc1.12.2-1.2.0.jar`  
  Renderiza en 3D la segunda capa de la skin para dar más detalle al aspecto del jugador.
- **Ambient Environment** — `AmbientEnvironment-1.0.2.jar`  
  Añade pequeños efectos visuales ambientales para que los biomas se sientan más vivos.
- **AmbientSounds** — `AmbientSounds_v3.1.7_mc1.12.2.jar`  
  Reestructura el audio ambiental con paisajes sonoros adaptados al bioma y la ubicación.
- **AppleSkin** — `AppleSkin-mc1.12-1.0.14.jar`  
  Muestra directamente en el HUD información útil sobre comida y saturación.
- **Aqua Acrobatics** — `AquaAcrobatics-1.15.4.jar`  
  Mejora el movimiento bajo el agua, la natación y el desplazamiento acuático.
- **Armor Sound Tweak** — `ArmorSoundTweak-2.1.0.jar`  
  Ajusta y mejora los efectos de sonido relacionados con la armadura.
- **Better Advancements** — `BetterAdvancements-1.12.2-0.1.0.77.jar`  
  Proporciona una interfaz de avances más cómoda y legible.
- **Better Chat** — `betterchat-1.4.jar`  
  Mejora la presentación y legibilidad del chat mediante opciones de personalización adicionales.
- **Better Third Person** — `BetterThirdPerson-Forge-1.12.2-1.9.0.jar`  
  Añade una cámara en tercera persona más flexible, con mejor posicionamiento y control.
- **Biome Info** — `biomeinfo-1.12.2-v1.2.5.jar`  
  Muestra al jugador información relacionada con el bioma actual.
- **Colorful Health Bar** — `colorfulhealthbar-0.0.4a.jar`  
  Añade barras de vida más informativas y personalizables.
- **Controlling** — `Controlling-3.0.12.4.jar`  
  Añade herramientas para buscar y gestionar las teclas asignadas.
- **Corpse** — `corpse-1.12.2-1.0.8.jar`  
  Crea un cadáver persistente al morir un jugador, manteniendo su inventario reunido en un único lugar.
- **Custom Cursor Mod** — `CustomCursorMod-1.2.2.jar`  
  Permite personalizar el cursor del ratón utilizado por la interfaz del juego.
- **Custom Skin Loader** — `CustomSkinLoader_Universal-15.0.1.jar`  
  Proporciona compatibilidad con la carga de skins alternativas o personalizadas en versiones antiguas de Minecraft.
- **Deeper Depths** — `Deeper-Depths-1.12.2-1.1.1a.jar`  
  Amplía la exploración subterránea con terrenos más profundos y nuevo contenido bajo tierra.
- **Default Options** — `DefaultOptions_1.12.2-9.2.8.jar`  
  Permite a los autores del modpack incluir ajustes de cliente predeterminados junto al pack.
- **Durability Tooltip** — `durabilitytooltip-1.1.6-forge-mc1.12.jar`  
  Muestra directamente la durabilidad de los objetos en sus tooltips.
- **Dynamic Surroundings** — `DynamicSurroundings-1.12.2-3.6.1.0.jar`  
  Mejora el audio ambiental y añade atmósfera y efectos más inmersivos.
- **Enchantment Descriptions** — `EnchantmentDescriptions-1.12.2-1.1.15.jar`  
  Muestra descripciones legibles de los encantamientos en los tooltips de los objetos.
- **Falling Leaves** — `fallingleaves-2.1.2.2.jar`  
  Añade partículas decorativas de hojas cayendo alrededor de los árboles.
- **FancyMenu** — `fancymenu_forge_2.14.9_MC_1.12-1.12.2.jar`  
  Proporciona menús principales, overlays y pantallas de interfaz altamente personalizables.
- **Forced Resource Packs** — `forcedresourcepacks-1.1.jar`  
  Ayuda a forzar resource packs obligatorios en los clientes.
- **Friendly Fire** — `FriendlyFire-1.12.2-1.5.10.jar`  
  Permite controlar si los jugadores pueden dañar a aliados, mascotas o compañeros.
- **FTB Utilities** — `FTBUtilities-5.4.1.131.jar`  
  Proporciona utilidades como claims, equipos, waypoints, teletransporte y herramientas de servidor.
- **Good Skeletons Don't Strafe** — `GoodSkeletonsDontStrafe-v1.1.1-1.12.2.jar`  
  Cambia el movimiento de los esqueletos para que su combate a distancia sea más directo.
- **Googly Eyes** — `GooglyEyes-1.12.2-7.1.1.jar`  
  Añade un efecto visual divertido que coloca ojos móviles a las entidades.
- **Highlighter** — `Highlighter-1.12.2-forge-1.1.7.jar`  
  Resalta objetos y bloques bajo el cursor para mejorar su visibilidad.
- **Hwyla** — `Hwyla-1.8.26-B41_1.12.2.jar`  
  Muestra información sobre el bloque o la entidad que estás mirando.
- **Instant Skin** — `InstantSkin.jar`  
  Acelera o simplifica la obtención y visualización de skins en configuraciones compatibles.
- **Inventory Totem** — `inventorytotem_1.12.2-1.3.jar`  
  Muestra de forma más clara y cómoda la información del inventario relacionada con los tótems.
- **Inventory Tweaks** — `InventoryTweaks-1.63.jar`  
  Añade numerosos atajos para ordenar y gestionar el inventario.
- **Item Borders** — `ItemBorders-1.12.2-forge-1.2.0.jar`  
  Añade bordes de colores a los objetos del inventario según su rareza.
- **Item Scroller** — `itemscroller-1.12.2-0.12.0.jar`  
  Permite transferencias rápidas de objetos con el ratón y desplazamiento ágil por los inventarios.
- **Jade** — `Jade-0.1.0.jar`  
  Añade un panel de información en pantalla para bloques, entidades y contenedores.
- **JEI (Just Enough Items)** — `jei_1.12.2-4.16.1.301.jar`  
  Navegador de objetos y recetas para consultar crafteo, fundición y usos.
- **Just Enough Botania** — `Just-Enough-Botania-1.12.2-v0.2.jar`  
  Añade información y recetas al estilo de JEI para el contenido de Botania.
- **Just Enough Resources (JER)** — `JustEnoughResources-1.12.2-0.9.2.60.jar`  
  Amplía JEI con información sobre minerales, drops y recursos generados en el mundo.
- **Map Tooltip** — `maptooltip-1.12.2-1.0.jar`  
  Muestra información adicional relacionada con mapas mediante los tooltips de objetos.
- **MCEF (Minecraft Chromium Embedded Framework)** — `mcef-1.12.2-1.11.jar`  
  Integra contenido web basado en Chromium dentro de Minecraft para mods e interfaces que lo necesiten.
- **Mouse Tweaks** — `MouseTweaks-2.10-mc1.12.2.jar`  
  Mejora la interacción con el inventario mediante arrastre, clic y movimiento de objetos más rápidos.
- **My Server Is Compatible** — `MyServerIsCompatible-1.12.2-1.0.jar`  
  Ayuda a mostrar a los jugadores información sobre la compatibilidad entre el modpack y el servidor.
- **Name Pain** — `namepain-1.5.0 forge-1.12.x.jar`  
  Mejora el renderizado y manejo de nombres largos o problemáticos.
- **Nimble** — `Nimble-0.0.2.jar`  
  Añade pequeñas mejoras de calidad de vida para el movimiento y las interacciones del cliente.
- **Obscure Tooltips** — `obscure_tooltips-forge-1.12.2-3.10.2.jar`  
  Mejora los tooltips de objetos añadiendo contexto y legibilidad.
- **Overloaded Armor Bar** — `overloadedarmorbar-1.0.4g.jar`  
  Permite mostrar valores de armadura y otros indicadores del HUD más allá de los límites de vanilla.
- **Pickup Notifier** — `PickUpNotifier-v1.1.5-1.12.2.jar`  
  Muestra una notificación visual al recoger objetos.
- **Raids Backport** — `Raids-Backport-1.12.2-1.1.5b.jar`  
  Añade a Minecraft 1.12.2 las incursiones y sus mecánicas relacionadas.
- **Server Tab Info** — `ServerTabInfo-1.12.2-1.2.6.jar`  
  Añade más información del servidor y de los jugadores a la lista TAB.
- **Smart Particles** — `smart_particles+mc1.12.2-12.02.9-Forge.jar`  
  Reduce el renderizado innecesario de partículas para mejorar el rendimiento visual.
- **Sound Filters** — `SoundFilters-0.12.1_for_1.12.jar`  
  Añade filtros de sonido ambiental, como audio amortiguado detrás de las paredes.
- **Spiritual Comeback** — `SpiritualComeBack-1.12.2-1.0.0.jar`  
  Permite volver tras morir en forma espiritual para recuperar objetos o interactuar con mecánicas relacionadas con la muerte.
- **ToroHealth Damage Indicators** — `torohealth-1.12.2-11.jar`  
  Muestra la vida y la información de daño de los enemigos en un HUD compacto.
- **Toughness Bar** — `toughnessbar-2.4.jar`  
  Añade al HUD un indicador visible de la resistencia de la armadura.
- **TrashSlot** — `TrashSlot_1.12.2-8.4.10.jar`  
  Añade una ranura de basura dedicada para eliminar rápidamente objetos no deseados.
- **VisualOres** — `visualores-0.2.8.jar`  
  Añade resaltados y efectos visuales a los minerales para identificarlos mejor bajo tierra.
- **WAILA Harvestability** — `WailaHarvestability-mc1.12-1.1.12.jar`  
  Muestra si el bloque seleccionado puede extraerse con la herramienta actual.
- **Waystones** — `Waystones_1.12.2-4.1.0.jar`  
  Añade waystones fabricables para viajes rápidos y teletransporte entre puntos enlazados.
- **WI Zoom** — `wi-zoom-v1.1-MC1.12.2-release.jar`  
  Añade una función de zoom similar a una tecla de acercamiento de cámara.
- **WTS (What's That Slot)** — `WTS-1.1.0.jar`  
  Identifica las ranuras del inventario y explica qué objetos pueden colocarse en ellas.
- **Xaero's Minimap** — `xaerominimap-forge-1.12.2-26.4.2.jar`  
  Añade un minimapa detallado con waypoints, marcadores de entidades y overlays configurables.
- **Xaero's World Map** — `xaeroworldmap-forge-1.12.2-1.44.2.jar`  
  Añade un mapa mundial a pantalla completa con datos de exploración y soporte para waypoints.

[↑ Volver arriba](#top)

---
