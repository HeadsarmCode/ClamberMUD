Warrior's level-8 special is **Lure**. It isn't Warrior-only: it comes from the Wilds archetype pool, so Barbarian, Beastmaster, Berserker, Ranger, Skald and Spiritwalker also learn it at character level 8. It starts at skill level 1 and caps at 15.

## What it does
`lure <target>` is an attack with a 15-second cooldown and no other cost. You toss bloody meat at a foe and it rolls whether to go for it:

- **Living targets** bite on 85% + skill level, so 86% at level 1, 95% at level 10, and always from level 15.
- **Undead, constructs, elementals and spirits** bite on 35% + 2 × skill level, so 37% at level 1, 55% at level 10 and 65% at level 15.

On a bite, two things happen:
1. **Stagger:** the target loses its next attack. Staggering a boss also **breaks the big attack it's winding up**, which is Lure's strongest use.
2. **Lured (9 seconds, about 3 rounds):** a defence penalty of 5 × the skill's power. That raises **everyone's** chance to hit it by the same number of percentage points, not just yours, so the whole party gains.

On a miss, nothing happens and the cooldown is still spent.

## How it grows
| Skill level | Power | Lured penalty | Extra |
|---|---|---|---|
| 1 | 1.0 | +5% to hit | — |
| 5 | 1.65 | +8% | **A second living foe** is also staggered and Lured (+6%) |
| 10 | 2.65 | +13% | **Your companions** each get a free attack on the target |
| 15 | 4.15 | +20% | **Sickened (12 s)**, living targets only: −6 to its damage and about 16 poison per round, roughly 64 in all |

## Things worth knowing
- **The second foe at level 5 can be anyone in the room.** Since area effects started reaching the whole room (D-416), Lure picks the second foe the same way area attacks do: anyone you can see except your party, your friends and idle townsfolk. That has three consequences:
  - It can be an **idle monster** that wasn't in the fight. Since that change a debuff starts a fight, so Lure pulls it in.
  - It can be **another climber** standing in the room, which starts a PvP fight with them.
  - It takes the **first one in room order**, not a foe that's already fighting you.

  The level-5 milestone text ("another living foe in the room goes for the scraps") technically allows all of this. Pulling in a random bystander is probably not what it was meant to do, though, and I'd call it a bug.
- **The level-10 milestone does nothing for a Warrior.** Nothing Warrior learns, and no race or lineage special, gives a companion. For Warrior, Barbarian, Berserker and probably Skald it's a dead milestone; it only pays off for Beastmaster, Ranger and Spiritwalker.
- **Lured feeds later skills.** Bring It Down (level 80) counts a Lured target as rattled prey from its own level 5.
- **Sickened is the real damage.** Before level 15 Lure deals no damage at all. At 15 its poison is a sizeable chunk on living targets. Bloodless and undead foes never get it, since it only applies to living targets.
