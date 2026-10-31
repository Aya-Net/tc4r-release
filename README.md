# TC4R

**Research, alchemy, infusion, and magical constructs for Minecraft.**

English · [简体中文](README.zh-CN.md)

[Downloads and releases](https://github.com/Aya-Net/tc4r-release/releases)

**Thaumic Core for Release (TC4R)** is a magic mod for Minecraft, with the mod ID **`tc4r`**.

Scan the world, discover its aspects, unlock research, and build an alchemical workshop. Experiment with wands and magical energy, use infusion to create equipment, and put magical constructs to work.

This repository provides compiled **TC4R core runtime JARs** and matching **native API JARs**. The current mod version is **1.0.1**; each file also identifies its Minecraft version and loader.

## What awaits you

- **Research and discovery.** Investigate the world and unlock knowledge through a connected research system.
- **Wands and magical energy.** Explore energy nodes, assemble wands, and turn research into practical abilities.
- **Alchemy and infusion.** Extract and transport essentia, build a workshop, and create magical tools and equipment.
- **Constructs and exploration.** Automate tasks with constructs and encounter the consequences of dangerous research.

## Choose your version

| Minecraft | Loader | Java | Runtime JAR | Native API JAR |
| --- | --- | --- | --- | --- |
| 1.20.1 | Forge 47.4.10 or newer | 17 | `tc4r-1.20.1-forge-1.0.1.jar` | `tc4r-1.20.1-forge-1.0.1-api.jar` |
| 1.21.1 | NeoForge 21.1.248 or newer | 21 | `tc4r-1.21.1-neoforge-1.0.1.jar` | `tc4r-1.21.1-neoforge-1.0.1-api.jar` |

Choose the file for your exact Minecraft version and loader from the [Releases page](https://github.com/Aya-Net/tc4r-release/releases). Release notes include SHA-256 checksums.

## Installation

1. Create an instance with the Minecraft version, loader, and Java version listed above.
2. Install matching versions of **Curios** and **TerraBlender** using the requirements below.
3. Download the runtime JAR and place it directly in the instance's `mods` folder.
4. When updating, replace the previous TC4R runtime JAR and restart the game or server.

This release contains the core mod. Addons must target the same TC4R version, Minecraft version, and loader.

## Required dependencies

These ranges come from the released JARs' loader metadata. Install files made for the same Minecraft version and loader.

| Dependency | Minecraft 1.20.1 · Forge | Minecraft 1.21.1 · NeoForge |
| --- | --- | --- |
| [Curios](https://modrinth.com/mod/curios/versions) | `>= 5.14.1+1.20.1`, `< 6` | `>= 9.5.1` |
| [TerraBlender](https://modrinth.com/mod/terrablender/versions) | `>= 3.0.1.10`, `< 4` | `>= 4.1.0.8` |

## Presentation and resources

TC4R combines single-color textures with 8-bit-style sound, giving its magic a simple, distinctive retro character.

## Resource-pack authoring example

The separate [TC4R resource-pack authoring example](https://github.com/Aya-Net/tc4r-resourcepack-example) illustrates resource layout and organization. The matching release is [v1.0.1](https://github.com/Aya-Net/tc4r-resourcepack-example/releases/tag/v1.0.1).

**This resource pack is an independent learning example, separate from and not part of the TC4R core project. It is provided solely for studying resource-pack creation. Materials remain the property of their respective rights holders; please open an issue in the example repository to request removal of infringing material. Existing permissions remain applicable.**

## License

Author: **thaumic scissors**.

Covered material is distributed under **TC4R Source-Available, No-Redistribution License 1.0** (`LicenseRef-TC4R-No-Redistribution`). Private viewing, use, and local modification are permitted; redistribution requires prior written permission. Read the [standalone license](LICENSE) or [download it from v1.0.1](https://github.com/Aya-Net/tc4r-release/releases/download/v1.0.1/LICENSE-TC4R.txt); `LICENSE-TC4R.txt` and `NOTICE-TC4R.txt` inside each JAR give the full terms and scope. Third-party material remains subject to its own notices and permissions.
