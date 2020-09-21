# LeeesNC
[![Download](https://img.shields.io/github/downloads/blockparole/LeeesNC/latest/total.svg?label=download%20latest&style=popout-square)](https://github.com/blockparole/LeeesNC/releases/latest)
[![RepoSize](https://img.shields.io/github/languages/code-size/blockparole/LeeesNC.svg?label=repo%20size&style=popout-square)](https://github.com/blockparole/LeeesNC)
[![HitCount](http://hits.dwyl.com/blockparole/LeeesNC.svg)](https://github.com/blockparole/LeeesNC)

A Minecraft Plugin that changes a Players name color on their command.  

![screenshot](https://i.imgur.com/JrDYh5H.png)

Usage: `/nc <color modifier + any amount of format modifiers>`  
Example: `/nc ITALIC dark-red STRIKETHROUGH magic underline BOLD`  

|Colors         |Format          |
|---------------|----------------|
|`AQUA`         |`BOLD`          |
|`BLACK`        |`ITALIC`        |
|`BLUE`         |`MAGIC`         |
|`DARK_AQUA`    |`STRIKETHROUGH` |
|`DARK_BLUE`    |`UNDERLINE`     |
|`DARK_GRAY`    |                |
|`DARK_GREEN`   |                |
|`DARK_PURPLE`  |                |
|`DARK_RED`     |                |
|`GOLD`         |                |
|`GRAY`         |                |
|`GREEN`        |                |
|`LIGHT_PURPLE` |                |
|`RED`          |                |
|`WHITE`        |                |
|`YELLOW`       |                |

Player name format is saved in the config file via UUID:
```
command-needs-permission: false
modifier-allowed-bold: true
modifier-allowed-strikethrough: false
modifier-allowed-underline: false
modifier-allowed-italic: true
modifier-allowed-magic: false
9fb22b27-5fda-48ed-8a5a-ad6e1ff30d71: §2§l
```======
Spigot name colour plugin for anarchy servers
Please join my discord http://discord.6b6t.org and ask me before you make your own version or if you need help
