<div align="center">

# [Download v1.5.2](https://www.mediafire.com/file/e269lq4883mla18/TP_Items_v1.5.2.mcpack/file#)
# Teleportation Items and Warp Commands
  This is a behavior pack that adds two new custom commands. One to teleport you to "Spawn" that the world operators have marker with a custom entity, and an other command to teleport your self back to your respawn point. There is as well a <img src="https://user-images.githubusercontent.com/115075789/209723243-ce4783f9-c1ff-4481-ba3f-017430d506bc.png" width="17"> TP Menu *(teleportation menu)*, that allows you to send tp requests to other players asking them if you are allowed to teleport to them. *(tpr - tpa system)*

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
  | `tpi.bed` | Teleports you to your respawn point by using end portals |
  | `tpi.spawn` | Teleports you to the location that has been set as the "Spawn" by world operators using an entity marker |

# Marking down "Spawn" and respawn point warp
  To mark down the location where `tpi.spawn` should teleport to, you have to summon the spawn marker entity using ``/summon tpi:spawn`` on that location. To make `tpi.bed` work. Teleport your self to the end dimension and summon the marker entity using ``/summon tpi:bed`` somewhere in the end, preferably somewhere, where normal players can't access. So secure that location with deny blocks too. 

# TP Menu Information
  [<img src="https://user-images.githubusercontent.com/115075789/206479917-fc91efd8-29a1-4b46-8d55-50cf3c7aef93.png" width="500">]()

  To make the TP Menu UI appear, you right-click/use the <img src="https://user-images.githubusercontent.com/115075789/209723243-ce4783f9-c1ff-4481-ba3f-017430d506bc.png" width="17"> TP Menu item. You will be greeted with 3 options:

### Send out a TP Request
  Allows you to select a specific player that is online at the moment and send them a request so you can teleport to them.

### Your outgoing request
  Here will appear the TP Request that you have send to an other player. You can have only one outgoing request at a time. Since have multiple doesn't have any use, you can only be at one location at a time. And like that others can't spam you with tp requests as easily.

### Manage incoming requests
  Here go the TP requests that other players send to you, you can chose which to deny and to accept. When accepted, that player will teleport to you.

</div align>
