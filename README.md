# Loupgarenne

**A modern fork of Lugaru HD**

Loupgarenne is a fork of [OSS Lugaru](https://gitlab.com/osslugaru/lugaru) focused on
technical improvements and modern platform support. The goal is to add enhancements to Lugaru while preserving the original gameplay experience.

## Features implemented

- Unlocked framerate with fixed timestep physics
- Fully frame-rate independent animations, timers, and visual effects
- Apple Silicon (ARM64) support for macOS builds
- UI fixes
- Build pipeline improvements and refactoring

## Features I'd like to see implemented

- Anisotropic texture filtering
- Proper anti-aliasing
- Enhanced shadows
- Settings to improve view distance
- Enhanced font rendering
- More builds: Linux ARM64, FreeBSD, CentOS etc. Nintendo Switch?

## Credits

- **Original game**: [Wolfire Games](http://www.wolfire.com) - Lugaru HD
- **Open source project**: [OSS Lugaru team](https://gitlab.com/osslugaru/lugaru)
- **This fork**: Loupgarenne

## Getting the game data

This repository contains the source code, but you need the game data files to play.
You can purchase Lugaru HD from:
- [Steam](https://store.steampowered.com/app/25010/Lugaru_HD/)
- [Humble Bundle](https://www.humblebundle.com/store/lugaru)

## Installation

Download the latest release for your platform from the [Releases page](https://github.com/ryandeering/loupgarenne/releases):

- **Windows**: `loupgarenne-x.x-windows-x64.zip` (64-bit) or `loupgarenne-x.x-windows-x86.zip` (32-bit)
- **macOS**: `loupgarenne-x.x-macos-universal.zip` (Intel and Apple Silicon)
- **Linux**: `loupgarenne-x.x-linux-x64.tar.gz`

Extract the archive and either:
- Copy the executable (`lugaru.exe` on Windows, `lugaru` on Linux, or the app bundle on macOS) into your existing Lugaru HD installation folder

## Project links

**Upstream OSS Lugaru:**
- GitLab repository: https://gitlab.com/osslugaru/lugaru
- Project website: https://osslugaru.gitlab.io

## The game

Lugaru (pronounced Loo-GAH-roo) is a cross-platform third-person action game.
The main character, Turner, is an anthropomorphic rebel bunny rabbit with
impressive combat skills. In his quest to find those responsible for
slaughtering his village, he uncovers a far-reaching conspiracy involving the
corrupt leaders of the rabbit republic and the starving wolves from a nearby
den. Turner takes it upon himself to fight against their plot and save his
fellow rabbits from slavery.

## Name

Loupgarenne takes inspiration from the French loup-garou, meaning werewolf, which is also the origin of the name Lugaru.
Garenne is, in modern French, a word for a rabbit warren - making it a fitting double meaning for a game centred on rabbits and wolves.

## History

Lugaru was originally developed by David Rosen of [Wolfire Games](http://www.wolfire.com)
and was [open sourced in 2010](http://blog.wolfire.com/2010/05/Lugaru-goes-open-source).
It was made cross-platform with the help of [Ryan C. Gordon](http://icculus.org).

Various forks were made at that time, and the most interesting developments
were put back together under the OSS Lugaru organization, originally on
[Google Code](https://code.google.com/p/lugaru) and then on
[Bitbucket](https://bitbucket.org/osslugaru/lugaru).

The OSS Lugaru repository on [GitLab](https://gitlab.com/osslugaru/lugaru) is run
by the OSS Lugaru team, aiming to revitalise the development effort, clean
things up, ensure the code base builds and runs fine on all supported
platforms, and ease packaging of Lugaru in Linux distributions.

Loupgarenne is a fork of OSS Lugaru focused on enhancements, technical improvements and modern platform support.

## Compiling

See the `COMPILING.md` for compilation instructions on all supported
platforms.

## Support

This is a passion project, not a profit project! If you'd like to buy me a coffee:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/ryandeering)

## Licensing

The source code is distributed under the GNU General Public License version 2
or (at your option) any later version (GPLv2+).

The assets (campaigns, graphical and audio assets, etc.) in the `Data` folder
are distributed under the Creative Commons Attribution - Share Alike license,
some in version 3.0 Unported (CC-BY-SA 3.0) and others in version 4.0
International (CC-BY-SA 4.0) as described in the `CONTENT-LICENSE.txt` file.
