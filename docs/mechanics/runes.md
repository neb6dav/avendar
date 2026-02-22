# Runes

The rune system is a specialized enchantment mechanic available to **Earth scholars** (particularly Runesmiths). Runes are carved into weapons and armor, then invoked to grant persistent magical effects. Unlike ordinary enchantments, runes interact with a complex attunement system that limits their total power and scales their mana cost dynamically.

---

## Overview

Runes represent ancient earth-magic symbols drawn from the deep geological memory of Avendar's stone. A runesmith carves these symbols into physical objects, binding elemental force into the material. Once carved, a rune must be **invoked** (activated) to provide its benefit — and can be **revoked** (deactivated) at will.

---

## The Sixteen Runes

Runes are organized by complexity — measured in **syllables**. More complex runes are more powerful but may be harder to carve and invoke.

| Rune | Type | Syllables | Description |
|------|------|-----------|-------------|
| **Still** | Base | 1 | Stabilizing, grounding effect |
| **Stone** | Base | 1 | Raw earth-power enhancement |
| **Ground** | Base | 1 | Anchoring, anti-levitation resistance |
| **Bind** | Intermediate | 2 | Binding force; restraining effect |
| **Strength** | Intermediate | 2 | Physical power enhancement |
| **Truth** | Intermediate | 2 | Detection or clarity effect |
| **Sunder** | Intermediate | 2 | Armor-penetrating or breaking effect |
| **Order** | Intermediate | 2 | Stabilization against chaos |
| **Fossil** | Intermediate | 2 | Preservation; hardening effect |
| **Tremor** | Advanced | 3 | Shockwave or destabilizing effect |
| **Calcify** | Advanced | 3 | Hardens organic material |
| **Gravitas** | Advanced | 3 | Weight-related; encumbrance effect |
| **Erosion** | Advanced | 3 | Gradual weakening of targets |
| **Pulverize** | Advanced | 3 | Crushing, destruction-oriented |
| **Adamantine** | Advanced | 3 | Ultimate hardening; extreme protection |
| **Empowerment** | Advanced | 3 | General magical amplification |

---

## Carving Runes

To carve a rune, the runesmith must:
1. Know the rune (via the learned bit system — each rune corresponds to a learned skill bit)
2. Have an appropriate weapon or piece of armor
3. Succeed on a skill check (`carve rune` command)

A successful carve inscribes the rune onto the object. A failed carve does nothing (or may waste the attempt). Objects can potentially hold multiple runes.

---

## Invoking and Revoking

| Command | Effect |
|---------|--------|
| `invoke rune <object>` | Activates a carved rune, applying its effect |
| `revoke rune <object>` | Deactivates an active rune, removing its effect |

When a rune is invoked, it enters the **invoked runes** list visible through the `runes` command display. Runes that are carved but not active appear in the **invokable runes** list.

---

## Attunement System

The attunement system is the heart of rune complexity. It limits and prices how many runes can be active at once:

- **Attunement count** — the total number of active runes counts against attunement
- **Mana cost scaling** — as more runes are invoked, the mana cost of each active rune increases
- **Monotonic exception** — a single-syllable ("mono") rune invoked first may be free or very cheap
- **Diminishing returns** — the more runes active, the more each costs

This creates strategic tension: a runesmith can invoke many weak runes cheaply, or fewer powerful runes at higher cost, but cannot maximize everything.

The formula adjusts costs based on total active attunements, with the first attunement being cheapest and each subsequent one more expensive.

---

## Viewing Your Runes

The `runes` command displays three sections:

1. **Known Runes** — organized by syllable count; shows all runes you have learned
2. **Invoked Runes** — currently active runes with the object they are carved on
3. **Invokable Runes** — carved but inactive runes, showing their current mana cost if invoked

---

## Roleplaying Runes

Runes in Avendar are tied to Earth sphere tradition and the deep memory of stone. Runesmiths are craftspeople as much as they are scholars — their power lives in patience, precision, and understanding of material. The runes they carve echo the geological age of the world, drawing on forces older than any recorded history.

Carving a rune is an act of permanence; the mark left on an object persists until the object is destroyed. Some weapons and armor become heirlooms precisely because of the runes they carry.
