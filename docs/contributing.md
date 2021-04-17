## Contributing Guide

***1*** The first step to contributing to the Kabuki Starship is to install Git at <https://git-scm.com> and to clone our source repositories using the command:

```BASH
git clone https://github.com/KabukiStarship/KabukiStarship --recursive
```

***2*** Read the [Roadmap](./roadmap.md).

***3*** Look through the Kabuki Starship project Contributing Guide in the `/docs/contributing.md` file in each repository:

* [Script2](https://github.com/KabukiStarship/Script2) - The Serial Chinese Room, Interprocess, and Telemetry (SCRIPT) Script (Script2) is a modern Embedded-C++ framework, dynamic I am You Language (IMUL) interpreter, and the SCRIPT Specification.
* [ScriptTek](https://github.com/KabukiStarship/ScriptTek) - A cross-API Firmware Development Kit for mbed, Arduino, and Kabuki Toolkit.
* [KabukiToolkit](https://github.com/KabukiStarship/KabukiToolkit) - A Modern Embedded-C++, Script2, and I am You Language (IMUL) toolkit.
* [KabukiBenchmark](https://github.com/KabukiStarship/KabukiBenchmark) - An extendable Modern-Embedded-C++ benchmarking utility.
* [KabukiPress](https://github.com/KabukiStarship/KabukiPress) - A Modern Embedded-C++, Script2, and IMUL web and document framework and server.
* [IGeek](https://github.com/KabukiStarship/IGeek) - The Interactive Gym Environment and Education Kit is an AI gym environment and game engine for building, training, testing, and comparing Agents in different types of environments.
* [IGeekBlockWorld](https://github.com/KabukiStarship/IGeekBlockWorld) - A block world environment for the Interactive Gym Environment and Educational Kit (IGEEK).
* [IGeekCardWorld](https://github.com/KabukiStarship/IGeekCardWorld) - A card game environment for the Interactive Gym Environment and Education Kit.
* [IGeekCarWorld](https://github.com/KabukiStarship/IGeekCarWorld) -  An autopilot for the Interactive Gym Environment and Education Kit (IGEEK).
* [IGeekHuman](https://github.com/KabukiStarship/IGeekHuman) - A biomimicry environment for IGEEK simulating an abstract human body with robotic white blood cells and viruses.
* [IGeekPacWorld](https://github.com/KabukiStarship/IGeekPacWorld) -  A Search and destroy mini-game for IGeek where you battle ghosts in a maze.
* [IGeekTileWorld](https://github.com/KabukiStarship/IGeekTileWorld) - A 2D tile world environment for IGeek.
* [IGeekTypecraft](https://github.com/KabukiStarship/IGeekTypecraft) - A typing tutor and Interactive Gym Environment and Education Kit (IGeek) environment where you mine, craft, build, and fight mobs by doing typing lessons.)
* [IGeekWikiWorld](https://github.com/KabukiStarship/WikiWorld) - An IGeek Wiki-like site environment that fits as much of Wikipedia into RAM as possible.

***4*** Dive into the code!

All of the above APIs depend on [Script2](https://github.com/KabukiStarship/Script2), which is not working right now, so getting Script2 working is the most important task. After than all of the code in [ScriptTek](https://github.com/KabukiStarship/ScriptTek) and [KabukiToolkit](https://github.com/KabukiStarship/KabukiToolkit) have to get fixed. The GUI toolkit we're using is [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear) and the core is getting swapped out with Script2 with Embedded-C++ bindings. We're then going to take a minimalist C++ graph plotting library and replace the core of that out with our Nuklear remake. For right now we're just going to use Nuklear as is to focus on IGeekCarWorld and IGeekWikiWorld and just update the code that we need to get started.

## License

Copyright © 2021 [Kabuki Starship](https://kabukistarship.com).

This Source Code Form is subject to the terms of the Mozilla Public License, v. 2.0. If a copy of the MPL was not distributed with this file, You can obtain one at <https://mozilla.org/MPL/2.0/>.
