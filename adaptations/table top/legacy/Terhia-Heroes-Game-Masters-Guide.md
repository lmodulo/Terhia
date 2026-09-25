# Terhia: Heroes — Game Master's Guide

**v0.1 — 25 September 2026.** Companion to Terhia-Heroes-Players-Guide.md v0.1 (PG). Built from Terhia-Heroes-GM-Guide-Handoff.md and Terhia-Canon.md v1.2. Mechanics only; no adventures. Every rule that touches canon is a G-row in §13 for Joe's ratification. Canon is not edited by this file.

**Sources loaded for this draft.** Handoff (whole). Canon v1.2: Part I (Transport, Moons, Substrate and Nodes), Parts II–IV (schools, ranks, costs), Part V (Money, Kind and Labor, Anchor Prices), Part VI (Institutions, Terminology, Force Types, Class Matrix), Part VIII (Ecological Engine), XI.2 (Document Exemplars), XI.3 (Beast Register), XI.6 (Do-not-re-raise), R.8. The PG level and talent tables were recovered from the PG session record. **Not available in this session:** the PG file itself, Terhia-Game-Masters-Guide.md v0.3 (Chronicle), Terhia-Grand-Beasts.md v0.2. Where the handoff asked for a port from those files (Lines/Cohesion, relic §9, the End procedure, "what an emergence leaves"), this draft rebuilds from canon and the handoff's description; the ports should be checked against the originals in the revision session (§13.3).

**Two additions beyond the handoff, on Joe's brief for this session:** a **Tempo** track (actions per turn grow with level; §3) and a **gear system** with eight slots, tiers, intrinsics, and sockets that seat relics with attributes (§7). Both change PG numbers; the PG revisions are listed in §13.2, not applied silently.

---

## Contents

1. Fixed by the PG
2. Decisions taken for this draft (D1–D11)
3. Tempo: actions per turn
4. Opposition: stat blocks, tiers, roles, encounter budget
5. Mobs
6. Grand Beasts as bosses
7. Gear and relics
8. Contracts and the quest loop
9. Rank-up, rest, travel, and the moons
10. Adjudication
11. Exemplars (28 stat blocks, 3 Mobs, 4 beasts, 4 contracts, one played round)
12. Calibration pass
13. Register: G-rows, PG revisions, open decisions

---

## 1. Fixed by the PG

The GMG builds against these. Any change is a PG revision (§13.2), never a silent GMG override.

| Item | Value |
|:--|:--|
| Resolution | d20 + attribute modifier + Rank Bonus vs Guard / Ward / DC |
| Rank Bonus (RB) · Rank Die (RD) | +2 / +4 / +6 / +8 · d6 / d8 / d10 / d12 |
| Levels by rank | Novice 1–4 · Adept 5–8 · Master 9–12 · Guru 13–16 (PG §13.1) |
| Guard · Ward | 10 + Poise + armor + shield + RB (+1 martial) · 10 + Reserve + RB (+1 magic) |
| Vigor per level | Martial 12/+7 · Alchemy 10/+6 · Magic 8/+5 · + Reserve each level |
| Strain Capacity | 6 / 9 / 12 / 16 + Reserve; full refresh at a Breather (10 min); three Breathers a day; a Breather restores a quarter of maximum Vigor |
| Marks | Permanent; floors 0/1/2/3 by rank; Stages at 3/6/8/10; Overdraw = 1 Mark; Push = 1 Mark; the End at 10 |
| Turn | Move (6) + Action + Quick + Reaction; one Sustained effect at a time (Tempo adds Actions: §3) |
| Damage kinds | Physical, Fire, Frost, Storm, Stone, Force, Toxin, Necrotic, Sacred |
| DoT | Burning 3/stack (decays) · Bleeding 2/stack · Poisoned 1/stack and −stacks Ward · cap 5 |
| Crits | Chance 20 (max 17–20); Rate ×2 (×3 by talent/ability); a crit adds one hex stack |
| Areas | One roll compared to each defense; half damage on a miss |
| Downed | Death Clock 3; stabilize DC 10; death permanent except *Refuse Death* and *Threshold* |
| Grid | 1 square = 1 pace; diagonals 1; Medium 1×1, Large 2×2, Huge 3×3, Grand Beast 4×4+; Mob = block |
| Advancement | Abilities per PG §13.1; talents at 2/6/10/14; attribute +2 at 4/8/12/16 within caps 18/20/22/22 |

**Nominal key modifier** for calibration: +3 / +4 / +5 / +6 at levels 1 / 5 / 9 / 13 (handoff 4.10).

---

## 2. Decisions taken for this draft

Working readings of the handoff's D1–D9, plus two new decisions this session's brief required. Each is a G-row; none is settled until Joe rules.

| # | Decision | Reading used in this draft | Where it lands |
|:-:|:--|:--|:--|
| D1 | Moon-phase mechanic | **(a), one lever:** in your school's own phase, Strain Capacity +2; in the two far phases (two steps away in the cycle), Strain Capacity −1; adjacent phases no effect. Martial and Alchemy schools: no moon, no effect | §9.4 |
| D2 | Starting level | **Level 3** recommended (full Novice kit; Vigor survives one bad round). Encounter tables are written from level 1 regardless | §4.6 |
| D3 | Apothecarist Adaptations | Not a GMG matter; unchanged | — |
| D4 | Relic bond cost | **(c) no Capacity cost.** Sockets are the cap (§7.4); the only bond rule is that an over-rank relic seated in the Trinket costs 1 Strain Capacity while seated | §7.5 |
| D5 | Death permanence | **As written.** An optional table rule, *Carried Back*, is written in §10.7 for Joe to accept or strike | §10.7 |
| D6 | Mob size unit | **Three units:** band 5 (1×5), squad 10 (2×5), platoon 40 (5×8). A sliding block is permitted for animals only | §5.1 |
| D7 | Guru scenario powers and the registries | **Yes, automatic:** a Ground-scale effect in registered territory files itself (§8.5) | §8.5 |
| D8 | Chronicle ↔ Heroes conversion | **Incompatible at the sheet level.** A character converts by rank, Marks count, and school only; abilities and gear are re-picked | §13.4 |
| D9 | "Err on the side of power" for the Sorcerer | **Yes**, applied to every GMG ruling that touches the Arcane school (Canon XI.6) | throughout |
| D10 | Tempo (new) | Actions per turn: 1 at level 1, **2 at level 6, 3 at level 12**; no Strain-costing ability twice in one turn (§3) | §3, §13.2 |
| D11 | Gear slots (new) | **Eight:** Head, Chest, Legs, Gloves, Boots, Accessory ×2, Trinket. One socket per piece. Weapons and shields carry no tier and no socket in this draft (G-row for Joe) | §7 |

---

## 3. Tempo: actions per turn

**Tempo** is the number of Actions a character takes on its turn. Move, Quick, and Reaction do not change.

| Level | Tempo | What it means at the table |
|:-:|:-:|:--|
| 1–5 | 1 | Move + one Action + Quick + Reaction (PG as written) |
| 6–11 | 2 | Two Actions a turn. An Adept Elementalist casts and Cores; a Master Hexblade Strikes twice (four attacks, since the Master Strike form already makes two) |
| 12–16 | 3 | Three Actions a turn. A level-12 Master Sorcerer casts three spells; a Guru Berserker Strikes three times |

### 3.1 Rules

1. **No repeats.** A Strain-costing ability may be used once per turn. The Core (0 Strain) may be used with every Action. Three Actions means three *different* costed abilities, or Cores in the gaps.
2. **Strain is the governor.** Nothing here raises Strain Capacity. A level-12 Sorcerer with Capacity 15 spending 3 + 2 + 2 Strain a turn is at Overdraw on turn 3. Tempo gives the option of a burst; the Ledger sends the bill.
3. **One Sustained effect** at a time, as the PG. A second Action cannot start a second Sustain.
4. **Dash** and other Action-cost movement may be taken with any Action. Move itself stays one per turn.
5. **Quick** stays one per turn; **Reaction** one per round. Talents that grant a second Reaction are unchanged.
6. **Summons act on the summoner's turn** and share its Quick: a familiar, golem, turret, construct, or companion takes its own Move and one Action when its summoner takes a turn, regardless of the summoner's Tempo. (Handoff risk 8; PG revision.)
7. **Readings** cost 0 Strain and are not Actions (as PG); Tempo does not multiply them.

### 3.2 Opposition Tempo

| Block | Novice | Adept | Master | Guru |
|:--|:-:|:-:|:-:|:-:|
| Standard | 1 | 1 | 1 | 1 |
| Elite | 1 | 1 | 2 | 2 |
| Boss | 1 | 2 | 2 | 3 |
| Boss **Interrupts** (§4.4) | 1 | 1 | 2 | 3 |
| Practitioner NPC | by level, as a PC | | | |

A standard enemy is meant to die to one PC turn at its tier; it does not need Tempo. Elites and Bosses need it, or a level-11 party of four takes eight Actions to a Boss's one.

---

## 4. Opposition

### 4.1 Stat block template

```
NAME · Tier · Role · Size · Speed · Tempo
Guard / Ward · Vigor · Attack bonus
Attacks: n per Action, damage per hit (kind)
Abilities: 2–4, PG format (cost in Strain where the block has it; range; effect)
Resist / Vulnerable: damage kinds (resist = half; vulnerable = +1 RD of the tier)
Reads as: one line per school that plausibly reads it (§10.3 gives the defaults)
Elite/Boss only: shake-off; Interrupts; Weakness (Boss)
Mob only: unit, block, drill, Cohesion, attack cap (§5)
```

### 4.2 Tier table (rescaled for Tempo)

Guard, Ward, and Attack keep the handoff's proposal: they set the 55–65% same-rank hit rate, and Tempo does not change hit rates. Vigor is rescaled because Tempo changes what a party does in a round. Handoff figures in parentheses where they changed.

| Tier | Guard / Ward | Attack | Vigor: Standard / Elite / Boss | Damage per round: Standard / Elite / Boss | Design Tempo (party) |
|:--|:-:|:-:|:-:|:-:|:-:|
| Novice | 14 / 13 | +4 | 12 / 30 / **75** (60) | 6 / 10 / 16 | 1 |
| Adept | 17 / 16 | +7 | 30 / 70 / **220** (140) | 12 / 20 / 32 | 2 |
| Master | 20 / 19 | +10 | 60 / 140 / **450** (280) | 20 / 34 / 55 | 2 |
| Guru | 24 / 23 | +14 | **100** (120) / 280 / **800** (560, avatar) | 34 / 55 / 90 | 3 |

**Tempo adjustments (two lines).** A level-5 party has Tempo 1 against Adept blocks designed for Tempo 2: halve Adept Elite and Boss Vigor (35 / 110). A level-12 party has Tempo 3 against Master blocks designed for Tempo 2: multiply Master Elite and Boss Vigor by 1.5 (210 / 675). No other adjustment.

**Damage per round → attacks.** Split the per-round figure across the block's attacks: Novice standard 1 × 6 (1d6+3); Adept standard 1 × 12 (2d8+3) or 2 × 6; Master standard 2 × 10 (2d8+1 each); Guru standard 2 × 17 (2d12+4 each). Elites make two attacks per Action; Bosses make two per Action plus Interrupts, and the per-round figure includes the Interrupts (Interrupt strike: 4 / 8 / 8 / 8 by tier). Dice are optional; the flat figure is the calibration.

**Why these numbers.** A standard enemy dies to one PC turn of its tier (two hits at Novice; two Actions at Master). An Elite dies to one round of focused party fire. A Boss survives 3–4 rounds of a full party at the design Tempo. §12 shows the arithmetic.

### 4.3 Roles

Apply to the tier line. Standard-line Vigor unless the role says otherwise.

| Role | Vigor | Guard | Speed | Damage | Build note |
|:--|:-:|:-:|:-:|:-:|:--|
| Brute | ×1.5 | −1 | 6 | ×1.25 | Melee; may be Large; one Cleave-type ability |
| Skirmisher | ×0.75 | +1 | 8 | ×1 | Ranged or hit-and-run; Disengage as a Quick |
| Caster | ×0.75 | −1 (Ward +2) | 6 | ×1 (one area per fight) | Strain 4 / 6 / 8 / 10 by tier; abilities cost 2; no Overdraw unless a named practitioner |
| Controller | ×1 | 0 | 6 | ×0.75 | Two hex abilities; one Stun-capable at most (§10.5) |
| Support | ×1 | 0 | 6 | ×0.5 | Heal = the tier's standard damage per round, one target; one boon |
| Elite | Elite line | +1 | 6–8 | Elite line | Any role above as its base; 3–4 abilities; shake-off (PG) |
| Boss | Boss line | +2 | 6–8 | Boss line | Interrupts; a listed Weakness; phases if a Grand Beast (§6) |

### 4.4 Elites and Bosses

