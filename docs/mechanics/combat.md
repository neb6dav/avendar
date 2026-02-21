# Avendar: Combat Mechanics

Combat is a central pillar of Avendar's gameplay. The game is an **RP+/PvP+ MUD**, meaning both roleplaying and player-vs-player combat are encouraged and enforced. Unlike some MUDs where PK is discouraged, Avendar uses inter-character combat as a method for in-game conflict resolution and as an enhancement to roleplay.

---

## Basic Combat

### Command Structure

Commands in Avendar are generally constructed in the order of **verb/action → object → target**. Avendar does **not** use bridging words or prepositions like 'to', 'from', 'with', 'my', or 'at' in commands. Interaction with objects defaults to your own inventory first, then the room.

### The Lag System

Avendar uses a **lag** system rather than a countdown timer:
- When you execute a command (such as casting a spell or making an attack), there is a delay before your next command executes
- You may **queue up multiple commands** while lagged; they will execute in the order you enter them
- Different abilities create varying amounts of lag
- Managing lag is a core skill in Avendar PvP

---

## Melee Combat

### Attacks and Damage

**Key melee mechanics:**
- Characters can gain **multiple attacks** per round as they advance in level and skill (e.g., `second attack`)
- **Hitroll** affects the chance to land an attack
- **Damroll** affects how much damage a successful attack deals
- **Armor class (AC)** affects how difficult a character is to hit

### Melee Skills

| Skill | Description |
|-------|-------------|
| **Parry** | Deflects incoming melee attacks; effectiveness for fighters was reduced in updates |
| **Fend** | Defensive skill; overall effectiveness was slightly reduced |
| **Gash** | Deals bonus damage compared to regular melee; now deals less bonus damage than before |
| **Bash** | Knockdown attempt; has a mana cost; follows general rules of melee combat |
| **Shield Bash** | Knockdown with a shield; has a mana cost; no longer more effective than regular bash against deflection |

### Defensive Stance

A defensive stance provides:
- Protection against spells (this protection was **reduced by half** in updates)
- Physical damage reduction applies **only to regular melee attacks** (not to bash/special attacks)

---

## Ranged Combat

Several classes specialize in archery and ranged combat:
- **Air Templars** blend swordsmanship with archery
- **Rangers** are the primary ranged combat specialists (30+ skills)
- Wind magic can enhance arrow attacks in some combinations

---

## Spellcasting in Combat

### Concentration

A **concentration skill** determines whether spells succeed during combat:
- Spellcasting no longer fails concentration when **outside of combat**
- When concentration fails, the skill itself improves (learning through failure)
- The **Battlecaster** trait (renamed from "armored caster") allows certain templars to automatically pass concentration checks
- Individual spell percents improve effective caster level when cast regularly

### Spell Interruption

Being attacked while casting can interrupt or disrupt spellcasting, depending on the caster's concentration skill and the nature of the attack.

---

## Player Killing (PK)

### PK System Overview

The PK system is a **compromise between open and non-PK**:
- Ranges are established permitting characters to kill each other as long as they are **within certain levels of each other**
- There are **no completely "safe" areas** (though city guards and taverns with bouncers offer safer zones)
- PK clashes sometimes involve groups of four or more players

### PK and Roleplay

Unlike some MUDs where PvP is discouraged, Avendar views inter-character combat as:
- A method for **in-game conflict resolution**
- An **enhancement to roleplay**
- A tool for playing out ideological conflicts between Houses

The balance of player-driven conflict and staff-enforced roleplaying has helped Avendar remain active for decades.

### PK Considerations by Race

Some racial choices heavily influence PK engagement:
- **Shuddeni** (always evil) — Automatically in conflict with good-aligned characters; expect heavy PvP
- **Ch'taren** (always good) — Natural enemies of evil races; expect frequent PvP in houses
- If player-killing isn't your preference, avoid playing these races in a House

---

## Alignment and Combat Experience

Alignment affects combat experience (XP) gain:

| Scenario | XP Effect |
|----------|-----------|
| Good character kills evil mob | **More XP** |
| Good character kills good mob | **Loses XP** |
| Evil character kills good mob | **Extra XP** |
| Evil character kills evil mob | **Slightly less XP** |

This creates a mechanical bias toward good alignments, as many aggressive areas are already populated by hostile evil creatures.

---

## Death and Permanent Death

### Permanent Death System

Avendar incorporates **permanent death** (character loss):
- Ensuring regular character churn means no character or group of characters can perpetually dominate
- New or returning players are never perpetually unable to catch up

### Character Lifespan

Player characters in Avendar have a **finite lifespan**. It is intended that no player character remain in active play for longer than about **a year and a half of real-life time**, either due to:
- Running out of deaths (each character has a limited number of lives)
- Reaching their maximum age

This design philosophy ensures the world is always changing and no single character can accumulate permanent, overwhelming power.

---

## Special Combat Abilities

### Frenzy

> *"Imbues its target with rage, granting a bonus to both hitroll and damroll. However, the lack of care caused by this state causes a penalty to the target's armor class."*

- Cannot be cast on someone already berserk
- Those imbued with rage are **unable to retreat or cower** away from battle
- It is not possible to cast this spell on someone already under a berserk effect

### Demonbound Weapons (Void Templar)

Void Templars can infuse their weapons with demonic essence through demonbound rites:
- Grants unnatural speed
- Grants supernatural strength
- Can grant the ability to leech life from foes

Spirit Templars can **purge** demonbound weapons through exorcism.

### Summoning in Combat

Void Scholars of the **Riven Veil** path can conjure demons directly to the Prime Material to fight alongside them — or unleash them against enemies — making them powerful force multipliers in extended combat.

---

## Group Combat

### Grouping

Characters can form **groups** to adventure and fight together. Group composition typically involves:
- A tank/melee fighter to hold enemy attention
- Healers (Water scholars, Spirit scholars/templars)
- Damage dealers (Fire scholars, offensive melee)
- Support (Psionicists, Bards)

### House Warfare

At higher levels, combat often involves **House conflicts** over the **ten Stones of Power**. These ideological wars can involve large-scale group PvP battles between rival Houses.

---

## Combat and Equipment

### Equipment Importance

Equipment is the **primary means by which you gain power** for your character once you have reached hero level and maxed all skills:
- Exceptional items are often **limited** (only so many copies exist in the game world)
- Particularly exceptional or legendary items are **limit 1**
- Powerful but less rare items may have higher limits
- Items can be imbued with elemental properties that affect combat

### Item Loss in PK

Dying to another player may result in the loss of equipment, making PvP both a risk and a reward system — defeating enemies can yield valuable limited gear.

---

## Sources

- [avendar.net/Avendar:Basics](https://avendar.net/Avendar:Basics)
- [avendar.net/character-creation/roleplay-in-avendar/alignments/](https://avendar.net/character-creation/roleplay-in-avendar/alignments/)
- [avendar.net/2020/01/june-2019-mega-update-part-4/](https://avendar.net/2020/01/june-2019-mega-update-part-4/)
- [mudstats.com — Avendar](http://mudstats.com/World/AvendarTheCrucibleofLegends)
- [topmudsites.com — Avendar](https://www.topmudsites.com/forums/muddisplay.php?mudid=avendar)
