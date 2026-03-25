# 🖍️ Crayon Casino Bot - Complete Command Reference

Welcome to the Crayon Casino Bot! This bot offers a wide variety of commands for gaming, gambling, utility, and entertainment. All commands use the prefix `?`.

## 🎮 Casino & Gambling Commands

### 🎰 Slot Machine Games
- **?slots** - Play the slot machine with emotes
- **?blackjack** (aliases: `?bj`) - Play blackjack against the dealer
- **?hit** (aliases: `?hitme`) - Hit in blackjack (draw another card)
- **?stand** (aliases: `?stay`) - Stand in blackjack (keep current hand)
- **?bjall** (aliases: `?blackjackall`, `?allin`, `?yolo`) - Go all-in on blackjack
- **?plinko** - Play plinko game with multipliers
- **?plinkoboard** - Show plinko board layout and multipliers
- **?roulette** - Play roulette with betting options
- **?gamble** - Gamble crayons with custom chance
- **?ghelp** - Show gambling help and rules

### 🎣 Pool Fishing Game
- **?pool** (aliases: `?pull`) - Fish for emotes from the pool
- **?poolinfo** (aliases: `?poolhelp`) - Show pool game information
- **?poolrates** (aliases: `?rates`) - Show rates for specific rarity
- **?jackpot** (aliases: `?legendary`) - Show jackpot information

### 🎲 Simple Games
- **?roll** - Roll a dice (1-6)
- **?flip** - Flip a coin (heads or tails)
- **?duel** - Challenge another user to a crayon duel
- **?accept** (aliases: `?ACCEPT`) - Accept a duel challenge
- **?deny** (aliases: `?DENY`) - Decline a duel challenge
- **?duelhelp** (aliases: `?duelrules`, `?crayonduelhelp`) - Show duel rules

## 📊 Stats & Economy Commands

### 💰 Currency & Balance
- **?crayons** (aliases: `?Crayons`, `?bal`) - Check your crayon balance
- **?stats** - View your gaming statistics
- **?top** - Show top players by crayon count
- **?bstats** - Show overall bot statistics

### 🏆 Leaderboards
- Various game-specific leaderboards available through individual game commands

## 🎮 Gaming & Entertainment

### 🎯 Game Store Links
- **?currentgame** (aliases: `?playing`, `?whatgame`, `?game`) - Check current game being played
- **?gamelinks** (aliases: `?findgame`, `?search`, `?links`) - Get store links for current/specified game
- **?steam** - Get Steam store link for a game
- **?xbox** - Get Xbox Game Pass link for a game
- **?epic** - Get Epic Games Store link for a game
- **?st** - Get direct Steam store link (shortcut)

### 📺 Stream Information
- **?live** - Check if a streamer is live
- **?livestats** (aliases: `?lstats`) - Show live check statistics (mod only)
- **?streaminfo** (aliases: `?info`, `?stream`) - Get detailed stream information

## 🤖 AI Commands

### 🧠 AI Interaction
- **?ai** - Ask the AI assistant a question
- **?mood** - Check or change AI mood (mood admins only)
- **?moods** - List all available AI moods

### 🎭 AI Administration (Bacon_Space only)
- **?ama** - Add a mood admin
- **?rma** - Remove a mood admin
- **?masters** - Show list of mood admins
- **?checkup** - Check AI connection status (mods only)
- **?delay** - Show your AI cooldown information

### 🚫 Content Moderation (Bacon_Space only)
- **?addblock** - Add a word to blocked words list
- **?removeblock** - Remove a word from blocked words list
- **?blocklist** - Show blocked words count
- **?reloadblocks** - Reload blocked words from file
- **?banuser** (aliases: `?userban`) - Ban user from using AI
- **?unbanuser** (aliases: `?userunban`) - Unban user from using AI
- **?bannedlist** (aliases: `?bannlist`, `?banlist`) - Show banned users list

## 💬 Social & Interaction Commands

### 👋 Social Actions
- **?hug** - Send a virtual hug to someone
- **?bite** - Playfully bite someone
- **?slap** - Playfully slap someone
- **?bonk** - Bonk someone
- **?fistbump** - Give someone a fist bump
- **?poke** - Poke someone
- **?lick** - Lick someone with a random message

### 📈 Social Stats
- **?bitestats** - Show bite statistics
- **?biteleaderboard** - Show bite leaderboard
- **?bonkstats** - Show bonk statistics
- **?bonkleaderboard** - Show bonk leaderboard
- **?fbstats** - Show fistbump statistics
- **?fblb** - Show fistbump leaderboard
- **?lickstats** - Show lick statistics
- **?lickleaderboard** - Show lick leaderboard

### 🎤 Streamer Tools
- **?so** - Give a shoutout to another streamer

## 🛠️ Utility & Admin Commands

