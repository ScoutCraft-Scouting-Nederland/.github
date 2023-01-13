<a name="readme-top"></a>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/ScoutCraft-Scouting-Nederland/">
    <img src="https://raw.githubusercontent.com/ScoutCraft-Scouting-Nederland/.github/b233df2dd658fc315d87842a1b1667a26b1be5a5/profile/images/logo.png" alt="Logo" width="160" height="80">
  </a>

<h3 align="center">ScoutCraft</h3>

  <p align="center">
    Overview repository for open source resources created by ScoutCraft
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project
ScoutCraft was, during Corona, the place for Dutch Scouts to meet each other and make new friends. On the Minecraft server and in the Discord community about 5000 scouts spent over 150.000 hours. As the projects stops, after exactly 3 years, on 28 april 2023, we decided to make a lot of our resources available, as is. This file is an overview of what we have available and links to all our different repositories.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Maintenance
As the ScoutCraft project has officially ended, we don't update our resources anymore on regular basis. That said, we do monitor the repositories and are open for PR's and issues. If an issue is critical, we will look into a solution. If you want to do more development and change the plugins, you need to make a fork. As we use this as an archive. We will mention forks with great improvements, such as new features, new maps, etcetera. If you think your fork should be mentioned, send us an email!
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Our resources
In the last 3 years, we made a lot of resources for Minecraft servers, such as: plugins and minigames with maps, configs for lots of different plugins and Discord bots. We split it up in a few repositories. All our plugin's and minigames have there own repository, our configs are bundled in one repository, our maps are also bundled in one repository. Our worlds are distributed externally. See the category for more information.

### Plugins
All our self made plugins have their own repository. Here you can find all the information you need to run this plugins on there own. Our best or most useful plugins have a easy to run version which is almost drag and drop. Most of our minigames also have a maps, which you can find in the maps repository. The following plugins are available.

- PillowFight
- Levend Statego
- Werewolves
- Eagle
- Geocache
- Hangman
- PresentHunt
- Lodge

### Servers
We made many servers with lots of configs for plugins and server software. For most of our servers, you can find the files we used to setup here. Most of this configs were updated and fine tuned while monitored in production for months or even years. So you can be sure they are well-tested. You can download the servers as a zip file externally. Per server is explained whats comes with your download. All downloads have a `TODO.txt` file in the zip. Here you can find what you have to change to run them on your own system.

Some of our servers come without a map, because the map was to big or we thought it would be better to start the server with a new world. All the maps are also downloadable.

#### Proxy
As proxy we used a waterfall server which made it possible to connect all our servers. 

#### Survival

<details>
  <summary>Read more</summary>

In this package
- Startup command
- server.properties
- Configs
 - Bukkit
 - Spigot
 - Paper
 - Airplane
 - Pufferfish
 - Purpur
- Plugins
  - CoreProtect
  - EagleServer
  - Essentials
  - InventoryRollback
  - LuckPerms
  - LWC
  - OpenInv
  - Quests
  - Spartan
  - Towny
  - WarpCrystals
  - WorldEdit
  - WorldGuard

</details>

#### Creative

Our PlotSquared Creative server has lots of things players want from a creative server, while it keeps efficient and save. It has support for: FastAsyncWorldEdit, Rollback, HeadDatabase, ArmorStandTools and lots more.
<details>
  <summary>Read more</summary>

In this package
- Startup command
- server.properties
- Configs
 - Bukkit
 - Spigot
 - Paper
 - Airplane
 - Pufferfish
 - Purpur
- Plugins
  - AntiRedstoneClock
  - ArmorStandTool
  - BanItem
  - CoreProtect
  - EagleServer
  - Essentials
  - FastAsyncWorldEdit
  - HeadDatabase
  - PlotSquared

</details>

#### SkyBlock
Our Skyblock server runs on IridiumSkyblock. The server is not perfect, but has a fun system of upgrading your island. Next to this we kept it efficient for admins and moderators with CoreProtect, Rollback and FarmControl.
<details>
  <summary>Read more</summary>

