# Alchemy

Alchemy is a crafting system available to Druids and Naturalists that allows the creation of consumable magical items — oils, potions, and pills — by combining spell-imbued ingredients. The outcome depends on which spells the alchemist knows, what ingredients they combine, and the "platonic bias" of those ingredients.

---

## Overview

Unlike fixed recipes, Avendar's alchemy is emergent: the alchemist combines 3–9 ingredients and the resulting product is determined by the biases present in those ingredients relative to the alchemist's known spells. Skilled alchemists can influence the outcome by carefully selecting ingredients.

---

## The Three Alchemy Skills

| Command | Product | Ingredient Count | Notes |
|---------|---------|-----------------|-------|
| `mix` | **Oil** (applied to weapons/equipment) | 3–9 items | Liquid ingredients only for some specials |
| `brew` | **Potion** (drunk for effect) | 3–9 items | |
| `make` | **Pill** (swallowed for effect) | 3–9 items | Solid ingredients only for some specials |

Each skill is a separate trainable ability. Higher skill improves success rate and product quality.

---

## Platonic Biases

Each alchemical ingredient carries one or more **platonic biases** that reflect its elemental and conceptual nature. When combined, the dominant biases of all ingredients determine what spell effect the product contains.

### Elemental Biases

| Bias | Color Indicator | Associated Sphere |
|------|----------------|-------------------|
| **Spirit** | Golden tones | Spirit |
| **Water** | Blue tones | Water |
| **Air** | White/clear tones | Air |
| **Earth** | Brown tones | Earth |
| **Fire** | Red tones | Fire |
| **Void** | Black tones | Void |
| **Nature** | Green tones | Druidic |
| **Ancient** | Purple/prismatic | Ancient magic |
| **Transmogrify** | Silver tones | Transformation |

### Conceptual Biases

| Bias | Effect Type |
|------|------------|
| **Damage** | Direct harm spells |
| **Malediction** | Curses and debuffs |
| **Protection** | Defensive buffs |
| **Order** | Binding and stabilizing effects |
| **Enhancement** | Stat and ability boosts |
| **Chaos** | Unpredictable or scatter effects |
| **Obscurement** | Invisibility, illusion, confusion |
| **Healing** | Curative spells |
| **Knowledge** | Detection and information |
| **Planar** | Transportation and planar effects |
| **Alteration** | Transformation effects |

---

## Product Appearance

The appearance of an alchemical product is described using color words and adjectives derived from the dominant bias and the skill used:

**Colors** (from most Spirit-dominant to most Void-dominant, lightest to darkest):
- Spirit: gold-flecked → golden → aureate → bright gold → aurulent → dazzlingly golden → sunfire
- Water: blue-tinged → pale blue → light blue → sky blue → blue → dark blue → deep blue → royal blue → navy blue → midnight blue
- Air: clear → faint → pale → faint white → white → bright white → bleached → bone-white → chalk-white → alabaster
- Earth: dark yellow → faint brown → light brown → copper-colored → brown → russet → chestnut → umber → dark brown → deep brown
- Fire: pink → pale red → light red → rosy → red → vermillion → sanguine → maroon → scarlet → crimson
- Void: grey → dark grey → light black → dusty black → black → ebony → onyx → coal-black → midnight-black → pitch-black
- Nature: green-tinged → pale green → light green → lime green → green → pine green → olive green → deep green → dark green → forest green
- Ancient: lavender → lilac → mauve → light purple → purple → amethyst → violet → deep purple → dark purple → royal purple
- Transmogrify: silver-flecked → silver-tinged → pale silver → sterling → silver → argentate → bright silver → shining silver → dazzling silver → moonlight-silver

**Adjectives** (randomly applied): shimmering, clotted, coagulated, pungent, hazy, misty, viscous, warm, steaming, thin, glutinous, milky, aromatic, caustic, cold, fragrant, foaming, metallic, oily, pearlescent, sparkling, sticky, swirling, strange-smelling, frozen, frothy, foul-smelling, foul, flaming, filmy, dense, fermenting, smoking, odd, odorless, oozing, opaque, syrupy, tasteless, bland, acrid-smelling, cloudy, bubbling, incandescent, murky, greasy

