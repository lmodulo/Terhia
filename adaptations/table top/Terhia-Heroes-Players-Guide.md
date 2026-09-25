# Terhia: Heroes — Player's Guide

Draft v0.1 (25 September 2026). Built against Terhia-Canon v1.2. Sister ruleset to *Terhia: Chronicle* (Player's Manual v0.3): same world, same twelve schools, same four ranks, same six attributes; a different player promise. Where a rule below reuses a Chronicle rule it says so; where it departs, it departs on purpose and the departure is listed in §17 for ratification.

**Scope.** Player-facing rules only: what a player character is, resolution, attributes and their limits, the turn, movement on a gridded table, damage and criticals, boons and hexes, Strain / Overdraw / Marks, readings, joins, advancement, the twelve classes with their spells and skills, gear and relic interfaces, and the character sheet. Not here: opposition and Grand Beast stat blocks, Mob rules, relic generation, contracts, encounter budgets, calibration (Game Master's Guide — see the handoff file).

**Status.** Nothing in this file is canon. Every rule that touches a canon sentence is listed in §17 with the reading taken.

**Notation.** RD = Rank Die. RB = Rank Bonus. Key = the modifier of the class's key attribute. Squares are the unit of distance (§6). "Burst 2" = every square within 2 of a point. "N rounds" counts down at the end of the affected creature's turn; "1 round" = until the end of its next turn.

---

## 0. The two games

| | **Terhia: Chronicle** | **Terhia: Heroes** (this file) |
|:--|:--|:--|
| Player promise | You are practitioners whose power costs the body; no one holds the whole picture | You are exceptional practitioners taking contracts, hunting Grand Beasts, and confronting region-scale threats |
| What Strain means | The cost engine; every use edges toward permanent deterioration | The fuel that lets you use your class repeatedly; it refreshes |
| What Marks mean | Accumulate with use | Only when you deliberately push past your limits |
| Readings | Private, partial information | Read a weakness → exploit it |
| Joins | Two hard checks | Cross-class combination attacks |
| Grand Beasts | Problems that change type by tier | Bosses that change type by tier, and can be fought |
| Advancement | Four ranks | Sixteen levels, four per rank |

Both games use the same canon. A Chronicle character and a Heroes character are the same kind of person; the Heroes character is the one the harbor keeper sends for when something under the harbor wakes up.

---

## 1. The player character

### 1.1 One school

Everyone in Terhia is born with exactly one school, latent; training makes a practitioner. A player character is a trained practitioner of unusual talent. The class name is the Common Tongue registry term for the school; practitioners use the working terms (a Necromancer says "reader"; a Sorcerer "runs the overlay").

| Class | School | Type | Key attribute | Damage kind | Role tags |
|:--|:--|:--|:--|:--|:--|
| **Elementalist** | Elemental (Saelura, red) | Magic | Attunement | Fire / Frost / Storm / Stone | Damage, Control, Battlefield |
| **Sorcerer** | Arcane (Orrivane, purple) | Magic | Reckoning | Force | Control, Damage, Battlefield |
| **Apothecarist** | Nature (Threnis, green) | Magic | Attunement | Physical (via Companion / soma) | Heal, Boon, Summon |
| **Necromancer** | Necrotic (Velquor, black) | Magic | Attunement | Necrotic | Damage, Hex, Control |
| **Apostle** | Divine (Namaris, gold) | Magic | Standing | Sacred | Boon, Heal, Control |
| **Hexblade** | Sword/Shield | Martial | Poise | Physical | Defender, Control |
| **Vanguard** | Glaive | Martial | Poise | Physical | Damage, Control (reach) |
| **Warden** | Longbow + dagger | Martial | Poise | Physical | Ranged damage, Hex, Utility |
| **Paladin** | Hammer | Martial | Frame | Physical | Damage, Battlefield (breach) |
| **Berserker** | Ax | Martial | Frame | Physical | Damage (escalating) |
| **Artificer** | Alchemy, Light Arts | Alchemy | Reckoning | Fire / Physical (devices) | Control, Summon, Boon |
| **Warlock** | Alchemy, Dark Arts | Alchemy | Reckoning | Toxin | Hex, Control, Summon |

**Magic classes** cast **spells**. **Martial and Alchemy classes** use **skills**. The rules treat them identically; the words differ because the world's registries do.

### 1.2 Ranks and levels

Four in-world ranks; sixteen character levels, four per rank. Rank is the large power jump: it sets the Rank Bonus, the Rank Die, the Strain Capacity, and the form of the class's Core ability. Levels within a rank supply talents, abilities, Vigor, and attribute increases.

| Rank | Levels | Rank Bonus (RB) | Rank Die (RD) | Strain Capacity | Attribute cap | Marks floor | Fantasy |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:--|
| **Novice** | 1–4 | +2 | d6 | 6 | 18 | 0 | Talented adventurer — "I can fight" |
| **Adept** | 5–8 | +4 | d8 | 9 | 20 | 1 | Established hero — "I can do something no ordinary person can" |
| **Master** | 9–12 | +6 | d10 | 12 | 22 | 2 | Regional legend — "I decide how this battle happens" |
| **Guru** | 13–16 | +8 | d12 | 16 | 22 | 3 | World-class practitioner — "I decide what happens to this place" |

Strain Capacity adds the Reserve modifier. Marks floor: reaching a rank raises your Marks to at least the floor (canon: cost first appears on the file at Adept; every Guru has a cost file).

### 1.3 The design test

Every ability in §14 is written to one rule: **each rank changes what the ability is for, not how large its number is.** Novice targets a creature. Adept controls the creature. Master changes the battlefield. Guru changes the scenario. The canon's scale ladder — Personal → Circle → Line → Ground — is the same ladder, and on the table it reads: one square → Burst 2–3 → a Line or Wall → the whole map.

---

## 2. Resolution

**The roll:** d20 + attribute modifier + Rank Bonus, against a target number.

- **Attack rolls** target a defense: **Guard** (anything you dodge, block, or take on armor: weapons, projectiles, force, elemental blasts) or **Ward** (anything you resist from the inside: poison, fear, the boundary, a grip on your body, a word that lands). Each ability says which.
- **Checks** target a Difficulty. You add the Rank Bonus to a check when it falls inside your school's competence (the GM rules; the class entry gives examples).
- **Advantage / Disadvantage:** roll two d20 and keep the higher / lower. One instance of each cancels the other; multiple instances don't stack.
- **Natural 20:** the attack hits and is a critical (§7.3); the check succeeds. **Natural 1:** the attack misses; the check fails; any Strain spent is spent.
- **Area attacks:** roll **once** and compare the result to each target's defense. Targets you hit take the full effect; targets you miss take half damage and no rider, unless the ability says otherwise.
- **Contested rolls:** both roll; the higher wins; ties go to the defender.

| Difficulty | Number |
|:--|:-:|
| Easy | 10 |
| Moderate | 13 |
| Hard | 16 |
| Severe | 19 |
| Master-grade | 22 |
| Guru-grade | 26 |
| Beyond one hand | 30 — reachable only by a Join (§12) |

---

## 3. Attributes

Six attributes, shared with Chronicle. Scores run 8–22. Modifier = (score − 10) ÷ 2, rounded down.

| Score | 8–9 | 10–11 | 12–13 | 14–15 | 16–17 | 18–19 | 20–21 | 22 |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Modifier | −1 | 0 | +1 | +2 | +3 | +4 | +5 | +6 |

| Attribute | Governs | Keyed classes |
|:--|:--|:--|
| **Frame** | Force, weight, carrying, holding ground, breaking things, shoving | Paladin, Berserker |
| **Poise** | Reach, timing, precision, balance, stealth, initiative, Guard | Hexblade, Vanguard, Warden |
| **Reserve** | The body's depth: Vigor, Strain Capacity, Ward; resisting poison, pain, exhaustion | every class (capacity) |
| **Reckoning** | Measuring, reading structure, counting, memory, craft, letters, seals | Sorcerer, Artificer, Warlock |
| **Attunement** | Feeling what answers: the elements, the living, the dead; animals; noticing by relation | Elementalist, Apothecarist, Necromancer |
| **Standing** | Presence and voice as they land on others; command; being believed; the calling-back | Apostle |

**Defaults.** Assign the array **16, 14, 13, 12, 10, 8** in any order (the Chronicle array is 15/14/13/12/10/8; heroes start a point higher). Or roll 4d6 six times, drop the lowest die each time, assign; if the six modifiers total less than +5, roll again.

**Maximums.** Novice 18; Adept 20; Master 22; Guru 22. A score of 22 (+6) exceeds the ordinary human range; it is available only at Master and above.

**Increases.** At levels 4, 8, 12, and 16: +2 to one attribute, or +1 to two, within the cap for your rank.

**Notice** (perceiving what is there): Reckoning or Attunement, the player's choice each time; the GM describes the result in the register of the attribute used — measured or felt.

---

## 4. Derived values

| Value | Formula |
|:--|:--|
| **Vigor** (level 1) | Martial 12 · Alchemy 10 · Magic 8, + Reserve modifier |
| **Vigor** (each level after 1st) | Martial +7 · Alchemy +6 · Magic +5, + Reserve modifier |
| **Guard** | 10 + Poise modifier + Armor + Shield + Rank Bonus (+1 for Martial classes) |
| **Ward** | 10 + Reserve modifier + Rank Bonus (+1 for Magic classes) |
| **Alchemy classes** | +1 to Guard or Ward, chosen at creation |
| **Speed** | 6 squares (heavy armor −1) |
| **Initiative** | d20 + Poise modifier; Martial classes add the Rank Bonus |
| **Strain** | Capacity by rank (§1.2) + Reserve modifier; current / Capacity |
| **Marks** | 0–10; never decrease (§9) |
| **Crit Chance** | 20 (the d20 result that crits; talents and relics widen it) |
| **Crit Rate** | ×2 (the multiplier on damage dice; talents and relics raise it) |
| **Reactions** | 1 per round · **Quick Actions** 1 per turn |

**Armor:** none 0 · light +1 · medium +2 · heavy +3 (heavy: Speed −1, Disadvantage on stealth). **Shield:** +2 for the Hexblade (trained), +1 for anyone else who carries one; a Necromancer cannot (bare-handed, §14). Each class lists its armor allowance; wearing heavier than allowed: Disadvantage on every attack roll and spell.

**Weapons.** Everyone can use simple weapons (dagger d4, staff d6, club d6, hand-ax d6, sling d4 range 12) without the Rank Bonus. Martial classes use their school's weapon with the Rank Bonus: longsword d8 · glaive d10 (reach 2) · longbow d8 (range 24; Disadvantage against adjacent targets — the Warden's dagger covers that distance) · maul d12 (two-handed) · great-ax d12 (two-handed). Thrown flasks and vials: range 8, keyed to Reckoning, with the Rank Bonus.

---

## 5. The turn

Each round, in Initiative order, a creature takes a turn:

**Move** (up to Speed) **+ Action + Quick Action + Reaction** (the Reaction is spent on anyone's turn, once per round).

| Action | Use it for |
|:--|:--|
| **Strike** | One weapon attack (Martial) or your class Core ability (§14). Martial Strikes scale: Novice 1 attack (weapon + Key); Adept 1 attack (weapon + RD + Key); Master 2 attacks (each weapon + RD + Key); Guru 2 attacks (each weapon + 2 RD + Key) |
| **Cast / Use** | Any ability listed as an Action |
| **Dash** | Move again (Speed) |
| **Disengage** | Your movement this turn doesn't provoke Punishes |
| **Shove** | Frame vs Guard: push 1 square (2 if Frame modifier is +3 or more) or knock Prone |
| **Help** | Grant an adjacent ally Advantage on their next attack or check |
| **Ready** | Name a trigger and an Action; it happens as your Reaction when the trigger occurs |
| **Read** | Only if you have no Quick Action left; normally a Quick Action (§11) |

**Quick Action:** anything listed as Quick; Read; drink or apply a draught; drop Prone; pick up an item; the Second Wind (§9). **Reaction:** anything listed as a Reaction; Punish (§6.4); a Readied action; a Join partner's half (§12).

**Sustained.** An ability marked Sustained continues while you keep it. Sustaining costs the listed upkeep at the start of each of your turns (usually your Quick Action, sometimes Strain). You can sustain one effect at a time. A sustained effect ends when you drop it, when its upkeep isn't paid, when you are Stunned or Downed, or when its duration runs out.

**Ability format in §14:** **Name** · Type · Action type · Strain cost · Range / Area · Effect. Types: Damage, Control, Heal, Boon, Hex, Defense, Utility, Summon, Battlefield.

---

## 6. Movement and the table

The game is played on a grid of 1-inch squares with figurines. One square is one pace (five feet in the old measure). A Medium creature occupies one square; Large 2×2; Huge 3×3; a Grand Beast avatar 4×4 or larger; a Mob is a block of squares (GM Guide).

### 6.1 Moving

- **Speed 6.** Move up to Speed on your Move; Dash for another Speed.
- **Diagonals count 1.** (Table option: 1-2-1 alternating; the GM chooses at the campaign's start.)
- **Difficult terrain** (rubble, mud, brush, shallow water, ice, a burning square's edge): 2 per square. **Climbing and swimming:** 2 per square; a hard climb needs Frame DC 13; a Frost or Stone Wall is a hard climb.
- **Jumping:** long jump with a running start = Frame modifier + 2 squares (minimum 1); standing, half. High jump 1 square; 2 with Frame 16+.
- **Falling:** 1d6 per full 2 squares fallen (maximum 20d6); you land Prone. Forced movement off a ledge counts.
- **Allies' squares** can be passed through at 2 per square, never ended in. **Enemies' squares** cannot be entered unless the enemy is two size categories smaller or larger.
- **Standing up from Prone** costs half your Speed.

### 6.2 Range and area

| Term | Meaning |
|:--|:--|
| **Reach 1 / 2** | Adjacent squares (including diagonals) / within 2 squares (glaive) |
| **Range 8 / 12 / 24** | Thrown / most spells / longbow; ranged attacks against an adjacent target have Disadvantage |
| **Burst n** | Every square within n of a chosen point, the point included (Burst 1 = 3×3; Burst 2 = 5×5; Burst 3 = 7×7) |
| **Cone n** | From your square: n long, widening to n wide at the far end |
| **Line n** | n squares long, 1 wide, starting adjacent to you |
| **Wall n** | n contiguous squares of your choice within range, 2 squares high, standing until removed |
| **Ground** | The whole encounter map, as the GM defines it at the start of the fight |

Canon's scale ladder on the table: **Personal** = one target · **Circle** = Burst 2–3 · **Line** = Line 12 / Wall 6+ · **Ground** = the map.

### 6.3 Position

- **Cover.** Half cover (a low wall, a figurine between): +2 Guard against attacks that cross it and +2 Ward against area effects that begin beyond it. Three-quarters cover (an arrow slit, a doorway edge): +5. Full cover: not targetable; area effects deal half damage through it.
- **High ground.** A ranged attack from at least 2 squares above its target: +2.
- **Flanking.** A melee attack against a creature that has one of your allies adjacent to it on the opposite side: +2.
- **Hidden.** Enemies don't know your square; your attacks from Hidden have Advantage; you are revealed when you attack (unless the ability says otherwise), when you end your turn without cover or concealment, or when an enemy's Notice check beats your Poise + RB + 10.
- **Elevation and flight.** Flying creatures ignore ground terrain; Rooted, Grabbed, Prone, and Tempest-class effects bring them down (fall damage applies).

### 6.4 Engagement

- **Threatened squares.** Every square within your reach.
- **Punish.** Reaction: when an enemy leaves a square you threaten without Disengaging, make one weapon attack against it (a Martial Strike, single attack; Magic and Alchemy classes use a simple weapon). Forced movement never provokes.
- **Pushing.** A push moves the target the stated number of squares directly away (or as the ability says). A pushed creature that hits a wall, an object, or another creature stops and takes 1d6 per square of push it lost (maximum 3d6); the creature it hit takes the same. A push into a hazard square applies the hazard.
- **Hazard squares** (set by the GM at the start of the encounter): fire (Burning 1 on entering or ending a turn there), deep water (swim; heavy armor sinks: Frame DC 13 per turn), a pit or drop (fall), unstable footing (Poise DC 13 or Prone).
- **Destructible terrain.** Walls, doors, and bridges have Vigor and a break threshold; Paladin and Sorcerer abilities address them directly. Values are in the GM Guide.

---

## 7. Damage

### 7.1 Base damage

- **Weapon damage** = the weapon die + Key modifier, scaled by rank as in §5 (Strike).
- **Spell and skill damage** = the number of Rank Dice the ability lists + Key modifier. The modifier is added once per hit, however many dice.
- **Rank Die:** Novice d6 · Adept d8 · Master d10 · Guru d12. Every ability written in RD scales itself when you rank up.
- **Damage kinds:** Physical (cut, pierce, crush — the sub-kind only matters to relics and resistances), Fire, Frost, Storm, Stone, Force, Toxin, Necrotic, Sacred.
- **Resistance:** the target takes half of that kind. **Vulnerability:** the target takes half again as much (×1.5, rounded down). **Immunity:** none.
- **Temporary Vigor** (Fortified) is lost first and cannot be restored by healing.
- **Objects and structures:** Vigor by material (GM Guide); crush damage and Paladin Strikes deal double to them.

### 7.2 Applying damage

Damage reduces current Vigor. At 0 Vigor a creature is **Downed** (§10.3). Damage below 0 is not tracked except for the Berserker's *The Gate Opens All the Way* and for Mobs.

### 7.3 Criticals

- **Crit Chance** is the d20 range that crits on an attack roll. Default: 20 only (5%). "Crit Chance 19–20" = 10%; "18–20" = 15%. Widened by talents, relics, and specific abilities (a Warden's Quarry, a read Seam). The maximum is 17–20.
- **Crit Rate** is what a crit does to the damage dice. Default ×2: roll the damage dice twice, add the modifier once. Crit Rate ×3: roll three times. Flat bonuses (+2, +Gate) are never multiplied.
- A critical hit that applies a numbered hex (Burning, Bleeding, Poisoned) applies **one extra stack**.
- A critical hit against a creature with a listed weakness (a read Seam, a compensating forelimb) may also trigger the GM's listed critical consequence — a limb lamed, a shield split, a construct's plate sprung.
- Area attacks crit only against the target the natural 20 was compared to first; the GM chooses the nearest if unclear. Damage over time never crits.

### 7.4 Damage over time

Three numbered hexes deal damage at the start of the affected creature's turn. Stacks are written Burning 3, Poisoned 2, etc. Each has a maximum of **5 stacks**; further applications are lost.

| Hex | Damage per stack, per turn | Decay | Removed by |
|:--|:--|:--|:--|
| **Burning (n)** | 3 Fire | −1 stack after each tick | Spending a Move to drop and roll (ends it); entering deep water; any Frost effect on the target |
| **Bleeding (n)** | 2 Physical | none | Any Vigor restoration; a Quick Action to bind (Reckoning DC 12, by the bleeder or an adjacent ally) |
| **Poisoned (n)** | 1 Toxin, and **−n Ward** while it lasts | none | An antidote or a cure ability; a full Rest |

Burning spreads: a Burning creature that ends its turn adjacent to dry brush or another Burning-capable hazard square ignites it. Poisoned's Ward penalty is the Warlock's snowball: the more poison, the easier the next dose lands.

### 7.5 Healing

Vigor restoration comes from abilities (Apothecarist, Apostle, Warlock draughts, Artificer maintenance for constructs), from the Second Wind (§9.4), and from rest (§10). Healing removes Bleeding. Healing never restores temporary Vigor and never removes Marks.

---

## 8. Boons and hexes

Boons are conditions that help; hexes are conditions that hinder. Support classes (Apostle, Apothecarist, Warlock, Artificer) grant boons to allies; every class inflicts some hex. A named condition applied twice doesn't stack — take the longer duration. Numbered conditions (Burning 2, Fortified 6) stack or replace as their entry says.

### 8.1 Boons

| Boon | Effect |
|:--|:--|
| **Bolstered** | +2 on attack rolls |
| **Guarded** | +2 Guard |
| **Warded** | +2 Ward |
| **Fortified (n)** | n temporary Vigor. Doesn't stack; take the higher |
| **Regenerating (n)** | Regain n Vigor at the start of your turn |
| **Hastened** | Speed +2; you may Dash as a Quick Action |
| **Inspired** | Advantage on your next attack roll or check, then it ends |
| **Empowered** | +1 RD damage on your next hit, then it ends |
| **Resolute** | Immune to Frightened and Dazed; can't be moved against your will by a push of 1 |
| **Hidden** | See §6.3 |
| **Set** | Can't be pushed or knocked Prone; ends when you move |

### 8.2 Hexes

| Hex | Effect |
|:--|:--|
| **Burning / Bleeding / Poisoned (n)** | See §7.4 |
| **Weakened** | −2 damage on every hit you deal; Disadvantage on Frame checks |
| **Exposed** | Attacks against you gain +2; you take +2 damage from every hit |
| **Slowed** | Speed halved; you can't Dash |
| **Rooted** | Speed 0; you can still act; you can be moved by others |
| **Dazed** | No Quick Action, no Reaction |
| **Stunned** | No Move, Action, Quick, or Reaction; attacks against you have Advantage. Never lasts longer than 1 round from a single application; an Elite or Boss gets a Ward check (DC = the applier's attack roll) at the end of its turn to shake it early |
| **Prone** | Melee attacks against you have Advantage; ranged attacks against you have Disadvantage; your attacks have Disadvantage; standing costs half your Speed |
| **Grabbed** | Rooted, and the grabber may move you when it moves. Escape: an Action, Frame or Poise vs the grabber's Guard |
| **Frightened** | Disadvantage on attacks while you can see the source; you can't willingly move closer to it |
| **Blinded** | Your attacks have Disadvantage; attacks against you have Advantage; you must guess the square of anything not adjacent |
| **Bound** (Hexblade) · **Quarry** (Warden) · **Sanctioned** (Apostle) · **Marked** (GM) | Class-specific; defined in the class entry |

### 8.3 Duration and removal

Unless an ability says otherwise: boons and hexes from an Action last **2 rounds**; from a Quick Action or Reaction **1 round**; from a Sustained ability, while sustained. A hex is removed by the entry's listed cure, by a Heal that says "remove hexes", or by a full Rest. Boons end when their duration ends or the recipient is Downed.

---

## 9. Strain, Overdraw, Push, and Marks

This is the largest departure from Chronicle. In Heroes, **Strain is what lets you do the cool thing repeatedly; Overdraw is what lets you do something outrageous.**

### 9.1 Strain

- Every class ability with a number after its action type costs that much Strain. Core abilities and Strikes cost 0.
- Strain refreshes to full at a **Breather** (§10.1). Nothing else drains it: not time, not damage.
- You cannot spend Strain you don't have — except by Overdraw.

### 9.2 Overdraw

When you use an ability you cannot afford, pay all the Strain you have (down to 0) and take **1 Mark**. The ability works. Overdraw once per turn.

### 9.3 Push

Once per round, after you make an attack roll or check with an ability and before its result is resolved, you may take **1 Mark** to do one of the following:

- **Maximize:** every damage die of this ability shows its maximum.
- **Reach:** add your Rank Die to the d20 roll.
- **Widen:** enlarge the area by 1 (Burst 2 → 3; Cone 6 → 7; Line 12 → 13) or double the range.
- **Refill** (once per encounter, on your own turn): Strain to full.

A Push is a permanent Mark. The player decides; the table remembers. This is the moment of "the harbor keeper sent for me."

### 9.4 Second Wind

Once per encounter, as a Quick Action: regain RD Strain and RD Vigor.

### 9.5 Marks and Stages

Marks are permanent. They never decrease — canon: cost stage is monotonic. Ranks set floors (§1.2). Every school's cost progression has four named stages (canon, Parts II–IV); the fourth is the End.

| Marks | Stage | Effect (all schools) |
|:-:|:--|:--|
| 3 | **Stage 1 — the tell** | The cost shows on you. Anyone who Reads you knows what you are and roughly what it has cost; −1 on checks to pass as anything else |
| 6 | **Stage 2 — the body pays** | Maximum Vigor −5 |
| 8 | **Stage 3 — the price compounds** | Strain Capacity −2 |
| 10 | **Stage 4 — the End** | The character's End scene is played (GM Guide); the character leaves play |

The stage names in each class entry are the canon names. What they look like is in the canon's Emotional Payload paragraphs; the GM uses them.

**Arithmetic of a career.** A Guru starts at 3 Marks. That is seven Pushes or Overdraws between the day the roll lists you and the End. Spend them on the days that deserve it.

---

## 10. Rest, recovery, Downed, and death

### 10.1 Breather

Ten minutes out of danger. Strain refreshes to full. Regain a quarter of your maximum Vigor (round up). Up to three Breathers between full Rests.

### 10.2 Full Rest

A night's sleep, or eight hours under shelter. All Vigor and Strain; every hex ends except those an entry says persist; Warlock doses and Artificer loadouts are prepared; Companions and familiars re-bond. Marks stay.

### 10.3 Downed

At 0 Vigor you fall Prone, unconscious, with a **Death Clock of 3**. At the start of each of your turns, and each time you take damage while Downed, the clock drops by 1. At 0 you are dead. An adjacent ally can **stabilize** you as a Quick Action (Attunement or Reckoning DC 10): the clock stops. Any Vigor restoration brings you up with that Vigor, still Prone.

### 10.4 Death

Death is permanent. Two Guru abilities and no others say otherwise: the Apostle's *Refuse Death* (lifespan transferred: it costs the Apostle a Mark) and the Necromancer's *Threshold* (a delay measured in breaths, not a return). Both are written in §14.

---

## 11. Readings

Every school reads the world in its own register. In Heroes a Reading is an action-enabling power: **read a weakness → exploit it**.

- **Read** · Quick Action · 0 Strain · a target within the listed range · once per round. The GM gives one true fact in the school's register (a load path; a compensating forelimb; who this creature will attack next; what the ground answers). 
- **Exploit.** Each class entry lists what its Reading unlocks. The exploit lasts until the end of your next turn unless stated. Announcing a read weakness to allies costs nothing.
- **What a reading cannot see** is still true in Heroes: a Sorcerer reads mass and load, not intent; an Apostle reads intent, not mass. A Grand Beast's vulnerability is written in one school's register and is complete only when two schools read it together — which is what Joins are for.

---

## 12. Joins

A Join is two practitioners of different schools acting as one. In Heroes, Joins are combination attacks.

**Procedure.** The initiator uses an Action and pays 2 Strain; the partner uses their Reaction and pays 2 Strain. Both must have the listed abilities and be within 12 squares of each other (or as listed). The initiator makes one attack roll with +2. A Join can be Pushed by one of the two, not both. A Join's effect replaces both component abilities for that turn.

| Join | Schools | Requires | Effect |
|:--|:--|:--|:--|
| **Storm Cage** | Arcane + Elemental | *Anchor* + *Elemental Lash* (Storm) | A fixed Burst 2 volume within 12 fills with lightning: 3 RD storm vs Ward to each creature inside, and the volume holds them (Rooted) for 2 rounds |
| **Second Breath** | Nature + Divine | *Cure* + *Steady* | A Downed ally within 6 rises with Vigor = 2 RD + both Keys, Resolute, and acts immediately as a Reaction |
| **Break the Line** | Hammer + Glaive | *Drive* + *Corridor* | The Paladin opens the formation (Line 3, Prone), the Vanguard turns it into a corridor: Strike vs every creature the Line touched; a Mob loses 2 RD Cohesion |
| **Last Witness** | Necrotic + Longbow | *Last Words* + *Loose* | The reader shows the archer where the dead saw their killer: the Warden's next Strike against that killer, anywhere within 48 squares, ignores cover, is a critical, and reveals the killer's position to the party |
| **Frost Wall** | Sword/Shield + Elemental | *Shield Wall* + *Wall* (Frost) | A Wall 6 of ice with the Hexblade's line inside it: full cover, and allies behind it gain Guarded; the wall lasts 3 rounds |
| **Alchemist's Fire** | Dark Arts + Elemental | *Vial* + *Kindle* | Burst 2 within 8: 2 RD fire + 2 RD toxin; Burning 2 and Poisoned 2 to all hit |
| **Called Fury** | Divine + Ax | *Command* + *Commit* | The Apostle names a target; the Berserker reaches it: move up to double Speed ignoring terrain and Strike with Advantage, +2 RD; the Gate rises 2 |
| **Hammerfall** | Arcane + Hammer | *Precision Force* (pull) + *Breach* | The Sorcerer pulls the target into the maul: Strike auto-hits, is a critical, and the target is Stunned 1 round |
| **Eye and Arrow** | Light Arts + Longbow | *Familiar* + *Loose* | The Warden shoots through the familiar's sight: a Strike at any target the familiar can see, no line of sight needed, with Advantage; the Warden stays Hidden |
| **Snarl** | Nature + Light Arts | *Wild Call* + *Adhesive* | Burst 2 within 8: living brush and adhesive: Rooted 2 rounds and 1 RD per turn while held |

Improvised Joins are adjudicated by the GM (handoff); a listed Join is always available to characters who hold the requirements.

---

## 13. Advancement and talents

### 13.1 Level table

| Level | Gains |
|:-:|:--|
| 1 | Class kit: Core (Novice form), Reading, signature resource, Novice abilities A and B, armor and weapon |
| 2 | Talent |
| 3 | Novice ability C |
| 4 | Attribute increase |
| **5** | **Adept:** RB +4, RD d8, Strain Capacity 9, Marks floor 1, Core (Adept form), Adept ability A |
| 6 | Talent |
| 7 | Adept ability B |
| 8 | Attribute increase |
| **9** | **Master:** RB +6, RD d10, Strain Capacity 12, Marks floor 2, Core (Master form), Master ability A |
| 10 | Talent |
| 11 | Master ability B |
| 12 | Attribute increase |
| **13** | **Guru:** RB +8, RD d12, Strain Capacity 16, Marks floor 3, Core (Guru form), Guru ability A |
| 14 | Talent |
| 15 | Guru ability B |
| 16 | Attribute increase; signature resource maximum +1 |

Vigor increases at every level (§4). Rank-up is an in-world event: a board, a roll, a Circle's recognition, or nobody's recognition at all; the GM Guide covers what the registries make of it.

### 13.2 Talents

Choose one at levels 2, 6, 10, and 14. Each may be taken once.

| Talent | Effect |
|:--|:--|
| **Keen** | Crit Chance 19–20 with your Strike and Core |
| **Brutal** (Master+) | Crit Rate ×3 with your Strike and Core |
| **Tough** | +2 Vigor per level, retroactive |
| **Fleet** | Speed +1; once per encounter Dash as a Quick Action |
| **Deep Reserve** | Strain Capacity +2 |
| **Second Reaction** | Once per encounter, take a second Reaction in a round |
| **Steady Hand** | No Disadvantage on ranged attacks against adjacent targets; no Disadvantage from Prone on your attacks |
| **Sure** | +1 Guard or +1 Ward |
| **Field Hand** | Stabilize and bind as free actions on your turn; your Breathers restore a third of maximum Vigor instead of a quarter |
| **Trade** | Name a trade, tongue, or craft: add your Rank Bonus to its checks |

---

## 14. The twelve classes

Each entry gives: the fantasy; key attribute, armor, Vigor type; the **signature resource** (the little game only this class plays); the **Core** (the 0-Strain ability that changes form at every rank); the **Reading** and its exploit; the ability list by rank (Novice A/B/C, Adept A/B, Master A/B, Guru A/B, gained per the level table); and the four canon cost stages. Damage entries add the Key modifier once per hit unless noted.

Every ability answers three questions: what do I do every round (the Core and the resource); what makes me unlike every other class (the resource and the Reading); what happens at the next rank that the table will remember (the Core's next form and the Guru abilities).

---

### 14.1 Elementalist — Elemental (Saelura)

**Fantasy.** Battlefield elemental controller. Novice throws the element; Adept shapes what it does to the target; Master shapes the battlefield; Guru changes rivers, streets, and weather.
**Key** Attunement · **Armor** light · **Vigor** Magic · simple weapons.

**Elements.** Every Elemental spell chooses an element when cast: **Fire**, **Frost** (water and ice), **Storm** (air and lightning), **Stone** (earth). Damage kind follows the element.

**Element riders** (from Adept; applied on a hit):

| Element | Adept | Master | Guru |
|:--|:--|:--|:--|
| Fire | Burning 1 | Burning 2 | Burning 3 |
| Frost | Slowed 1 round | Slowed, and no Reactions 1 round | Slowed 2 rounds, no Reactions |
| Storm | Push 1 | Push 2 | Push 3 |
| Stone | Rooted 1 round | Rooted 1 round and Prone | Rooted 2 rounds and Prone |

**Signature resource — Momentum.** Each time you cast an Elemental spell of the same element as your previous Elemental spell this encounter, gain 1 Momentum (maximum 3; 4 at level 16). When you cast, you may spend all your Momentum: +1 RD damage per point, or enlarge the area by 1 per 2 points. Casting a different element resets Momentum to 0.

**Core — the Kindle line.**
- **Novice · Kindle** · Damage · Action · 0 · range 12, one target vs Guard · 1 RD + Key of the chosen element.
- **Adept · Elemental Lash** · 2 RD + Key; the element's rider on a hit.
- **Master · Elemental Sweep** · Burst 2 on a point within 12, or Cone 6, or Line 12 · 3 RD + Key, half on a miss; riders on every hit. Fire is a fire front; Frost a wave; Stone an eruption; Storm throws the group.
- **Guru · Cataclysm** · Battlefield · Action · 5 · Ground · Sustained (upkeep: 2 Strain). Choose a shape each round you sustain it: **Inferno** — Burst 4 within 24: 4 RD fire, Burning 3; the squares keep burning (entering one: Burning 1). **Flood** — Wall 24, three squares wide, moving 6 per round: 4 RD frost, push 3, the ground becomes difficult terrain and stays so. **Quake** — Burst 4: 4 RD stone, Prone; structures inside collapse; the area becomes rubble. **Tempest** — the whole map: ranged attacks against you have Disadvantage, flyers are grounded, each enemy in the open takes 2 RD storm at the start of each of your turns.

**Reading — Read the Answer** · Quick · 0 · a point or creature within 12: which element the ground answers here, and one weakness (a resistance, a vulnerability, a fault line). Exploit: your next spell of that element against that target has +2 to hit and grants 1 extra Momentum.

**Spells.**
- **Novice A · Ember Shield** · Boon · Quick · 1 · self or an adjacent ally · Guarded 2 rounds; anyone who hits the bearer in melee takes 1 RD fire.
- **Novice B · Gust** · Control · Action · 1 · Cone 3 vs Guard · push 2; no damage; extinguishes Burning in the cone and clears smoke.
- **Novice C · Surge Step** · Utility · Quick · 1 · self · move 3 squares on your element without provoking. Fire: squares crossed burn this round (Burning 1 to anyone entering). Frost: squares crossed become difficult terrain. Storm: the move may cross a gap. Stone: the move may go through rubble as if clear.
- **Adept A · Wall** · Battlefield · Action · 3 · Wall 6 within 12, 3 rounds · Fire: crossing costs 2 RD fire and Burning 2. Frost: solid, full cover, 20 Vigor per square. Storm: a creature that ends its turn adjacent is pushed 2. Stone: solid, 30 Vigor per square; its top is high ground.
- **Adept B · Shape the Ground** · Control · Action · 2 · Burst 2 within 12, 3 rounds · Stone or Frost: difficult terrain, and creatures inside vs Guard are Slowed. Storm or Fire: clear the area of terrain, smoke, or brush.
- **Master A · Storm Call** · Damage · Action · 4 · Sustained (upkeep: Quick) · while sustained, at each upkeep a bolt strikes one creature within 12: 2 RD storm vs Guard, Dazed on a hit. Counts as a Storm cast for Momentum.
- **Master B · Eruption** · Damage / Control · Action · 3 · Burst 3 within 12, delayed: it happens at the start of your next turn and everyone can see the ground is wrong · 4 RD + Key stone (Prone) or fire (Burning 3), half on a miss.
- **Guru A · River Leaves Its Bank** · Battlefield · Action · 5 · Ground · a body of water, a lava stream, a slope of scree: a Wall 24 that moves 6 squares per round for 3 rounds; anything in its path takes 4 RD and is carried with it; the terrain is permanently changed.
- **Guru B · Harbor Kept** · Boon / Battlefield · Action · 5 · Ground · a sustained work: a harbor kept ice-free, a fire held off a town, an aquifer held raised. It persists as long as you sustain it, in or out of combat. Each full day of sustaining is 1 Mark (canon: sustained works draw cost after casting ends).

**Cost stages.** Fatigue → Muscle failure → Organ strain → Collapse.

---

### 14.2 Sorcerer — Arcane (Orrivane)

**Fantasy.** Reality engineer. Novice moves things with force and sees structure; Adept applies force with precision and predicts; Master edits whole encounters; Guru edits time and gravity. Canon's standing rule: where a ruling on this class could go either way, the stronger reading is taken.
**Key** Reckoning · **Armor** light · **Vigor** Magic · simple weapons.

**Signature resource — Overlay.** Quick · 1 Strain · activate. The Overlay runs until the encounter ends or you are Stunned or Downed. While it runs, gain 1 **Overlay charge** at the start of each of your turns (maximum 3; Master 4; Guru 5). Spend charges: **1** = +1 to a Sorcerer spell attack roll or a Reckoning check (declare before rolling; any number of charges). **2** = *Predict* (Reaction): an attack against you or an ally within 6 is rolled with Disadvantage. **3** = required to cast a Guru edit. Canon: the full overlay is Master technique; below Master the class runs it partially — structural sight.

**Core — the Force line.**
- **Novice · Force Bolt** · Damage · Action · 0 · range 12 vs Guard · 1 RD + Key force.
- **Adept · Precision Force** · 2 RD + Key; on a hit choose: push 2, pull 2, disarm (drops one held item), or trip (Prone).
- **Master · Force at Scale** · Burst 2 within 12 · 3 RD + Key force, half on a miss; every creature hit is moved 2 squares in a direction you choose for each of them. You arrange the encounter.
- **Guru · Substrate Edit** · Battlefield · Action · 4 · 3 Overlay charges · Burst 3, placed exterior (you cannot be inside it) · Sustained (upkeep: Quick). Choose: **Slow Field** — time runs slow inside: creatures inside have Speed 1, no Reactions, one Action or Quick per turn; attacks into or out of it have Disadvantage; projectiles crossing it stop. **Gravity Well** — pinned: creatures inside are Rooted and Prone and take 3 RD force at the start of their turns; or lifted: creatures inside float 2 squares up, can't move, ranged attacks against them have Advantage; release them at will (fall damage). Edits hold only under attention: if you take damage of your level or more in one hit, Reckoning DC 13 or the edit ends.

**Reading — Read Structure** · Quick · 0 · one object, structure, or creature within 12: its Guard, Ward, current Vigor, and one load-bearing point. Exploit: your next spell or attack against it ignores cover and any Guard from armor.

**Spells.**
- **Novice A · Telekinetic Grip** · Control · Action · 2 · one creature within 12 vs Ward · Grabbed and Rooted; Sustained (upkeep: Quick); at each upkeep move it 2 squares (1 if Large) — into a hazard, off a ledge, into reach.
- **Novice B · Deflect** · Defense · Reaction · 1 · a ranged attack against you or an adjacent ally: the target's Guard +RD against it.
- **Novice C · Unseen Hand** · Utility · Quick · 0 · a light object within 12: open, pull, drop, trigger, carry.
- **Adept A · Anchor** · Boon / Control · Quick · 2 · one ally within 12 can't be moved or knocked Prone against their will for 3 rounds; or an object or a volume of air within 12 is fixed in place for 3 rounds (a beam caught, a door held, a cage for a Join).
- **Adept B · Momentum Theft** · Defense · Reaction · 2 · a projectile or a charging creature within 12: the projectile drops; the creature stops in its square and loses its next Move.
- **Master A · Shatter Point** · Battlefield · Action · 4 · a structure or construct within 12 that you have Read fails at the read point: a wall segment collapses (Line 6 of rubble; 4 RD to creatures adjacent; difficult terrain); a bridge span drops; a gate falls; a construct is Stunned 1 round and Exposed 2 rounds.
- **Master B · Total Perception** · Boon · Quick · 3 · Sustained (upkeep: Quick) · you and allies within 6 re-roll Initiative now with Advantage; attacks against you have Disadvantage; you may spend Overlay charges on allies' attack rolls within 6.
- **Guru A · Time Debt** · Control · Action · 5 · once per encounter · one creature within 12 vs Ward · it is pulled out of the sequence: it loses its next turn, and every ally may make a Reaction attack against it.
- **Guru B · Exterior Placement** · Utility · passive · while a Substrate Edit is sustained you may move its volume 3 squares at each upkeep, and Slow Field's Speed penalty doesn't apply to your allies (they act at your pace).

**Cost stages.** Headache → Tremor → Time-lag perception → Memory dissonance (the End: identity-time fracture).

---

### 14.3 Apothecarist — Nature (Threnis)

**Fantasy.** Shapeshifting life-master. Novice runs with an animal and mends; Adept cures, commands beasts, and borrows a soma; Master regenerates allies and lends somas; Guru takes an apex form and calls the ground's animals.
**Key** Attunement · **Armor** light · **Vigor** Magic · simple weapons (staff).

**Companion** (Novice). A bonded animal (wolf, hawk, lynx, boar, otter — a natural creature of the region): Vigor 3 × your level, Guard = your Guard, attacks with your attack bonus for 1 RD + 2 physical, Speed 8 (a hawk flies 12). Commanding it is a Quick Action; uncommanded it stays with you and defends. From Master it acts on your turn without a command. If it dies, a new bond forms after a full Rest. It uses its own figurine.

**Signature resource — Adaptations** (from Adept). Somas you can borrow: **Hawk** (see 24 squares in the dark; Advantage on Notice; +2 on ranged attacks) · **Wolf** (Speed +2; ignore difficult terrain; track by scent) · **Bear** (+2 on Frame checks; +1 RD on melee damage; Fortified RD) · **Serpent** (melee hits apply Poisoned 1; Advantage on Ward against toxin) · **Lizard** (Regenerating 2) · **Otter** (swim at Speed; hold breath ten minutes) · **Bat** (blindsense 6: Blinded doesn't affect you) · **Stag** (leap 4; +1 Guard). Adopt one: Quick · 1 Strain · it lasts until a Rest or you drop it. Active at once: Adept 1, Master 2, Guru 3.

**Core — the Mend line.**
- **Novice · Mend** · Heal · Action · 1 · touch · 1 RD + Key Vigor; removes Bleeding.
- **Adept · Cure** · touch, or within 6 delivered by your Companion · 2 RD + Key; remove one hex (Poisoned, Burning, Bleeding, Blinded, Slowed).
- **Master · Regenerate** · range 6 · 3 RD + Key; Regenerating RD for 3 rounds; remove all hexes.
- **Guru · Remake** · Action · 5 · touch · the target is restored to full Vigor, or a Downed ally rises at full Vigor, or a limb regrows, a permanent injury is undone. Used on someone at 0 Vigor it costs you 1 Mark: the body is borrowed from your own.

**Reading — Read the Living** · Quick · 0 · a creature within 6: its current Vigor, one hex or injury it carries, one bodily weakness (the forelimb compensating for an old fracture). Exploit: attacks by you or any ally who can hear you against that weakness crit on 19–20 until the end of your next turn.

**Spells.**
- **Novice A · Wild Call** · Damage / Control · Action · 1 · Burst 1 on a point within 12 vs Guard · small wildlife swarms: 1 RD + Key physical; creatures hit have Disadvantage on their next attack.
- **Novice B · Stabilize** · Heal · Quick · 0 · touch a Downed ally: the clock stops; they regain 1 Vigor at the start of their next turn.
- **Novice C · Hold Attention** · Control · Action · 1 · a beast within 12 vs Ward · for 1 round it can attack no one but you and moves toward you.
- **Adept A · Beast Command** · Control · Action · 3 · a natural creature of Adept tier or lower within 12 vs Ward · it obeys you for 3 rounds. Grand Beasts have Advantage on the Ward.
- **Adept B · Thicken Hide** · Boon · Quick · 2 · an ally within 6 · Fortified 2 RD, and they resist 2 physical damage from every hit, 3 rounds.
- **Master A · Share Soma** · Boon · Quick · 3 · touch an ally · one of your active Adaptations is theirs too for 3 rounds (Bear to the Paladin; Wolf to the Vanguard; Hawk to the Warden).
- **Master B · Channel Redirect** · Heal / Control · Action · 4 · touch · move up to 3 RD Vigor from one creature you touch (a willing ally, or a creature you or an ally have Grabbed) to another creature you touch, yourself included. Canon Master: redirects channels to manage life force.
- **Guru A · Apex Form** · Boon · Action · 5 · self · Sustained (upkeep: Quick), 5 rounds at most · every soma active at once; natural weapons 2 RD + Key; Speed 10; Regenerating 5; Large size. When it ends: Dazed 1 round.
- **Guru B · Command the Ground** · Summon / Battlefield · Action · 5 · Ground · the region's animals arrive over 2 rounds as a Mob under your orders (Cohesion 3 × RD); or the local flora seizes the field: Burst 4, enemies vs Ward are Grabbed at the start of each of their turns, 3 rounds.

**Cost stages.** Scar tissue → Sensory narrowing → Partial morphic blending → Species bleed.

---

### 14.4 Necromancer — Necrotic (Velquor)

**Fantasy.** Master of the death boundary. The school does not raise, animate, or command the dead — canon — and never will here. Novice senses death and residue; Adept reads recent crossings; Master weaponizes residue and interrogates scenes; Guru holds a crossing open.
**Key** Attunement · **Armor** light; no gloves, gauntlets, or shield (bare-handed practice) · **Vigor** Magic · simple weapons.

**Signature resource — Residue.** Gain 1 Residue whenever a creature dies within 6 squares of you (maximum 5). In a place of prior death the GM may start you with some. Spend it as listed. Residue doesn't persist past the scene.

**Core — the Boundary line.**
- **Novice · Chill of the Boundary** · Damage · Action · 0 · range 12 vs Ward · 1 RD + Key necrotic; the target regains no Vigor until the end of your next turn.
- **Adept · Boundary Touch** · 2 RD + Key; Weakened 1 round on a hit; delivered by touch it deals +1 RD.
- **Master · Residue Bloom** · spend 1 Residue · Burst 2 within 12 vs Ward · 3 RD + Key necrotic, half on a miss; creatures hit are Frightened 1 round — the boundary opens in front of them.
- **Guru · Threshold** · Control · Action · 5 · Sustained (upkeep: Quick), 3 rounds · one creature within 6 that is Downed or dies this round: you hold its crossing. **An ally** stands at 1 Vigor that cannot drop for 3 rounds; at the end it is Downed again unless healed above 1 — the delay measured in breaths. **An enemy** dies at the end of the third round no matter what; until then it takes 2 RD necrotic at the start of each of its turns and cannot regain Vigor.

**Reading — Read the Crossing** · Quick · 0 · a body or a place within 6: when it died, how, and the emotional register. Exploit: a creature within 12 that has killed something this encounter: you learn its current Vigor and which of its defenses is lower; your next spell against it has +2.

**Spells.**
- **Novice A · Grave Cold** · Control · Action · 1 · Burst 1 within 12 vs Ward · Slowed 1 round; if anything died in the area this scene, gain 1 Residue.
- **Novice B · Self-Grounding** · Defense · Quick · 1 · self · controlled pain: remove Frightened and Dazed from yourself; Resolute 2 rounds.
- **Novice C · Sense the Door** · Utility · Action · 0 · learn whether anything within 24 squares is at 0 Vigor or dying, with direction and distance.
- **Adept A · Last Words** · Utility · Action · 2 · touch a body dead less than a day: what it saw in its last three breaths; if it saw its killer, you can describe them. Enables *Last Witness*.
- **Adept B · Ward of Residue** · Boon · Quick · spend 1 Residue · an ally within 6 · Fortified 2 RD; while it lasts the first hex applied to them fails.
- **Master A · Residue Edge** · Boon / Hex · Quick · 3 · bare hand on an ally's weapon · for 3 rounds its hits deal +1 RD necrotic and apply Weakened.
- **Master B · Boundary Interrogation** · Utility · Action · 3 · a death scene within 12 in analytic detail: every crossing there, separated by age; who stood where; the instant consciousness was and was not.
- **Guru A · Open Door** · Damage / Control · Action · 3 Strain + 3 Residue · Burst 3 within 12 vs Ward · the boundary thins: 4 RD necrotic, Frightened 2 rounds; a creature at half Vigor or less that fails by 5 or more is Stunned 1 round.
- **Guru B · Stand in the Doorway** · Boon · Quick · 4 · 3 rounds · you and allies within 3 squares cannot be reduced below 1 Vigor by any single hit; the excess is lost.

**Cost stages.** Skin pallor → Death-residue sensation → Touch erosion → Boundary thinning.

---

### 14.5 Apostle — Divine (Namaris)

**Fantasy.** Champion and voice. Novice steadies and inspires; Adept commands and shields; Master sanctions enemies and performs miracles; Guru refuses death and rallies armies. The Apostle's healing is the will, not the flesh (the Apothecarist's); at Master it becomes miraculous, and at Guru it is paid in years.
**Key** Standing · **Armor** medium · **Vigor** Magic · simple weapons.

**Signature resource — Conviction.** Gain 1 Conviction whenever an Apostle boon or Vigor restoration you grant lands on an ally (maximum 5). Spend as listed. Lost when the encounter ends.

**Core — the Word line.**
- **Novice · Rebuke** · Damage / Hex · Action · 0 · range 12 vs Ward · 1 RD + Key sacred; on a hit −2 on the target's next attack roll.
- **Adept · Command** · 2 RD + Key; on a hit, one word: **Halt** (Rooted 1 round), **Kneel** (Prone), **Drop** (drops a held item), **Back** (moves 2 away).
- **Master · Sanction** · 3 RD + Key; **Sanctioned** 3 rounds: every hit against the target deals +RD sacred, and any ally who hits it gains Bolstered 1 round.
- **Guru · Rally the Ground** · Boon / Battlefield · Action · 5 · Ground · Sustained (upkeep: Quick) · every ally on the map gains Bolstered, Guarded, Resolute, and Fortified 2 RD; allied Mobs gain +RD Cohesion; at each upkeep one ally within sight regains RD Vigor.

**Reading — Read the Heart** · Quick · 0 · a creature within 12: its resolve (steady, wavering, Frightened, loyal to whom) and what it wants this round. Exploit: your next Rebuke or Command against it has Advantage; against a Mob, you learn which part will break first.

**Spells.**
- **Novice A · Steady** · Boon · Quick · 1 · touch · Fortified 1 RD + Key; removes Frightened. Canon: touch steadies pain without treating the source.
- **Novice B · Inspire** · Boon · Quick · 1 · an ally within 12 · Inspired.
- **Novice C · Voice Carries** · Boon · Action · 1 · allies within 6 who can hear you · +2 Speed this round and Resolute 1 round.
- **Adept A · Encouragement Lands** · Boon · Action · 2 · Burst 3 around you · allies: Bolstered 2 rounds; gain 1 Conviction per ally affected, up to 3.
- **Adept B · Stand With Me** · Defense · Reaction · 2 · when an ally within 6 is hit: the damage is halved; you take the other half.
- **Master A · Miracle** · Heal · Action · 3 Strain + 3 Conviction · an ally within 12 · 3 RD + Key Vigor; remove all hexes; a Downed ally rises with that Vigor.
- **Master B · Boon of Endurance** · Boon · Action · 3 · up to 3 allies within 6 · Regenerating 3 and Resolute, 3 rounds.
- **Guru A · Refuse Death** · Heal · Action · 5 Strain + 1 Mark · once per encounter · a creature that died this encounter within 6 · it returns with half its maximum Vigor and no hexes. The Mark is the years transferred — canon: lifespan transference is the ability, not its side effect.
- **Guru B · Lent Years** · Heal · Quick · 1 Mark · an ally within 6 · full Vigor, now. The Assay counts it in years; so do you.

**Cost stages.** Minor aging → Frailty → Organ degradation → Lifespan compression.

---

### 14.6 Hexblade — Sword/Shield (Ethosless)

**Fantasy.** The defender and duelist. Novice shields allies and locks enemies; Adept binds, counters, intercepts; Master shuts down elite enemies and casters; Guru stands inside a formation and takes it apart.
**Key** Poise · **Armor** heavy, shield (+2 trained) · **Vigor** Martial · longsword d8.

**Signature resource — Parry.** Gain 1 Parry whenever an attack misses you, or whenever you Intercept (maximum 3; 4 at level 16). Spend: **1** = *Riposte* (Reaction, free): a Strike against an adjacent creature that just missed you. **2** = *Bind*: your next hit makes the target **Bound** — Rooted, and it can attack no one but you, until it spends an Action and beats your Guard with Frame or Poise. **3** = *Full Cover* (Reaction): an attack that has hit you or an adjacent ally misses instead.

**Core — the Cut and Cover line.**
- **Novice · Cut and Cover** · Attack · Action · 0 · Strike; hit or miss, you are Guarded until your next turn.
- **Adept · Shield Check** · Strike + RD; on a hit choose: Bound (as *Bind*, no Parry cost), or push 1 and Dazed 1 round.
- **Master · Complete Defense** · two Strikes; between them you may Intercept for free; each hit applies Exposed 1 round.
- **Guru · Kill the Corners** · Battlefield · Action · 5 · two Strikes with +2 RD each; then until your next turn every enemy that misses you triggers a free Riposte, and a Mob you are adjacent to loses RD Cohesion each round. The platoon standard as attrition of structure.

**Reading — Read the Weight** · Quick · 0 · a creature within 6: whom it will attack next and how. Exploit: your Reactions against that creature this round have Advantage, and your Intercept costs 0.

**Skills.**
- **Novice A · Intercept** · Defense · Reaction · 1 · when an ally within 2 squares is attacked: move up to 2 to be adjacent to them; the attack targets you instead. Gain 1 Parry.
- **Novice B · Shield Wall** · Boon · Quick · 1 · you and adjacent allies are Guarded while you don't move this round.
- **Novice C · Line Step** · Utility · Quick · 1 · move 2 without provoking; you may swap places with an adjacent ally.
- **Adept A · Lockdown** · Control · Action · 2 · Strike; hit: Rooted 2 rounds and no Reactions.
- **Adept B · Bulwark** · Defense · Quick · 2 · you may take two Reactions this round.
- **Master A · Counter-Practitioner** · Control · Reaction · 3 · when a creature within 6 begins any ability with a Strain cost: move up to your Speed and Strike; on a hit the ability fails and its Strain is spent. Canon: closes the distance inside a chant; takes flasks and bolts on the boss.
- **Master B · Shut Down** · Control · Action · 4 · Strike against an Elite or Boss; hit: Stunned 1 round; you gain 3 Parry.
- **Guru A · Fold the Line** · Battlefield · Action · 5 · Sustained (upkeep: Quick) · while you stand inside a Mob it cannot move, it loses 2 Cohesion at each upkeep, and every enemy adjacent to you is Dazed.
- **Guru B · The Guard That Will Not Drop** · Defense · Quick · 4 · 3 rounds · Guard +RD; attacks against allies adjacent to you have Disadvantage; you gain 1 Parry from every miss against any adjacent ally, not only you.

**Cost stages.** Scar accumulation → Residue mapping → Startle lock → The guard that will not drop.

---

### 14.7 Vanguard — Glaive (Rationalist)

**Fantasy.** Mobile reach fighter. Novice keeps spacing and controls the two-pace circle; Adept sweeps and denies; Master dominates melee geometry; Guru is moving area denial — priced by doctrine as terrain.
**Key** Poise · **Armor** medium · **Vigor** Martial · glaive d10, reach 2.

**Signature resource — Flow.** Gain 1 Flow whenever you hit a creature you did not hit with your previous attack this encounter (maximum 4; 5 at level 16). Spend: **1** = shift 2 squares without provoking, after any attack. **2** = one extra Strike as a Quick Action. **4** = *Sweep* at 0 Strain.

**Core — the Point line.**
- **Novice · Set the Point** · Attack · Action · 0 · Strike, reach 2; on a hit the target cannot move closer to you this round.
- **Adept · Sweep** · Strike + RD against every enemy within reach 2 in a half-circle (one roll compared to each Guard).
- **Master · Corridor** · move up to your Speed in a straight line; Strike + RD against every enemy within reach along it; each hit pushes the target 1 square to the side.
- **Guru · Moving Circle** · Battlefield · Action · 5 · Sustained (upkeep: Quick, 1 Strain) · the two-square circle is wherever you walk: enemies inside have Disadvantage; an enemy that enters it or starts its turn inside takes a Strike (no Reaction cost; once per creature per round); Mobs treat it as impassable; you may *Corridor* as your Move each round. A platoon engaging you is not outnumbered so much as unscheduled.

**Reading — Read the Flow** · Quick · 0 · where each enemy within 6 intends to move this round. Exploit: +2 on your attacks this round against any creature that moves.

**Skills.**
- **Novice A · Keep Spacing** · Control · Reaction · 1 · when an enemy moves adjacent to you: Strike it and push it 1.
- **Novice B · Hinge** · Utility · Quick · 1 · swap places with an adjacent ally, or slide an adjacent ally 1 square.
- **Novice C · Haft and Butt** · Attack · Action · 1 · two Strikes at −2 each against creatures in reach; one may push 1 instead of dealing damage.
- **Adept A · Trip Line** · Control · Action · 2 · Strike up to 2 creatures in reach; hits knock Prone.
- **Adept B · Deny** · Control · Quick · 2 · Sustained (upkeep: Quick) · three contiguous squares adjacent to you: the first enemy each round to enter them takes a Strike and stops there.
- **Master A · Break Formation** · Battlefield · Action · 4 · enter a Mob: Strike each adjacent creature (one roll); the Mob loses RD Cohesion and can bring no more than 2 attacks against you this round.
- **Master B · Anchor the Hinge** · Boon · Quick · 3 · 3 rounds · allies within 2 have +2 Guard against creatures you have hit this encounter; you gain 2 Flow.
- **Guru A · Unscheduled** · Control · Reaction · 5 · once per round: when any enemy within 4 squares ends its movement, *Corridor* to it and Strike; if it belongs to a Mob, the Mob loses RD Cohesion.
- **Guru B · Terrain** · Battlefield · passive · *Moving Circle*'s upkeep is the Quick only (no Strain); enemies inside it cannot Dash or Disengage.

**Cost stages.** Joint wear → Conditioning debt → Spinal compression → The seizing.

---

### 14.8 Warden — Longbow and dagger (Reverie)

**Fantasy.** Supernatural sniper and hunter. Novice shoots from concealment and reads ground; Adept marks prey and disappears; Master holds a zone by overwatch; Guru is unfindable artillery that stops a platoon by making the first ten deaths unanswerable.
**Key** Poise · **Armor** light · **Vigor** Martial · longbow d8 range 24; dagger d4 (covers the bow's blind distance: no Disadvantage against adjacent targets while you hold it).

**Signature resource — Quarry.** Quick · 0 · a creature you can see is your **Quarry**; +1 damage against it. At the start of each of your turns that it is still your Quarry, gain 1 **Insight** (maximum 3; 4 at level 16): **Insight 1** = +2 on attacks against it. **2** = Crit Chance 19–20 against it. **3** = your attacks ignore its cover and resistances. One Quarry at a time; changing resets Insight.

**Core — the Loose line.**
- **Novice · Loose** · Attack · Action · 0 · Strike with the bow.
- **Adept · Mark and Vanish** · Strike + RD; if you attacked from Hidden, you remain Hidden.
- **Master · Overwatch** · two Strikes; and (Sustained, upkeep: Quick) a zone Burst 3 within 24: the first enemy each round to enter it or act inside it takes a free Strike with Advantage — the shot arrives where the target will be.
- **Guru · Unanswerable** · Battlefield · Action · 5 · Sustained (upkeep: Quick) · you are Hidden and stay Hidden after attacks; finding you needs Notice DC 26. At each upkeep, three Strikes against three different targets within 24. A Mob that loses a member to you loses 2 Cohesion per death: fear does the arithmetic.

**Reading — Read the Ground** · Quick · 0 · the routes enemies within 24 will take, and the chokepoints. Exploit: Advantage on your first attack this round against any creature crossing a route you read.

**Skills.**
- **Novice A · Vanish** · Utility · Quick · 1 · with cover or concealment: you are Hidden (found by Notice ≥ 10 + Poise + RB).
- **Novice B · Pin** · Control · Action · 1 · Strike; hit: Rooted 1 round.
- **Novice C · Camp Scout** · Utility · passive · you cannot be surprised; when you have scouted, the party has +2 Initiative.
- **Adept A · Snare** · Control · Action · 2 · a square within 6, hidden until sprung: the first enemy to enter is Rooted 2 rounds and takes 2 RD.
- **Adept B · Track** · Utility · Action · 0 · find your Quarry across any biome, up to a day behind; Advantage on every check to follow it.
- **Master A · Bleeding Shot** · Damage / Hex · Action · 3 · Strike + RD; hit: Bleeding 3.
- **Master B · Hold the Pass** · Battlefield · Action · 4 · Sustained (upkeep: Quick) · a Line 12 you can see: each enemy that crosses it takes a free Strike; a Mob that crosses it loses RD Cohesion.
- **Guru A · The Unclosing Eye** · passive · immune to surprise and Blinded; Insight maximum 4; Crit Chance 19–20 against your Quarry from Insight 1.
- **Guru B · The First Ten Deaths** · Control · Action · 5 · against a Mob within 24: three Strikes, each a kill against a Mob member; the Mob then makes its Cohesion check (GM Guide) with Disadvantage or routs.

**Cost stages.** Draw-side deformation → Watch-broken sleep → Sensory tuning → The unclosing eye.

---

### 14.9 Paladin — Hammer (Devout)

**Fantasy.** Juggernaut and breacher. Novice smashes armor and doors; Adept strikes the seam and sends shockwaves; Master stops charges and breaks gates; Guru breaks formations and walls as demolition — a collapsing building that walks.
**Key** Frame · **Armor** heavy · **Vigor** Martial · maul d12, two-handed.

**Signature resource — Impact.** Gain 1 Impact whenever a Strike hits (maximum 3; 4 at level 16). Spend: **1** = that hit knocks Prone. **2** = *Armor Break*: the target is Exposed 2 rounds. **3** = *Shockwave* (Quick): Burst 1 around you, 2 RD crush vs Guard, Prone.

**Core — the Breach line.**
- **Novice · Breach** · Attack · Action · 0 · Strike; objects, constructs, and shields take double; a hit on a shield-bearer reduces its shield bonus by 1 until repaired.
- **Adept · Seam Strike** · Strike + RD; ignores Guard from armor and shield; hit: Exposed 1 round.
- **Master · Charge-Stopper** · two Strikes; and (Sustained, upkeep: Quick) *Set*: while you don't move, any creature that moves adjacent to you takes a Strike with Advantage; on a hit it stops and is Prone; a Mob that charges you loses RD Cohesion. Why the columns held anything flat.
- **Guru · Demolition** · Battlefield · Action · 5 · strike a wall, gate, or Mob: a structure fails as a structure — a Line 6 segment collapses into Burst 2 of rubble, 4 RD and Prone to everyone in it; a Mob fails as a structure — Cohesion −2 RD, every member within Burst 2 is Prone and takes 4 RD, and the Mob cannot act next round.

**Reading — Read the Seam** · Quick · 0 · an object, structure, or armored creature within 6: its load path. Exploit: your next Strike against it crits on 18–20.

**Skills.**
- **Novice A · Set** · Boon · Quick · 1 · until you move: Set, and +2 Guard.
- **Novice B · Drive** · Control · Action · 1 · Strike; hit: push 2 and you may follow.
- **Novice C · Split the Door** · Utility · Action · 0 · a barred door, a gap in a shield wall, a barricade: open it (Frame + RB vs the GM's DC; no roll for anything below Hard).
- **Adept A · Ground Slam** · Damage / Control · Action · 3 · Burst 1 around you vs Guard · 2 RD + Key crush, Prone; half on a miss.
- **Adept B · Bulwark Step** · Utility · Quick · 2 · move 2 ignoring difficult terrain and through Medium or smaller enemies, who are pushed 1 aside.
- **Master A · Break the Gate** · Battlefield · Action · 4 · a gate or wall segment within reach opens or collapses (read its load path first for the crit range); creatures behind it in Burst 2 take 3 RD and are Prone.
- **Master B · Column** · Boon · Quick · 3 · 3 rounds · allies within 2 gain Set and +1 Guard.
- **Guru A · Crack the Line** · Battlefield · Action · 5 · Line 6 from you: every enemy in it takes 3 RD, is pushed to one side (your choice each), and is Prone; the Line is a corridor for allies this round — no Punishes inside it.
- **Guru B · The Wall Fails** · Control · Reaction · 5 · once per encounter · when a Mob charges anyone within 12 it breaks against you instead: it stops, loses 3 RD Cohesion, and you *Shockwave* for free.

**Cost stages.** Micro-fracture conditioning → Bone remodeling → Deep-set brittleness → The settling.

---

### 14.10 Berserker — Ax (Reverie)

**Fantasy.** Escalating destructive fury. Novice commits harder than fear allows; Adept opens the gate and chains kills; Master sustains frenzy under direction; Guru opens the gate all the way and becomes a battlefield event with a bill afterward.
**Key** Frame · **Armor** medium · **Vigor** Martial · great-ax d12, two-handed.

**Signature resource — the Gate.** Quick · 1 Strain · open it. The Gate opens at 1 and rises by 1 at the start of each of your turns while open. **Maximum Gate:** Novice 2, Adept 3, Master 4, Guru 5. While open: melee damage +Gate; resist Gate damage from every hit; immune to Frightened; Ward −Gate; at Gate 3 or more you must Strike the nearest creature in reach at least once each turn unless you pass Standing DC 10 + Gate. **Closing:** a Quick and Standing DC 10 + Gate; automatic when no enemy is visible; an adjacent ally can spend an Action to call you back (automatic). When it closes: Dazed 1 round — post-gate collapse.

**Core — the Commit line.**
- **Novice · Commit** · Attack · Action · 0 · move 1, then Strike.
- **Adept · Momentum Kill** · Strike + RD; if the target drops to 0, immediately Strike another creature in reach; chain up to Gate times.
- **Master · Sustained Frenzy** · two Strikes; the Gate rises 1 extra this turn; an ally within 6 may spend a Quick to aim you: Advantage on both Strikes. A Master berserker is aimable.
- **Guru · The Gate Opens All the Way** · Battlefield · Action · 5 · once per encounter · Gate = 5. Until the end of the round you do not register wounds: you cannot be Downed (track Vigor below 0); every Strike that hits grants another Strike; you can't be Frightened, Stunned, Rooted, or Dazed. When nothing in reach stands, or the round ends: the bill — Prone, Dazed 1 round, and if your Vigor is 0 or less you are Downed with the clock at 1.

**Reading — Read Fear** · Quick · 0 · which creatures within 6 are Frightened, wavering, or resolved. Exploit: your Strikes against Frightened creatures crit on 19–20 this round.

**Skills.**
- **Novice A · Over the Barricade** · Utility · Move · 0 · your Move ignores difficult terrain and may leap 2; if you move 4 or more before a Strike this turn, +RD damage.
- **Novice B · Shrug** · Defense · Reaction · 1 · reduce one hit's damage by RD + Gate.
- **Novice C · First Over** · Boon · Quick · 1 · allies within 3 who move toward an enemy this round gain +2 Speed and Resolute 1 round.
- **Adept A · Roar** · Hex · Action · 2 · Burst 3 around you vs Ward · Frightened 1 round; a Mob loses 1 Cohesion.
- **Adept B · Reckless** · Boon / Hex · Quick · 0 · this turn your Strikes have Advantage; until your next turn attacks against you have Advantage.
- **Master A · Cleave** · Damage · Action · 4 · Strike against every adjacent enemy (one roll); each kill raises the Gate by 1, even past its maximum, to 5.
- **Master B · Hits That End Exchanges** · passive · Crit Rate ×3 while the Gate is open.
- **Guru A · The Calling-Back** · passive · allies within 6 can call you back as a Quick; called back after *The Gate Opens All the Way*, you are Dazed only, not Prone.
- **Guru B · Nothing in Reach Stands** · Battlefield · Action · 5 · against a Mob: *Cleave* every adjacent member, move up to your Speed, *Cleave* again; the Mob loses Cohesion equal to twice your kills.

**Cost stages.** Post-gate collapse → Frenzy amnesia → Affect blunting → Heart-burn.

---

### 14.11 Artificer — Alchemy, Light Arts (Rationalist)

**Fantasy.** Gadget combat engineer. Novice throws flasks and lays smoke; Adept builds conditional devices and a familiar; Master deploys turrets, constructs, and gadget systems; Guru integrates a household of familiars and equips a company from a wagon.
**Key** Reckoning · **Armor** medium · **Vigor** Alchemy · thrown flasks range 8; simple weapons.

**Signature resource — Loadout.** After a Rest, **prime** Devices from your known list: Novice 2, Adept 3, Master 4, Guru 6 primed. A primed Device is used once at 0 Strain. An unprimed or spent Device costs its listed Strain. Devices marked *(bench)* can only be made at a Rest.

**Core — the Flask line.**
- **Novice · Flask** · Damage / Hex / Control · Action · 0 · thrown, range 8, one square vs Guard · **fire**: 1 RD + Key fire, Burning 1; or **smoke**: Burst 1 concealment 1 round; or **adhesive**: Rooted 1 round.
- **Adept · Conditional Flask** · 2 RD + Key, Burst 1; set a trigger — impact, proximity, or a count of rounds; fire: Burning 2; adhesive: Rooted 2 rounds; smoke: 2 rounds.
- **Master · Gadget System** · deploy one: a **Turret** (Vigor 4 × level, Guard 16 + RB; on each of your turns it Strikes for 2 RD + Key at range 12; lasts until destroyed or the encounter ends), a **Lift** or **Line** (allies cross a gap or a height of up to 6 as a Move), or a **Lock** (a door, gate, or portal sealed: DC 26 to open).
- **Guru · Integration** · Battlefield · Action · 5 · Ground · Sustained (upkeep: Quick) · familiars and devices act in concert: every ally on the map has +2 on attack rolls (eyes everywhere); at each upkeep one ally's gear or one construct regains 2 RD; you may deploy a primed Device at any square a familiar can see; an enemy Mob seen by two familiars loses 1 Cohesion per round.

**Reading — Read the Make** · Quick · 0 · an object, construct, trap, or piece of gear within 6: what it does and its flaw. Exploit: your next attack against a construct, gear, or trap crits on 18–20; or bypass a read trap without a check.

**Skills.**
- **Novice A · Smoke** · Control · Action · 1 · Burst 1 within 8, 2 rounds · creatures inside are Hidden from those outside and Blinded to them.
- **Novice B · Adhesive** · Control · Action · 1 · one target within 8 vs Guard · Rooted 1 round (Large: Slowed instead).
- **Novice C · Maintenance** · Heal · Action · 1 · touch a construct, golem, familiar, or piece of gear: 2 RD Vigor, or restore a broken shield or armor bonus.
- **Adept A · Familiar** · Utility · *(bench)* · a small bound construct on a wren, rat, or beetle frame: Vigor 5, Speed 8 (a wren flies 12); carries a light object; you see and hear through it within 24; direct it as a Quick. Adept 1, Master 2, Guru 4. Each familiar reduces your Strain Capacity by 1 while bonded — canon's divided attention.
- **Adept B · Timed Charge** · Damage · Action · 2 · place within 8; at the start of your next turn: Burst 1, 3 RD + Key, Prone.
- **Master A · Construct** · Summon · Action · 4 · a clockwork guard: Vigor 4 × level, Guard 15 + RB, Strike 2 RD + Key crush, Speed 5; 3 rounds; command as a Quick.
- **Master B · Signal Line** · Boon · Quick · 2 · Ground · allies within 24 may act on your Initiative once this encounter, and can communicate at any distance for the scene.
- **Guru A · Company Standard** · Boon · Action · 5 · Ground · from the wagon: every ally regains 2 RD Vigor and one primed Device of yours; allied Mobs regain RD Cohesion.
- **Guru B · Infrastructure** · Battlefield · *(bench)* · 5 · a device that alters infrastructure: a bridge dropped on demand, a lift that carries a Mob, a gate that opens for you alone, a signal line across a city ward. A scenario power; the GM adjudicates its reach.

**Cost stages.** Reagent-etched hands → Close-work sight → Fume-worn lungs → The divided attention.

---

### 14.12 Warlock — Alchemy, Dark Arts (Ethosless)

**Fantasy.** Poison and control alchemist. Novice handles what others must not; Adept grades venoms and builds a golem; Master makes contact-grade compounds and tailored poisons; Guru doses grounds and crowds and holds the antidote no one else can check.
**Key** Reckoning · **Armor** light · **Vigor** Alchemy · thrown vials range 8; simple weapons.

**Signature resource — Formula.** After a Rest, compound **Doses** from Properties you know: Novice 3, Adept 4, Master 5, Guru 6 doses. A Dose combines two Properties. Use a Dose as an **Action** (throw, range 8, vs Ward), a **Quick** (coat your weapon or an adjacent ally's: its next 3 hits deliver it), or a **drink** (a draught, Quick). Doses cost no Strain. **Improvise:** Action + 2 Strain to compound one Dose on the spot.

| Property | Rank | Effect |
|:--|:--|:--|
| Numbing | Novice | Slowed 1 round |
| Wasting | Novice | Poisoned 2 |
| Blistering | Novice | 1 RD toxin; Weakened 1 round |
| Choking | Novice | Dazed 1 round |
| Preserving | Novice | *draught* — Fortified RD |
| Purging | Novice | *draught* — removes Poisoned and Burning; 1 RD Vigor |
| Sleep | Adept | Stunned 1 round; a target at half Vigor or less: 2 rounds |
| Quickening | Adept | *draught* — Hastened 2 rounds, then 1 RD toxin |
| Corroding | Master | armor bonus −2 for the scene |
| Paralytic | Master | Stunned 1 round, then Slowed 2 rounds |

**Onset** (from Adept): a thrown or coated Dose may be **delayed** one round; a delayed Dose on a target that hasn't noticed it (the GM rules) has its damage and durations doubled.

**Core — the Vial line.**
- **Novice · Vial** · Damage / Hex · Action · 0 · thrown, range 8, vs Ward · 1 RD + Key toxin, Poisoned 1.
- **Adept · Graded Venom** · 2 RD + Key, Poisoned 2; choose the onset.
- **Master · Contact Compound** · 3 RD + Key, Burst 1, Poisoned 2 to all hit; a Master's poison needs skin, not a cup: it ignores immunity below Guru, and a coated weapon delivers it on every hit, not three.
- **Guru · Dose the Ground** · Battlefield · Action · 5 · Burst 4 within 12 · Sustained (upkeep: Quick) · enemies inside are Poisoned 2 at the start of each of their turns (stacking), and Frightened, Slowed, or Dazed (choose at casting); a Mob inside loses RD Cohesion per round; a well, granary, or censer inside is dosed for a phase.

**Reading — Read the Dose** · Quick · 0 · a creature within 6: what it has consumed, its resistances, its tolerance. Exploit: your next Dose against it ignores resistance and applies one extra stack.

**Skills.**
- **Novice A · Purgative** · Heal · Action · 1 · touch · remove Poisoned and Blinded; 1 RD Vigor.
- **Novice B · Preservation Draught** · Boon · Quick · 1 · an ally within 6 · Fortified RD, 3 rounds.
- **Novice C · Handle It** · passive · immune to Novice-grade poisons; Advantage on Ward against toxin.
- **Adept A · Push Draught** · Boon · Quick · 2 · an ally within 6 · Hastened and Bolstered 3 rounds; when it ends, 2 RD toxin — the bill presented later.
- **Adept B · Golem** · Summon · *(bench)* · a clay-bound golem: Vigor 3 × level, Guard 14 + RB, Strike 2 RD + Key crush, Speed 4; obeys one-word orders (Quick); unordered, it attacks the nearest creature. Lasts the scene. One at a time until Master.
- **Master A · Tailored Poison** · Hex · Action · 4 · a named recipient within 8 whom you have Read or studied: the Ward roll is made at Disadvantage for them; Poisoned 4 and Weakened 3 rounds; ignores immunity below Guru.
- **Master B · Standing Orders** · Boon · Quick · 3 · your golem holds an order for the scene (guard this, hold that, carry them).
- **Guru A · The Antidote No One Can Check** · Heal · Action · 5 · touch · cure any poison, hex, or Dose, Guru-grade included; or lay a **hold** — a dose only you can undo: the target takes 1 RD toxin at the start of each of its turns until you release it (Ward at casting negates).
- **Guru B · Golem Team** · Summon · *(bench)* · 5 · up to four golems under standing orders, acting as a Mob with Cohesion 3 × RD.

**Cost stages.** Tolerance dosing → Organ staining → Taste-death → The venomous body.

---

## 15. Gear and relics (interface only)

The full gear and relic rules are a GM Guide workstream (handoff, item 5). What a player needs to know now:

- **Six gear slots:** head, chest, gloves, boots, ring, amulet. Gear is graded by the maker's rank (Novice / Adept / Master / Guru), readable by the Artificer's *Read the Make*. Each slot carries a fixed intrinsic at Adept and Master grade (no choices to make); Guru-grade gear is always a named piece. Chronicle v0.3 §10 is the starting model.
- **Weapons and armor** are the class kit (§4). Better-made versions add +1 to hit (Adept), +1 damage (Master), or a socket (Guru).
- **Sockets** hold **relics**. A relic comes from an event — properly resolved Grand Beast emergences leave one, connected to the beast's Trait, Dependency, Dominance, or Tether — never from a shop. A relic **grants a new action or alters a class mechanic** ("the Shalei tooth: your Riposte deals +1 RD frost and Slows"), not a flat bonus. One relic per socket; a character has at most one socketed weapon and one socketed armor piece plus the ring and amulet.
- **Bond cost.** Chronicle seats a relic as a bond on Strain Capacity (−1 to −3 by tier). Whether Heroes keeps that cost, halves it, or drops it in favor of a per-character relic cap is open (handoff, decision D4).

---

## 16. The character sheet

Standardized. Every field is on it; nothing else is.

```
TERHIA: HEROES — CHARACTER SHEET
────────────────────────────────────────────────────────────────
Name ____________________   Player ____________   Culture / homeland ____________
Class ________ School ________ Ethos ________ Moon ________  Level __  Rank ________
Rank Bonus +__   Rank Die d__   Crit Chance __–20   Crit Rate ×__

ATTRIBUTES (score / modifier)            DEFENSES
  Frame      __ / __                       Guard   __  = 10 + Poise + armor __ + shield __ + RB (+1 martial)
  Poise      __ / __                       Ward    __  = 10 + Reserve + RB (+1 magic)
  Reserve    __ / __                       Speed   __  Initiative +__
  Reckoning  __ / __
  Attunement __ / __                     VIGOR   current ____ / maximum ____   Fortified ____
  Standing   __ / __                     STRAIN  current ____ / capacity ____   Second Wind [ ]

THE LEDGER (the part other people cannot see — keep it honest)
  Marks  ○○○ | ○○○ | ○○ | ○○   (3 · 6 · 8 · 10)      Stage __  ________________
  Cost stages (school): 1 ______________ 2 ______________ 3 ______________ End ______________
  The End, written once at creation: ________________________________________________

SIGNATURE RESOURCE  ____________   current __ / max __   (how it builds: ________________)

CORE  (current form) ______________________________________________________________
READING  ____________________  exploit: ____________________________________________

ABILITIES (name · type · action · Strain · range/area · effect)
  Novice A ______________________________________________________________________
  Novice B ______________________________________________________________________
  Novice C ______________________________________________________________________
  Adept A  ______________________________________________________________________
  Adept B  ______________________________________________________________________
  Master A ______________________________________________________________________
  Master B ______________________________________________________________________
  Guru A   ______________________________________________________________________
  Guru B   ______________________________________________________________________
TALENTS  L2 __________  L6 __________  L10 __________  L14 __________
JOINS held (with whom) __________________________________________________________

CONDITIONS NOW   boons: ________________________   hexes: ________________________
                 Burning __  Bleeding __  Poisoned __   Death Clock  ○○○

KIT
  Weapon _____________ (die d__, reach/range __)    Armor _____________ (+__)   Shield (+__)
  Head ________  Chest ________  Gloves ________  Boots ________  Ring ________  Amulet ________
  Relics (socket · effect · bond) ______________________________________________
  Companion / familiar / golem: name ______ Vigor __/__ Guard __ attack +__ damage ____ Speed __
  Doses / primed Devices / Adaptations active: ___________________________________
  Coin and kind __________________  Tongues and trades __________________________

NOTES  contracts held · debts · who knows what you are
────────────────────────────────────────────────────────────────
```

---

## 17. Design register — for ratification

Every rule that touches a canon sentence, with the reading taken. Nothing here is canon until Joe rules; Canon itself is untouched. Numbering is Heroes-local (H-rows) so the register never collides with Chronicle's.

| # | Rule | Canon touchpoint | Reading taken | Status |
|:-:|:--|:--|:--|:-:|
| H1 | Two rulesets share one canon; Heroes changes the player promise only | Design Thesis; Premise | The world is not made more powerful; the PCs are | open |
| H2 | Sixteen levels, four per in-world rank | Part II, Ranks | Levels are a table device; the registries still count four ranks | open |
| H3 | Rank Bonus +2/+4/+6/+8; Rank Die d6/d8/d10/d12 (Chronicle: d4/d6/d8/d12) | Part III: "Novice → Guru progresses exponentially" | Rank is the large jump; d10 admitted for a smoother curve | open |
| H4 | Attributes reused from Chronicle; array 16/14/13/12/10/8; caps 18/20/22/22 | — (Chronicle PM §3) | Heroes start one point higher; 22 available at Master | open |
| H5 | Strain refreshes fully at a Breather; **Marks only from Overdraw and Push** | Premise: "severity in cost nearly equal to the power"; Parts II–IV cost progressions | Routine use is paid in recoverable Strain; permanent cost only past normal limits. The largest departure in the file | open |
| H6 | Marks floors by rank 0/1/2/3 | Part II, Rank Distribution (cost first appears at Adept; every Guru has a cost file) | Direct | open |
| H7 | Stages at 3/6/8/10 with uniform penalties; stage names per school from canon; the End at 10; Marks never decrease | Parts II–IV; Chronicle compliance rule (cost stage monotonic) | Uniform mechanics, school flavor; End scene in GM Guide | open |
| H8 | **Sacred** damage kind for Divine offense (*Rebuke*, *Sanction*) | Part II, Divine Adept: "voice and presence carry physical weight" | Offensive Divine is not in canon; the kind is a game term and lands as weight, not fire | open |
| H9 | Sorcerer runs a partial Overlay from Novice; Guru edits cost 4 Strain | Part II, Arcane (overlay is Master technique); R.0 Sorcerer rule (stronger reading) | Partial overlay = "structural sight"; the standing rule applied | open |
| H10 | Apothecarist Adaptations from Adept; *Apex Form* at Guru | Part II, Nature Guru (morphic borrowing is the peak technique) | Brainstorm placed "adapt" at Adept; canon places borrowing at Guru. Flag: either lower the whole soma list to Master+, or keep Adept for class fun | open |
| H11 | Apothecarist Companion at Novice | Part II, Nature Novice ("summon and hold attention of small wildlife") | A bonded animal is the heroic extension of that line | open |
| H12 | *Remake* (Guru heal to full / regrowth) and *Command the Ground* | Part II, Nature Master and Guru | Inventions; Remake's Mark on a Downed target keeps cost in the school | open |
| H13 | Necromancer Residue resource; *Residue Bloom*, *Open Door* as offense; *Threshold* = boundary holding; no undead anywhere | Part VI Terminology: "does not raise, animate, or command the dead"; Part II Necrotic Guru | Preserved exactly; offense is boundary and residue, never bodies | open |
| H14 | *Refuse Death* and *Lent Years* cost a Mark each | Part II, Divine Guru: transference is the spell | Direct | open |
| H15 | Four elements including Stone; *Harbor Kept* costs 1 Mark per day sustained | Part II, Elemental Novice (fires, water, gusts); Guru (sustained works keep drawing cost) | Earth admitted as the fourth element (brainstorm); sustained-work cost kept | open |
| H16 | Martial Strike scaling: 1 attack → +RD → 2 attacks → 2 attacks +2 RD; Guru martial abilities calibrated against a Mob | Part III: "a Guru can fight platoons" | Calibration deferred to GM Guide (handoff item 10) | open |
| H17 | Mobs and Cohesion referenced, defined in GM Guide | Chronicle GMG Lines / Cohesion | Reuse the Chronicle model on a grid | open |
| H18 | Grid: 1 square = 1 pace; Speed 6; diagonals 1; sizes M/L/H/Grand | Chronicle PM §4 (6 paces per Move) | Direct to squares | open |
| H19 | Area attacks: one roll compared to each target; half damage on a miss | — | Speed at the table | open |
| H20 | Readings as Read → Exploit; private hand-outs dropped | Design Thesis; Part I, Three Readings | The thesis survives in what each Reading cannot see and in Joins; it no longer governs table procedure. Flag as a deliberate weakening | open |
| H21 | Joins: Action + Reaction, 2 Strain each, +2 to hit; ten listed | Chronicle PM §8 (two hard checks) | Combination attacks; improvised Joins in GM Guide | open |
| H22 | Dagger is not a school; the Warden's dagger removes adjacent Disadvantage | Part III preamble; XI.6 | Direct | open |
| H23 | Necromancer: no gloves slot, no shield | Part II, Necrotic physical practice (bare-handed) | Direct | open |
| H24 | Artificer familiar: −1 Strain Capacity each while bonded | Part IV, Light Arts cost (divided attention) | Direct | open |
| H25 | Warlock Doses cost no Strain; improvising costs 2 | Part IV, Dark Arts | The bench is the practice; the field is the exception | open |
| H26 | Berserker Gate maxima 2/3/4/5; the calling-back by an adjacent ally; post-gate Dazed | Part III, Ax (the gate; companions train for the calling-back; post-gate collapse) | Direct | open |
| H27 | Talents (ten) | — | Invention; all are table-mechanical, none touches the world | open |
| H28 | Healing: Breather restores a quarter of maximum Vigor (three per day); full Rest restores all | Chronicle GMG §6 ("nothing heals for free") | Not adopted in Heroes; rest heals. Flag | open |
| H29 | Death permanent; *Refuse Death* (Mark) and *Threshold* (delay) are the only exceptions | Part II, Divine and Necrotic Guru | Direct | open |
| H30 | Crit Chance / Crit Rate defined; a crit adds one hex stack; maximum Crit Chance 17–20 | — | Invention | open |
| H31 | Hexblade *Counter-Practitioner* cancels an ability mid-cast | Part III, Sword/Shield Master (closes the distance inside a chant) | Direct | open |
| H32 | Paladin *Demolition* and Sorcerer *Shatter Point* destroy structures with listed values | Part III Hammer Guru; Part II Arcane Master | Structure Vigor table in GM Guide | open |
| H33 | Moon phase: no mechanical effect in this draft | Part I, Moons (casting cost lowest in the school's own phase); 11 Sep 2026 decision (cost varies by phase only) | Deferred to the GM session (handoff decision D1): a phase rule must exist, because canon says cost varies by phase | open |
