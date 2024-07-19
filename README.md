# Awesome Mafia Modding tools and Resources

A curated list of awesome Mafia modding tools and resources.

## Contents

### [Cheats](pages/cheats.md)
### [Patches](pages/patches.md)

- [Communities](#communities)
- [Editors](#editors)
  - [3D Map editors](#3d-map-editors)
  - [Collision editors](#collision-editors)
  - [Lightmap editors and creators](#lightmap-editors-and-creators)
  - [Script editors](#script-editors)
  - [Text and Value editors](#text-and-value-editors)
  - [Scene2.bin Editors](#scene2bin-editors)
  - [Cache.bin Editors](#cachebin-editors)
  - [Check.bin Editors](#checkbin-editors)
- [DTA extractors and packers](#dta-extractors-and-packers)
- [Tools](#tools)
  - [4ds tools](#4ds-tools)
  - [5ds tools](#5ds-tools)
- [Addons and Plugins](#addons-and-plugins)
- [Resources and Documentations](#resources-and-documentations)
- [Contribute](#contribute)
- [License](#license)

### Communities

- [MafiaHub](https://discord.gg/eBQ4QHX) - MafiaHub Community Discord server
- [Greavesy's Toolbox](https://discord.gg/HFCksVXXWy) - Home of Toolkits and Community Discord server

## Editors
To start modding Mafia, you need an arsenal of various editors, but what's even more important... You **NEED** MafiaDataXTractor
- [MafiaDataXTractor](https://github.com/user-attachments/files/16238944/MafiaDataXTractor.zip) - Extracts .dta files of Mafia to allow for modding and editing. For Mafia 1.0 use MafiaDataXTractor 1.0, for Mafia 1.1/1.2/1.3 use MafiaDataXTractor 1.1
: To correctly extract the .dta files, place the MafiaDataXTractor to your Mafia game directory where Game.exe is located and run MafiaDataXTractor as Administrator!

### 3D Map Editors
- [Mafcapone](https://github.com/user-attachments/files/16227907/Mafcapone.cl-1.zip) - Mission editor for Mafia
- [Capone](https://github.com/user-attachments/files/16268034/Capone.1.0d1.zip) - Mission editor for Mafia 1.0 ONLY
- [LS3D Sandbox](https://github.com/user-attachments/files/16315526/LS3D.Sandbox.zip) - **! Unsure of functionality !**
- [LS3D Sandbox 2](https://github.com/user-attachments/files/16315525/LS3D.Sandbox.2.zip) - **! Unsure of functionality !**

### Collision Editors
Mafia has a special collision file called "tree.klz"
- [TreeRE](https://github.com/user-attachments/files/16255223/TreeRE.Collection.zip) - Collision editor

### Lightmap Editors and Creators
- [LS3D Lightmapper](https://github.com/user-attachments/files/16315522/LS3D.Lightmapper.zip) - 3D lightmap editor based on LS3D Sandbox
- [LMToner](https://github.com/user-attachments/files/16315521/LMToner.v6.2.zip) - ??? Can create colored lightmaps?
- [LmapGen 2](https://github.com/user-attachments/files/16315519/LmapGen.2.zip) - ??? Clones lightmap from .4ds model to another .4ds model?

### Script Editors
Mafia uses a special scripting language, it has no official name but the community adopted the name "Mafia Script"
- [Project Angelo](https://github.com/user-attachments/files/16238313/Project_Angelo_script_inspector.zip) - In-game script editor and debugger for Mafia 1.0 ONLY!
- [BScriptView](https://github.com/user-attachments/files/16255201/BScriptView.Collection.zip) - Scene2.bin editor and Script editor
- [DCED 2](https://github.com/user-attachments/files/16268313/DCED2.zip) - Scene2 editor and Script editor, also known as "DONCity Editor 2"

### Text and Value editors
Mafia's text is stored in tables with a .def extension
- [CSVtoDEF](https://github.com/user-attachments/files/16238771/CSVtoDef.zip) - Converts .csv file sheet into Mafia .def text file
- [Car Index Editor](https://github.com/user-attachments/files/16268038/Car.Index.Editor.zip) - ???
- [M Editor](https://github.com/user-attachments/files/16315588/M.Editor.v1.12.zip) - Can edit various texts and values such as .def files, vehicle settings, loading screens, GUI and more
- [Mafia Car Value Editor](https://github.com/user-attachments/files/16315594/Mafia.Car.Value.Editor.zip) - Can edit car settings, editor has English, Czech and Russian versions
- [Mafia Editor (.def)](https://github.com/user-attachments/files/16315596/Mafia.Editor.def.v2.0.zip) - Can edit .def text files
- [Mafia Text Editor](https://github.com/user-attachments/files/16315707/Mafia.Text.Editor.1.0.%2B.1.1.zip) - Can edit .def text files
- [Mafia Value Editor](https://github.com/user-attachments/files/16315708/Mafia.Value.Editor.v0.0.6.81.zip) - Can edit Scene2.bin, car settings and weapon settings
- [Mafia Weapons Editor](https://github.com/user-attachments/files/16315709/Mafia.Weapon.Editor.zip) - Can edit weapon settings
- [Mafia Weapon Value Editor](https://github.com/user-attachments/files/16315710/Mafia.Weapon.Value.Editor.zip) - Can edit weapon settings

### Scene2.bin Editors
Scene2.bin is a soul of every Mafia mission as it houses everything the player can interact with
- [Boz Scene Tree Editor](https://github.com/user-attachments/files/16267683/Boz.Scene.Tree.Editor.zip) - Can edit all values of Scene2.bin mission file
  - [Boz Scene Tree Editor on github by djbozkosz](https://github.com/djbozkosz/BozSceneTreeEditor)
 
### Cache.bin Editors
- [Cache Fu!cker](https://github.com/user-attachments/files/16268030/Cache.Fucker.v1.0.zip) - ???
- [Cache.bin Editor](https://github.com/user-attachments/files/16268032/Cache.bin.Editor.zip) - Can edit position and values of cache.bin
- [CacheRE](https://github.com/user-attachments/files/16268033/CacheRE.v1.1.%2B.1.2.zip) - Can edit all values of cache.bin

### Check.bin Editors
Check.bin is a file where the pedestrian and vehicle mesh networks are stored, without it, Lost Heaven would be a ghost town
- [Check.bin Editor](https://github.com/user-attachments/files/16273704/Check.bin.Editor.EN%2BRU.zip) - Can edit and create check.bin navigation mesh for pedestrians, vehicles, enemies and more
- [CheckRE](https://github.com/user-attachments/files/16273712/CheckRE.1.3.zip) - Can edit check.bin to add pedestrians and vehicles

## DTA extractors and packers
- [MafiaDataXTractor](https://github.com/user-attachments/files/16238944/MafiaDataXTractor.zip) - Most popular program for extracting .dta files
- [DTAUnpacker](https://github.com/user-attachments/files/16268332/DTA.Unpacker.cline.zip) - Commandline program for unpacking .dta files
  - [DTAUnpacker on github by jovan-s](https://github.com/jovan-s/DTAUnpacker)
- [DTA Packer](https://github.com/user-attachments/files/16268337/DTAs.Packer.zip) - Adds modified files into .dta file (*documentation needed*)
- [DTA Unpacker](https://github.com/user-attachments/files/16268335/DTA.Unpacker.zip) - Extract files from .dta files of Mafia, Hidden & Dangerous 2, Chameleon

## Tools
- [Mafia DTA Extractor Tool](https://github.com/user-attachments/files/16255367/Mafia.DTA.Extractor.zip) - Exctracts Mafia's .dta files (includes preset extraction keys for billboard and patch DTA files and all other common DTA files)
- [Car Changer](https://github.com/user-attachments/files/16268035/Car.Changer.v1.4.zip) - ???
- [TACO-M](https://github.com/user-attachments/files/16238359/TACO-M.zip) - Mafia memory manipulation tool
- [def2bbrd](https://github.com/user-attachments/files/16268316/def2bbrd.v0.5.zip) - ???
- [DNC Extractor](https://github.com/user-attachments/files/16268324/DNC.Extractor.zip) - Can export and import .dnc files from and to scene2.bin file (for use with DCED 2)
- [Dog Maker](https://github.com/user-attachments/files/16268326/Dog.Maker.zip) - Creates .dnc files of a dog using specified values by the user
- [Draw Distance Unlimiter](https://github.com/user-attachments/files/16268327/Draw.Distance.Unlimiter.zip) - Patches cache.bin of a selected mission to increase draw distance (follow instructions given by the program)
- [Effects.bin Editor](https://github.com/user-attachments/files/16273701/Effects.bin.Editor.zip) - Can edit effects.bin file to add or remove particle effects from a mission
- [Glow Maker](https://github.com/user-attachments/files/16273702/Glow.Maker.zip) - ???
- [GmfRE](https://github.com/user-attachments/files/16273703/GmfRE.v1.1.zip) - ??? Making custom font for Mafia?
- [CHG Editor](https://github.com/user-attachments/files/16273713/CHG.Editor.v1.1.%2B.v3.0.zip) - ???
- [CHG Maker](https://github.com/user-attachments/files/16273714/CHG.Maker.zip) - ??? Some script creator/editor?
- [Mafia 1.0 Plus](https://github.com/user-attachments/files/16315590/Mafia.1.0.Plus.zip) - ???
- [Mafia Car Adder and Remover](https://github.com/user-attachments/files/16315591/Mafia.Car.Adder.Remover.v0.62.Beta.zip) - ??? Can add new cars and remove cars?
- [Mafia Car Installer](https://github.com/user-attachments/files/16315593/Mafia.Car.Installer.zip) - ??? Can add new cars?
- [Mafia GetPos](https://github.com/user-attachments/files/16315597/Mafia.GetPos.zip) - ??? for Mafia 1.0 ONLY!
- [Mafia Load Editor](https://github.com/user-attachments/files/16315705/Mafia.Load.Editor.v1.0.zip) - Can add and edit loading screens for missions

### 4ds tools
.4ds is LS3D model file
- [4ds Converter](https://github.com/user-attachments/files/16267266/4ds.Converter.2004.zip) - Converts .4ds model files to .obj and .wrl for use with 3D Modeling Programs (**16 BIT PROGRAM**)
- [4ds Distance fix](https://github.com/user-attachments/files/16267267/4ds.Distance.Fix.2007.zip) - ??? Probably makes model visible on long distances?
- [4ds From PS2 Converter](https://github.com/user-attachments/files/16267269/4ds.From.PS2.Converter.zip) - Converts .4ds models from Mafia on PS2 to models for use on Mafia PC
- [4ds Texture Manager](https://github.com/user-attachments/files/16267271/4ds.Manager.Textures.zip) - ???
- [Light Sector Cleaner](https://github.com/user-attachments/files/16267273/4ds.Sector.Cleaner.zip) - ??? Removes light sources from sectors?
- [4ds Unlocker](https://github.com/user-attachments/files/16267274/4ds.Unlocker.zip) - Makes .4ds model file able to be edited with Zazona Modeler and possibly other 3D Modeling Programs
- [4ds View](https://github.com/user-attachments/files/16267276/4ds.View.v8.3.zip) - .4ds Model viewer
- [Boz 4ds Full Manager](https://github.com/user-attachments/files/16267681/Boz.4ds.Full.Manager.zip) - Can edit all values of .4ds model

### 5ds tools
.5ds is LS3D animation file
- [5ds Converter](https://github.com/user-attachments/files/16267277/5ds.Converter.v1.1.zip) - Converts .3ds Animation file to .5ds Animation file for use with Mafia

## Addons and Plugins
Addons and plugins for various 3D Modeling Programs for use with Mafia's file formats
- [Noesis .4ds Plugin](https://github.com/user-attachments/files/16315885/noesis-plugins-master.zip) - Plugin for importing LS3D .4ds model
  - [Noesis .4ds Plugin on github by RoadTrain](https://github.com/RoadTrain/noesis-plugins)
- [Blender Mafia 4ds Addon](https://github.com/user-attachments/files/16315886/BlenderMafia4ds-master.zip) - Addon for importing and exporting Mafia .4ds model for Blender 2.8
  - [Blender Mafia 4ds Addon on github by djbozkosz](https://github.com/djbozkosz/BlenderMafia4ds)

## Resources and Documentations

- [MSDR CZ](https://github.com/user-attachments/files/16228218/MSDR.CZ.pdf) - Mafia Script & Data Reference in Czech language
- [3D Model List](https://github.com/user-attachments/files/16238692/3D.Model.List.zip) - Characters Model list in English and Russian, Model list in Russian
- [Zazona Modeler basics (Czech)](https://github.com/user-attachments/files/16238734/zaklady_zmodeleru.pdf) - Basic Guide for Zmodeler v1.07b/c in Czech language
- [Cutscene Guide (Czech)](https://github.com/user-attachments/files/16238732/navod_cutsceny.pdf) - Guide for In-Game cutscenes in Czech language
- [BScriptView v6.0 Guide](https://github.com/user-attachments/files/16255436/BScriptView.6.0.pdf) - Guide for BScriptView v6.0
- [Model Implementation Guide](https://github.com/user-attachments/files/16255438/Mr.Robville.s.Model.Implementation.Guide.2015.pdf) - Guide explains how to take a model from any 3D program and place it in an empty scene
- [Empty Mission](https://github.com/user-attachments/files/16255595/Empty_Mission.zip) - Empty mission, useful for creating new map or mission from scratch
- [Mafia Script Helper 2](https://github.com/user-attachments/files/16315706/Mafia.Script.Helper.v2.0.zip) - Mafia Script reference in Czech and English, similar to MSDR

## Contribute

Contributions are welcome! Please follow our [contribution guidelines](https://github.com/MafiaHub/awesome-mafia/blob/main/CONTRIBUTING.md) to contribute to this list.

## License

This list is licensed under the [Apache 2.0 License](https://github.com/MafiaHub/awesome-mafia/blob/main/LICENSE).
