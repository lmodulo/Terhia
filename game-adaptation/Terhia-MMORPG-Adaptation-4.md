# Terhia — MMORPG Adaptation Brainstorm

> Drafted 23 September 2026 from Terhia-Canon.md v1.1 (revision of 12 September 2026). Register: craft/adaptation, not canon. Nothing in this file is ratified; section 9 lists the items that touch canon and need a ruling. Figures marked "placeholder" are tuning starting points, not records.
>
> **Version.** v0.1.1, 23 September 2026: editorial-feedback pass, listed in the Changelog after section 9. In sections 1–8, mechanics and canon citations added or changed in this pass carry tags, and untagged ones are unchanged from v0.1. In section 9, the Canon position column is the citation, and [N] marks a pending source. [C]: derived from ratified canon, section cited. [N]: rests on pending canon, R.1 item or block cited. [A]: adaptation-only mechanic that asserts nothing about the world. [R]: implies a world fact or conflicts with a ratified line; listed in section 9. From v0.2: a canon [V] section counts as [C] when every source it cites is ratified. [C] on an Emotional Payload paragraph, Part X, or XI.5 cites ratified craft-register text, and [C] on Part VII's Doctrine cites in-world text; under the canon's register rule neither is evidence of a world fact, so each supports an adaptation choice only.
>
> **Brief.** Adapt the Terhia canon as an MMORPG with visual quality on the level of Black Desert Online (BDO). Map the twelve classes onto genre archetypes. Adapt skills and abilities for fun gameplay built on deep combat systems.
>
> **Version.** v0.2-draft, 23 September 2026: defect pass from the handoff, run without Terhia-Canon.md in session. Canon facts used in this pass come from the findings recorded in the handoff; no canon line was re-read. Elements changed in v0.1.1 or v0.2-draft carry tags. Full tagging of every kit and system element, the quote audit, and the dependency-status check are owed to a canon pass (Changelog, v0.2-draft, Canon checks owed). The version reads v0.2 when those close.
>
> **Version.** v0.2, 23 September 2026: canon pass against Terhia-Canon.md v1.1. The six canon checks owed by v0.2-draft are closed (Changelog, v0.2). Canon errors found in the text are corrected in place and listed there; decisions stay with Joe, and every default holds.
>
> **Canon read for this pass.** v0.1.1: Parts I–XI except XI.2, plus R.5 and R.8; not read: R.0–R.4 and Appendix H. v0.2-draft: none. v0.2: in full, Part I, Parts II–IV, Part VI, Part VIII, Part X, XI.5, XI.6, R.0, R.1, R.5, R.8; by section, Part V (Economic Baseline, Money, Population, Anchor Prices, Phase Cascade, Material Signatures, and the law and ritual paragraphs of all six culture profiles), Part VII (front matter, Doctrine, status table), Part IX (1145, 1155, Purge Years, Antler War, Baishui, Node Decade, The Present, Appendices C and D); by search only, XI.2 and XI.3; not read: XI.1, XI.4, Appendix H.
>
> **Session load for follow-up work.** This file, about 26k tokens (measured at v0.2), plus Parts II–IV (schools, ranks, costs) and Part X (visual grammar), about 8.8k: about 35k tokens, against about 61k for the full canon.

## Contents

1. What the canon supplies, and where it resists
2. Classes and archetypes
3. Combat architecture
4. Class kits
5. PvE: the Ecological Engine as encounter framework
6. Factions, law, and economy
7. Rank progression and Guru scarcity
8. Art direction
9. Adaptation register

Changelog follows section 9.

## Summary

The canon already contains most of an MMO's system spine: one rank ladder shared by every school, twelve per-school cost curves, a calendar that can run as a weekly world-state clock, a creature generator with boss-design rules built in, and a faction model that doesn't lock players to a side. The adaptation problems are concentrated in six places:

- Cost is permanent and ends in collapse or death.
- Guru is a roll of names, not a level cap.
- The Necrotic school has no combat abilities.
- Nothing resurrects.
- Martial and alchemy schools have no visual signature.
- A live server would resolve plot states the canon keeps pending.

## 1. What the canon supplies, and where it resists

| Canon system | MMO system | Friction |
|:--|:--|:--|
| Ranks Novice–Guru, shared by all institutions | Progression tiers; rank-ups as boards, verification, initiation | Guru is a roll (Ledger 23 names, Assay 14) [N: Block 3 row 3a], not a cap every player reaches |
| Cost progressions; "severity nearly equal to power" | Per-school strain plus persistent wear | Canon cost only moves forward and ends terminally |
| 400-day year, 80-day phases, own-phase casting discount | Weekly world-state rotation | Canon only specifies own-phase cheapest and portals dearest in Velquor |
| Ecological Engine: four-factor formula, tier ≤ node, vulnerability logic per tier | Emergence generator plus boss templates | How the ethos factor expresses itself is unstated; Guru tier can't be killed |
| Biome × Moon grid | Zone hazard tables per phase | Five environment states per biome is a large art bill |
| Ethos, institution, and culture as independent axes; 12 factions; 5 vacant cells | Contract-based standing, no faction lock | The genre default is faction lock |
| Two mints, phase-priced fares, Manifest Rule, Meridian routes | Trade, logistics, smuggling, inspection | Figures are [N] and are records, not facts |
| 12 classes with institutional roles | 12 classes, uneven role coverage | Registry names mislead genre expectations |
| Part X visual grammar | VFX rules, typeset UI, presentation scaling | Covers magic schools only |
| Chronicle; Appendices C and D | Historical "record" instances; residue props | Instances may not supply what the records omit |

One decision sits above all of these. Servers will resolve what canon holds open: the airship charter, the Ethosless × Gold slot, the Frostvatn basin. The cleanest handling follows "numbers are records." [N: D6, Block 2] Each server's history is that server's record, starting from canon's 1245. Nothing a server produces is canon.

## 2. Classes and archetypes

Character creation keeps five axes separate:

- **Culture:** origin, homeland, and naming form. Birth-moon applies to Tangata only and age-set cohort to Umutu only, per the asymmetry rule.
- **School:** the combat kit.
- **Registry class:** a title given by whichever registry the character joins.
- **Ethos:** belief, per Part VI's design principle "Ethos = belief, Institution = charter" [C]. Each class has a default, not a lock [R: Part VI's ratified list "Ethos (character classes)" pairs each class with one ethos; section 9].
- **Institution:** standing, earned by contract.

No school is gated by culture (XI.6).

Six of the twelve registry names point players at the wrong genre archetype:

- **Necromancer:** the school does not raise the dead.
- **Archpriest:** an Elemental, not a healer.
- **Paladin:** hammer infantry with no Divine magic.
- **Hexblade:** purely martial, no magic.
- **Warlock:** poisons and golems, not pact casting.
- **Apothecarist:** a Nature healer; potions belong to the Warlock.

The one-school premise also rules out genre hybrids: no holy paladin, no spellblade, no battlemage. Hybrid play happens at the group level. Having players select a school, with its working term shown, handles both problems. The registry word appears only on documents [N: Part VI, Terminology; R.1 item 20].

| School (working term) | Registry class | Default ethos [R] | Genre archetype → role | Skill test |
|:--|:--|:--|:--|:--|
| Arcane (overlay work) | Sorcerer | Rationalist | Mage → controller, precision burst | Cast rhythm; parameter tuning |
| Glaive (holding the circle) | Vanguard | Rationalist | Lancer → zone tank | Spacing; grip routing |
| Light Arts (bench work, bonding) | Artificer | Rationalist | Engineer → pet and deployable support | Splitting attention across familiars; setup |
| Elemental (sustained work) | Archpriest | Devout | Elementalist → AoE artillery, terrain | Upkeep budget; placement |
| Hammer (holding flat) | Paladin | Devout | Juggernaut → breaker tank, siege | Stack release timing; seam targeting |
| Divine (boon work, transfer) | Apostle | Devout | Cleric/bard hybrid → healer-leader | Budgeting self-debits; positioning under escort |
| Longbow + dagger (overwatch) | Ranger | Reverie | Archer, no pet → sniper, scout | Position selection; leading targets |
| Ax (the gate) | Berserker | Reverie | Barbarian → frenzy melee | Gate timing; trust in the group |
| Nature (attunement, channel work) | Apothecarist | Reverie | Druid without elemental casting → contact healer, shapeshifter | Contact uptime; wound triage |
| Necrotic (boundary reading; practitioners say "reader") | Necromancer | Ethosless | No genre match → death-window support, executioner | Charge economy; hold timing |
| Sword/Shield (escort; counter-practitioner work) | Hexblade | Ethosless | Guardian/spellbreaker → bodyguard tank, anti-caster | Reads; intercept timing |
| Dark Arts (dosing) | Warlock | Ethosless | Alchemist/poisoner → DoT, golem summoner | Onset timing; debt management |

Specs are an adaptation taxonomy built on canon ability clusters [A]. In three classes canon itself presents the alternatives: Arcane's two writable variables, time and gravity (Part II, Arcane Guru); Divine's two delivery modes, sustained contact and directed speech (Part II, Divine Master); and Elemental sub-discipline specialization (Part II, Elemental Master) across the four elements Part X codes [C]. In the other nine, the split divides ability clusters that canon does not present as alternatives [A]. Eleven classes have two specs and the Archpriest has four, so the roster reaches 26 variants without adding schools (section 4). Each class chooses its spec at a fixed rank, and every spec has a playable form below Guru (section 4, Spec branching) [A].

Role coverage differs by charter, and canon explains each gap:

- **Crown:** the default triad is a complete tank/DPS/healer trinity.
- **Accord:** no healer. Canon states the reason as a critique, not a creed: the institution "cannot heal, so it studies the healer" (Part II, Nature institutional role) [C]. Part VI gathers the line as clause 5 of the Ledger's Ethos Statement and records that the Accord has no creed.
- **Chimera:** no tank. Its rangers and berserker bands "could not take a walled town" (Part IX, Antler War; Part VI, Force Types, Muster row) [C].
- **Ethosless:** death management replaces healing.

Because standing is contract-based, groups hire across charters. That matches canon: the Accord "licenses what it cannot staff," and the Unsworn hold contracts with all three.