In this package
- Startup command
- server.properties
- Configs
 - Bukkit
 - Spigot
 - Paper
- Plugins
  - Citizens
  - CoreProtect
  - EagleServer
  - Essentials
  - FarmControl
  - FastAsyncWorldEdit
  - InventoryRollback
  - IridiumSkyblock
  - LuckPerms
  - OpenInv

</details>

#### Lobbies
Our lobbies are small, fast and with a few fun minigames. It has support for: NPC server selectors, Holographs, Hangman, hiding players and a seeking game. It is possible to use multiple lobbies and load balance your players. We used up to three. 
<details>
  <summary>Read more</summary>

In this package
- Startup command
- server.properties
- Configs
 - Bukkit
 - Spigot
 - Paper
 - Airplane
 - Pufferfish
 - Purpur
- Plugins
  - ArmorStandTools
  - Citizens
  - EagleServer
  - Hangman
  - Lodge
  - LuckPerms

</details>

#### Minigames
##### PillowFight
Pillow Fight is a minigame where you have to punch other players of platforms. It is fun with 2 - 16 players. Pillow Fight has support for multiple maps, solo/duo/teams mode, power-ups and statistics. It runs with SlimeWorldManager support which makes map loading blazing fast. In this package you find everything you need to run it on your own. We also have the source code for the plugin available and have over 10 self-build maps to use!

<details>
  <summary>Read more</summary>

In this package
- Startup command
- server.properties
- Configs
 - Bukkit
 - Spigot
 - Paper
 - Airplane
 - Pufferfish
 - Purpur
- Plugins
  - EagleServer
  - Luckperms
  - PillowFight
  - SlimeWorldManager

</details>

##### Levend Statego
Levend Stratego is a minigame based on the real-life game Levend Stratego, which is based on the Dutch board game Stratego. In the game teams have to search for the flag of the other team and bring the flag to their own base. The game has support to hide your own flag, for choosing your next roll after you died.
In this package you find everything you need to run it on your own. We also have the source code for the plugin available and have 2 maps to use.
<details>
  <summary>Read more</summary>

In this package
- Startup command
- server.properties
- Configs
 - Bukkit
 - Spigot
 - Paper
 - Airplane
 - Pufferfish
 - Purpur
- Plugins
  - EagleServer
  - LevendStratego
  - Luckperms
  - SlimeWorldManager

</details>

### Maps
For all of our own minigames, and some downloaded minigames, we made our own maps. In this repository you can find all the beautiful maps made by the builders of ScoutCraft.

#### Lobbies
- Lobby 1
- Lobby 2
    - Christmas edition 
- Lobby 3
    - Christmas edition

#### PillowFight (PF)
- PF lobby
- Star Wars
- Star Wars 2
- Tertis
- Tetris 2
- Balooza
- Onrust
- Steampunk
- Planetarium
- Doomsday
- Racetrack
- Treehouse
- Shipyard
- The Pirate Bay

#### Levend Stratego (LS)
- LS Lobby
- Mystico
- VOC

#### Werewolves (WW)
- Werewolves

#### Quests
- Quests

### Worlds
Some worlds of our survival and creative servers are published externally. There are only interesting for players of ScoutCraft looking for what they build. The maps are tens of gigabytes in size, so be aware of this.
- Survival 1
- Survival 2
- Survival 3
- Creative

### Other
We made some software outside of Minecraft. A Discord bot for example. You can find this here:
- Scotty
- Scotty Music

<!-- ROADMAP -->
## Roadmap

- [ ] Plugins
- [ ] Configs
- [ ] Maps
- [ ] Worlds (via External link)
- [ ] Other

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

All the software, such as plugins and maps, is made available under the MIT License. The documents are available under CC-BY-SA-4.0. See `LICENSE.txt` in the repository for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Timo Klabbers - timo.klabbers@scouting.nl </br>
Franck van Velzen - Franck.van.velzen@scouting.nl

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png