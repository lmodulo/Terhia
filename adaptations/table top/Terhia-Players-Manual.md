# Terhia — Player's Manual

Tabletop rules, draft v0.3 (24 September 2026). Built against Terhia-Canon v1.1. v0.3 adds gear and relics (section 10) and the hooks they need in sections 5, 6, and 13.

**Scope.** This manual holds the rules a player needs: the check, attributes, the cost engine, turns and engagements, readings, gear and relics, and the twelve classes with their techniques and cost stages. It does not explain the world. Grand beasts, factions, institutions, cultures, and money are separate modules; where a rule below points at one of them, the pointer is marked *(module)* and carries an interim rule to use until the module exists.

**Reading order.** To play: sections 1–8, then your class entry in section 12. Sections 9–11 and 13 as they come up. A player needs neither the Game Master's Guide nor the Canon to play.

**Dice.** The standard set: d4, d6, d8, d10, d12, d20. d100 is two d10.

**Distance and time.** Distances are in paces. An engagement is fought in rounds; each character takes one turn per round. A scene is a continuous stretch of play. A day, a phase (80 days), and a year (400 days, five phases) are the units of rest and downtime.

---

## 1. What a character is

Every character in Terhia is born with one **school** and only one. A character who has trained that school is a **practitioner** and has a **rank**; a character who has not is a **latent** (section 11). Player characters are practitioners unless the table decides otherwise.

Culture and homeland do not fix the school. A culture's characteristic occupations — pilotage, well-keeping, terrace farming, fire-lineage burning — are trades (section 9), held by practitioners of any school and by latents.

There are twelve schools in three types:

| Type | Schools | Class (registry name) |
|:--|:--|:--|
| Magic | Necrotic, Elemental, Arcane, Divine, Nature | Necromancer, Elementalist, Sorcerer, Apostle, Apothecarist |
| Martial | Sword/Shield, Glaive, Longbow, Hammer, Ax | Hexblade, Vanguard, Warden, Paladin, Berserker |
| Alchemy | Light Arts, Dark Arts | Artificer, Warlock |

A school has four ranks: **Novice, Adept, Master, Guru.** Rank determines a character's **Rank Die** (d4, d6, d8, d12), which techniques they can use, the scale they can work at, and the minimum **cost stage** their body carries.

**Power is paid for.** Every technique draws **Strain** from the body. Strain past the body's line becomes **Marks**. Marks are permanent, and enough of them advance the practitioner's **cost stage**, which never reverses. Section 6 holds the engine.

**The design principle, stated as a rule.** No character perceives the whole of any scene. Each school reads one **layer** of the world and is blind to the rest. The rules never give one player the joined picture; the table assembles it, or fails to, by talking. Section 8 holds the procedure.

---

## 2. The Check

**Check = d20 + attribute modifier + Rank Die (school work only).**

Compare the total to a **Difficulty** set by the GM, or to an opponent's total in an opposed check. Equal or higher succeeds.

- The Rank Die is added only when the check is work of your own school: a technique, a school reading, an attack with your school's weapon. All other checks are d20 + modifier.
- When a technique has a magnitude (damage, paces, turns, cups, Cohesion), the magnitude is the **Rank Die result shown on that same check**, plus any listed modifier. One roll answers both whether and how much.
- **Natural 20:** success, and the Rank Die counts as its maximum.
- **Natural 1:** failure. Strain and Marks are still paid. Any Held technique you are maintaining breaks.
- **Favor / Hindrance:** roll the d20 twice and keep the higher / lower. Favor and Hindrance cancel one for one. They never apply to the Rank Die.

| Difficulty | Number |
|:--|:-:|
| Easy | 10 |
| Moderate | 13 |
| Hard | 16 |
| Severe | 19 |
| Master-grade | 22 |
| Guru-grade | 26 |
| Beyond one hand | 30 — reachable only by a **Join** (section 8) |

---

## 3. Attributes

Six attributes, scored 3–18. Modifier = (score − 10) ÷ 2, rounded down.

| Score | 3 | 4–5 | 6–7 | 8–9 | 10–11 | 12–13 | 14–15 | 16–17 | 18 |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Modifier | −4 | −3 | −2 | −1 | 0 | +1 | +2 | +3 | +4 |

| Attribute | What it governs | Schools keyed to it |
|:--|:--|:--|
| **Frame** | Force, weight, carrying, holding ground, breaking things | Hammer, Ax |
| **Poise** | Reach, timing, precision, balance, Guard, initiative | Sword/Shield, Glaive, Longbow |
| **Reserve** | The body's depth: Vigor, Strain Capacity, resisting poison, pain, exhaustion, and cost | — (every practitioner's capacity) |
| **Reckoning** | Measuring, reading structure, counting, memory, craft, letters, seals, contracts | Arcane, Light Arts, Dark Arts |
| **Attunement** | Feeling what answers: the living, the dead, the elements; animals; noticing by relation | Elemental, Nature, Necrotic |
| **Standing** | Presence and voice as they land on others; command; being believed; holding a group; the calling-back | Divine |

**Notice.** Perceiving the Plain layer (section 8) is a Reckoning check or an Attunement check, the player's choice each time. The GM describes what is found in the terms of the attribute used — measured, or felt.

---

## 4. Derived values

| Value | Formula |
|:--|:--|
| **Vigor** | Base by type (Martial 12, Alchemy 10, Magic 8) + Reserve modifier + 4 per rank above Novice |
| **Guard** | 10 + Poise modifier + armor + shield + martial rank bonus (Novice +1, Adept +2, Master +3, Guru +4; martial schools only) |
| **Strain Capacity** | By rank (Novice 9, Adept 11, Master 13, Guru 17) + Reserve modifier − bonds (section 6) |
| **Movement** | 6 paces per Move |
| **Initiative** | d20 + Poise modifier; martial practitioners add their Rank Die |
| **Marks** | Start at 0 |
| **Cost stage** | Start at the rank minimum (Novice 0, Adept 1, Master 2, Guru 3) |

---

## 5. Creating a character

