---
type: encounter
tags: [encounter, combat, session-3, optional]
status: active
difficulty: medium
location: "[[locations/loom-sanctum]]"
---

# Loom Frame Guardian

> *"UNAUTHORIZED ACCESS DETECTED. INITIATING CONTAINMENT PROTOCOL."*

## Overview

| Attribute | Value |
|-----------|-------|
| Type | Combat (optional encounter) |
| Session | [[sessions/session-03-the-spiral|Session 3]] (if exploring) |
| Difficulty | Medium |
| Goal | Protect access to [[locations/loom-sanctum\|Loom Frame]] installations |
| Location | Any [[locations/loom-sanctum\|Loom Frame]] location |

---

## Setup

The [[lore/the-loom-consortium|Loom Consortium]] doesn't leave its infrastructure unguarded. Each Loom Frame—the massive arcane-mechanical devices that maintain [[locations/the-gilded-reach|the Gilded Reach]]—is protected by Frame Wardens: animated constructs designed to neutralize threats.

### Triggering the Encounter

PCs encounter Frame Wardens when:
- Accessing a Loom Frame without [[characters/npcs/orenthal-vane|Vane's]] override codes
- Attempting to damage or interfere with the Frame
- Spending too long in restricted areas
- Discovered by [[lore/the-loom-consortium|Consortium]] security

### Read-Aloud

> The Loom Frame hums with arcane energy—a massive cylinder of brass and crystal, pulsing with geometric patterns. Cables snake from it into the stone floor, the walls, the ceiling. You can feel it vibrating in your bones.
>
> Then the statues move.
>
> Two figures of polished brass unfold from alcoves you didn't notice. Their faces are featureless. Their hands end in articulated claws. Their chests glow with the same spiral pattern as the Frame.
>
> "UNAUTHORIZED ACCESS DETECTED," one intones in a voice like grinding gears. "INITIATING CONTAINMENT PROTOCOL."

---

## Enemies

### Frame Wardens (2)

Reflavored Animated Armor with Consortium aesthetics.

```
Frame Warden
Medium construct, unaligned
AC 18 (natural armor)
HP 33 (6d8 + 6)
Speed 25 ft.

STR 14 (+2) DEX 11 (+0) CON 13 (+1)
INT 1 (-5) WIS 3 (-4) CHA 1 (-5)

Damage Immunities: poison, psychic
Condition Immunities: blinded, charmed, deafened, exhaustion,
   frightened, paralyzed, petrified, poisoned
Senses: blindsight 60 ft. (blind beyond this radius),
   passive Perception 6
Languages: understands Common but can't speak

False Appearance. While motionless, the warden is indistinguishable
from a decorative statue.

Actions:
Multiattack. The warden makes two slam attacks.

Slam. Melee Weapon Attack: +4 to hit, reach 5 ft.,
one target. Hit: 1d6 + 2 bludgeoning damage.

Containment Field (Recharge 5-6). The warden releases a pulse
of arcane energy in a 10-foot radius. Each creature in that area
must succeed on a DC 13 Dexterity saving throw or take 2d6 force
damage and be restrained until the end of their next turn.
```

| Creature | AC | HP | Attack | Damage |
|----------|----|----|--------|--------|
| Frame Warden (x2) | 18 | 33 | +4 | 1d6+2 x2 (slam) |

---

## Combat Dynamics

### Terrain: Loom Frame Chamber

| Feature | Effect |
|---------|--------|
| Energy conduits | Dangerous to touch (1d6 lightning), can be severed |
| Crystal nodes | Provide half cover, shatter if struck (2d4 piercing in 5 ft.) |
| Control console | DC 15 Arcana to disable wardens (requires 2 actions) |
| Unstable floor | Some sections unstable (DC 12 Dex or fall prone) |

### Warden Tactics

- **Defensive Priority**: Focus on preventing access to the Frame
- **Tandem Movement**: One engages while the other flanks
- **Containment Field**: Use when multiple PCs are clustered
- **Relentless**: Will not retreat or negotiate

### Disabling Options

Players can avoid or end combat through:

**Hack the Console** (DC 15 Arcana, 2 actions):
> The console flickers as you work the strange controls. Finally, the wardens freeze mid-swing, then fold back into their alcoves.

**Use [[characters/npcs/orenthal-vane|Vane's]] Codes** (Automatic if given):
> "Override alpha-seven," you speak clearly. The wardens pause, then step aside, creating a clear path to the Frame.

**Destroy the Wardens**: Standard combat resolution.

**Destroy the Frame**: The wardens deactivate, but the Frame's destruction has consequences (reality glitches, potential collapse).

---

## Aftermath

### If Wardens Are Destroyed

The way to the Loom Frame is clear. However:
- An alarm may have been triggered
- [[lore/the-loom-consortium|Consortium]] security may be alerted
- Other frames may have enhanced security

### If PCs Used Override Codes

The wardens remain inactive. [[characters/npcs/orenthal-vane|Vane's]] codes grant temporary access to [[lore/the-loom-consortium|Consortium]] systems.

### If PCs Hacked the Console

They gain temporary access and potentially learn:
- **DC 12 Investigation**: Basic Frame function (reality maintenance)
- **DC 15 Investigation**: Location of other Frames
- **DC 18 Investigation**: How to broadcast an awakening signal

---

## Loot

The Frame chamber contains:

| Item | Location |
|------|----------|
| Brass components | From destroyed wardens—worth 50 gp |
| Crystal shards | If nodes shattered—arcane focus components |
| Maintenance logs | Console—clues about [[lore/the-loom-consortium\|Consortium]] operations |
| Emergency override key | Hidden compartment (DC 14 Investigation)—one-time use |

---

## DM Notes

### Purpose
This encounter provides:
- Action during exploration sequences
- Demonstration of [[lore/the-loom-consortium|Consortium]] resources
- Opportunity to learn more about the Frames
- Mechanical challenge for combat-focused groups

### Scaling
**Easier**: Only one warden, or wardens at half HP.
**Harder**: Three wardens, or add a Frame Overseer (use Helmed Horror statblock).

### Optional: Frame Overseer

For an extended exploration sequence, add a more powerful guardian:

```
Frame Overseer (Helmed Horror)
AC 20, HP 60
Attacks: +6, 1d8+4 longsword x2
Special: Spell immunity (fireball, heat metal, hold person)
```

The Overseer commands the wardens and can activate/deactivate them remotely.

### Connection to Story

The Loom Frames are central to the [[locations/the-gilded-reach|Gilded Reach's]] existence. What PCs do here affects the finale:
- Destroy Frames → Reality destabilizes (Option D)
- Access Frames → Can broadcast awakening signal (Option B)
- Learn codes → Can negotiate from strength (Option C)
