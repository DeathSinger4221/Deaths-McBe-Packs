<div align="center">

# [Download v1.11.0](https://www.mediafire.com/file/3u41zj7y2s8wr0d/TP_Items_v1.11.0.mcpack/file#)
  `The blue download text is clickable! It's a link.`

  Join my [**Discord Server**](https://discord.gg/bs66cpWkqf) for Support & Updates

  Here a [**YouTube Video**](https://youtu.be/LNbnUohyj9U) on how to use the Pack (OUTDATED)

  Updated on 03.09.2024

---
# Teleportation Items
  [<img src="https://github.com/DeathSinger4221/Deaths-McBe-Packs/blob/main/thumbnails/tpItems.png?raw=true" width="80%">]()\
  This is a behavior pack that adds  a **TP Menu** *(teleportation menu)* that allows you to send tp requests to other players asking them if you are allowed to teleport to them *(tpr - tpa system)*, and adds a **marker system** for world admins to mark down important locations to which anyone can teleport to! Or only other admins.\
  This includes a personal marker everyone has, their respawn poin! (can be disabled)

  `No Experimental Toggles needed!`

  [<img src="https://github.com/user-attachments/assets/2475dc9e-60d3-4236-af89-e48430b2574b" width="40%">](https://www.mediafire.com/file/3u41zj7y2s8wr0d/TP_Items_v1.11.0.mcpack/file#)

---
# Pack Settings for obtaining the TP Menu
  [<img src="https://github.com/user-attachments/assets/c68e266e-c6cc-4fe4-bc30-c66f8f7559f9" width="60%">]()\
  [<img src="https://github.com/user-attachments/assets/66425865-f7a0-42b3-a859-8676135f8d26" width="60%">]()\
  [<img src="https://github.com/user-attachments/assets/f8708593-f8f4-48fc-9925-1e09d5576b77" width="60%">]()
</div align>

---
# TP Menu
  To make the TP Menu UI appear, you right-click/use the **TP Menu** item.\
  *(Can be found in the Equipment Section of the Creative Menu)*

## Features
  * ### Send a TP Request
    You can search for specific players that are online by their Player Name and send them a request for **you** to **teleport to them**!\
    And they can either accept or deny your request.\
    When sending a Tp Request, you will have to stay still for a certain amount of time for them to recieve your request.\
    The waiting time can be configured in [InGame Menu Settings](#ingame-menu-settings).

  * ### Manage your outgoing Request
    You can cancel the request you have sent to an other player anytime before they accept it.

  * ### Manage your incoming Requests
    You can individualy accept or deny any TP Request that comes your way.\
    When acepting, you will have to stay still for a certain amount of time for them to teleport to you.\
    The waiting time can be configured in [InGame Menu Settings](#ingame-menu-settings).

  * ### Teleport to a Marker
    Players that have the `tpiManager` tag, info about it [here](#tpi-manager-tag), can create world **markers that only other players with the tag can teleport to**, or world **markers that everyone can teleport to**.\
    This includes a personal world marker that every player has by default, their respawn point, which is more or less self-explanatory.\
    The presence of this personal marker can be toggled on or off for everyone in [InGame Menu Settings](#ingame-menu-settings).\
    When a player wants to teleport to a marker, they will have to stay still for a certain amount of time for them to teleport to that marker.\
    The waiting time can be configured in [InGame Menu Settings](#ingame-menu-settings).

  * ### TPI Manager Tag
    This is a tag (`tpiManager`) that is given using the command `/tag @s add tpiManager`, this tag gives to a player who has it the ability to configure the [InGame Menu Settings](#ingame-menu-settings) and create, delete and edit world markers.\
    Players with this tag do not need to stay still for any duration of time; their TP Requests and TP Accepts get forwarded immediately, same with the teleportation to a marker.

> [!IMPORTANT]
> The TPI Manager tag is **CASE SESITIVE**, and will not work in any other format.

  * ### TPI Blacklist Tag
    Players with the blacklist tag, are unable to use any feature related to this behaviour pack.\
    They will recieve a message in chat telling them they are blacklisted if they attempt to open the TP Menu.\
    The blacklist tag can be configured in [InGame Menu Settings](#ingame-menu-settings).

## InGame Menu Settings
  When a player has the `tpiManager` tag (CASE SENSITIVE), they recieve an **additional option in the TP Menu**, where they can change the pack's configuration or manage world markers. The Following button is the one that appears when you're a TPI Manager
<div align="center">

  [<img src="https://github.com/user-attachments/assets/7ebdf0be-1e90-4a13-a5d0-6998a8437ff7" width="50%">]()\
  This button leads you to the following GUI:

  [<img src="https://github.com/user-attachments/assets/d1ba749c-7aa8-40f7-b7a2-64f21b2624f7" width="50%">]()\
  Then when you select **Pack Configuration**, you'll get the following aspects you can configure InGame.

  [<img src="https://github.com/user-attachments/assets/a56e8662-a04f-4b92-9332-762486dfb1b6" width="50%">]()

</div align>