1. **Choose a school.** The class name follows from it (section 1). Read its entry in section 12.
2. **Assign attributes.** Place 15, 14, 13, 12, 10, 8 as you choose; or roll 4d6 six times, drop the lowest die each time, and assign.
3. **Set rank.** Novice by default. A table that starts at Adept applies the rank's minimum cost stage and its Stage 1 effect from the first session.
4. **Compute derived values** (section 4).
5. **Learn techniques.** A starting character knows the school's free Reading and **two** other techniques of its rank. The rest are learned in play (section 6, Advancement).
6. **Tongue.** Record a birth tongue *(culture module; until it exists, the language of the character's culture — each culture has one; Canon Part V, Culture Profiles)* and a Common Tongue grade (section 9). Practitioners who have sat a registry board have Registry grade.
7. **Two Trades** (section 9).
8. **Kit** from the class entry — all of it Novice gear, with no relics (section 10) — plus ordinary clothing, a bedroll, rations for a phase turn, and starting coin *(economy module; until it exists, 10 seals; Canon Part V, Economic Baseline — Money and Anchor Prices — for what a seal buys)*.
9. **Open the ledger.** Write Strain 0 / Capacity, Marks 0 / 10, Stage as set. This block is the character's cost file; keep it current.

---

## 6. The Ledger: Strain, Overdraw, Marks, Stage

### Strain

Every technique has a Strain cost, listed in its entry. Basic weapon use, movement, and the free Reading cost nothing.

| Tier of technique | Typical cost | Typical upkeep per turn (Held) |
|:--|:-:|:-:|
| Novice | 1 | 1 |
| Adept | 2 | 1 |
| Master | 3 | 2 |
| Guru | 5 | 3 |

Strain accumulates during play. It cannot exceed Capacity except by Overdraw.

**Rest.** A short rest (an hour, no exertion) clears half of current Strain, rounded down. A full rest (a night, eight hours) clears all of it. Some cost stages restrict rest; the class entry says so.

### Overdraw

If a technique's cost would take Strain above Capacity, the practitioner may still use it. Every point above Capacity is taken as a **Mark** instead of Strain. Marks are recorded permanently. The technique resolves normally.

A practitioner always *can* act. The question is what it costs.

### Marks and Stage

When Marks reach **10**, the cost stage advances by one and Marks reset to 0. Stage is permanent and only ever rises. Each school has four named stages and an **End**; the effects are in the class entries. Effects accumulate: a Stage 3 practitioner carries Stages 1, 2, and 3.

**Rank minimums.** Adept is Stage 1 or higher; Master is Stage 2 or higher; Guru is Stage 3 or higher. On advancing rank, a practitioner below the minimum rises to it and Marks reset to 0. A practitioner already at or above it is unchanged and keeps their Marks.

**Mark-costed techniques.** Some techniques list a cost in Marks (M) rather than Strain. They cannot be paid with Strain unless a phase rule allows it. They are the techniques whose cost is the technique.

**Bonds.** Familiars, golems, and seated relics (section 10) are bonds. Each bond reduces Strain Capacity by the amount listed for as long as the bond exists. Releasing a bond (a scene of unbinding, or the construct's destruction; for a relic, unseating it) restores the capacity.

### The End

At Stage 4, when Marks reach 10 again, the practitioner reaches their school's End. The End is a scene, played by the GM and the player together, after which the character leaves play in the manner the class entry names. Nothing in these rules reverses a stage; one Guru technique can reset a Stage 4 practitioner's Marks to 0 (Apostle, *Years for Years*), which buys time and nothing else.

### Phase pricing (magic schools only)

The five moons hold phase in a fixed cycle: **Velquor → Saelura → Orrivane → Namaris → Threnis → Velquor.** Each magic school has one moon. The current phase modifies the school's costs:

| Current phase relative to the school's moon | Strain costs | Mark costs |
|:--|:--|:--|
| **Own** phase | −1 (minimum 1) | May be paid as 4 Strain per Mark instead |
| **Adjacent** phase (either neighbor in the cycle) | As written | As written |
| **Far** phase (either of the other two) | +1 | As written |

| School (moon) | Own | Adjacent | Far |
|:--|:--|:--|:--|
| Necrotic (Velquor) | Velquor | Threnis, Saelura | Orrivane, Namaris |
| Elemental (Saelura) | Saelura | Velquor, Orrivane | Namaris, Threnis |
| Arcane (Orrivane) | Orrivane | Saelura, Namaris | Threnis, Velquor |
| Divine (Namaris) | Namaris | Orrivane, Threnis | Velquor, Saelura |
| Nature (Threnis) | Threnis | Namaris, Velquor | Saelura, Orrivane |

Martial and alchemy schools have no moon and no phase modifier.

**Procedure.** The modifier changes only at a phase turn, once in eighty days. At creation and at each phase turn, write on the sheet the school's modifier for the current phase (−1, 0, or +1) and whether Marks may be paid as Strain this phase (own phase only). Mark each seated relic the same way: whether the new phase is one of the relic's far phases (section 10). Price every technique from the sheet. The moon table is consulted at the phase turn and not again until the next; the GM announces the phase, and the sheet carries the number.

### Advancement

- **Techniques.** At the end of each session, a player may add one technique of the character's current rank that the character does not yet know. The GM may allow a second for a session in which the character's school work was decisive.
- **Rank.** A character who knows every technique of their rank may sit for the next rank during a downtime phase. Novice to Adept and Adept to Master require a teacher or examiner of the higher rank *(institutions module for who examines; the Game Master's Guide §8 gives the interim rule)*. Master to Guru requires a Guru of the school or a Guru-grade deed witnessed and recorded. On advancing: new Rank Die, new Strain Capacity, new Vigor, +1 to one attribute (maximum 18), and the rank's minimum cost stage.
- **Staying.** A character may decline to sit. An Adept who never sits for Master keeps a Stage 1 body for as long as they never overdraw past 10 Marks. Declining is a choice the rules respect.

---

## 7. Turns and engagements

### Initiative

When an engagement begins, everyone rolls Initiative (section 4). Act in descending order each round. Ties: higher Poise score, then martial before magic before alchemy. Characters who did not know the engagement was beginning are **Surprised**: they act last in the first round and have no Ready that round. A character maintaining *Watch* or *Overwatch* is never Surprised.

### The turn

On your turn, in any order:

- **Move** — up to 6 paces. May be taken twice if you take no Act.
- **Act** — one technique marked Act, or one attack, or an ordinary action of comparable weight.
- **Ready** — one technique marked Ready, or a minor action (draw, drop, speak a sentence, open a door), or hold a Reaction until your next turn.

At the **start** of your turn, before anything else: pay upkeep on every Held technique you are maintaining, or let it drop; resolve ongoing effects on you (burning, poison, Downed checks).

### Held techniques

A Held technique begins on the turn it is used and continues while the practitioner pays its upkeep and gives it the action its entry names (Act or Ready) each turn. It drops when upkeep is not paid, when the practitioner chooses, on a natural 1, or when **attention breaks**: whenever a practitioner maintaining a Held technique takes damage, they make a Reserve check at Difficulty 10 + damage taken, or the hold drops. When an edit on the substrate drops, the substrate reasserts at once: what was slowed runs, what was held falls.

### Attacks

- **Melee:** d20 + Frame or Poise (whichever your school uses; Frame for anyone else) + Rank Die (school weapon only) vs the target's Guard. Reach 1 pace (glaive 2).
- **Ranged:** d20 + Poise + Rank Die (school weapon only) vs Guard. Beyond half range, Hindrance. Throwing range 10 paces.
- **Damage:** weapon die + the attribute modifier used to hit + the Rank Die result from the attack roll (school weapon only). Armor is already in Guard; it does not reduce damage.
- **Cover:** half cover +2 Guard, full cover cannot be targeted. Concealment: attacker has Hindrance.
- **Numbers:** three or more attackers adjacent to one target each have Favor, unless the target's class says otherwise.

### Vigor, Downed, and crossing

Damage reduces Vigor. At 0 Vigor a character is **Downed**: prone, unable to Move, Act, or Ready. At the start of each of their turns while Downed, they make a Reserve check at Difficulty 10 + turns Downed; on a failure they **cross** (die). Any restoration of Vigor above 0 ends Downed. A Nature Adept's *Steady* or a Divine Master's *Boon: resolve* suspends the checks.

A character reduced to 0 by a single hit that also exceeds their maximum Vigor crosses at once.

### Conditions

| Condition | Effect |
|:--|:--|
| **Prone** | Half movement to rise (costs a Move); melee attackers have Favor; ranged attackers Hindrance |
| **Frightened** | Cannot willingly move closer to the source; −2 on all checks while it is in view |
| **Stuck** | Cannot Move; Frame check at the listed Difficulty (Act) to free |
| **Sickened** | −2 on all checks; cannot pay upkeep on Held techniques |
| **Exhausted** | −2 on all checks per level; at level 3, Downed; one level clears per full rest |
| **Burning** | d4 damage at the start of each turn until a Move is spent to smother it |
| **Poisoned** | As the poison's entry; ended by the listed Reserve check or a purgative of sufficient grade |
| **Unconscious** | As Downed, without the crossing checks |

### Lines

A formation of soldiers is a **Line**, a single entity with **Cohesion** instead of Vigor. Only techniques that say "Cohesion" damage it directly; other damage to its members is pooled by the GM at one Cohesion per 10 Vigor. A Line at 0 Cohesion breaks into individuals. Master martial techniques reach a Line; Guru martial techniques are built for one. Full Line rules are in the Game Master's Guide.

### Healing at a glance

Vigor returns at a full rest: Reserve modifier + 4, minimum 4. A short rest restores nothing. The Nature Master's *Channel Work* and the Divine Master's *Mend* are the only techniques that restore Vigor outright; the Divine Adept's *Encourage* grants Vigor that fades at rest. The Divine Master's cost is paid in Marks. A cure and a healing are not the same thing, and the rules keep them apart.

---

## 8. Readings and layers

A scene holds information in **layers**. The **Plain layer** — what eyes, ears, and hands give anyone — is open to everyone through Notice. Every other layer is open only to a school, and only at the grade the practitioner's rank allows.

| Layer | Read by | What it holds |
|:--|:--|:--|
| **Structure** | Arcane | Mass, motion, load, composition, position; where a thing will be |
| **Life** | Nature | What lives, its condition, where damage sits, what it needs, what relates to what |
| **Boundary** | Necrotic | What died, when, how, in what register; the moment of crossing |
| **Intent** | Divine | What people feel and mean; where fear, calm, resolve, and hostility sit |
| **Element** | Elemental | What fire, water, air, and ground are doing and will do next |
| **Make** | Light Arts, Dark Arts | How a thing was made, bound, or dosed; what it carries; whose work it is |
| **Field** | The five martial schools, one aspect each | Sword/Shield: **Weight** (who will commit, and how). Glaive: **Geometry** (corridors, hinges, where the melee flows). Longbow: **Ground** (distance, cover, approaches). Hammer: **Seams** (where a thing breaks). Ax: **Nerve** (who holds, who breaks) |

**Grades.** A reading returns more as rank rises:

| Rank | Returns | Scale |
|:--|:--|:--|
| Novice | One fact, imprecise | Personal (touch, or what is near) |
| Adept | Two facts, one of them precise | Personal, deepened by contact |
| Master | Three facts, all precise | Circle (20 paces) |
| Guru | The layer entire | Ground (a valley, a ward, a harbor) |

**Procedure.** The free Reading of your school is a Ready action and costs nothing. Higher-grade readings are techniques with listed costs. The GM delivers what a reading returns **to the reading player alone** — by note, whisper, or side channel. What the character then says aloud is the player's sentence, not the GM's fact. Others act on the sentence.

**The Join.** The joined picture of a scene is never narrated. Any task at Difficulty 30 is beyond one practitioner: it requires two practitioners of different schools each to succeed at Difficulty 22 on their own layer of the same problem. Certain outcomes exist only as Joins; the Game Master's Guide lists the standing ones.

**Records.** Every number the GM gives is a record kept by someone: a count, a roll, a tally, a story. Two records of one thing may disagree, and both stand. A player may always ask who counted.

---

## 9. Tongue and trades

**Common Tongue grade.** None (a few market words), **Market** (trade, tolls, numbers, short instructions), or **Registry** (full; the language of boards, contracts, and courts). Practitioners who have sat a board have Registry grade. A reading relayed to someone who does not share the reader's birth tongue arrives intact only if both have Registry grade; at Market grade, the GM reduces it to its plainest fact; at None, it does not arrive.

**Trades.** Each character has two trades — a line of ordinary work: pilotage, caravan work, letters, smithing, herding, fishing, terrace farming, well-keeping, registry clerking, midwifery, fire-lineage burning, or any the table agrees. A trade gives +2 on checks that fall squarely within it, and a registry trade gives Registry grade Common Tongue.

---

## 10. Equipment

| Weapon | Die | Notes |
|:--|:-:|:--|
| Dagger | d4 | Throwable; the Warden's close weapon |
| Staff, club | d6 | — |
| Hand ax, mace | d6 | — |
| Sword, spear | d8 | Spear reach 2 |
| Longbow | d8 | Range 200 paces; two hands |
| Sling | d4 | Range 40 paces |
| Glaive | d10 | Reach 2; two hands |
| Maul, warhammer | d10 | Two hands |
| Great ax | d12 | Two hands |

| Armor | Guard | Notes |
|:--|:-:|:--|
| Padded or leather | +1 | — |
| Mail | +2 | −1 on Poise checks |
| Plate | +3 | −2 on Poise checks; +1 Strain on every magic technique |
| Shield | +2 | +1 if not Sword/Shield school |

Alchemists need a **field kit** (portable; Novice work) or a **bench** (a room and a day to set up; Adept and higher work). Necrotic practitioners work bare-handed; gloves make their readings Hindered.

Weapons, shields, and armor give what the tables say and nothing more. The school weapon already carries the Rank Die, the largest bonus any equipment gives, and nothing below adds to it. Armor is worn in the chest slot.

### Gear

Six **slots**: head, chest, gloves, boots, ring, amulet. A slot holds one piece of **gear**. Gear has a **tier** — Novice, Adept, Master, Guru — which is the rank of the practitioner who made it; the Make layer reads it (section 8). Anyone wears gear of any tier. Tier fixes what the piece gives and how many **sockets** it has; sockets hold **relics**.

| Tier | Made by | Gives | Sockets |
|:--|:--|:--|:--|
| Novice | Any smith or tailor. Ordinary clothing, boots, and gloves; the armor table above | Nothing beyond the tables | 0 — a Master-trade smith or jeweler cuts one socket into a Novice piece for a day's work and a seal |
| Adept | An Adept Artificer at the bench, or a Master craft trade | The slot's Adept line | 1 |
| Master | A Master Artificer's *System*-grade work, days at the bench | The slot's Adept and Master lines | 2 |
| Guru | A Guru Artificer, if anyone; each piece is named, and the roll of them is short | Written by the Game Master | 3 |

| Slot | Adept gear | Master gear, in addition |
|:--|:--|:--|
| **Head** | +1 Initiative | Never Surprised |
| **Chest** | +1 maximum Vigor; Guard as the armor table | The armor's penalties are removed: mail's and plate's Poise penalty, plate's magic Strain |
| **Gloves** | +1 damage with the school weapon | Favor on lockwork, bench work, and other fine-work checks |
| **Boots** | Movement 7 | *Footing*: not knocked prone or moved by shoves, water, or ground effects below Master tier |
| **Ring** | Strain Capacity +1 | One Held technique's upkeep is −1 per turn (minimum 1) |
| **Amulet** | Your school's far phases are priced as adjacent — Strain costs only; magic schools | One seated relic, named at the phase turn, treats its far phases as adjacent |

A socket holds one relic of the gear's tier or lower. Gear never adds a flat bonus to a check total; Initiative and damage are not checks. No amulet extends the own-phase rule that lets Marks be paid as Strain. A Necrotic practitioner has no gloves slot. Martial and alchemy schools have no moon; their Adept amulet gives nothing until a relic is seated in it.

### Relics

A relic is what an emergence leaves: a grand beast's trait, a shard of the site its enhancement drew on, the remains of a dominance broken, a fragment of a tether. Nobody makes one. It comes from the ground as the beast did, with the beast's fields on its record — base animal, ground, moon at emergence, tier — and its own designation. The Game Master writes a relic when it is found; the player records it when it is seated. A character starts play with none.

**A seated relic is a bond.** While it is seated in gear you wear, it reduces your Strain Capacity by its Capacity cost (section 6, Bonds). Unseating it restores the capacity. The relic draws on the wearer as the beast drew on its ground, and the bill is the wearer's.

| Tier | Gives | Governed by | Capacity |
|:--|:--|:--|:-:|
| Novice | A **Trait**: small, always on | A **Rigidity** — one fixed condition: first use each scene only; not by night; not against a Line; only while you are above half Vigor; only on ground of the biome it came from | −1 |
| Adept | An **Enhancement**: an effect of Adept-technique scale | A **Dependency** — it feeds: 1 Strain each time it is used; or 1 Strain per scene it is worn; or it is inert in the relic's far phases | −1 |
| Master | A **Dominance**: a strong effect | An **Inversion** — in the relic's far phases the effect runs the other way | −2 |
| Guru | A fragment of a **Domain**: one effect at Line or Ground scale | A **Tether** — inert away from its ground, or bound to you at 1 Mark per phase it stays seated | −3 |

**Moons.** A relic has a moon — the phase at its emergence — and its own, adjacent, and far phases follow the cycle in section 6. Write the moon on the sheet beside the relic. At each phase turn, mark whether the new phase is one of its far phases; the Dependency and the Inversion read from that mark.

**Dice.** Where a relic's effect names a die, it is the die of the relic's tier: d4, d6, d8, d12. "Rank Die" is the wearer's.

**Reading a relic.** The effect is known the first time it is used. The governor is known when a reading returns it — Life for a Dependency, Element for an Inversion, Structure or Notice (Difficulty 13, after a scene of wearing) for a Rigidity — or once it has shown twice. Until then the Game Master applies it and says so; the ledger is charged either way.

**Seating.** An Artificer of at least the relic's tier seats it as bench work at the tier's Strain cost (Novice 1, Adept 2, Master 3, Guru 5). A Master-trade smith or jeweler seats a Novice or Adept relic for a day and a seal per tier. A relic sits in one socket; moving it is unseating and seating again. Guard from relics is +2 at most, whatever is seated.

**What a relic gives.** The Game Master writes each relic as one line from this table — one domain, at the emergence's tier, with a governor from the tier's row above. The Master column reads *effect / what it becomes in the relic's far phases*. Guru relics are written by the Game Master as Guru beasts are.

| Domain | Novice (Trait) | Adept (Enhancement) | Master (Dominance / Inversion) |
|:--|:--|:--|:--|
| **Damage** | +1 damage with the school weapon | 1 Strain: roll the Rank Die twice for damage on one attack, once per scene | Weapon die one step up / one step down |
| **Guard** | +1 Guard | 1 Strain, Reaction: halve the damage of one hit | +2 Guard / −2 Guard |
| **Burning** | Your first hit each scene: the target is Burning | 1 Strain on a hit: the target is Burning | Every hit: Burning / your hits set nothing, and the first hit on you each scene sets you Burning |
| **Poison** | Your school weapon carries a coat as *Stable Poison* (d4 at the start of the victim's turn for d4 turns; Reserve check at Difficulty 12 ends it), renewed at each full rest | At each full rest, 1 Strain: the coat is *Graded Venom*, numbing (−d6 Poise) or weakening (−d6 Frame); Reserve check at Difficulty 14 resists | Every hit: killing grade, d6 at the start of each of the victim's turns, Reserve check at Difficulty 14 ends it / the coat is inert |
| **Vigor** | — (healing has no free tier) | At the start of your turn, your choice: recover 1 Vigor and take 1 Strain | Once per scene: roll d8, recover that much Vigor and take that much Strain / 1 Strain at the start of each of your turns, nothing back |
| **Strain** | The first point of Strain you take each scene is not taken | Techniques of Novice and Adept tier cost −1 Strain (minimum 1) | Every technique costs −1 Strain (minimum 1) / +1 Strain |
| **Movement** | Movement +1 | 1 Strain: take two Moves and an Act this turn, once per scene | Movement +2, and difficult ground does not slow you / Movement −2 |
| **Reading** | Notice with Favor | 1 Strain: your school's free Reading returns one more fact, once per scene | Your school's readings return one grade more in facts, at your own scale / one grade fewer |

Relics do what the table says and nothing else. No relic returns another school's layer, and none reaches a scale your rank does not; a reading relic deepens your own layer at your own scale. Strain from a relic is Strain: past Capacity it is Marks, as always.

---

## 11. Latents (optional)

A latent has a school and no training. No Rank Die, no techniques, no Strain, no Marks, no stage. Instead, a **Knack**: once per scene the GM gives the latent their school's Novice reading as a hunch, unasked, and one narrow, reliable use of the school that fits their trade (weather a day early; a voice that steadies a labor; cattle that follow). A latent can train: one full phase with a teacher of the school makes a Novice.

---

## 12. The twelve classes

Each entry gives: keyed attribute, moon, reading, working terms (what practitioners call the practice), Vigor base, kit, techniques by rank, and cost stages.

**Technique notation.** *Name* — Mode · Action · Cost. Modes: **Instant** (resolves now), **Held** (upkeep each turn; the action named is what it takes each turn), **Reading** (returns layer information), **Reaction** (triggered; uses your Ready), **Bench** (made during rest; cost paid then), **Bond** (permanent; cost is capacity), **Passive** (always on). Costs are Strain unless marked **M** (Marks). "Rank Die" means the result rolled on the check that resolved the technique. "Circle" is 10 paces unless stated; "Line" is a formation; "Ground" is a landscape feature.

### Elementalist (Elemental)

Attribute: Attunement · Moon: Saelura · Reading: Element · Working terms: sustained work; harbor-keeping; aquifer-holding · Vigor base 8 · Kit: staff or spear, leather.

**Novice**
- *Read the Element* — Reading · Ready · 0. Element layer at Novice grade.
- *Kindle* — Instant · Act · 1. Ignite flammable material within 5 paces, or put out a fire up to a campfire's size.
- *Draw Water* — Instant · Act · 1. Rank Die cups of clean water into a vessel or cupped hands.
- *Breath of Air* — Instant · Ready · 1. Within 5 paces: snuff candle-size flames, clear smoke from your space, shift a light object one pace, or give one missile attack against you Hindrance this turn.

**Adept.** *Responding element:* on reaching Adept, choose the element that answers — fire, water, air, or ground. Techniques of that element use the Rank Die normally; techniques of the other three use d4 as the Rank Die at any rank. *Imprecision:* on any Adept elemental technique whose check totals below 13, the effect lands but the GM places it one pace off the intended point.
- *Lash* — Instant · Act · 2. One target within 10 paces: check vs Guard; Rank Die + Attunement damage. Fire: target Burning. Water: prone if the Rank Die shows 4 or more. Air: pushed Rank Die paces. Ground: Stuck (Difficulty 12).
- *Shroud* — Held · Ready · 2, +1/turn. Smoke, spray, dust, or wind at Personal scale: attacks on you from beyond 2 paces have Hindrance; you are concealed from anyone farther than 5 paces.
- *Shape* — Instant · Act · 2. Move a cart-load of your element within 5 paces: fill a trench, raise a knee-high bank, bend a hearth fire into a doorway. A shaped hazard deals Rank Die damage to anything that enters it and lasts the scene.

**Master.** *Specialization:* the responding element is fixed. Choose a sub-discipline naming the functional-scale product you make without a check: forge or war (fire); harbor or well (water); sail or storm (air); road or wall (ground).
- *Work at Scale* — Held · Act · 3, +2/turn. Produce your element at functional scale in a Circle: a well's draw of water, a forge's fire, a wind that fills a sail, a wall of packed earth a pace thick, per turn held.
- *Sweep* — Instant · Act · 3. Everything within 5 paces of a point within 20 paces: check vs each Guard; Rank Die + Attunement damage and the element's Lash effect. A Line loses Rank Die ÷ 2 Cohesion.
- *Still* — Instant · Act · 3. Within a Circle, your element stops for Rank Die turns: fire does not spread, water goes flat, wind dies, ground stops moving. Ends any Elemental technique of Adept or lower tier there; ends a Master technique on an opposed check.

**Guru**
- *Sustained Work* — Held (standing) · Act to begin · 5, then 1 M per phase held. A Ground-scale alteration that persists without turn-by-turn attention: a harbor kept clear, an aquifer held raised, a river held to a course. While it stands, your Strain Capacity is reduced by 5. If you release it or die, it unwinds over Rank Die days.
- *Storm-scale Sweep* — Instant · Act · 5. Sweep at Ground scale: everything within 30 paces of a point, or one whole Line. Rank Die + Attunement damage; a Line loses Rank Die Cohesion.
- *Burn* — Instant · Ready · 1 M. Recover Rank Die Strain. The body as the power source.

**Cost stages**
1. **Fatigue.** Short rests clear nothing; only a full rest clears Strain.
2. **Muscle failure.** −2 Frame. You cannot take two Moves in a turn. On a natural 1 on any check you drop what you hold.
3. **Organ strain.** Maximum Vigor −8. Each time you overdraw, Reserve check at Difficulty 12 or fall Downed at the end of your turn.
4. **Collapse.** Each time you begin a Guru technique or pay its upkeep, Reserve check at Difficulty 15 or you are Downed until a full rest.
- **End.** The collapse from which the body does not rise. The character dies.

### Sorcerer (Arcane)

Attribute: Reckoning · Moon: Orrivane · Reading: Structure · Working terms: overlay work; running the overlay; substrate editing · Vigor base 8 · Kit: staff, leather, slate and chalk.

**Novice**
- *Read Structure* — Reading · Ready · 0. Structure layer at Novice grade.
- *Lift* — Held · Ready · 1, +1/turn. Move an object you could lift with one hand, within 10 paces, at walking pace.
- *Push* — Instant · Act · 1. Force on one target within 10 paces: check vs Guard; shoved Rank Die paces, or a held object knocked loose if the Rank Die shows 4.

**Adept.** *Restraint:* an Adept who uses two Arcane techniques in one turn takes 1 additional Strain.
- *Ambient Read* — Passive. The Structure reading at Adept grade, with no action, for anything you touch or watch for a full turn.
- *Precise Force* — Instant · Act · 2. Force on a mechanism within 10 paces — a bolt, a joint, a strap, a hinge: check against the mechanism's Difficulty; it opens, jams, or breaks as you choose. Or force on a body: Rank Die + Reckoning damage that ignores shield and armor.
- *Brace* — Held · Act · 2, +1/turn. Hold a structure within 10 paces in place: a failing beam, a door being forced, a falling creature (which lands unharmed).

**Master**
- *The Overlay* — Held · Ready · 3, +1/turn. Structure layer at Master grade across the Circle. While running: +Rank Die to Guard against attacks you can see; once per turn re-roll one failed Reckoning check; full data on any object in the Circle. Upkeep is doubled while you are below half Vigor.
- *Predict* — Instant · Ready · 3 (Overlay running). Name where one moving thing in the Circle will be at the end of its next Move; it is so unless a practitioner intervenes. Give one ally +Rank Die to hit it, or step out of its path so that one attack from it misses.
- *Force at Scale* — Instant · Act · 3. Everything in a 5-pace radius within 20 paces is shoved Rank Die paces; or one Line's front rank is held one turn (the Line cannot Move).

**Guru.** *Attention:* attention-break checks for a Guru edit are at Difficulty 12 + damage. *Write presumes read:* every Guru technique requires the Overlay running and adds the Overlay's upkeep to its own.
- *Dilate* — Held · Act · 5 × ratio factor × radius factor, then +3/turn × ratio factor. A bounded region runs slow or fast against its surroundings. Ratio ½ or 2: factor 1; ¼ or 4: factor 2. Radius 1 pace: factor 1; 5 paces: 2; 20 paces: 3. In a slowed region creatures get half their actions (one Act or one Move per turn; at ¼, one action every other turn); in a fast region, double. *Exterior placement:* the Guru stands outside the region. A Guru inside their own region pays 1 M per turn in addition and loses the Rank Die from initiative each round they remain.
- *Weigh* — Held · Act · 5 × radius factor, +3/turn. Set gravity's magnitude and vector in a bounded region. Pin: everything inside is prone and crawls one pace only on a Frame check against your check. Arrest: a falling mass stops. Redirect: a fall becomes a slide in a direction you name. A pinned Line loses Rank Die Cohesion on the turn it is pinned.
- *Overlay at Ground* — Held · Act · 5, +3/turn. The Overlay at Guru grade across a valley, a ward, a harbor.

**Cost stages**
1. **Headache.** −1 on Reckoning checks while Strain is at half Capacity or more.
2. **Tremor.** Hindrance on fine manipulation; *Precise Force* and lockwork at +2 Difficulty.
3. **Time lag.** −4 initiative. Once per session the GM may declare a lag: you lose your next turn.
4. **Memory dissonance.** At each full rest roll a d20; on 1–4 one technique of the GM's choice is unavailable until the next full rest. Your account of anything more than a day old is a record the GM may correct.
- **End.** Identity-time fracture. The character leaves play; they persist in the world, unrecognizing.

### Apothecarist (Nature)

Attribute: Attunement · Moon: Threnis · Reading: Life · Working terms: attunement; channel work; somatic integration · Vigor base 8 · Kit: staff or dagger, leather, a satchel of simples.

**Novice**
- *Read Life* — Reading · Ready · 0. Life layer at Novice grade: condition of flora and fauna within 10 paces.
- *Speak Small* — Instant · Act · 1. One animal within 5 paces conveys one thing it cares about — fear, food, a direction, a presence — as an impression.
- *Call* — Held · Ready · 1, +1/turn. Small wildlife within 20 paces comes and stays while held: a distraction (one foe of your choice has −2 on checks) or a noise that carries.

**Adept.** *Listening:* no Nature technique below Master restores Vigor.
- *Directed Read* — Reading · Act · 2. Life layer at Adept grade, by contact: where damage sits, what is wrong (wound, poison, sickness, exhaustion), and what the body needs. On a plant or a patch of ground within 10 paces: the same.
- *Steady* — Instant · Act · 2 (touch). A Downed creature stops making crossing checks. Or: end one condition on the touched creature — Frightened, Sickened, or one level of Exhausted.
- *Quiet* — Held · Ready · 2, +1/turn. One animal within 10 paces is calm and will not attack while held; a mount or beast of burden obeys.

**Master**
- *Channel Work* — Held · Act · 3, +2/turn (sustained contact). Each turn held, the patient recovers Rank Die Vigor. After three consecutive turns you may instead remove one poison, one disease, or one condition of any kind. On a natural 1 the channel does not answer: this patient gains nothing from you until the next full rest.
- *Redirect* — Instant · Act · 3 (touch). Within one body, move up to Rank Die points between the patient's Vigor and their current Strain, in either direction.
- *Ward-Read* — Reading · Act · 3. Life layer at Master grade across the Circle, through walls: every living thing, its condition, what it needs.

**Guru**
- *Borrow* — Held · Act · 5, +2/turn. One animal trait for a bounded period: a hawk's eyes (see a mile; readings at Ground scale), a wolf's endurance (ignore Exhausted; double movement; +Rank Die Vigor while held), a bear's frame (+Rank Die on Frame checks and damage), a fish's breath, a bat's ears, a hound's nose. A borrow may be made *standing* for a scene at 1 M instead of upkeep; each further scene it stands costs 1 M. A second trait at once doubles the upkeep.
- *Channel at Scale* — Held · Act · 5, +3/turn. Channel Work on every patient within reach or 5 paces at once.
- *The Ground Answers* — Held · Act · 5, +3/turn. Life layer at Guru grade across the Ground, and influence at that scale: call every animal within a mile, quiet a herd, know a forest entire.

**Cost stages**
1. **Scar tissue.** Contact techniques that were Ready become Act. −1 Poise.
2. **Sensory narrowing.** Lose one sense permanently, your choice: smell, taste, warmth of touch, or hearing beyond 10 paces. Notice checks −2.
3. **Partial morphic blending.** A visible animal trait. −2 on Standing checks with strangers; +1 on one Frame or Poise use the trait fits, chosen when the stage is reached.
4. **Species bleed.** At each full rest, Reserve check at Difficulty 12 or the next scene is played by the GM: you are the animal.
- **End.** The animal walks away. The character leaves play.

### Necromancer (Necrotic)

Attribute: Attunement · Moon: Velquor · Reading: Boundary · Working terms: reader; boundary reading; boundary holding · Vigor base 8 · Kit: dagger, leather, no gloves.

**Practice.** Bare-handed; gloves give Hindrance on every Necrotic technique. Phantom sensations map onto the living body; controlled pain keeps the line between self and the dead. Nothing in this school raises, animates, or commands the dead.

**Novice**
- *Sense the Crossing* — Reading · Ready · 0. Boundary layer at Novice grade: whether someone died here; recent, old, or ancient; one, several, or many. On a battlefield (many dead within the Circle) a Novice takes 1 Strain per turn unless Grounded.
- *Ground* — Instant · Ready · 0 (1 Vigor). Controlled pain. Until your next turn you are immune to battlefield overwhelm and to any Frightened effect that comes from the dead.
- *Cold Read* — Instant · Act · 1 (touch). Whether death touched this object or place: the weapon that killed, the bed someone died in.

**Adept**
- *Attune* — Held · Ready · 2, +1/turn. Boundary layer at Adept grade across the Circle as it happens: every crossing, where, and its register (violent, peaceful, confused, empty). In an engagement you know when anything in the Circle dies, seen or not, and whether a Downed creature will cross this turn.
- *Register* — Reading · Act · 2 (at the site). A crossing's register and its time: to the day within a year, to the season within a decade.
- *Phantom Map* — Instant · Ready · 2 (1 Vigor). The wound that killed here maps onto your body: the cause of death in general terms — blade, fall, water, poison, age, cold.

**Master**
- *Boundary Reading* — Reading · Act · 3 (bare contact with site or remains). The moment of crossing in analytic detail: what the dead saw, heard, felt, and feared, and who was present as the dead perceived them. The reading is the dead's frame, partial and colored by their fear; the GM delivers it so. Deaths at one site are distinguished across centuries.
- *Name the Crossing* — Instant · Act · 3. On a crossing that happened this scene: the killer as the dead saw them — a description; a name only if the dead knew it.
- *Stand in the Cold* — Held · Act · 3, +2/turn. Residue gathers in a 10-pace Circle around you: living creatures inside it are Frightened of you unless they pass a Reserve check at Difficulty 10 + Rank Die each turn. You are immune.

**Guru.** Standing in the doorway is the occupation, and thinning is its cost.
- *Hold the Door* — Held · Act · 5, then 1 M per turn held. A creature that crossed this turn or last is held at the boundary for up to Rank Die turns: it can speak, answer, name, and say goodbye. It cannot act and cannot be healed back; when the hold ends, the crossing completes. (See the Join *Return* in the Game Master's Guide.)
- *Shut the Door* — Instant · Ready · 1 M. A Downed creature within the Circle that would cross this turn does not; it remains Downed.
- *Read at Ground* — Reading · Act · 5. Boundary layer at Guru grade across the Ground: every death in a valley, a battlefield's full account, a ward's crossings this phase.

**Cost stages**
1. **Skin pallor.** Recognizable as a reader by anyone who knows the signs; −2 on Standing checks with such people.
2. **Death residue sensation.** You feel every crossing within the Circle whether or not you Attune: in any scene where something dies, 1 Strain per crossing unless Grounded that turn.
3. **Touch erosion.** You cannot feel living touch. Contact techniques used on you by others have Hindrance. Notice by Attunement has Hindrance.
4. **Boundary thinning.** At each full rest roll a d20; on 1–3 you wake unable to tell the living from the dead until midday: Notice returns the Boundary layer and nothing else.
- **End.** The boundary does not close. The character crosses.

### Apostle (Divine)

Attribute: Standing · Moon: Namaris · Reading: Intent · Working terms: boon work; transfer · Vigor base 8 · Kit: staff or mace, padded, a stole.

**Novice**
- *Read Intent* — Reading · Ready · 0. Intent layer at Novice grade: where fear, calm, or hostility sits among those in view.
- *Carry* — Instant · Ready · 1. Your next sentence is heard clearly by everyone within 20 paces whatever the noise, and you have +Rank Die on a Standing check to be believed or obeyed on it.
- *Calm* — Instant · Act · 1. One distressed creature within 5 paces ends Frightened, or one member of a panicking crowd stops.
- *Steady Touch* — Instant · Act · 1 (touch). Pain steadied without treating its source: the creature ignores the penalties of one condition for Rank Die turns. The condition remains.

**Adept**
- *Encourage* — Instant · Act · 2. One ally within 20 paces who can hear you: +Rank Die on their next check, or Rank Die temporary Vigor that fades at the next rest. Encouragement lands physically; it is not healing.
- *Command* — Instant · Act · 2. One creature within 20 paces: your check against Difficulty 10 + their Reserve modifier + their Rank Die maximum. On success they carry out one short instruction this turn that does not directly harm them: stop; drop it; look at me; sit.
- *Reassure* — Held · Ready · 2, +1/turn. Allies within the Circle are immune to Frightened and have +1 Guard while held.

**Master.** Divine restoration is paid in years, and years are Marks.
- *Boon* — Held · Act · 3, +2/turn (contact, or directed speech at one creature within 10 paces). Choose one while held: *confidence* (+Rank Die on all checks), *endurance* (Rank Die temporary Vigor at the start of each turn, to a cap of twice the Rank Die maximum), or *resolve* (immune to Frightened and Command; crossing checks suspended; may take one turn of actions while Downed).
- *Boon at Scale* — Instant · Act · 3. Every ally in the Circle has +Rank Die on their next check.
- *Mend* — Instant · Act · 1 M (touch). Restore Rank Die + Standing Vigor. Payable in Strain only in Namaris (section 6).

**Guru**
- *Transfer* — Instant · Act · 2 M. A living or held creature you touch is restored to full Vigor; every condition, poison, and disease on it ends.
- *Years for Years* — Instant · Act · 5 M. A creature at Stage 4 has its Marks reset to 0. Or: a creature dying of age or of an untreatable illness is given Rank Die years.
- *Boon at Ground* — Held · Act · 5, +3/turn. Boon (confidence or resolve) on a Line, a crowd, or everyone within 30 paces.

**Cost stages**
1. **Minor aging.** Apparent age advanced by years. Strain Capacity −1.
2. **Frailty.** −2 Frame, −2 Reserve. Movement 5.
3. **Organ degradation.** Maximum Vigor −8. Short rests clear nothing.
4. **Lifespan compression.** Every Mark you take also reduces maximum Vigor by 1, permanently.
- **End.** The years are spent. The character dies.

### Hexblade (Sword/Shield)

Attribute: Poise · Reading: Field — Weight · Working terms: escort; escort of record; counter-practitioner work · Vigor base 12 · Kit: sword, shield, mail.

**Novice**
- *Read Weight* — Reading · Ready · 0. Which visible opponent is about to commit, and to what.
- *Cover* — Reaction · Ready · 1. An adjacent ally is attacked: the attack is rolled against your Guard instead.
- *Hold the Door* — Held · Act · 1, no upkeep. You fill a doorway or a gap up to 2 paces: no one passes without winning an opposed Poise check against you, and you attack anyone who tries.
- *Wall* — Passive. Adjacent to another shield-bearer, both have +1 Guard (+2 with one on each side).

**Adept**
- *Bind* — Instant · Act · 2. Opposed Poise against an adjacent foe: their weapon is trapped until they spend an Act to free it, and you attack them at once.
- *Check* — Reaction · Ready · 2. An adjacent foe Moves or attacks: opposed Poise; on your success they are shoved Rank Die paces or lose the attack.
- *Blind Angle* — Passive. Numbers give no Favor against you while you can see the attackers, and you fight two adjacent foes with no penalty.

**Master.** The escort of record.
- *Complete Defense* — Held · Act · 3, +2/turn. Attacks you can see must beat your Guard plus a fresh Rank Die rolled against each. You make no attacks while held.
- *Read the Chant* — Reaction · Ready · 3. A practitioner within 10 paces begins a technique: you know its school and tier, may spend your next turn's Move now to close with them, and attack; on a hit the technique fails and its cost is still paid.
- *On the Boss* — Reaction · Ready · 3. A flask, bolt, or arrow at you or an adjacent principal is taken on the shield boss: no effect; a flask's contents are spent.

**Guru.** The platoon standard expressed as structure.
- *The Queue* — Held · Act · 5, +3/turn. A Line engaging you can bring only one member against you per turn, and you may attack a different member each turn.
- *Kill the Corners* — Instant · Act · 5. A Line within reach loses Rank Die Cohesion and one member is Downed.
- *Fold* — Instant · Act · 5. A Line within reach must reform: it loses its next turn's attacks and Move.

**Cost stages**
1. **Scar accumulation.** Recognizable as a hexblade; −2 on checks to pass as anything else.
2. **Residue mapping.** During the phase of any magic school whose technique has ever damaged you, −1 on Reserve checks.
3. **Startle lock.** Any unexpected approach or touch, friend or foe, triggers *Cover* or *Check* against the approacher at 1 Strain, unless you pass a Poise check at Difficulty 12.
4. **The guard that will not drop.** Your Ready may be spent only on Reactions and Readings. *Encourage*, *Reassure*, and *Boon* have no effect on you.
- **End.** No one reaches them. The character leaves play.

### Vanguard (Glaive)

Attribute: Poise · Reading: Field — Geometry · Working terms: zone work; holding the circle · Vigor base 12 · Kit: glaive, mail.

**Novice**
- *Read Geometry* — Reading · Ready · 0. The nearest corridor, hinge, or gap in the field.
- *Reach* — Passive. You attack at 2 paces. A foe who closes from beyond your reach to adjacent takes an attack from you if you have a Ready unspent.
- *Set the Point* — Reaction · Ready · 1. A charging foe reaches you: you attack first, and the weapon die is doubled.
- *Keep Spacing* — Passive. Numbers give no Favor against you while you have an open pace to step into.

**Adept**
- *The Circle* — Held · Act · 2, +1/turn. A 2-pace circle around you: any foe that enters or stands in it takes an attack; on a hit it is stopped at the edge or knocked prone.
- *Haft and Butt* — Instant · Act · 2. Two attacks this turn, the second at −2; or one attack that also trips (target prone).
- *Transition* — Reaction · Ready · 2. A foe closes inside your reach: you change grip and fight at 1 pace with no penalty this turn.

**Master**
- *Deny* — Held · Act · 3, +2/turn. A corridor up to 3 paces wide: nothing passes; each attempt takes an attack; a Line attempting it loses Rank Die Cohesion per turn.
- *Hinge* — Held · Ready · 3, +1/turn. Allies adjacent to you in a line count as a shield wall (+1 Guard), and that line cannot be Folded.
- *Read the Flow* — Reading · Ready · 0. Geometry at Master grade across the Circle: where the melee will be next turn. Reposition one ally 5 paces at once.

**Guru.** The platoon standard expressed as space.
- *Walking Circle* — Held · Act · 5, +3/turn. The Circle moves with you; anything it passes takes an attack; a Line you walk through loses Rank Die Cohesion per turn.
- *Terrain* — Passive. A Line cannot bring more than three members against you in a turn; formations must route around you as around a wall.
- *Retire* — Instant · Act · 5. Every foe within 2 paces is attacked once.

**Cost stages**
1. **Joint wear.** At the end of any scene in which you used a Glaive technique, take 1 Strain that only a full rest clears.
2. **Conditioning debt.** Two hours of drill each morning, or your martial Guard bonus is halved that day. Short rests must be spent drilling.
3. **Spinal compression.** Movement 4. *Set the Point* cannot be used against a mounted charge.
4. **The seizing.** At each full rest, Reserve check at Difficulty 12 or no Glaive techniques until the next full rest.
- **End.** The spine seizes. The character leaves play.

### Warden (Longbow, with dagger)

Attribute: Poise · Reading: Field — Ground · Working terms: overwatch; warding · Vigor base 12 · Kit: longbow, forty arrows, dagger, leather.

**The dagger.** It covers the bow's blind distance: switching between bow and dagger is free, and the dagger is a school weapon for this class.

**Novice**
- *Read Ground* — Reading · Ready · 0. Distances, cover, and the safe approach.
- *Volley* — Instant · Act · 1. Loose into an area 3 paces across within range: every creature in it is attacked at −2; a Line loses d4 Cohesion.
- *Watch* — Held · Ready · 0 (may be held while resting). Nothing approaches within 100 paces unseen unless it beats your Poise check. You are never Surprised.

**Adept**
- *Mark* — Instant · Ready · 2. One moving target within range: for the scene, its movement and half cover give you no penalty.
- *Track* — Instant · Act · 2 (outside an engagement). Follow a trail across any ground: Poise check against the GM's Difficulty; on success you know direction, numbers, and the trail's age.
- *From Concealment* — Passive. Loosing from concealment does not reveal your position unless the target beats your Poise check.

**Master.** Overwatch.
- *Overwatch* — Held · Ready · 3, +2/turn (prepared position). Any foe that Moves within your range takes an attack from you with Favor; a Line moving through your ground loses Rank Die Cohesion per turn.
- *Where They Will Be* — Instant · Act · 3. Your attack against a target that Moved this turn hits automatically, unless the target is a practitioner, in which case it is opposed by their Poise check.
- *Read the Slope* — Reading · Ready · 0. Ground at Master grade: every approach to the position you hold.

**Guru.** The platoon standard expressed as ground the platoon will not cross.
- *Unanswerable* — Held · Act · 5, +3/turn (prepared ground). A Line within 300 paces: each turn one member drops with no shooter seen, and the Line loses Rank Die Cohesion to fear; it cannot advance without a Cohesion check at Difficulty 16.
- *Ground They Will Not Cross* — Instant · Act · 5. Name a stretch of ground within range: no Line crosses it this scene without a Cohesion check at Difficulty 20; on failure it halts.
- *Never Seen* — Passive. On prepared ground, non-practitioners cannot locate you; practitioners need a reading.

**Cost stages**
1. **Draw-side deformation.** Recognizable as a bow. −1 on Frame checks with the off arm.
2. **Watch-broken sleep.** A full rest clears only half your Strain unless someone else keeps the watch and tells you so.
3. **Sensory tuning.** You cannot be Surprised, on Watch or off. In any crowd, −2 on every check that is not a reading.
4. **The unclosing eye.** No rest clears more than half your Strain. *Overwatch* costs no upkeep: you are never off it.
- **End.** The eye never closes. The character leaves play.

### Paladin (Hammer)

Attribute: Frame · Reading: Field — Seams · Working terms: the column; holding flat · Vigor base 12 · Kit: maul, mail.

**Novice**
- *Read Seams* — Reading · Ready · 0. Where the nearest thing would break if struck.
- *Split* — Instant · Act · 1. Attack a shield or barricade: on a hit the shield's Guard bonus is gone for the scene, or the barricade is opened.
- *Open* — Instant · Act · 1. Break a door or bar: Frame check against the material's Difficulty.
- *Footing* — Passive. You are not knocked prone or moved by shoves, water, or ground effects below Master tier.

**Adept**
- *The Join* — Instant · Act · 2. Your attack ignores the target's armor and shield; on a hit, the armor's Guard bonus is −1 until repaired.
- *Through* — Instant · Act · 2. Against a barricade, wall section, gate, or construct: damage doubled.
- *Set* — Reaction · Ready · 2. You are struck: halve the damage.

**Master**
- *Charge-Stop* — Reaction · Ready · 3. A charging creature or Line reaches you: the charge ends there. A creature takes Rank Die + Frame damage and is prone; a Line loses Rank Die Cohesion and halts.
- *Load Path* — Instant · Act · 3. A gate or wall section within reach: Frame check at +Rank Die against its Difficulty; on success it opens or falls in one blow.
- *Column* — Passive. Allies behind you move at full pace through what you break, and you are full cover for the one directly behind you.

**Guru.** The platoon standard expressed as breakage.
- *Where the Weight Is Stored* — Instant · Act · 5. A Line within reach loses Rank Die Cohesion, its members are prone, and it cannot attack next turn.
- *Demolition* — Instant · Act · 5. A structure up to a gatehouse or a tower section collapses.
- *The Walking Building* — Held · Act · 5, +3/turn. You take half damage from weapons, and every attack you land on a Line also deals Rank Die ÷ 2 Cohesion.

**Cost stages**
1. **Micro-fracture conditioning.** +1 maximum Vigor. −1 on Reserve checks against cold.
2. **Bone remodeling.** +1 Frame, −1 Poise.
3. **Deep-set brittleness.** A natural 20 against you breaks a bone: −2 Frame until a Nature Master's *Channel Work* sets it.
4. **The settling.** −4 Frame. *Charge-Stop* requires a Reserve check at Difficulty 14 or you are the one knocked down. Carried weight halved.
- **End.** The settling completes. The character leaves play.

### Berserker (Ax)

Attribute: Frame · Reading: Field — Nerve · Working terms: the gate; opening; calling-back · Vigor base 12 · Kit: great ax, leather.

**The Gate.** The Adept and higher techniques of this school run through the Gate. While the Gate is open: immune to Frightened; ignore the penalties of conditions and wounds; +Rank Die damage; −2 Guard; no readings; you cannot retreat and must attack the nearest hostile creature each turn. When the Gate closes, take Strain equal to the number of turns it was open (post-gate collapse). Strain past Capacity is Marks, as always.

**Novice**
- *Read Nerve* — Reading · Ready · 0. Whether one visible creature will hold or break this turn.
- *Commit* — Instant · Act · 1. Charge: Move your full distance and attack with +Rank Die damage; −2 Guard until your next turn.
- *First Over* — Passive. Barricades and difficult ground do not slow a charge.

**Adept**
- *Open the Gate* — Held · Act · 0 to open, +1/turn. The Gate, as above. You may close it on your turn.
- *Ending Hit* — Instant · Act · 2. Roll the Rank Die twice for damage. A target at half Vigor or less is Downed by any hit.
- *Suppression* — Passive. While the Gate is open, +Rank Die on Reserve checks against pain, poison, and fear; a poison's onset is delayed until the Gate closes.

**Master.** Aimable.
- *Direction* — Passive. While the Gate is open, an ally within 20 paces may spend a Ready and a Standing check at Difficulty 13 to name your target for the turn; otherwise, nearest.
- *Held Gate* — Passive. Gate upkeep is 1 per two turns; post-gate collapse is halved.
- *Breach* — Instant · Act · 3. Attack every adjacent foe once; a Line loses Rank Die Cohesion and one member is Downed.

**Guru.** The platoon standard expressed literally.
- *All the Way* — Held · Act · 0 to open, then 1 M per turn after the first Rank Die turns. The Gate fully open. Wounds are not registered: damage is recorded but does not Down you until the Gate closes, and if it then exceeds twice your maximum Vigor you cross. Numbers are not registered: attack every adjacent foe each turn; numbers give no Favor against you. Time is not registered: you cannot close the Gate. A Line you engage loses Rank Die Cohesion per turn. The Gate closes only by the *Calling-Back*, or one turn after nothing hostile is in reach — a turn in which you attack whatever is nearest.
- *The Calling-Back* — Any ally may attempt it as an Act: Standing check at Difficulty 10 + turns the Gate has been open. Apostles add their Rank Die. Success closes the Gate at the end of the Berserker's next turn.
- *Nothing Standing* — Passive. While *All the Way* is open, every hit you land on a creature at or below half Vigor Downs it.

**Cost stages**
1. **Post-gate collapse.** When the Gate closes you are Exhausted one level until a short rest.
2. **Frenzy amnesia.** You do not remember anything that happened while the Gate was open; the GM tells you what others say.
3. **Affect blunting.** Permanently immune to Frightened. *Encourage*, *Reassure*, and *Boon* have no effect on you. −2 on Standing checks with those close to you.
4. **Heart-burn.** Each turn the Gate is open beyond your Reserve modifier in turns (minimum 1), Reserve check at Difficulty 12 or take d6 damage the Gate does not ignore.
- **End.** The calling-back goes unanswered. The character dies in the Gate.

### Artificer (Light Arts)

Attribute: Reckoning · Reading: Make · Working terms: bench work; bonding · Vigor base 10 · Kit: field kit, dagger, leather, an unbound familiar frame.

**Bench work.** Bench techniques are performed during rest; their Strain is paid then. Items last until used; flasks keep for a phase.

**Novice**
- *Read the Make* — Reading · Ready · 0. What a thing is made of and whether it was bench-made.
- *Field Kit* — Bench · 1 per flask. Up to Rank Die stable flasks per full rest: *fire* (thrown at a point; 2d4 to everything within a pace; Burning), *smoke* (concealment 3 paces across for a scene), *adhesive* (a creature or door Stuck, Difficulty 12). Thrown flasks are Poise attacks.
- *Simple Gadget* — Bench · 1. One device, one function, no decision in it: a lamp, a trip-line alarm, a spring latch, a signal whistle, a counterweight.
- *Maintain* — Instant · Act · 1. Repair or reset another's gadget or construct: a golem or familiar recovers d4 Vigor; a device is re-armed.

**Adept**
- *Trigger* — Bench · 2. A flask with a timed trigger (up to a day) or a conditional one (opened, stepped on, seal broken, wetted).
- *Familiar* — Bond · Capacity −1. One small bound construct on a wren, rat, or beetle frame: Vigor 3, Guard 12; flies or crawls at 6 paces; carries a flask or a note; fetches a small object; watches. Commands are a Ready. Spend a Ready to perceive through it: Plain layer only.
- *Bench Reading* — Reading · Act · 2 (bench, an hour). Make at Adept grade: a flask's contents, a gadget's function, and the school and rank of a construct's maker.

**Master.** Workshop scale.
- *Specialized Familiar* — Bond · Capacity −2 each. A familiar with one specialized sense — hears through walls, smells a dose, sees in the dark, feels tremor in the ground — working up to a mile away. A Ready receives what it senses.
- *System* — Bench · 3 (days). A gadget system: a lock no Novice opens, a lift, a signal line between two points, a trap array. Its Difficulties are set by the GM at Master-grade.
- *Production* — Bench · 3. Novices under your supervision make flasks at your grade for a day; a workshop you run outputs Rank Die items a day.

**Guru.** The platoon standard expressed as logistics.
- *Household* — Bond. Up to twelve familiars at once. Each active familiar beyond the fourth costs −1 on every check not made through a familiar.
- *In Concert* — Held · Act · 5, +3/turn. Every familiar acts on your turn: eyes give your side the Plain layer of the whole field (no one on your side is Surprised; every position is known); hands deliver flasks as a volley (a Line loses Rank Die Cohesion); tools repair (every construct and gadget on your side recovers d6).
- *The Wagon* — Bench · 5 (a day). Equip a company: Rank Die × 10 flasks or gadgets. A Line you equip has +2 maximum Cohesion and +1 Guard for a phase.

**Cost stages**
1. **Reagent-etched hands.** −1 on Poise checks for fine work away from the bench.
2. **Close-work sight.** −2 on every check that depends on seeing beyond 5 paces; ranged attacks at Hindrance.
3. **Fume-worn lungs.** Strain Capacity −2. You cannot take two Moves in a turn.
4. **The divided attention.** Every bond costs one further point of Capacity. −2 on Standing checks made in person.
- **End.** Wholly divided among the familiars. The character leaves play.

### Warlock (Dark Arts)

Attribute: Reckoning · Reading: Make (dose) · Working terms: dosing; the pharmacopoeia · Vigor base 10 · Kit: field kit, dagger, leather, three vials.

**Bench work** as for the Artificer. **Handling:** you are immune to your own preparations.

**Novice**
- *Read the Dose* — Reading · Ready · 0. Whether a cup, a blade, or a body carries something, and roughly what kind.
- *Stable Poison* — Bench · 1. A blade coat or a cup dose: on the first hit or the drink, d4 damage at the start of the victim's turn for Rank Die turns; Reserve check at Difficulty 12 each turn ends it.
- *Purgative* — Bench · 1. Ends a Novice-grade poison or an ordinary sickness in the drinker, who is Sickened for one turn.
- *Preserve* — Bench · 1. A draught that keeps a body, a sample, or a store of food from decay for a phase.

**Adept**
- *Graded Venom* — Bench · 2. Choose onset — a breath, an hour, a day, a phase turn — and grade: *numbing* (−Rank Die Poise), *weakening* (−Rank Die Frame), *sleeping* (Unconscious), *killing* (d6 at the start of each turn). Reserve check at Difficulty 14 resists; a Purgative of Adept grade or higher ends it.
- *Past the Budget* — Bench · 2. A potion. The drinker has +Rank Die on one attribute's checks and Rank Die temporary Vigor for a scene. At their next rest the bill arrives: Strain equal to the Rank Die result, and if that overdraws, Marks.
- *First Golem* — Bond · Capacity −1. Vat-grown or clay-bound: Vigor 15, Guard 10, Frame +3, attacks d8+3, movement 5. Obeys one-word orders given as a Ready. Makes no check but Frame.

**Master.** Contact-grade work.
- *Contact-Grade* — Bench · 3. A poison delivered by skin — a wax, a coin, a page, a glove. Onset chosen. Reserve check at Difficulty 16; no Purgative below Master grade touches it.
- *Tailored* — Bench · 3 (a sample, or a day's observation of a named person). A potion or poison that affects only the named person and is inert to everyone else; +Rank Die to its Difficulty or effect.
- *Standing Orders* — Bond · Capacity −2. Up to three golems, each holding one simple standing order: guard this door; follow her; carry this until sundown; strike anyone who crosses this line.

**Guru.** The platoon standard by other means.
- *Dose the Well* — Bench · 5 (Ground). A dose in a well, a granary, or a censer steers everyone who draws on it for a phase: calm, fear, sleep, sickness, or obedience to one phrase. A Line so dosed loses Rank Die Cohesion when it first matters.
- *The Antidote No One Can Check* — Bench · 5. Cures any poison, Guru-grade included; or a dose only you can undo, laid on a recipient as a standing hold.
- *Golem Team* — Bond · Capacity −3. Up to twelve golems under standing orders, acting as a Line with Cohesion 12.

**Cost stages**
1. **Tolerance dosing.** Immune to Novice and Adept poisons. −1 on Standing checks at a shared meal.
2. **Organ staining.** Visible. −2 on Standing checks with strangers; contact techniques used on you by Nature and Divine practitioners have Hindrance.
3. **Taste-death.** Immune to every poison. Food gives nothing: a full rest requires a preserving draught. −2 Reserve.
4. **The venomous body.** Your blood, sweat, and touch are an Adept-grade *Graded Venom* (numbing) to anyone who touches you or treats you by contact. Maximum Vigor −8.
- **End.** Death by the immunities' cost.

---

## 13. The character sheet

Record: name · school and class · rank and Rank Die · the six attributes and modifiers · Vigor (current / maximum) · Guard · Movement · Initiative bonus · **the ledger:** Strain (current / Capacity), Marks (current / 10), Stage and its effects, bonds · the school's moon, the current phase, and this phase's cost modifier · techniques known · Tongue and Trades · kit · **gear** by slot — tier, sockets, and the relic seated in each, with its moon, its Capacity cost, and this phase's far-phase mark · the school's End, written out once, at creation.

The ledger is the part of the sheet other people cannot see. Keep it honest.