- **Shake-off** as the PG: Elites and Bosses end Stunned early on their shake-off.
- **Hex stack caps:** standard 5 (PG), **Elite 4, Boss 3.** A Boss's Ward at −3 from Poisoned is still a Boss's Ward; the Warlock snowball (handoff risk 7) stops at −3.
- **Interrupts.** At the end of any other creature's turn, a Boss may spend one Interrupt: a strike at the tier's Interrupt figure (4 / 8 / 8 / 8), a Move of 3, or a listed Interrupt ability. Interrupts refresh at the start of the Boss's turn. They cannot use phase abilities, Sustain, or Overdraw.
- **Weakness.** Every Boss lists one: a Reading that reveals it, and the mechanical effect of exploiting it (Guard −4 for a round; a resistance removed; an ability lost until the next phase). Grand Beast weaknesses come from the canon tier table (§6).
- **Bosses and Slow Field / mass hexes.** A Boss entering a Sorcerer's *Slow Field* or any Ground-scale hex makes a Ward check (d20 + tier Ward bonus vs the caster's ability DC) on entry and at the start of each of its turns; success ends the effect for it alone. The field stays (D9: the Sorcerer keeps the ability; the Boss keeps its check). Elites make the check on entry only.

### 4.5 Practitioner opposition

Enemy practitioners **use the PG classes at their listed level**; there are no separate "enemy caster" tables for named people. The GM runs the resource:

- Strain Capacity, Marks (start at the rank floor), Tempo by level, talents per PG (pick two that fit; skip the rest).
- **NPC Push and Overdraw: allowed.** Budget: **3 Marks per session across all NPCs**, and every NPC Mark is narrated in the school's register exactly as a PC's would be (§10.1). An NPC at Stage 3+ has the Stage penalties on the sheet.
- Unnamed practitioners (a garrison's Adept, a column's Apostle) use the Caster / Support / Controller roles above with a school label and one PG ability; they do not Push.
- A **rival practitioner party** is a listed encounter type: four PG characters at the party's level ±1, run with the same rules. §11.6 plays one round of it.

### 4.6 Encounter budget

**Threat Points (TP)** are counted in the tier of the party.

| Block | TP (own tier) |
|:--|:-:|
| Standard (any role) | 1 |
| Elite | 3 |
| Boss | 6 |
| Mob band 5 / squad 10 / platoon 40 (at its drill tier) | 2 / 4 / 10 |

**Cross-tier conversion.** One tier below the party: ÷3 (a Novice standard is ⅓ TP to an Adept party). One tier above: ×3. **Two tiers or more above: not a stand-up fight** (§4.7).

**Budget for four PCs, own-tier TP:** Easy 2 · Standard 4 · Hard 6 · Deadly 8. Five PCs ×1.25; three PCs ×0.75. Levels 1–2 use Easy and Standard only. A day of adventuring holds about 12 TP between night rests; three Breathers are the spacer.

**Within-tier level.** A block has a tier, not a level. A level-8 party against Adept blocks is at the top of the band and will find Standard fights easy; use Hard. A level-5 party uses the Tempo adjustment (§4.2) and treats Hard as Deadly.

**The ±1 rank rule.** An encounter's enemies are within one rank of the party, or the scene is a chase, a puzzle, or a Boss with a listed Weakness — never a stand-up fight.

### 4.7 Rank mismatch: what a Novice party sees when it meets a Master

Hit chance of an attacker of one tier against the standard Guard of another (natural 1 always misses):

| Attacker → Guard of | Novice 14 | Adept 17 | Master 20 | Guru 24 |
|:--|:-:|:-:|:-:|:-:|
| Novice +4 | 55% | 40% | 25% | 5% |
| Adept +7 | 70% | 55% | 40% | 20% |
| Master +10 | 85% | 70% | 55% | 35% |
| Guru +14 | 95% | 90% | 75% | 55% |

A Master standard enemy against a level-3 party: 85% to hit, 20 damage a round, into martial Vigor around 35 and magic Vigor around 25. Two rounds. The party's expected damage against Guard 20 is 25% of 25 a round; the enemy's 60 Vigor lasts ten rounds. **Survivable only by leaving.**

**Leaving procedure.** The round the party decides to leave, run it as a chase: the enemy takes its full turn each round; a PC is safe at the end of a round in which it is out of the enemy's reach and line of sight, or behind a structure the enemy cannot break in one round (§10.8), or in a gap the enemy's size cannot enter. Downed PCs are the cost of deciding late. The GM should say the tier out loud when the first Reading lands — "this is above you" is a legitimate Reading result at every school (§10.3).

---

## 5. Mobs

The Chronicle's Lines / Cohesion model converted to figurines. A Mob is one block on the grid with one stat line. Individuals do not exist unless an ability says "a member."

### 5.1 Units, blocks, drill

| Unit | Members | Block | Typical use |
|:--|:-:|:-:|:--|
| Band | 5 | 1×5 (or 5 loose squares as a sliding block, animals only) | A patrol, a pack, a boarding party |
| Squad | 10 | 2×5 | A gate guard, a caravan escort, a hunting party |
| Platoon | 40 | 5×8 | The Steel Quorum standard (Canon, Force Types): forty foot under one officer |

**Drill** is the unit's discipline, not its members' rank. Members are Novice-tier bodies at every drill; Adept and Master drill are what an Accord garrison, a Paladin column, or a Quorum-doctrine line have that a levy does not. Guru drill does not exist: a Guru is a person.

### 5.2 Mob stat line

| Drill | Cohesion per member | Guard / Ward | Attack | Damage per hit | Speed | Attack cap per target | Cohesion bonus |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Novice | 4 | 14 / 11 | +4 | 6 | 4 | 3 | +2 |
| Adept | 6 | 15 / 12 | +5 | 8 | 5 | 4 | +4 |
| Master | 8 | 16 / 13 | +6 | 10 | 6 | 5 | +6 |

**Cohesion** = members × the drill's per-member figure: a Novice platoon 160, an Adept platoon 240, a Master platoon 320; a Novice squad 40; a band 20. Cohesion is the Mob's Vigor. Tempo 1. No Reactions.

### 5.3 Attacks

- The Mob makes **one attack roll per edge square adjacent to a target**, against every adjacent target, up to the **attack cap per target**.
- **Engulfed:** a target adjacent to the block on two or more sides, or inside it, is attacked by every adjacent edge square with no cap. Corners and gaps are where Mobs kill. A Medium figure in front of a platoon's long face takes at most the cap; the same figure at a corner takes up to five.
- **Reach lines** (glaive drill): edge squares attack at 2 paces.
- **Volleys** (bow lines): instead of edge attacks, the Mob makes one ranged area attack per turn — Burst 1 at any point within 12, damage per hit × 2, one roll compared to each Guard in the area, half on a miss. Cohesion halves the number of volleys it can make when below half.

### 5.4 Damage to a Mob

- **Single-target** attacks and abilities deal their damage to Cohesion normally.
- **Area effects and DoTs deal double damage to Cohesion.** This is the whole reason casters exist at the platoon scale. Handoff 4.3: "PC area effects deal damage to Cohesion directly" — here, directly and doubled.
- **Hexes** apply to the block: Stunned, the Mob makes no attacks until its next turn ends; Slowed, Speed halves; Blinded, attacks at Disadvantage; Prone does not apply (a block cannot fall over).
- A crit against a Mob adds a hex stack as usual and kills a member if any ability cares.
- **Every PG ability that names Cohesion, a Mob, or a member works as written**, and those numbers are the ones this table was tuned to.

### 5.5 Cohesion check, rout, break

- **Check.** The first time a Mob is at or below half Cohesion, and at the end of every later round in which it took damage while at or below half: **d20 + Cohesion bonus vs 10 + damage taken this round.** Failure: the Mob **routs**.
- **Rout.** A routed Mob moves away from the nearest enemy at double Speed on its turns and makes no attacks. It **breaks** (is removed) if it takes any further damage, or when it leaves the map. A broken Mob's members are casualties, deserters, and prisoners at the GM's split; the number is a record, not a rule.
- **Rally.** An Elite officer adjacent to or inside a routed Mob may spend its Action: Cohesion check vs 15; success ends the rout at current Cohesion. One attempt per rout.
- **Broken outright** at Cohesion 0.

### 5.6 Members and officers

- A **member** exists only when an ability says so (Warden *First Ten Deaths*, and any ability that names one). A member is a Novice standard body with the drill's Guard; killing one reduces Cohesion by the per-member figure.
- Most Mobs have an **officer**: an Elite of the drill's tier occupying one square of the block. While the officer lives the Mob has +2 on Cohesion checks and can Rally. The officer can be targeted as a member by anything that names one, and by any attack that reaches its square (the block's squares in front of it give it cover: +2 Guard). Kill the corners, then the officer: that is the Sword/Shield Guru line in canon, expressed as a rule.

### 5.7 Movement and shape

A block moves as one piece at its Speed and cannot enter a gap narrower than its short side. **Reshaping** (5×8 to 4×10, a column to a line) costs the Mob's Action. Difficult ground halves Speed. A Mob cannot Dash; only a rout doubles its Speed. Sliding blocks (animals: a herd, a swarm) reshape freely and ignore the gap rule.

### 5.8 What a Mob reads as

| School | Reads |
|:--|:--|
| Sorcerer | The block's load: which corner carries the weight of its formation (attacks there count double against Cohesion this round, once per fight) |
| Elementalist | Ground and weather under it: whether it can be flooded, burned, or blown (the biome hazard, §9.3, applies if so) |
| Apostle | Its fear: the Cohesion check DC after the next round, before the round is played |
| Apothecarist | Its fatigue: whether it has marched (Speed −1 if so) |
| Necromancer | Its dead: how many it has lost today (Cohesion bonus −1 per 10 members lost, this fight) |
| Warden | Where it will go: the block's next Move, declared |
| Hexblade | Its officer's square |
| Vanguard | Its hinge: the square whose loss forces a reshape (kill a member there, the Mob loses its next Action) |
| Paladin | Its stored weight: where the shield wall's load sits (a Breach there deals double to Cohesion) |
| Berserker | Whether it will stand (a Mob that has already failed one check will not) |
| Artificer | Its kit: reach, volley, or neither |
| Warlock | What it drank: the dose that would drop its Guard by 2 for a round if delivered |

### 5.9 Calibration: the platoon standard

A Guru martial PC (level 13, Tempo 3) does about 61 Cohesion a round with Strikes alone (§12). Against a Novice platoon (160): round 1 → 99; round 2 → 38, under half, check vs 71 — automatic rout. **Two rounds.** Adept platoon (240): routs in round 3. Master platoon (320): under half in round 3, check at +6 vs 71, routs in round 3. Add the Guru abilities that name Cohesion and the range is **2–3 rounds**, inside the handoff's 2–4. A Master party of four (130/round) routs a Novice platoon in one round; a Novice party of four (25/round) cannot break a platoon and should not be shown one except as scenery or as the thing to hide from.

---

## 6. Grand Beasts as bosses

### 6.1 Constraints

- **Node ceiling.** Beast tier cannot exceed the local node's activity (Canon Part I; Part VIII). A dormant-node region hosts nothing above Adept. The GM checks the node reading before placing a fight, and the Sorcerer's Reading can report it.
- **Register discipline.** Emergences are entered per homeland and tier in the Grand Beasts module's register, built by the Generation Procedure (base animal × biome × moon × ethos). This file does not invent species. The four exemplars in §11.4 are treatments of existing register rows and are labelled as illustrations.
- **Tier table** (Canon Part VIII): power source → vulnerability origin → vulnerability logic is the fight's structure, not flavor.

### 6.2 Phase template

```
PHASE n — Trigger: [Vigor at ½ / ¼; a turn count; an event on the map]
Change: [map: what moves, floods, collapses, lights; the beast's position; resistances gained or lost]
New abilities: [1–2, PG format; one may be an Interrupt ability]
New Reading: [one line per school: what it can now see that it could not]
Interrupts this phase: [count]
```

A phase is announced when its trigger lands; the change is applied before the next turn. Damage carries over between phases; abilities do not stack across phases unless the entry says so.

### 6.3 Fight structure by tier