A successful creation might produce "a shimmering golden potion" (Spirit-biased healing) or "a pungent midnight-black oil" (Void-biased malediction).

---

## Sphere-Based Spell Lists

Alchemy draws from the alchemist's known spells. The product's effect is chosen from spells the alchemist knows that match the dominant platonic bias. Each sphere contributes differently:

### Void Sphere Examples
| Spell | Biases | Power |
|-------|--------|-------|
| Voidwalk | Obscurement, Alteration, Planar | 10 |
| Possession | Planar, Obscurement | 9 |
| Vortex | Planar | 9 |
| Embrace of Isetaton | Malediction | 7 |
| Globe of Darkness | Obscurement | 7 |
| Sleep | Malediction, Obscurement | 8 |
| Weaken | Damage, Malediction | 7 |

### Spirit Sphere Examples
| Spell | Biases | Power |
|-------|--------|-------|
| Avatar | Planar, Alteration | 10 |
| Spirit Sanctuary | Planar, Obscurement | 9 |
| Astral Projection | Planar | 8 |
| Wrath of Kyana | Malediction, Damage | 7 |
| Soul Flare | Malediction | 7 |

### Water Sphere Examples
| Spell | Biases | Power |
|-------|--------|-------|
| Resurrection | Healing, Planar | 10 |
| Sanctuary | Enhancement, Protection | 9 |
| Revitalize | Healing | 8 |
| Mass Heal | Healing | 7 |
| Icy Prison | Planar, Order | 8 |
| Wall of Water | Planar | 8 |

### Fire Sphere Examples
| Spell | Biases | Power |
|-------|--------|-------|
| Disintegration | Chaos, Damage | 10 |
| Implosion | Chaos, Damage | 10 |
| Firestorm | Chaos, Damage | 8 |
| Ring of Fire | Malediction, Damage | 7 |

### Earth Sphere Examples
| Spell | Biases | Power |
|-------|--------|-------|
| Diamond Skin | Alteration, Protection | 10 |
| Crystalize Magic | Order, Protection | 9 |
| Flesh to Stone | Order, Alteration | 8 |
| Stone Skin | Alteration, Protection | 7 |
| Wall of Stone | Protection, Order | 7 |

### Air Sphere Examples
| Spell | Biases | Power |
|-------|--------|-------|
| Tempest | Chaos, Damage | 7 |
| Chain Lightning | Chaos, Damage | 8 |
| Cloudkill | Planar, Damage, Malediction | 8 |
| Greater Invis | Obscurement | 9 |
| Blade Barrier | Planar, Enhancement, Protection | 7 |

---

## Alchemy Special Processing

Some special ingredient processing skills allow transformation of raw ingredients before combining:

| Processing | Result | Restriction |
|-----------|--------|-------------|
| Distillate | A distillate of [ingredient] | Liquids only |
| Powder | Fine powder ground from [ingredient] | Solids only |
| Reforged Metal | Metal reforged from [ingredient] | Metals only |
| Concentrate | A concentrate of [ingredient] | Liquids only |
| Solution | A solution of [ingredient] | Solids only |
| Diluted | Some diluted [ingredient] | Liquids only |

---

## Tips for Alchemists

- **Match biases to desired effects**: For a healing potion, use Water-biased ingredients with Healing conceptual bias.
- **Power matters**: Higher-power spells require more matching bias ingredients to appear.
- **Ingredient count**: More ingredients (up to 9) can stabilize the dominant bias and improve the chance of a desired spell outcome.
- **Know your spells**: Only spells you have learned can appear in your products.
- **Sphere affinity**: Each druidic subtype (herbalist, apothecary, etc.) may have different natural affinities, making certain products easier to craft.
