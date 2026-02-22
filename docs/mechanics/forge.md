# The Forge System

The Forge is an advanced crafting system that allows skilled smiths to create powerful, customized weapons. Forged weapons are generated with semi-random special properties influenced by the weapon type and the materials used in their creation. The system also supports weapon naming for unique, one-of-a-kind creations.

---

## Overview

Forging is available to characters with the appropriate smithing skills. Rather than producing a generic item, forging produces a weapon with unique statistics and special properties determined by:

1. **Weapon type** — the base form and its elemental affinities
2. **Materials used** — each material biases the outcome toward certain properties
3. **Skill level** — higher skill reduces flaws and increases the quality of the result
4. **Naming** — an optional 100-mana investment to give the weapon a unique name

---

## Weapon Types

Twenty distinct weapon types can be forged, spanning all combat styles:

| Weapon | Type | Hands | Notes |
|--------|------|-------|-------|
| **Rapier** | Piercing | One | Fast, precise |
| **Shortsword** | Slashing | One | Versatile |
| **Broadsword** | Slashing | One | Balanced |
| **Claymore** | Slashing | Two | High damage |
| **Quarterstaff** | Bashing | Two | Caster-friendly |
| **Staff** | Bashing | Two | Magical variant |
| **Mace** | Bashing | One | Blunt force |
| **Warhammer** | Bashing | Two | Heavy crusher |
| **Morningstar** | Bashing | One | Spiked bludgeon |
| **Javelin** | Piercing | One | Thrown |
| **Spear** | Piercing | Two | Reach weapon |
| **Dirk** | Piercing | One | Small, concealable |
| **Dagger** | Piercing | One | Light, fast |
| **Halberd** | Slashing | Two | Polearm |
| **Lucerne** | Piercing | Two | Polearm with hook |
| **Hatchet** | Slashing | One | Axe variant |
| **Battleaxe** | Slashing | Two | Heavy axe |
| **Fallenstar** | Slashing | One | Exotic design |
| **Flail** | Bashing | One | Chain weapon |
| **Whip** | Slashing | One | Reach, flexible |

---

## Forge Traits

Each weapon type has **traits** — elemental and functional affinities that describe what the weapon is naturally suited for. Traits influence what special properties the weapon is likely to receive.

| Trait | Description |
|-------|-------------|
| **Parry** | Defensive weapon, favors parrying specials |
| **Casting** | Suited for spellcasters |
| **Water** | Water sphere affinity |
| **Earth** | Earth sphere affinity |
| **Void** | Void sphere affinity |
| **Spirit** | Spirit sphere affinity |
| **Air** | Air sphere affinity |
| **Fire** | Fire sphere affinity |

---

## Special Properties

Forged weapons can gain the following special properties. Each has base odds of appearing and is influenced by trait bias:

| Special | Effect | Multiple Allowed? |
|---------|--------|-----------------|
| **Parry** | Bonus to parrying attacks | Yes |
| **Casting** | Bonus to spell casting | Yes |
| **NoDisarm** | Cannot be disarmed | No |
| **Vampiric** | Life-steal on hit | No |
| **Poison** | Applies poison on hit | No |
| **Hitroll** | Bonus to hit rolls | Yes |
| **Damroll** | Bonus to damage rolls | Yes |
| **Saves** | Bonus to saving throws | Yes |
| **Luck** | Luck bonus | Yes |
| **HitPoints** | Bonus max hit points | Yes |
| **Mana** | Bonus max mana | Yes |
| **Moves** | Bonus max movement | Yes |
| **Water** | Water sphere enhancement | Yes |
| **Earth** | Earth sphere enhancement | Yes |
| **Void** | Void sphere enhancement | Yes |
| **Spirit** | Spirit sphere enhancement | Yes |
| **Air** | Air sphere enhancement | Yes |
| **Fire** | Fire sphere enhancement | Yes |

### Bias System

Each special property has a **bias** relative to each weapon type and each material:

| Bias Level | Description |
|------------|-------------|
| **Prohibited** | Cannot appear on this weapon/material |
| **Unlikely** | Possible but rare |
| **Normal** | Standard probability |
| **Likely** | Increased probability |
| **Guaranteed** | Always appears |

The combined weapon bias and material bias determine the final odds. For example, a staff is likely to gain Casting properties but unlikely to gain Vampiric, while materials from the Fire plane boost Fire sphere enhancements.

---

## Materials

Materials used in forging each carry their own affinities. The materials available in the world — metals, stones, and unusual substances — all contribute different biases to the forging outcome.

**Key material categories:**
- **Common metals** (iron, steel): balanced biases, no special emphasis
- **Magical metals** (mithril, adamantite): enhance physical properties (Hitroll, Damroll)
- **Elemental materials** (volcanic stone, glacial ice): strong elemental affinities
- **Exotic materials** (bone, corruption): unusual or specialized properties

---

## The Forging Process

1. **Gather base materials** — collect the raw ingredients needed for your chosen weapon type
2. **Begin forging** — use the forge skill with your chosen weapon type as the argument
3. **Skill check** — your smithing skill determines quality; higher skill = fewer flaws = better specials
4. **Material bias** — the materials consumed influence which special properties appear
5. **Result** — receive a unique weapon with randomly-determined specials within the bias constraints

### Flaws

Lower skill levels introduce **flaws** — imperfections that reduce the weapon's effectiveness or limit which properties can appear. Expert smiths produce flawless weapons with maximum potential for powerful specials.

---

## Weapon Naming

For an additional cost of **100 mana**, a smith can give a forged weapon a unique name using the `name weapon` command. This:
- Assigns a custom name to the weapon
- Makes the weapon truly unique and identifiable
- Is a permanent change that cannot be undone

The naming ability requires that the smith have the appropriate naming effect active. Named weapons become legendary items with their own identity in the game world.

---

## Roleplaying the Forge

The Forge system represents Avendar's tradition of master craftsmanship. A smith who creates a forged weapon is not merely following a recipe — they are inscribing their own elemental understanding into the metal. The result reflects both the smith's skill and the mystical properties of the materials used.

Forged weapons are valued not just for their mechanical power but as artifacts of craft. In Avendar's roleplay-heavy environment, a well-named weapon with a storied history carries as much weight as the numbers on its stats sheet.