| Tier | Vigor (Boss line) | Phases | Vulnerability procedure |
|:--|:-:|:-:|:--|
| Novice | 75 | 2 | **Pattern.** The beast runs a fixed 3-turn cycle (e.g., stalk → charge → recover) with a **tell** the turn before its big attack. A PC who has read the pattern (any Reading, or two full cycles observed) gains the **exploit**: on the recover turn, attacks against it have Advantage and its Guard is −4. Phase 2 at half Vigor: the cycle changes and a new tell must be read. A hunt: the party's first job is to watch |
| Adept | 220 | 3 | **Dependency.** A food, a den, a moon-lit pool, a substrate reading at a site on the map. While intact: one resistance and one ability. **Denying it** removes both for the rest of the fight: two Actions at the site and a check vs DC 16 (any attribute the fiction supports), or breaking a 30-Vigor object there. Phase 2 at half Vigor: the beast moves to the dependency and fights at it. Phase 3 at a quarter: damage ×1.25, Speed +2, no more Interrupts (it has stopped thinking) |
| Master | 450 | 4, map change between each | **Reversal.** The arena is the beast's: an environmental condition (fog, flooded ground, heat, ice, dark) grants it +1 Interrupt, one resistance, and puts a hazard on the party. The party must **reverse the condition mid-fight**: a map task of 3 steps in Phase 1 (each an Action at a point plus a check vs DC 18, or a structure break, §10.8), 2 steps in Phase 2, 1 in Phase 3. Reversal opens a **vulnerability window** of 2 rounds: Guard −4, Vulnerable to one named kind, no Interrupts. Each phase the beast re-asserts the condition and changes the map (water rises, a ridge falls, the fog thickens). Phase 4 has no reversal: the beast is at a quarter Vigor and the window is permanent |
| Guru | 800 per manifestation | Repeats | **Tether.** The avatar is 4×4 or larger and built of parts (§6.5). It can be climbed, blinded, broken piece by piece, and its manifestation destroyed at 0 Vigor — and it **returns at the next phase of its moon** (or the next night, on the GM's clock) at full unless the tether is unseated. The tether is a node anchor: a basin, a range, a reef, an oasis. Unseating it is a **campaign objective**, not a fight: three **tether points** on a regional map, each unseated by a Guru-scale action (a Guru ability at Ground scale; a season's engineering work; a joint operation; a treaty that moves people). Each tether point unseated removes one part permanently from the next manifestation and one ability with it. All three unseated: the domain collapses with the avatar (Frostvatn, 1232) |

**Beast Tempo.** Novice 1 · Adept 2 · Master 2 · Guru 3, plus Interrupts by tier (§3.2). A beast's Interrupts are its own: a lash, a step, a call.

### 6.4 What each school's Reading reveals about a beast

One line per class per tier. Readings are 0 Strain and free of Actions; the GM says the line and no more. A Reading that fails is still a result.

| Class | Novice | Adept | Master | Guru |
|:--|:--|:--|:--|:--|
| Sorcerer | Mass and charge line | Where the enhancement sits (the load path) | The arena's held variable, as a quantity | The tether's coordinates |
| Elementalist | Which element it uses or fears | Which element its dependency needs | The condition, and what reverses it | Which moon it embodies; what sustained work would hold it |
| Apostle | Its agitation (when it will flee) | What it protects (the dependency as a want) | Whether it knows the inversion is coming | Returns "the Debtor" — a doctrinal problem, not a target |
| Apothecarist | Injury and the compensating limb | The biological dependency, named | Its channels, and which one the dominance drains | Fails: not a living system |
| Necromancer | What it has killed, how recently | What it feeds on, by its dead | Where the arena's deaths cluster (the reversal site) | The crossing count at the node |
| Warden | Its next square | Its den and route | Where the condition flows from | The domain's edge |
| Hexblade | The tell, one turn early | When it draws on the enhancement | The seam: the window's length | The phase in which it is thinnest (Interrupts −1) |
| Vanguard | Its charge lane | The ground it holds | The corridor to the reversal point | Which part has reach |
| Paladin | Its footing | The dependency structure's break threshold | The structure to break for reversal | The part carrying the load (break it first) |
| Berserker | Whether it registers wounds | What draws it off the dependency | The timing of its fear | Fails: the gate reads nothing above Master |
| Artificer | Speed and reach as numbers | A flask or gadget that disrupts the dependency | The mechanism of reversal (pins, levers, drains) | Which tether point is load-bearing |
| Warlock | What poisons it | Its diet, as a dose | What sickens it during the inversion | Fails: nothing to dose |

Failures are canon-consistent partial views (Design Thesis): the party assembles the beast from lines no single school could produce.

### 6.5 Avatar stat guidance (Guru tier)

- **Size** 4×4 minimum; 5×5 or 6×6 for a lake or range embodiment. Speed 6, or 0 if the manifestation is the terrain.
- **Parts.** 3–5 parts, each with its own Guard (the tier Guard 24 for the body; ±2 by part: a limb 22, a core 26) and **part Vigor = 800 ÷ (parts + 1)**, rounded. Damage to a part is damage to the avatar. **Destroying a part** removes one listed ability, grants a Reading of the tether to whoever destroyed it, and does not reduce the avatar's remaining Vigor below the parts still standing.
- **Climbing:** a PC on the avatar (a check vs DC 20 with a Move) attacks the part it stands on with Advantage and is attacked only by Interrupts.
- **Blinding, driving back:** hexes apply per part (Blinded on the head part removes its ranged ability); a Ground-scale Force or Storm effect moves the avatar 1 pace per 50 damage.
- **Regeneration between phases:** full Vigor and all parts, minus those permanently removed by unseated tether points.
- **Manifestation destroyed:** the avatar dissolves for the phase; the GM sets the return date; the campaign clock runs.

### 6.6 Outcome lines: what an emergence leaves

The beast's tier fixes the outcome line and the relic origin (§7.6):

| Tier | Outcome line | Leaves, if the vulnerability logic was executed | Leaves, if killed by attrition alone |
|:--|:--|:--|:--|
| Novice | **Trait** | 1 Novice relic (Rigidity governor) | Nothing usable; a hide |
| Adept | **Dependency** | 1 Adept relic (Dependency) + 1 Novice relic | 1 Novice relic |
| Master | **Dominance** | 1 Master relic (Inversion) + 1 Adept relic; the arena's condition ends for a season | 1 Adept relic; the condition persists |
| Guru | **Tether** | 1 named Guru relic (Tether) + 2 Master relics at domain collapse; the node reading falls one step | Per manifestation destroyed: 1 Master relic; the avatar returns |

The canon-strict register in the Grand Beasts module records the emergence; the GMG records nothing about it except what the party carried away.

---

## 7. Gear and relics

Gear is what a character wears; a relic is what a socket in that gear seats. Gear has a **slot**, a **tier**, an **intrinsic** (a fixed bonus by slot and tier), and **one socket**. A relic has a **rank**, an **attribute** (any numeric or mechanical property the game names), from Master rank an **alteration** (a new action or a changed class mechanic), and a **governor** (the condition under which it works, inherited from the beast that left it). This section replaces the Chronicle's six-slot model for Heroes (D11).

### 7.1 The eight slots

| Slot | What the piece is | Intrinsic stat |
|:--|:--|:--|
| Head | Helm, coif, hood, circlet, veil | Ward (and Guard from Master) |
| Chest | The PG's armor (light / medium / heavy) | Guard, on top of the PG armor value |
| Legs | Greaves, leggings, skirts of plate or quilt | Vigor |
| Gloves | Gauntlets, gloves; **wraps** for the Necrotic school, which works bare-palmed (Canon Part II: gloves muffle attunement) | Attack rolls and damage |
| Boots | Boots, sandals, snow-shoes, climbing irons | Hazard checks; Speed from Master |
| Accessory ×2 | Ring, amulet, belt, bracer, sash, token on a cord | Strain Capacity |
| Trinket | A tooth, a charm, a keeper's token, a page | **No intrinsic. Its socket accepts a relic of any rank** |

Weapons and shields keep their PG values and carry no tier and no socket in this draft (G-row 11; the obvious extension is one socket on the weapon, tiered like the rest).

### 7.2 Tiers and makers

A piece's tier is its maker's grade: Novice, Adept, Master, Guru. Trade grades are Ledger examination grades adopted by the trades (a Master smith is a board grade in Accord territory, a guild grade in Crown territory, a reputation in Chimera territory — G-row 12). Artificers make gadget-class pieces at their own rank. **Guru-grade gear is always named** and has a record: who made it, for whom, and where it has been.

| Tier | Source | Price band (§8.3) |
|:--|:--|:--|
| Novice | The PG starting kit; any market | Kit |
| Adept | Ledger-certified workshops; Chancel armories; a settlement's best maker | 8–20 seals a piece |
| Master | Master makers on the roll; commission, one phase to make | 60–150 seals a piece |
| Guru | Not sold. Commissioned by an institution, inherited, taken, or awarded (§8.3, access) | A lease-scale figure, if it is ever priced |

### 7.3 Intrinsics

| Slot | Novice | Adept | Master | Guru (named) |
|:--|:--|:--|:--|:--|
| Head | — | Ward +1 | Ward +1, Guard +1 | Ward +2, Guard +1 |
| Chest | PG armor value | Guard +1 | Guard +1 | Guard +2; Resist one damage kind, chosen at making |
| Legs | — | Vigor +5 | Vigor +10 | Vigor +20 |
| Gloves / wraps | — | Damage +1 on Strike and Core | Attack +1, damage +1 | Attack +1, damage +2 |
| Boots | — | +2 on checks against hazards | Speed +1 | Speed +1; difficult ground costs no extra Move |
| Accessory (each) | — | Strain Capacity +1 | Strain Capacity +1 | Strain Capacity +1 |
| Trinket | — | — | — | — |

Intrinsics stack across slots and do not stack within one. A full named kit at Guru: Ward +2, Guard +4 above PG armor, Vigor +20, attack +1, damage +2, Speed +1, Capacity +2, one resistance. §12 checks this against the tier table.

### 7.4 Sockets

- **One socket per piece.** A socket seats **one relic of rank equal to or below the piece's tier**: a Master helm seats a Master, Adept, or Novice relic; an Adept ring seats Adept or Novice.
- **The Trinket's socket seats any rank.** An over-rank relic there (a Novice carrying a Master relic) costs **1 Strain Capacity while seated** — the only bond cost in the game (D4).
- **Seating and unseating** take a Breather. A relic seated unread (§7.7) reveals its governor the first time it fails.
- **Maximum seated: eight**, one per slot, and **the same attribute in at most two sockets**. No Capacity cost beyond the Trinket rule.

### 7.5 Relics

A relic is beast residue with a shape: a tooth, a stone from a den, a bead of reef-glass, a shard of lake ice that does not melt. It drops only from an emergence's outcome line (§6.6); it is never made, and the Ledger's workshops cannot copy one.

**Rank** = the tier of the emergence that left it. **Power is sorted by rank** in the catalogue below; a Novice relic is a small permanent bonus, a Guru relic is a named piece of a Guru ability.

**Attribute catalogue.** Open: any property the PG or GMG names can be a relic attribute at the magnitude of its column. Where a column is "—", a relic of that rank cannot carry the attribute.

