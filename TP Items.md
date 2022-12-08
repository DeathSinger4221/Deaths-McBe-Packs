<div align="center">

### [Download Version 1.4.0](https://www.mediafire.com/file/csl5vvvlxevt0wf/TP_Items_v1.4.mcpack/file#)
# Teleportation Items and Warp Commands
  This is a behavior pack that adds some new custom commands. One to mark down the "Spawn" where you build your server builds and an other one that teleports you to the "Spawn", and an other command to teleport your self back to your respawn point. There is as well a TP Menu *(teleportation menu)*, that allows you to send tp requests to other players asking them if you are allowed to teleport to them. *(tpr - tpa system)*
 
# Experimental Toggles
  <img src="https://user-images.githubusercontent.com/115075789/206471420-eefcbf8d-8a34-48b0-a613-ac9baa4d9966.png" width="700">

# Custom Commands Information
  | **Command** | **Description** |
  | :---: | --- |
  | `tpi.item` | Gives you the TP Menu used for sending and recieving TP Requests to and from other players online |
  | `tpi.bed` | Teleports you to your respawn point by using end portals |
  | `tpi.spawn` | Teleports you to the location that has been set as the "Spawn" by world operators using `tpi.set_spawn` |
  | `tpi.set_spawn` | **[Operators Only]** Use to set the location for `tpi.spawn` to teleport to |

# Warning
  When using the `tpi.bed` command for the first time, it will __teleport to the void and fail__. Because it can't run `/setblock` in unloaded chunks. To successfully set the bed warp system up. Teleport to the end dimension using `/execute as @s in minecraft:the_end run tp @s 0 5 0` and then run the `tpi.bed` command, you should see an end_portal block appear at 0 1 0 and bedrock at 0 0 0. If this happens, the bed warp has been set up.

# TP Menu Information
  <img src="https://user-images.githubusercontent.com/115075789/206479917-fc91efd8-29a1-4b46-8d55-50cf3c7aef93.png" width="500">

  To make the TP Menu UI appear, you right-click/use the TP Menu item. You will be greeted with 3 options:

### Send out a TP Request:
  Allows you to select a specific player that is online at the moment and send them a request so you can teleport to them.

### Your outgoing request:
  Here will appear the TP Request that you have send to an other player. You can have only one outgoing request at a time. Since have multiple doesn't have any use, you can only be at one location at a time. And like that others can't spam you with tp requests as easily.

### Manage incoming requests:
  Here go the TP requests that other players send to you, you can chose which to deny and to accept. When accepted, that player will teleport to you.

</div align>
