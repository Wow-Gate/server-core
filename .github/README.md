# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore

[![CodeFactor](https://www.codefactor.io/repository/github/azerothcore/azerothcore-wotlk/badge)](https://www.codefactor.io/repository/github/azerothcore/azerothcore-wotlk)
[![core-build](https://github.com/azerothcore/azerothcore-wotlk/workflows/core-build/badge.svg?branch=master&event=push)](https://github.com/azerothcore/azerothcore-wotlk/actions?query=workflow%3Acore-build+branch%3Amaster+event%3Apush)
[![core-modules-build](https://github.com/azerothcore/azerothcore-wotlk/workflows/core-modules-build/badge.svg?branch=master&event=push)](https://github.com/azerothcore/azerothcore-wotlk/actions?query=workflow%3Acore-modules-build+branch%3Amaster+event%3Apush)
[![windows-build](https://github.com/azerothcore/azerothcore-wotlk/workflows/windows-build/badge.svg?branch=master&event=push)](https://github.com/azerothcore/azerothcore-wotlk/actions?query=workflow%3Awindows-build+branch%3Amaster+event%3Apush)
[![macos-build](https://github.com/azerothcore/azerothcore-wotlk/workflows/macos-build/badge.svg?branch=master&event=push)](https://github.com/azerothcore/azerothcore-wotlk/actions?query=workflow%3Amacos-build+branch%3Amaster+event%3Apush)
[![docker-build](https://github.com/azerothcore/azerothcore-wotlk/workflows/docker-build/badge.svg?branch=master&event=push)](https://github.com/azerothcore/azerothcore-wotlk/actions?query=workflow%3Adocker-build+branch%3Amaster+event%3Apush)
[![Bountysource](https://www.bountysource.com/badge/tracker?tracker_id=40032087)](https://www.bountysource.com/teams/azerothcore/bounties "Put money on issues or get paid for fixing them")
[![StackOverflow](http://img.shields.io/badge/stackoverflow-azerothcore-blue.svg)](https://stackoverflow.com/questions/tagged/azerothcore?sort=newest "Ask / browse questions here")
[![Discord](https://img.shields.io/discord/217589275766685707.svg)](https://discord.gg/gkt4y2x "Our community hub on Discord")


## Introduction

AzerothCore (AC) is an open-source game-server application for World of Warcraft, currently supporting the 3.3.5a game version.

It is written in C++ and is based on MaNGOS, TrinityCore and SunwellCore.


## Why AzerothCore?

1. Stability
1. The authenticity of the content
1. [Modularity](https://en.wikipedia.org/wiki/Modular_programming)
1. A lot of modules to choose from
1. Better configuration files system
1. Compatibility with other emulators
1. Friendly and helpful community
 
## Requirements

Docker
For GNU/Linux, install ([docker](https://docs.docker.com/install/linux/docker-ce/ubuntu))

For macOS 10.12+ Sierra and newer, install ([Docker Desktop for Mac](https://hub.docker.com/editions/community/docker-ce-desktop-mac))

For Windows 10, install ([Docker Desktop for](https://hub.docker.com/editions/community/docker-ce-desktop-windows))

Before proceeding, make sure that docker has docker compose installed on your system by typing in a terminal:

```bash

# To see the docker version
docker --version

# To see the version of docker compose
docker compose version

# You should see similar output:
Docker version 20.10.5, build 55c4c88
Docker Compose version 2.10.2
```

## Clone the server-core repository

```bash

git clone https://github.com/Wow-Gate/server-core.git

```

## Running the root folder

```bash
# Compile AzerothCore
./acore.sh docker build

# Download customer data
./acore.sh docker client-data

# Run the containers
./acore.sh docker start:app:d
```
 
## Stay in touch

- Author - [Wesley Campana Ferreira](https://www.linkedin.com/in/wesley-campana-ferreira-081b55152)
- Website - [Portfolio](https://cyber-portfolio.netlify.app/)

## License

- The new AzerothCore source components are released under the [GNU AGPL v3](https://github.com/azerothcore/azerothcore-wotlk/blob/master/LICENSE-AGPL3)
- The old sources based on MaNGOS/TrinityCore are released under the [GNU GPL v2](https://github.com/azerothcore/azerothcore-wotlk/blob/master/LICENSE-GPL2)
