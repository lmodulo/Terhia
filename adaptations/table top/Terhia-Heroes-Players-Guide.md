# Terhia: Heroes — Player's Guide

Draft v0.6 (25 September 2026; v0.1–v0.5 the same day). Built against Terhia-Canon v1.2. **v0.6 replaces each class's fixed ability list with a larger pool (§13.3, §14):** every class keeps nine picks — three Novice, two Adept, two Master, two Guru — drawn from pools of 21–28, so one class supports several builds; the Elementalist's list splits by element, with a sub-discipline from Master. Every v0.5 ability is kept word for word apart from its letter label (two exceptions: *Storm Call*'s Momentum sentence is now its [Storm] tag, and *Standing Orders* carries a *requires Golem* tag); the Cores, Readings, and every rule in §2–§13.2 and §15 are unchanged; two signature resources gain options (three Apothecarist somas, seven Warlock Properties). New register rows H61–H72. v0.5 applied the Game Master's Guide v0.4 calibration-closure pass to §15.1 (H60): the gloves' damage bonus is on the Strike and the Core at every tier; the Guru chest's resistance is never Physical; the kit the GM's opposition tables assume, and the budget step for an own-tier kit, are stated for the player.** No other rule changes in v0.5. **v0.4 adds §1.4 (who the character is in the world), replaces the character sheet (§16), and adds register rows H51–H59;** the source is the Cultures-and-Factions module (Terhia-Heroes-Cultures-and-Factions.md v0.1), which holds the full entries and its own register (CF-rows). No rule in §2–§15 changes in v0.4. v0.2 was the reconciliation pass with the Game Master's Guide v0.2 (its ten PG revisions applied here; H34–H41). **v0.3 applies rulings R1–R8 of the issue-by-issue ratification pass** (Terhia-Heroes-Rulings.md): the Guru Strike's second Rank Die against Cohesion only; Tempo at the rank boundaries (2 at level 9, 3 at level 13); Guru relic alterations of another school usable only as a Push; *Harbor Kept* on the harbor economy's schedule; Readings free with the exploit costing the Quick; a Mob's squares as enemies' squares; *Time Debt*, the Boss Stun, and *Threshold* settled; the moon rule ratified. New register rows H42–H50; Issues 9–15 of the ledger remain open. Sister ruleset to *Terhia: Chronicle* (Player's Manual v0.3): same world, same twelve schools, same four ranks, same six attributes; a different player promise. Where a rule below reuses a Chronicle rule it says so; where it departs, it departs on purpose and the departure is listed in §17 for ratification.

**Scope.** Player-facing rules only: what a player character is, who the character is in the world (culture, homeland, household, name, tongues, charter, faction, coin — §1.4), resolution, attributes and their limits, the turn, movement on a gridded table, damage and criticals, boons and hexes, Strain / Overdraw / Marks, readings, joins, advancement, the twelve classes with their spell and skill pools, gear and relics (the player's side), and the character sheet. Not here: opposition and Grand Beast stat blocks, Mob rules, relic generation, contracts, encounter budgets, calibration (Game Master's Guide).

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

### 1.4 Who you are in the world

Class answers what you can do. This section answers who you are: the fields on the sheet (§16) above the attribute line. The full entries — six cultures, twelve homelands, three institutions, twelve factions, coin, tongues — are in the Cultures-and-Factions module (Terhia-Heroes-Cultures-and-Factions.md, v0.1); this section is the player's summary, and the module's section numbers are given in brackets.

**Thirteen steps, after the class.** (1) **Culture**, one of six. (2) **Homeland**, one of the culture's two by default — a minority birth is allowed and is a character in itself [3.0]. (3) **Born at**: the seat, a town, or none — the road, the drove-lines, the fire country, a boat. (4) **Household**, from the culture's list [2] or your own inside its profile; it sets your coin, your tongues, and what you owe. (5) **Born**: day, phase, year — `48 Velquor 1222`; the present year is 1245; the phase gives your culture's age marker. (6) **Name**, four fields: full name in the culture's form; what you are called; what a registry files; your formal introduction [7.5]. (7) **Tongues** [7.1]. (8) **Ethos and moon** — set by the class (§1.1), not chosen. (9) **Charter of record** — the homeland's institution unless you were trained, registered, or recognized elsewhere; read the standing table below. (10) **Faction** — none, or one Member affiliation [5.3]. (11) **Coin and kind** [6.5]. (12) **The laws you carry and the word you hold**, copied from the culture entry [2]. (13) **God** — Crown homelands only, optional, yours to write [4.5].

**What identity never does.** No culture, homeland, household, charter, or faction adds to or subtracts from an attribute, a defense, Vigor, Strain Capacity, damage, or an attack roll; none restricts or grants a class or school; none changes an ability. Canon XI.6 rules out the essence reading. Identity works through three levers only: **Advantage or Disadvantage on a check**, **a procedural right**, and **what is filed, owed, or refused**.

**The six cultures** [2].

| Culture | Homelands (charter) | Tongue | Name form | The laws you carry | The word you hold |
|:--|:--|:--|:--|:--|:--|
| **Menneske** | Isavík (Gold Crown) · Grimskov (Blue Accord) | The Menneske tongue; one language across the strait | Personal name, then *of* a settlement or its stem as a byname (Aslaug of Stenhavn) | Witness-law · Ice-law · Winter-count | Assent given by staying silent |
| **Renlei** | Zhenshui · Tienling (both Blue Accord) | The Renlei tongue | Family name first, then a given name of one or two syllables (Luo Deshi) | Seal law · Phase-contract law · Examination standing | A price quoted with its phase |
| **Unsaan** | Bahr-Al-Asra (Gold Crown) · Zand-Kala (Blue Accord) | One language, two registers: Asran (citadel, rites), Kalani (gardens, contracts) | Personal name and house (Asran) or garden-name (Kalani); an office-holder takes the place-name (al-Rimal) | Guest-right · Shade-and-water servitudes · Name law | The third night, when a host may ask a guest's business |
| **Yamana** | Teocalli (Gold Crown) · Yaxkulu (Green Chimera) | The Yamana tongue | A personal name; formally, the oldest inherited duty | Road law · Duty inheritance · Water law at the terraces | A duty inherited from someone you never met |
| **Umutu** | Oasira (Gold Crown) · Zulwazi (Green Chimera) | The Umutu tongue | Personal name, the age-set cohort (phase and year), the well or keeper lineage | Water law · Passage law · Market truce | Water owed back to a well |
| **Tangata** | Awanui · Koremu (both Green Chimera) | The Tangata tongue | Personal name, birth-moon, house-lineage; a navigator adds the channels claimed | Way law · Closed ground · Fire law | A way that is closed, as distinct from not yet open |

**The laws you carry.** On your culture's ground, or dealing with anyone of your culture, you have Advantage on any check that turns on one of your three laws. Checks only — never an attack roll. Off your ground the law still binds you, and the other party may not know it exists [2, CF4].

**Age.** Menneske count winters; Renlei, Unsaan, and Yamana count years; an Umutu is a cohort — five a year, cut by birth phase, written as the phase and year; a Tangata carries a birth-moon, a berth and not a destiny. A registry converts all four to a number and is wrong in a way the GM decides [1, 2].

**Your charter reads your ethos** [4.3]. Ethos comes from the class (§1.1: Rationalist — Sorcerer, Vanguard, Artificer; Devout — Elementalist, Paladin, Apostle; Reverie — Warden, Berserker, Apothecarist; Ethosless — Necromancer, Hexblade, Warlock). Charter comes from where you stand. Read the cell for the territory you are in; the sheet holds the home cell.

| Ethos ↓ / Charter → | Blue Accord | Gold Crown | Green Chimera |
|:--|:--|:--|:--|
| **Rationalist** | *Home.* Licensed, filed, priced. Ledger file 1 | *Chartered guest* — the Assay's charter; the Witness, tolerated. Ledger file 1, Chancel favor 0 | *Individual* — no body to adjudicate merit. Circle recognition 0 |
| **Devout** | *Chartered* — the Firstday Watch; registered by function; a healing is measured, not sacramental. Ledger file 1 | *Home.* Sacramental, Assay-certified, benefice-bearing. Chancel favor 1 | *Under treaty* — the Namarite Tithe; you owe the way-toll. Chancel favor 0, Circle 0 |
| **Reverie** | *Licensed where the Accord cannot staff* — Ash-and-Antler; "experimental mercy techniques." Ledger file 1 | **Proscribed** — the Edict of Amilpan, 1189. Chancel favor 0, Circle recognition 1. Identification starts enforcement: a column on flat ground, nothing in the trees | *Home.* Recognized by keepers; nothing written. Circle recognition 1 |
| **Ethosless** | **Unregistered** — legible and prosecutable; no registry to be late to. Any Reading by a registered practitioner, manifest, or assessment files a Register entry. Ledger file 0, Off-Ledger credit 1 | **Anathema** — the Purge, 1164–66. Guest-right shelters you three nights anyway. Chancel favor 0, Off-Ledger credit 1 | *Received* — what the Crown anathematizes and the Ledger cannot admit. Circle 1, Off-Ledger 1 |

**Registry status**, one word on the sheet, two if you carry two [4.4]: *Registered* (grade — the Ledger's file; a cost file from Adept), *Attuned* (grade — the Assay's roll), *Recognized* (a keeper said it), *Unregistered*, *Proscribed*, *Anathema*, *Off-Ledger*. The GM Guide (§9.1) has what each recognition looks like and costs.

**The four tracks** [5.2]. Ledger file, Chancel favor, Circle recognition, Off-Ledger credit; 0–5 each; the GM Guide (§8.4) names what every step unlocks and (§8.5) what loses one. Contracts move them; so do the factions. Standing with one moves the others: +2 with the Chancel is −1 with the Circles; a Ledger file of record is what the Off-Ledger charges for.

**Factions** [5]. Twelve, three per ethos: Rationalist — the Cobalt Ledger (Accord), the Indigo Assay (Crown), Steel Quorum (none); Devout — Firstday Watch (Accord), Gilt Chancel (Crown), the Namarite Tithe (Chimera); Reverie — Ash-and-Antler (Accord-licensed), Bramble Concord (Chimera), the Sedge Circles (none); Ethosless — Black Meridian (Chimera), the Off-Ledger (none), the Unsworn (all, by contract). Ethos is belief and institution is charter; the two are independent. Three relations: **Member** — one at a time; its register is yours, its gift and demand apply, its track starts at 1; **Contractor** — as contracts run; **Marked** — it has something on you. Most level-1 characters have no Member affiliation; the file, favor, recognition, or credit comes first.

**Coin** [6]. Two mints, no third. The **seal** (silver, the Ledger's, Baishui) and its **eighth** (copper, eight to the seal); the **gilt** (gold-washed silver, the Chancel's, Qasr-Al-Rimal). The Chimera mints nothing. Both coins pass everywhere; the rate is the desk's — 1 gilt = 1 seal 2 eighths at a Ledger desk, 1 = 1 at a Chancel desk, worse at a caravan house. Write `12s 3e` and `4g`; never total them. A labor-day is an eighth; a head of cattle is six seals; a Master warden's season is sixty. Castings, fares, and Guru leases are priced by the phase; bread moves a little, and late. **Starting coin, by household standing:** rich in coin 12 seals (10 gilts); ordinary 4 (3); rich in standing not coin, 1 at most and a claim under Kind; nothing, 1 and a debt you choose. The coinless are not poor; the Ledger records them as poor.

**Debts that are not money** [6.6]. Winters (Menneske), well-days (Umutu), a duty (Yamana), a roof (Unsaan), a way (Tangata), a name (the Circles, the Off-Ledger), a Mark, sealed coin by phase (Renlei). The sheet keeps them owed and held. No table converts them; a registry that does is wrong in a way the GM decides.

**Tongues** [7]. Your culture's tongue at **Full**. The Common Tongue at **Full** if you are Registered or Attuned or your household is one that has it — a registry, board, or portal household; clergy; a caravan, harbor, factor's, guild, or customs house; a navigator or keeper who treats with outsiders; a runner lineage; a law house; an Unsworn company — and at **Market** otherwise: a few dozen words of market and toll; anything past that is at Disadvantage, and you cannot read it. **None** only by choice. One neighbor tongue at Market if the household trades across a border. The **Trade** talent (§13.2) taken for a tongue raises it one level; at Full it adds the Rank Bonus as written.

**The lexical gap** [7.3]. When a scene turns on one of the six words above and the parties are of different cultures speaking the Common Tongue, the speaker whose word it is has **Disadvantage** on the check to be understood on that point. The listener's Full fluency in the speaker's tongue removes it, and so does an interpreter who holds both at Full — and an interpreter's presence is a fact about who has standing in the scene, which the GM says aloud. A party of two cultures hears two sentences.

**Registry words and working words** [7.6]. The class names are Common Tongue registry terms. Practitioners speaking to practitioners use the working terms — a Necromancer is a *reader*, a Sorcerer *runs the overlay*, a Warden holds *overwatch*, a Berserker *opens the gate*. A character who uses the registry word for their own school is telling the table something.

**God** [4.5]. For the four Crown homelands only — Isavík, Teocalli, Bahr-Al-Asra, Oasira — the sheet has a line for the Lender's local name, or the Steward's for an Elementalist. The Renlei and the Tangata have no gods in canon, as a scope decision; no rule fills the line.

---

## 2. Resolution

**The roll:** d20 + attribute modifier + Rank Bonus, against a target number.

- **Attack rolls** target a defense: **Guard** (anything you dodge, block, or take on armor: weapons, projectiles, force, elemental blasts) or **Ward** (anything you resist from the inside: poison, fear, the boundary, a grip on your body, a word that lands). Each ability says which.
- **Checks** target a Difficulty. You add the Rank Bonus to a check when it falls inside your school's competence (the GM rules; the class entry gives examples).
- **Advantage / Disadvantage:** roll two d20 and keep the higher / lower. One instance of each cancels the other; multiple instances don't stack.
- **Natural 20:** the attack hits and is a critical (§7.3); the check succeeds. **Natural 1:** the attack misses; the check fails; any Strain spent is spent.
- **Area attacks:** roll **once** and compare the result to each target's defense. Targets you hit take the full effect; targets you miss take half damage and no rider, unless the ability says otherwise. **Elites and Bosses take nothing on a miss** (with half-on-miss, an area was worth 87% of a single-target attack per target against a Boss; without it, about 70% — GM Guide §12.3 b).
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
| **Tempo** | Actions per turn: 1 at levels 1–8, 2 at levels 9–12, 3 at levels 13–16 (§5) |

**Armor:** none 0 · light +1 · medium +2 · heavy +3 (heavy: Speed −1, Disadvantage on stealth). **Shield:** +2 for the Hexblade (trained), +1 for anyone else who carries one; a Necromancer cannot (bare-handed, §14). Each class lists its armor allowance; wearing heavier than allowed: Disadvantage on every attack roll and spell.

**Weapons.** Everyone can use simple weapons (dagger d4, staff d6, club d6, hand-ax d6, sling d4 range 12) without the Rank Bonus. Martial classes use their school's weapon with the Rank Bonus: longsword d8 · glaive d10 (reach 2) · longbow d8 (range 24; Disadvantage against adjacent targets — the Warden's dagger covers that distance) · maul d12 (two-handed) · great-ax d12 (two-handed). Thrown flasks and vials: range 8, keyed to Reckoning, with the Rank Bonus.

---

## 5. The turn

Each round, in Initiative order, a creature takes a turn:

**Move** (up to Speed) **+ Actions (your Tempo) + Quick Action + Reaction** (the Reaction is spent on anyone's turn, once per round).

**Tempo** is how many Actions you take on your turn: **1** at levels 1–8, **2** at levels 9–12, **3** at levels 13–16 — it steps at the rank boundaries, with the Rank Bonus and the Core's new form. Move, Quick, and Reaction do not multiply. Four rules govern the extra Actions:

- **No repeats.** An ability with a Strain cost may be used once per turn. Your Core (0 Strain) and the Strike may be used with every Action. Three Actions means three *different* costed abilities, or Cores in the gaps.
- **Strain is the governor.** Tempo raises nothing else. A level-13 Sorcerer spending 4 + 3 + 2 Strain a turn against Capacity 19 is at Overdraw on turn 3: Tempo gives you the option of a burst, and the Ledger sends the bill.
- **One Sustained effect** at a time, as below; a second Action cannot start a second Sustain. **One Ready** a turn: a Readied Action fires as your Reaction, and you have one Reaction.
- **Summons act on your turn.** A Companion, familiar, golem, turret, or construct takes its own Move and one Action when you take your turn, whatever your Tempo, and uses your Quick if it needs one (commanding it is that Quick). A summoner with Tempo 3 has three Actions and one summon's Action, not six.

| Action | Use it for |
|:--|:--|
| **Strike** | One weapon attack (Martial) or your class Core ability (§14). Martial Strikes scale: Novice 1 attack (weapon + Key); Adept 1 attack (weapon + RD + Key); Master 2 attacks (each weapon + RD + Key); Guru 2 attacks (each weapon + RD + Key; against a Mob, each attack adds a second RD) |
| **Cast / Use** | Any ability listed as an Action |
| **Dash** | Move again (Speed) |
| **Disengage** | Your movement this turn doesn't provoke Punishes |
| **Shove** | Frame vs Guard: push 1 square (2 if Frame modifier is +3 or more) or knock Prone |
| **Help** | Grant an adjacent ally Advantage on their next attack or check |
| **Ready** | Name a trigger and an Action; it happens as your Reaction when the trigger occurs |
| **Exploit, command, or draught** | Only if your Quick Action is spent this turn: act on a Reading (the exploit, §11), command a summon, or drink or apply a draught. The Reading itself is free |

**Quick Action:** anything listed as Quick; act on a Reading (the exploit, §11); command a summon; drink or apply a draught; drop Prone; pick up an item; the Second Wind (§9). A Reading itself costs nothing (§11). **Reaction:** anything listed as a Reaction; Punish (§6.4); a Readied action; a Join partner's half (§12).

**"Strike" inside an ability** means one weapon attack at your rank's dice (weapon + Key at Novice; + RD from Adept; a Guru's attack adds a second RD against a Mob's Cohesion only). The Strike **Action** makes the number of attacks in the table (one at Novice and Adept, two at Master and Guru); a Master or Guru Core form that says "two Strikes" is that two-attack Strike Action with its rider, not two Actions. A Punish, a Riposte, a Join's Strike, and "an extra Strike" are one attack each.

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
- **Allies' squares** can be passed through at 2 per square, never ended in. **Enemies' squares** cannot be entered unless the enemy is two size categories smaller or larger. A Mob's squares are enemies' squares; abilities that say "enter a Mob" are the way in (GM Guide §5.7).
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

Three numbered hexes deal damage at the start of the affected creature's turn. Stacks are written Burning 3, Poisoned 2, etc. Each has a maximum of **5 stacks** — an Elite 4, a Boss 3, so the Warlock's snowball stops at −3 Ward on a Boss; further applications are lost.

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
| **Stunned** | No Move, Action, Quick, or Reaction; attacks against you have Advantage. Never lasts longer than 1 round from a single application; a Boss can be Stunned once per phase — a second Stun in the same phase is Slowed instead (shake-off below) |
| **Prone** | Melee attacks against you have Advantage; ranged attacks against you have Disadvantage; your attacks have Disadvantage; standing costs half your Speed |
| **Grabbed** | Rooted, and the grabber may move you when it moves. Escape: an Action, Frame or Poise vs the grabber's Guard |
| **Frightened** | Disadvantage on attacks while you can see the source; you can't willingly move closer to it |
| **Blinded** | Your attacks have Disadvantage; attacks against you have Advantage; you must guess the square of anything not adjacent |
| **Bound** (Hexblade) · **Quarry** (Warden) · **Sanctioned** (Apostle) · **Marked** (GM) | Class-specific; defined in the class entry |

**Shake-off (Elites and Bosses).** At the end of its turn, an Elite or Boss makes one **Ward check** — d20 + (its Ward − 10) — against any one hex on it that denies it a Move, Action, or Reaction, or dictates its target: Stunned, Rooted, Grabbed, Bound, Dazed, Frightened. The DC is the attack roll that applied the hex, or 10 + the applier's Key modifier + Rank Bonus where no roll was made. Success ends that hex. One check a turn, against the hex it chooses. A Boss also makes the check on entering a Ground-scale or Battlefield hex (a Sorcerer's *Slow Field*, an Elementalist's *Tempest*, a Warlock's *Dose the Ground*); success ends the effect for it alone and the effect stays for everyone else. This is the one rule that keeps a Boss a Boss under a party of four; the GM Guide (§4.4, §10.4) says what it absorbs.

### 8.3 Duration and removal

Unless an ability says otherwise: boons and hexes from an Action last **2 rounds**; from a Quick Action or Reaction **1 round**; from a Sustained ability, while sustained. A hex is removed by the entry's listed cure, by a Heal that says "remove hexes", or by a full Rest. Boons end when their duration ends or the recipient is Downed.

---

## 9. Strain, Overdraw, Push, and Marks

This is the largest departure from Chronicle. In Heroes, **Strain is what lets you do the cool thing repeatedly; Overdraw is what lets you do something outrageous.**

### 9.1 Strain

- Every class ability with a number after its action type costs that much Strain. Core abilities and Strikes cost 0.
- Strain refreshes to full at a **Breather** (§10.1). Nothing else drains it: not time, not damage.
- You cannot spend Strain you don't have — except by Overdraw.
- **The moon** (Magic classes only; canon: casting cost varies by phase and by nothing else). In your school's own phase, Strain Capacity **+2**; in the two far phases (two steps away in the cycle Velquor → Saelura → Orrivane → Namaris → Threnis), **−1**; in the adjacent phases, no change. The Elementalist's moon is Saelura. Nothing else in the game changes by phase. Write your moon on the sheet (§16).

### 9.2 Overdraw

When you use an ability you cannot afford, pay all the Strain you have (down to 0) and take **1 Mark**. The ability works. Overdraw once per turn.

### 9.3 Push

Once per round, after you make an attack roll or check with an ability and before its result is resolved, you may take **1 Mark** to do one of the following:

- **Maximize:** every damage die of this ability shows its maximum.
- **Reach:** add your Rank Die to the d20 roll.
- **Widen:** enlarge the area by 1 (Burst 2 → 3; Cone 6 → 7; Line 12 → 13) or double the range.
- **Refill** (once per encounter, on your own turn): Strain to full.
- **Use** (on your own turn, instead of after a roll): activate the alteration of a Guru relic of a school not your own (§15.2); the alteration's own action type and Strain cost apply.

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

Death is permanent. Two Guru abilities and no others say otherwise: the Apostle's *Refuse Death* (lifespan transferred: it costs the Apostle a Mark) and the Necromancer's *Threshold* (a delay measured in breaths, not a return). Both are written in §14. An optional table rule, *Carried Back*, is in the GM Guide (§10.7); it is off by default.

---

## 11. Readings

Every school reads the world in its own register. In Heroes a Reading is an action-enabling power: **read a weakness → exploit it**.

- **Read** · free · 0 Strain · no action · a target within the listed range · once per round. The GM gives one true fact in the school's register (a load path; a compensating forelimb; who this creature will attack next; what the ground answers). The sentence is the whole result; the next Reading is next round.
- **Exploit** · Quick Action. Act on the Reading: each class entry lists what its Reading unlocks. The exploit lasts until the end of your next turn unless stated. If your Quick is spent, the exploit — or a summon's command, or a draught — may be taken as an Action instead (§5). Announcing a read weakness to allies costs nothing.
- **What a reading cannot see** is still true in Heroes: a Sorcerer reads mass and load, not intent; an Apostle reads intent, not mass. A Grand Beast's vulnerability is written in one school's register and is complete only when two schools read it together — which is what Joins are for.

---

## 12. Joins

A Join is two practitioners of different schools acting as one. In Heroes, Joins are combination attacks.

**Procedure.** The initiator uses an Action and pays 2 Strain; the partner uses their Reaction and pays 2 Strain. Both must have the listed abilities and be within 12 squares of each other (or as listed). The initiator makes one attack roll with +2. A Join can be Pushed by one of the two, not both. A Join's effect replaces both component abilities for that turn. **Each Join can be performed once per encounter:** a pair that holds two Joins can perform both, one each; the same Join is not repeated until the next fight. Where a Join says "Strike", it means one weapon attack (§5), whatever the Strike's rank form.

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

Improvised Joins are adjudicated by the GM (GM Guide §10.3) under the same once-per-encounter limit; a listed Join is always available to characters who hold the requirements.

---

## 13. Advancement and talents

### 13.1 Level table

| Level | Gains |
|:-:|:--|
| 1 | Class kit: Core (Novice form), Reading, signature resource, two Novice abilities from your pool (§13.3), armor and weapon |
| 2 | Talent |
| 3 | A third Novice ability |
| 4 | Attribute increase |
| **5** | **Adept:** RB +4, RD d8, Strain Capacity 9, Marks floor 1, Core (Adept form), an Adept ability |
| 6 | Talent |
| 7 | A second Adept ability |
| 8 | Attribute increase |
| **9** | **Master:** RB +6, RD d10, Strain Capacity 12, Marks floor 2, Core (Master form), a Master ability · **Tempo 2** (§5) · Elementalist sub-discipline (§14.1) |
| 10 | Talent |
| 11 | A second Master ability |
| 12 | Attribute increase |
| **13** | **Guru:** RB +8, RD d12, Strain Capacity 16, Marks floor 3, Core (Guru form), a Guru ability · **Tempo 3** (§5) |
| 14 | Talent |
| 15 | A second Guru ability |
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

### 13.3 Choosing abilities

Each class entry in §14 lists a **pool** at each rank, larger than the number you hold. The number you hold does not change: **three Novice, two Adept, two Master, two Guru — nine in a career**, as the level table gives them. What changes is which nine; two characters of one class should be able to meet and play differently.

- **Picks.** At each level that grants an ability, choose one from that rank's pool that you do not already hold.
- **Down-picks.** Any pick may be spent on an ability from an earlier rank's pool instead (a Master who wants a fourth Novice trick may have it). Never from a later rank.
- **Requires.** An ability marked *requires* needs the named ability held first (the Artificer's familiar skills, the Warlock's golem skills).
- **Tagged spells.** The Elementalist's element-bound spells and sub-discipline are in §14.1; no other class has a restriction on its pool.
- **Retraining.** At each rank-up (levels 5, 9, 13) you may exchange one ability you hold for another you qualify for. In the world this is a board's syllabus, a keeper's season, a column's drill manual, or a winter of bench work — the GM may ask which.
- **Joins** (§12) name specific abilities; a Join is available to a pair only if both hold what it requires. Cores are always held.
- **Opposition.** An NPC practitioner holds nine picks like a PC; the GM chooses them (GM Guide §4.5).

**Budget.** New abilities are written to the GM Guide's calibration lines (§12.1): Novice picks are control or utility at 0–1 Strain and at most 1 RD; Adept picks 2–3 Strain and at most 3 RD single-target or 2 RD in an area; Master picks 3–4 Strain and at most 4 RD; Guru picks 4–5 Strain or a Mark, at scenario scale. Passives cost a pick in place of Strain. Where a new ability bends a rule of §5 (an extra Action, a second summon Action), it says so and is listed in §17.

---

## 14. The twelve classes

Each entry gives: the fantasy; key attribute, armor, Vigor type; the **signature resource** (the little game only this class plays); the **Core** (the 0-Strain ability that changes form at every rank); the **Reading** and its exploit; the **ability pool** by rank (hold three Novice — two at level 1, one at 3 — two Adept at 5 and 7, two Master at 9 and 11, two Guru at 13 and 15; §13.1, §13.3), with a **Builds** line naming a few of the directions the pool supports (suggestions, not paths — any mix is legal); and the four canon cost stages. Damage entries add the Key modifier once per hit unless noted.

**A Core keeps every form it has had.** Choose the form each time you use it: a Master Elementalist casts *Kindle*, *Elemental Lash*, or *Elemental Sweep* as the round wants. The Novice, Adept, and Master forms cost 0 Strain. **The Guru form is the exception:** it is a scenario-scale ability and costs the Strain it lists; the Master form remains the Guru's 0-Strain turn.

Every ability answers three questions: what do I do every round (the Core and the resource); what makes me unlike every other class (the resource and the Reading); what happens at the next rank that the table will remember (the Core's next form and the Guru abilities).

---

### 14.1 Elementalist — Elemental (Saelura)

**Fantasy.** Battlefield elemental controller. Novice throws the element; Adept shapes what it does to the target; Master shapes the battlefield; Guru changes rivers, streets, and weather.
**Key** Attunement · **Armor** light · **Vigor** Magic · simple weapons.

**Elements.** Every Elemental spell chooses an element when cast: **Fire**, **Frost** (water and ice), **Storm** (air and lightning), **Stone** (earth). Damage kind follows the element.

**Element-bound spells.** A spell tagged [Fire], [Frost], [Storm], or [Stone] is always cast as that element and counts as it for Momentum; an untagged spell chooses its element when cast, as the Core does. **Sub-discipline** (level 9; canon's Master: "sub-discipline specialization becomes pronounced"): name one element. Element-bound Master and Guru spells you hold must be of it; *Eruption* counts as Stone or Fire. Novice and Adept element-bound spells, the untagged spells, and every form of the Core stay open to you. Retraining (§13.3) may change the sub-discipline only at level 13, and only by exchanging every element-bound Master spell you hold.

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

**Reading — Read the Answer** · free · 0 · exploit: Quick · a point or creature within 12: which element the ground answers here, and one weakness (a resistance, a vulnerability, a fault line). Exploit: your next spell of that element against that target has +2 to hit and grants 1 extra Momentum.

**Spells** — hold three Novice, two Adept, two Master, two Guru (§13.3). Tagged spells are element-bound.
**Builds.** *Pyromancer* — Ember Shield, Searing Brand, Pyre, Kiln Heart: stacks Burning and cashes it. *Frost warden* — Rime Skin, Hoarfrost, Deep Freeze, Winter Held: slows, then locks. *Stormcaller* — Gust, Arc, Storm Call, Wind Road: pushes, chains, and moves the party. *Earthshaper* — Heave, Earthen Grasp, Fault Line, Raise the Bastion: builds and breaks terrain. *Generalist* — Surge Step, Wall, Conduit, Harbor Kept: the Core carries the elements; the picks carry the party.

*Novice*
- **Ember Shield** [Fire] · Boon · Quick · 1 · self or an adjacent ally · Guarded 2 rounds; anyone who hits the bearer in melee takes 1 RD fire.
- **Rime Skin** [Frost] · Defense · Reaction · 1 · when you or an adjacent ally is hit in melee · the damage is reduced by RD + Key; the attacker is Slowed 1 round.
- **Gust** [Storm] · Control · Action · 1 · Cone 3 vs Guard · push 2; no damage; extinguishes Burning in the cone and clears smoke.
- **Heave** [Stone] · Control · Action · 1 · one square within 12 · a knee-high lip of earth rises: the square is low cover (+2 Guard to a creature behind it) and difficult terrain for the scene; a creature standing in it vs Guard is Prone.
- **Surge Step** · Utility · Quick · 1 · self · move 3 squares on your element without provoking. Fire: squares crossed burn this round (Burning 1 to anyone entering). Frost: squares crossed become difficult terrain. Storm: the move may cross a gap. Stone: the move may go through rubble as if clear.
- **Elemental Ward** · Defense · Quick · 1 · an ally within 6 · they resist one element's damage (your choice) for 2 rounds; if the element is the one the ground answers here (your Reading), also Warded.
- **Minor Works** · Utility · Action · 0 · within 6 · canon's Novice, whole: light or snuff a small fire, draw a cup of water from damp air, raise or still a light wind, shift a stone of a hand's weight. No combat effect; the GM says what it solves.

*Adept*
- **Wall** · Battlefield · Action · 3 · Wall 6 within 12, 3 rounds · Fire: crossing costs 2 RD fire and Burning 2. Frost: solid, full cover, 20 Vigor per square. Storm: a creature that ends its turn adjacent is pushed 2. Stone: solid, 30 Vigor per square; its top is high ground.
- **Shape the Ground** · Control · Action · 2 · Burst 2 within 12, 3 rounds · Stone or Frost: difficult terrain, and creatures inside vs Guard are Slowed. Storm or Fire: clear the area of terrain, smoke, or brush.
- **Searing Brand** [Fire] · Hex · Action · 2 · one creature within 12 vs Ward · 2 RD + Key fire and Burning 1; for 2 rounds its Burning does not decay.
- **Hoarfrost** [Frost] · Control · Action · 3 · Burst 2 within 12 vs Ward · 2 RD frost, Slowed 2 rounds; the squares ice over for 3 rounds (unstable footing: Poise DC 13 or Prone on entering).
- **Arc** [Storm] · Damage · Action · 3 · one creature within 12, then up to two more, each within 4 of the last · one roll compared to each Guard, in order; 2 RD + Key storm to each hit; the arc stops at the first miss.
- **Earthen Grasp** [Stone] · Control · Action · 2 · one creature within 12 vs Guard · stone closes over its feet: 1 RD + Key stone, Rooted 2 rounds, and Exposed while Rooted.

*Master* — element-bound Master spells must be of your sub-discipline.
- **Storm Call** [Storm] · Damage · Action · 4 · Sustained (upkeep: Quick) · while sustained, at each upkeep a bolt strikes one creature within 12: 2 RD storm vs Guard, Dazed on a hit.
- **Thunderclap** [Storm] · Control · Action · 3 · Burst 2 around you vs Ward · 2 RD + Key storm, Dazed 1 round, push 2; you may exclude any creature you can see.
- **Eruption** [Stone or Fire] · Damage / Control · Action · 3 · Burst 3 within 12, delayed: it happens at the start of your next turn and everyone can see the ground is wrong · 4 RD + Key stone (Prone) or fire (Burning 3), half on a miss.
- **Pyre** [Fire] · Damage · Action · 4 · one creature within 12 vs Ward · 4 RD + Key fire; if it is already Burning, add 1 RD per stack (at most +2 RD), then its Burning becomes 2.
- **Deep Freeze** [Frost] · Control · Action · 4 · one creature within 12 vs Ward · 3 RD + Key frost; Slowed 2 rounds with no Reactions; a target that was already Slowed is Stunned 1 round instead (the Boss limit applies).
- **Glacier** [Frost] · Battlefield · Action · 4 · Line 12 from you, 2 wide · creatures in it vs Guard take 3 RD frost and are Rooted 1 round; the line becomes a Frost Wall (full cover, 20 Vigor per square) for 3 rounds.
- **Fault Line** [Stone] · Battlefield · Action · 4 · Line 12 from you · the ground splits: 3 RD + Key stone vs Guard, Prone; the line is a trench for the scene (difficult terrain; a creature in it has cover against ranged attacks; a structure across it takes double from every source).
- **Conduit** · Boon · Quick · 3 · an ally within 6 · for 3 rounds their weapon hits deal +1 RD of your chosen element and apply its Adept rider.
- **Answering Body** · passive · you resist your sub-discipline's element; Momentum built in it has a maximum one higher.

*Guru* — element-bound Guru spells must be of your sub-discipline.
- **River Leaves Its Bank** · Battlefield · Action · 5 · Ground · a body of water, a lava stream, a slope of scree: a Wall 24 that moves 6 squares per round for 3 rounds; anything in its path takes 4 RD and is carried with it; the terrain is permanently changed.
- **Harbor Kept** · Boon / Battlefield · Action · 5 · Ground · a sustained work: a harbor kept ice-free, a fire held off a town, an aquifer held raised. It persists as long as you sustain it, in or out of combat. While held: Strain Capacity −1 per full phase held, restored at one per phase after release; each full year held (five phases) is 1 Mark (canon: sustained works draw cost after casting ends; the Escrow's organ-strain waivers are Stage 3).
- **Kiln Heart** [Fire] · Battlefield · Quick · 4 · Sustained (upkeep: Quick) · Burst 2 around you is a fire hazard to enemies only (Burning 1 on entering or ending a turn there); your Fire ignores resistance; Burning you apply does not decay while sustained.
- **Winter Held** [Frost] · Battlefield · Action · 5 · Ground · for the scene: open water freezes walkable; enemies who move more than 2 squares in a turn check Poise DC 13 or fall Prone; an enemy that ends its turn in the open is Slowed. Out of combat it holds a ford or a pass frozen for a day, on *Harbor Kept*'s schedule if held longer.
- **Wind Road** [Storm] · Utility / Battlefield · Action · 5 · Sustained (upkeep: Quick, 1 Strain) · you and up to five allies within 12 fly at Speed +2 and cannot be knocked Prone; ranged attacks against a flyer have Disadvantage. Out of combat, a day's wind-work doubles a boat's or an airship's pace (canon: guild wind-crew, priced by phase).
- **Raise the Bastion** [Stone] · Battlefield · Action · 5 · within 24 · up to four Wall 6 segments of stone (30 Vigor per square), or one tower 3×3, three squares high (full cover and high ground on top; you place who stands on it); permanent until broken. Creatures in placed squares are lifted to the top.

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

**Reading — Read Structure** · free · 0 · exploit: Quick · one object, structure, or creature within 12: its Guard, Ward, current Vigor, and one load-bearing point. Exploit: your next spell or attack against it ignores cover and any Guard from armor.

**Spells** — hold three Novice, two Adept, two Master, two Guru (§13.3). Canon allows the Guru two writable variables, time and gravity; every Guru spell below is one of them except *Echo Gate* (H64).
**Builds.** *Kineticist* — Telekinetic Grip, Dancing Blade, Crush, Vector Lock, Redirect the Fall: holds and throws bodies. *Seer* — Deflect, Catch, Calculated Shot, Foreknowledge, Total Perception, Time Debt: prediction and denial. *Structuralist* — Kinetic Lance, Measured Casting, Shatter Point, Arrest, Echo Gate: moves the map, not the enemy. *Chronometer* — Momentum Theft, Trajectory, Quickened Hour, Exterior Placement: makes the party faster than the fight.

*Novice*
- **Telekinetic Grip** · Control · Action · 2 · one creature within 12 vs Ward · Grabbed and Rooted; Sustained (upkeep: Quick); at each upkeep move it 2 squares (1 if Large) — into a hazard, off a ledge, into reach.
- **Deflect** · Defense · Reaction · 1 · a ranged attack against you or an adjacent ally: the target's Guard +RD against it.
- **Unseen Hand** · Utility · Quick · 0 · a light object within 12: open, pull, drop, trigger, carry.
- **Kinetic Lance** · Damage / Control · Action · 1 · Line 6 vs Guard · 1 RD + Key force to each creature hit, and each is pushed 1 along the line.
- **Kinetic Buffer** · Defense · Reaction · 1 · when you are hit in melee · the damage is reduced by RD + Key and the attacker is pushed 1.
- **Catch** · Utility · Reaction · 1 · within 12 · a falling creature or object stops a pace above the ground and lands unhurt; or a thrown object or flask is caught in the air and may be dropped where you choose within 2.
- **Dancing Blade** · Damage · Action · 1 · a simple or martial weapon within 12 · it attacks one creature within 2 of it: d20 + Reckoning + RB vs Guard, weapon die (no Key); Sustained (upkeep: Quick), 3 rounds at most: at each upkeep it may move 6 and attacks again.

*Adept*
- **Anchor** · Boon / Control · Quick · 2 · one ally within 12 can't be moved or knocked Prone against their will for 3 rounds; or an object or a volume of air within 12 is fixed in place for 3 rounds (a beam caught, a door held, a cage for a Join).
- **Momentum Theft** · Defense · Reaction · 2 · a projectile or a charging creature within 12: the projectile drops; the creature stops in its square and loses its next Move.
- **Calculated Shot** · Damage · Action · 2 · one creature within 24 you have Read this encounter · 3 RD + Key force vs Guard; ignores cover; it may bank off one surface you can see, so line of sight to the target is not needed.
- **Crush** · Damage / Control · Action · 3 · one creature within 12 vs Ward · force from every side: 2 RD + Key force and Slowed 2 rounds; a Grabbed target takes +1 RD.
- **Measured Casting** · passive · once per turn, a Sorcerer spell costing 2 or more costs 1 less if you have not moved this turn. Canon's Adept: restraint is the training; rushing is what burns.

*Master*
- **Shatter Point** · Battlefield · Action · 4 · a structure or construct within 12 that you have Read fails at the read point: a wall segment collapses (Line 6 of rubble; 4 RD to creatures adjacent; difficult terrain); a bridge span drops; a gate falls; a construct is Stunned 1 round and Exposed 2 rounds.
- **Total Perception** · Boon · Quick · 3 · Sustained (upkeep: Quick) · you and allies within 6 re-roll Initiative now with Advantage; attacks against you have Disadvantage; you may spend Overlay charges on allies' attack rolls within 6.
- **Foreknowledge** · Defense · Reaction · 2 · 2 Overlay charges · when an enemy within 12 declares an attack · you or its target moves up to 3 squares before it resolves; the attack is made against the square.
- **Vector Lock** · Control · Action · 4 · Burst 2 within 12 vs Ward · momentum zeroed: 3 RD + Key force, half on a miss; creatures hit cannot move or be moved and have no Reactions for 1 round.
- **Trajectory** · Boon · Quick · 3 · Sustained (upkeep: Quick) · allies' ranged attacks against targets within 12 of you ignore cover and have no Disadvantage against adjacent targets; each ally's first ranged hit in a round deals +1 RD force.

*Guru* — each edit is placed exterior to you (canon doctrine since 1201).
- **Time Debt** · Control · Action · 5 · once per encounter · one creature within 12 vs Ward · it is pulled out of the sequence: it loses its next turn, its Interrupts (if it has them) are not refreshed, and every ally may make a Reaction attack against it. Not a hex: no shake-off applies, and it does not count as a Boss's Stun for the phase.
- **Exterior Placement** · Utility · passive · while a Substrate Edit is sustained you may move its volume 3 squares at each upkeep, and Slow Field's Speed penalty doesn't apply to your allies (they act at your pace).
- **Quickened Hour** · Boon · Action · 5 · 3 Overlay charges · Burst 2 within 12, exterior · Sustained (upkeep: Quick) · time runs fast inside: an ally who starts its turn inside takes one extra Action that turn, usable for a Strike, a Core, or a Dash only (never a costed ability). Time: the canon's fast region.
- **Arrest** · Defense · Reaction · 4 · within 24 · gravity held: a collapsing structure, a falling creature or object, a charge, or a volley stops where it is until the end of your next turn; a charging creature loses the rest of its movement and its next Action. Canon: arresting a collapse.
- **Redirect the Fall** · Control · Action · 4 · one creature, Huge or smaller, within 24 vs Ward · its gravity's vector turns: it falls 6 squares in any direction you choose — sideways into a wall, up and down again — taking falling damage for 6 squares plus 3 RD force, and lands Prone.
- **Echo Gate** · Utility / Battlefield · Action · 5 · 3 Overlay charges · Sustained (upkeep: Quick) · two points within 24 you can see, neither containing you · each becomes a 1-square gate: a creature stepping into one steps out of the other as 1 square of movement; projectiles and area effects pass through. A field version of station work (canon: portal stations are Guru-presided); the Ledger files every opening (GM Guide §8.5).

**Cost stages.** Headache → Tremor → Time-lag perception → Memory dissonance (the End: identity-time fracture).

---

### 14.3 Apothecarist — Nature (Threnis)

**Fantasy.** Shapeshifting life-master. Novice runs with an animal and mends; Adept cures, commands beasts, and borrows a soma; Master regenerates allies and lends somas; Guru takes an apex form and calls the ground's animals.
**Key** Attunement · **Armor** light · **Vigor** Magic · simple weapons (staff).

**Companion** (Novice). A bonded animal (wolf, hawk, lynx, boar, otter — a natural creature of the region): Vigor 3 × your level, Guard = your Guard, attacks with your attack bonus for 1 RD + 2 physical, Speed 8 (a hawk flies 12). Commanding it is a Quick Action; uncommanded it stays with you and defends. From Master it acts on your turn without a command. If it dies, a new bond forms after a full Rest. It uses its own figurine.

**Signature resource — Adaptations** (from Adept). Somas you can borrow: **Hawk** (see 24 squares in the dark; Advantage on Notice; +2 on ranged attacks) · **Wolf** (Speed +2; ignore difficult terrain; track by scent) · **Bear** (+2 on Frame checks; +1 RD on melee damage; Fortified RD) · **Serpent** (melee hits apply Poisoned 1; Advantage on Ward against toxin) · **Lizard** (Regenerating 2) · **Otter** (swim at Speed; hold breath ten minutes) · **Bat** (blindsense 6: Blinded doesn't affect you) · **Stag** (leap 4; +1 Guard) · **Boar** (after moving 3 or more squares in a turn, your next melee hit deals +1 RD and pushes 1) · **Gecko** (climb at full Speed, overhangs included) · **Owl** (move silently; Hidden in dim light while you do not attack). Adopt one: Quick · 1 Strain · it lasts until a Rest or you drop it. Active at once: Adept 1, Master 2, Guru 3.

**Core — the Mend line.**
- **Novice · Mend** · Heal · Action · 1 · touch · 1 RD + Key Vigor; removes Bleeding.
- **Adept · Cure** · touch, or within 6 delivered by your Companion · 2 RD + Key; remove one hex (Poisoned, Burning, Bleeding, Blinded, Slowed).
- **Master · Regenerate** · range 6 · 3 RD + Key; Regenerating RD for 3 rounds; remove all hexes.
- **Guru · Remake** · Action · 5 · touch · the target is restored to full Vigor, or a Downed ally rises at full Vigor, or a limb regrows, a permanent injury is undone. Used on someone at 0 Vigor it costs you 1 Mark: the body is borrowed from your own.

**Reading — Read the Living** · free · 0 · exploit: Quick · a creature within 6: its current Vigor, one hex or injury it carries, one bodily weakness (the forelimb compensating for an old fracture). Exploit: attacks by you or any ally who can hear you against that weakness crit on 19–20 until the end of your next turn.

**Spells** — hold three Novice, two Adept, two Master, two Guru (§13.3).
**Builds.** *Beastmaster* — Pack Bond, Hold Attention, Alpha, Pack, Command the Ground: the Companion is the weapon. *Mender* — Stabilize, Thicken Hide, Hold the Channel, Lifeweb, Green Return: nobody drops. *Thornwarden* — Bramble, Wild Call, Open the Wound, Pollen Drift, Channel Redirect: the living ground fights for you. *Shapeshifter* — Sense the Green, Beast Command, Share Soma, Apex Form, Herd Soma: the somas are the build.

*Novice*
- **Wild Call** · Damage / Control · Action · 1 · Burst 1 on a point within 12 vs Guard · small wildlife swarms: 1 RD + Key physical; creatures hit have Disadvantage on their next attack.
- **Stabilize** · Heal · Quick · 0 · touch a Downed ally: the clock stops; they regain 1 Vigor at the start of their next turn.
- **Hold Attention** · Control · Action · 1 · a beast within 12 vs Ward · for 1 round it can attack no one but you and moves toward you.
- **Pack Bond** · passive · your Companion's attacks deal +1 RD; when you and your Companion attack the same creature in a turn, the second attack has Advantage.
- **Bramble** · Control · Action · 1 · Burst 1 within 12, on soil or brush · thorn growth for the scene: difficult terrain; a creature entering or starting its turn there is Bleeding 1.
- **Speak With Beasts** · Utility · Action · 0 · a natural animal within 6 · one question, one answer, in its register (where water is, what passed, what it fears). Canon's Novice: rudimentary animal communication.
- **Sense the Green** · Utility · Action · 0 · Burst 12 around you · the condition of flora and fauna: creatures hidden in brush or among animals are revealed to you; fouled water, sick animals, and fresh tracks are named.

*Adept*
- **Beast Command** · Control · Action · 3 · a natural creature of Adept tier or lower within 12 vs Ward · it obeys you for 3 rounds. Grand Beasts have Advantage on the Ward.
- **Thicken Hide** · Boon · Quick · 2 · an ally within 6 · Fortified 2 RD, and they resist 2 physical damage from every hit, 3 rounds.
- **Open the Wound** · Hex · Action · 2 · touch, or within 6 delivered by your Companion vs Guard · you find where the damage sits and widen it: 2 RD + Key physical, Bleeding 2; the target regains no Vigor until the end of your next turn.
- **Alpha** · Boon · Quick · 2 · your Companion · it is Large for 3 rounds: +1 RD on its attacks, Fortified 2 RD, and its hits push 1.
- **Pollen Drift** · Control · Action · 3 · Burst 2 within 12 vs Ward · Blinded 1 round; creatures hit have Disadvantage on Notice for the scene.

*Master*
- **Share Soma** · Boon · Quick · 3 · touch an ally · one of your active Adaptations is theirs too for 3 rounds (Bear to the Paladin; Wolf to the Vanguard; Hawk to the Warden).
- **Channel Redirect** · Heal / Control · Action · 4 · touch · move up to 3 RD Vigor from one creature you touch (a willing ally, or a creature you or an ally have Grabbed) to another creature you touch, yourself included. Canon Master: redirects channels to manage life force.
- **Hold the Channel** · Heal · Reaction · 3 · when an ally within 6 would be Downed · they drop to 1 Vigor instead, and regain 2 RD at the start of their next turn.
- **Lifeweb** · Heal · Action · 4 · up to four allies within 12 · Sustained (upkeep: Quick) · the channels are linked: damage any linked ally takes is split evenly among all of them (round down); at each upkeep each regains 1 RD.
- **Pack** · Summon · Action · 4 · your Companion calls its kind: two more of its species join it for the scene (Vigor half the Companion's each). They move with it; its Action makes one attack for each of the pack still standing.

*Guru*
- **Apex Form** · Boon · Action · 5 · self · Sustained (upkeep: Quick), 5 rounds at most · every soma active at once; natural weapons 2 RD + Key; Speed 10; Regenerating 5; Large size. When it ends: Dazed 1 round.
- **Command the Ground** · Summon / Battlefield · Action · 5 · Ground · the region's animals arrive over 2 rounds as a Mob under your orders (Cohesion 3 × RD); or the local flora seizes the field: Burst 4, enemies vs Ward are Grabbed at the start of each of their turns, 3 rounds.
- **Herd Soma** · Boon · Action · 5 · allies within 6 · each takes one of your active Adaptations, your choice for each, for 3 rounds.
- **Green Return** · Heal / Battlefield · Action · 5 · Ground · Sustained (upkeep: Quick) · the ground's life flows toward the party: at each upkeep every ally on the map regains RD Vigor; enemies standing on soil, brush, or timber are Slowed.

**Cost stages.** Scar tissue → Sensory narrowing → Partial morphic blending → Species bleed.

---

### 14.4 Necromancer — Necrotic (Velquor)

**Fantasy.** Master of the death boundary. The school does not raise, animate, or command the dead — canon — and never will here. Novice senses death and residue; Adept reads recent crossings; Master weaponizes residue and interrogates scenes; Guru holds a crossing open.
**Key** Attunement · **Armor** light; no gloves, gauntlets, or shield — the Gloves slot takes wraps that leave the palm bare (§15) · **Vigor** Magic · simple weapons.

**Signature resource — Residue.** Gain 1 Residue whenever a creature dies within 6 squares of you (maximum 5). In a place of prior death the GM may start you with some. Spend it as listed. Residue doesn't persist past the scene.

**Core — the Boundary line.**
- **Novice · Chill of the Boundary** · Damage · Action · 0 · range 12 vs Ward · 1 RD + Key necrotic; the target regains no Vigor until the end of your next turn.
- **Adept · Boundary Touch** · 2 RD + Key; Weakened 1 round on a hit; delivered by touch it deals +1 RD.
- **Master · Residue Bloom** · spend 1 Residue · Burst 2 within 12 vs Ward · 3 RD + Key necrotic, half on a miss; creatures hit are Frightened 1 round — the boundary opens in front of them.
- **Guru · Threshold** · Control · Action · 5 · Sustained (upkeep: Quick), 3 rounds · one creature within 6 that is Downed or dies this round: you hold its crossing. **An ally** stands at 1 Vigor that cannot drop for 3 rounds and may act. When the hold ends, a creature that died this round returns to death whatever its Vigor; a Downed creature returns to Downed at its clock unless healed above 1 during the hold — a delay measured in breaths, not a return. **An enemy** dies at the end of the third round no matter what; until then it takes 2 RD necrotic at the start of each of its turns and cannot regain Vigor.

**Reading — Read the Crossing** · free · 0 · exploit: Quick · a body or a place within 6: when it died, how, and the emotional register. Exploit: a creature within 12 that has killed something this encounter: you learn its current Vigor and which of its defenses is lower; your next spell against it has +2.

**Spells** — hold three Novice, two Adept, two Master, two Guru (§13.3). Nothing below raises, animates, or commands the dead (canon, Part VI).
**Builds.** *Reader* — Sense the Door, Mortal Count, Last Words, Boundary Interrogation, Finish the Sentence: the investigator the Ledger will not admit. *Grave-cold* — Grave Cold, Pallor, Shiver, The Instant, Open Door: fear and denial. *Residue-eater* — Residue Well, Ebb, Cold Room, Wake of Crossings, Short Crossing: the more that dies, the harder it lands. *Doorkeeper* — Self-Grounding, Ward of Residue, Deathwatch, Stand in the Doorway: holds the party on the right side.

*Novice*
- **Grave Cold** · Control · Action · 1 · Burst 1 within 12 vs Ward · Slowed 1 round; if anything died in the area this scene, gain 1 Residue.
- **Self-Grounding** · Defense · Quick · 1 · self · controlled pain: remove Frightened and Dazed from yourself; Resolute 2 rounds.
- **Sense the Door** · Utility · Action · 0 · learn whether anything within 24 squares is at 0 Vigor or dying, with direction and distance.
- **Numbing Touch** · Hex · Quick · 1 · touch vs Ward · bare palm to skin: Weakened 1 round.
- **Pallor** · Hex · Action · 1 · a creature within 12 vs Ward · the boundary shows on its face: Frightened 1 round, 2 rounds if it is at half Vigor or less.
- **Mortal Count** · Utility · Quick · 0 · within 12 · you know which creature is nearest to death (lowest share of its Vigor); your next attack against it this round has +2.
- **Residue Well** · passive · you gain Residue from deaths within 12 squares (not 6), and you begin every encounter with 1 Residue.

*Adept*
- **Last Words** · Utility · Action · 2 · touch a body dead less than a day: what it saw in its last three breaths; if it saw its killer, you can describe them. Enables *Last Witness*.
- **Ward of Residue** · Boon · Quick · spend 1 Residue · an ally within 6 · Fortified 2 RD; while it lasts the first hex applied to them fails.
- **Ebb** · Damage · Action · 2 · one creature within 12 vs Ward · 2 RD + Key necrotic; against a creature at half Vigor or less, +1 RD and it regains no Vigor until the end of your next turn.
- **Shiver** · Control · Reaction · 2 · when a creature within 12 attacks one of your allies · vs Ward: the attack has Disadvantage and it is Frightened of you 1 round.
- **Cold Room** · Battlefield · Action · 3 · Burst 2 within 12 · Sustained (upkeep: Quick) · a room where someone died: an enemy that starts its turn inside takes 1 RD necrotic and regains no Vigor; a death inside grants you Residue wherever you stand.

*Master*
- **Residue Edge** · Boon / Hex · Quick · 3 · bare hand on an ally's weapon · for 3 rounds its hits deal +1 RD necrotic and apply Weakened.
- **Boundary Interrogation** · Utility · Action · 3 · a death scene within 12 in analytic detail: every crossing there, separated by age; who stood where; the instant consciousness was and was not.
- **Wake of Crossings** · Damage · Action · 4 · one creature within 12 vs Ward · 4 RD + Key necrotic; spend up to 2 Residue for +1 RD each.
- **The Instant** · Control · Action · 3 · a creature within 12 at half Vigor or less, vs Ward · you show it the instant consciousness was and was not: Dazed and Frightened 2 rounds (the shake-off applies to each).
- **Deathwatch** · Boon · Quick · 3 · Sustained (upkeep: Quick) · you and allies within 6 know the current Vigor of every creature within 24, and crit on 19–20 against any creature at a quarter of its Vigor or less.

*Guru*
- **Open Door** · Damage / Control · Action · 3 Strain + 3 Residue · Burst 3 within 12 vs Ward · the boundary thins: 4 RD necrotic, Frightened 2 rounds; a creature at half Vigor or less that fails by 5 or more is Stunned 1 round.
- **Stand in the Doorway** · Boon · Quick · 4 · 3 rounds · you and allies within 3 squares cannot be reduced below 1 Vigor by any single hit; the excess is lost.
- **Finish the Sentence** · Utility · Action · 5 · a creature within 6 that died within the hour, or is dying now · the crossing is held for three breaths: it finishes what it was saying, names a killer, says goodbye — three questions, answered as it knew them. Canon's Guru, whole: a delay, not a return; it cannot act.
- **Short Crossing** · Battlefield · Action · 5 · Ground · Sustained (upkeep: Quick), 3 rounds at most · the boundary lies close across the map: a standard enemy at a quarter of its Vigor or less that takes necrotic damage from you crosses (it drops to 0 and dies); your necrotic damage deals +1 RD; every death on the map grants you 1 Residue. Elites and Bosses take the +1 RD only.

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

**Reading — Read the Heart** · free · 0 · exploit: Quick · a creature within 12: its resolve (steady, wavering, Frightened, loyal to whom) and what it wants this round. Exploit: your next Rebuke or Command against it has Advantage; against a Mob, you learn which part will break first.

**Spells** — hold three Novice, two Adept, two Master, two Guru (§13.3).
**Builds.** *Chaplain* — Steady, Get Up, Slow the Pulse, Miracle, Lent Years: the will that keeps bodies standing. *Herald* — Inspire, Voice Carries, Oath, Standard, The Order Given: the party acts harder and more often. *Inquisitor* — Denounce, Calm, Weight of Voice, Judgment, Unmake the Will: the voice as a weapon. *Shield of the Rite* — Word of Warning, Stand With Me, Unbreakable, Refuse Death: takes the hit and refuses the loss.

*Novice*
- **Steady** · Boon · Quick · 1 · touch · Fortified 1 RD + Key; removes Frightened. Canon: touch steadies pain without treating the source.
- **Inspire** · Boon · Quick · 1 · an ally within 12 · Inspired.
- **Voice Carries** · Boon · Action · 1 · allies within 6 who can hear you · +2 Speed this round and Resolute 1 round.
- **Calm** · Control · Action · 1 · a creature within 6 that can hear you, vs Ward · its pulse slows: it attacks no one this round unless it is attacked first. Canon: presence produces calm in the distressed.
- **Word of Warning** · Defense · Reaction · 1 · an ally within 12 who can hear you is attacked · +2 Guard or +2 Ward against that attack.
- **Get Up** · Heal · Action · 1 · a Downed ally within 12 who can hear you · 1 RD + Key Vigor; they may stand as a free action on their turn.
- **Denounce** · Hex · Quick · 1 · a creature within 12 vs Ward · the next attack against it before the end of your next turn has Advantage.

*Adept*
- **Encouragement Lands** · Boon · Action · 2 · Burst 3 around you · allies: Bolstered 2 rounds; gain 1 Conviction per ally affected, up to 3.
- **Stand With Me** · Defense · Reaction · 2 · when an ally within 6 is hit: the damage is halved; you take the other half.
- **Weight of Voice** · Damage / Control · Action · 2 · Cone 4 vs Ward · the voice lands physically: 2 RD + Key sacred, push 2; half on a miss, no push.
- **Slow the Pulse** · Heal · Quick · 2 · an ally within 6 · reassurance made physical: remove Frightened, Dazed, and Bleeding; Regenerating 3 for 2 rounds.
- **Oath** · Boon · Action · 2 · an ally within 12 swears against one creature you can both see · for 3 rounds their hits against it deal +1 RD sacred; if it falls to their hit, you gain 2 Conviction.

*Master*
- **Miracle** · Heal · Action · 3 Strain + 3 Conviction · an ally within 12 · 3 RD + Key Vigor; remove all hexes; a Downed ally rises with that Vigor.
- **Boon of Endurance** · Boon · Action · 3 · up to 3 allies within 6 · Regenerating 3 and Resolute, 3 rounds.
- **Unbreakable** · Boon · Quick · 3 · an ally within 6 · for 3 rounds: Resolute and Warded, and a Stun on them becomes Dazed instead.
- **Judgment** · Damage · Action · 4 Strain + 2 Conviction · a creature within 12 vs Ward · 4 RD + Key sacred; a Sanctioned target is also Stunned 1 round (the Boss limit applies).
- **Standard** · Boon · Action · 4 · Sustained (upkeep: Quick) · Burst 2 around you, moving with you · allies inside are Bolstered; at each upkeep each ally inside gains Fortified RD and you gain 1 Conviction.

*Guru*
- **Refuse Death** · Heal · Action · 5 Strain + 1 Mark · once per encounter · a creature that died this encounter within 6 · it returns with half its maximum Vigor and no hexes. The Mark is the years transferred — canon: lifespan transference is the ability, not its side effect.
- **Lent Years** · Heal · Quick · 1 Mark · an ally within 6 · full Vigor, now. The Assay counts it in years; so do you.
- **Unmake the Will** · Control · Action · 5 · once per encounter · a creature or Mob within 12 vs Ward · the voice takes the fight out of it: a standard enemy surrenders or flees; an Elite is Frightened 2 rounds and loses its next Action; a Boss loses its next Action (not a Stun; no shake-off); a Mob checks Cohesion at Disadvantage (GM Guide §5.5).
- **The Order Given** · Boon · Action · 5 · once per encounter · every ally on the map who can hear you, allied Mobs included · each immediately takes a Move and one Strike or Core, out of turn; you gain 1 Conviction for each ally who hits.

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

**Reading — Read the Weight** · free · 0 · exploit: Quick · a creature within 6: whom it will attack next and how. Exploit: your Reactions against that creature this round have Advantage, and your *Intercept*, if you hold it, costs 0.

**Skills** — hold three Novice, two Adept, two Master, two Guru (§13.3).
**Builds.** *Bodyguard* — Intercept, Principal, Bulwark, Escort of Record, The Guard That Will Not Drop: the principal lives. *Duelist* — Shield Bash, Challenge, Blind Angle, Duelist's Measure, Shut Down: one opponent, taken apart. *Counter-practitioner* — Line Step, Disarm, Counter-Practitioner, Breath Reader, Take the Flask: the escort of record against casters. *Line-breaker* — Shield Wall, Hold the Door, Lockdown, Retire the Options, Fold the Line: the formation dismantled.

*Novice*
- **Intercept** · Defense · Reaction · 1 · when an ally within 2 squares is attacked: move up to 2 to be adjacent to them; the attack targets you instead. Gain 1 Parry.
- **Shield Wall** · Boon · Quick · 1 · you and adjacent allies are Guarded while you don't move this round.
- **Line Step** · Utility · Quick · 1 · move 2 without provoking; you may swap places with an adjacent ally.
- **Shield Bash** · Control · Action · 1 · an adjacent creature · a shield attack (d6 + Key, with the Rank Bonus) vs Guard; hit: Dazed 1 round.
- **Hold the Door** · Control · Quick · 1 · until your next turn, enemies cannot move out of squares adjacent to you except by Disengaging, and a Disengage past you provokes anyway.
- **Principal** · Boon · Quick · 0 · once per encounter · name an ally: while they are within 2 of you, your *Intercept* costs 0 Strain and Parry you gain from it is 2.
- **Challenge** · Hex · Quick · 1 · a creature within 6 vs Ward · for 1 round it has Disadvantage on attacks against anyone but you.

*Adept*
- **Lockdown** · Control · Action · 2 · Strike; hit: Rooted 2 rounds and no Reactions.
- **Bulwark** · Defense · Quick · 2 · you may take two Reactions this round.
- **Blind Angle** · Damage · Action · 2 · Strike with Advantage against a creature that is Bound, or that attacked someone other than you on its last turn; hit: +1 RD.
- **Duelist's Measure** · Boon · Quick · 2 · one creature within 6 · for 3 rounds: +2 Guard against it, and your Ripostes against it deal +1 RD.
- **Disarm** · Control · Action · 2 · Strike; hit: it drops one held weapon or focus; until it spends an Action to recover it, its weapon attacks deal −1 RD, or a practitioner's first costed ability costs 2 more Strain.

*Master*
- **Counter-Practitioner** · Control · Reaction · 3 · when a creature within 6 begins any ability with a Strain cost: move up to your Speed and Strike; on a hit the ability fails and its Strain is spent. Canon: closes the distance inside a chant; takes flasks and bolts on the boss.
- **Shut Down** · Control · Action · 4 · Strike against an Elite or Boss; hit: Stunned 1 round; you gain 3 Parry.
- **Breath Reader** · passive · you read casting posture and breath: your Punishes and Reactions against a creature using a costed ability have Advantage, and a creature adjacent to you that begins one provokes a Punish.
- **Take the Flask** · Defense · Reaction · 3 · when a thrown flask, vial, or bolt, or an area centered within 6, would land · move up to 3 to its point; it resolves against you alone, and you take half.
- **Escort of Record** · Boon · Action · 3 · Sustained (upkeep: Quick) · one ally · while they are within 3 of you, attacks against them have Disadvantage, and every miss against them gives you 1 Parry.

*Guru*
- **Fold the Line** · Battlefield · Action · 5 · Sustained (upkeep: Quick) · while you stand inside a Mob (GM Guide §5.7) it cannot move, it loses RD Cohesion at each upkeep, and its attacks against you are capped at the drill's attack cap (no engulfment).
- **The Guard That Will Not Drop** · Defense · Quick · 4 · 3 rounds · Guard +RD; attacks against allies adjacent to you have Disadvantage; you gain 1 Parry from every miss against any adjacent ally, not only you.
- **Retire the Options** · Control · Action · 5 · a creature or Mob within 6 vs Ward · for 2 rounds it takes only one of Move, Action, or Reaction each turn (the shake-off applies; a Mob loses RD Cohesion instead of checking). Canon: a formation's options retire one by one.
- **Turn Numbers into a Queue** · Defense · passive · no more than two creatures may attack you in a round; a Mob can bring one attack against you a round. The platoon, made to wait.

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

**Reading — Read the Flow** · free · 0 · exploit: Quick · where each enemy within 6 intends to move this round. Exploit: +2 on your attacks this round against any creature that moves.

**Skills** — hold three Novice, two Adept, two Master, two Guru (§13.3).
**Builds.** *Pikeman* — Keep Spacing, Extend, Deny, Circle Nobody Enters, Unscheduled: the two-pace circle as a wall. *Skirmisher* — Hinge, Pole Vault, Hook, Shifting Guard, Geometry: moves bodies, including its own. *Line officer* — Rank Drill, Point Guard, Read the Melee, Anchor the Hinge, Doctrine: the formation fights better around you. *Reaper* — Haft and Butt, Trip Line, Break Formation, Bent Line, The Last Reach: many targets, every round.

*Novice*
- **Keep Spacing** · Control · Reaction · 1 · when an enemy moves adjacent to you: Strike it and push it 1.
- **Hinge** · Utility · Quick · 1 · swap places with an adjacent ally, or slide an adjacent ally 1 square.
- **Haft and Butt** · Attack · Action · 1 · two Strikes at −2 each against creatures in reach; one may push 1 instead of dealing damage.
- **Extend** · Attack · Action · 1 · a Strike at reach 3 with +1 RD; hit: the target is pushed 1.
- **Rank Drill** · passive · while an ally is adjacent to you, +1 Guard and +1 on attack rolls.
- **Point Guard** · Boon · Quick · 1 · an ally within 2 · Guarded while they stay within 2 of you, 2 rounds.
- **Pole Vault** · Utility · Move · 1 · leap up to 3 squares over a creature, a gap, or a low wall, planting the haft; the move does not provoke.

*Adept*
- **Trip Line** · Control · Action · 2 · Strike up to 2 creatures in reach; hits knock Prone.
- **Deny** · Control · Quick · 2 · Sustained (upkeep: Quick) · three contiguous squares adjacent to you: the first enemy each round to enter them takes a Strike and stops there.
- **Circle Nobody Enters** · Battlefield · Quick · 3 · Sustained (upkeep: Quick) · a creature that enters your reach standing checks Poise vs your Guard or falls Prone in the first square it entered. Canon's Adept: the two-pace circle nobody enters standing.
- **Hook** · Control · Action · 2 · Strike + RD at reach 2; hit: pull it 1 toward you, and a Medium or smaller target is Prone.
- **Shifting Guard** · Defense · passive · after you spend Flow to shift, +2 Guard until your next turn.

*Master*
- **Break Formation** · Battlefield · Action · 4 · enter a Mob (GM Guide §5.7): Strike each adjacent creature (one roll); the Mob loses RD Cohesion and can bring no more than 2 attacks against you this round.
- **Anchor the Hinge** · Boon · Quick · 3 · 3 rounds · allies within 2 have +2 Guard against creatures you have hit this encounter; you gain 2 Flow.
- **Read the Melee** · Boon · Quick · 3 · allies within 6 · each may shift up to 2 now without provoking; you gain 1 Flow per ally who moves (at most 3).
- **Geometry** · Control · Action · 3 · Strike + RD; hit: move the target to any square within your reach, Large or smaller.
- **Bent Line** · Defense · Reaction · 3 · when an enemy within your reach attacks an ally · Strike it first; hit: its attack has Disadvantage.

*Guru*
- **Unscheduled** · Control · Reaction · 5 · once per round: when any enemy within 4 squares ends its movement, *Corridor* to it and Strike; if it belongs to a Mob, the Mob loses RD Cohesion.
- **Terrain** · Battlefield · passive · *Moving Circle*'s upkeep is the Quick only (no Strain); enemies inside it cannot Dash or Disengage.
- **The Last Reach** · Attack · Action · 5 · your reach is 4 this Action · one roll compared to the Guard of every enemy within 4: each hit takes a Strike's damage (one attack) and is Prone; a Mob loses RD Cohesion.
- **Doctrine** · Boon · Action · 5 · Ground · 3 rounds · every ally adopts your spacing: melee reach +1, and the first Punish each round costs them no Reaction. Canon: Steel Quorum doctrine, written and sold.

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
- **Guru · Unanswerable** · Battlefield · Action · 5 · Sustained (upkeep: Quick) · you are Hidden and stay Hidden after attacks; finding you needs Notice DC 26. At each upkeep, three Strikes against targets within 24 — one target or several; against a Mob, each may name a member (a hit kills it) or strike the block. While it is sustained, these three are your Strikes for the turn: the Strike Action and any ability that includes a Strike are unavailable on your turn; Reactions are unaffected. A Mob that loses a member to you loses 2 Cohesion per death: fear does the arithmetic.

**Reading — Read the Ground** · free · 0 · exploit: Quick · the routes enemies within 24 will take, and the chokepoints. Exploit: Advantage on your first attack this round against any creature crossing a route you read.

**Skills** — hold three Novice, two Adept, two Master, two Guru (§13.3).
**Builds.** *Sniper* — Vanish, Leading Shot, Called Shot, Where It Will Be, No Counted Arrows: one arrow, the right one. *Hunter* — Camp Scout, Read Sign, Track, Snare, Bleeding Shot: the Quarry never leaves the map. *Skirmisher* — Dagger Work, Nock and Move, Ghost, Pinning Volley: close, then gone. *Holder of the pass* — Volley, Pin, Hold the Pass, Impassable, No Safe Pace: ground the enemy will not cross.

*Novice*
- **Vanish** · Utility · Quick · 1 · with cover or concealment: you are Hidden (found by Notice ≥ 10 + Poise + RB).
- **Pin** · Control · Action · 1 · Strike; hit: Rooted 1 round.
- **Camp Scout** · Utility · passive · you cannot be surprised; when you have scouted, the party has +2 Initiative.
- **Volley** · Damage · Action · 1 · Burst 1 within 24 vs Guard · 1 RD + Key physical; half on a miss.
- **Dagger Work** · Attack · Quick · 1 · after a bow Strike this turn · a dagger Strike (d4 + Key) against an adjacent creature.
- **Read Sign** · Utility · Action · 0 · a trail, camp, or crossing · how many passed in the last day, of what kind, at what pace, and whether they expected to be followed.
- **Nock and Move** · Utility · passive · you may split your Move before and after each Action.

*Adept*
- **Snare** · Control · Action · 2 · a square within 6, hidden until sprung: the first enemy to enter is Rooted 2 rounds and takes 2 RD.
- **Track** · Utility · Action · 0 · find your Quarry across any biome, up to a day behind; Advantage on every check to follow it.
- **Leading Shot** · Attack · Action · 2 · Strike + RD against a creature that moved this round, with Advantage; a Hastened target loses Hastened.
- **Ghost** · Utility · Quick · 2 · while Hidden · move up to your Speed from cover to cover without breaking Hidden.
- **Pinning Volley** · Control · Action · 3 · Burst 2 within 24 vs Guard · 2 RD + Key physical, Slowed 1 round; half on a miss, no Slow.

*Master*
- **Bleeding Shot** · Damage / Hex · Action · 3 · Strike + RD; hit: Bleeding 3.
- **Hold the Pass** · Battlefield · Action · 4 · Sustained (upkeep: Quick) · a Line 12 you can see: each enemy that crosses it takes a free Strike; a Mob that crosses it loses RD Cohesion.
- **Where It Will Be** · passive · your Readied Strikes and your *Overwatch* Strikes crit on 18–20. Canon's Master: the shot arrives where the target will be.
- **Called Shot** · Control · Action · 4 · Strike + RD at a named part; hit: legs (Slowed 2 rounds, no Dash), arm (Weakened 2 rounds), or eyes (Blinded 1 round). The shake-off applies.
- **Impassable** · Battlefield · Action · 4 · Burst 3 within 24 · for the scene the ground is under your bow: difficult terrain for enemies, and an enemy entering it is Frightened 1 round. Canon: what made the Mwamba foothills impassable.

*Guru*
- **The Unclosing Eye** · passive · immune to surprise and Blinded; Insight maximum 4; Crit Chance 19–20 against your Quarry from Insight 1.
- **The First Ten Deaths** · Control · Action · 5 · against a Mob within 24: three Strikes, each a kill against a Mob member; the Mob then checks Cohesion at Disadvantage vs 10 + your Rank Bonus + kills this turn, or routs (GM Guide §5.5).
- **No Counted Arrows** · passive · beyond 12 squares your attacks never break Hidden, and a creature you hit cannot tell which square the shot came from.
- **No Safe Pace** · Battlefield · Action · 5 · Ground · Sustained (upkeep: Quick) · an enemy that moves more than 2 squares in a turn takes a free Strike (at most three a round); a Mob that advances loses RD Cohesion.

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

**Reading — Read the Seam** · free · 0 · exploit: Quick · an object, structure, or armored creature within 6: its load path. Exploit: your next Strike against it crits on 18–20.

**Skills** — hold three Novice, two Adept, two Master, two Guru (§13.3).
**Builds.** *Breacher* — Split the Door, Shield Splitter, Joint Strike, Break the Gate, Where the Weight Is Stored: armor, doors, and bosses read as seams. *Column* — Set, Escort the Rite, Unmoved, Column, Iron Rite: the line that holds anything flat. *Quake* — Drive, Overhead, Ground Slam, Tremor, A Building That Walks: everything near you falls down. *Formation-breaker* — Footing, Bulwark Step, Reverberate, Crack the Line, The Wall Fails: shield walls fail as structures.

*Novice*
- **Set** · Boon · Quick · 1 · until you move: Set, and +2 Guard.
- **Drive** · Control · Action · 1 · Strike; hit: push 2 and you may follow.
- **Split the Door** · Utility · Action · 0 · a barred door, a gap in a shield wall, a barricade: open it (Frame + RB vs the GM's DC; no roll for anything below Hard).
- **Shield Splitter** · Control · Action · 1 · Strike; hit: its shield bonus is lost until repaired, and it is Exposed 1 round.
- **Overhead** · Attack · Action · 1 · Strike at Disadvantage; hit: +2 RD.
- **Footing** · passive · you are never pushed more than 1 square, and unstable footing never knocks you Prone. Canon's Novice: footing kept under weight.
- **Escort the Rite** · Boon · Quick · 1 · an adjacent ally · Warded 1 round, and they cannot be pushed while adjacent to you.

*Adept*
- **Ground Slam** · Damage / Control · Action · 3 · Burst 1 around you vs Guard · 2 RD + Key crush, Prone; half on a miss.
- **Bulwark Step** · Utility · Quick · 2 · move 2 ignoring difficult terrain and through Medium or smaller enemies, who are pushed 1 aside.
- **Joint Strike** · Attack · Action · 2 · Strike + RD against an armored creature or construct; hit: Slowed and Weakened 1 round.
- **Reverberate** · passive · when your *Breach* or *Seam Strike* hits, each creature adjacent to the target takes your Key modifier in crush.
- **Unmoved** · Defense · Reaction · 2 · when you would be pushed, pulled, Grabbed, or knocked Prone · it fails; gain 1 Impact.

*Master*
- **Break the Gate** · Battlefield · Action · 4 · a gate or wall segment within reach opens or collapses (read its load path first for the crit range); creatures behind it in Burst 2 take 3 RD and are Prone.
- **Column** · Boon · Quick · 3 · 3 rounds · allies within 2 gain Set and +1 Guard.
- **Tremor** · Battlefield · Action · 4 · Burst 2 around you vs Guard · 3 RD + Key crush, Prone, half on a miss; the area becomes rubble (difficult terrain) for the scene.
- **Iron Rite** · Boon · Action · 3 · Sustained (upkeep: Quick) · you and allies within 2 resist 3 physical damage from every hit.
- **Load Path** · passive · your *Read the Seam* exploit crits on 17–20; a critical against a structure or construct also drops it to half its current Vigor.

*Guru*
- **Crack the Line** · Battlefield · Action · 5 · Line 6 from you: every enemy in it takes 3 RD, is pushed to one side (your choice each), and is Prone; the Line is a corridor for allies this round — no Punishes inside it.
- **The Wall Fails** · Control · Reaction · 5 · once per encounter · when a Mob charges anyone within 12 it breaks against you instead: it stops, loses 3 RD Cohesion, and you *Shockwave* for free.
- **A Building That Walks** · Battlefield · Action · 5 · Sustained (upkeep: Quick) · as you move, every enemy you pass adjacent to takes 2 RD crush and is Prone (once per creature per round), and walls in your path break as you walk through them. Canon: a collapsing building that walks.
- **Where the Weight Is Stored** · Control · Action · 5 · once per encounter · an Elite or Boss you have Read · Strike; hit: its Guard from armor, shell, or plate is gone for the encounter (Guard −4 if the stat block does not separate it) and it is Prone.

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
- **Guru · The Gate Opens All the Way** · Battlefield · Action · 5 · once per encounter · Gate = 5. Until the end of the round you do not register wounds: you cannot be Downed (track Vigor below 0); every Strike that hits grants another Strike, up to Gate extra Strikes this turn (as *Momentum Kill* chains); you can't be Frightened, Stunned, Rooted, or Dazed. When nothing in reach stands, or the round ends: the bill — Prone, Dazed 1 round, and if your Vigor is 0 or less you are Downed with the clock at 1.

**Reading — Read Fear** · free · 0 · exploit: Quick · which creatures within 6 are Frightened, wavering, or resolved. Exploit: your Strikes against Frightened creatures crit on 19–20 this round.

**Skills** — hold three Novice, two Adept, two Master, two Guru (§13.3).
**Builds.** *Shock trooper* — Over the Barricade, Headlong, Roar, Worth a Breach, Nothing in Reach Stands: first over, into the block. *Butcher* — Blood Up, Rending Blow, Cleave, Wound-Hunger, The Heart Spent: kills fuel kills. *Aimed weapon* — First Over, Gate Discipline, Aimable, Hits That End Exchanges, The Calling-Back: the fury the party points. *Unkillable* — Shrug, Pain Is Later, Reckless, Numbers Do Not Register: stays up and makes them pay for it.

*Novice*
- **Over the Barricade** · Utility · Move · 0 · your Move ignores difficult terrain and may leap 2; if you move 4 or more before a Strike this turn, +RD damage.
- **Shrug** · Defense · Reaction · 1 · reduce one hit's damage by RD + Gate.
- **First Over** · Boon · Quick · 1 · allies within 3 who move toward an enemy this round gain +2 Speed and Resolute 1 round.
- **Headlong** · Attack · Action · 1 · Dash, then Strike; hit: Frightened 1 round.
- **Blood Up** · passive · each time you are hit in melee, your next hit deals +1 damage (the bonus stacks to 3, and is spent on that hit).
- **Haft Hook** · Control · Action · 1 · Strike; hit: pull the target 1 toward you, and it loses its shield bonus until the end of your next turn.
- **Hand-Ax** · Attack · Action · 0 · a thrown hand-ax, range 8, with the Rank Bonus: d6 + Key + Gate.

*Adept*
- **Roar** · Hex · Action · 2 · Burst 3 around you vs Ward · Frightened 1 round; a Mob loses 1 Cohesion.
- **Reckless** · Boon / Hex · Quick · 0 · this turn your Strikes have Advantage; until your next turn attacks against you have Advantage.
- **Rending Blow** · Hex · Action · 2 · Strike + RD; hit: Bleeding 2, or Bleeding 3 at Gate 3 or more.
- **Pain Is Later** · Defense · Quick · 2 · while the Gate is open · Fortified 2 RD.
- **Gate Discipline** · passive · the forced-Strike check at Gate 3+ is Standing DC 10 (not + Gate), and closing a Gate of 3 or less leaves you with no Dazed.

*Master*
- **Cleave** · Damage · Action · 4 · Strike against every adjacent enemy (one roll); each kill raises the Gate by 1, even past its maximum, to 5.
- **Hits That End Exchanges** · passive · Crit Rate ×3 while the Gate is open.
- **Aimable** · passive · an ally within 12 (not 6) may aim you as a Quick; while aimed you ignore the forced-nearest rule and your Strikes deal +1 RD.
- **Worth a Breach** · Battlefield · Action · 4 · Strike a barricade, gate, shield wall, or Mob · a structure takes triple; a Mob loses RD Cohesion and you enter it (GM Guide §5.7). Canon's Master: worth a breach alone.
- **Wound-Hunger** · Heal · passive · while the Gate is open, each creature you drop to 0 restores RD Vigor to you.

*Guru*
- **The Calling-Back** · passive · allies within 6 can call you back as a Quick; called back after *The Gate Opens All the Way*, you are Dazed only, not Prone.
- **Nothing in Reach Stands** · Battlefield · Action · 5 · against a Mob: *Cleave* every adjacent member, move up to your Speed, *Cleave* again; the Mob loses Cohesion equal to twice your kills.
- **Numbers Do Not Register** · passive · while the Gate is open, flanking and Mobs grant no Advantage against you, and each enemy adjacent to you beyond the first adds +1 to your melee damage (at most +4).
- **The Heart Spent** · Battlefield · Action · 5 · once per encounter · move up to your Speed through enemies (no Punishes), and Strike every enemy you pass adjacent to (one roll); the Gate rises 2. Afterward: Dazed 1 round.

**Cost stages.** Post-gate collapse → Frenzy amnesia → Affect blunting → Heart-burn.

---

### 14.11 Artificer — Alchemy, Light Arts (Rationalist)

**Fantasy.** Gadget combat engineer. Novice throws flasks and lays smoke; Adept builds conditional devices and a familiar; Master deploys turrets, constructs, and gadget systems; Guru integrates a household of familiars and equips a company from a wagon.
**Key** Reckoning · **Armor** medium · **Vigor** Alchemy · thrown flasks range 8; simple weapons.

**Signature resource — Loadout.** After a Rest, **prime** Devices from your known list: Novice 2, Adept 3, Master 4, Guru 6 primed. A primed Device is used once at 0 Strain. An unprimed or spent Device costs its listed Strain. Devices marked *(bench)* can only be made at a Rest.

**Core — the Flask line.**
- **Novice · Flask** · Damage / Hex / Control · Action · 0 · thrown, range 8, one square vs Guard · **fire**: 1 RD + Key fire, Burning 1; or **smoke**: Burst 1 concealment 1 round; or **adhesive**: Rooted 1 round.
- **Adept · Conditional Flask** · 2 RD + Key, Burst 1; set a trigger — impact, proximity, or a count of rounds; fire: Burning 2; adhesive: Rooted 2 rounds; smoke: 2 rounds.
- **Master · Gadget System** · deploy one: a **Turret** (Vigor 4 × level, Guard 16 + RB; on each of your turns it Strikes for 2 RD + Key at range 12; lasts until destroyed or the encounter ends), a **Lift** or **Line** (allies cross a gap or a height of up to 6 as a Move), or a **Lock** (a door, gate, or portal sealed: DC 26 to open). **One Gadget System deployed at a time;** deploying another dismantles the first.
- **Guru · Integration** · Battlefield · Action · 5 · Ground · Sustained (upkeep: Quick) · familiars and devices act in concert: every ally on the map has +2 on attack rolls (eyes everywhere); at each upkeep one ally's gear or one construct regains 2 RD; you may deploy a primed Device at any square a familiar can see; an enemy Mob seen by two familiars loses 1 Cohesion per round.

**Reading — Read the Make** · free · 0 · exploit: Quick · an object, construct, trap, or piece of gear within 6: what it does and its flaw. Exploit: your next attack against a construct, gear, or trap crits on 18–20; or bypass a read trap without a check.

**Skills** — hold three Novice, two Adept, two Master, two Guru (§13.3). Your known list for the Loadout is the skills you hold; a passive is not primed. *Familiar* is the prerequisite of three skills below and of *Integration*'s familiar clauses; without it, *Integration* gives the +2 and the regained Vigor only.
**Builds.** *Bomber* — Flash Powder, Tripwire, Proximity Mine, Timed Charge, Walking Arsenal: the field is mined before the fight starts. *Engineer* — Maintenance, Spare Parts, Construct, Arsenal Discipline, Overclock: the turret and the guard do the fighting. *Spymaster* — Grapnel, Familiar, Specialized Familiar, Signal Line, Eyes Everywhere: nothing on the map is unseen. *Quartermaster* — Smoke, Harness, Net Flask, Company Standard, Infrastructure: equips and moves the company.

*Novice*
- **Smoke** · Control · Action · 1 · Burst 1 within 8, 2 rounds · creatures inside are Hidden from those outside and Blinded to them.
- **Adhesive** · Control · Quick · 1 · one target within 8 vs Guard · Rooted 1 round (Large: Slowed instead). A Quick, so it stacks with the *Flask*: root it, then hit it.
- **Maintenance** · Heal · Action · 1 · touch a construct, golem, familiar, or piece of gear: 2 RD Vigor, or restore a broken shield or armor bonus.
- **Tripwire** · Control · Action · 1 · a Line 3 within 8, hidden until sprung · the first creature to cross it is Prone, and you know it crossed.
- **Flash Powder** · Control · Action · 1 · Burst 1 within 8 vs Ward · Blinded 1 round.
- **Grapnel** · Utility · Quick · 1 · a point within 8 · haul yourself there (a climb or a gap, no check), or pull a Medium or smaller creature 2 squares toward you vs Guard.
- **Spare Parts** · passive · prime one more Device after each Rest.

*Adept*
- **Familiar** · Utility · *(bench)* · a small bound construct on a wren, rat, or beetle frame: Vigor 5, Speed 8 (a wren flies 12); carries a light object; you see and hear through it within 24; direct it as a Quick. Adept 1, Master 2, Guru 4. Each familiar reduces your Strain Capacity by 1 while bonded — canon's divided attention.
- **Timed Charge** · Damage · Action · 2 · place within 8; at the start of your next turn: Burst 1, 3 RD + Key, Prone.
- **Proximity Mine** · Damage · Action · 2 · a square within 8, hidden until sprung · the first enemy to move within 1 of it sets it off: Burst 1, 2 RD + Key fire, Burning 1.
- **Harness** · Boon · Quick · 2 · an ally within 8 · spring-rigged boots and straps: Hastened 2 rounds.
- **Net Flask** · Control · Action · 2 · *(bench)* · thrown, range 8, Burst 1 vs Guard · weighted mesh: Grabbed (escape DC 10 + Key + RB); Large creatures Slowed instead.

*Master*
- **Construct** · Summon · Action · 4 · a clockwork guard: Vigor 4 × level, Guard 15 + RB, Strike 2 RD + Key crush, Speed 5; 3 rounds; command as a Quick.
- **Signal Line** · Boon · Quick · 2 · Ground · allies within 24 may act on your Initiative once this encounter, and can communicate at any distance for the scene.
- **Specialized Familiar** · Utility · *(bench)* · requires *Familiar* · one familiar carries a specialized sense: sight in darkness to 24, hearing through a wall, scent of poison or blood, or sight of the Hidden (it finds them without a check); you may direct it up to a mile away.
- **Arsenal Discipline** · passive · your Turret and *Construct* deal +1 RD and have half again their Vigor.
- **Overclock** · Boon · Quick · 3 · a turret, construct, golem, or familiar within 8, yours or an ally's · it takes a second Action this turn; afterward it is Slowed 1 round.

*Guru*
- **Company Standard** · Boon · Action · 5 · Ground · from the wagon: every ally regains 2 RD Vigor and one primed Device of yours; allied Mobs regain RD Cohesion.
- **Infrastructure** · Battlefield · *(bench)* · 5 · a device that alters infrastructure: a bridge dropped on demand, a lift that carries a Mob, a gate that opens for you alone, a signal line across a city ward. A scenario power; the GM adjudicates its reach.
- **Walking Arsenal** · Battlefield · Action · 5 · for the encounter you may keep up to three Gadget Systems deployed at once (Turrets, Lifts, Lines, Locks in any mix).
- **Eyes Everywhere** · Utility · passive · requires *Familiar* · while two or more familiars are deployed, the party cannot be surprised, and no creature within 24 of a familiar is Hidden from you.

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
| Sleep | Adept | Stunned 1 round; a target at half Vigor or less is Slowed 2 rounds after (Stunned never exceeds 1 round, §8.2) |
| Quickening | Adept | *draught* — Hastened 2 rounds, then 1 RD toxin |
| Corroding | Master | armor bonus −2 for the scene |
| Paralytic | Master | Stunned 1 round, then Slowed 2 rounds |
| Clouding | Novice | Blinded 1 round |
| Sweating | Novice | *draught* — resist Fire and Frost 2 rounds |
| Thinning | Adept | Bleeding 2 |
| Rousing | Adept | *draught* — Empowered and Resolute; Weakened 1 round when it ends |
| Maddening | Master | Frightened 2 rounds; on its next turn it attacks the nearest creature, whoever that is (the shake-off applies) |
| Withering | Master | regains no Vigor for 2 rounds |
| Stilling | Guru | Stunned 1 round and Poisoned 2; ignores immunity (the Boss limit applies) |

**Onset** (from Adept): a thrown or coated Dose may be **delayed** one round; a delayed Dose on a target that hasn't noticed it (the GM rules) has its damage and durations doubled.

**Core — the Vial line.**
- **Novice · Vial** · Damage / Hex · Action · 0 · thrown, range 8, vs Ward · 1 RD + Key toxin, Poisoned 1.
- **Adept · Graded Venom** · 2 RD + Key, Poisoned 2; choose the onset.
- **Master · Contact Compound** · 3 RD + Key, Burst 1, Poisoned 2 to all hit; a Master's poison needs skin, not a cup: it ignores immunity below Guru, and a coated weapon delivers it on every hit, not three.
- **Guru · Dose the Ground** · Battlefield · Action · 5 · Burst 4 within 12 · Sustained (upkeep: Quick) · enemies inside are Poisoned 2 at the start of each of their turns (stacking), and Frightened, Slowed, or Dazed (choose at casting); a Mob inside loses RD Cohesion per round; a well, granary, or censer inside is dosed for a phase.

**Reading — Read the Dose** · free · 0 · exploit: Quick · a creature within 6: what it has consumed, its resistances, its tolerance. Exploit: your next Dose against it ignores resistance and applies one extra stack.

**Skills** — hold three Novice, two Adept, two Master, two Guru (§13.3). *Golem* is the prerequisite of two skills below.
**Builds.** *Poisoner* — Needle, Venom Ladder, Hidden Dose, Tailored Poison, Contagion: the Ward snowball, all the way down. *Brewer* — Preservation Draught, Deep Kit, Push Draught, Bitter Reserve, Pharmacopoeia Entire: the party's bottles. *Golemancer* — Handle It, Golem, Vat-Grown Brute, Standing Orders, Golem Team: strong, stupid, and obedient. *Crowd-steerer* — Know the Taste, Choking Cloud, Contagion, Censer: no one in the square wants to be there.

*Novice*
- **Purgative** · Heal · Action · 1 · touch · remove Poisoned and Blinded; 1 RD Vigor.
- **Preservation Draught** · Boon · Quick · 1 · an ally within 6 · Fortified RD, 3 rounds.
- **Handle It** · passive · immune to Novice-grade poisons; Advantage on Ward against toxin.
- **Needle** · Hex · Quick · 1 · an adjacent creature vs Ward · Poisoned 1.
- **Know the Taste** · Utility · Action · 0 · a drop on the tongue · what a substance is, its grade, and roughly where it was made.
- **Smelling Salts** · Heal · Quick · 1 · an adjacent ally · remove Dazed and Frightened; a Downed ally is stabilized.
- **Deep Kit** · passive · compound one more Dose after each Rest.

*Adept*
- **Push Draught** · Boon · Quick · 2 · an ally within 6 · Hastened and Bolstered 3 rounds; when it ends, 2 RD toxin — the bill presented later.
- **Golem** · Summon · *(bench)* · a clay-bound golem: Vigor 3 × level, Guard 14 + RB, Strike 2 RD + Key crush, Speed 4; obeys one-word orders (Quick); unordered, it attacks the nearest creature. Lasts the scene. One at a time until Master.
- **Venom Ladder** · passive · a Dose or *Vial* that poisons a creature already Poisoned adds one extra stack.
- **Choking Cloud** · Control · Action · 3 · Burst 2 within 8 vs Ward · Poisoned 1 and Dazed 1 round; the cloud stays 1 round (entering it: Poisoned 1).
- **Hidden Dose** · Hex · Action · 2 · a creature within 8 that is eating, drinking, or breathing unawares (the GM rules) · your next Dose against it this encounter takes the Onset doubling without the notice check.

*Master*
- **Tailored Poison** · Hex · Action · 4 · a named recipient within 8 whom you have Read or studied: the Ward roll is made at Disadvantage for them; Poisoned 4 and Weakened 3 rounds; ignores immunity below Guru.
- **Standing Orders** · Boon · Quick · 3 · requires *Golem* · your golem holds an order for the scene (guard this, hold that, carry them).
- **Contagion** · Hex · Action · 4 · a Poisoned creature within 8 · its Poisoned stacks spread: each creature within 2 of it, vs Ward, gains the same number of stacks.
- **Vat-Grown Brute** · Summon · *(bench)* · requires *Golem* · your golem is Large, Vigor 5 × level, Strike 3 RD + Key crush, and its hits push 1.
- **Bitter Reserve** · Heal · Quick · 3 · self · a draught you built for yourself: remove every hex, regain 2 RD Vigor, Warded 2 rounds.

*Guru*
- **The Antidote No One Can Check** · Heal · Action · 5 · touch · cure any poison, hex, or Dose, Guru-grade included; or lay a **hold** — a dose only you can undo: the target takes 1 RD toxin at the start of each of its turns until you release it (Ward at casting negates).
- **Golem Team** · Summon · *(bench)* · 5 · up to four golems under standing orders, acting as a Mob with Cohesion 3 × RD.
- **Censer** · Battlefield · Action · 5 · Ground · Sustained (upkeep: Quick) · the air of the field is yours: choose at casting — enemies are Frightened of a point you name; or they attack no one who has not attacked them this round; or they are Slowed. A Mob loses RD Cohesion per round; allies who took your draught at the last Breather are immune. Canon: dosing that steers crowds.
- **Pharmacopoeia Entire** · passive · a Dose may combine three Properties, and *Improvise* costs 1 Strain.

**Cost stages.** Tolerance dosing → Organ staining → Taste-death → The venomous body.

---

## 15. Gear and relics

Gear is what you wear; a relic is what a socket in that gear seats. The GM Guide (§7) has the maker tiers, prices, the full attribute catalogue, the governors, and ten sample relics; this is the player's side of it. (v0.2: this replaces v0.1's six-slot interface; the GM Guide's eight-slot model, D11, is the one both files now use.)

### 15.1 Gear

**Eight slots:** Head · Chest (your armor, light / medium / heavy, §4) · Legs · Gloves (wraps for a Necromancer, who works bare-palmed) · Boots · Accessory ×2 (ring, amulet, belt, bracer, sash, a token on a cord) · Trinket (a tooth, a charm, a page). A piece is graded by its maker's rank — Novice, Adept, Master, Guru — readable by the Artificer's *Read the Make*; Guru-grade gear is always a named piece with a record. Each slot carries a fixed **intrinsic** by tier (no choices to make) and **one socket**.

| Slot | Adept | Master | Guru (named) |
|:--|:--|:--|:--|
| Head | Ward +1 | Ward +1, Guard +1 | Ward +2, Guard +1 |
| Chest | Guard +1 (above the armor value) | Guard +1 | Guard +2; Resist one damage kind other than Physical, chosen at making |
| Legs | Vigor +5 | Vigor +10 | Vigor +20 |
| Gloves / wraps | Damage +1 on Strike and Core | Attack +1; damage +1 on Strike and Core | Attack +1; damage +2 on Strike and Core |
| Boots | +2 on checks against hazards | Speed +1 | Speed +1; difficult ground costs no extra Move |
| Accessory (each) | Strain Capacity +1 | Strain Capacity +1 | Strain Capacity +1 |
| Trinket | — | — | — (its socket seats a relic of any rank) |

Novice-grade gear is the starting kit: no intrinsic, no socket. Intrinsics stack across slots, never within one. The gloves' damage bonus is on your Strike and your Core, not on a costed ability. **A full kit adds up to:** Adept — Ward +1, Guard +1, Vigor +5, damage +1, Capacity +2; Master — Ward +1, Guard +2, Vigor +10, attack +1, damage +1, Speed +1, Capacity +2; Guru — Ward +2, Guard +3, Vigor +20, attack +1, damage +2, Speed +1, Capacity +2, one resistance, and difficult ground free. The GM's opposition tables assume you are in the kit of one tier below your own — nothing at Novice and Adept, the Adept kit at Master, the Master kit at Guru — and a party in its own tier's full kit, or carrying four or more seated relics, is run one budget step harder (GM Guide §4.6, §7.3, §12.3 i). The Guru chest's resistance is a commitment made when the piece is commissioned: it is never Physical, so it is chosen against a named threat and does nothing against the next one. **Weapons and shields** keep their §4 values and carry no tier and no socket in this draft (GM Guide G11).

### 15.2 Relics

A relic is beast residue with a shape: a tooth, a den-stone, a bead of reef-glass, a shard of lake ice that does not melt. It comes only from a properly resolved Grand Beast emergence (the outcome line, GM Guide §6.6) — never from a shop, never made, never copied. Its **rank** is the tier of the emergence that left it.

- **Attribute.** Every relic carries one numeric or mechanical property at the magnitude of its rank — damage, attack, Guard, Ward, Vigor, Strain Capacity, Speed, healing dealt, a DoT on hit, a resistance, a crit step, a Reading line, Cohesion damage, a summon bonus, a hex resistance, casting speed, and at Guru a once-per-encounter extra Action (the catalogue is GM Guide §7.5). A Novice relic is a small permanent bonus (+1 damage); a Guru relic is a named piece of a Guru's book.
- **Alteration** (Master and Guru relics only). One new action or one changed class mechanic, written in ability format on the relic's entry — "*Sink*: once per Breather, as an Action, move 6 through sand and surface adjacent to a target." A Guru alteration is a piece of the Guru ability of the relic's moon: a practitioner of that school uses it at the entry's cost; anyone else uses it only as a Push (§9.3, *Use*).
- **Governor.** The condition under which it works, inherited from the beast that left it: **Rigidity** (Novice — one fixed condition: on a turn you did not Move; against a target that Moved this round), **Dependency** (Adept — feed it a Breather a day in contact with what it needs, or it goes dormant), **Inversion** (Master — in the beast's inverted condition the attribute becomes a penalty of the same size for the scene), **Tether** (Guru — it works within the emergence's domain, or for seven days after a Breather taken there, or in the hands of its bonded holder).
- **Seating.** A socket seats one relic of rank equal to or below the piece's tier; seating or unseating takes a Breather. The Trinket seats any rank, and an over-rank relic there costs **1 Strain Capacity while seated** — the only bond cost in the game (D4). **At most eight seated, and the same attribute in at most one socket.**
- **Reading it.** The school of the relic's moon reads it fully in one Reading; any other school reads the attribute and its magnitude; a martial or alchemy Reading gives one word. The Ledger's assessors identify one for a fee — and file it, and whoever brought it.

---

## 16. The character sheet

Standardized. Every field is on it; nothing else is. v0.6 renumbers the ability lines as picks (§13.3) and adds the sub-discipline and retraining lines. v0.4 adds the Identity, Standing, Tongues, Coin and kind, and Debts blocks (§1.4; module CF-rows) and keeps every v0.3 block. Fields above the attribute line describe the character; none of them changes a number below it.

```
TERHIA: HEROES — CHARACTER SHEET
────────────────────────────────────────────────────────────────
IDENTITY
  Full name (in your culture's form) ____________________________________________  Player __________
  Called ______________________   Registry name (what the Ledger or Assay files) ____________________
  Introduction (formal, in your own words) ______________________________________________________
  Culture ___________  Homeland ___________  Born at ___________  Household ___________________
  Born ___ __________ ____ (day · phase · year)    Age _____ (years / winters / cohort ______ / birth-moon ______)
  Trained at _______________   Look (cloth · palette · mount) ___________________________________
  God (Crown homelands only, optional) _______________

CLASS
  Class ________ School ________ Ethos ________ Moon ________  Level __  Rank ________
  Rank Bonus +__   Rank Die d__   Tempo __   Crit Chance __–20   Crit Rate ×__

STANDING (the part the registries can see)
  Charter of record ______________   Registry status ______________ (grade ____)   on this ground: ______________
  Faction ______________________  relation: Member / Contractor / Marked   its register: ______________
  Ledger file ○○○○○   Chancel favor ○○○○○   Circle recognition ○○○○○   Off-Ledger credit ○○○○○   (0–5)
  Cost file exists [ ] (from Adept)   examiner / sacrist / keeper of record ______________   phase ________

TONGUES (Full · Market · None)
  Own ______________ Full  (registers ______________)   Common Tongue ________   Others ______________
  The word you hold ____________________________________________________
  The laws you carry  1 ______________  2 ______________  3 ______________

ATTRIBUTES (score / modifier)            DEFENSES
  Frame      __ / __                       Guard   __  = 10 + Poise + armor __ + shield __ + RB (+1 martial)
  Poise      __ / __                       Ward    __  = 10 + Reserve + RB (+1 magic)
  Reserve    __ / __                       Speed   __  Initiative +__
  Reckoning  __ / __
  Attunement __ / __                     VIGOR   current ____ / maximum ____   Fortified ____
  Standing   __ / __                     STRAIN  current ____ / capacity ____ (moon +2 / −1)   Second Wind [ ]

THE LEDGER (the part other people cannot see — keep it honest)
  Marks  ○○○ | ○○○ | ○○ | ○○   (3 · 6 · 8 · 10)      Stage __  ________________
  Cost stages (school): 1 ______________ 2 ______________ 3 ______________ End ______________
  The End, written once at creation: ________________________________________________

SIGNATURE RESOURCE  ____________   current __ / max __   (how it builds: ________________)

CORE  (current form) ______________________________________________________________
READING  ____________________  exploit: ____________________________________________

ABILITIES (name · type · action · Strain · range/area · effect)
  (nine picks; a pick may hold an earlier rank's ability — mark it ↓)
  Novice 1 ______________________________________________________________________
  Novice 2 ______________________________________________________________________
  Novice 3 ______________________________________________________________________
  Adept 1  ______________________________________________________________________
  Adept 2  ______________________________________________________________________
  Master 1 ______________________________________________________________________
  Master 2 ______________________________________________________________________
  Guru 1   ______________________________________________________________________
  Guru 2   ______________________________________________________________________
  Sub-discipline (Elementalist) ________   Retrained at rank-up: 5 ______ 9 ______ 13 ______
TALENTS  L2 __________  L6 __________  L10 __________  L14 __________
JOINS held (with whom) __________________________________________________________

CONDITIONS NOW   boons: ________________________   hexes: ________________________
                 Burning __  Bleeding __  Poisoned __   Death Clock  ○○○

KIT
  Weapon _____________ (die d__, reach/range __)    Armor _____________ (+__)   Shield (+__)
  Head ______  Chest ______  Legs ______  Gloves ______  Boots ______  Accessory ______  Accessory ______  Trinket ______
  Relics (slot · rank · attribute · governor) ___________________________________
  Companion / familiar / golem: name ______ Vigor __/__ Guard __ attack +__ damage ____ Speed __
  Doses / primed Devices / Adaptations active: ___________________________________
  Trades and crafts ____________________________

COIN AND KIND
  Seals ____s ____e    Gilts ____g    (the rate at this desk: 1g = ________)
  Kind (cattle · a boat's place · well credit in days · a toll-right · water shares · grain) _________________

DEBTS   owed ______________________________________   held ______________________________________
        (winters · well-days · a duty · roofs · a way · a name · a Mark · sealed coin, with its phase)

NOTES  contracts held · who knows what you are · what your charter cannot see about you
────────────────────────────────────────────────────────────────
```

**Filling the top of the sheet.** Identity is §1.4's thirteen steps in order. *Registry name* is what a clerk would write and is usually not your name: a Menneske's settlement and moot of record; a Renlei's seal and grade; an Unsaan garden-name filed as a family name; a Yamana name and file; an Umutu name and a number the Umutu do not recognize; for a Tangata, often nothing. *On this ground* is the registry status read against the territory the party is in now — a Registered Adept Warden is *Proscribed* the day the party crosses into Teocalli. *Its register* is the contract form your faction uses (GM Guide §8.2). *The word you hold* and *the laws you carry* are copied from the culture entry; they are the two things the table checks when a scene crosses cultures.

---

## 17. Design register — for ratification

Every rule that touches a canon sentence, with the reading taken. Nothing here is canon until Joe rules; Canon itself is untouched. Rows marked *ruled* carry the ruling's number from Terhia-Heroes-Rulings.md (v0.3); rows H42–H50 are new in v0.3; **rows H51–H59 are new in v0.4** and H60 in v0.5; **H61–H72 are new in v0.6;** H51–H59 point at the Cultures-and-Factions module's CF-rows, which hold the full readings. Numbering is Heroes-local (H-rows) so the register never collides with Chronicle's.

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
| H15 | Four elements including Stone; *Harbor Kept* costs Strain Capacity −1 per phase held and 1 Mark per year held | Part II, Elemental Novice (fires, water, gusts); Guru (sustained works keep drawing cost); Part V, the Escrow lease and its waivers | Earth admitted as the fourth element (brainstorm); v0.3: the rate set to the harbor economy — 1 Mark a day was the End in a week for a Guru leased by the year | amended (R4) |
| H16 | Martial Strike scaling: 1 attack → +RD → 2 attacks → 2 attacks +2 RD; Guru martial abilities calibrated against a Mob | Part III: "a Guru can fight platoons" | GMG §12 (v0.2): a Guru Strike is 47 an Action, and a Guru martial is ~70% ahead of a Guru caster single-target and level at two targets; a Guru martial alone routs a Master-drill platoon in two rounds. GMG G34 offers the trim (weapon + RD + Key at Guru) if Joe wants the Master gap instead. v0.3: see H42 | ruled (R1) |
| H17 | Mobs and Cohesion referenced, defined in GM Guide | Chronicle GMG Lines / Cohesion | Reuse the Chronicle model on a grid | open |
| H18 | Grid: 1 square = 1 pace; Speed 6; diagonals 1; sizes M/L/H/Grand | Chronicle PM §4 (6 paces per Move) | Direct to squares | open |
| H19 | Area attacks: one roll compared to each target; half damage on a miss; **v0.2: Elites and Bosses take nothing on a miss** | — | Speed at the table; the exemption keeps an area at ~70% of a single-target attack per target against a Boss (GMG §12.3 b) | open |
| H20 | Readings as Read → Exploit; private hand-outs dropped | Design Thesis; Part I, Three Readings | The thesis survives in what each Reading cannot see and in Joins; it no longer governs table procedure. Flag as a deliberate weakening. v0.3: the sentence is free and the exploit priced (H46); the *private* question is Issue 9 of the ledger | amended (R5) |
| H21 | Joins: Action + Reaction, 2 Strain each, +2 to hit; ten listed | Chronicle PM §8 (two hard checks) | Combination attacks; improvised Joins in GM Guide | open |
| H22 | Dagger is not a school; the Warden's dagger removes adjacent Disadvantage | Part III preamble; XI.6 | Direct | open |
| H23 | Necromancer: wraps in the Gloves slot (bare palms), no shield | Part II, Necrotic physical practice (bare-handed) | Direct; v0.2 aligns with GMG §7.1 (wraps carry the slot's intrinsic) | open |
| H24 | Artificer familiar: −1 Strain Capacity each while bonded | Part IV, Light Arts cost (divided attention) | Direct | open |
| H25 | Warlock Doses cost no Strain; improvising costs 2 | Part IV, Dark Arts | The bench is the practice; the field is the exception | open |
| H26 | Berserker Gate maxima 2/3/4/5; the calling-back by an adjacent ally; post-gate Dazed | Part III, Ax (the gate; companions train for the calling-back; post-gate collapse) | Direct | open |
| H27 | Talents (ten) | — | Invention; all are table-mechanical, none touches the world | open |
| H28 | Healing: Breather restores a quarter of maximum Vigor (three per day); full Rest restores all | Chronicle GMG §6 ("nothing heals for free") | Not adopted in Heroes; rest heals. Flag | open |
| H29 | Death permanent; *Refuse Death* (Mark) and *Threshold* (delay) are the only exceptions | Part II, Divine and Necrotic Guru | Direct; v0.3 makes *Threshold*'s delay true mechanically (H48) | confirmed (R7) |
| H30 | Crit Chance / Crit Rate defined; a crit adds one hex stack; maximum Crit Chance 17–20 | — | Invention | open |
| H31 | Hexblade *Counter-Practitioner* cancels an ability mid-cast | Part III, Sword/Shield Master (closes the distance inside a chant) | Direct | open |
| H32 | Paladin *Demolition* and Sorcerer *Shatter Point* destroy structures with listed values | Part III Hammer Guru; Part II Arcane Master | Structure Vigor table in GM Guide | open |
| H33 | Moon phase: Magic classes' Strain Capacity +2 in the school's own phase, −1 in the two far phases (§9.1; GMG D1, reading (a)) | Part I, Moons (casting cost lowest in the school's own phase); 11 Sep 2026 decision (cost varies by phase only) | v0.2: adopted from the GMG; one lever, nothing else varies by phase | ratified (R8) |
| H34 | Tempo: Actions per turn 1 / 2 / 3 at levels 1 / 6 / 12; no costed ability twice a turn; one Ready a turn; summons act on the summoner's turn with one Move and one Action; "Strike" inside an ability is one attack (§5, §13.1) | — | GMG G1 and PG revisions 1–3 applied. Alternative kept from G1: Tempo at rank boundaries (9, 13). The one-attack reading of "Strike" is what the GMG's damage model already assumed; without it a Master Core form saying "two Strikes" read as four attacks an Action. v0.3: Tempo 2 at level 9 and 3 at level 13 (H44) | ruled (R2) |
| H35 | Gear: eight slots, maker tiers, fixed intrinsics, one socket each; relics with a ranked attribute, a Master+ alteration, and a governor; no bond cost except an over-rank Trinket relic (−1 Capacity); the same attribute in at most one socket (§15) | Part VIII (relics are beast residue, not made); Part II (Necrotic works bare-palmed) | GMG §7 (D4, D11) applied; replaces v0.1's six-slot, no-flat-bonus interface. The one-socket-per-attribute cap is new in v0.2: a per-hit damage relic multiplies with the Master Strike's two attacks and with Tempo (GMG §12.3) | open |
| H36 | Elites and Bosses: hex stack cap 4 / 3; a Boss Stunned once per phase; one shake-off a turn (d20 + Ward − 10 vs the applier's attack roll) against any hex that denies a Move, Action, or Reaction or dictates a target; a Boss also checks on entering a Ground-scale hex (§7.4, §8.2) | — | GMG G4, G29 and revision 7, generalized: one rule in place of per-hex patches. In v0.1 *Bound*, *Telekinetic Grip*, and *Lockdown* had no Boss escape at all. v0.3: a Stunned Boss loses its turn, as this file's Stunned says; the GMG's contrary sentence is struck (R7) | amended (R7) |
| H37 | Each Join once per encounter; "Strike" in a Join is one weapon attack (§12) | Chronicle PM §8 | At Adept+ a 4-Strain auto-critical (*Hammerfall*, *Last Witness*) was the correct opener every turn; once a fight keeps a Join the remembered move | open |
| H38 | A Core keeps every form it has had; the Guru form costs its listed Strain, the exception to the 0-Strain rule (§14) | — | Every Guru Core form in v0.1 cost 4–5 Strain against a rule that Cores cost 0; without this line a Guru had no 0-Strain turn | open |
| H39 | Artificer: one Gadget System deployed at a time; *Adhesive* is a Quick (§14.11) | Part IV, Light Arts | A 0-Strain turret per Action out-damaged the 4-Strain *Construct*; *Adhesive* as an Action duplicated the adhesive *Flask* at a Strain | open |
| H40 | Warlock *Sleep*: Stunned 1 round, then Slowed 2 rounds on a target at half Vigor (§14.12) | — | v0.1's "Stunned 2 rounds" broke the 1-round Stun cap | open |
| H41 | Berserker *The Gate Opens All the Way*: the hit-chain is capped at Gate extra Strikes a turn (§14.10) | Part III, Ax | Consistency with *Momentum Kill*; unbounded at Tempo 3 the once-per-fight burst was ~450 expected against a Guru Boss's 800 (GMG §12.4) | open |
| H42 | Guru Strike: two attacks at weapon + RD + Key; the second RD applies against a Mob's Cohesion only (§5) | Part III: "the ceiling is lower (a platoon, not a harbor)"; "the curves cross at Master"; the Guru lines locate the platoon standard in the Guru technique | R1: a Guru martial is +23% over a Guru caster single-target, matching Master; 47 an Action against Cohesion, where the platoon standard lives | ruled (R1) |
| H43 | *Unanswerable*: the upkeep's three Strikes are the turn's Strikes; one target or several; members or the block (§14.8) | Part III, Longbow Guru | R1: with permanent Hidden the Guru form was ~148 a turn on a lone Boss, uncounted in GMG §12; now ~46 at Advantage, or ~70 to Cohesion — the form trades output for being unfindable | ruled (R1) |
| H44 | Tempo 1 / 2 / 3 at levels 1–8 / 9–12 / 13–16 (§4, §5, §13.1) | §1.2 "rank is the large power jump"; Part III | R2: every Tempo step at a rank boundary; the GMG's tier table loses its correction lines. The brief's "a high-level Master casts three" is given up; 9 / 12 is a three-line delta if it returns | ruled (R2) |
| H45 | Push *Use*: a Guru relic's alteration of another school is usable only as a Push, 1 Mark, once per round (§9.3, §15.2) | Premise (one school per person); Design Thesis | R3: the relic draws the school's cost from a body not trained to pay it; own-school use at the entry's cost; a second-school Reading attribute returns one word | ruled (R3) |
| H46 | Readings free, once per round; the exploit costs the Quick, or an Action when the Quick is spent, as may a summon's command or a draught (§5, §11) | Design Thesis; Part I, Three Readings | R5: the GMG's tables are free information; the riders stay priced; the Quick is the upkeep slot at Master and Guru, and the Action fallback is what a sustaining character uses | ruled (R5) |
| H47 | *Time Debt* is not a hex and not a Stun: a Boss loses its next turn with no shake-off and no Interrupt refresh, once per encounter (§14.2) | R.0 Sorcerer rule (D9) | R7: the one lockdown a Boss cannot shake, bounded by once per encounter | ruled (R7) |
| H48 | *Threshold* on a dead ally is a delay: death resumes when the hold ends whatever its Vigor; a Downed ally returns to Downed at its clock unless healed (§14.4) | Part II, Necrotic Guru: "Not resurrection; a delay measured in breaths" | R7: as written, any heal in the window was a return cheaper than *Refuse Death* | ruled (R7) |
| H49 | *The First Ten Deaths*: the Mob checks at Disadvantage vs 10 + RB + kills (§14.8). *Fold the Line*: RD Cohesion per upkeep and the drill's attack cap in place of the Dazed rider (§14.6) | Part III, Longbow and Sword/Shield Guru | R6 for *First Ten Deaths* (DC 21 for a Guru, an 84% rout from full; under the old DC every forced check was automatic). *Fold the Line* is a working reading: Dazed does nothing to a block | First Ten Deaths ruled (R6); Fold the Line open |
| H50 | A Mob's squares are enemies' squares; entry by ability only (§6.1; GMG §5.7) | — | R6 | ruled (R6) |
| H51 | Identity fields on the sheet — culture, homeland, birth settlement, household, birth date and age marker, four name fields, tongues, charter, registry status, faction, four tracks, god, look — modify no attribute, defense, Vigor, Strain, damage, or attack; restrict or grant no class or school (§1.4, §16) | XI.6 (no school assigned to any culture as an essence); Part V, Naming and Address; Common Tongue Distribution | Module CF1, CF15, CF16, CF17. Identity works through Advantage on checks, procedural rights, and what is filed or owed | open |
| H52 | Charter of record defaults to the homeland's institution; the ethos × charter table sets registry status and the starting track step; *Proscribed* and *Anathema* as flags; status read against the territory (§1.4) | Part VI, Faction table and vacant cells; Part VII, Doctrinal Status; Part IX (Purge, Edict); GMG §8.4, §9.1 | Module CF2, CF3, CF19, CF23. Starting steps are the game's figures | open |
| H53 | The laws you carry: Advantage on checks that turn on your culture's three laws, on your ground or with your people; checks only, never an attack (§1.4) | Part V, each profile's Governance and law | Module CF4. Invention on canon law; alternative: procedural rights only, no Advantage | open |
| H54 | The Common Tongue at Full / Market / None by registration and household; the lexical gap — Disadvantage on the point unless the listener holds the speaker's tongue at Full or an interpreter with both is present, whose presence is a standing fact (§1.4) | Part V, The Common Tongue; Common Tongue Distribution | Module CF5, CF6. The Design Thesis applied to speech | open |
| H55 | The Trade talent taken for a tongue raises it one level (None → Market → Full); at Full it adds the Rank Bonus as written; §13.2's text unchanged (§1.4) | H27 | Module CF7. A use of an existing talent, not a new one | open |
| H56 | Faction affiliation: one Member (its register is yours; its track starts at 1), Contractors as contracts run, Marked by consequence; the GMG's four reputation tracks carried on the sheet (§1.4, §16) | Part VI, Faction ("ethos = belief, institution = charter"); GMG §8.4 (G19) | Module CF9, CF10, CF11. **Naming flag (CF11):** the GMG's Chimera column is headed "Sedge Circles"; the sheet says *Circle recognition* | open |
| H57 | Coin notation — seals and eighths, gilts, never totaled; the desk's rate; starting coin by household standing 12 / 4 / 1 / 1 seals (10 / 3 gilts); the debts block, never converted (§1.4, §16) | Part V, Money; Kind and Labor; Anchor Prices; Canon Discipline 5 | Module CF12, CF13, CF14. Prices are the game's figures (the G17 precedent); an episode's figure governs | open |
| H58 | The character sheet expanded: Identity, Standing, Tongues, Coin and kind, and Debts blocks; every v0.3 block kept; the KIT line's "Coin and kind · Tongues and trades" moved to the new blocks, leaving "Trades and crafts" (§16) | — | "Every field is on it; nothing else is" still holds | open |
| H59 | God line for the four Crown homelands, optional, the player's; no rule assigns a god; Renlei and Tangata have none (§1.4, §16) | Part VII scope ("nothing in this Part assigns a god to any character"); Part VI, D3 scope note | Module CF17 | open |
| H60 | Gear (§15.1): the gloves' damage bonus on Strike and Core at every tier; the Guru chest's resistance never Physical; the assumed kit (one tier below) and the budget step stated for the player; the kit totals listed | — (a GMG calibration matter, G51) | The kit is not what moves hit rates; the budget step is the tool (GMG §12.3 i). v0.4's Master and Guru gloves lines did not give the damage bonus a scope; the GMG's model always read it as Strike and Core | open |
| H61 | Ability pools: each class holds nine picks (3 / 2 / 2 / 2 by rank) from pools of 20–28; down-picks from an earlier rank allowed; one exchange at each rank-up; *requires* tags (§13.1, §13.3, §14) | Part II–IV rank lines (each new ability sits on its rank's canon line) | Joe's brief: more options, same maximum. The pick count, Tempo, and Strain schedules the GMG calibrated are untouched; what the GMG has not checked is every new entry (GMG G53) | open |
| H62 | Down-picks and retraining | — | Invention. Alternative: no down-picks (tighter rank identity) and no retraining (choices permanent, as in Chronicle) | open |
| H63 | Elementalist element-bound spells, one to two per element at each rank; the sub-discipline at level 9 binds element-bound Master and Guru spells to one element (§14.1) | Part II, Elemental: Novice fires, water, gusts; Adept "learns which element responds"; Master "sub-discipline specialization becomes pronounced" | The sub-discipline is the canon Master line made a rule; it is what keeps four Elementalists from holding one list. Alternative: tags without the sub-discipline (element spells free at every rank) | open |
| H64 | Sorcerer *Echo Gate* (Guru): a field gate pair, Sustained | Part I, Transport (Echo Portals are Arcane, stations Guru-presided); Part II, Arcane Guru (time and gravity the only writable variables); R.0 Sorcerer rule | Invention: canon does not say how a portal works, and the Guru's edit is limited to time and gravity. Taken on the standing rule (err on power). Alternative: strike it, or keep it station-only as a scenario power with no combat use | open |
| H65 | Sorcerer *Quickened Hour* (Guru): the fast volume; allies inside take one extra Action for Strike, Core, or Dash only | Part II, Arcane Guru (a region runs slow or fast; exterior placement) | The canon's other half of time dilation, which v0.5 used only as *Slow Field*. Bends §5's Tempo (an Action outside the table); bounded to 0-Strain actions so Strain still governs. GMG check (h) | open |
| H66 | Necromancer additions stay on the boundary: sensing, residue, fear, the dying's last words; *Short Crossing* ends standard enemies at a quarter Vigor; *Finish the Sentence* is canon's Guru line | Part VI Terminology ("does not raise, animate, or command the dead"); Part II, Necrotic Guru | Preserved; no ability touches a body except to read it | open |
| H67 | Apostle *Unmake the Will* and *The Order Given* (Guru, once per encounter); *Judgment*'s Stun on a Sanctioned target | Part II, Divine Adept–Master (voice with physical weight; boon application) | Inventions at Guru scale. *Unmake the Will* on a Boss is a lost Action, not a Stun, and not a hex; *The Order Given* gives the party an out-of-turn Move and attack — GMG check (f) | open |
| H68 | Martial additions each read off a canon rank line (Hexblade *Retire the Options*, *Turn Numbers into a Queue*; Vanguard *Circle Nobody Enters*, *Doctrine*; Warden *Where It Will Be*, *No Counted Arrows*, *No Safe Pace*, *Impassable*; Paladin *Footing*, *A Building That Walks*; Berserker *Aimable*, *Worth a Breach*) | Part III, each school's rank lines | Direct where the name is canon's phrase | open |
| H69 | Artificer and Warlock additions: *Specialized Familiar* (Master), *Walking Arsenal* (Guru; lifts the one-System cap for an encounter), *Overclock* (a summon's second Action); Warlock *Censer*, *Pharmacopoeia Entire*, seven new Properties including Guru *Stilling* | Part IV, Light and Dark Arts rank lines | *Walking Arsenal* and *Overclock* bend H39 and §5's one-summon-Action rule on purpose, each bounded (an encounter; one Action and a Slowed); GMG check (m) | open |
| H70 | Apothecarist: three new somas (Boar, Gecko, Owl) on the Adaptation list; *Herd Soma* (Guru) lends somas party-wide | Part II, Nature Guru (morphic borrowing is the peak technique) | Rides on H10: the somas are still available from Adept, which is the flag already open there | open |
| H71 | Novice Elementalist *Minor Works*: canon's Novice line as a 0-Strain utility with no combat effect | Part II, Elemental Novice | Direct | open |
| H72 | The character sheet's ability block renumbered as picks; sub-discipline and retraining lines added (§16) | — | "Every field is on it; nothing else is" still holds | open |
