<div align="center">

# [Download v1.7.1](https://www.mediafire.com/file/fohvr50m4yek68w/TP_Items_v1.7.1.mcpack/file#)
Join my [Discord Server](https://discord.gg/bs66cpWkqf) for Support & Updates

---

# Teleportation Items and Warp Commands
  This is a behavior pack that adds new **custom commands**. Like one to teleport you to "Spawn" or GameArenas that the world operators have marked with custom entities, a command to teleport yourself to your respawn point. There is as well a **TP Menu** *(teleportation menu)*, that allows you to send tp requests to other players asking them if you are allowed to teleport to them. *(tpr - tpa system)*

---

# Experimental Toggles
  | | |
  | :--- | :---: |
  | **Holiday Creator Features** | [<img src="https://user-images.githubusercontent.com/115075789/207722874-c9c3b1d5-8ee3-428f-95a9-564a5bd21361.png" width="75">]() |
  | **Custom Biomes** | [<img src="https://user-images.githubusercontent.com/115075789/207723014-b09cdef4-b687-42e0-a371-6632e93f5458.png" width="75">]() |
  | **Upcoming Creator Features** | [<img src="https://user-images.githubusercontent.com/115075789/207723014-b09cdef4-b687-42e0-a371-6632e93f5458.png" width="75">]() |
  | **Beta APIs** | [<img src="https://user-images.githubusercontent.com/115075789/207722874-c9c3b1d5-8ee3-428f-95a9-564a5bd21361.png" width="75">]() |
  | **MoLang Features** | [<img src="https://user-images.githubusercontent.com/115075789/207723014-b09cdef4-b687-42e0-a371-6632e93f5458.png" width="75">]() |

# Custom Commands Information
  | **Command** | **Description** |
  | :---: | :--- |
  | `tpi.item` | Gives you the TP Menu used for sending and receiving tp requests to and from other players online |
  | `tpi.bed` | Teleports you to your respawn point |
  | `tpi.spawn` | Teleports you to the location that has been set as the "Spawn" by world operators using an entity marker |
  | `tpi.games` | Teleports you to the location that is used for MiniGames, set by world operators using an entity marker |

  Commands have a cooldown of 3 seconds by default. Can change that in the Config File

# Marking down "Spawn" and MineGames location
  | Marker | How to place marker |
  | :---: | :---: |
  | "Spawn" | `/summon tpi:spawn <position: x y z>` |
  | MiniGames | `/summon tpi:games <position: x y z>` |

# TP Menu Information
  [<img src="https://user-images.githubusercontent.com/115075789/206479917-fc91efd8-29a1-4b46-8d55-50cf3c7aef93.png" width="500">]()

  To make the TP Menu UI appear, you right-click/use the **TP Menu** item. You will be greeted with 3 options:

### Send out a TP Request
  Allows you to select a specific player that is online at the moment and send them a request so you can teleport to them.

### Your outgoing request
  Here will appear the TP Request that you have send to an other player. You can have only one outgoing request at a time. Since having multiple doesn't have any use, you can only be at one location at a time. And like that preventing players from sending requests to eveyone oline.

### Manage incoming requests
  Here go the TP requests that other players send to you, you can chose which to deny and to accept. When accepted, that player will teleport to you.

# Config File
  If you want to change the cooldown time or disable it completely or if you want to change the `tpi.` prefix to something else! However you will have to change that manually inside the pack folder. `/TP Items/scripts/config.js`
 
</div align>