Canon also specifies the power curve. Martial Novices are competent, magic Novices barely functional, the curves cross at Master, and a martial Guru fights a platoon (forty foot, the Quorum's figure, itself [N]). Expressed as how many NPC foot soldiers a character can take on:

- Martial, ×3 per rank from 1.5: 1.5 / 4.5 / 13.5 / 40.5.
- Magic, ×5 per rank from 0.5: 0.5 / 2.5 / 12.5 / 62.5.

The two cross at Master. Both alchemy Gurus are calibrated to the platoon standard, so alchemy takes the martial curve. These values apply to NPC formations only; PvP uses normalized power. Early magic weakness is covered by bought consumables, since Dark Arts are "purchased by everyone." NPC baseline stock guarantees that supply (section 6, Economy) [A].

BDO already has a Ranger with longbow and dagger and a Berserker with axes. Terhia's versions have to stand apart through prepared-ground overwatch and the gate/calling-back mechanic, not through weapons.

## 3. Combat architecture

| Layer | Governs | Canon source | Main users |
|:--|:--|:--|:--|
| Commitment | Inputs, animation weight, telegraphs | Sword/Shield Adept reads weight "before the commitment" | All; martial classes read it earliest |
| Strain | Cost of output | Parts II–IV cost progressions | All, per school |
| Perception | Class-specific information | Overlay, attunement, boundary reading, reading posture, flow, and load paths | All, differently |
| Environment | Terrain, hazards, edits | Biome × Moon grid; "flat" vs "trees"; sustained works | Archpriest, Sorcerer, Paladin, Reverie classes |
| Formation | NPC group integrity | Platoon standard; Force Types | Martial Gurus |
| Downed state | Zero-HP state and its timer | Holding, transfer, channel work, preservation draughts | Five classes |
| Phase | Weekly modifiers | Moons and Calendar; Phase Cascade | Magic schools only |

### Strain: one container, twelve contents

The formula is: strain cost = k(school) × k(phase) × output. No ability is free, per the premise that severity equals power. Strain is a game resource, not canon cost; the two are defined apart in Cost and strain: terms, below [A].

The UI container is shared: a meter with stage bands. The stages, effects, decay, and recovery stay per school, and Arcane keeps five bands. A single generic overheat bar would erase the canon's central distinction between schools.

Bands carry penalties only [A]. Rank gates techniques and strain prices them: no technique is gated by band, and no band discounts one. Every technique stays usable until the final band's collapse or lockout, and high-output techniques cost enough to cross several bands in one use. Strain permits redlining and never rewards it. The Warlock's budget potions, which "push a body past its budget and present the bill later" (Part IV), and the Berserker's held pool already work this way [C/A]. The player's decision is whether the situation is worth the price, not how to reach a stronger state. Design test: if a player would enter a band with nothing to cast, the band is mistuned [A].

Where canon describes a cost that serves before it harms, the serving phase runs on the cost file, over a career, and never as an encounter band. Hammer conditioning is "bones densified through years of controlled breaking": "Strong young. Brittle early." Dark Arts tolerance means "nothing can ever poison you again." Longbow tuning hears fletching "at two hundred paces" and "cannot be turned down" (Parts III–IV, Emotional Payload) [C]. At encounter scale those bands show only their price [A].

Strain runs on three timescales:

- **Encounter strain** decays after combat.
- **Wear** is session-scale. It builds when you end fights in high bands or collapse, and clears with rest suited to the school.
- **The cost file** is permanent and only moves forward: a stage is "the same or later than in their previous appearance, never earlier" (XI.5 item 3) [C]. It starts at Adept, "the rank at which cost first appears on the file" [N: Block 3 row 3a], and drives the visual wear layer. It changes what a character can do, not how much damage it deals (Cost file consequences, below) [A]. Stat effects are limited to minor sidegrades or an opt-in hardcore ruleset.

A magic casting costs ×0.7 strain in its own phase (placeholder) and ×1.0 otherwise. Martial and alchemy schools have no governing moon, and the Phase Cascade prices only "what is cast." So seven of the twelve classes are unaffected by phase. The weekly shift moves the five magic classes against a stable baseline.

Guardrail: penalties that corrupt input (cast lag, slot lockouts, involuntary actions) appear only in a school's last two bands, last no longer than 1.5 seconds per instance (placeholder), and show a UI cue before they fire [A]. No band misreports the HUD: a band can remove information from the perception layer, and never adds false information [A].

### Cost and strain: terms

| Term | Layer | Definition |
|:--|:--|:--|
| Cost | Canon | What practice does to a practitioner's body and life, per school (Parts II–IV). Casting cost varies with moon phase, not node activity: a design decision of 11 September 2026, not a ratification item (Part I, Substrate and Nodes; R.1 item 25) [C] |
| Cost stage | Canon | A named step in a school's cost progression. Stages move only forward (XI.5 item 3) [C] |
| Cost file | Game record of canon cost | A character's permanent stage record. The only game layer that carries canon stages [A] |
| Strain | Game | Per-encounter resource that prices techniques and decays after combat. Not a canon quantity [A] |
| Band | Game | A strain threshold that carries a penalty. Labeled with canon stage names by default [R, section 9: Cost timescales] |
| Wear | Game | Session-scale residue of ending fights in high bands; cleared by school-specific rest [A] |
| Strain modifier | Game | A multiplier on strain. The phase modifier and the Arcane Guru dilation parameters mirror canon cost [C]. Every other modifier is [R] against the phase-only line (section 9, Strain modifiers beyond phase) |

### Cost file consequences

The file changes what a character can do, not how much damage it deals [A]. Canon already records most of the channels: the Emotional Payload paragraphs of Parts II–IV (craft register) describe how each school's body changes and how other people respond [C].

- **Body.** The wear layer (section 8), plus idle, rest, and traversal animations drawn from each school's progression: the raised draw-side shoulder, the Glaive veteran who stands "like a bent pike," the Hexblade who takes only a chair facing the door [C]. Residue scars ache during the phase of the school that caused them, generalized from canon's red-moon burn; this shows as idle animation and status text, with no stat effect [A].
- **Perception.** The class perception layer shifts with the file as a sidegrade that follows the school's progression: Longbow tuning widens and can't be filtered, Nature attunement narrows, Light Arts sight holds near and fails far [C]. The size of each shift is a placeholder [A].
- **Response.** NPC reactions and dialogue options open or close by school and stage, starting from the reactions canon records: healers who hesitate at a stained Warlock and the tailor who adjusts for a Ranger's shoulder "without asking" (Parts III–IV) [C], and the examination that reads the file aloud (Part IX, Second Register; section 7) [C]. A reaction rule beyond those is [A] if it asserts nothing about Terhia and [R] if it states a social fact.
- **Contracts.** Contracts that open to some file stages and close to others [R, section 9].
- **Guru files.** Every name on the Ledger's Guru roll has a cost file the Escrow Convention makes "a matter of treaty" (Part II, Rank Distribution) [N: Block 3 row 3a]. The server extends this to every rolled Guru and shows each stage publicly [A].

Excluded: permanent stat loss, and any file stage that adds offensive output [A]. The opt-in hardcore ruleset keeps its terms (section 7).

### Perception, downed state, formation, terrain

**Perception.** This is the Design Thesis turned into a mechanic: each class sees different combat information (detailed per class in section 4). Every boss mechanic should be readable by at least two perception modes. That rewards communication without requiring any particular class.

**Downed state.** Zero HP puts a character into the downed state on a timer. The UI label is "Boundary" for every class by default [R, section 9: Downed-state label]. There are five tools, none of them resurrection:

- The Necromancer holds: the ally keeps acting for a few breaths.
- The Apostle transfers: an instant restore, paid in years.
- The Apothecarist stabilizes by contact, slowly.
- The Warlock's preservation draught pauses the timer, and a budget potion stands the ally up with a deferred debt.
- The Artificer's familiars drag the ally clear and resupply.

When the timer expires, the character is defeated and respawns at the nearest settlement with wear added [A]. Defeat ends the playable account of an incident and asserts nothing about what happened to the character in the fiction: the game does not claim that player characters survive what they suffer or that anyone carried them off, and lethal violence stays lethal in Terhia [A]. Strain collapse is flagged "cannot always cure": it can be held or preserved, not healed.

**Formation.** NPC formations carry five integrity stats, one per martial Guru calibration line in Part III:

- Cohesion (Sword/Shield: "attrition of structure, not of men first").
- Space (Glaive).
- Ground and morale (Longbow).
- Structure (Hammer: "expressed as breakage").
- Headcount (Ax: "expressed literally").

Each martial class attacks a different stat, and a formation fails when any one of them breaks.

**Terrain.** The navigation mesh is tagged flat, broken, wooded, or walled. Paladin bonuses peak on flat ground and fall off in woods. Ranger and Berserker peak in woods. Ranger and Berserker attacking into walled ground lose their terrain bonus and take a penalty; defenders on the wall are unaffected [A]. That turns the rangers and berserker bands that "could not take a walled town" (Part IX, Antler War) [C] into a class rule without applying a force type to players. Values stay small (±10% placeholder).

**Counters.** Skirmish intent for prototype testing, not balance values [A]. Each edge appears once: if A beats B, B loses to A. No pair beats each other.

| Class | Beats (mechanism) | Loses to |
|:--|:--|:--|
| Hexblade | Sorcerer, Archpriest, Apostle (reads casting posture; closes inside a chant) | Vanguard, Artificer, Apothecarist |
| Sorcerer | Ranger (projectile redirection); Berserker (leap and charge control) | Hexblade, Apostle |
| Paladin | Berserker (Set ends charges); Artificer (structure damage on deployables) | Ranger, Archpriest |
| Vanguard | Berserker (entry strikes on rushes); Hexblade (dive onto a principal meets the circle) | Ranger, Apostle |
| Ranger | Paladin, Vanguard (approaches over open ground; slow-moving holders) | Sorcerer, Necromancer, Archpriest |
| Necromancer | Ranger (names the killer of a stealth kill [R, section 9: Necrotic Master killer-naming]); Apostle (execute marks end targets its heals keep near defeat) | Berserker |
| Artificer | Warlock (scent and heat detection of covert dosing); Hexblade (chokepoint locks against a melee principal-guard) | Paladin |
| Warlock | Apothecarist, Apostle (antidotes no one else can check; cleanse-reliant healing) | Artificer, Berserker |
| Apostle | Sorcerer, Vanguard (calm and resolve break crowd-control chains) | Hexblade, Necromancer, Warlock |
| Berserker | Warlock (fear immunity and the held pool absorb delayed-onset burst); Necromancer (weak in duels) | Sorcerer, Paladin, Vanguard |
| Archpriest | Paladin (terrain breaks a Set position); Ranger (terrain edits deny overwatch ground) | Hexblade |
| Apothecarist | Hexblade (out-sustains attrition through wound triage); beast adds in PvE | Warlock |

Dominance check: 24 edges. No class beats more than three; every class loses to at least one. Net edges run from −1 (Ranger, Apostle, Berserker) to +1 (Necromancer, Artificer, Archpriest). The +1 classes carry situational weaknesses the matrix does not list as edges: the Necromancer's duel weakness, the Artificer's thread penalty, the Archpriest's imprecise placement. Prototype testing adds edges where a net advantage shows [A].

### The phase week

| Phase | Cheaper casting for | Ambient pattern (grid) | Activity anchored in canon |
|:--|:--|:--|:--|
| Velquor | Necrotic | Distortion: mirages, tidal distortion, fault shifts, bog-light, lake-ice anomaly | Meridian runs; portal fares dearest. 1 Velquor, the Longest Night, is a window for Guru-tier emergences where readings allow (Frostvatn 1230 and the Watch's 1027 entry both rose at Velquor's strongest) [C: Part IX, 1230; N: Appendix D, Block 3 row 3d-iii]. Appendix D also records Guru-tier risings in Namaris (1062), Threnis (1091), and Saelura (1118), so Velquor is the strongest window on record, not the only one |
| Saelura | Elemental | Stabilizes or heals: oases, waterholes, thaw pockets, soil, rapid healing | Well work; gathering and recovery |
| Orrivane | Arcane | Disorients: herd agitation, heat delirium, echo hallucination, compass drift | Portal fares cheapest [C: Part I, Moons and Calendar]; the Ledger publishes its rank roll each Orrivane phase [N: Block 3 row 3a]; trade; examinations scheduled here [A] |
| Namaris | Divine | Burns or blinds: fire spread, sandstorm, storm surge, avalanche, whiteout | Tithe circuit; fire spreads across combat terrain |
| Threnis | Nature | Apex and dominant fauna: apex emergence, burrow dominance, reef intelligence | Master-tier emergence window (Shalei 1155 and Mwamba 1186 were both Threnis) [C: Part IX, 1145–63 and Antler War]; Chimera claims open; Passage renewals |

Phase-turn days are market truces in Renlei homelands, where canon records the custom [C: Part V, Renlei, Ritual; Part I, Moons and Calendar]. Other homelands trade normally at the turn [A].

The clock: one in-game day is 126 real minutes. That makes a phase 7 real days (lining up with the weekly reset), a year 35 days, and a Ledger hour 5.25 minutes. A Guru-tier operation as long as Frostvatn (two years) becomes a 10-week season.

With the longest night on 1 Velquor, midsummer falls near 41 Orrivane. The extended grid already reads that way: Saelura has thaw, sap-rise, and spring resurgence; Namaris is fire season; Velquor has lake-ice. Canon names seasons without placing them in the calendar: winters (Menneske ice-law; the Frost winters), summer (the Hexblade's cold patch), the dry season (Ulanga, Part VII), and "the season" of a warding contract, which Anchor Prices sets at one Threnis phase [N: Block 3 row 3b-iv]. Isavík's Solvør is the returning sun after the Longest Night (Part VII, God Register) [C], which fits a solstice at 1 Velquor for that homeland. Canon also places the Yamana on a western continent (Part V, Yamana), so two continents raise a hemisphere question. That needs a ruling before art commits to seasonal environment states.

## 4. Class kits

**Kit convention (v0.2).** Each rank bullet restates its school's canon entry for that rank (Parts II–IV) and is [C] for the ability it names. The game mechanics built on it (values, targeting, timers, UI) are [A]. Each numbered band carries the canon stage name for that step [C] and a game effect [A]. Anything that goes beyond the canon entry carries its own tag.

### Rationalist defaults

**Sorcerer — Arcane.** Ranged precision controller. Specs: time or gravity, the two variables canon makes writable.

- **Novice** throws arena objects telekinetically and shoves with force.
- **Adept** gets Read Structure, which marks a target and exposes its weight and hitbox data. Casts on a read target cost less. Unread casts pay a surcharge that climbs with cast frequency ("rushing produces burnout"), so rhythm is the skill [R, section 9: Strain modifiers beyond phase].
- **Master** gets the Overlay toggle. It shows trajectories and predicted positions a beat ahead and auto-leads thrown objects, draining strain while it runs.
- **Guru** places Dilation Volumes to slow enemies or speed up allied recovery. The player sets radius, ratio, and duration, and each multiplies cost [C: Part II, Arcane Guru]. Three tiers each, so 1× to 27× base (placeholder) [A]. Gravity Vectors pin a target, arrest a fall, or redirect a leap or projectile. Edits need the Overlay running and hold only while channeled; a stagger ends them. A volume that contains the caster multiplies strain and builds desync, per exterior-placement doctrine.

Strain, in five bands:

1. Headache: the overlay flickers.
2. Tremor: aim sways on precise casts.
3. Time-lag: cooldowns recover and strain decays more slowly (placeholder ×1.25) [A].
4. Memory dissonance: brief lockouts of skill slots, under the guardrail (section 3).
5. Identity-time fracture: collapse.

Desync feeds bands three and four directly, as canon states.

**Vanguard — Glaive.** Zone tank and area denial. Specs: line hinge or moving circle.

- **Novice** sets the point, a braced counter to charges, and gains a spacing bonus beside allies.
- **Adept** holds the circle, a two-pace reach zone. Each enemy that enters takes one automatic entry strike per window. Three grips: blade for cuts; haft for sweeps, trips, and parries; butt for short stuns. Switching grips is how combos route.
- **Master** reads battlefield geometry: enemy pathing corridors and the hinge of a line. It can extend the circle into a denied lane. It can also anchor, which regenerates guard for allied line members while it holds position.
- **Guru** walks the circle. NPC formations can commit only a fixed number of attackers into it at once. That is "priced as terrain" turned into a rule.

Strain:

1. Joint wear: slower grip changes.
2. Conditioning debt.
3. Spinal compression: shorter dodges.
4. The seizing: lockout.

Conditioning debt should be a rested-style bonus earned from optional drill content. Implemented the way canon states it ("two hours every morning, forever"), it becomes a daily chore with a penalty attached.

**Artificer — Light Arts.** Engineer and pet support. Specs: household (familiars) or systems (gadgets). Field-kit and conditional flasks are shared kit in both specs [A].

- **Novice** throws field-kit flasks (fire, smoke, adhesive) and repairs allies' gear and shields mid-fight.
- **Adept** builds conditional flasks (timed, proximity, tripwire) and bonds a first familiar. Options: a wren for spotting and marks, a rat to fetch and carry, or a beetle frame to carry loads and plate a position. Canon gives all three frames the same duties (carries, watches, fetches); the role split and the plating are [A].
- **Master** runs familiars with specialized senses at distance: remote viewing, and stealth detection by scent or heat. It also builds gadget systems:
  - a lock seals a door or chokepoint;
  - a lift builds vertical platforms;
  - a signal line shares marks and buffs among linked allies.
- **Guru** runs a household of familiars on standing tasks, plus a wagon deployable that resupplies and repairs a group. This is the platoon standard expressed as logistics.

Signature: each active familiar is a thread of attention. Each thread cuts the Artificer's own action speed and dodge recovery (placeholder −8% per thread). The class decision is distributed versus concentrated power.

Strain:

1. Reagent-etched hands: slower flask handling.
2. Close-work sight: long-range accuracy loss; near work unaffected, not improved [A].
3. Fume-worn lungs: slower stamina regeneration.
4. The divided attention: thread penalties persist after familiars are dismissed.

### Devout defaults

**Archpriest — Elemental.** AoE artillery and terrain shaper. Specs: fire, water, wind, or stone.

- **Novice** has short-range utility: ignite, minor water, gusts.
- **Adept** is when the element responds. The specialization is discovered in play rather than picked from a menu. Placement is imprecise, with area variance that shrinks with rank. Perception shows where the element already exists in the terrain, and works built from material already present cost less [R, section 9: Strain modifiers beyond phase].
- **Master** produces at functional scale: walls, trenches, fire lines, raised water, held wind. This is terrain other players collide with.
- **Guru** casts sustained works that keep drawing strain after the cast ends.

Signature: upkeep. Each persistent work adds strain per second until dismissed, and concurrent works multiply the cost (1.0 / 1.5 / 2.25, placeholder) [R, section 9: Strain modifiers beyond phase]. Per-second upkeep alone is output priced over time [A]. The class's output is how much ground it can hold while spending itself — canon's "strategic infrastructure that consumes itself."

Strain:

1. Fatigue: slower stamina regeneration.
2. Muscle failure: slower attacks and movement.
3. Organ strain: lower max HP.
4. Collapse: downed, with the longest downed-state timer of any class. A Guru-tier collapse writes to the cost file.

The title reads "Archpriest" on Crown documents, a function title on Accord documents, and nothing in Chimera territory [N: Part VI, Terminology; R.1 item 20].

**Paladin — Hammer.** Breaker tank and siege. Specs: charge-stopper or breacher.

- **Novice** splits shields, opens doors, and keeps footing under weight.
- **Adept** strikes the join. Armor, guards, and barricades show seams, and hits on seams deal structural damage (guard break, armor shred).
- **Master** Sets: a planted counter-stance that ends charges and rushes. It also reads load paths on gates and constructs.
- **Guru** hits where a formation stores its weight, and an NPC shield wall fails as a structure. In PvP, a guard break on one linked shield-wall member spreads to the adjacent linked guards.

Terrain: strongest on flat ground, weakest in woods [C: Part III, Hammer institutional role; Part IX, Antler War].

Strain:

1. Micro-fracture conditioning: stacks accrue from holding Set and from heavy hits, and grant nothing at encounter scale; the conditioning benefit sits on the cost file (section 3) [A].
2. Bone remodeling.
3. Deep-set brittleness: past a threshold, the stacks add crit vulnerability [A].
4. The settling: lockout.

The timing skill is releasing Set before the stacks reach brittleness [A].

**Apostle — Divine.** Healer-leader. Specs: directed speech (cone, group) or sustained contact (single target, stronger). Those are canon's own two delivery modes.

- **Novice** has three tools:
  - speaks with intent, a cone buff;
  - projects calm, which removes fear and panic;
  - steadies pain by touch, giving flinch and stagger resistance but no healing.

  Its perception shows allies' fear and panic states.
- **Adept** turns encouragement into stamina restoration, and reassurance slows bleed ticks. Canon's Adept entry is encouragement that lands physically and a slowed pulse; the stamina and bleed effects are [A].
- **Master** applies boons: confidence (accuracy), endurance (stamina and higher strain thresholds), and resolve (resistance to crowd control).
- **Guru** transfers: large heals and restores for downed allies.

Signature: Part II gives Divine no restorative ability below Guru, and at Guru restoration is lifespan transference (Part II, Divine abilities) [C], so the kit has no free heal. The Crown's creed says the same in its own voice, in the in-world register: "The healing is the transfer; the Apostle's own aging is the debit" (Part VII, clause 2).

- Each transfer writes its years to the cost file when it happens, and the file shows them as visible aging (section 8). Years never refill; at Guru, "compression is the spell" (Part II, Divine Guru) [C].
- Transfer tolerance caps transfers per encounter. It is bodily tolerance, not years: it refills between encounters and restores no lifespan [A].
- As tolerance drains, the Apostle's own max HP and move speed drop for the fight (frailty) [A].
- Encounter tuning assumes no transfers outside Guru-tier operations, so a transfer is an emergency expenditure, not part of a rotation [A].

That makes the healer the group's scarcest resource. At formation level, canon's Crown column is Hammer (Paladin) with Archpriest and Apostle support [C: Part VI, Force Types, Column row, a view of Part III, Part VII, and Part IX]; the group template follows that column [A].

Strain:

1. Minor aging.
2. Frailty.
3. Organ degradation.
4. Lifespan compression.

### Reverie defaults

**Ranger — Longbow and dagger.** Sniper, scout, area denial. Specs: overwatch or tracking.

- **Novice** fires volleys, keeps camp watch (a detection radius at rest), and covers the bow's blind distance with the dagger. The dagger has no separate progression, per the Part III decision.
- **Adept** marks moving targets and tracks across biomes (trails only the Ranger sees). It fires from prepared concealment without breaking it.
- **Master** sets overwatch on a slope, treeline, or pass. Shots auto-lead to predicted positions. Enemies crossing the covered ground are engaged automatically at reduced damage.
- **Guru** denies ground. Victims get no damage-direction indicator and no projectile trace. NPC formations lose morale with each death they can't answer. In PvP, the traceless effect is the entire Guru payoff.

Strain:

1. Draw-side deformation: slower dagger.
2. Watch-broken sleep: no rest regeneration unless another player keeps watch at camp.
3. Sensory tuning: ambient audio can't be filtered, and the perception layer marks every sound source in range, relevant or not. The wider range itself sits on the cost file (section 3) [A].
4. The unclosing eye: no rest states.

**Berserker — Ax.** Frenzy melee. Specs: directed frenzy or full gate.

- **Novice** commits through fear effects and goes first over barricades.
- **Adept** opens the gate. That gives fear immunity, pain suppression (incoming damage deferred into a held pool), and exchange-ending finishers against staggered targets.
- **Master** directs the frenzy, keeping control of targeting through longer holds.
- **Guru** opens the gate all the way. It can't close on its own, and targeting becomes nearest-first. It ends when nothing in reach stands or an ally channels the calling-back. Post-gate collapse follows.

Signature: the held pool releases when the gate closes (placeholder 60%). Calling-back is a verb any class can perform — canon's "the companions' first duty." The Berserker is the one class with no perception layer: the gate trades information for output.

Strain:

1. Post-gate collapse: downtime.
2. Frenzy amnesia: when the gate closes, target locks and marks set before it are cleared, and the combat log for the gate period is withheld [A].
3. Affect blunting: incoming buffs are weaker ("joy arrives muffled").
4. Heart-burn: the strain ceiling drops across a session.

**Apothecarist — Nature.** Contact healer and shapeshifter. Specs: channel work or morphic borrowing.

- **Novice** senses creature and plant condition, and holds or redirects small wildlife (control on beast adds, decoys).
- **Adept** locates where damage sits. On allies, wounds become individually treatable: bleed, fracture, burn, poison. On beasts, the Adept-tier dependency and weak points show. Contact deepens reading, so tether effects ramp up with uninterrupted contact.
- **Master** redirects channels through sustained contact. It can heal over time, move a wound from one linked ally to another, or spread incoming damage across a linked group [R, section 9: Nature wound redistribution]. Strain collapse and a Warlock's venomous body are flagged "cannot always cure": channel work gives resistance there, not repair.
- **Guru** borrows animal soma for bounded periods: hawk's eyes (range, marks, crits) and wolf's endurance (stamina, sprint). Further aspects are learned by attuning to emergences in different biomes, a collection loop fed by the Ecological Engine.

Strain:

1. Scar tissue.
2. Sensory narrowing: the attunement radius shrinks, so distant allies drop out of the attunement layer and contact tethers break at shorter range; party frames stay accurate [A].
3. Partial morphic blending: aspect traits persist after the aspect expires, without its bonuses; hands and posture stay partly animal, so contact abilities are weaker until the traits fade [A].
4. Species bleed: bursts of aspect behavior outside player control.

### Ethosless

**Necromancer — Necrotic.** Death-window support, executioner, investigator. Specs: reading or holding. Canon gives this school perception and holding, not harm.

- **Novice** senses death sites: "a room where someone died feels different" (Part II, Necrotic Novice) [C]. It also sees every combatant's distance to the boundary, which shows execute windows. That extends canon from where death happened to the living [R, section 9].
- **Adept** reads recent crossings in an area as a general impression without specifics: that something died, approximately when, and the emotional register (violent, peaceful, confused, empty) (Part II, Necrotic Adept) [C]. Each crossing in range grants a charge. That makes the class strong in large fights and dense PvE and weak in duels, by design ("a battlefield is overwhelming").
- **Master** reads a death site in detail:
  - In PvP, it names the killer of a fallen ally and reveals them for a window [R, section 9: Necrotic Master killer-naming]. This directly counters stealth kills. Canon's school "has twice named a killer" (Part II, Necrotic institutional role) [N: R.1 item 14], and the naming the Chronicle narrates came through Guru holding (Part IX, 1163).
  - In PvE, readings of fallen elites or old sites expose encounter information.
- **Guru** holds the boundary. An ally in the downed state keeps acting for a few breaths (placeholder five seconds) and is defeated when the hold expires unless restored: "a delay measured in breaths" (Part II, Necrotic Guru) [C]. A held enemy elite yields information.

The kit has no Necrotic harm: Part II gives the school perception and holding at every rank, and nothing that injures [C]. Its offense is knowledge applied with an ordinary weapon:

- Untrained weapon handling: basic attacks only, with no martial techniques and no progression, so the one-school premise holds [A].
- Execute marks: spending a charge marks a target inside its execute window for the whole group, and the Necromancer's own basic attack ends a marked target still inside the window [A; rests on the Novice extension, section 9].
- Death-site readings (Master) and holding (Guru), as listed above [C].

Self-grounding spends the Necromancer's own HP to shed strain, which is canon's controlled pain.

Strain:

1. Pallor.
2. Death residue sensation: residue from recent crossings saturates the reading, so charges register more slowly (placeholder −25%) [A].
3. Touch erosion: bare-handed readings take longer, and contact healing on the Necromancer is weaker [A].
4. Boundary thinning: healing received falls toward zero, which forces grounding; no damage reduction [A].

**Hexblade — Sword and shield.** Bodyguard tank, anti-caster duelist. Specs: escort or counter-practitioner.

- **Novice** links guards with adjacent allies (shared block). It designates a principal and intercepts attacks aimed at them within range.
- **Adept** uses the shield as a second weapon: binds (weapon lock), checks (interrupts), and blind-angle control (flank attacks guarded automatically). It sees heavy-attack commitment earlier than other classes.
- **Master** has three counter-practitioner tools:
  - reads casting posture and breath before anyone else sees a cast tell;
  - parries flasks and bolts on the shield boss;
  - closes inside a chant, a gap-closer that interrupts channels.
- **Guru** kills the corners, and NPC cohesion fails in stages. In PvP, it gains bonuses against targets outside their group's support radius.

Strain:

1. Scar accumulation.
2. Residue mapping: each school that has hit you leaves a scar with its own sensation (canon's cold patch and red-moon burn), shown by texture rather than school color, since school color leaves with the casting (Part X, culture palette cross-reference). The scars ache under strain, slowing guard recovery (placeholder). No resistance: canon's residue is a record of every school that touched the body, not a defense [A].
3. Startle lock: involuntary guards that can cut off your own combos.
4. The guard that will not drop: locked in guard.

**Warlock — Dark Arts.** Damage-over-time, golem summoner, risky support. Specs: poisons or golems. Potions and draughts (purgatives, preservation draughts, budget potions, tailored potions, antidotes) are shared kit in both specs [A].

- **Novice** coats weapons and projectiles, clears ally poisons with purgatives, and pauses a downed ally's timer with a preservation draught.
- **Adept** has three tools:
  - Grades venoms by chosen onset. The player sets the delay, and a longer onset gives a larger payload, used to line up burst windows.
  - Brews budget potions: an ally exceeds stamina or strain caps now and pays a deferred debt later.
  - Raises a first golem, strong and stupid.
- **Master** works contact-grade poison into surfaces and strikes ("needs skin, not a cup"). It tailors potions to one named target and gives golems standing orders: guard, hold, attack the mark.
- **Guru** doses areas through censers and water, fields golem teams, and makes antidotes "no one else can check" (Part IV, Dark Arts Guru) [C]; in play, only the Warlock can administer them [A].

Perception shows dose stacks and tolerance on targets.

Strain:

1. Tolerance dosing: allied draughts and potions act at reduced strength on the Warlock; the immunity itself builds on the cost file (section 3) [A].
2. Organ staining: heals on the Warlock land slower ("healers hesitate").
3. Taste-death: food buffs stop working.
4. The venomous body: allied contact abilities used on the Warlock cost the caster, since canon makes "your blood a hazard" (Part IV, Dark Arts) [C]. Attackers are not poisoned: the adaptation does not turn the hazard into a weapon [A].

### Spec branching

Every class chooses its spec at a fixed rank, and every spec is playable below Guru [A]. Six specs were Guru-only in v0.1.1. Each now has a pre-Guru form that extends a lower-rank ability and does not grant the Guru ability early [A]. The forms hold under all three Guru models: under the roll, the pre-Guru form is the endgame kit for most players of that spec; under operation-only, the Guru form runs inside operations; under cost-gated, every player reaches it (section 7).

| Class | Spec chosen at | Specs | Pre-Guru form of the Guru-only spec |
|:--|:--|:--|:--|
| Sorcerer | Master | Time; gravity | Time: the Overlay's lookahead extends (placeholder ×1.5) and shows enemy cast and recovery timings. Gravity: Novice telekinesis scales with the Adept read, throwing heavier objects and shoving farther [A: canon's Novice entry is light objects]. No edit of time or gravity below Guru |
| Vanguard | Master | Line hinge; moving circle | Moving circle: the circle still drops when the Vanguard moves, but re-plants in 0.5 s instead of 1.5 s (placeholder), and the first entry strike after a re-plant staggers. Walking the circle stays at Guru |
| Artificer | Adept | Household; systems | Household: from Master, each familiar accepts one queued order (fetch, watch a point) that runs for 20 s (placeholder) without a thread penalty. Standing tasks stay at Guru |
| Archpriest | Adept, discovered in play; pronounced at Master, canon's word (Part II, Elemental Master) [C] | Fire; water; wind; stone | Not Guru-only |
| Paladin | Master | Charge-stopper; breacher | Not Guru-only |
| Apostle | Master | Directed speech; sustained contact | Not Guru-only |
| Ranger | Master | Overwatch; tracking | Not Guru-only |
| Berserker | Master | Directed frenzy; full gate | Full gate: holds run 50% longer than the directed spec's (placeholder). Past the directed limit, targeting drifts to nearest-first and the held pool releases at 75% (placeholder). The gate still closes on its own below Guru |
| Apothecarist | Master | Channel work; morphic borrowing | Morphic borrowing: Novice wildlife control scales to beast adds up to elite size, and attuning to emergences records aspects that unlock at Guru. The collection loop starts at Master; bodily borrowing stays at Guru |
| Necromancer | Master | Reading; holding | Holding: the Master reads each downed ally's remaining timer exactly and shares it with the group; spending a charge flags that ally for the group's downed-state tools. Rests on the Novice extension [R, section 9: Necrotic perception of the living]. Holding stays at Guru |
| Hexblade | Master | Escort; counter-practitioner | Not Guru-only |
| Warlock | Adept | Poisons; golems | Not Guru-only |

## 5. PvE: the Ecological Engine as encounter framework

| Tier | Power source | Vulnerability logic | Encounter template | Scale |
|:--|:--|:--|:--|:--|
| Novice | Amplified natural trait | Pattern exploitation | Rigid behavior loops with punish windows | Solo, open world |
| Adept | Magical enhancement | Substrate disruption | The enhanced state holds until readers find the dependency (a den-site reading, a water source) and the group disturbs it | Small group |
| Master | Environmental dominance | Environmental reversal | The beast owns the arena. The win condition is changing the environment, or fighting in the phase when its dependency inverts | World boss, multi-week |
| Guru | Lunar embodiment | Domain displacement | Can't be killed. The operation unseats the tether: engineering works, defending the works, and supply | Server season |

**Timing.** The Shalei record sets the Master-tier cadence [C: Part IX, 1145–63]: emergence in Threnis, a road closed, then displacement the following Saelura when hunters collapsed its oasis dependency. In phase order that is a three-week arc:

1. Threnis: emergence.
2. Velquor: a week of dominance.
3. Saelura: reversal.

Frostvatn sets the Guru template, including its cost ledger. On a server with a Guru roll (section 7), the operation spends the cost files of that server's rolled Gurus, which gives the roll a function.

**Tier ceilings.** Node readings per zone cap tiers. A server-wide Watch reading rises across seasons and stays unexplained, as in canon, where no reading can see why the figure rises (Part I, Three Readings) [N: Block 3 row 3c], and widens where Master and Guru tiers can occur. Canon's present state already works as a live-service content ramp: readings are not back to baseline, and Frostvatn was "the decade's largest expression, not its conclusion."

**Generation.** The generator combines biome fauna, the phase's grid cell, and the ethos of the ground. It writes each emergence to a per-server register, never to XI.3. R.8 rules out a bestiary list, and a generator satisfies "environmentally produced, not designed." The Deep Watcher, canon's one archetype usable at any tier, is the obvious first test across all four tiers.

**Resolution.** A kill is one resolution among several. Displacement and way-law terms (the Puketai precedent, a biome effect rather than a beast, Part IX, 1224) are valid outcomes. Appendix D adds three more displacements: closed ground held empty (Marama, 1091), the sea let in over the tether (1118), and a Saelura stabilization (Shalei, 1062) [N: Block 3 row 3d-iii]. Standing consequences differ by institution: the Ledger files culls as contracts, and the Concord negotiates.

**Warning signs.** The Ambient Ecological Confirmation rule is a craft rule in canon; here it becomes a world-design rule. Each zone carries an environmental indicator that shifts before the UI announces an emergence, so experienced players read the ground first.

## 6. Factions, law, and economy

Standing is contract-based across all twelve factions. The five vacant cells stay empty until ruled on. Filling Ethosless × Gold in particular would settle the rumor in The Present.

**Territory.** The three Readings "disagree about what a node is and agree about where the nodes are." So the same map sites carry three claim systems:

- Accord ground is licensed by examination: competitive trials, since "standing is examined."
- Crown ground is held by benefice. Benefice rests on certified miracles, and an Assay audit that finds a claim fraudulent voids it (Part VI, Indigo Assay; Part IX, 1226) [C]; the claim mechanics are [A].
- Chimera ground is claimed in Threnis week and held by presence. Closures lapse at the phase turn unless renewed [C: Part I, Moons and Calendar; Part V, Tangata, closed ground].

BDO uses "node" for territory units. Keeping Terhia's substrate node as the site, and the claim system as the ownership layer, stops the two meanings from merging.

**Contract warfare.** The Marendi rule applies: two Unsworn companies fielded on opposite sides stand down in view of both principals, and each contract is satisfied for the day (Part IX, 1184; Part VI, Force Types, Company row) [C]. Hiring a company of the compact that the enemy has fielded becomes a way to remove it from the field [A].

**Law** is layered: cultural law per homeland sits on top of charter enforcement.

- Menneske: a kill before three witnesses is a binding record, which makes it a bounty [R, section 9: Witness law for kills].
- Renlei: bounty contracts need seals.
- Unsaan: hosting houses are inviolable for three nights, and the host is liable for the guest.
- Yamana: PvP on a causeway carries a double penalty.
- Umutu: truce ground at Tinwara and Marendi disables both combat and pressing claims — "knives or papers."
- Tangata: ways carry tolls, and closed ground is trespass.

**Practice legality** varies by territory:

- Necrotic practice is anathema on Crown ground (Part VII, clause 5) [C]. In Accord territory it is registered but distrusted, and a boundary reading is inadmissible as evidence; Chimera territory receives it (Part II, Necrotic institutional role) [N: R.1 item 14]. Accord enforcement targets unregistered practice, not the school.
- Nature is proscribed on Crown ground, with "reverie generally" (Part VII, clause 5; Part IX, 1189) [C]. How the Edict reaches the Reverie-default martial classes depends on decision 9.
- Dark Arts are licensed nowhere (Part IV, Dark Arts institutional role) [C].

Enforcement triggers only on casting in sight of settlement enforcement. It shapes where these classes live and trade without locking any content.

**Registration** is a player choice. Registered characters (Ledger or Assay) get portals [R, section 9: Portal access by registration], certified markets, leases, and audits. Unregistered characters get Off-Ledger and Meridian access and can be prosecuted in Accord territory.

**Economy.**

- Two mints, with exchange rates that differ by location [N: Block 3 row 3b-i].
- Castings, fares, and leases are priced by phase. Staples follow freight costs with a lag [N: D2; Block 3 row 3b-v].
- Four transport modes have distinct rules:
  - Portals carry light cargo under manifest, with the goose clause intact.
  - Airships carry bulk and are the first thing inspectors board.
  - Caravans are slow and way-tolled, and profit when portals fail.
  - Ice harbors depend on an Escrow-leased harbor-grade Guru (Stenhavn; four alive at the Convention's signing) [N: Part I, Transport; R.1 item 12]. Other harbors do not.
- Meridian runs happen in Velquor, over Threnis-territory routes.
- Only Artificers and Warlocks craft consumables; everyone buys them.
- NPC baseline supply [A]. Each settlement stocks basic consumables (field-kit flasks, purgatives, basic draughts), a limited quantity per phase, at a fixed price of 1.5× material cost (placeholder). Standing NPC buy orders at 0.8× material cost (placeholder) set a price floor for player crafters. Light Arts stock sells at certified vendors; Dark Arts stock sells off-register through dealers, since Dark Arts are licensed nowhere. Player crafting supplies everything above basic grade and all volume beyond the phase allowance. Prices rest on the pending Economic Baseline (section 9, Canon dependencies).
- BDO-style life skills become board-certified trades, with small school knacks drawn from D1's latent-capacity reading.

**Navigation.** Tangata channels require the channel's tale, whose text encodes the hazards. Accord charts miss those hazards ("a better wreck record"). Rotokere has three competing tales and its pilots recite none; asked, they say the lake already knows (Appendix C, item 3) [N: R.1 item 21]. The game leaves it unexplained. The ninth channel off Puketai opens only in Velquor and stays unclaimed [R, section 9: Ninth channel as a route].

## 7. Rank progression and Guru scarcity

A rank-up takes the form of the place where it happens:

- a Ledger board: an examination trial;
- Assay verification: Divine;
- Sedge initiation: Nature;
- compact or muster standing: martial classes on the Chimera side.

Unregistered rank is recognized by reputation only. Boards read the cost file aloud (Part IX, Second Register) [C], and the UI carries the Second Register option: "declined to review results."

There are three ways to handle Guru:

- **The roll.** Registered Guru standing is a limited roll per server, sized from the published rolls [N: Block 3 row 3a]. It carries obligations: Escrow leases, portal-station standing, benefices. Unregistered Guru seats are capped per server as well, and the server never publishes the cap, so the Chimera's count stays "whoever stayed unregistered, which is the one number no table gives" without becoming unbounded [A]. Canon's unregistered Gurus are few, not many: the Purge made Dark Arts Gurus "rare, unregistered, and priced accordingly" (Part IV) [C]. An unregistered Guru carries the unregistered penalties (section 6) and none of the roll's obligations.
- **Cost-gated.** Everyone can reach Guru, and Guru castings write permanently to the cost file. A completed file retires the character. Yamana duty inheritance supplies the model for a legacy mechanic: unmet duties and some unlocks pass to a successor (Part V, Yamana) [C]. As a culture feature it applies to Yamana characters only, per the asymmetry handling in section 2 [A].
- **Operation-only.** Guru castings exist only inside Guru-tier operations.

Under every option, a Guru-scale casting is a server event: it enters the server's history (section 1), and every player can see that it happened and where. Attribution follows registration: the roll names a registered Guru, and an unregistered Guru's casting enters the history unattributed [A].

The roll, plus the capped unregistered path, keeps canon's numbers and makes registration a real endgame decision. A registered seat trades obligations for portals, certified markets, and a named place in the history; an unregistered seat trades prosecution risk for freedom from the roll. For most characters Master ends ordinary progression, and Guru is a scarce seat the server records [A]. Cost-gating works as an opt-in hardcore ruleset.

The six specs that existed only at Guru (Sorcerer, Vanguard, Artificer, Berserker, Apothecarist, Necromancer) now have pre-Guru forms that hold under all three models (section 4, Spec branching) [A]. The Guru ruling still decides how many players see the Guru form.

## 8. Art direction

**Color.** The ground carries the culture's palette, and school color arrives with a casting and leaves with it (Part X). This needs two additions to Part X:

- Martial VFX stay physical: dust, sparks, motion trails, impact deformation.
- Alchemy VFX stay material: glass, fumes, smoke, clay, brass.

Three distinct classes of VFX, plus school color that doesn't linger, keep a fifty-player fight readable. Large BDO fights lose legibility on exactly this point.

**Sky.** Five moons, with the dominant phase tinting night light:

- Saelura: the red moon on held water (the Umutu palette) [N: Block 3 row 3g].
- Velquor: the darkest nights under the black moon. This is a rendering reading of "Black," and it suits Meridian runs.
- The Longest Night: lamp-amber Menneske settlements, from the Menneske palette and the lamp-lit eve (Part V, Menneske, Ritual; Material Signatures) [N: Block 3 row 3g]. Canon does not state how other cultures light the night.

**Materials.** The Material Signatures table already works as an art bible at BDO's level of detail: fiber, building, mount, craft, and palette per culture. Its [N] cells (fiber, craft, palette) need ratifying before they become asset specs.

**Wear layer.** From Adept onward, the cost file shows on the body, by school:

- tremor and muscle wasting;
- grey hair and papery skin;
- a stoop, or the raised draw-side shoulder;
- fur and eye changes;
- stained nailbeds and eye-whites;
- acid-white fingertips;
- scars textured by the school that caused them, not colored by it (Part X: school color leaves with the casting).

**UI.**

- Accord and Crown content arrives as typeset documents (Part X rule 4, with XI.2 as templates).
- Chimera content never arrives as a form, since "nothing is registered." It comes as spoken terms and tales.
- Codex entries are sourced records that keep their discrepancies, following the Purge-count pattern.
- Maps are layered records, each with blind spots.

**Presentation.** HUD margins, camera distance, and audio compression track the encounter stage: stable, rising, crisis. Removing the HUD entirely is reserved for Guru-tier moments and capped per season. That is the game's version of Part X's limit of two full-bleed pages per volume [C: Part X, Panel Compression Scale].

**Sourcing.** Carving, textile-border, and body-pattern motifs from Polynesian, Mesoamerican, and Saharan African sources carry lineage meanings in those cultures. They need review before they become cosmetic unlocks.

## 9. Adaptation register

Part X set the precedent: adaptation work lives in the craft register. An MMO adaptation document can keep the same discipline by separating three things: canon used as-is, adaptation-only mechanics, and items that touch canon and need a ruling. The canon-touching items so far:

| Item | Canon position | Proposed handling |
|:--|:--|:--|
| Server continuity | Airship charter, Ethosless × Gold, and the Frostvatn basin are pending | Server histories are records from a shared 1245 start; none are canon |
| Necrotic harm | Part II gives the school perception and holding only | Removed from the kit in v0.1.1; offense is untrained weapon handling plus execute marks. The v0.1 harm tools are kept in the Changelog; reinstating them needs a ruling |
| Phase cost matrix | Own phase cheapest; portals dearest in Velquor | Own-phase discount only, until ruled |
| Seasons | Named but not placed in the calendar: winters, summer, the dry season, and a warding "season" of one Threnis phase (Anchor Prices [N]). Solvør is the returning sun after the Longest Night (Part VII). The extended grid fits a solstice at 1 Velquor. Two continents | Rule before seasonal art |
| Martial and alchemy visuals | Absent from Part X | Physical and material VFX classes |
| Ethos in emergences | Canon "does and does not state how" | The generator needs a rule |
| Guru population | Rolls of 23 and 14, and the unregistered count is "the one number no table gives" (Part II, Rank Distribution) [N: Block 3 row 3a]; unregistered Dark Arts Gurus are "rare" (Part IV) | Default: the roll plus a capped, unpublished unregistered path, with Guru castings as server events under every option. Alternatives: cost-gated; operation-only; or seats reached by roll or by an operation role |
| Player death | No resurrection | Downed-state tools; defeat and respawn are a play abstraction with no in-fiction claim about survival (section 3) |
| Crafting | Premise: everyone is born with one magic or martial school. Part IV calls the two alchemy disciplines arts and gives them the shared rank ladder; no canon line places them under the premise (canon-side finding, Changelog v0.2) | Class-crafted consumables; trades kept separate |
| Names and words | No named Umutu or Tangata individuals; no invented vocabulary (conlang) | Coin names per Money (Part V) [N: Block 3 row 3b-i]; register each |
| Record instances | No filling in omissions; residue never explained; Frostvatn undecided | Competing records shown on screen; no quest resolves residue |
| Episode cast | No culture assigned (XI.6) | Kept out of the game until ruled |
| Culture features | Birth-moon and cohort are culture-specific | Not universal creation options |
| Ethos flexibility | Part VI's ratified list "Ethos (character classes)" pairs each class with one ethos. Part VI also defines ethos as belief, independent of institution, and has detached Devout "lapse Ethosless" (vacant cell Devout × None). Evidence bearing on reading (b), found in v0.2: the Purge expelled "Hexblades and Warlocks of no institutional charter" (Part IX, 1163), which implies chartered ones who were not expelled as Ethosless; and every homeland holds "adherents of every ethos" (Part IX, The World in 1145) | Default, not a lock, pending a ruling between two readings. (a) The list fixes a practitioner's ethos by school: the game then locks ethos to school, since a free choice would contradict a ratified line, and creation keeps four free axes. (b) The list records each school's institutional tradition: individuals can hold another ethos, and Part VI needs a clarifying line |
| Cost timescales | A cost stage is "the same or later than in their previous appearance, never earlier" (XI.5 item 3) | Encounter strain and session wear are play representations that decay; only the cost file carries canon stages. Bands borrow canon stage names as labels for temporary effects; a ruling could require separate labels. The sharpest cases: Elemental collapse is death in canon (Part IX, 1230: an Elemental Guru "dead of collapse"), and identity-time fracture retired an Arcane Guru (same ledger), while both name recoverable bands here |
| Necrotic perception of the living | The Novice senses where death happened: "a room where someone died feels different" (Part II). No rank senses the living's distance to death | Execute windows and execute marks rest on this extension. Without it, the class keeps readings, holding, and untrained weapon handling |
| Cost stage in contracts | Contracts are priced by rank and season: "Warding contracts price Master overwatch by the season" (Part III). No line has contracts screen by cost stage | Contract access that opens or closes by file stage states a labor-market fact; rule before building it |
| Strain modifiers beyond phase | Casting cost varies with moon phase only: a design decision of 11 September 2026, taken against node activity ("the node made the enemy, not the bill"; Part I, Substrate and Nodes; R.1 item 25). Canon's own lines also vary cost with output: the Arcane Guru dilation parameters multiply cost, "rushing produces burnout" (Arcane Adept), and sustained works keep drawing cost (Elemental Guru), all Part II. Read at its stated scope, the decision bears only on modifiers priced by place or environment, which here is the Archpriest present-material discount; the Sorcerer modifiers and the concurrent-works multiplier price practice, as those canon lines do (finding for decision 2) | Default: kept as strain modifiers, which the section 3 glossary defines as game quantities, not canon cost. Affected: Sorcerer read-target discount and rush surcharge; Archpriest present-material discount and concurrent-works multiplier. If rejected, the Sorcerer's rhythm skill moves to cast-timing windows, and Archpriest upkeep keeps a flat per-work rate |
| Downed-state label | The Design Thesis assigns the boundary reading to the Necrotic school | The mechanic is named the downed state. Default UI label: "Boundary" for every class. Alternative: a label per institution, drawn from canon vocabulary |
| Ninth channel as a route | Given in a tale, together with the renewal practice of leaving it unclaimed | Default: navigable in Velquor, unclaimed (section 6). Alternative: tale content only, with no route |
| Nature wound redistribution | Master channel redirection through sustained contact is canon; moving a wound between people is not stated (confirmed in v0.2: Part II, Nature Master) | Default: the Master kit moves a wound between linked allies and spreads damage across a linked group (section 4). Alternative: channel work acts only on the contact target |
| Portal access by registration | Portals carry passengers and light cargo, and the Manifest Rule registers cargo declarations (Part I, Transport; Part IX, 1159). No canon line ties passage to practitioner registration (confirmed in v0.2) | Default: registered characters get portal access (section 6). Alternative: portals take anyone who pays the fare, and registration changes only manifest inspection |
| Witness law for kills | Menneske witness-law: "a thing said before three witnesses binds" (Part V, Menneske). It covers speech, not acts (confirmed in v0.2) | Default: a kill before three witnesses becomes a bounty record (section 6). Alternative: witness law covers what canon covers, and bounties come from charter enforcement |
| Necrotic Master killer-naming | Master boundary reading reconstructs the crossing's experiential texture (Part II). The naming the Chronicle records came through Guru holding, with the dying speaking (Part IX, 1163); Baishui's refused reading is a method that "might name" a killer (Part IX, 1211) | Default: the Master names the killer of a fallen ally in PvP (section 4). Alternative: the Master reads when and how the crossing happened, and naming moves to Guru holding. Affects the Necromancer–Ranger counter edge |

### Canon dependencies

Design elements that rest on pending canon [N]. Statuses confirmed against R.0 and R.1 in v0.2; every row is still pending. If a row is rejected, the listed elements need rework.

| Pending canon | Where recorded | Design elements that depend on it |
|:--|:--|:--|
| Platoon standard, forty foot | Block 3, row 3j (R.1 item 39) | Power curves (section 2); formation stats (section 3) |
| Phase Cascade | Block 2, D2; Block 3, row 3b-v (R.1 item 33) | Martial and alchemy classes phase-neutral (section 3); phase pricing (section 6) |
| Biome × Moon grid extension, six biomes | Block 2, row 17 (R.1 item 17) | Phase-week hazards (section 3); seasonal reading (section 3) |
| Appendix D, prior Guru-tier events | Block 3, row 3d-iii (R.1 item 42) | Velquor Guru-tier window (section 3); displacement outcomes (section 5) |
| Material Signatures fiber, craft, and palette cells | Block 3, row 3g (R.1 item 34) | Culture art specs; Saelura and Longest Night lighting (section 8) |
| Economic Baseline; Money; Kind and Labor; Anchor Prices; Population Magnitudes | Block 2, row 26 (R.1 item 26); Block 3, rows 3b-i to 3b-iv (R.1 items 30–32) | Economy, including NPC baseline prices (section 6); coin names (section 9); warding "season" (section 3) |
| Substrate and Nodes | Block 2, row 13 (R.1 item 13) | Node definitions (section 5); territory claims (section 6) |
| The Three Readings | Block 3, row 3c (R.1 item 27) | Territory claims (section 6); unexplained reading rise (section 5) |
| Practitioner, latent and trained | Block 2, D1; Block 3, row 3a′ (R.1 item 28) | Trade knacks (section 6) |
| Transport table | Block 2, row 12 (R.1 item 12) | Transport rules; harbor Gurus (section 6) |
| Airship propulsion | Block 2, row 24 (R.1 item 24) | Airship rules (section 6) |
| Force Types | R.1 item 39: a view; only the platoon-standard paragraph (3j) and two naval cells (3k) are pending | Formation system rests on 3j. The Crown column row is a view of ratified text, so the Apostle group template is [C] |
| Rank Distribution (Ledger statistic): the rolls of 23 and 14, the unregistered count, cost first on the file at Adept, the Ledger roll's files as a matter of treaty | Block 3, row 3a (R.1 item 29) | Cost-file onset and Guru files (section 3); roll sizing, unregistered cap (section 7); Orrivane roll publication (section 3); Guru population row (this section). Boards reading the file aloud rests on Part IX, Second Register [C] |
| Terminology: registry terms and working terms | Block 2, row 20 (R.1 item 20) | Working terms in class selection (section 2); Archpriest title by territory (section 4) |
| Design Thesis; Canon Discipline 1–4 | Block 2, row 19 (R.1 item 19) | Perception layer (section 3); Downed-state label row (this section) |
| Numbers are records (Canon Discipline 5) | Block 2, D6 (R.1 item 47) | Server histories as records (section 1) |
| Necrotic institutional role | Block 2, row 14 (R.1 item 14) | Necrotic legality in Accord and Chimera territory (section 6); "has twice named a killer" (section 4) |
| Residue appendix | Block 2, row 21 (R.1 item 21) | Goose clause (section 6); Rotokere (section 6); record instances (this section) |
| Ledger hours | Block 2, row 23 (R.1 item 23) | Ledger hour in the clock (section 3) |

### Open rulings

Joe's decisions from the handoff, with the default in force until ruled.

| # | Decision | Register row | Default in force |
|:-:|:--|:--|:--|
| 1 | Guru model | Guru population | The roll plus a capped, unpublished unregistered path; Guru castings are server events |
| 2 | Strain modifiers beyond phase | Strain modifiers beyond phase | Kept as strain-only modifiers |
| 3 | Necrotic harm | Necrotic harm | None; untrained weapon handling plus execute marks |
| 4 | Phase cost matrix beyond the own-phase discount | Phase cost matrix | Own-phase discount only |
| 5 | Seasons by phase; hemisphere | Seasons | Undecided; no seasonal art |
| 6 | Downed-state name | Downed-state label | "Boundary" as the UI label |
| 7 | Ninth channel as a route | Ninth channel as a route | Navigable in Velquor, unclaimed |
| 8 | Ethos factor in emergences | Ethos in emergences | Unspecified |
| 9 | Ethos lock by school | Ethos flexibility | Default, not a lock |
| 10 | Necrotic Novice perception of the living | Necrotic perception of the living | Kept |
| 11 | Contracts by cost-file stage | Cost stage in contracts | Not built |
| 12 | Bands borrowing canon stage names | Cost timescales | Borrowed |
| 13 | Nature wound redistribution | Nature wound redistribution | Wounds move between linked allies |
| 14 | Portal access by registration | Portal access by registration | Registered characters only |
| 15 | Witness law for kills | Witness law for kills | A kill before three witnesses is a bounty record |
| 16 | Necrotic Master killer-naming | Necrotic Master killer-naming | The Master names the killer |

Decisions 13–15 were unnumbered rows in v0.2-draft; decision 16 is new in v0.2.

## Changelog

### v0.1.1, 23 September 2026

Editorial-feedback pass. A simulated review was sorted into signal and noise, each item was checked against the canon by search and targeted reads, and the signal was implemented as surgical edits. Section numbers 1–9 are unchanged. The tag key is in the header.

**Changes by section.**

| Section | Change |
|:--|:--|
| Header | Version line and tag key |
| Contents | Pointer to this Changelog |
| 2, Ethos bullet | Cites Part VI's design principle [C]; the default-not-a-lock rule is tagged [R] against Part VI's ratified list |
| 2, class table | Default ethos column tagged [R] |
| 2, specs paragraph | Specs restated as an adaptation taxonomy. The three splits canon presents itself are cited (Arcane Guru, Divine Master, Elemental Master); the other nine are [A]. Variant count corrected from 24 to 26 |
| 3, Strain | The band-unlock rule is replaced by the redline rule: bands carry penalties only, rank gates techniques, and strain prices them. Design test added |
| 3, Strain | New rule: a cost that canon describes as serving before it harms (Hammer, Dark Arts, Longbow) serves on the cost file, never as an encounter band |
| 3, Strain, cost-file bullet | Cites XI.5 item 3 for the only-forward rule. The Adept-onset quote is tagged [N: Block 3 row 3a]. Stat effects narrowed to minor sidegrades |
| 3, new subsection | Cost file consequences: body, perception, response, contracts [R], and Guru files. Permanent stat loss and offense-adding stages are excluded |
| 3, Boundary | Carried off the field, with no in-fiction death, is replaced by defeat and respawn as a play abstraction that makes no in-fiction claim about survival |
| 4, Artificer band 2 | Near-work bonus removed |
| 4, Paladin bands 1 and 3, timing line | Band 1 stacks grant nothing at encounter scale (v0.1: damage reduction); the conditioning benefit moves to the file. Band 3 adds crit vulnerability (v0.1: the stacks inverted into it). Timing line matched |
| 4, Apostle signature | Part VII clause 2 cited. Years write to the file at each transfer and never refill. The encounter resource becomes transfer tolerance, which refills and restores no lifespan. Tuning assumes no transfers outside Guru-tier operations |
| 4, Ranger band 3 | Perception-radius growth moves to the file. The band keeps unfilterable audio and marks every sound source in range |
| 4, Apothecarist band 3 | Persisting aspect traits carry no bonuses and weaken contact abilities until they fade |
| 4, Necromancer | Novice: canon quote cited [C]; execute-window perception tagged [R]. Guru: canon quote cited; a hold that expires ends in defeat, not death. Harm tools removed; offense is untrained weapon handling plus execute marks. Band 3 slows bare-handed readings (v0.1: weakened contact abilities; the contact harm tool is removed). Band 4 loses its damage reduction |
| 4, Hexblade band 2 | Adaptive resistance removed. Residue scars ache under strain and slow guard recovery |
| 4, Warlock bands 1 and 4 | Band 1: allied draughts and potions weaken on the Warlock, and poison immunity moves to the file (v0.1: immunity in the band). Band 4: attackers are no longer poisoned; the cost to allied casters stays, with Part IV cited |
| 7, the roll | Roll sizing tagged [N: Block 3 row 3a]. The unregistered path is capped per server, and the cap is unpublished (v0.1: unlimited). Part IV cited on the scarcity of unregistered Gurus |
| 7, new paragraph | Guru-scale castings are server events under every Guru option; attribution follows registration |
| 7, default rationale | Restated for the capped path, with the trade each seat makes. Master ends ordinary progression for most characters |
| 7, new note | Open item: the six Guru-only specs need pre-Guru forms |
| 9, rows updated | Necrotic harm, Guru population, Player death |
| 9, rows added | Ethos flexibility, Cost timescales, Necrotic perception of the living, Cost stage in contracts |

**Removed v0.1 text, kept for reversal.** Verbatim. Reinstating the Necromancer tools or the unlimited unregistered path depends on the Necrotic harm and Guru population rows in section 9.

| Location | v0.1 text |
|:--|:--|
| 3, Strain | Each band pairs a penalty with an unlock: stage techniques usable only at or above that band. Paying cost becomes a choice rather than a tax. |
| 3, Boundary | When the timer expires, the character is carried off the field to the nearest settlement with wear added, so player characters never die in-fiction. |
| 4, Apostle | Transfers debit a pool of years that refills between encounters. |
| 4, Necromancer, lead-in | The class's offensive tools are adaptation inventions, not canon: |
| 4, Necromancer, tool 1 | Bare-handed touch that thins a target's boundary: damage taken rises as they near death, and healing received falls. |
| 4, Necromancer, tool 2 | Residue imprints on ground where things died. |
| 7, the roll | Unregistered Gurus are unlimited and off the roll, which matches the Chimera's "whoever stayed unregistered, which is the one number no table gives." They carry the unregistered penalties. |

**Feedback not implemented.**

| Feedback item | Disposition | Reason |
|:--|:--|:--|
| A crossed band makes high-stage techniques cheaper | Not adopted | A discount inside a band rewards entering it, which the redline rule excludes |
| Insurance as a cost-file channel | Not adopted | Canon has no insurance institution. Contracts are kept, as an [R] channel |
| Guru seats reached by seasonal role, appointment, or temporary state | Recorded as an alternative in section 9 | The Guru model is still open; the default keeps the roll and caps the unregistered path |
| Necromancer: prevent healing at the boundary | Not adopted | Harm by another route; Part II gives the school no harm |
| Necromancer: expose trauma; reveal lethal openings | Not adopted | No canon basis; each would be a further invention |
| Necromancer: extend a final action; identify who struck whom; predict a crossing | Already in the kit | Guru holding [C]; Master reading [C]; Novice execute window [R] |
| Ethos option 1: canon locks ethos, and the game's free choice is adaptation-only | Replaced | A free choice would contradict a ratified line, so it cannot be [A]. Reading (a) in section 9 locks ethos in the game instead |
| Suggested wording: two adaptation specs per class | Not used as worded | The Archpriest has four specs, and canon presents three of the splits itself |
| Register row: Specializations | Not added | The section 2 rewrite and the [A] tags cover it; specs assert no world fact |
| Register rows: Refillable Apostle resource; Strain-gated techniques | Not added | Both mechanics are removed. The remaining issue, bands borrowing canon stage names, is the Cost timescales row |
| Register row: Automatic defeat recovery | Merged | Into the Player death row |
| Scope: prove the systems on a vertical slice first | Outside this document | Production planning is outside the brief; the handoff's depth plan already builds one class and one encounter set before the rest |
| Praise and summary verdicts | No action | Nothing to implement |

**Feedback premises corrected.**

- The review cites the cost file's only-forward rule as a canon line. The wording is v0.1's own; the canon line is XI.5 item 3, now cited in section 3.
- The review treats every cost as harm only. Canon describes three costs that serve before they harm: Hammer conditioning, Dark Arts tolerance, and Longbow tuning. Section 3 places that serving phase on the cost file.
- The review treats the Necromancer's view of the living's distance to death as canon practice. Canon's Novice senses places where death happened; the extension is now [R].
- The review says canon sets no sub-disciplines. Canon presents three splits (Arcane Guru, Divine Master, Elemental Master), now cited in section 2.
- The review grounds the ethos coupling in the class matrix, which is pending [N: R.1 item 16]. The ratified basis is Part VI's list, now cited.
- The review's quotation on the unregistered Guru count is a paraphrase. The canon line, from Rank Distribution [N: Block 3 row 3a], is cited in section 7.

**Handoff defects affected.**

| Defect | Status |
|:-:|:--|
| 3 | Closed: 26 variants (section 2) |
| 4 | Open, and more pressing: the capped unregistered path leaves fewer players at Guru (section 7 note) |
| 6 | Superseded: bands carry no techniques. The replacement work is file-scale serving-phase sidegrades |
| 8 | Partly closed: Hexblade adaptive resistance removed; Necromancer execute window tagged [R]. Still untagged: Apothecarist wound transfer, portal access tied to registration, witness-law extension |
| 13 | Closed: unregistered path capped; roll benefits stated |

Unaffected and still open: 1, 2, 5, 7, 9, 10, 11, 12, 14, 15, 16, 17. Handoff decisions whose v0.1 default changed: 1 (Guru model) and 3 (Necrotic harm).

**Quote audit.** Run on v0.1.1 with the handoff's command: 64 quoted fragments checked. Two non-matches, both carried from v0.1: "maximum two full bleeds per volume." (defect 1, open) and "placeholder" (the document's own term). Every quote added in this pass matches the canon, and its attribution was checked against the cited section.

### v0.2-draft, 23 September 2026

Defect pass from the handoff (Terhia-MMORPG-Adaptation-Handoff, with its section 10 addendum). Terhia-Canon.md was not in session, so no canon line was re-read and the quote audit was not run. Canon facts used here come from findings the handoff records. No rulings on decisions 1–12 were given, so every default holds and each affected item is tagged [R]. Section numbers 1–9 are unchanged.

**Changes by section.**

| Section | Change | Defect |
|:--|:--|:-:|
| Header | v0.2-draft version line; canon-read line split by pass; load estimate corrected to measured figures | 17 |
| 1, table | Guru roll figures tagged [N: Block 3 row 3a] | 2 |
| 2, specs paragraph | Pointer to spec branching | 4 |
| 2, power curve | Pointer to NPC baseline supply | 14 |
| 3, layer table | Boundary row renamed Downed state | 10 |
| 3, Strain | Strain defined as a game resource distinct from canon cost | 9 |
| 3, Strain, guardrail | Restated: input-corrupting penalties only in a school's last two bands, 1.5 s cap (placeholder), cue before firing; no band misreports the HUD | 5 |
| 3, new subsection | Cost and strain: terms (cost, cost stage, cost file, strain, band, wear, strain modifier) | 9 |
| 3, Downed state | Mechanic renamed; "Boundary" kept as the default UI label, tagged [R] | 10 |
| 3, Terrain | The walled-ground line replaced with a Ranger and Berserker rule for attacks into walled ground | 15 |
| 3, Counters | List replaced with a beats/loses-to matrix and a dominance check | 16 |
| 3, phase week | Phase-turn truces limited to Renlei homelands | 11 |
| 4, Sorcerer | Read-target discount and rush surcharge tagged [R]. Dilation multipliers tagged [C]; tier values placeholder [A]. Band 3: cast lag replaced with slower cooldown recovery and strain decay. Band 4 placed under the guardrail | 5, 9 |
| 4, Artificer | Flasks made shared kit | 7 |
| 4, Archpriest | Present-material discount and concurrent-works multiplier tagged [R]. Band 4 uses the downed-state timer | 9, 10 |
| 4, Apostle | Paladin-escort line replaced with the Crown column pairing, tagged [N: Force Types] | 2 |
| 4, Berserker | Band 2: HUD thinning replaced with post-gate clearing of target locks, marks, and the gate-period log. HUD test note removed | 5 |
| 4, Apothecarist | Wound transfer and damage spreading tagged [R]. Band 2: ally-frame dimming replaced with attunement-layer loss; party frames stay accurate | 5, 8 |
| 4, Necromancer | Guru holding uses the downed state. Band 2: phantom hit indicators replaced with slower charge gain | 5, 10 |
| 4, Warlock | Potions and draughts made shared kit. Novice draught pauses the downed timer | 7, 10 |
| 4, new subsection | Spec branching: spec rank for all twelve classes; pre-Guru forms for the six Guru-only specs | 4 |
| 6, Law | Menneske kill-witness rule tagged [R] | 8 |
| 6, Registration | Portal access tagged [R] | 8 |
| 6, Economy | NPC baseline supply and price floor | 14 |
| 6, Navigation | Ninth channel tagged [R] | 12 |
| 7, open note | Replaced with a pointer to spec branching | 4 |
| 8, Presentation | Quotation marks removed from the paraphrase; Part X cited | 1 |
| 9, Player death row | Boundary tools renamed downed-state tools | 10 |
| 9, rows added | Strain modifiers beyond phase; Downed-state label; Ninth channel as a route; Nature wound redistribution; Portal access by registration; Witness law for kills | 8, 9, 10, 12 |
| 9, new subsections | Canon dependencies (handoff section 5 plus the section 10 row); Open rulings (decisions 1–12) | — |

**Removed v0.1.1 text, kept for reversal.** Verbatim.

| Location | v0.1.1 text |
|:--|:--|
| 3, Strain, guardrail | Guardrail: penalties that corrupt input or misreport the HUD (cast lag, phantom damage, slot lockouts) stay in the top bands, are short, and are telegraphed. |
| 3, Terrain | Walled ground resists musters. |
| 3, Counters | Hexblade beats casters. Sorcerer beats projectiles and leaps. Paladin beats charges and structures. Vanguard beats rushes and dives. Ranger beats approaches over open ground. Necromancer beats stealth kills and targets that depend on heals. Artificer beats stealth and holds chokepoints. Warlock beats healers who rely on cleansing: its antidotes are ones "no one else can check." Apostle beats fear and chains of crowd control. Berserker beats burst windows and fear. Archpriest beats static positions. Apothecarist beats stacked wounds and beast adds. |
| 3, phase week | Phase-turn days are server-wide market truces. |
| 4, Sorcerer band 3 | Time-lag: longer cast times. |
| 4, Apostle | That makes the healer the group's scarcest resource, and the Paladin escort the canon pairing. |
| 4, Berserker band 2 | Frenzy amnesia: the HUD thins during the gate. |
| 4, Berserker | HUD thinning has to keep critical signals readable; test it early. |
| 4, Apothecarist band 2 | Sensory narrowing: the attunement radius shrinks and distant ally frames dim. |
| 4, Necromancer band 2 | Death residue sensation: subtle phantom hit indicators. |
| 7, open note | Open: six specs exist only at Guru (Sorcerer, Vanguard, Artificer, Berserker, Apothecarist, Necromancer). Under any capped model most players of those specs never reach them, so each needs a pre-Guru form, shaped by the Guru ruling (section 9). |
| 8, Presentation | That is the game's version of "maximum two full bleeds per volume." |

**Handoff defects.**

| Defect | Status after v0.2-draft |
|:-:|:--|
| 1 | Closed: quotation marks removed. Confirm the Part X citation in the canon pass |
| 2 | Partly closed: Apostle pairing fixed, Guru roll figures tagged. The sweep of every uncited canon claim is owed: 50 lines mention canon without a tag |
| 3 | Closed in v0.1.1 |
| 4 | Closed: spec ranks set, pre-Guru forms defined for all six. How many players see the Guru form depends on decision 1 |
| 5 | Closed: guardrail restated; Sorcerer, Necromancer, Berserker, and Apothecarist bands comply |
| 6 | Superseded in v0.1.1; the replacement is depth item 2 |
| 7 | Closed: flasks and potions are shared kit |
| 8 | Named items closed: wound transfer, portal access, and witness law tagged [R] and registered. Tagging of every kit and system element is owed to the canon pass |
| 9 | Closed pending decision 2: glossary added; modifiers tagged [R] and registered |
| 10 | Closed pending decision 6: mechanic renamed; label registered |
| 11 | Closed: Renlei homelands only. Section citation owed |
| 12 | Closed pending decision 7: tagged [R] and registered |
| 13 | Closed in v0.1.1 |
| 14 | Closed: NPC baseline supply and price floor |
| 15 | Closed: class rule for walled ground |
| 16 | Closed: matrix with dominance check |
| 17 | Closed: header load figures measured on this file |

**Canon checks owed.** Required before the version reads v0.2. Load per the handoff: grep, plus R.0 and R.1 for statuses.

1. Quote audit with the handoff's command, pointed at this file. Expected non-matches: the document's own terms (placeholder, Boundary, if canon lacks it) and the verbatim record of defect 1 in the removed-text table. Log the result here.
2. Defect 2 sweep: check each uncited canon claim against its section and tag it [C] or [N].
3. Tag every kit and system element [C] or [A]; move anything that implies a world fact to [R].
4. Canon dependencies: confirm each row's status in R.0 and R.1, and locate the four items marked to locate.
5. Citations added in this pass without a checked section: the Renlei phase-turn truce custom; the location of the 11 September 2026 phase-only ratification; the Force Types column pairing; the Arcane Guru dilation parameters; Part X's full-bleed limit; Part II, Elemental Master for spec formalization.
6. Register rows citing canon positions from the handoff (Nature wound redistribution, Portal access by registration, Witness law for kills): confirm each canon position.

**Quote audit.** Not run: canon not in session. The only quotation added in this pass is "could not take a walled town", reused from section 2, where v0.1.1's audit matched it.

### v0.2, 23 September 2026

Canon pass against Terhia-Canon.md v1.1, with the canon in session (read list in the header). It closes the six canon checks v0.2-draft owed. Where the text misstated canon, it is corrected in place; where a mechanic rests on an extension, it is tagged and registered. No decision was taken for Joe: every default holds, and findings that bear on an open decision are written into its register row. Section numbers 1–9 are unchanged.

**Changes by section.**

| Section | Change | Canon basis |
|:--|:--|:--|
| Header | v0.2 version line; canon-read line for v0.2; load figure measured; tag key extended for [V] sources and for craft and in-world registers | Front matter, "How to read this file" and "Registers" |
| 1 | "Numbers are records" tagged | D6, Block 2 |
| 2, class table | Working terms matched to the Terminology table: Sword/Shield is "escort; counter-practitioner work" ("escort of record" is the Unsworn contract phrase); Necrotic adds "reader" | Part VI, Terminology |
| 2, role coverage | Accord: "its creed" replaced; canon gives the line as a critique and states that the Accord has no creed. Chimera: the quote attributed to rangers and berserker bands, cited | Part II, Nature; Part VI, Ethos Statements; Part IX, Antler War |
| 3, glossary | Phase-only line: "ratified" corrected to "design decision, not a ratification item", located | Part I, Substrate and Nodes; R.1 item 25 |
| 3, cost file | Reading the file aloud re-sourced to Part IX [C] (was [N]). Guru files scoped to the Ledger's roll, the extension tagged [A] | Part IX, Second Register; Part II, Rank Distribution |
| 3, formation | Hammer stat carries its calibration word, "breakage", so it no longer shares Sword/Shield's "structure" | Part III, Hammer Guru |
| 3, terrain and counters | Walled-ground rule sourced to the Antler War. Necromancer–Ranger edge tagged [R] | Part IX, Antler War |
| 3, phase week | Velquor: Appendix D's Guru-tier risings in Namaris, Threnis, and Saelura added, so Velquor is the strongest window, not the only one. Orrivane: "Ledger rates published" made specific (the rank roll; exchange rates publish at every phase turn); examinations tagged [A]. Renlei truce and Shalei/Mwamba cited | Appendix D; Part II, Rank Distribution; Part V, Money; Part V, Renlei |
| 3, seasons | "Canon states no seasons" corrected: canon names winters, summer, the dry season, and a phase-length warding season, and Solvør fits a winter solstice at 1 Velquor for Isavík | Part III, Sword/Shield and Hammer payloads; Part V, Menneske; Part V, Anchor Prices; Part VII, God Register |
| 4, all kits | Kit convention added: rank bullets [C] for the ability named, mechanics [A], band names [C], band effects [A], extensions tagged individually | Parts II–IV |
| 4, Sorcerer | Dilation citation confirmed. Gravity pre-Guru form tagged [A] against the Novice "light objects" line | Part II, Arcane |
| 4, Artificer | Familiar role split and beetle plating tagged [A]; canon gives all three frames the same duties | Part IV, Light Arts Adept |
| 4, Paladin | Terrain line cited | Part III, Hammer; Part IX, Antler War |
| 4, Apostle | No-free-heal rule re-sourced to Part II's ability list (world register); Part VII clause 2 kept as the Crown's in-world statement. Adept stamina and bleed effects tagged [A]. Crown column tagged [C] (a view of ratified text) | Part II, Divine; Part VII, register line; Part VI, Force Types |
| 4, Necromancer | Adept corrected to canon's "general impression without specifics" (the "class of cause" is removed). Master killer-naming tagged [R] and registered; "twice named a killer" tagged [N] | Part II, Necrotic; Part IX, 1163 and 1211; R.1 item 14 |
| 4, Hexblade | Residue scars shown by texture, not school color: school color leaves with the casting, which section 8's color rule also adopts | Part X, culture palette cross-reference |
| 4, Warlock | Guru antidotes: canon says no one else can check them; "only the Warlock can administer" is kept as an [A] mechanic | Part IV, Dark Arts Guru |
| 5 | Shalei arc corrected from two weeks to three (Threnis, Velquor, Saelura). Reading rise re-sourced to the Three Readings (it is not residue). Puketai marked as a biome effect; Appendix D displacement methods added | Part IX, 1155 and 1224; Part I, Three Readings; Appendix D |
| 6, territory | Crown claims: the Assay voids benefice resting on a fraudulent miracle claim, not deeds. Chimera claim rule cited | Part VI, Indigo Assay; Part IX, 1226; Part V, Tangata |
| 6, contract warfare | Marendi rule narrowed to what canon records: Unsworn companies, in view of both principals, contract satisfied for the day | Part IX, 1184; Part VI, Force Types |
| 6, practice legality | Necrotic practice is registered in Accord territory, and only its testimony is inadmissible; enforcement there targets unregistered practice. Nature's proscription extended to "reverie generally", with a pointer to decision 9 | Part II, Necrotic institutional role; Part VII, clause 5 |
| 6, economy | Harbors: only ice harbors depend on a leased Guru. Mint and phase-pricing lines tagged | Part I, Transport; Part V, Money; Phase Cascade |
| 6, navigation | Rotokere matched to Appendix C: three competing tales, none recited | Appendix C, item 3 |
| 7 | Board reading cited. The cost-gated legacy mechanic scoped to Yamana characters, matching section 2's culture-feature rule | Part IX, Second Register; Part V, Yamana |
| 8 | Saelura and Longest Night lighting tagged [N]; lamp-amber scoped to the Menneske. Wear-layer scars textured, not colored. Full-bleed citation located | Part V, Material Signatures and Menneske; Part X |
| 9, register | Rows corrected: Seasons, Crafting, Names and words (coin names sit in Money, not Naming and Address), Strain modifiers beyond phase, Portal access, Witness law, Nature wound redistribution. Ethos flexibility and Cost timescales gain canon evidence. New row: Necrotic Master killer-naming | As cited in each row |
| 9, dependencies | Every row located and confirmed pending; Force Types corrected to a view with two pending parts; seven rows added (Three Readings split out, airship propulsion split out, Terminology, Design Thesis, numbers are records, Necrotic institutional role, Residue, Ledger hours) | R.0; R.1 |
| 9, open rulings | The three unnumbered rows numbered 13–15; decision 16 added | — |

**Canon checks owed by v0.2-draft.**

1. Quote audit. Run on sections 1–9 and the header with the handoff's method (normalized substring match against the canon): 84 quoted fragments, one non-match, "placeholder" (the document's own term). Attribution was checked for every quote added or moved in this pass. Closed.
2. Uncited canon claims. Closed as a sweep of sections 1–8 read against their sources, not as a line count: every claim found wrong, pending, or drawn from a craft or in-world source is corrected or tagged (table above). Statements that restate ratified canon and name their Part in the sentence were left untagged.
3. Tagging of kit and system elements. Closed by the kit convention (section 4) plus individual tags on every extension found.
4. Canon dependencies. Closed: all rows located in R.0 and R.1 and confirmed pending; seven rows added.
5. Unchecked citations. Closed: Renlei truce (Part V, Renlei, Ritual); phase-only line (Part I, Substrate and Nodes; a design decision, not a ratification); Crown column (Part VI, Force Types, a view); Arcane dilation (Part II, Arcane Guru); full-bleed limit (Part X, Panel Compression Scale); Elemental specialization (Part II, Elemental Master: specialization "becomes pronounced" at Master; the spec table's "formalized" is replaced with canon's word).
6. Register rows from the handoff. Closed: Nature wound redistribution, Portal access, and Witness law each confirmed against canon, with the canon position reworded where the handoff's wording was loose.

**Findings for Joe's open decisions.** Each is written into its register row; no default changed.

- Decision 2 (strain modifiers). The phase-only line was decided against node activity, and canon's own Arcane and Elemental lines vary cost with output. Read at that scope, only the Archpriest present-material discount conflicts with it.
- Decision 9 (ethos lock). Two canon lines bear on reading (b): the Purge list's "Hexblades and Warlocks of no institutional charter" and "adherents of every ethos" in every homeland (Part IX).
- Decision 12 (band names). Elemental collapse is death in canon and identity-time fracture ended a Guru's practice; both name recoverable bands here.
- Decision 16 (new). Canon's recorded killer-naming is Guru holding; the Master version is an extension.

**Canon-side findings for Terhia-Canon.md.** Not adaptation defects; listed for a canon session, as R.5 candidates.

- The Premise says everyone is born with one magic or martial school. Part IV calls Light and Dark Arts "arts", and Part VI lists Artificer and Warlock as classes with the shared ladder. No line says whether an alchemist was born with a school, and which.
- The phase-only decision reads "casting cost varies with moon phase only" while Part II's Arcane Guru line multiplies cost by ratio, radius, and duration. The decision's own example shows its scope is node activity; one clarifying clause would close the gap.

**Context note.** This pass loaded most of the canon (about 45k tokens of its 61k) plus this file. Follow-up work on the open decisions does not need the full canon: load this file with R.0, R.1, and the Part each decision cites.
