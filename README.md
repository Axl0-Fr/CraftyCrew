# CraftyCrew
A cool way to play on small servers with friends!


CraftyCrew started as a small project to host a Minecraft server on a Raspberry Pi to play with friends. Then I installed some clientside mods, then some server side. Then some of both. Keep in mind that you need to download the `CraftyCrew - Server` files to host a server. 

![CraftyCrew Title](https://cdn.modrinth.com/data/cached_images/91102c7ae79fdc3e1213f3c4f562af0b42c00e3f.png)

CraftyCrew is a modpack adding some simple but practical new mechanics to the game. 

### Everything works together! Examples: 

Server with the modpack, somebody playing with _High_, somebody _Potato_, somebody _Vanilla_... everything still works! you've just got to have **A** verion of the modpack to play on a server with the modpack. Absolutelyt no need to all be on th esame version! 
I did that so I could play with my friends without worrying about them not having a good enough PC to play.

_If you experience bugs and get kicked out of the server while typing in chat, try disabling the `No Chat Reports` mod. If this doesn't solve your problem, don't hesitate to ask for help on our [Discord](https://discord.gg/UP9e3PW7ZX)._

Versions are made to go together. They are put under the format (v*.*.*)
the first number represents the Minecraft version. The second number Means the Version of the modpack for this minecraft verison (so if server is on 1.1.* then all clients _should be_ on this version, for a better experience. The 3rd number is for small updates. 

# Content
<details>
<summary>A list of the new things added to the game</summary>

## Server
- Clumps: Clumps XP orbs together to reduce lag.
- Double Doors: Multiple identical double doors, trapdoors and fence gates can be opened simultaneously.
- Dynamic Lights: Supported entities and items such as torches or lanterns emit light! Server-side only!
- Fabric Seasons: A simple mod that adds seasons to the game, dynamically changing biomes as you play.
- FSit: Sit anywhere!
- HerdsPanic: Herds just start to panic when a member panics.
- Immersive Snow: Small tweaks that add to Minecraft's Winter theme. Intended for use with a season mod.
- Simple Voice Chat Enhanced Groups: A server side Fabric mod providing useful features to Simple Voice Chat groups.
- Lithium: No-compromises game logic/server optimization mod. 
- No Portals: Disable Nether Portals, End Portals, and End Gateways at your will.
- Nyf's Spiders: Modifes spiders to be more realistic.
- Players Drop Heads: Players drop their heads when killed!
- Realistic Sleep: Makes sleeping speed up time instead of skipping to day.
- Simple Backups: A simple mod to create scheduled backups.
- Skeleton Horse Spawn: Allows skeleton horses to spawn naturally with a skeleton riding it and other tweaks.
- Spawn Animations: Hostile mobs dig out of the ground or poof into existence when they spawn!
- Voice Chat Interaction: Voice chat skulk sensor activation and warden detection.
- Simple Voice Chat: A working voice chat in Minecraft!
## Client
A lot of optimisation mods are not listed here, [go there if you are interested](https://modrinth.com/modpack/fabulously-optimized). 
Keep in mind every version also has the mods listed on the version below. Here is the versions list: 
`Potato > Low > Medium > High > Ultra`
### Potato
- Fresh Animations: Make your game like the trailers! Dynamic animated entities to freshen your Minecraft experience.
- Better Animations: Overhaul your Minecraft player animations and bring them to life!
- Nyf's Spiders: Modifes spiders to be more realistic.
- Fabric Seasons: A simple mod that adds seasons to the game, dynamically changing biomes as you play. (Only visual in multiplayer, the actual game mechanics are server-side)
- Xaero's Minimap: Displays a map of the nearby world terrain, players, mobs, entities in the corner of your screen. Lets you create waypoints which help you find the locations you've marked.
- Xaero's World Map: Adds a full screen world map which shows you what you have explored in the world. Works great together with Xaero's Minimap.
- SeasonHUD: This is an addon for FabricSeasons that displays the current season on the HUD or under the minimap
- Verticality: Verticalize your hotbar! (Configurable in the Esc menu)
- Simple Voice Chat: A working voice chat in Minecraft!
- No Resource Pack Warnings: Disable warnings for outdated resource/data packs.
### Low 
- Mouse Tweaks: Enhances inventory management by adding various functions to the mouse buttons.
- Presence Footsteps: An Overly complicated Sound Mod.
- AppleSkin: Food/hunger-related HUD improvements. 
- Shulker Box Tooltip: View the contents of shulker boxes from your inventory. 
- Sound Physics Remastered: A Minecraft mod that provides realistic sound attenuation, reverberation, and absorption through blocks.
### Medium
- 3D Skin Layers: Render the player skin layer in 3d!
- BetterF3: BetterF3 is a mod that replaces Minecraft's original debug HUD with a highly customizable, more human-readable HUD.
- Fastload: Modifies how worlds are loaded to speed up loading times.
- FPS Reducer: Reduce GPU and CPU usage automatically when no user operation exists.
- InvMove: Forge/Fabric/Quilt mod that adds the ability to walk around while in inventories
- Blur: Adds a blur effect to all GUI backgrounds.
- Charmonium: Ambient and environmental sounds in keeping with vanilla Minecraft.
- Ambient Environment: Adds more ambiance to a Minecraft world. 
- Effective: Client-side mod designed to improve Minecraft's ambience through particles, visual effects and sounds. 
- Nemo's Ambience: Nemo's Ambience aims to make Minecraft feel more alive!
- Reacharound: Reacharound block placement.
- Visuality: Little visual improvements by adding a bunch of new particles.
### High 
- Advancement Plaques: Replace those boring advancement popups with something flashier.
- Auto HUD: A mod which dynamically hides parts of the user interface
- Auto Third Person: Automatically put yourself in third-person mode when you perform certain actions. Clientside only! Configurable!
- Cave Dust: Dust is a Minecraft mod that adds the white ash particle from the Basalt Deltas biome to the underground to simulate dust!
- Dynamic Crosshair: A mod that hides or changes the crosshair dependent on context
- Eating Animations: A mod that adds sprite animations for edible and drinkable items.
- Fisrt-person Model: Enables the third-person Model in first-person
- LambdaBetterGrass: A Minecraft mod which adds better grass and snow to the game.
- Legendary Tooltips: Give your rare items a fancier tooltip! Also adds additional tooltip configuration options.
- Make Bubbles Pop: Client-side mod that makes bubble particles pop and lets them rise realistically to the water surface.
- Wakes: Adds splashes and wakes while traveling on water.
### Ultra
- Explosive Enhancements: Makes the explosion animation look cooler.
- A whole lot of chat mods

</details>

<details>
<summary>Server-side Tutorial</summary>

### Setup
  
1. Open your terminal
2. Change your directory to `Files`
3. Type the text that is written in `Launch.txt` 
4. There is a part that says `Xm3G`. Change the number to the quantity of RAM you want to allocate to the server
5. It will tell you to accept the EULA. Do it
6. Redo Step 3 and 4 
Wait until it tells you the serveer is done!

If you want to mess with domain names or anything, I'm really not the guy to ask, you might find some help on the Internet. 

If you are experiencing any issues, don't hesitate to ask for help on [our Discord](https://discord.gg/UP9e3PW7ZX).

</details>

Don't hesitate to join [our Discord](https://discord.com/invite/8vqnCKxrgd) if you are interested in the modpack, want to help, or even just chill with the comunity!

Thanks a lot to [Creatomat](https://modrinth.com/user/Creatomat)  for all his help with [Better Animations](https://modrinth.com/resourcepack/better-animations).