### 🔧 Bot Information
- **?ping** - Check bot latency
- **?uptime** - Show how long bot has been running
- **?version** (aliases: `?ver`) - Show bot version information (currently v10)

### 🏠 Channel Management
- **?join** - Make bot join a channel
- **?leave** - Make bot leave a channel

### 🔄 Bot Management
- **?reload** - Reload bot cogs (admin only)
- **?clear** - Clear chat (mod only)

## 💱 Currency Conversion Commands

### 💵 Money Conversion
- **?convert** (aliases: `?money`, `?currency`, `?exchange`) - Convert between currencies
- **?cad** - Convert CAD to USD
- **?usd** - Convert USD to CAD or other currency
- **?currencies** (aliases: `?currencylist`) - List supported currencies
- **?rates** (aliases: `?exchangerates`) - Show exchange rates

## 🎨 Special Features

### 🌈 7TV Integration
- **?7tv** - 7TV related commands

### 🎭 Entertainment
- **?joke** - Get a random joke
- **?wyr** - "Would You Rather" questions
- **?translate** - Translate text between languages
- **?ir** - Internet-related commands
 
### 🎳 Special Games
- **?bowl** (aliases: `?bowling`, `?strike`) - Play bowling game
- **?boom** (aliases: `?boommorph`, `?teleport`) - Boom/morph effect
- **?booml** - Boom effect variant
- **?archery** [distance] [power] - Take a shot at the target (10-100m, light/medium/heavy)
- **?practice** - Free practice mode to improve your skills
- **?archeryinfo** - Show current conditions and your detailed stats
- **?archerystats** [username] - View comprehensive archery statistics
- **?archeryleaderboard** - Top archers by accuracy, score, bullseyes, and best shots
- **?equipment** - View your current gear and available upgrades
- **?upgrade** [bow/arrows] [type] - Purchase new equipment

### 🕵️ Detective Missions

Take on undercover missions, find hidden items, and climb the detective ranks!

#### 🎯 Detective Commands
- **?detective** - Start a new detective mission with random objectives
- **?found [item]** - Report that you've found a required item for your mission
- **?detectivestats** - View your detective statistics and rank progression
- **?missionstatus** - Check your current active mission status

#### 🕵️ Detective Features
- **Mission System**: Random mission intros and item combinations
- **Time Pressure**: 5-minute mission timer adds excitement
- **Progressive Ranks**: Advance from Rookie to Master Detective
- **Item Collection**: Find various detective tools and gadgets
- **Persistent Stats**: Track missions completed, items found, and success rate
- **Cooldown System**: 2-minute cooldown between missions prevents spam

#### 🏆 Detective Ranks
- **Rookie** (0 missions) → **Investigator** (5 missions) → **Detective** (15 missions)
- **Senior Detective** (30 missions) → **Lead Detective** (50 missions) → **Special Agent** (75 missions)
- **Master Detective** (100+ missions)

#### 🔍 Mission Items
Find various detective tools including: lockpick, micro camera, signal emitter, data shard, crypto key, cipher disk, micro drone, thermal scope, noise filter, fake id, forging kit, cover docs, keycard, proximity probe

#### 📋 Mission Structure
```
🕵️ [Rank] [Username] - [Random Intro] Your Mission is to find [item1] and [item2]!
```

Mission intros include: "New intel found:", "Encrypted package received:", "Surveillance pickup:", "Asset secured:", "Field report:"

### 🎪 Crayon Circus

The Crayon Circus features 12 different mini-games that rotate daily! Each game has unique mechanics and rewards.

#### 🎮 Circus Games

**Skill & Challenge Games:**
- **Juggling Challenge** (🎯) - Guess how many balls you can juggle (1-10)
- **Tightrope Walk** (🎪) - Test your balance in a multi-step tightrope walk
- **Trapeze Swing** (🎭) - Time your trapeze release perfectly (early/perfect/late)
- **Strongman Contest** (💪) - Guess weight you can lift (50-200kg)
- **Acrobatics** (🤸) - Describe your acrobatic move and get rated by audience

**Performance & Entertainment:**
- **Lion Taming** (🦁) - Choose your approach to tame the lion (gentle/brave/tricky)
- **Clown Makeup** (🎨) - Create a clown design and get rated by the audience
- **Magic Show** (🪄) - Choose your magic trick (vanish/levitate/escape)
- **Fire Breathing** (🔥) - Choose your fire pattern (short/medium/long)
- **Ringmaster Performance** (🎤) - Choose your opening style (grand/funny/mysterious)

**Luck & Fortune:**
- **Fortune Teller** (🔮) - Get your daily fortune and win crayons

#### 🎯 Circus Commands
- **?circus** - Play today's featured circus mini-game
- **?circusinfo** - Show today's circus game and rules
- **?circusstats** [username] - View circus performance statistics
- **?circusleaderboard** - Show top circus performers by earnings, games played, and tickets
- **?tickets** - Check your circus tickets balance

