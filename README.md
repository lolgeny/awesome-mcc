# awesome-mcc
A curated list of minecraft commands and mapmaking resources.

**Contributions are welcome and wanted. See [CONTRIBUTING.md](CONTRIBUTING.md) for more info.**

# Table of contents
- [Blockbench](#blockbench)
- [Data](#data)
- [Environment](#environment)
- [Generators](#generators)
- [Libraries](#libraries)
- [Mods](#mods)
- [Processing](#processing)
- [Programming languages](#programming-languages)
- [Programs](#programs)
- [Statistics](#statistics)
- [Templates](#templates)
- [Tutorials](#tutorials)
- [Utility](#utility)

# Blockbench
[Website](https://www.blockbench.net): easy to use, free, modern blockmodel editor. features plugins, display settings, custom keybindings, bedrock edition export and multi-cube editing.

- [Armor Stand Animator](https://github.com/DoubleF3lix/Armor-Stand-Animator) - provides an interface for Blockbench to animate armor stands which is converted to a data pack

# Environment
Add-ons for your coding environment to aid in development.

- [Data Pack Helper Plus](https://marketplace.visualstudio.com/items?itemName=SPGoding.datapack-language-server) - Visual Studio Code extension for data pack development
- [NBT Viewer](https://marketplace.visualstudio.com/items?itemName=Misodee.vscode-nbt) - Visual Studio Code extension for viewing any nbt file including structures

# Data
Varying sources of any documentable data for the game in various machine & human readable formats.

- [ArticData](https://github.com/Articdive/ArticData) - repository of version-controlled history of curated additional game data generated with a Fabric mod
- [Minecraft Assets](https://mcasset.cloud) - provides an interface to view a version-controlled history **all** raw minecraft data & assets for any version [hosted on GitHub](https://github.com/InventivetalentDev/minecraft-assets/tree/1.17.1)
- [mcdata](https://github.com/Arcensoth/mcdata) - repository of version-controlled history of the Minecraft server's officially generated game data, along with processed files for most types
- [mc-nbtdoc](https://github.com/Yurihaia/mc-nbtdoc) - partially-automatic updating repository of version-controlled history of Minecraft nbt schemas including entities, blocks, & items utilizing a generated Fabric mod & manual labor
- [Vanilla Datapack](https://github.com/SPGoding/vanilla-datapack) - automatically updating repository of version-controlled history of Minecraft's Datapack with indexed type summaries (does not include Structure binaries, only their paths/names in the summary)

# Generators
External tooling for easier generation/creation of various data(pack) files

- [allay](https://pypi.org/project/allay/) - a parser to convert a descriptive text format into minecraft text components
- [mcgen](https://github.com/Arcensoth/mcgen) - create your own copy of mcdata
- [misode.github.io](https://misode.github.io) - a collection of amazing generators for datapacks
- [Raycast Generator](https://skylinerw.com/vdvman1/raycast/) - generate raycast datapacks
- [Shapes Generator](https://chencmd.github.io/Shapes-Generator/) - a web tool that can generate mcfunction files consisting of static particle commands

# Libraries
Packs written for usage in other packs and/or maps that provide reusable functionality.

Data:
- [Arithmatic WASD](https://github.com/MulverineX/wasd_arithmetic) - detection of local direction input (ie wasd)
- [Exported 1.18 Settings](https://github.com/misode/vanilla-worldgen/tree/1.18-experimental) - using modding, the vanilla worldgen files for the 1.18 experimental snapshots
- [ftde](https://github.com/gibbsly/ftde) - prevent players from messing with fence gates and trapdoors while in adventure and survival
- [Lantern load](https://github.com/LanternMC/load) - a simple implementation of version resolution intended to allow data packs and their dependencies to load in a controllable order
- [ltos](https://github.com/gibbsly/ltos) - a utility that allows you to reliably determine where a block was broken and who or what broke it, as well as where an entity was killed and who or what killed it
- [NBT Crafting API](https://github.com/BigPapi13/NBT-Crafting-API) - allows datapack creators to get the nbt data of items used in the crafting table and apply it to the output
- [Quiet custom blocks](https://github.com/Ellivers/QCB) - make barrel based blocks without the noise
- [Ray Collision Detector](https://github.com/K-bai/Minecraft-Ray-Collision-Detector) - advanced ray casting and block/entity collition detection.
- [Score based damage](https://github.com/ErrorCraft/Score-Based-Damage/releases) - apply damage dynamically based on a score
- [String Parsing](https://github.com/5uso/String-Parser) - parse strings into a char array

Asset:
- [Negative space font](https://github.com/AmberWat/NegativeSpaceFont/blob/master/README.md) - resource pack with positive and negative sized spaces

Shader:
- [Core shaders - Onnowhere](https://github.com/onnowhere/core_shaders) - contains utilities and examples for core shaders
- [Depth shaders - Onnowhere](https://github.com/onnowhere/depth_shaders) - contains examples of depth shaders including function to linearize depth
- [FancyPants](https://github.com/Ancientkingg/fancyPants) - allows datapack devs to add custom textured armor to the game with coloured leather armor with core shaders
- [Mc Atlas UV Resolver](https://github.com/OrangeUtan/mc-atlas-uv-resolver/releases) - generated uv atalas for 1.17
- [Player model mapping](https://user-images.githubusercontent.com/30565442/132574881-47defa76-cbe7-420d-9ca4-56b743666eca.png) - reference for the value of gl_VertexID in rendertype_entity_translucent for a player model
- [Core Shader Info](https://docs.google.com/document/d/18AhcnAI55liax72yh70njUomIzezOKshCurfdZPTKwM/edit#heading=h.o0otiitbizd) - a helpful guide to minecraft's shader system
- [VanillaDynamicEmissives](https://github.com/ShockMicro/VanillaDynamicEmissives/) - a simple way to make emissive textures without Optifine
- [VertexEdit](https://github.com/onnowhere/VertexEdit) - a GLSL shader image tool for vanilla Minecraft with various vertex and UV editing features

# Mods
Modifications to the base game that can aid in datapack & map creation/development.

- [Chase enabler](https://github.com/MrDodojo/minecraftChaseEnabler) - enables a debug feature called *Chase* on multiple versions
- [Data reload](https://www.curseforge.com/minecraft/mc-mods/data-reload) - displays datapack load errors in chat (when installed server side) and adds a F3+Y keybind to /reload (when installed client side)
- [Gitmod](https://github.com/rx-modules/GitMod) - a cursed serverside git client in mc
- [Language reload](https://modrinth.com/mod/language-reload) - adds F3+J to reload language files instantly, instant switching between languages
- [Resource reload](https://github.com/PotatoPresident/resource-reload/tree/1.0.0) - resends the server resource pack to clients on `/reload`
- [Shader reload](https://www.curseforge.com/minecraft/mc-mods/shader-reload) - adds F3+R to reload shaders only much faster, displaying errors in chat
- [Worldedit](https://www.curseforge.com/minecraft/mc-mods/worldedit) - a map editor that runs in game

# Processing
External meta tooling for pack environment & development; ala Webpack.

- [babelbox](https://github.com/OrangeUtan/babelbox) - a language localization generator
- [beet](https://github.com/mcbeet/beet) - the Minecraft pack development kit
- [Mitochondria](https://mito.thenuclearnexus.live/) - a website to merge resourcepacks and datapacks

# Programming languages
Designed to pre-compile to minecraft packs in order to abstract and/or speed development.

- [Bell](https://github.com/Miestrode/bell) - programming language to help Minecraft data pack developers work smarter and faster
- [CMC](https://github.com/Command-Master/CMC) - an object oriented language which compiles to commands
- [debris](https://github.com/Inky-developer/debris) - Debris is a powerful language & compiler which aims to make the process of creating a datapack easier and quicker
- [lectern](https://github.com/mcbeet/lectern) - literate programming, in Minecraft
- [mc-build/lang-mc](https://mcbuild.dev) - a function like language with syntactic sugar for creating datapacks.
- [McFunctionExtensions](https://github.com/cgytrus/MCFunctionExtensions) - some extensions to the vanilla Minecraft functions syntax
- [minity](https://minity-script.github.io/#/) - A scripting language for Vanilla Minecraft
- [Onyx](https://pypi.org/project/onyx-mclib) - a python library to create datapacks
- [Sandstone](https://github.com/TheMrZZ/Sandstone) - a javascript library for datapacks
- [Trident](https://energyxxer.com/trident/) - an extensive programming language for datapacks

# Programs
External applications/tools to aid in pack creation/development.

- [Advancement Disabler](https://www.youtube.com/watch?v=GdOZf-WIonQ) - datapacks and scripts for disabling vanilla advancements and recipes
- [Chunker](https://chunker.app/) - tool for converting between java and bedrock worlds
- [Entity motion predictor](https://www.desmos.com/calculator/z7ouukcemh) - predict an entity's motion
- [Image to particles converter](https://github.com/RedCocoon/PythonSiphon/blob/main/minecraft-tools/image_to_particles_converter.py) - convert an image into particles
- [Mapcraft](https://mapcraft.app/) - software that increases the possibilities of mapmakers without any complex installation
- [Minecraft version compare](https://github.com/Plagiatus/mc-version-compare/releases) - a program that analyses the assets and data folders of the jars of two versions and shows you what changed between them
- [NBT Studio](https://github.com/tryashtar/nbt-studio) - an up to date NBT viewer and editor with lots of new features

# Statistics
External applications/tooling to show off your packs' girth.

- [DatapackStats](https://github.com/ICY105/DatapackStats) - a small java program that will generate a bunch interesting numbers about your datapack
- [Function analyser](https://github.com/ErrorCraft/FunctionAnalyser) - analyse all of your functions and generate a report that includes details about them

# Templates
- [MapmakingTemplate](https://github.com/Plagiatus/MapmakingTemplate) - a template for maps, with a datapack, resourcepack and helpful explanations

# Tutorials
- [aqoc](https://aqoc.github.io) - a collection of tutorials for common command questions
- [Custom UI bars](https://www.youtube.com/watch?v=EL2X6ppZSCQ) - how to add custom ui bars such as mana
- [Entity hit detection](https://www.youtube.com/watch?v=YZfCBBvOMN4) - how to target hit entities
- [How not to use /execute](https://gist.github.com/Aeldrion/419e3da12666280cbfd2dabf567dc36c) - common mistakes people make with `/execute`
- [Practices and tricks](https://gist.github.com/Ellivers/762822ee452f1beb058f044ec3139d73) - some good practices and common tricks for making a data pack for people that aren't as experienced
- [Removing red numbers from sidebars](https://www.youtube.com/watch?v=dD6V0bKf-Bc) - how to display in the scoreboard without red number lines
- [Smooth Rotation](https://www.youtube.com/watch?v=xamAY7fpgeQ) - smoothly rotate the player over time
- [Workaround to MC-227930](https://gist.github.com/GrantGryczan/f0a51fc195f76da570d67826974bf2de#file-guide-to-working-around-mc-227930-md) - how to forceload a chunk this tick

# Utility
Packs that provide utility for the development of packs.

- [Benchmark](https://www.planetminecraft.com/data-pack/benchmark-a-data-pack-for-testing-function-efficiency/) - a data pack for testing the efficiency of some function or command technique
- [Command Block Preview](https://www.planetminecraft.com/data-pack/command-block-preview/) - preview command block context with floating text
