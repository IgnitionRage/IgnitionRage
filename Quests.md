# Quests.py Usage Guide

The `quests.py` module is a comprehensive RPG-style questing system for your Twitch bot. Here's how to use it:

## **Core Commands**

### **Character Management**
- `?char` - View your complete character sheet including class, level, XP progress, HP, attack/defense stats, gold, location, active quests, and achievements
  - Shows XP percentage to next level
  - Displays current and maximum HP
  - Lists up to 2 active quests with progress
  - Shows first 3 achievements (with count if more)

- `?inv` - Display all items in your inventory with counts, plus current stats
  - Shows gold amount and current HP
  - Lists attack/ defense stats
  - Displays current location
  - Groups duplicate items with counts (e.g., "Herbs x3")
  - Shows item descriptions from the items database

### **Quest System**
- `?quest` - View all available daily quests that you haven't started yet
  - Shows quest ID, title, and description
  - Displays up to 5 available quests
  - Includes hint: "?quest [quest_id] to start a quest!"
  - If no quests available, suggests completing current quests or waiting for daily reset

- `?quest [quest_id]` - Start a specific quest from the available list
  - Examples: `?quest daily_0`, `?quest daily_1`, `?quest daily_2`
  - Checks if you meet the area's level requirement
  - Adds quest to your active quest list
  - Shows quest title, description, location, and required progress (0/X)
  - Error if quest ID not found or already started

- `?questlog` - View your complete quest history and current progress
  - **Active Quests Section**: Shows all incomplete quests with progress (X/Y)
    - Displays quest title, current progress, required amount, and location
  - **Recently Completed Section**: Shows last 5 completed quests
    - Displays quest title with XP and gold rewards earned
  - If no active quests, shows "Active Quests: None"

### **Combat & Exploration**
- `?battle [monster] [attack_type]` - Engage in turn-based combat with monsters
  - **Monster Options**: Must be available in your current area
    - Forest: goblin, wolf, treant
    - Desert: scorpion, sand_worm, dust_devil  
    - Mountains: dragon, golem, harpy
    - Dungeon: skeleton, ghost, necromancer
  - **Attack Types**: 
    - `slash` - Standard physical attack
    - `magic` - Magical attack
    - `special` - Special ability attack
  - **Combat Mechanics**: 
    - Turn-based battle with damage calculations
    - Damage = Your Attack - Monster Defense + Random modifier
    - Victory grants XP, gold, and quest progress
    - 30% chance for item drops from area
    - Defeat respawns you with 50% HP
  - **Examples**: `?battle goblin slash`, `?battle dragon magic`

- `?explore` - View detailed information about your current location
  - Shows area name and description
  - Lists all monsters found in this area
  - Shows all items that can be discovered here
  - Lists all available areas you can travel to
  - **Example Output**: "Current Location: Mystic Forest - A dense forest filled with ancient trees and hidden paths"

- `?explore [area]` - Travel to a new area (requires minimum level)
  - **Area Requirements**:
    - `forest` - Level 1 (starting area)
    - `desert` - Level 5 requirement
    - `mountains` - Level 10 requirement  
    - `dungeon` - Level 15 requirement
  - **Travel Effects**:
    - Updates your current location
    - 30% chance to discover a random item from that area
    - If item found, adds to inventory automatically
    - Error message if you don't meet level requirement
  - **Examples**: `?explore desert`, `?explore mountains`
  - **Available Areas**: forest, desert, mountains, dungeon

## **Character Classes**

Choose from 4 classes with unique bonuses:
- **Warrior**: +20 HP, +5 Attack, +3 Defense (Master of combat)
- **Mage**: +10 HP, +8 Attack, +1 Defense (Magic wielder)  
- **Rogue**: +15 HP, +6 Attack, +2 Defense (Stealthy fighter)
- **Healer**: +12 HP, +3 Attack, +2 Defense (Support specialist)

## **Game World**

### **Areas** (with level requirements)
- **Mystic Forest** (Level 1): goblins, wolves, treants
- **Scorching Desert** (Level 5): scorpions, sand worms, dust devils
- **Dragon Peaks** (Level 10): dragons, golems, harpies
- **Shadow Dungeon** (Level 15): skeletons, ghosts, necromancers

### **Quest Types**
- **Monster Hunt**: Slay specific monsters
- **Resource Gathering**: Collect items from areas
- **Boss Challenge**: Defeat powerful bosses
- **Rescue Mission**: Save targets from dangerous areas

## **Progression System**

- **XP & Levels**: Gain XP from combat and quests (100 XP per level)
- **Stat Growth**: +2 Attack, +1 Defense, +10 HP per level
- **Achievements**: Unlock at levels 5, 10, 20
- **Gold & Loot**: Earn currency and items from victories

## **Getting Started**

### **Step-by-Step Tutorial**

1. **Check Your Character**
   - Use `?char` to see your starting stats
   - You begin as Level 1 Warrior with 100 HP, 10 Attack, 5 Defense
   - Starting location: Mystic Forest
   - Starting gold: 100

2. **Explore Your Starting Area**
   - Try `?explore` to see Forest details
   - You'll see available monsters: goblin, wolf, treant
   - Available items: herbs, wood, mushrooms

3. **Find and Start a Quest**
   - Use `?quest` to see available daily quests
   - Try `?quest daily_0` to start your first quest
   - Note the area requirement and target

4. **First Battle**
   - Use `?battle goblin slash` to fight your first monster
   - Combat is automatic - just watch the results
   - Victory gives XP, gold, and quest progress
   - Check if you leveled up!

5. **Track Your Progress**
   - Use `?questlog` to see quest progress
   - Use `?inv` to check for new items
   - Use `?char` to see level improvements

### **Pro Tips**

- **Combat Strategy**: Attack types don't currently affect damage, but future updates may add elemental advantages
- **Area Progression**: Complete quests and grind XP to unlock new areas at levels 5, 10, and 15
- **Daily Quests**: 3 new quests generate each day - check `?quest` regularly
- **Item Collection**: 30% drop chance from combat, 30% discovery chance when exploring new areas
- **Level Up Benefits**: Each level grants +10 HP, +2 Attack, +1 Defense and full heal

### **Common Command Patterns**

```
?char                         # Check stats
?quest                        # See available quests  
?quest daily_0               # Start first quest
?explore                     # View current area
?battle goblin slash         # Fight easiest monster
?questlog                    # Check progress
?inv                         # See items/gold
?explore desert              # Try new area (level 5+)
```

## **Command Aliases**

- **Character**: ```?char``` (short for character)
- **Inventory**: ``` ?inv ``` (short for inventory)

The system automatically saves progress and generates new daily quests!