#### 🏆 Circus Features
- **Daily Rotation**: A new featured game every day at midnight
- **Minute Cooldown**: Play the featured game every 60 seconds (instead of once per day)
- **Skill Progression**: Build skill levels in each game for better success rates
- **Combo System**: Consecutive wins build combo multipliers (up to 3x)
- **Ticket Rewards**: Earn tickets for successful performances (future prizes coming!)
- **Persistent Stats**: Track your circus career across all games
- **Varied Difficulty**: Games range from luck-based to skill-based challenges

#### 💰 Reward Structure
- **Min Reward**: 5 crayons for participation
- **Max Rewards**: 30-55 crayons depending on game difficulty
- **Combo Multipliers**: 1.5x (1+ wins), 2x (3+ wins), 3x (5+ wins)
- **Skill Bonuses**: 10% bonus per skill level in each game

## 📋 Command Categories Summary

### 🎲 Gambling & Casino
- Slots, Blackjack, Roulette, Plinko, Pool, Gamble, Dice, Coin Flip, Duels

### 📊 Economy & Stats
- Balance, Statistics, Leaderboards, Bot Stats

### 🗺️ Crayon Quests
Embark on epic adventures, battle monsters, and collect treasures in a persistent fantasy world!

#### 🎭 Quest Features
- **Character Classes**: Warrior, Mage, Rogue, Healer with unique abilities and stats
- **Turn-Based Combat**: Strategic battles with monsters using attack and defense mechanics
- **World Exploration**: Multiple areas (Forest, Desert, Mountains, Dungeon) with level requirements
- **Quest System**: Daily and weekly quests with different objectives (slay, collect, rescue)
- **Progression**: Level-based advancement with XP, stat increases, and achievements
- **Inventory Management**: Collect items, materials, and equipment for crafting
- **Persistent World**: Save your character and progress across sessions

#### 🗺️ Quest Commands
- **?quest** - View available quests and start one
- **?battle** [monster] [attack_type] - Fight monsters in turn-based combat
- **?inventory** - View your character stats, items, and equipment
- **?explore** [area] - Travel to different locations and discover secrets
- **?character** - View your detailed character sheet and progression
- **?questlog** - View your active and completed quest history

#### ⚔️ Combat Mechanics
- **Attack Types**: Slash (physical), Magic (special), Special (ultimate abilities)
- **Strategy Elements**: Monster weaknesses, terrain advantages, equipment bonuses
- **Loot System**: Random item drops from defeated monsters
- **Risk vs Reward**: Stronger monsters give better rewards but are harder to defeat

#### 🌍️ World Areas
- **Mystic Forest** (Level 1+): Goblins, wolves, treants with herbs and wood
- **Scorching Desert** (Level 5+): Scorpions, sand worms, dust devils with oasis water
- **Dragon Peaks** (Level 10+): Dragons, golems, harpies with iron ore and dragon scales
- **Shadow Dungeon** (Level 15+): Skeletons, ghosts, necromancers with dark crystals

#### 🏆 Progression System
- **Level Requirements**: 100 XP per level with stat bonuses
- **Character Classes**: Each class has unique HP, attack, and defense bonuses
- **Achievement Badges**: Level milestones, quest completions, and special accomplishments
- **Equipment Upgrades**: Find and craft better gear for improved combat performance

### 🎮 Gaming
- Game store links, Stream info, Current game detection, Crayon Circus, Archery Range, Detective Missions, Crayon Quests

### 🤖 AI Assistant
- Chat, Mood management, Admin controls, Content moderation

### 💬 Social
- Hugs, Bites, Slaps, Bonks, Fistbumps, Pokes, Licks, Shoutouts

### 🛠️ Utility
- Bot info, Channel management, Currency conversion

### 🎨 Entertainment
- Jokes, Would You Rather, Translation, Special effects

## 📝 Usage Tips

1. **All commands use the `?` prefix**
2. **Most games require crayons** - use `?daily` (if available) to get started
3. **Check your balance** with `?crayons` or `?bal`
4. **Many commands have cooldowns** to prevent spam
5. **Some commands are moderator/admin only**
6. **Use `?help` with specific commands** for detailed usage (where available)

## 🔐 Permission Levels

- **Everyone**: Most gaming and social commands
- **Moderators**: Channel management, some admin commands
- **Bacon_Space**: AI administration, user management, bot control

## 🎯 Getting Started

1. Check your balance: `?crayons`
2. Try a simple game: `?flip` or `?roll`
3. Play slots: `?slots 10` (bet 10 crayons)
4. Check stream game: `?currentgame`
5. Ask the AI: `?ai hello there`

---

*This bot is part of the Crayon Casino ecosystem. Enjoy responsibly!* 🖍️🎰
