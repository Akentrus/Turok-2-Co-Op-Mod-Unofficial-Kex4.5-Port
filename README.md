# Turok 2 Remaster Co-Op Mod Unofficial Kex4.5 Port

**Original By:** BehemothProgrammer  
**Ported By:** Akentrus

The original base README has also been made by BehemothProgrammer i just changed a few things as this version does not offer a dedicated server. (yet?)

> **NOTE:** Any bugs found in this version should NOT be reported to the original mod pages and author as they might've been introduced by me.  
>
> I've gotten the okay from the original mod author to port this mod but he still recommends to stick with the kex3 version as this is proven to be more stable  
>
> If something breaks the original author should not be held responsible.

---

## How To Start

1. Download and copy the `mods` folder to your Turok 2 - Seeds of Evil directory.

   **IMPORTANT:**
   
   Please remove any other mods (`.kpf` files) in your `Turok 2 - Seeds of Evil/mods` folder. If you have any others mods this coop mod will not work correctly including older versions of this mod.

2. Again, make sure you copied the mod folder to the correct location. Should be like this:

   ```text
   Turok 2 - Seeds of Evil\mods\COOP\
   ```

3. Start the game and select *Play Co-Op Game* from the main menu.
4. Create a new Lobby.
5. Set the Game Mode to "Raptor Fest".
6. Set the Time Limit to "No Limit".
7. Set the Frag Limit to "No Limit".
8. Start the Game!
9. Remember you can use console commands to adjust the in game options at any time. Read below for the full list.

---

## How to save/load your game

To save your game the host must exit back to the title screen and click the save game menu option and make a save there.

To load your game the one who saved has to click load co op game in the main menu once you loaded the game you will be put back to the title screen from there just start a lobby on any map and you will be teleported to the last map you were on when you saved your game after a few seconds.

---

## Console Commands

> **Commands have not yet been verified for the kex 4.5 engine**

When in game Open the console (with the `~` key) and type `call help` (no quotes) for a list of all console commands.

If you're using the Dedicated Server App type in the console tab window instead.

### Server Cheat Commands

| Command | Description |
|---|---|
| `call slap0 .. 15` | Slaps a player with id. Type playeridx to find the player id to slap |
| `call grav0 .. 100` | Sets gravity. Default value 60 |
| `call speed0 .. 100` | Sets player speed. Default value 50 |
| `call dmg0 .. 100` | Sets the damage scale that players deal out. Default value 10 |
| `call def0 .. 100` | Sets how much scaled damage players will receive. Default value 10 |
| `call jump` | Toggles Double Jump ability. Jump again while in the air |
| `call dash` | Toggles Ground Dash ability. Double tap move direction |
| `call airdash` | Toggles Air Dash ability. Double tap move direction |
| `call slam` | Toggles Ground Slam ability. Press Crouch when high in the air |
| `call tiny` | Toggles enemy tiny mode |
| `call fweapons` | Toggles players fast weapon animations |
| `call ammo` | Toggles unlimited ammo |
| `call weapons` | Gives all SP weapons to all players |
| `call weaponsmp` | Gives all MP weapons to all players |
| `call items` | Gives all inventory items to all players |
| `call missions` | All mission objectives become complete |
| `call secrets` | All secrets become found |
| `call stations` | Unlocks all Checkpoint Station Warps |
| `call noclip` | Toggles noclip for all players |
| `call noclipid0 .. 15` | Toggles noclip for a player with id. Type playeridx to find the player id |
| `call god` | Toggles god mode for all players. Death pits and poison water still kills. |
| `call lives` | Toggles infinite lives |
| `call lives1 .. 10` | Gives extra lives |
| `call spawnai` | Spawns a random ai enemy at your position |

### Server Commands

| Command | Description |
|---|---|
| `call dif0 .. 4` | 0 = Easy, 1 = Normal, 2 = Hard, 3 = Hardcore, 4 = Ultra Hardcore |
| `call bleedout` | Toggles the ability to revive players until they bleedout |
| `call backpack` | Toggles ammo packs will drop when a player dies that contain 20% of the players ammo |
| `call aivanish` | Toggles AI from vanishing shortly after dying |
| `call showdamage` | Toggles damage number popups |
| `call cloak` | Toggles players cloaking |
| `call leader0 .. 15` | Sets a player with id as the party leader. Type playeridx to find the player id |
| `call noleader` | Make it so there is no party leader |
| `call autosave` | Toggle dedicated server auto saving |
| `call restart` | Restarts the current map as you entered it |
| `call newgame` | Start a new game when the next map begins |

### Commands For Everyone

| Command | Description |
|---|---|
| `call xray` | Toggles the X-Ray effect around all players through walls as far as the camera's far clip plane |
| `call showmods` | Displays a list of the current servers mod settings |
| `call stats` | Displays current game progress. Keys obtained, Mission Objectives, Lives |

---

## Known Issues

When starting a lobby and later exiting the game you will get an error popup about GC not being able to see the player reference this has to do with the engine update and is currently not fixable on the mods side simply click "Ok" it won't affect anything in the game besides being annoying.

Please note that this error was not in the original mod for Kex 3.0.

---

## Community Links

- **Original Mod Link on moddb:** https://www.moddb.com/mods/turok-2-co-op-mod
- **Original Mod Link on Turok Forum:** https://www.turokforums.com/index.php?topic=611.msg11712#msg11712
- **Discord Turok Server:** https://discordapp.com/invite/C4JPu4B

---

## Special Thanks (From the original mod)

| Name | Contributions |
|---|---|
| Dima Chotin | supporter, Title art, German Localization |
| Badger | supporter, tester, Death Marsh Swamp |
| SixtyFour | tester, Fossil Cavern Map, B464 Map, Cradle To Grave Map |
| dc.all | supporter |
| Dinomite | supporter |
| Joshua Manrique | supporter |
| Coyote Knight | supporter |
| Zaxiade | Alt PC Song - Adon's Theme Dubstep Remix |
| threefeetlow | Alt PC Song - Main Theme HD Remix |
| SigillumSanguis | Alt PC Song - Port of Adia Metal Cover, River of Souls Metal Cover, Primagen's Lightship Metal Cover |
| Matthew Beckham | Alt PC Song - Hub Theme - Metal Cover |
| The Bellevue Youth Symphony Orchestra | Alt PC Song - Death Marshes |

