# osu!framework [![Build status](https://ci.appveyor.com/api/projects/status/fh5mnml3vsfheymp?svg=true)](https://ci.appveyor.com/project/peppy/osu-framework) [![CodeFactor](https://www.codefactor.io/repository/github/ppy/osu-framework/badge)](https://www.codefactor.io/repository/github/ppy/osu-framework) [![dev chat](https://discordapp.com/api/guilds/188630481301012481/widget.png?style=shield)](https://discord.gg/ppy)

A game framework written with [osu!](https://github.com/ppy/osu) in mind.

# Requirements

- A desktop platform with the [.NET Core SDK 2.2](https://www.microsoft.com/net/learn/get-started) or higher installed.
- When working with the codebase, we recommend using an IDE with intellisense and syntax highlighting, such as [Visual Studio Community Edition](https://www.visualstudio.com/) (Windows), [Visual Studio Code](https://code.visualstudio.com/) (with the C# plugin installed) or [Jetbrains Rider](https://www.jetbrains.com/rider/) (commercial).

# Objectives

This framework is intended to take steps beyond what you would normally expect from a game framework. This means things like basic UI elements, text rendering, advanced input handling (textboxes) and performance overlays are provided out-of-the-box. Any of the osu! code that is deemed useful to other game projects will live in this framework project.

- Anywhere we implement graphical components, they will be displayed with a generic design and will be derivable for further customisation.
- Common elements used by games (texture caching, font loading) will be automatically initialised at runtime.
- Allow for isolated development of components via a solid testing environment (`VisualTests` and `TestCases`). Check the [wiki](https://github.com/ppy/osu-framework/wiki/Development-and-Testing) for more information on how these can be used to streamline development.

# Contributing

Contributions can be made via pull requests to this repository. We hope to credit and reward larger contributions via a [bounty system](https://www.bountysource.com/teams/ppy). If you're unsure of what you can help with, check out the [list of open issues](https://github.com/ppy/osu-framework/issues).

Note that while we already have certain standards in place, nothing is set in stone. If you have an issue with the way code is structured; with any libraries we are using; with any processes involved with contributing, *please* bring it up. I welcome all feedback so we can make contributing to this project as pain-free as possible.

# Licence

This framework is licensed under the [MIT licence](https://opensource.org/licenses/MIT). Please see [the licence file](LICENCE) for more information. [tl;dr](https://tldrlegal.com/license/mit-license) you can do whatever you want as long as you include the original copyright and license notice in any copy of the software/source.

The BASS audio library (a dependency of this framework) is a commercial product. While it is free for non-commercial use, please ensure to [obtain a valid licence](http://www.un4seen.com/bass.html#license) if you plan on distributing any application using it commercially.

# Projects that use osu!framework

[osu!](https://github.com/ppy/osu) – rhythm is just a *click* away!

<!--
We love to see people using our framework! Add your project here via a PR!

Conditions:
 - Must be a github link (ie. your project is open source)
 - Must be actively developed
-->
