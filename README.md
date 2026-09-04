# Minecraft Paper 1.21 Plugin Ideas

> 60 plugin ideas I want to build to level up.

![Java 21](https://img.shields.io/badge/Java-21-orange)
![Paper 1.21](https://img.shields.io/badge/Paper-1.21-green)
![Status](https://img.shields.io/badge/Status-Planned-blue)

---

## Progress

| # | Plugin | Description | Category | Status |
|---|--------|-------------|----------|--------|
| 1 | Mace Smash FFA | Players get a Mace and Wind Charges. Knock opponents out of the arena or score fall-damage kills. | Minigames & Arenas | `planned` |
| 2 | Wind Charge Parkour Race | A parkour course where players use unlimited Wind Charges to boost across gaps. First to finish wins. | Minigames & Arenas | `planned` |
| 3 | Simple Spleef | Classic spleef with a twist: players get a random power-up (e.g. Speed II) every 30 seconds via config. | Minigames & Arenas | `planned` |
| 4 | 1v1 Duel Arena | A /duel command that teleports two players into an arena, gives them kits, and announces the winner. | Minigames & Arenas | `planned` |
| 5 | Capture the Flag (Lite) | Two teams, two wool colors. Steal the enemy wool and bring it back to your base using simple region checking. | Minigames & Arenas | `planned` |
| 6 | Bow Spleef | Arrows break the blocks they hit. Last player standing wins. Great for practicing projectile events. | Minigames & Arenas | `planned` |
| 7 | Mob Arena Lite | Waves of zombies spawn in a contained arena. Players buy in, and the last one alive gets a reward. | Minigames & Arenas | `planned` |
| 8 | Checkpoint Parkour | A parkour lobby where stepping on a pressure plate saves your location. Fall? Respawn at the last checkpoint. | Minigames & Arenas | `planned` |
| 9 | TNT Run | Classic minigame where blocks disappear 1 second after a player steps on them. Last one standing wins. | Minigames & Arenas | `planned` |
| 10 | Color Match | Chat says "RED!" and players have 5 seconds to stand on red wool. Wrong color = eliminated. | Minigames & Arenas | `planned` |
| 11 | Custom Join/Leave Messages | Replace default messages with configurable, colorful MiniMessage formats (e.g. &e{player} &7has joined!). | QoL & Utility | `planned` |
| 12 | Simple Home System | /sethome and /home with a configurable cooldown and a limit of 1-3 homes per player. | QoL & Utility | `planned` |
| 13 | AFK Kicker & Rewarder | Kick players after X minutes of no movement, OR reward them with $1 for every 10 minutes of being AFK. | QoL & Utility | `planned` |
| 14 | Crafting Table Anywhere | Right-clicking a "Portable Crafter" stick opens a crafting GUI. Never search for a table again. | QoL & Utility | `planned` |
| 15 | Custom Death Messages | Intercept PlayerDeathEvent to show funny or informative messages (e.g. "{player} was smashed by {killer}'s Mace!"). | QoL & Utility | `planned` |
| 16 | Player Heads GUI | /heads opens a GUI to browse and buy player heads using an economy plugin. | QoL & Utility | `planned` |
| 17 | Simple Warp System | /setwarp and /warp for server owners to create fast-travel points, stored in a simple warps.yml. | QoL & Utility | `planned` |
| 18 | Night Vision Toggle | A /nv command that gives or removes Night Vision, perfect for cave explorers. | QoL & Utility | `planned` |
| 19 | Compass Tracker | Right-click a compass to open a GUI of online players. Click a name and the compass points to them. | QoL & Utility | `planned` |
| 20 | Chat Format Manager | Format chat based on permissions (e.g. [Admin] Name: Message) without a heavy chat manager. | QoL & Utility | `planned` |
| 21 | Quick Sell GUI | /quicksell opens a GUI, drop items in, plugin calculates total value from prices.yml and deposits it. | Economy & Shops | `planned` |
| 22 | Custom /pay Command | A secure player-to-player money transfer system with /pay <player> <amount>. | Economy & Shops | `planned` |
| 23 | Daily Login Rewards | A GUI that resets every 24 hours. Day 1 = $100, Day 2 = $200, Day 7 = custom reward. | Economy & Shops | `planned` |
| 24 | Simple Admin Shop | /adminshop opens a GUI where players can buy/sell vanilla items at server-set prices. | Economy & Shops | `planned` |
| 25 | Playtime Rewards | Tracks online time. Every 60 minutes the player receives a configurable reward (money, key, or message). | Economy & Shops | `planned` |
| 26 | Custom Currency Items | Right-click an Emerald "Gold Coin" to add $100 to Vault balance. Shift-right-click to withdraw. | Economy & Shops | `planned` |
| 27 | Auction House Lite | Players list items in a global YAML-based GUI. Others can browse and buy them. Simple, no real-time DB. | Economy & Shops | `planned` |
| 28 | Job System Lite | A listener that pays players for breaking specific blocks (e.g. $1 per Cobblestone). Fully configurable. | Economy & Shops | `planned` |
| 29 | Vote Rewards Listener | Listens for vote events (or a dummy command) and grants a Crate Key as a reward. | Economy & Shops | `planned` |
| 30 | Bank System | /deposit and /withdraw commands. The bank gives 1% interest every real-life day. | Economy & Shops | `planned` |
| 31 | Vampire Sword | Any sword with "Vampire I" in its lore heals the player 1 heart when they damage an entity. | Custom Mechanics | `planned` |
| 32 | Explosive Arrows | Arrows from a bow with "Explosive" lore create a small, non-griefing explosion on impact. | Custom Mechanics | `planned` |
| 33 | Double Jump Boots | Leather boots named "Spring Boots" give Jump Boost II when the player sneaks in mid-air. | Custom Mechanics | `planned` |
| 34 | Custom Crafting Recipes | Use ShapedRecipe to add 2-3 new recipes via config (e.g. 8 Golden Apples = 1 Notch Apple). | Custom Mechanics | `planned` |
| 35 | Lucky Block | Breaking a Sponge has a 50% chance to drop diamonds, and 50% to spawn a hostile mob or bad effect. | Custom Mechanics | `planned` |
| 36 | Custom Mob Drops | A config.yml that lets server owners set a % chance for mobs to drop custom items (e.g. 5% Zombie = Iron Ingot). | Custom Mechanics | `planned` |
| 37 | Throwing Knives | Snowballs that deal 2 hearts of damage and play a "thwack" sound on impact. | Custom Mechanics | `planned` |
| 38 | Speed Boots | Gold boots that permanently apply Speed I to the wearer as long as they are equipped. | Custom Mechanics | `planned` |
| 39 | Custom Food | A configurable "Mystery Stew" that applies a random positive or negative potion effect when eaten. | Custom Mechanics | `planned` |
| 40 | Weapon Abilities | Right-click a "Fire Wand" stick to shoot a small fireball, with a 5-second cooldown via HashMap. | Custom Mechanics | `planned` |
| 41 | Custom World Border | A command to set a world border that slowly shrinks over time, with chat warnings at 500, 200, and 50 blocks. | World & Environment | `planned` |
| 42 | Tree Capacitor (Lite) | Right-click the bottom log of a tree with an axe to break the entire tree (recursive, max 50 blocks). | World & Environment | `planned` |
| 43 | Custom Biome Sounds | Play a custom sound via player.playSound when a player enters a specific biome (e.g. spooky sounds in Dark Forest). | World & Environment | `planned` |
| 44 | Weather Controller | /lockweather sunny or /lockweather rain to prevent the server weather from changing naturally. | World & Environment | `planned` |
| 45 | Simple Mob Stacker | If 3+ of the same mob are within 2 blocks, merge into one mob with multiplied health and a count name tag. | World & Environment | `planned` |
| 46 | Custom Ore Generation | A command that scans a chunk and replaces a % of Stone with a custom "Ruby" ore block. | World & Environment | `planned` |
| 47 | Auto-Replanting | When a player breaks a crop (wheat, carrots), the plugin automatically places the seed back on farmland. | World & Environment | `planned` |
| 48 | Fine-Grained Mob Griefing | Stop Creepers from breaking blocks but allow Endermen to pick up blocks, controlled via config.yml. | World & Environment | `planned` |
| 49 | Custom Sleep | Allow the night to be skipped if only 1 player sleeps (instead of vanilla 50%), with a custom message. | World & Environment | `planned` |
| 50 | Spawn Protection Plus | A custom radius around spawn where PvP is disabled and players get a warning if they try to hit someone. | World & Environment | `planned` |
| 51 | Simple Ban/Kick System | /ban and /kick commands that save to bans.yml and prevent rejoining with a custom message. | Admin & Moderation | `planned` |
| 52 | Staff Chat | /sc <message> lets players with a specific permission talk in a private, color-coded chat channel. | Admin & Moderation | `planned` |
| 53 | Report System | /report <player> <reason> saves the report to reports.yml and notifies online staff. | Admin & Moderation | `planned` |
| 54 | Command Blocker | A config.yml list of blocked commands (e.g. /pl, /bukkit:*, /ic) that normal players cannot use. | Admin & Moderation | `planned` |
| 55 | Join Title & Sound | Display a large, customizable Title/Subtitle and play a sound (e.g. ENTITY_PLAYER_LEVELUP) on join. | Admin & Moderation | `planned` |
| 56 | Inventory See | /invsee <player> opens a GUI showing the target player's exact inventory and armor (read-only). | Admin & Moderation | `planned` |
| 57 | Freeze Command | /freeze <player> prevents the target from moving, jumping, or chatting until an admin unfreezes them. | Admin & Moderation | `planned` |
| 58 | Server Restart Warning | A scheduler that broadcasts a chat message every minute for the last 5 minutes before a restart. | Admin & Moderation | `planned` |
| 59 | Maintenance Mode | /maintenance on kicks all non-staff players and prevents joining, showing a "Server under maintenance" message. | Admin & Moderation | `planned` |
| 60 | Simple Rank GUI | An admin-only GUI to click on a player's head and assign them a permission group (requires Vault/LuckPerms). | Admin & Moderation | `planned` |

## 🗂️ Categories (by Theme)

### 🎮 Minigames & Arenas
> **Focus:** Game Loops, Player Tracking, Teleportation, Inventory Management

| # | Plugin | Description | Focus | Status |
|---|--------|-------------|-------|--------|
| 1 | Mace Smash FFA | Players get a Mace and Wind Charges. Knock opponents out or score fall-damage kills. | PvP, Arena, Item-Giving | `planned` |
| 2 | Wind Charge Parkour Race | Parkour course using unlimited Wind Charges to boost across gaps. First to finish wins. | Race, Timer, Teleport | `planned` |
| 3 | Simple Spleef | Classic spleef with random power-ups every 30 seconds via config. | Block-Break, Potion, Timer | `planned` |
| 4 | 1v1 Duel Arena | /duel teleports two players into an arena, gives kits, announces the winner. | Command, Teleport, Kit | `planned` |
| 5 | Capture the Flag (Lite) | Two teams, two wool colors. Steal the enemy wool and bring it to your base. | Teams, Region, Item-Check | `planned` |
| 6 | Bow Spleef | Arrows break blocks they hit. Last player standing wins. | Projectile, Block-Place, Last-Player | `planned` |
| 7 | Mob Arena Lite | Waves of zombies in a contained arena. Last one alive gets a reward. | Waves, Spawn, Economy | `planned` |
| 8 | Checkpoint Parkour | Pressure plates save your location. Fall? Respawn at the last checkpoint. | Pressure Plate, Location Save, Respawn | `planned` |
| 9 | TNT Run | Blocks disappear 1 second after a player steps on them. Last one standing wins. | Block-Remove, Timer, Last-Player | `planned` |
| 10 | Color Match | Chat says a color, players have 5 seconds to stand on it. Wrong color = eliminated. | Chat, Block-Check, Elimination | `planned` |

### 🛠️ Quality of Life & Utility
> **Focus:** Event Cancellation, Basic Commands, Player Feedback

| # | Plugin | Description | Focus | Status |
|---|--------|-------------|-------|--------|
| 11 | Custom Join/Leave Messages | Configurable, colorful MiniMessage join/leave messages (e.g. &e{player} &7has joined!). | Event, MiniMessage, Config | `planned` |
| 12 | Simple Home System | /sethome and /home with configurable cooldown and 1-3 homes per player. | Command, YAML, Teleport | `planned` |
| 13 | AFK Kicker & Rewarder | Kick after X minutes idle OR reward $1 per 10 minutes AFK. | Scheduler, Move Event, Economy | `planned` |
| 14 | Crafting Table Anywhere | Right-click a "Portable Crafter" stick to open a crafting GUI. | Inventory, Item-Lore, Right-Click | `planned` |
| 15 | Custom Death Messages | Funny or informative death messages via PlayerDeathEvent (e.g. "{player} was smashed by {killer}'s Mace!"). | Event, String Format | `planned` |
| 16 | Player Heads GUI | /heads opens a GUI to browse and buy player heads with economy integration. | GUI, Skulls, Vault | `planned` |
| 17 | Simple Warp System | /setwarp and /warp for fast-travel points stored in warps.yml. | Command, YAML, Teleport | `planned` |
| 18 | Night Vision Toggle | /nv gives or removes Night Vision. Perfect for cave explorers. | Potion, Command, Toggle | `planned` |
| 19 | Compass Tracker | Right-click compass opens GUI of online players. Click a name to track them. | GUI, Compass, Player List | `planned` |
| 20 | Chat Format Manager | Format chat by permissions (e.g. [Admin] Name: Message) without a heavy chat manager. | AsyncChat, Permission, MiniMessage | `planned` |

### 💰 Economy & Shops
> **Focus:** Vault API Integration, GUI Creation, YAML Data Storage

| # | Plugin | Description | Focus | Status |
|---|--------|-------------|-------|--------|
| 21 | Quick Sell GUI | /quicksell opens a GUI, drop items in, get paid based on prices.yml. | GUI, Vault, YAML | `planned` |
| 22 | Custom /pay Command | Secure player-to-player money transfer with /pay <player> <amount>. | Command, Vault, Validation | `planned` |
| 23 | Daily Login Rewards | GUI that resets every 24h. Day 1 = $100, Day 2 = $200, Day 7 = custom reward. | GUI, Scheduler, Data | `planned` |
| 24 | Simple Admin Shop | /adminshop opens a GUI to buy/sell vanilla items at server-set prices. | GUI, Config, Vault | `planned` |
| 25 | Playtime Rewards | Tracks online time. Every 60 minutes a configurable reward (money, key, message). | Scheduler, Data, Vault | `planned` |
| 26 | Custom Currency Items | Right-click a "Gold Coin" emerald to add $100 to Vault. Shift-right-click to withdraw. | Item-Name, Vault, Right-Click | `planned` |
| 27 | Auction House Lite | List items in a global YAML GUI. Others browse and buy. Simple, no real-time DB. | GUI, YAML, Vault | `planned` |
| 28 | Job System Lite | Listener pays players for breaking specific blocks (e.g. $1 per Cobblestone). | Event, Config, Vault | `planned` |
| 29 | Vote Rewards Listener | Listens for vote events and grants a Crate Key as reward. | Event, Reward, Config | `planned` |
| 30 | Bank System | /deposit and /withdraw. Bank gives 1% interest every real-life day. | Command, YAML, Scheduler | `planned` |

### ⚔️ Custom Mechanics & Items
> **Focus:** Item Lore Checking, Basic Cooldowns, Potion Effects

| # | Plugin | Description | Focus | Status |
|---|--------|-------------|-------|--------|
| 31 | Vampire Sword | Sword with "Vampire I" lore heals 1 heart on damage dealt. | Lore-Check, Damage-Event, Heal | `planned` |
| 32 | Explosive Arrows | "Explosive" bow lore creates a small, non-griefing explosion on arrow impact. | Projectile, Lore-Check, Explosion | `planned` |
| 33 | Double Jump Boots | "Spring Boots" leather boots give Jump Boost II when sneaking mid-air. | Sneak, Potion, Item-Check | `planned` |
| 34 | Custom Crafting Recipes | ShapedRecipe adds new recipes via config (e.g. 8 Golden Apples = 1 Notch Apple). | ShapedRecipe, Config, Crafting | `planned` |
| 35 | Lucky Block | Breaking Sponge: 50% diamonds, 50% hostile mob or bad potion effect. | Block-Break, Random, Mob-Spawn | `planned` |
| 36 | Custom Mob Drops | Config.yml for % chance of mobs dropping custom items (e.g. 5% Zombie = Iron Ingot). | Entity-Death, Config, Loot | `planned` |
| 37 | Throwing Knives | Snowballs deal 2 hearts damage and play a "thwack" sound on hit. | Projectile, Damage, Sound | `planned` |
| 38 | Speed Boots | Gold boots that permanently apply Speed I while equipped. | Equip, Potion, Armor | `planned` |
| 39 | Custom Food | "Mystery Stew" applies a random positive or negative potion effect when eaten. | Food, Potion, Random | `planned` |
| 40 | Weapon Abilities | Right-click "Fire Wand" stick to shoot a fireball with a 5s cooldown via HashMap. | Right-Click, Cooldown, Fireball | `planned` |

### 🌍 World & Environment
> **Focus:** Block Manipulation, World Events, Simple Recursion

| # | Plugin | Description | Focus | Status |
|---|--------|-------------|-------|--------|
| 41 | Custom World Border | Set a shrinking world border with chat warnings at 500, 200, and 50 blocks. | WorldBorder, Scheduler, Chat | `planned` |
| 42 | Tree Capacitor (Lite) | Right-click bottom log with axe to break the entire tree (recursive, max 50 blocks). | Right-Click, Recursion, Block-Break | `planned` |
| 43 | Custom Biome Sounds | Play custom sounds when entering a biome (e.g. spooky sounds in Dark Forest). | Biome-Check, Sound, Move | `planned` |
| 44 | Weather Controller | /lockweather sunny or rain to prevent natural weather changes. | Weather, Command, Scheduler | `planned` |
| 45 | Simple Mob Stacker | 3+ same mobs within 2 blocks merge into one with multiplied health and count tag. | Entity, Nearby-Check, Merge | `planned` |
| 46 | Custom Ore Generation | Scan a chunk and replace a % of Stone with a custom "Ruby" ore block. | Chunk, Block-Replace, Custom Block | `planned` |
| 47 | Auto-Replanting | Break a crop and the plugin automatically places the seed back on farmland. | Block-Break, Block-Place, Crop | `planned` |
| 48 | Fine-Grained Mob Griefing | Stop Creepers breaking blocks but allow Endermen to pick up blocks, via config.yml. | Entity-Explode, Config, Toggle | `planned` |
| 49 | Custom Sleep | Night skips if only 1 player sleeps (instead of vanilla 50%) with custom message. | Bed, Time, Config | `planned` |
| 50 | Spawn Protection Plus | Radius around spawn where PvP is disabled with a warning message on hit attempt. | Region, PvP, Warning | `planned` |

### 🛡️ Admin, Moderation & Management
> **Focus:** Permissions, YAML Storage, Staff Utilities

| # | Plugin | Description | Focus | Status |
|---|--------|-------------|-------|--------|
| 51 | Simple Ban/Kick System | /ban and /kick save to bans.yml, prevent rejoining with a custom message. | Command, YAML, AsyncPlayerPreLogin | `planned` |
| 52 | Staff Chat | /sc lets permissioned players talk in a private, color-coded staff channel. | Command, Permission, Chat | `planned` |
| 53 | Report System | /report saves to reports.yml and notifies online staff members. | Command, YAML, Notification | `planned` |
| 54 | Command Blocker | Config.yml list of blocked commands (e.g. /pl, /bukkit:*) for normal players. | Command, Config, Permission | `planned` |
| 55 | Join Title & Sound | Customizable Title/Subtitle and sound (ENTITY_PLAYER_LEVELUP) on player join. | Title, Sound, Join | `planned` |
| 56 | Inventory See | /invsee opens a read-only GUI showing a player's inventory and armor. | GUI, Inventory, Read-Only | `planned` |
| 57 | Freeze Command | /freeze prevents target from moving, jumping, or chatting until unfrozen. | Command, Move-Cancel, Chat-Cancel | `planned` |
| 58 | Server Restart Warning | Broadcasts a chat message every minute for 5 minutes before a scheduled restart. | Scheduler, Chat, Countdown | `planned` |
| 59 | Maintenance Mode | /maintenance kicks non-staff and blocks joins with a "Server under maintenance" message. | Command, Kick, Join-Cancel | `planned` |
| 60 | Simple Rank GUI | Admin-only GUI to click player heads and assign permission groups (Vault/LuckPerms). | GUI, LuckPerms, Permission | `planned` |

---

## Tech Stack

- **Java 21**
- **Paper API 1.21**
- **MiniMessage** (for chat formatting)
- **Vault** (for economy integration)
- **YAML** (for data storage)

---

> Status key: `planned` `in-progress` `done`