| Attribute | Novice | Adept | Master | Guru |
|:--|:-:|:-:|:-:|:-:|
| Damage, Strike or Core, one kind | +1 | +2 | +3 | +4 |
| Damage kind (Strike or Core deals a named kind) | — | yes | yes, +1 | yes, +2 |
| Attack rolls | — | +1 | +1 | +2 |
| Guard | +1 | +1 | +2 | +2 |
| Ward | +1 | +1 | +2 | +2 |
| Vigor | +5 | +10 | +20 | +30 |
| Strain Capacity | — | +1 | +1 | +2 |
| Speed | — | +1 | +1 | +2 |
| Healing dealt, per heal | +1 | +2 | +3 | +1 RD |
| Casting speed | — | 1/encounter: Core as a Quick | 1/Breather: a costed ability as a Quick | Every turn: the Core as a Quick |
| Crit Chance | — | — | +1 step (max 17–20) | +1 step |
| Crit Rate | — | — | — | ×3 on one named ability |
| DoT on hit (Burning, Bleeding, or Poisoned) | — | 1 stack on a crit | 1 stack on hit, once a turn | 1 stack on every hit |
| Resistance, one kind | — | — | half | half, and immune to its DoT |
| Death Clock | — | +1 | +1 | +2 |
| Breather | — | restores a third | restores a third | restores half |
| Reach or range | — | Strike reach +1 or Core range +4 | same | same, and areas +1 scale step 1/encounter |
| Reading | — | one line one tier up, own school | same | one line of a second school (the relic's moon) at Novice level (G-row 13) |
| Cohesion damage | — | ×1.5 | ×2 | ×2; areas ×3 |
| Summon (familiar, golem, companion, construct) | — | +1 Guard and attack | +2 | +2; one extra Action for the summon |
| Hex resistance, one named hex | — | +2 on checks against it | immune | immune |
| Tempo | — | — | — | 1/encounter: one extra Action |

**Alteration (Master and Guru only).** One new action or one changed class mechanic, written in PG format on the relic entry. A Master alteration is bounded to an encounter (a new Reaction; a movement mode; a once-per-Breather effect). **A Guru alteration is a bounded piece of the Guru ability of the relic's moon** — Sustained Works (Saelura / Elemental), Substrate Editing (Orrivane / Arcane), Morphic Borrowing (Threnis / Nature), Boundary Holding (Velquor / Necrotic), Lifespan Transference (Namaris / Divine) — usable by any class, at a cost the entry states. This is the handoff's "the GM can see the intended power": a Guru relic hands a Warden a sentence of a Guru's book, tethered.

**Governors** reuse the beast vocabulary. A relic's governor is the vulnerability logic of the tier that left it:

| Origin | Governor | What it means on the sheet |
|:--|:--|:--|
| Novice (Trait) | **Rigidity** | The attribute works only under one fixed condition, written on the entry: on a turn you did not Move; against a target that Moved this round; at night; below half Vigor |
| Adept (Dependency) | **Dependency** | The relic must be fed once a day — a Breather in contact with its dependency (water, fire, forest ground, the sky of its phase) — or it goes dormant until fed |
| Master (Dominance) | **Inversion** | In the beast's inversion condition (its dominance reversed: rain on a desert relic; clear dry air on a fog relic; daylight on a dark one), the attribute becomes a penalty of the same size for the scene, and the alteration is unavailable |
| Guru (Tether) | **Tether** | Works within the emergence's domain, or for seven days after a Breather taken there, or in the hands of its **bonded holder** (bond: a Breather at the tether site; one holder at a time; re-bonding takes a phase). Outside its tether: dormant. Always named for the emergence's register designation |

### 7.6 Where relics come from

Only from outcome lines (§6.6). The drop is a consequence of *how* the beast was beaten: a Master beast killed by attrition leaves an Adept relic and its arena's condition; the same beast beaten by reversal leaves the Master relic. The GM never rolls for relics; the outcome line is the roll. Rank of relic ≤ tier of emergence ≤ node reading: a dormant-node region has no Master relics that were not carried in.

### 7.7 Identifying a relic

- The school of the relic's moon reads it fully (attribute, magnitude, governor, tether) with one Reading. Any other school's Reading gives the attribute and magnitude only. A martial or alchemy Reading gives one word (Hexblade: the governor's condition; Artificer: the attribute; Warlock: whether it is safe to carry against skin; the others: "beast").
- The Cobalt Ledger's assessors identify any relic for a fee (2 seals, Adept; 10, Master; a Guru relic is not identified, it is filed) and the identification is a record: the relic now has a file, and so does whoever brought it.

### 7.8 Relics and the registries

- Accord: beast residue is declared cargo under the Manifest Rule; an undeclared relic on a portal manifest is smuggling. Velquor-line relics are registered but their Readings are inadmissible, like the school's.
- Crown: Velquor-line relics are contraband in Chancel territory since the Purge; Namaris-line relics are sacramental property and the Assay will ask for them.
- Chimera: a relic from a Threnis emergence belongs to the ground; the way's keeper decides who carries it, and nothing is written.
- Off-Ledger: priced in kind; a Guru relic buys a company.

(G-rows 14–16.)

### 7.9 Relic entry template

```
NAME (rank) · Origin: [emergence designation · homeland · tier · moon] · Line: Trait / Dependency / Dominance / Tether
Attribute: [catalogue row, magnitude]
Alteration (Master+): [one action or class-mechanic change, PG format, with cost]
Governor: Rigidity / Dependency / Inversion / Tether — [the specific condition]
Seats in: [any socket of tier ≥ rank; the Trinket]
Bond: none; 1 Capacity if over-rank in the Trinket
```

### 7.10 Ten sample relics

Origins marked *[register]* are emergences that exist in the Grand Beasts module's register or must be entered there; Canon XI.3 rows are cited where one exists. None of these is canon until its emergence has a row.

**1. Watcher's tooth (Novice).** Origin: the Deep Watcher archetype at Novice tier (XI.3; otter, water, node-active). Line: Trait. *Attribute:* Damage +1 Frost on Strike. *Governor:* Rigidity — only against a target that Moved this round (the ambush from still water).

**2. Den-earth pouch (Adept).** Origin: an Adept pack emergence, Taiga × Threnis, pack coordination (the Canon Part VIII worked example, not entered). Line: Dependency. *Attribute:* Attack +1. *Governor:* Dependency — a Breather on forest ground each day, or dormant.

**3. Waterhole stone (Adept).** Origin: an Adept emergence, Savanna × Saelura, waterhole stabilization *[register]*. Line: Dependency. *Attribute:* Healing dealt +2. *Governor:* Dependency — submerged for one Breather a day.

**4. Shalei burrow-tooth (Master).** Origin: Shalei burrow-dominant, 1155 (XI.3; desert, Threnis, Master, oasis dependency read as energy inversion). Line: Dominance. *Attribute:* Resistance, Stone. *Alteration:* **Sink** — once per Breather, as an Action, move 6 through sand or loose earth, ignoring Reactions, and surface adjacent to a target: your next Strike this turn has Advantage. *Governor:* Inversion — on wet ground or in rain, Vulnerable to Stone instead, and no Sink.

**5. Mwamba apex-claw (Master).** Origin: Mwamba apex, 1186 (XI.3; forest with mountain overlay, Threnis, Master). Line: Dominance. *Attribute:* DoT — Bleeding 1 stack on hit, once a turn. *Alteration:* **Overwatch** — once per encounter, as a Reaction, a Strike or Core against a creature that ends its Move within your range. *Governor:* Inversion — in open ground with no cover within 6 paces, your hits deal no Bleeding and you take 1 Bleeding stack each time you hit.

**6. Frostvatn basin-shard (Guru, named).** Origin: Frostvatn manifestation, 1230–32 (XI.3; tundra with mountain overlay, Velquor, Guru, the lake basin). Line: Tether. *Attribute:* Death Clock +2. *Alteration:* **Boundary held** — once per day, when an ally within 6 is Downed, their Death Clock does not tick for three rounds and they may speak (Necrotic Guru: a delay measured in breaths, not resurrection). *Governor:* Tether — the Frostvatn basin under the Hrafnrygg, or its bonded holder; re-bond at the basin. What the Chancel says about a person carrying it is a scene, not a rule.

**7. Harbor-keeping ember (Guru, named).** Origin: a Saelura embodiment *[register]* — a harbor or oasis node. Line: Tether. *Attribute:* Resistance, Fire, and immune to Burning. *Alteration:* **Sustained work** — as an Action, set one environmental hold in a 12×12 area (ice-free water; a raised spring; a still wind; a cool shade) and walk away. It holds while you are within a mile. Each day it holds costs 1 Strain Capacity, restored when you release it; a work held through a whole 80-day phase costs 1 Mark (Elemental Guru: the body as an ongoing power source). *Governor:* Tether — the embodiment's harbor or oasis, or its bonded holder.

**8. Overlay lens (Guru, named).** Origin: an Orrivane embodiment *[register]* — a portal-station or coordinate node. Line: Tether. *Attribute:* for a Sorcerer, Crit Chance +1 step on the Core (D9); for anyone else, the Sorcerer's Reading line at Novice level (mass and charge line). *Alteration:* **Gravity, bounded** — once per Breather, as an Action, set gravity in a Burst 2 for three rounds: *down* (creatures in it are Prone with Speed 1, Force 1 RD per round) or *up* (flying creatures fall; thrown and falling objects hang and drop when it ends). Ward check on entry for Elites and Bosses (§4.4). *Governor:* Tether — the station or node, or its bonded holder. Canon: edits hold only under attention; if the holder is Stunned the effect ends.

**9. Borrowed soma (Guru, named).** Origin: a Threnis embodiment *[register]* — a canopy or apex predator node. Line: Tether. *Attribute:* Speed +2. *Alteration:* **Morphic borrowing** — once per day, for ten rounds, take one animal trait: a climb Speed equal to your Speed; night eyes (no Blinded from darkness); or a bite, a Strike-kind attack at 1 RD + Key, Physical, that inflicts Bleeding 1 on a crit. The fifth use in a campaign, and every fifth after, is 1 Mark, narrated as species bleed. *Governor:* Tether — the emergence's forest, or its bonded holder.

**10. Lent-years token (Guru, named).** Origin: a Namaris embodiment *[register]* — a rite site or benefice ground. Line: Tether. *Attribute:* Healing dealt +1 RD. *Alteration:* **Transfer, bounded** — once per day, as an Action, move Vigor from yourself to a touched ally, one for one, up to five times your level; and once per phase, take one Mark from a touched ally onto yourself (the Assay reads it as a lent year; a Chancel Apostle reads it as their business). *Governor:* Tether — the rite site, or its bonded holder; re-bond at the site during Namaris.

---

## 8. Contracts and the quest loop

### 8.1 The loop

Contract → Travel → Discovery → Danger → Location → Fight → Revelation → Boss → Relic → Consequences → Next contract.

| Step | What the GM prepares |
|:--|:--|
| Contract | The posting in its institution's register (§8.2) and the one thing the poster is not saying (§8.6) |
| Travel | Mode, biome, phase, fare (§9.3); one ambient hazard from the grid |
| Discovery | A Reading opportunity: the ground tells one school one thing |
| Danger | A Standard or Hard encounter within one rank (§4.6) |
| Location | The map: the beast's dependency site, arena, or tether point; structures (§10.8) |
| Fight | The Boss or Grand Beast at its tier (§6.3) |
| Revelation | The phase change that shows what the contract was actually about |
| Boss | The final phase; the vulnerability procedure |
| Relic | The outcome line (§6.6, §7.6) |
| Consequences | The registries (§8.5); the reputation track (§8.4); the poster's reaction |
| Next contract | Generated from the consequence, not from a board |

### 8.2 Contract templates, each in its institution's register

Forms follow Canon XI.2; bracketed values are filled per contract. Filled examples are in §11.5.

**Cobalt Ledger — posting** (a typeset notice at a registry or a portal station)

> COBALT LEDGER · CONTRACT POSTING · [registry, homeland] · [moon] [year]
> Matter: [emergence / cull / escort / survey], at [ground], node reading [tier] as of [phase].
> Tier rating: [Novice / Adept / Master]. Licensed practitioners of the rating or above; registration to be shown.
> Fee: [seals], half on posting, half on the assessor's confirmation of outcome. Residue to be declared under the Manifest Rule.
> Standing: completion is entered on the licensee's file as [contract of record / noted].
> Assessor of record: [seal]. Posting lapses at the phase turn.

**Gilt Chancel — commission** (benefice paper, denominated in gilts)

> GILT CHANCEL · COMMISSION · [parish, homeland] · [day] Namaris [year]
> The Chancel commissions [name(s)] to [matter] at [ground], for the relief of [parish / column / rite].
> Benefice clause: on completion certified by the Indigo Assay, a benefice of [gilts] is entered to the commissioned; on failure, nothing is entered and the commission is cancelled from this date.
> Sacramental property recovered is the Chancel's. Velquor-line residue is to be surrendered.
> Attribution: work of the commissioned alone; assistance by unregistered practitioners voids the benefice.
> Examiner of record: [seal, Orrivane]. Copy to the Scribe's room, Qasr-Al-Rimal.

**Sedge Circle — request** (no paper; spoken by a keeper, before whoever is there)

> [Keeper], of [way or ground], says it once: [the thing wanted], at [ground], before the turn.
> What is owed is [in kind: a share, a season's watch, a name kept, a way opened]. It is not written.
> What is not the party's: the ground, the beast's dead, anything the keeper names as the ground's.
> If the way closes while they are on it, it was closed to them.

**Off-Ledger — job, priced in kind** (an Unsworn or compact form, stripped of the clauses that would make it enforceable)

> Job: [matter] at [ground]. Principal: [not named]. Priced: [in kind — a relic, a passage, a debt cancelled, a name struck from a roll].
> Registration: not asked. Residue: the principal's, or the price is halved.
> Stand-down: none. Simultaneous contract: assumed.
> Witness: none. The word binds, or the next job does not come.

### 8.3 Reward table

| Tier of contract | Coin | Kind | Standing (§8.4) | Gear grade | Access |
|:--|:--|:--|:-:|:--|:--|
| Novice | 2–6 seals (a labor-day is an eighth; a head of cattle six seals) | A meal, a bed, passage on a cart | +1 with the poster | Novice kit; an Adept piece as a favor | A name at the registry; a way not closed |
| Adept | 10–30 seals; 8–25 gilts | A mount; a season's grain; a familiar frame | +1, sometimes +2 | An Adept piece | A board sitting; a parish letter; a keeper's word |
| Master | 60–150 seals (a Master warden's season is 60); 50–120 gilts | A house; a workshop lease; a company's contract | +2 | A Master piece, commissioned | A Master's roll entry; an Assay certification; a Circle's recognition; a portal manifest without inspection |
| Guru | Not paid; leased. Hundreds to thousands of seals a year (the Stenhavn lease is 5,200) | A homeland's budget line | +3; a treaty matter | A named piece, awarded | The Escrow roll; the Chancel's rite; the Concord's speakership for a phase |

### 8.4 Reputation tracks

One track per institution, 0–5, plus the Off-Ledger. Each step names what it unlocks; a step lost is a Register entry, an audit, or a closed way (§8.5).

| Step | Cobalt Ledger (file) | Gilt Chancel (favor) | Sedge Circles (recognition) | Off-Ledger (credit) |
|:-:|:--|:--|:--|:--|
| 0 | No file | Unknown | Strangers on the way | No jobs |
| 1 | Noted | Heard of | Named by a keeper | A job, priced high |
| 2 | Licensed for contracts of the tier | Parish letter | A way opened once | Jobs at market price |
| 3 | Preferred: postings sent before they are posted | Commissioned | A season's welcome | Jobs priced in relics |
| 4 | Of record: the file is cited as evidence | Benefice-bearing | A share of the ground | The principal's name |
| 5 | On the roll (Master+) | The Chancel's rite | A seat at the fire session | A company of your own |

Standing with one institution moves the others: +2 with the Chancel is −1 with the Circles; a Ledger file of record is what the Off-Ledger charges for.

### 8.5 Consequences of a contract done wrong

| Consequence | Trigger | Effect |
|:--|:--|:--|
| **Register entry** (Accord) | Unregistered practice at Adept or above in Accord territory; undeclared residue; a Ground-scale effect in registered territory (D7: automatic) | Ledger standing −1; the next posting requires a hearing; a Guru-scale effect files an Escrow audit within the phase (D7) |
| **Assay audit** (Crown) | A benefice claimed on another's work; a Velquor-line relic carried into Chancel territory; a transfer made without an Apostle | Chancel favor −2; benefice voided; the party's names on the Scribe's copy |
| **A closed way** (Chimera) | Taking what the keeper named as the ground's; a beast killed by attrition where the keeper asked for the dependency read; writing anything down | The way closes to the party until the next Threnis turn; Circle recognition −2 |
| **A price** (Off-Ledger) | A job's word broken | The next job is the debt; credit 0 |

Guru consequences are treaty matters (Canon Part II): a party that carries a named relic or unseats a tether has done something three institutions will file three ways.

### 8.6 What the poster is not saying

Roll or choose one per contract; the Revelation step is where it lands.

1. The tier rating is one step low, because the posting was written before the node reading rose.
2. The beast is the second one; the first was culled by attrition and left the arena's condition standing.
3. The residue is already promised to someone else.
4. The poster's own practitioner failed the job last phase and is on the party's route.
5. The dependency site is a village's well, den, grove, or rite ground.
6. The contract exists so that the registry can file who took it.
7. The benefice, share, or price is denominated in something the party does not yet know it has (a Mark, a name, a way).
8. The tether point the party is sent to is one of three, and the other two are someone else's contracts.

---

## 9. Rank-up, rest, travel, and the moons

### 9.1 Rank-up in the world

Rank-up happens on the level table (PG §13.1). What happens in the world is this:

| Recognition | What it looks like | What is recorded | Time and fee |
|:--|:--|:--|:--|
| **Ledger board** (Accord; any school) | An examination table; the cost read aloud; a waiver signed | A cost-file entry (Canon XI.2 form 1): rank, stage, examiner, phase | A phase's wait for a sitting; 2 / 8 / 30 seals by rank; Guru: the roll, by petition |
| **Chancel attunement** (Crown; Apostles by rite, others by the Assay's counters) | The Assay's reading; a rite in Namaris for Apostles | The Assay's roll; benefice-bearing certification (form 2) | Namaris only; tithe, not fee |
| **Circle recognition** (Chimera) | A keeper says it before whoever is there | Nothing | When the keeper says so |
| **No recognition** | The party knows; the registries do not | Nothing, until a Reading by a registered practitioner or an inspection files it | — |

- **Unregistered rank-up in Accord territory is prosecutable** under the Second Register: any Reading of the character by a registered practitioner, any portal manifest, any assessor's confirmation files a Register entry (§8.5). The Ethosless schools have no registry to be late to; a Necromancer, Hexblade, or Warlock ranks up unregistered by default and is filed only when noticed.
- Talents with a trade, and Trade checks, use the same grades (§7.2).

### 9.2 Rest on the road

- A **Breather** needs ten minutes stationary: a caravan halt, a ship or airship under way, a portal station's waiting room, a camp. Not a mount in motion, not a march.
- Three Breathers a day, as the PG. A day of travel by caravan halts once at noon and once at dusk; the third Breather is the party's choice.
- **Night rest:** as the PG. In a Biome × Moon cell that names healing (Saelura on forest, taiga, rainforest, grassland), Breathers restore a third of maximum Vigor instead of a quarter.

### 9.3 Travel

Modes from Canon Part I, priced by phase (Phase Cascade, Part V). Figures are this file's (G-row 17).

| Mode | Pace | Fare or cost | Phase rule |
|:--|:--|:--|:--|
| Echo portal (Accord stations, seat to seat) | Instant; a phase-turn queue at busy stations | Passenger 4 seals base; declared light cargo 1 seal a load | ×1 in Orrivane; ×1.5 in Saelura and Namaris; ×2 in Velquor and Threnis. Manifest declared; relics are residue |
| Airship (guild) | 2–4 days between seats, by wind | Half the portal fare; freight by the ton | Wind-crew share ×1.25 outside Saelura; inspectors board first |
| Overland caravan | A biome stage a day: grassland and savanna 1; forest, taiga, chaparral 1.5; desert and tundra 2; mountain overlay +1; rainforest 3 | Way-tolls in Chimera territory, in the traveler's coin, recorded nowhere; caravan fare 1 eighth a day | Freight cost lags the sky; bread moves a little, and late |
| Harbor shipping | A coast a day; ice-law in Velquor where no harbor Guru keeps the water | Passage 1 seal a day | Ice: no sailing from a kept harbor's neighbors in Velquor |

**Ambient hazards.** The Biome × Moon grid as travel and encounter effects. One cell per scene; the extension rows follow the pattern (Velquor distorts, Namaris burns or blinds, Orrivane disorients, Saelura stabilizes or heals, Threnis produces fauna). Hazard damage is the party's tier standard damage ×2, one roll against each defense in the area.

| Cell (Canon Part VIII) | Effect at the table |
|:--|:--|
| Forest × Velquor — geometric growth | Paths change; navigation check DC 15 each stage or a day lost |
| Forest × Namaris — fire spread | Burning 2 stacks on entering a burning square; fire moves 2 a round downwind |
| Forest / Grassland × Orrivane — herd agitation | A Mob of animals (sliding block, Novice drill) crosses the party's ground |
| Forest × Saelura — rapid healing | Breathers restore a third (§9.2) |
| Forest × Threnis — apex emergence | Beast tier at the node ceiling; a Threnis Warden contract |
| Desert × Velquor — mirages | Warden and Sorcerer Readings return one false line per day; navigation DC 15 |
| Desert × Namaris — sandstorms | Blinded; Speed halved; ranged attacks at Disadvantage; hazard damage once an hour without shelter |
| Desert × Orrivane — heat delirium | Strain Capacity −2 for the day without water; Readings at Disadvantage |
| Desert × Saelura — oasis stabilization | A safe Breather site; Adept dependency beasts gather at it |
| Desert × Threnis — burrow dominance | Master-tier arena: the ground is the beast's (§6.3) |
| Coastal × Velquor — tidal distortion | Squares flood at the end of each round, 1 pace a round from the water's edge; deep water rules |
| Coastal × Namaris — storm surge | Line 12 of water: hazard damage and 3 paces of push; structures take double |
| Coastal × Orrivane — migratory disruption | Ships and airships lose a day; birds as a sliding Mob |
| Coastal × Saelura — coral recovery | Way law: a keeper's ground; nothing taken |
| Coastal × Threnis — reef intelligence | The reef closes a channel: a way with a keeper (Puketai); not a beast |
| Mountain × Velquor — fault shifts | Unstable footing across the stage; structures at half break threshold |
| Mountain × Namaris — avalanche | Line 12 crush: hazard damage ×2 and Prone; Stone |
| Mountain × Orrivane — echo hallucination | Apostle and Necromancer Readings return the wrong register once |
| Mountain × Saelura — monastic refuge | A guaranteed safe night rest |
| Mountain × Threnis — predator magnification | Beast damage ×1.25 for the phase |

### 9.4 The moons (D1)

Canon: casting cost varies by moon phase only. Heroes' rule, one lever:

| Phase, relative to your school's moon | Strain Capacity |
|:--|:-:|
| Your own phase | +2 |
| The adjacent phases (one step either way in Velquor → Saelura → Orrivane → Namaris → Threnis) | — |
| The far phases (two steps either way) | −1 |

Martial and Alchemy schools: no moon, no effect. The Elementalist's moon is Saelura (Canon Part I). Fares and leases follow §9.3. Nothing else in the game changes by phase; this is the whole rule.

---

## 10. Adjudication

### 10.1 Overdraw and Push: narrating the Mark

Once per turn (Overdraw) and once per round (Push), as the PG. The GM narrates every Mark in the school's register, drawn from the canon cost progressions. Marks 1–2 are the first sign of the first item; Stage 1 (3 Marks) is the first item; Stage 2 (6) the second; Stage 3 (8) the third; the End (10) is the fourth, played (§10.7).

| School | Marks 1–2 | Stage 1 (3) | Stage 2 (6) | Stage 3 (8) | The End (10) |
|:--|:--|:--|:--|:--|:--|
| Elemental | A tremor in the hands after casting | Fatigue that a night does not clear | Muscle failure: help to stand | Organ strain: the skipped beat | Collapse |
| Arcane | A headache behind the eyes | Headache that stays | Tremor | Time-lag perception; memory dissonance | Identity-time fracture |
| Nature | A patch of tough skin | Scar tissue | Sensory narrowing: one sense gone | Partial morphic blending | Species bleed |
| Necrotic | A cold patch that does not warm | Skin pallor | Death-residue sensation | Touch erosion | Boundary thinning |
| Divine | A grey hair | Minor aging | Frailty | Organ degradation | Lifespan compression |
| Sword/Shield | A scar that aches in a phase | Scar accumulation | Residue mapping | Startle lock | The guard that will not drop |
| Glaive | A stiff shoulder | Joint wear | Conditioning debt | Spinal compression | The seizing |
| Longbow | A night's sleep lost | Draw-side deformation | Watch-broken sleep | Sensory tuning | The unclosing eye |
| Hammer | A knuckle that does not straighten | Micro-fracture conditioning | Bone remodeling | Deep-set brittleness | The settling |
| Ax | An hour not remembered | Post-gate collapse | Frenzy amnesia | Affect blunting | Heart-burn |
| Light Arts | An etched fingertip | Reagent-etched hands | Close-work sight | Fume-worn lungs | The divided attention |
| Dark Arts | A morning dose | Tolerance dosing | Organ staining | Taste-death | The venomous body |

Stage penalties are the PG's. An NPC's Marks are narrated the same way (§4.5). A Mark is never a number said aloud; it is the item in the column.

### 10.2 Readings: one sentence per school, and what it cannot see

The GM says one sentence. The table is the sentence's shape; the beast table (§6.4) and Mob table (§5.8) give the specifics for those targets.

| School | One sentence (people, constructs, places) | Cannot see |
|:--|:--|:--|
| Sorcerer | A quantity: mass, load, velocity, composition, coordinates | Why; anything that is not a quantity (the Ledger files it as anecdotal) |
| Elementalist | What the ground, water, air, or fire will do next | Anything living, as living |
| Apostle | What the person wants, and how badly | Anything without a will; the beast at Guru (§6.4) |
| Apothecarist | Where the body is injured and what it needs | Anything that is not a living system |
| Necromancer | What died here, when, and in what register | Anything that has not died; the killer's face |
| Warden | Where it will go and by which way | What it will do when it gets there |
| Hexblade | The posture before the act: casting, drawing, breaking | Intent without a body |
| Vanguard | The geometry: hinge, corridor, reach | Anything off the map |
| Paladin | The load path: where the weight is, what breaks | Anything without structure |
| Berserker | Whether it will stand, and whether it registers pain | Anything above Master; anything not a threat |
| Artificer | The mechanism: how it works, what it needs | Anything without parts |
| Warlock | The body's tolerances: what it drank, what would drop it | Anything without a body |

**Cost:** 0 Strain, no Action, once per target per round. **Load:** the sentence is the whole result; a player who wants more spends the next round on the next Reading. "This is above you" is a valid result at every school.

### 10.3 Improvised Joins

Two schools, two abilities, one effect. Procedure:

1. Each contributor names the ability contributed (a Core is allowed) and pays **2 Strain** (in addition to nothing else: the Join replaces the abilities' own costs).
2. The GM sets the effect at the level of the **higher component, one scale step up**: target → Burst 2 → Line → Ground.
3. **Refused** if the result would be Ground scale below Guru, or if either contributor is Stunned.
4. Both contributors spend an Action; the Join resolves on the later turn. One roll, the higher contributor's, compared to each defense.
5. Damage kind and hexes are the higher component's; range is the shorter.
6. A Join is never narrated as a whole: each contributor is told what their part did (Design Thesis).

### 10.4 Stunned: how many a fight can absorb

- Standard enemies: no limit.
- Elites: once per source per fight; then the shake-off applies immediately.
- **Bosses: once per phase.** A second Stun in the same phase becomes Slowed. A Stunned Boss loses its Interrupts until its next turn, not its turn (it is still a Boss).
- The 1-round cap is the PG's. *Slow Field* stays as written (D9); Elites and Bosses get the Ward check (§4.4).

### 10.5 Sustained effects

One per character, as the PG; Tempo does not add one. A Sustained effect ends if the character is Stunned or Downed. A Boss's Sustained effect (an arena condition) ends only by the phase procedure.

### 10.6 Summons at the table

A familiar, golem, turret, construct, or companion acts on its summoner's turn with one Move and one Action, and uses the summoner's Quick if it needs one (§3.1). Its stats are the summoner's tier standard block unless the PG ability says otherwise. A summoner with Tempo 3 has three Actions and one summon's Action, not six.

### 10.7 The End

At 10 Marks the character leaves play in a scene, not a death roll. Procedure (Chronicle port; check against the original in revision):

1. **Trigger.** The tenth Mark is taken. The GM says the fourth item of the school's column aloud (§10.1). Play continues to the end of the current round.
2. **The last act.** The character takes one final turn at full Tempo, any ability, no Strain cost, no Ward check against it (D9 applies to a Sorcerer's edit: the substrate gives). This turn is the legend.
3. **The recognition.** Each other player says one sentence about the character in their own school's register — what their Reading of them was.
4. **The record.** The GM names what the campaign keeps: a harbor kept, a pass held, a name on the roll, a way opened, a company with the character's name on its contract. It becomes a reputation step (§8.4) for the party, permanently.
5. **What is filed.** The registries file what they file (a cost-file closed; an Assay reading; nothing). The player may write the entry.

The character does not necessarily die on screen; they are done. A retired Guru is a person in the world with a Stage-3 sheet and no Strain.

**Optional: Carried Back (D5).** At the table's choice, a character who dies below Guru can be carried back to the Circles: the party takes 1 Mark each, spends a phase, and the character returns at the start of the next contract with Marks at the next Stage threshold. Off by default.

### 10.8 Structures

| Structure | Vigor | Break threshold (one hit at or above breaks it) |
|:--|:-:|:-:|
| Timber door, shutter, cart | 15 | 10 |
| Stone wall segment (1 square), pillar | 40 | 20 |
| Iron gate, portcullis | 60 | 30 |
| Bridge pin, keystone, lever | As read by the Paladin or Sorcerer (10–30) | half its Vigor |
| Airship gas cell | 20 | 10; Fire breaks it at 5 |

Abilities that target structures as written: Paladin *Breach* (double against structures); Sorcerer *Shatter Point* (ignores the break threshold: any hit breaks if the Reading found the point); Elementalist *Quake* (Ground scale, all structures in the area take its damage); Artificer *Lock* (a structure's break threshold +10 for a scene). Structures have no Guard: attacks hit; damage kinds Force and Stone deal full, Toxin and Necrotic deal none, Sacred none, Fire full to timber only.

### 10.9 Hazards

The PG's four (fire, deep water, drops, unstable footing) as written. Biome hazards are §9.3; hazard damage is the party's tier standard damage ×2. A hazard is never a Reaction's target; it is the map.

---

## 11. Exemplars

Not adventures. Blocks are built from §4; beasts are treatments of register rows; contracts fill the §8.2 forms. Damage figures are flat; roll the nearest dice if the table prefers. "Reads as" gives the most useful school only; §10.2 and §6.4 give the rest.

### 11.1 Twenty-eight stat blocks

**Novice tier** — Guard 14 / Ward 13 · Attack +4 · Tempo 1

| Role | Example | Vigor | Guard / Ward | Speed | Attacks | Abilities | Reads as |
|:--|:--|:-:|:-:|:-:|:--|:--|:--|
| Brute | A levy pikeman; a boar | 18 | 13 / 13 | 6 | 1 × 8 Physical | *Sweep* (1/fight): Burst 1 adjacent, 5 each, half on miss | Warden: charges the nearest figure |
| Skirmisher | A bandit archer; a jackal | 9 | 15 / 13 | 8 | 1 × 6, range 12 | *Aimed*: Advantage if it did not Move; Disengage as a Quick | Hexblade: the draw, one round early |
| Caster | A hedge-practitioner, any school | 9 | 13 / 15 | 6 | *Bolt* 1 × 6 (school's kind), range 12 | *Area* (1/fight): Burst 1, 6, half on miss; Strain 4 | Sorcerer: which school, by the shape of the cast |
| Controller | A net-thrower; a marsh snake | 12 | 14 / 13 | 6 | 1 × 4 | *Snare*: Ward check or Slowed; *Daze* (1/fight): on a hit, Stunned 1 round | Vanguard: its reach and the square it will take |
| Support | A drummer; a camp healer | 12 | 14 / 13 | 6 | 1 × 3 | *Mend*: 6 Vigor, range 6; *Steady*: an ally +2 Guard for a round | Apostle: whom it is trying to keep alive |
| Elite | A sergeant; a lead hound | 30 | 15 / 14 | 6 | 2 × 5 | *Rally* (§5.5); *Press*: an adjacent ally's next attack has Advantage; *Hold*: Guard +2 if it did not Move; shake-off | Necromancer: how many it has buried today |
| Boss | A bandit captain; a Novice beast (§11.4) | 75 | 16 / 15 | 6 | 2 × 6; Interrupt strike 4 | Two of the above, one Interrupt (a Strike); **Weakness:** a tell (§6.3) or a Reading-revealed fear: Guard −4 for a round when exploited | Any: "this is a captain" |

**Adept tier** — Guard 17 / Ward 16 · Attack +7 · Tempo 1 (Elite 1, Boss 2)

| Role | Example | Vigor | Guard / Ward | Speed | Attacks | Abilities | Reads as |
|:--|:--|:-:|:-:|:-:|:--|:--|:--|
| Brute | A column's breacher; a bear | 45 | 16 / 16 | 6 | 1 × 15 | *Cleave*: on a kill, a second attack; *Shove*: 2 paces on a hit (1/turn) | Paladin: where its weight sits |
| Skirmisher | A compact scout; a hawk | 23 | 18 / 16 | 8 | 2 × 6, range 12 | *Mark*: a target it hit is Advantaged for allies until its next turn; Disengage as a Quick | Warden: its next square |
| Caster | A registered Adept, any school | 23 | 16 / 18 | 6 | *Bolt* 1 × 10, range 12 | *Area* (1/fight): Burst 2, 12, half on miss; *Ward* (Quick): Guard +2 for a round; Strain 6 | Elementalist: what it will do to the ground |
| Controller | A whip-line handler; a python | 30 | 17 / 16 | 6 | 1 × 9 | *Grasp*: Ward check or Slowed and Prone; *Hush*: Ward check or the target's next costed ability fails (1/fight) | Hexblade: the casting posture, one round early |
| Support | An Apostle's deacon; a den-mother | 30 | 17 / 16 | 6 | 1 × 6 | *Mend*: 12; *Boon*: an ally +1 RD damage for a round; *Cover*: a Reaction, +4 Guard to an adjacent ally | Apothecarist: whom it is bound to |
| Elite | A column lieutenant; a pack leader | 70 | 18 / 17 | 6 | 2 × 10 | *Rally*; *Press*; *Second Wind* (1/fight): 20 Vigor; *Shield Line*: adjacent allies +1 Guard; shake-off | Vanguard: its hinge |
| Boss | A rival Adept practitioner (§4.5) or an Adept beast (§11.4) | 220 | 19 / 18 | 6 | Tempo 2: 2 Actions × 2 × 6; Interrupt strike 8 | One Interrupt; a dependency (§6.3) or a **Weakness** a Reading reveals; two role abilities | Necromancer: what it feeds on |

**Master tier** — Guard 20 / Ward 19 · Attack +10 · Tempo 1 (Elite 2, Boss 2)

| Role | Example | Vigor | Guard / Ward | Speed | Attacks | Abilities | Reads as |
|:--|:--|:-:|:-:|:-:|:--|:--|:--|
| Brute | A Large war-beast (2×2); a siege-golem | 90 | 19 / 19 | 6 | 2 × 12 | *Trample*: Line 4 through, 12 each, Prone; *Grip*: on a hit, Restrained (Ward check ends) | Paladin: the load path |
| Skirmisher | A Master warden of the other side; a raptor | 45 | 21 / 19 | 8 | 2 × 10, range 16 | *Overwatch*: a Reaction attack against a creature ending its Move in range; *Vanish*: Disengage and Hidden as a Quick (1/fight) | Warden: where the shot will land |
| Caster | A Master practitioner in a role (the named ones use PG classes) | 45 | 19 / 21 | 6 | *Bolt* 1 × 17, range 16 | *Area* (1/fight): Burst 2 or Line 8, 20, half on miss; *Sustain*: one arena effect (§6.3); Strain 8 | Sorcerer: the quantity it is holding |
| Controller | A Master Warlock's golem-handler; a tar-pit swarm | 60 | 20 / 19 | 6 | 2 × 7 | *Hold*: Ward check or Stunned 1 round (the fight's one Stun); *Bind*: Speed 1, no Reactions, Ward check ends | Warlock: what it drank |
| Support | A Master Apostle's deacon; a node-echo | 60 | 20 / 19 | 6 | 1 × 10 | *Mend*: 20; *Extra*: an ally takes one extra Action (1/fight); *Shield of Word*: an ally immune to one hex for a round | Apostle: what it wants kept |
| Elite | A Master officer; a domain guardian | 140 | 21 / 20 | 6 | Tempo 2: 2 × 8 per Action | *Rally*; *Press*; *Second Wind* (40); *Lock Step*: allies within 2 cannot be Slowed; shake-off | Vanguard: its corridor |
| Boss | A Master beast (§11.4); a rival Master party's lead | 450 | 22 / 21 | 6 | Tempo 2: 2 Actions × 2 × 10; Interrupt strikes 8 | Two Interrupts; the arena condition; **Weakness:** the reversal window (§6.3) | Elementalist: what reverses the condition |

**Guru tier** — Guard 24 / Ward 23 · Attack +14 · Tempo 1 (Elite 2, Boss 3). Guru-tier opposition is the avatar and what a node produces around it; named Gurus use the PG.

| Role | Example | Vigor | Guard / Ward | Speed | Attacks | Abilities | Reads as |
|:--|:--|:-:|:-:|:-:|:--|:--|:--|
| Brute | A manifestation-limb detached (Huge 3×3) | 150 | 23 / 23 | 6 | 2 × 21 | *Crush*: Burst 1, 21, Prone; *Reform*: at 0 Vigor, returns next phase | Sorcerer: its mass |
| Skirmisher | A moving light of the domain (aurora, mirage, fire-drift) | 75 | 25 / 23 | 10, flying | 2 × 17, range 16 | *Disorient*: Ward check or Readings fail for a round; *Fade*: Hidden as a Quick | Warden: the domain's edge, where it turns back |
| Caster | A lesser embodiment | 75 | 23 / 25 | 6 | *Bolt* 1 × 28, range 16 | *Area* (2/fight): Line 12, 34, half on miss; *Sustain*: the domain condition in Burst 4; Strain 10 | Elementalist: which moon |
| Controller | A domain-weight (gravity, ice, rot) | 100 | 24 / 23 | 4 | 2 × 13 | *Pin*: Ward check or Speed 0 and Prone; *Drain*: Strain +2 to a target in Burst 2, Ward check halves | Sorcerer: the variable it holds |
| Support | A node-echo (heals the avatar) | 100 | 24 / 23 | 0 | 1 × 17 | *Restore*: the avatar or a manifestation regains 34; *Bind Part*: a destroyed part is not destroyed until the echo dies | Necromancer: the crossing count it feeds on |
| Elite | A domain guardian (a Master beast bound to the tether) | 280 | 25 / 24 | 6 | Tempo 2: 2 × 14 per Action | Its Master-tier kit; *Tethered*: cannot leave the domain; shake-off | Apothecarist: fails — not a living system |
| Boss | The avatar (§6.5) | 800 | by part (22–26) | 6 or 0 | Tempo 3: 3 Actions × 2 × 11; Interrupt strikes 8 | Three Interrupts; parts; the tether (§6.3) | Sorcerer: the tether's coordinates |

### 11.2 Three Mob blocks

**Garrison squad (Novice drill).** 10 · 2×5 · Cohesion 40 · Guard 14 / Ward 11 · Attack +4, 6 per hit, cap 3 · Speed 4 · Officer: a Novice Elite (sergeant) in the rear rank · *Shield step*: Guard +1 if it did not Move · Cohesion bonus +2 (+2 with the officer). Reads as (Sorcerer): the sergeant's square. TP 4 at Novice.

**Column line (Adept drill, Hammer).** 40 · 5×8 · Cohesion 240 · Guard 15 / Ward 12 · Attack +5, 8 per hit, cap 4 · Speed 5 · Officer: an Adept Elite (lieutenant) · *Hold flat*: on flat ground, Cohesion checks +2; in trees, −2 (Canon: holds anything flat) · *Breach front*: the front face deals double to structures. Reads as (Paladin): where the wall's weight sits. TP 10 at Adept.

**Doctrine line (Master drill, Glaive).** 40 · 5×8 · Cohesion 320 · Guard 16 / Ward 13 · Attack +6, 10 per hit, cap 5, reach 2 · Speed 6 · Officer: a Master Elite · *The circle*: a figure entering reach takes one attack as the Mob's Reaction (the only Mob Reaction in the game; Steel Quorum doctrine) · *Reshape as a Quick* (doctrine-certified). Reads as (Vanguard): the hinge square. TP 10 at Master.

### 11.3 Four contracts, filled

**Ledger posting, Novice.** *COBALT LEDGER · CONTRACT POSTING · Grimskov registry · Saelura 1245. Matter: emergence at the mill-pond below Ulvskov, node reading Novice as of Saelura. Tier rating: Novice. Fee: 4 seals, half on posting. Residue to be declared. Standing: noted. Assessor of record: [seal].* Not said (§8.6, 5): the pond is the mill's, and the miller's latent school is Nature.

**Chancel commission, Adept.** *GILT CHANCEL · COMMISSION · a Tepemitla parish · 12 Namaris 1245. Commissions the bearers to deny the den of the pack at the parish's north pasture, for the relief of the Namaris circuit. Benefice: 15 gilts on Assay certification. Sacramental property recovered is the Chancel's. Attribution: the commissioned alone.* Not said (2): the parish's own Apostle culled the first pack by attrition; the den-site reading stands.

**Circle request, Master.** *The keeper of the Shalei crossing says it once: the ground at the oasis is the beast's again; open the road before the Saelura turn. Owed: a way opened for the party's whole life on the crossing. Not the party's: the oasis water, and what the beast has killed.* Not said (8): the oasis is one of three sites the Threnis-phase claims name, and the other two have keepers who did not ask.

**Off-Ledger job, Master.** *Job: bring the Mwamba apex-claw out of the foothills before the Assay's inspector reaches Tinwara. Principal: not named. Priced: a portal manifest without inspection, once. Registration: not asked. Residue: the principal's, or the price is halved.* Not said (3): the claw is promised to a company that already holds it.

### 11.4 One Grand Beast per tier, with phases

Treatments of register rows (Canon XI.3; Canon Part VIII worked example). Illustrations, not canon beasts.

**Novice — the Deep Watcher at Novice tier** (otter; lake, node-active; Trait line). Boss line: Vigor 75, Guard 16 / Ward 15, Speed 6 (swim 8), Tempo 1, Interrupt 1 (a bite, 4). *Pattern:* submerge (Hidden, no attacks) → surface-drag (one attack, 12, and the target is pulled 2 paces toward water, Ward check) → recover (surfaced, Guard −4 if the pattern has been read). *Tell:* the water stills the turn before the drag. **Phase 2** (Vigor 37): trigger, half Vigor; change, the fight is at the water's edge — squares within 2 of the water are deep water at the end of each round; new ability, *Drag Under*: on a drag, the target starts drowning (PG deep water); new Reading, Warden: the bank it will surface at. Exploit executed: 1 Novice relic (the Watcher's tooth, §7.10).

**Adept — the Ulvskov pack** (wolf; taiga × Threnis, pack coordination; node Adept; Dependency on a den-site reading). Boss: the pack leader, Vigor 220, Guard 19 / Ward 18, Speed 8, Tempo 2, Interrupt 1 (a call: the band Moves). With it: a **band** of wolves (Mob, 5, sliding block, Novice drill, Cohesion 20). *Dependency:* the den site, a 30-Vigor structure of earth and root two squares across on the map; while intact, *Pack Coordination* (the band's attacks +2, and the leader's Interrupt) and Resist Frost. *Deny it:* two Actions at the site and a check vs DC 16 (any attribute the fiction supports), or break it. **Phase 2** (110): the leader Moves to the den and fights at it; the band engulfs whoever is adjacent to the site. **Phase 3** (55): damage ×1.25, Speed 10, no Interrupts; the band checks Cohesion at the leader's death. Dependency executed: 1 Adept relic (the den-earth pouch) and 1 Novice; the pack is wolves again.

**Master — Shalei burrow-dominant, 1155** (XI.3; desert × Threnis, burrow dominance; Master-active node; oasis dependency read as energy inversion). Boss: Vigor 450 (675 against a level-12 party), Guard 22 / Ward 21, Speed 6 (burrow 8 through sand), Large 2×2, Tempo 2, Interrupts 2 (a surfacing strike, 8; a Move of 3 underground). *Arena condition — burrow dominance:* the sand is the beast's: it moves through it ignoring Reactions and Prone, has Resist Stone, and every round each PC on sand makes a check vs DC 15 or is Slowed by sinking (the hazard). *Reversal:* wet the sand from the oasis — three sluice-cuts on the dune lip, each an Action and a check vs DC 18 (or a break: 15 Vigor each); when all three are cut the water runs and the arena is wet sand for two rounds: **window** — Guard 18, Vulnerable Stone, no burrowing, no Interrupts. **Phase 2** (337): the beast collapses the first cut (map change: the north sluice is a 40-Vigor bank); two cuts remain. **Phase 3** (225): the pool drains a pace; one cut remains, at the pool's edge, and the beast holds it. **Phase 4** (112): no reversal; the window is permanent; the beast is above ground, damage ×1.25. Reversal executed: the Shalei burrow-tooth (Master) and 1 Adept relic; the Shakou road reopens for a season (the record: reopened 1156).

**Guru — the Frostvatn manifestation, 1230–32** (XI.3; tundra with mountain overlay; Velquor, 1 Velquor 1230; node off prior scale; geographic tether, the lake basin). The record does not settle what it was (a beast; the lake mother — R.5 #6, not settled here either). Treatment as the avatar: 6×6, Speed 0 (the manifestation is the lake's edge), Vigor 800 per manifestation, Tempo 3, Interrupts 3. **Parts** (4; part Vigor 160): the shelf (Guard 26, the body; *Heave*: Burst 2, 21 Frost, Prone); two reaches of ice (Guard 22 each; 2 × 11 Frost, reach 3; destroying one removes a reach); the eye (Guard 26; *Lake-ice anomaly*: Ground scale, all water squares freeze and all frozen squares are unstable footing; *Drain*: Strain +2 in Burst 3, Ward check halves). *Manifestation destroyed:* it returns at the next Velquor phase, or at the next Firstday, at full, minus parts unseated. **Tether points** (the record names two operations; the campaign may add a third and must enter it): (1) the Iselva headwaters — diverted by a season's works or an Elemental Guru's sustained work: removes the eye's *Drain*; (2) the basin's substrate anchor — unseated by a Sorcerer Guru's edit at Ground scale with the overlay reading the anchor, or a joint operation of three Gurus: removes the shelf's *Heave* and ends the domain when both are done (Velquor 1232). Tether executed: the Frostvatn basin-shard (Guru, named) and two Master relics; the node reading falls one step and does not return to baseline.

### 11.5 One round, played: a level-9 party against the Shalei burrow-dominant, Phase 1

*Phase:* Velquor, eleven days before the Saelura turn. *Map:* the oasis basin, 20×20; the pool (deep water) fills the centre 6×6; sand elsewhere; the dune lip on the north edge with three sluice-cuts marked at squares N4, N10, N16; a 40-Vigor bank of packed earth along the lip. *Party:* Hexblade (Guard 24 with a Master helm, Vigor 95, Tempo 2), Warden (Guard 22, Vigor 90, Tempo 2), Elementalist (Ward 21, Vigor 75, Strain Capacity 15 — Velquor is adjacent to Saelura, no effect — Tempo 2), Apostle (Ward 21, Vigor 72, Strain Capacity 14 — Velquor is a far phase for Namaris, −1 — Tempo 2). Key modifiers +5. *Beast:* Guard 22 / Ward 21, Vigor 450, burrowed under the pool's east shore.

**Readings (0 Strain, before anyone acts).** Sorcerer absent. Elementalist: *the condition is dry sand; water reverses it.* Warden: *it will surface at the shore square nearest the Apostle.* Hexblade: *the seam is two rounds wide.* Apostle: *it knows the Saelura turn is eleven days off.*

**Hexblade, Tempo 2.** Move 6 to the shore square the Warden named. Action 1, *Strike* (Master form, two attacks): d20+11 vs 22 — 14+11 hits, 9+11 misses; damage d8 + d10 + 5 = 15. Action 2, a Master ability (2 Strain; the PG's counter-practitioner stance, name per PG): the next attack against him from a surfacing target is answered by a Reaction Strike first. Beast 435.

**Elementalist, Tempo 2.** Action 1, *Elemental Sweep* (3 Strain): Line 8 of Fire along the east shore, one roll compared to the beast's Ward 21: 12+11 hits; 3d10 + 5 = 21 Fire, and Burning 1 stack. Action 2, Core (0 Strain, Master form): 3d10 + 5 Frost, d20+11 vs Ward 21 — 8+11 misses. Strain 3 of 15 spent. Beast 414, Burning.

**Warden, Tempo 2.** Move 6 toward N4. Action 1, Dash to the cut. Action 2, the first sluice-cut: a check vs DC 18, d20 + 5 + 6 — 9+11 = 20, cut one. Two cuts remain.

**Apostle, Tempo 2.** Action 1, an Adept boon (2 Strain; name per PG): the Hexblade deals +1 RD this round. Action 2, Core (0 Strain): Sacred, 3d10 + 5 at Ward 21 — 15+11 hits, 21. Beast 393. Strain 2 of 14.

**Beast, Tempo 2, Interrupts already spent one** (after the Warden's turn it Moved 3 underground toward the Warden). Burning ticks 3: 390. Action 1, surface adjacent to the Warden — the Hexblade's stance is 6 paces away and does not trigger — Strike ×2 at +10 vs 22: 17+10 hits, 10; 6+10 misses. Warden 80. Action 2, *Sand-take* (arena ability): Burst 2 at the Warden's cut, each PC in it checks vs DC 15 or is Slowed; the Warden rolls 11+5+6, holds the cut. Its two Interrupts refresh at the start of its turn; it holds them for the party's next turns (a surfacing strike, 8, or a Move of 3 underground, at the end of any PC's turn).

**Round tally.** Beast 390 of 450 after one round; the party at Tempo 2 dealt 60 against an expected 130 (two misses and one wasted Action on Dash); a Boss's 3–4 rounds holds. Cuts: one of three. The Warden took 10; the beast's 55-a-round budget is 40 in Action attacks and 16 in Interrupts, and it spent one Interrupt on a Move. By round three the Elementalist, at 3 Strain a Sweep and Tempo 2, is one Sweep from Overdraw, which is the design: the Ledger arrives on turn three.

---

## 12. Calibration pass

### 12.1 Assumed PG damage model

The PG file was not available; the model below is reconstructed from the handoff's own figures (Hexblade Master = 2 × (d8 + d10 + 4); Elementalist Sweep = 3d10 + 4; "casters' 3 RD Core at Master"). **Check each line against the PG in the revision session.**

| Rank (level) | Key | Attack bonus | Core (caster) | Rank ability, single target | Strike (martial) |
|:--|:-:|:-:|:--|:--|:--|
| Novice (1) | +3 | +5 | 1d6 + 3 = 6.5 | Core + 1 RD = 10 | d8 + d6 + 3 = 11, one attack |
| Adept (5) | +4 | +8 | 2d8 + 4 = 13 | 17.5 | d8 + d8 + 4 = 13, one attack |
| Master (9) | +5 | +11 | 3d10 + 5 = 21.5 | 27 | 2 × (d8 + d10 + 5) = 30 |
| Guru (13) | +6 | +14 | 4d12 + 6 = 32 | 38.5 | 2 × (d8 + d12 + 6) = 34 (assumed two attacks) |

Hit chance against own-tier Guard / Ward: 60% at Novice, Adept, Master; 55% at Guru. Crits at 5%, ×2. Expected multiplier 0.65 / 0.65 / 0.65 / 0.60.

### 12.2 Expected damage

Per Action, then per turn at the design Tempo (1 / 2 / 2 / 3). Caster turn = one costed ability + Cores.

| Rank | Core | Rank ability | Strike | **Martial / turn** | **Caster / turn** | **Party of four / round** (2 martial, 1 caster, 1 support at 0.7 caster) |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|
| Novice | 4.2 | 6.5 | 7.2 | 7.2 | 6.5 | 25 |
| Adept, level 5 (Tempo 1) | 8.5 | 11.4 | 8.5 | 8.5 | 11.4 | 36 |
| Adept, levels 6–8 | 8.5 | 11.4 | 8.5 | 17 | 19.9 | 68 |
| Master, levels 9–11 | 14.0 | 17.6 | 19.5 | 39 | 31.6 | 132 |
| Master, level 12 (Tempo 3) | 14.0 | 17.6 | 19.5 | 58 | 45.6 | 196 |
| Guru | 19.2 | 23.1 | 20.4 | 61 | 61.5 | 227 |

### 12.3 Checks

| Check | Result | Finding |
|:--|:--|:--|
| (a) Casters vs martials within ~20% single-target | Novice 10%; Adept 17%; **Master: martial +23%**; Guru 1% | Master gap is the handoff's risk 4 and is intended (areas hit several targets). No change; re-check with the PG's actual Master ability list |
| (b) Area vs single-target ~60% per target | Sweep 20.5 vs Strike 30 = 68% on paper; with half-on-miss, expected 16.9 vs 19.5 = **87%** | Risk 1 confirmed. **Recommend:** half damage on a miss applies against standard enemies only; Elites and Bosses take nothing on a miss. Expected against a Boss becomes 13.3 = 68% ✓ (PG revision 6) |
| (c) Boss survives 3–4 rounds of a full party | Novice 75 / 25 = 3.0; Adept 220 / 68 = 3.2 (level 5: 110 / 36 = 3.1); Master 450 / 132 = 3.4 (level 12: 675 / 196 = 3.4); Guru 800 / 227 = 3.5 | ✓ at every band with the rescaled Vigor and the two Tempo adjustments |
| (d) Guru martial breaks a platoon of 40 in 2–4 rounds | §5.9: Novice drill 2, Adept 3, Master 3 | ✓ with Strikes alone; the PG's Guru Cohesion abilities can only shorten it |
| (e) Support boons ≈ one extra member | Master support: 0.7 caster (22) + *Extra* (one martial Action, 19.5) + Mend 20 a round ≈ 1.2 members | ✓; verify against the PG's Apostle Conviction economy (risk 6) |
| Incoming damage per Boss fight vs party Vigor | Novice 48 of ~150; Adept 102 of ~230; Master 187 of ~330; Guru 315 of ~560 | 30–55% of party Vigor a Boss fight. Three Breathers at a quarter each carry a 12-TP day; a Boss focusing one Master caster (75 Vigor) at 55 a round downs it in two rounds, so Support and Cover are load-bearing |
| Tempo and Strain | A level-12 caster at 2 + 3 + 3 Strain a turn against Capacity 15 is at Overdraw on turn 3 | Intended (risk 9). The no-repeat rule keeps the best spell to once a turn; the Ledger arrives on schedule |
| Gear and relics | Full Master kit: attack +1, damage +1, Guard +2, Vigor +10, Capacity +2 ≈ +8% output. Six Master relics (damage +3 ×2, attack +1 ×2, crit step, DoT) ≈ +35% | **The tier table assumes an Adept kit and two relics at Master.** A party with a full Master kit and six or more seated relics is run one budget step harder (Hard as Standard). Simpler than rescaling |
| Stun chain (risk 2) | Bosses once per phase; Elites once per source; a fight against two Elites and a Boss absorbs at most five Stuns across four phases | Holds at a table of four |
| Warlock snowball (risk 7) | Boss hex cap 3: Ward 21 − 3 = 18; caster +11 hits on 7+ = 70% | Absorbed |
| Summons (risk 8) | One Move and one Action on the summoner's turn | Table actions bounded at Tempo + 1 per summoner |
| Readings load (risk 10) | §10.2, §6.4, §5.8: one sentence each | Fast enough; the GM reads the row, not the beast |

### 12.4 Not testable without the PG

Berserker Gate 5 + *Hits That End Exchanges* + Cleave (risk 5): the burst is intended; the post-gate bill must be checked against the Ax cost column (§10.1). Apostle *Miracle* at 3 Conviction (risk 6): if available every second round at Tempo 2, raise to 4 or cap Conviction gain at 2 a round. Master Strike vs Core (risk 4): see (a).

---

## 13. Register

### 13.1 G-rows

Same columns as the PG's H-rows. **Status: all open** until Joe rules. Consolidation with H1–H33 waits for the PG file (§13.3).

| # | Rule | Touches canon | Where | Note / alternative |
|:-:|:--|:-:|:--|:--|
| G1 | Tempo: Actions 1 / 2 / 3 at levels 1 / 6 / 12; no costed ability twice a turn (D10) | No | §3 | Alternative: Tempo at rank boundaries (9, 13) — loses "a Master Sorcerer casts three" |
| G2 | Opposition tier table, rescaled Vigor; two Tempo adjustments | No | §4.2 | Handoff figures kept for Guard / Ward / Attack |
| G3 | Threat Points, cross-tier ×3 / ÷3, budgets 2 / 4 / 6 / 8, 12 TP a day | No | §4.6 | — |
| G4 | Elite hex cap 4, Boss hex cap 3; Boss Interrupts 1 / 1 / 2 / 3; Boss Ward check vs Ground hexes | No | §4.4 | D9 kept *Slow Field* whole |
| G5 | NPC Push and Overdraw, 3 Marks a session | Yes: cost is universal (Parts II–IV) | §4.5 | Alternative: NPCs never Push |
| G6 | Mob units band / squad / platoon (D6); Cohesion 4 / 6 / 8 per member; area and DoT double against Mobs; engulf; rout and break | Yes: the platoon standard (Part VI) | §5 | Alternative: sliding block only |
| G7 | Beast fight structures by tier; phase template | Yes: tier table (Part VIII), used as written | §6.3 | — |
| G8 | Readings-by-school tables, including the lines that fail (Apostle, Apothecarist, Berserker, Warlock at Guru) | Yes: Design Thesis; Part VIII payload ("not a monster; a response") | §6.4, §10.2, §5.8 | The failures are the partial-view rule made mechanical |
| G9 | Avatar parts, part Vigor, tether points as campaign objectives; the avatar returns unless the tether is unseated | Yes: Frostvatn (Part I, Part IX, XI.3) | §6.5 | — |
| G10 | Outcome lines drop relics by how the beast was beaten; no relic is made or copied | Yes: "environmentally produced, not designed" (Part VIII); R.8 no species list | §6.6, §7.6 | — |
| G11 | Eight gear slots (D11); weapons and shields carry no tier or socket | No | §7.1 | Alternative: one socket on the weapon |
| G12 | Trade grades Novice–Guru for makers | Yes: rank names are Ledger examination grades (Part VI, Terminology); extension to non-practitioner trades is new | §7.2 | Alternative: gear tier by Artificer rank only |
| G13 | Guru relic attribute "one line of a second school's Reading"; Guru alterations are bounded pieces of the five Guru abilities usable by any class | **Yes: one school per person (Premise; Part II D1)** | §7.5, §7.10 | The relic does the work, not the person; but a Warden holding a Necrotic line is a fragmentation question. Alternative: Guru alterations usable only by the relic's own school |
| G14 | Accord: relics are declared residue under the Manifest Rule | Yes: Manifest Rule (Part I) | §7.8 | — |
| G15 | Crown: Velquor-line relics contraband; Namaris-line relics sacramental property | Yes: Purge; Part VII sacramental apparatus | §7.8 | — |
| G16 | Chimera: a Threnis relic belongs to the ground; the keeper decides | Yes: way law, fire law (Part V) | §7.8 | — |
| G17 | Travel paces and fares; phase multipliers ×1 / ×1.5 / ×2 | Yes: Phase Cascade (Part V); numbers are records (Canon Discipline 5) — these are the game's, not the world's | §9.3 | Flag: if an episode ever states a fare, the episode's figure governs |
| G18 | Contract fee bands from the two anchor prices | Yes: Anchor Prices (Part V) | §8.3 | — |
| G19 | Reputation tracks per institution, 0–5 | Yes: institution mechanics (Part VI) | §8.4 | — |
| G20 | Consequences: Register entry, Assay audit, closed way, price; Ground-scale effects file automatically (D7) | Yes: Second Register; Assay; way law; Escrow | §8.5 | D7 alternative: filing is a scene, not a rule |
| G21 | Rank-up recognition table; unregistered practice filed on any Reading or inspection | Yes: Second Register (Part IX); Rank Distribution (Part II) | §9.1 | — |
| G22 | Biome × Moon cells as table mechanics; hazard damage = tier standard ×2 | Yes: grid (Part VIII), used as written; mechanics are new | §9.3 | Cells may be revised without touching the pattern (canon) |
| G23 | Moon rule: own phase Capacity +2, far phases −1 (D1 (a)) | Yes: cost varies by phase only (Part I, R.0) | §9.4 | Alternatives (b)–(d) in the handoff |
| G24 | Mark narration table by school and Stage | Yes: cost progressions (Parts II–IV), used verbatim | §10.1 | — |
| G25 | Improvised Joins: 2 Strain each, one scale step up, Ground refused below Guru, never narrated whole | Yes: Design Thesis | §10.3 | — |
| G26 | The End procedure (Chronicle port, unverified); the campaign keeps a record as a reputation step | Yes: cost as the End of practice (Parts II–IV) | §10.7 | Check against Chronicle GMG v0.3 |
| G27 | Carried Back, optional (D5) | Yes: death permanence in the PG; Nature Master "cannot always cure" | §10.7 | Off by default |
| G28 | Structures table and which abilities target them | No | §10.8 | — |
| G29 | Stun budget: Bosses once per phase | No | §10.4 | — |
| G30 | Sample relics: five Guru relics tied to the five Guru abilities; the Frostvatn shard's Necrotic line | Yes: the five Guru abilities (Part II, ratified) | §7.10 | See G13 |
| G31 | Exemplar beasts: Deep Watcher at Novice; Ulvskov pack (illustration, not entered); Shalei 1155; Frostvatn 1230–32 treated without settling R.5 #6 | Yes: XI.3 rows; Part VIII worked example; XI.6 | §11.4 | None entered; none named beyond the register |
| G32 | Guru-tier "standard" opposition redefined as manifestations of the node | Yes: Rank Distribution (Gurus are a roll, not a rate) | §11.1 | — |
| G33 | Half damage on a miss: standard enemies only (recommended) | No | §12.3 (b) | PG revision 6 |

### 13.2 PG revisions required (to apply in the PG's own register, not here)

| # | PG section | Change | Reason |
|:-:|:--|:--|:--|
| 1 | §13.1 level table | Level 6: add "Tempo 2". Level 12: add "Tempo 3" | G1 |
| 2 | Turn structure | "Move + Action + Quick + Reaction" → "Move + Actions (Tempo) + Quick + Reaction"; add the no-repeat rule; Sustained unchanged | G1 |
| 3 | Summons (all classes with a familiar, golem, turret, construct, companion) | Act on the summoner's turn, one Move and one Action, sharing its Quick | Risk 8 |
| 4 | New section: Gear | Eight slots, tiers, intrinsics, one socket each, seating rules, Trinket over-rank bond; PG armor and weapon values unchanged | G11, D4 |
| 5 | New section: Relics (player-facing) | Rank, attribute catalogue, governors, seating cap, same attribute in two sockets | §7.5 |
| 6 | Areas | Half damage on a miss against standard enemies only | Risk 1 |
| 7 | Hexes | Elite cap 4, Boss cap 3; Boss once-per-phase Stun; Boss Ward check on Ground hexes | G4, G29 |
| 8 | Strain | Moon rule (D1) | G23 |
| 9 | Death | Optional Carried Back, if Joe accepts D5's second option | G27 |
| 10 | Verify only | Apostle Conviction / Miracle rate; Berserker post-gate bill; Master Strike vs Core | Risks 4–6 |

### 13.3 Revision session

Load: this file; the PG (whole); Chronicle GMG v0.3 §§ Lines / Cohesion, §9, the End; Grand Beasts v0.2 §2 and its register; Canon Part VIII only. Verify the three ports (§5, §7 against Chronicle §9, §10.7), the damage model (§12.1) against the PG's class entries, and every ability name in §11 against the PG. Consolidate G1–G33 with H1–H33 into one table. Apply §13.2 to the PG. Do not load the whole Canon; nothing in this file needs it.

**Context note.** This draft was written in one session at about 18,000 words after loading the handoff and roughly 15,000 tokens of Canon; the revision pass should start fresh with the four files above and nothing else.

### 13.4 Chronicle ↔ Heroes (D8)

Declared incompatible at the sheet level. A Chronicle character enters Heroes at the level that opens its rank (1 / 5 / 9 / 13), keeps its school, its Marks count, and its Stage, and re-picks abilities, talents, and gear from the PG. Chronicle relics (bond model) become Heroes relics of the same rank with an attribute chosen from the catalogue and the governor of their origin tier. Nothing converts the other way.
