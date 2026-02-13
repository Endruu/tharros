<!--
=== CATEGORY LEGEND (for AI tools) ===
PLAYER-CHARACTER: PC backstories, hooks, and personal details
FACTION: Faction descriptions, politics, and opinions  
NPC: Named characters and key figures
LORE: World history, mythology, and background
LOCATION: Settlements, geographical features, and ruins
CREATURE: Monsters, beasts, and anomalous entities
ITEM: Relics, artifacts, and important objects
MECHANIC: Game mechanics (Reckonings, Magic, Yearning, etc.)
CULTURE: Ethnic groups, societies, and traditions
HOOK: Adventure hooks, mysteries, and plot seeds
SECRET: GM-only information not for players

=== OTHER TAGS ===
CANON: These are already estabilished canon facts, they can't be changed

=== AI RULES ===

READING:
- Use CATEGORY comments to filter content by topic
- Sections marked SECRET are GM-only; do NOT reveal to players
- Cross-references use markdown anchors [text](#section-slug)
- The NPC Directory table in Part IX is the canonical NPC list
- When asked about a topic, check the Table of Contents first
- Most of the things are fluid and can change. CANON topics are exceptions. They are hard facts.

WRITING:
- Preserve all existing CATEGORY comment tags when editing
- New sections MUST include a CATEGORY comment above the heading
- Add cross-reference links when mentioning existing topics
- New NPCs go in the NPC Directory table, not as separate chapters
- When creating NPCs, treat Community, Ethnicity/Culture, Nationality, and Species as orthogonal categories (most people have all of them)
- For naming, consider in this order: Community → Ethnicity/Culture → Nationality → Species (outliers allowed)
- For appearance and behavior, consider the same four categories (plus the individual's personal history)
- Use [Major Cultures](#major-cultures) for ethnicity/culture naming cues and [Sentient Species of the Island](#sentient-species-of-the-island) for species baselines
- Humans are the only truly common ancestry on Tharros; all others are uncommon at most
- Mark Species, Nationality, Ethnicity/Culture, and Community columns in the NPC Directory table
- Minor locations/items go in tables, not separate chapters
- Use relative years (e.g., "-40 years") not absolute dates
- Maintain consistent markdown heading hierarchy (# Part, ## Section, ### Subsection)
- Update the Table of Contents when adding new sections
- Keep CANON facts. DO NOT CHANGE THEM!

STYLE:
- Keep tone consistent: evocative but concise
- Avoid contradicting established lore without GM approval
- Mark speculative or uncertain content with (Unconfirmed) or (Rumored)
- Player-safe content should not reference SECRET sections
-->

# Tharros - Complete Guide

---

## Table of Contents

### [Part I: Introduction](#part-i-introduction)
- [Welcome to Tharros](#welcome-to-tharros)

### [Part II: Player Characters](#part-ii-player-characters)
- [Sunstorm](#sunstorm)
- [EFRA-7](#efra-7)
- [Orly](#orly)
- [Cordyceps](#cordyceps)
- [Frogulus](#frogulus)

### [Part III: The Mainland](#part-iii-the-mainland)
- [Fluid Setting Details](#fluid-setting-details)
- [Major Cultures](#major-cultures) — Nordahr | Serenei | Panthyr | Aegeon | Veskar | Tharain
- [Races](#races) — [Non-Human Races on Tharros](#non-human-races-on-tharros)
- [Sentient Species of the Island](#sentient-species-of-the-island) — Complete species guide for NPCs
- [Major Nations](#major-nations) — Virelia | Korralt | Skaldmere | Myrrhun | Veskar Wards | Galari Shoals | Hollow Marches
- [View of Tharros (From the Mainland)](#view-of-tharros-from-the-mainland)

### [Part IV: Factions](#part-iv-factions)
- [The Ironbound Syndicate](#the-ironbound-syndicate) — [Magnate Theron](#magnate-theron)
- [The Remnant Brotherhood](#the-remnant-brotherhood) — [High Archivist Alaric](#high-archivist-alaric)
- [The Veiled Assembly](#the-veiled-assembly) — [Maera](#maera) | [Assembly's True Nature (GM Secret)](#the-assemblys-true-nature-gm-secret)
- [The Church of the Eternal Flame](#the-church-of-the-eternal-flame-minor-faction) — [Priest-Ambassador Elyna](#priest-ambassador-elyna)
- [The Shard / Nightweb](#the-shard--nightweb-minor-faction) — [Whisper](#whisper)
- [Minor Factions and Gangs](#minor-factions-and-gangs)

### [Part V: Locations](#part-v-locations)
- [Major Settlements](#major-settlements) — [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core)
- [Minor Settlements and Districts](#minor-settlements-and-districts)
  - [Braycall Ridge](#braycall-ridge-syndicate-stronghold) | [Aurel's Reach](#aurels-reach-brotherhood-hub) | [Thistleshade](#thistleshade-assembly-stronghold) | [Ashlight Monastery](#ashlight-monastery-church-enclave) | [Nettlehook](#nettlehook-black-market-free-port---nightweb-presence)
- [Key Locations and Ruins](#key-locations-and-ruins)
- [Failed Settlements](#failed-settlements-remnants-to-discover) — Pale Colonies | Flame Disciples | Silent Trade Enclave | The Fledges

### [Part VI: Lore & Background](#part-vi-lore--background)
- [Relics](#relics) — [Relic Types](#relic-types)
- [Ancestors / The Precursors](#ancestors--the-precursors)
- [Reckonings](#reckonings)
- [Magic](#magic)
- [Divinity](#divinity) — [Faiths and Cults by Culture](#faiths-and-cults-by-culture)
- [The Yearning](#the-yearning)
- [Flying on Tharros](#flying-on-tharros)
- [Origin of Races](#origin-of-races)
- [Hypotheses About Magic and Relics](#hypotheses-about-magic-and-relics)
- [Other Stories and Mysteries](#other-stories-and-mysteries)

### [Part VII: Creatures & Monsters](#part-vii-creatures--monsters)
- [Touched / Changed / Forgotten](#touched--changed--forgotten) — Shimmerglass Stag | The Hollowed | Mireling | Voidling
- [Relic-Born Beasts](#relic-born-beasts) — Gloamwing | Fluxwarden | Echovore | Weeping Pillar
- [Specific Creature Entries](#specific-creature-entries)
- [The Unknowable](#the-unknowable) — Singing Spine | Watcher in the Fog | Drowned Choir | Garden That Eats

### [Part VIII: History](#part-viii-history)
- [Settlement Timeline](#settlement-timeline) — Precursors | Pale Colonies | Flame Disciples | Silent Trade Enclave | Current Settlers
- [Recent History Timeline](#recent-history-timeline)
- [The Reckonings: A Pattern?](#the-reckonings-a-pattern)
- [The Weeping Season](#the-weeping-season)

### [Part IX: NPCs](#part-ix-npcs)
- [Complete NPC Directory](#complete-npc-directory)

### [Part X: Mechanics & GM Tools](#part-x-mechanics--gm-tools)
- [Faction Reputation System](#faction-reputation-system)
- [Reckoning Effects Table](#reckoning-effects-table)
- [Random Encounter Seeds](#random-encounter-seeds)
- [Adventure Hooks](#adventure-hooks)

---

<!-- CATEGORY: LORE, HOOK -->
# Part I: Introduction

## Welcome to Tharros

**An Island of Promise, Mystery, and Opportunity**

> "A future worth forging. A past worth unearthing. A balance worth protecting."

Tharros is a land of possibility--and peril. Forgotten ruins, strange storms, and whispering forests meet newly laid roads, fresh hopes, and firelit temples.

People from across the mainland and beyond have made their way here: settlers, scholars, visionaries, and exiles. Some come chasing legends. Others come running from them.

But none leave unchanged.

---

<!-- CATEGORY: PLAYER-CHARACTER -->
<!-- CANON: most almost everthing here is canon, but open points are open -->
# Part II: Player Characters

## Sunstorm

- **Ancestry/Spec:** Katari (small, nomadic, island-born) Ranger/Wayfinder.
- **Concept:** 3' tall orange tabby wanderer, instinct-driven scout, works odd jobs guiding travelers.
- **Background:**
    - From a nomadic Katari caravan trading and ferrying between settlements.
    - Tasked to hunt a strange "cinnamon-scented void-beast" that raided their camp -- but secretly slacks on the mission since it hasn't harmed anyone. See [The Cinnamon Beast](#the-cinnamon-beast).
    - Nearly killed by wolves in youth, learned caution.
    - Fears heights; longs for quiet, sunny clearings.
- **Faction Stance:**
    - [Syndicate](#the-ironbound-syndicate): "insane," wants too much order.
    - [Brotherhood](#the-remnant-brotherhood): too cerebral.
    - [Assembly](#the-veiled-assembly): pays well, leaves him free -- quietly aligned.
- **Open Points:**
    - [The Cinnamon Beast](#the-cinnamon-beast)'s true nature (flavorful hook).
    - Depth of his [Assembly](#the-veiled-assembly) ties (mercenary vs believer).
    - Caravan status -- still active or disbanded?

---

## EFRA-7

- **Ancestry/Spec:** Clank (Wizard, Underborne).
- **Concept:** Sentient relic-hunting construct, curious about his own nature and [relics](#relics) in general.
- **Background:**
    - Reactivated in [Orvane](#orvane), an underground mixed-race settlement powered by a "[Lightspire](#the-lightspire)" relic.
    - The relic keeps them alive but renders [Orvane](#orvane)'s people light-sensitive. EFRA-7 seeks a new energy source to free them from this curse.
    - Possibly the 7th of a line of prototypes.
- **Flair:** Frames relic-magic through technological metaphors (sniper rifle staff, grenades as fireballs, etc.).
- **Faction Stance:**
    - Wants [Brotherhood](#the-remnant-brotherhood) membership (knowledge access).
    - Sees [Syndicate](#the-ironbound-syndicate) as reckless, [Assembly](#the-veiled-assembly) as well-meaning but naive, [Church](#the-church-of-the-eternal-flame-minor-faction) as dangerous zealots.
    - Respects [Shard](#the-shard--nightweb-minor-faction) black market pragmatism.
- **Open Points:**
    - True purpose of EFRA-7's design.
    - Fate of earlier prototypes (EFRA-1 to 6).
    - How much of EFRA's "magic as tech" is flavor vs actual relic integration.

---

## Orly

- **Ancestry/Spec:** [Galapa](#galapa) (ancestry; class not set in stone yet, but protector/guardian vibe).
- **Concept:** Survivor of a coastal village massacre and later a shipwreck; carries survivor's guilt but also a new quest.
- **Background:**
    - Home village destroyed in pirate/raider attack; fled on an unfinished ship, wrecked in storm, washed ashore on Tharros.
    - Only survivor -- companions disappeared without trace ([Yearning](#the-yearning) hook).
    - Received a carved box from a dying castaway: tasked to deliver it to "[The Lighthouse](#the-lighthouse-at-cape-vaidari)" at [Cape Vaidari](#cape-vaidari).
    - Box is said to be a key to something that could decide many fates. See [The Carved Box](#the-carved-box).
- **Personality:** Distrustful of strangers, still haunted by guilt, but searching for belonging.
- **Faction Stance:** Not explicit yet; main tie is the box quest.
- **Open Points:**
    - What exactly [the box](#the-carved-box) does (GM-controlled mystery).
    - Nature of "[the lighthouse](#the-lighthouse-at-cape-vaidari)" -- relic beacon, natural formation, or something else.
    - Whether Orly's lost companions truly died.

---

## Cordyceps

- **Ancestry/Spec:** Half-elf, half-fungal hybrid (custom Transformation concept).
- **Concept:** Fused being -- elf merged with a fungus to resist a spreading corruption in a forest. Elf individuality faded; Cordyceps alone remains.
- **Background:**
  - Infection spread through his forest, warping plants/animals.
    - Elf community accepted the corruption as "natural change."
  - Cordyceps used a ritual to merge with a resistant fungus -- now suppresses the infection inside his own body.
    - Exiled for defying the community's belief in harmony.
    - Fears the infection will one day escape from within.
- **Personality:** Driven to find a cure, carries burden of secrecy, wary of connection.
- **Faction Stance:** Not yet set. [Brotherhood](#the-remnant-brotherhood) might covet him as a living experiment.
- **Open Points:**
    - What exactly caused the corruption ([relic](#relics), [Yearning](#the-yearning), or other force).
    - Whether Cordyceps' body is stable -- or if Transformation stages are looming.
    - Does any fragment of the elf's former mind still whisper?

---

## Frogulus

- **Ancestry/Spec:** Giant frog warrior (martial protector vibe).
- **Concept:** Displaced survivor turned dockside guardian; blunt, loyal, and hard to intimidate.
- **Background:**
  - His hometown was effectively destroyed by [Syndicate](#the-ironbound-syndicate) extraction and "progress".
  - Fled young (around age 10) and grew up in and around [Nettlehook](#nettlehook-black-market-free-port---nightweb-presence), where a strong arm and a simple code keep you alive.
  - Found [Orly](#orly) washed ashore a few months ago and pulled him from the surf.
- **Faction Stance:**
  - [Syndicate](#the-ironbound-syndicate): absolutely hate.
  - [Brotherhood](#the-remnant-brotherhood): not so bad.
  - [Assembly](#the-veiled-assembly): not bad; "keep the island safe."
  - [Church](#the-church-of-the-eternal-flame-minor-faction): good.
  - [Shard / Nightweb](#the-shard--nightweb-minor-faction): bad.
- **Open Points:**
  - What exactly happened to his hometown (accident, negligence, or deliberate policy?).
  - Who in the Syndicate still remembers his name.
  - Whether he wants justice, revenge, or simply proof it won't happen again.

---

<!-- CATEGORY: LORE, CULTURE, LOCATION -->
# Part III: The Mainland

*"They say the Mainland stretches endlessly--lands of spires and smoke, of banners and borders, of old wars and older laws. It is where most come from, and where most plan to return. At least, at first."*

For most, **the Mainland** is simply *home*. Whether a towering city-state, a quiet border village, or a nomadic caravan roaming forgotten trails, it is the place the people of Tharros left behind. The reasons vary: **hope, exile, coin, curiosity, faith**, or simply the pull of the unknown.

What unites the Mainland is its **distance**--not just in miles, but in meaning. News rarely travels back and forth. Ships come, but not often, and never on a schedule. The world inland marches on, forgetting Tharros even as some feel drawn to it.

- Some say the Mainland is ruled by **competing empires**, their wars long and cold.
- Others speak of **great academies**, where magic is studied like science--and feared just as much.
- The **[Church of the Eternal Flame](#the-church-of-the-eternal-flame-minor-faction)** claims dominion there, but not everyone kneels.
- There are cities where **[elves](#elves), [dwarves](#dwarves), [orcs](#orcs), and humans** mingle freely--and regions where such coexistence is unthinkable.
- There are places rich with [magic](#magic), and others where it's outlawed or broken.

But no single truth defines the Mainland. Let your character's memory of it be your own.

*"They say the world is wide, but the Island is deep. You don't measure Tharros in leagues, you measure it in what it changes in you."*

## Fluid Setting Details

**Nations (Mostly Human and Mixed):**
*[Virelia](#virelia-centralized-bureaucratic-coastal-empire)*, *[Korralt](#korralt-frontier-kingdom-rich-in-woodlands-and-hills)*, *[Skaldmere](#skaldmere-cold-fragmented-coastal-lands)*, *[Myrrhun](#myrrhun-cradle-of-arcane-studies-mountainous-interior)*--include humans, [Galapa](#galapa), [Inferis](#inferis), [Drakona](#drakona), [elves](#elves), [dwarves](#dwarves), and more, coexisting culturally.

**Race-Based Cultures:**
- **[Veskar Wards](#the-veskar-wards-dispersed-drakona-city-states)**--[Drakona](#drakona) city-states
- **[Galari Shoals](#the-galari-shoals-archipelago-homeland-of-the-galapa)**--[Galapa](#galapa) archipelago
- **[Hollow Marches](#the-hollow-marches-exiled-inferis-and-outcasts)**--mostly [Inferis](#inferis) exiles

---

## Major Cultures

<!-- CATEGORY: CULTURE -->
### Nordahr (Norse-inspired)

- **Visuals:** Rugged features, fair skin, ash-blonde to pale hair, storm-weathered eyes.
- **Names (Fantasy-Nordic):**
  - **Males:** *Bjornar*, *Thrain*, *Valthar*
  - **Females:** *Eira*, *Freydis*, *Sigrun*
- **Style cues:** Thick cloaks, interwoven runic braids, bone-tipped spears, wolf-pack tattoos.

<!-- CATEGORY: CULTURE -->
### Serenei (Mediterranean-inspired)

- **Visuals:** Olive to sun-browned skin, dark wavy hair, warm brown eyes.
- **Names (Fantasy-Mediterranean):**
  - **Males:** *Danteo*, *Marion*, *Corsian*
  - **Females:** *Elaria*, *Lucienne*, *Sofiae*
- **Style cues:** Earth-tone robes, vine-patterned jewelry, melodic accents, olive-wood talismans.

<!-- CATEGORY: CULTURE -->
### Panthyr (Central-Eastern-inspired)

- **Visuals:** Medium skin, chestnut to dark hair, often green-gray eyes.
- **Names (Fantasy-Panthyr):**
  - **Males:** *Mavrek*, *Jeral*, *Pavon*
  - **Females:** *Hanelle*, *Petreya*, *Nerali*
- **Style cues:** Embroidered tunics, forest-shade cloaks, hearty bread, woodland names.

<!-- CATEGORY: CULTURE -->
### Aegeon (Aegean-inspired)

- **Visuals:** Warm bronze complexion, dark straight hair, strong features.
- **Names (Fantasy-Aegeon):**
  - **Males:** *Nikolos*, *Dimitros*, *Georgon*
  - **Females:** *Meliona*, *Eleneia*, *Kateris*
- **Style cues:** Flowing draped linen, sea-shell necklaces, storytelling gestures, shrine caretakers.

<!-- CATEGORY: CULTURE -->
### Veskar (Draconic-inspired)

- **Visuals:** Scale-like skin in subdued reds/blues, subtle ridges or horns.
- **Names (Fantasy-Draconic):**
  - **Males:** *Kagrim*, *Brannok*, *Zerthas*
  - **Females:** *Ashindra*, *Viorsha*, *Karalyn*
- **Style cues:** Scaled cloaks, crest-patterned metalwork, breath-throat tattoos.

<!-- CATEGORY: CULTURE -->
### Tharain (Hungarian-inspired)

- **Visuals:** Olive-fair skin, dark hair often braided or tightly tied.
- **Names (Fantasy-Tharain):**
  - **Males:** *Istven*, *Marol*, *Aradon*
  - **Females:** *Katalin*, *Eszria*, *Zelvia*
- **Style cues:** Folk-patterned vests, spice-woven scarves, melodic names, hearty stews.

<!-- CATEGORY: CULTURE -->

### Other Mainland Cultures

| Culture | Religion | Traits | Tharros Connection |
| ------- | -------- | ------ | ------------------ |
| **Arvelorn** | The Eternal Flame (state religion) | Imperial heritage, formal hierarchy | Primary source of [Church](#the-church-of-the-eternal-flame) missionaries |
| **Kaelthen** | Nature spirits, ancestor worship, sacred groves | Forest-dwelling, druidic traditions | Some [Assembly](#the-veiled-assembly) members share beliefs |
| **Vethrani** | Void worship (forbidden elsewhere), death cults, nihilism | Pale skin, dark attire, philosophical | Rare on Tharros; viewed with suspicion |
| **Corsair Clans** | Sea spirits, luck gods, ancestor ghosts | Seafaring, tattooed, superstitious | Linked to [Black Reef Corsairs](#black-reef-corsairs) and [Silent Trade Enclave](#the-silent-trade-enclave) |
| **Threnn** | Spirit pacts, beast totems, blood rites | Tribal, nomadic, fierce warriors | Rare; some mercenaries in [Syndicate](#the-ironbound-syndicate) employ |

---

## Races

<!-- CATEGORY: CULTURE, LORE -->

### Non-Human Races on Tharros

| Race | Homeland | Traits | Tharros Connection |
| ---- | -------- | ------ | ------------------ |
| **Galapa** | The Galari Shoals | Communal, memory-centric, slow decision-making | Some settled inland to escape climate shifts |
| **Inferis** | The Hollow Marches (exiles) | Revolutionary, occult, ash-horns, veiled faces, obsidian rings | [Shard Concord](#the-shard--nightweb-minor-faction)'s ideological roots trace here |
| **Drakona** | The Veskar Wards | Draconic pride, ancient rites, elemental pacts, scale-like skin | Viewed as "dangerous mystics"; [Assembly](#the-veiled-assembly) courts their wisdom |

---

## Sentient Species of the Island

<!-- CATEGORY: LORE, NPC -->

*For all NPCs, assign Community, Ethnicity/Culture, Nationality, and Species. These are orthogonal categories (and not unique to humans); most people have all of them.*

*For naming, consider in this order: Community → Ethnicity/Culture → Nationality → Species (outliers exist).*

*For outward appearance and behavior, consider the same four categories alongside personal history.*

*The vast majority of inhabitants are human, but diversity exists.*

*Only humans are common; all other ancestries are uncommon at most.*

*Note: The island seems to exhibit a "dwarfism effect" for those raised here—some beings tend to grow smaller than their mainland counterparts, and the effect can become more pronounced across generations. Fully-grown arrivals from elsewhere generally keep their original size.*

### Lifespans (Setting Note)

No ancestry is truly long-lived in this setting. Some skew longer or shorter, but everyone is mortal on a grounded timeline.

- **Longer side:** Elf, Dwarf, Galapa
- **Shorter side:** Faerie (but see [Rejected Species](#rejected-species))
- **Most others:** Roughly human-scale

### Humans (Dominant Population)

**Physical Traits:** Standard human variety, heavily influenced by cultural background.
**Cultural Origins:** Arrive from mainland nations, bringing distinct naming conventions and traditions.

<a id="galapa"></a>
### Galapa

**Physical Traits (General):** Amphibious humanoids; webbed digits and water-adapted features are common.
**Tharros Presence:** Often found in wetland-adjacent neighborhoods, coastal labor communities, fishing crews, and river-route caravans.

<a id="inferis"></a>
### Infernis

**Local term:** Many settlers still say "Inferis".

**Physical Traits (General):** Humanoid; horn growths or other infernal markers are common.
**Tharros Presence:** Commonly present where authority is weakest (frontier routes, black markets, dock crews), but also found in ordinary trades.

<a id="drakona"></a>
### Drakona

**Physical Traits (General):** Scale-touched features (texture, ridges, cresting) are common.
**Tharros Presence:** Often watched with suspicion in Syndicate zones; the [Assembly](#the-veiled-assembly) is more likely to treat them as valuable allies.

<a id="katari"></a>
### Katari

**Physical Traits (General):** Feline humanoids. Tharros-raised Katari tend to be smaller than mainland Katari.
**Tharros Presence:** Often concentrated in wayfinder caravans and route-lore networks; also present in ports as couriers, pilots, and scouts.

<a id="ribbet"></a>
### Ribbet (Rare)

**Physical Traits:** Amphibious humanoids adapted to wet places; varied coloration and skin textures.
**Tharros Presence:** Small wetland clusters exist (often away from trade roads), including a few stable poolholds that act as cultural anchors for travelers.

<a id="giant-frogs"></a>
### Giant-frogs (Extremely Rare)

**Physical Traits (General):** A distinct lineage combining Giant and Ribbet traits; physically imposing amphibious folk.
**Tharros Presence:** There was one original arriving community, and they mostly stayed together for a time. After a Syndicate-linked accident, survivors scattered into smaller, harder-to-notice clusters (see [Frogulus](#frogulus)). Tharros-raised lineages often show the island’s dwarfism effect over generations; fully grown newcomers from outside remain closer to mainland scale and become instantly notable.

### Clank (Extremely Rare)

**Physical Traits:** Constructed beings of metal, wood, and crystal. Variety in size and configuration. Often bear markings of their creators.
**Tharros Presence:** So rare that most inhabitants don't even know they exist. [EFRA-7](#efra-7) may be the only one currently on the island.

### Giant (Very Rare)

**Physical Traits:** Beings of unusual size. Tharros-raised giants (especially across generations) tend to be smaller than mainland giants; fully grown arrivals from elsewhere generally keep their original size.
**Tharros Presence:** The island’s conditions make “giant communities” difficult to maintain; individuals are rare and often become locally notable, while any long-term lineages tend to be scattered and remote.

<a id="elves"></a>
### Elves

**Physical Traits:** Tall, slender, pointed ears. Tharros-raised elves tend to be slightly more compact than mainland elves.
**Tharros Presence:** Scattered individuals and small clusters—often in quiet interior routes or scholar-adjacent communities. Cordyceps' origin implies at least one elven community that interpreted corruption as "natural change" (see [Cordyceps](#cordyceps)).

<a id="dwarves"></a>
### Dwarves

**Physical Traits:** Short, stocky, bearded (traditionally), excellent crafters and miners.
**Tharros Presence:** Often show up where craft, mining, or salvage matters.

<a id="halflings"></a>
### Halflings

**Physical Traits:** Small (3-4 feet), nimble, often have large feet and curly hair.
**Tharros Presence:** Often visible in service communities (inns, kitchens, caravans) because those communities travel.

<a id="orcs"></a>
### Orcs

**Physical Traits:** Muscular, tusked, green or gray skin, fierce appearance.
**Tharros Presence:** Often visible in security and heavy labor communities because those jobs recruit broadly.

### Other ancestries (Present in small quantities)

All ancestries below are allowed and do exist on Tharros, but they’re uncommon or rarer—most settlers can go months without seeing one.

- **Goblin:** Uncommon; present in ports and hard-to-police trade lanes; often mistaken as “just another small folk” by humans who don’t know better.
- **Faun:** Rare; more likely to be found near old groves and quiet boundary places.
- **Firbolg:** Rare; tends to avoid large settlements.
- **Simiah:** Uncommon; often arrive as sailors, artisans, or scholars, then settle wherever they find acceptance.
- **Mixed Ancestry:** Exists at low levels across the island. Use it to represent two-lineage individuals without implying a large population.
- **Fungril:** Very rare/hidden; they’re more likely to live away from human communities (deep interior, ruin-adjacent fungal networks, or secluded wet places) rather than in towns.

### Rejected Species

**Faerie:** Notably absent from Tharros. The island seems to actively reject their presence. If a Faerie is introduced later, it should come with strong lore for how they arrived and stayed alive and unchanged.

### Transformed Beings (Unknown)

**Changed:** Humans or other species altered by [Reckonings](#reckonings). Varies widely in form and sanity.
**Hybrids:** Like [Cordyceps](#cordyceps) - beings merged with other entities (fungal, elemental, etc.).
**Note:** These are typically unique individuals rather than established species.

### NPC Creation Guidelines

**For Every NPC:**
1. **Choose Species** (humans are common; everything else is uncommon at most)
2. **Choose Nationality** (place of origin / passport-culture; can be mixed)
3. **Choose Ethnicity/Culture** (Nordahr/Serenei/etc; can differ from nationality)
4. **Choose Community** (profession, settlement, caravan, temple order, dock crew, etc.)
5. **Name the NPC** using: Community → Ethnicity/Culture → Nationality → Species
6. **Decide outward appearance and behavior** using the same four categories + personal history
7. **Remember island dwarfism** - this mainly shows up in those raised on Tharros, and can become more pronounced over generations
8. **Mark Species, Nationality, Ethnicity/Culture, and Community** in the NPC Directory

**Example (orthogonal categories in practice):** A **Drakona** who is a **Virelian citizen** but was raised in an **Aegeon dockside community** might have a *Virelian-style given name* and an *Aegeon-style family name*, speak with Aegeon mannerisms, and still present Drakona physical traits.

**Rarity Guidelines:**
- **Common:** Humans
- **Uncommon (at most):** Galapa, Infernis, Drakona, Katari, Elf, Dwarf, Halfling, Orc, Goblin, Simiah
- **Rare:** Ribbet, Faun, Firbolg, Mixed Ancestry
- **Very Rare:** Fungril, Giant-frogs, Giants
- **Rejected/Plot-Only:** Faerie, Clanks

---

## Major Nations

<!-- CATEGORY: LOCATION, CULTURE -->
### Virelia (Centralized, bureaucratic, coastal empire)

- **Primary Culture:** *[Serenei](#serenei-mediterranean-inspired)*
- **Racial Mix:** Predominantly Human, [Galapa](#galapa), and [Inferis](#inferis)
- **Identity:** Civilized, cosmopolitan, proud of their cities, art, and religion
- **Religion:** [The Eternal Flame](#divinity) is state-sanctioned
- **Traits:** Educated elites, slick diplomats, clean uniforms, high architecture
- **Minorities:** Pockets of [Drakona](#drakona) immigrants, older [Dwarven](#dwarves) enclaves
- **Tharros Connection:** The [Church](#the-church-of-the-eternal-flame-minor-faction), [Brotherhood](#the-remnant-brotherhood), and [Syndicate](#the-ironbound-syndicate) all have Virelian roots

### Korralt (Frontier kingdom, rich in woodlands and hills)

- **Primary Culture:** *[Panthyr](#panthyr-central-eastern-inspired)*
- **Racial Mix:** [Dwarves](#dwarves), Humans, some [Halflings](#halflings)
- **Identity:** Stubborn, honest, community-first, strong oral traditions
- **Religion:** Loosely follows [the Flame](#divinity), with strong regional saints
- **Traits:** Long stories, thick embroidery, warm drinks, loyal to kin
- **Minorities:** Nomadic [Galapa](#galapa) clans, especially along rivers
- **Tharros Connection:** Many ordinary settlers came from here, especially to escape taxes and famine

### Skaldmere (Cold, fragmented coastal lands)

- **Primary Culture:** *[Nordahr](#nordahr-norse-inspired)*
- **Racial Mix:** Humans, [Drakona](#drakona), some Half-[Orcs](#orcs)
- **Identity:** Proud seafarers, austere, survival-focused, deeply tribal
- **Religion:** Shamanic traditions mix with a distant respect for [the Flame](#divinity)
- **Traits:** Tattoos, ritual duels, sea ballads
- **Tharros Connection:** Mercenaries and [Brotherhood](#the-remnant-brotherhood) bodyguards often hail from here

### Myrrhun (Cradle of arcane studies, mountainous interior)

- **Primary Culture:** *[Tharain](#tharain-hungarian-inspired)*
- **Racial Mix:** Humans, [Inferis](#inferis), and [Elves](#elves)
- **Identity:** Scholarly, poetic, fatalistic; deeply interested in history
- **Religion:** [Flame](#divinity) is present, but often seen metaphorically
- **Traits:** Riddles, layered robes, [relic](#relics) obsession, ruined libraries
- **Minorities:** Tight-knit [Elf](#elves) enclaves with their own dialects
- **Tharros Connection:** [High Archivist Alaric](#high-archivist-alaric) and many senior [Brotherhood](#the-remnant-brotherhood) figures came from here

### The Veskar Wards (Dispersed Drakona city-states)

- **Race-Based Culture:** Primarily **[Drakona](#drakona)**
- **Identity:** Draconic pride, ancient rites, tradition of elemental pacts
- **Religion:** Personal connection to elemental forces and "Elder Flame" myths
- **Traits:** Formal speech, horn-braiding, breath-color ceremonies
- **Tharros Connection:** Often viewed as "dangerous mystics"; the [Assembly](#the-veiled-assembly) courts their wisdom

### The Galari Shoals (Archipelago homeland of the Galapa)

- **Race-Based Culture:** [Galapa](#galapa) majority, some Humans
- **Identity:** Communal, slow-moving decision-making, memory-centric culture
- **Religion:** Oceanic spirits, long memory lines, deep respect for natural rhythms
- **Traits:** Carved shells, floating shrines, oral family archives
- **Tharros Connection:** Some [Galapa](#galapa) settled inland Tharros to escape climate shifts

### The Hollow Marches (Exiled Inferis and outcasts)

- **Race-Linked Culture:** [Inferis](#inferis) dominant
- **Identity:** Rejects of other lands; revolutionary and occult undercurrents
- **Religion:** Heretical offshoots of [the Flame](#divinity), dark gods, personal transcendence
- **Traits:** Ash-horns, veiled faces, obsidian rings
- **Tharros Connection:** The [Shard](#the-shard--nightweb-minor-faction) Concord's ideological roots trace back here

---

<!-- CATEGORY: LORE, SECRET -->
## View of Tharros (From the Mainland)

*"It's out there, beyond the common trade lanes. Real enough if you know where to look. Just not the kind of place that makes it into textbooks or tour routes."*

### Mysterious but Real

Tharros is not a secret, but neither is it a household name. It's *the place everyone's heard of, but few can point to on a map*. Some treat it as a curiosity; others believe it's more myth than fact. There are ports that quietly send ships west--but no one makes it a routine.

- *"My cousin went to Tharros. Or so he said. His letters stopped after the third moon."*
- *"You can book passage there, sure. You just need to know the right harbormaster, and pay like you're buying a secret."*

### The Syndicate's Quiet Interest

The **[Ironbound Syndicate](#the-ironbound-syndicate)** operates outposts and controls trade routes. But they're *deliberate in keeping Tharros off the radar*. They avoid attracting state or rival corporate attention, presenting the island as unremarkable.

- *"Expansion territory, minimal output. Not worth inspection."*
- Internal memos, though, speak of "exceptional potential," "anomalous energies," and "competitive embargoes."

### The Church's Soft Warnings

The **[Church of the Eternal Flame](#the-church-of-the-eternal-flame-minor-faction)** acknowledges Tharros, but publicly speaks of it as spiritually barren or unstable. Missionaries go, but not the promising ones. Sermons frame it as a place of moral *testing*, or temptation.

- *"The Flame burns weak where the soil remembers other fires."*
- Some heretical sects believe Tharros is the *cradle* of true divinity. The Church condemns these ideas.

### The Scholar's Obsession

Academics refer to Tharros in footnotes and fringe journals. The **[Remnant Brotherhood](#the-remnant-brotherhood)** has seeded misinformation while pursuing [relics](#relics) and ruins in secret. Tharros is whispered about in university halls, often with mocking smiles.

- *"Tharros? The island with singing rocks and blinking ruins? Yes, I did a paper on it once."*
- *"No one ever publishes serious work on Tharros. Those who try... usually stop writing."*

### The Common Folk's View

For most people, Tharros is a foggy idea. Dangerous? Maybe. Exotic? Probably. Worth your life? Unlikely.

- *"It's out west, yeah? Past the old chain. Some folks strike it rich. Others don't come back."*
- *"Too many storms. Too many secrets. The sea doesn't like giving it back."*

---

<!-- CATEGORY: FACTION -->
# Part IV: Factions

Each of the major groups listed below claims to serve the island's well-being--but differ greatly on what that means. Some may offer you work, shelter, or purpose.

---

## The Ironbound Syndicate

<!-- CATEGORY: FACTION, NPC -->

**Progress through Industry**

*"Work. Prosper. Endure."*
--[Magnate Theron](#magnate-theron)

The Syndicate sees Tharros as a land of potential: mines to dig, rail to lay, towns to build. They bring coin, steel, and structure to those who cooperate--and little patience for those who don't.

- **Focus:** Infrastructure, jobs, protection, advancement
- **Settlements:** [Braycall Ridge](#braycall-ridge-syndicate-stronghold), parts of [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core)

**Quotes:**
- *"We're not here to ruin the island. We're here to use it wisely--together."*
- *"We don't mine the island. We mine the future."*
- *"The past had its time. Now it's our turn."*

### Magnate Theron

<!-- CATEGORY: NPC -->
**Spokesperson:** Industrial Visionary

"We are builders. We don't worship rubble, and we don't speak in riddles. Tharros offers promise--its forests, its ore, its secrets--and we mean to use it for the good of all. We offer jobs, safety, roads, trade, and progress. Work with us, and we'll build something better together."

**On the [Brotherhood](#the-remnant-brotherhood):** "Good intentions buried in old bones. They'd rather catalogue the world than fix it."
**On the [Assembly](#the-veiled-assembly):** "They oppose everything. You can't feed families with tree songs."
**On the [Church](#the-church-of-the-eternal-flame-minor-faction):** "Well-meaning, if a bit slow. Useful in keeping people calm."

### Public Opinions on the Syndicate

**"I came here with nothing. The Syndicate gave me a job, a roof, and a new start. They don't ask for prayers, just hard work. That's worth something."**
-- *[Gregor](#gregor), mill foreman at [Braycall Ridge](#braycall-ridge-syndicate-stronghold)*

**"They talk like they're building a better future, but they don't have to drink the water downstream from their smelters. I do."**
-- *[Rhea](#rhea), herbalist in [Thistleshade](#thistleshade-assembly-stronghold)*

**"They're honest, in their way. They tell you what they want, and they pay you for it. You just better not be in their way when they want it."**
-- *[Tanis](#tanis), dockhand in [Nettlehook](#nettlehook-black-market-free-port---nightweb-presence) Port*

**"Say what you will, but my sister's got a new leg thanks to their engineers. She walks now. That's not greed, that's miracle metal."**
-- *[Daro](#daro), tavern regular in [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core)*

**"I don't trust them. They smile too much when they talk about 'efficiency.'"**
-- *[Old Lenne](#old-lenne), retired miner*

---

## The Remnant Brotherhood

<!-- CATEGORY: FACTION, NPC -->

**Wisdom from the Past**

*"Preserve. Study. Respect."*
--[High Archivist Alaric](#high-archivist-alaric)

The ruins of Tharros may hold truths the world has forgotten--or truths it chose to forget. The Brotherhood studies the [Relics](#relics) and the language of a dead civilization. They claim their work prevents catastrophe. Others say it causes it.

- **Focus:** Research, expeditions, [relic](#relics) safety (or secrecy)
- **Settlements:** [Aurel's Reach](#aurels-reach-brotherhood-hub), [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core) archives

**Quotes:**
- *"You cannot build a future on bones unless you first learn the names of the dead."*
- *"If we forget the past, it will bury us again."*
- *"We don't fear the old world--we listen to it."*

### High Archivist Alaric

<!-- CATEGORY: NPC -->
**Speaker:** Scholar and Preserver (from [Myrrhun](#myrrhun-cradle-of-arcane-studies-mountainous-interior))

"Tharros was not merely an island. It was once a civilization of astonishing complexity--far beyond our understanding. We dedicate ourselves to preserving what remains, not to exploit it, but to understand it, learn from it, and prevent another catastrophe. We are not here to rule. We are here to remember."

**On the [Syndicate](#the-ironbound-syndicate):** "Short-sighted. They'd strip-mine a cathedral if it had copper in the walls."
**On the [Assembly](#the-veiled-assembly):** "Well-intentioned, but trapped in mysticism. They burn knowledge to save moss."
**On the [Church](#the-church-of-the-eternal-flame-minor-faction):** "Their unity dogma is quaint, but at least they care about balance."

### Public Opinions on the Brotherhood

**"I saw one of them pull a glyph-covered ring out of the mud and just... stare at it like it was an old lover. I think they *feel* something about this island no one else does."**
-- *[Calia](#calia), local guide*

**"They think they're better than the rest of us. Like books and ruins give them the right to decide who gets to live where."**
-- *[Miran](#miran), homesteader displaced by an excavation claim*

**"I spent two weeks with a Brotherhood crew cataloging coral patterns. They were respectful. Weirdly quiet, but good people. Passionate."**
-- *[Tarel](#tarel), fisher from the northern coast*

**"They say they preserve the past, but every time I ask about what they *found*, it's always 'restricted,' 'dangerous,' or 'inconclusive.' Sounds like gatekeeping."**
-- *[Bennet](#bennet), frustrated scholar*

**"The Brotherhood sponsored my child's education. Free scrolls, tutoring. Not all of them are dusty relic-huggers."**
-- *[Nina](#nina), merchant widow*

---

## The Veiled Assembly

<!-- CATEGORY: FACTION, NPC -->

**Harmony with the Island**

*"Listen. Protect. Endure."*
--[Maera](#maera)

The Assembly believes the land is not merely alive--it is wounded. Every act of exploitation deepens the scars. They resist [Syndicate](#the-ironbound-syndicate) expansion, [Brotherhood](#the-remnant-brotherhood) digging, and anything that harms the balance. But they are not above using force when warnings go ignored.

- **Focus:** Sustainable living, healing, resistance
- **Settlements:** [Thistleshade](#thistleshade-assembly-stronghold), scattered camps

**Quotes:**
- *"When the earth screams, we answer. Will you?"*
- *"The land is alive. Stop hurting it."*
- *"If you hurt the land, it will hurt you back."*

### Maera

<!-- CATEGORY: NPC -->
**Speaker:** Voice of the Island

"The land is older than any of us. It remembers pain. [Reckonings](#reckonings) are not storms or curses--they are immune responses. Every stone overturned, every [relic](#relics) disturbed without reverence brings us closer to collapse. We are not isolationists--we are guardians. Work with us, and we'll teach you to hear the island before it screams again."

**On the [Syndicate](#the-ironbound-syndicate):** "They call it progress. We call it poison."
**On the [Brotherhood](#the-remnant-brotherhood):** "Curiosity without wisdom. They wear lab coats and carry knives."
**On the [Church](#the-church-of-the-eternal-flame-minor-faction):** "Sometimes wise, sometimes meddling. Flame burns, even if holy."

### The Assembly's True Nature (GM Secret)

<!-- CATEGORY: FACTION, SECRET -->

**Moral Core**: The island is alive. You're trespassing.
**Public Face**: Protectors of balance and ancient wisdom.
**Reality**: Eco-radicals who will destroy what you build if it threatens the land.

**Political Posture:**
- **Openly opposed** to the [Brotherhood](#the-remnant-brotherhood) and [Syndicate](#the-ironbound-syndicate)--calls them both "colonial parasites," albeit using more poetic language when needed.
- Tries to win the hearts of common settlers in **[Marrowhold](#marrowhold-first-and-central-settlement---neutral-core)** and nearby homesteads by offering **free healing, guidance, and safe passage**--often before the factions even respond.
- Believes the people of Tharros (especially new settlers) can be **taught to live in balance**, but if they resist, they become **acceptable sacrifices**.

**Radical Core:**
- Operates **direct sabotage missions**: blowing up bridges, poisoning machines, and freeing captive [relics](#relics).
- Refers to these actions as "cleansings," "ritual corrections," or "symbiotic disruption."
- Hides weapons and [Relic](#relics)-based tools in the roots of ancient trees. Their hit cells are **small, autonomous**, and always vanish afterward.

**Propaganda Strategy:**
- Distributes **parables and cautionary poems** through wandering bards and herbalists.
- Claims their extreme actions are **the island's will**, not their own.
- Regularly spread rumors that **[Brotherhood](#the-remnant-brotherhood) experiments have caused [Reckonings](#reckonings)**, or that **[Syndicate](#the-ironbound-syndicate) drill sites are leaking madness**.

**Internal Conflict:**
- Not all Assembly members agree with [Maera](#maera)'s militant path.
- Some are trying to **build a cooperative model**, especially with sympathetic settlers and druids who aren't ready to take up arms.
- Others think she's **not going far enough**, and want to begin "pruning" [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core) itself before it becomes too dangerous.

**Tension Leverage:**
- In Marrowhold, Assembly agents are **healers, midwives, and guides**. Quietly asking questions. Offering protection "in case the Syndicate gets bold again."
- When Syndicate equipment breaks or goes missing? **Assembly eyes glint with satisfaction.**
- The Brotherhood blames them for *missing researchers*. Assembly calls them "claimed by the wild."

### Player-Facing Assembly Recruitment

<!-- CATEGORY: FACTION, HOOK -->
When characters interact with Assembly members, here's what they'll hear:

- "The island has always spoken. The question is whether you're listening or just digging."
- "You want to save your people? So do we. But we'll save them **from themselves** if we must."
- "The others speak of progress. We speak of continuity."
- "It's not terrorism. It's pruning."

### Public Opinions on the Assembly

**"When the storms came, they showed up with warm tea, salves, and seeds. They never asked for payment. They just said, 'respect the land, and it will respect you.'"**
-- *[Yarin](#yarin), farmer near the [Marrowwood](#marrowwood) border*

**"Their idea of 'balance' meant burning our storage shed because it was built on sacred soil. That shed fed four families. Tell me that's protection."**
-- *[Ilso](#ilso), survivor from an abandoned hamlet*

**"Some of them are strange. Talking to stones and birds and such. But I've never met one who lied to my face."**
-- *[Marda](#marda), courier*

**"They're stubborn. Gods help you if you try to reason with them once they've 'heard the will of the island.' But at least they believe something."**
-- *[Kerrik](#kerrik), ex-[Brotherhood](#the-remnant-brotherhood) assistant*

**"The Assembly midwives helped deliver my daughter when the [Church](#the-church-of-the-eternal-flame-minor-faction) clinic was full. They sing to the newborns. It's eerie... and beautiful."**
-- *[Orla](#orla), settler in [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core) outskirts*

---

## The Church of the Eternal Flame (Minor Faction)

<!-- CATEGORY: FACTION, NPC -->

**One Flame, Many Faces**

*"Kindle what connects us."*
--[Priest-Ambassador Elyna](#priest-ambassador-elyna)

The Church offers guidance, healing, and unity. They believe all divine sparks come from a single flame, worshipped in many forms. Their presence brings calm--but also quiet judgment. They often mediate disputes and care for the lost.

- **Focus:** Hospitals, shrines, social support, education
- **Settlements:** [Ashlight Monastery](#ashlight-monastery-church-enclave), temples in [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core)

**Quote:** *"We do not demand faith. Only that you keep your flame lit."*

### Priest-Ambassador Elyna

<!-- CATEGORY: NPC -->
**Voice:** Flamebearer of [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core)

"We believe the world carries a light at its center--one flame, many faces. Whether you call it hope, faith, [magic](#magic), or mercy, we are here to tend it. We offer healing, clarity, and unity in a divided land. We do not choose sides. We remind them of the spark that binds all."

**On the [Syndicate](#the-ironbound-syndicate):** "They mean well, but build too fast."
**On the [Brotherhood](#the-remnant-brotherhood):** "They chase truth but forget compassion."
**On the [Assembly](#the-veiled-assembly):** "They protect--but fire that is not tempered becomes wild."

### Extended Commentary on the Church

*From "On Flame and Structure" -- a forbidden commentary by an unnamed cleric, now preserved only in fragments whispered among exiles and dissenters.*

The Church of the Eternal Flame claims unity above all. One Flame. One truth. One path to salvation. To many, it offers comfort in a chaotic world--ritual, hierarchy, and answers to unanswerable things.

It teaches that all gods are reflections of the Flame, that miracles are but glimpses of divine order, and that true virtue lies in discipline, clarity, and purpose. Even when it tolerates other religions, it demands they align with its tenets: the Flame is supreme, even when hidden.

Some see this as wisdom. Others see it as conquest cloaked in theology.

On the mainland, the Church is vast, old, and deeply enmeshed with governance. Here, on Tharros, it is newer, smaller, but still influential. Officially, it mediates disputes and offers sanctuary. Unofficially, it positions itself as the sole moral compass--implicitly or explicitly.

Critics suggest that the Church's true goal is not salvation but *control*. That it uses faith to mold society into manageable forms. That its centralization is less about preserving truth and more about ensuring obedience.

And yet... when the monsters come, it is often Church clerics who stand first. When plagues strike, it is their candles that still burn.

Perhaps the Church is both shepherd and jailer. Perhaps that is the price of fire--it warms, and it scars.

### Public Opinions on the Church

**"They patched my husband up for nothing. Didn't even ask which Flame we light at home. That's more than I can say for the others."**
-- *Verra, blacksmith's wife*

**"Too soft. Always talking about unity. The island isn't unified, it's *fractured*. You can't just bless the cracks and hope they vanish."**
-- *[Sarth](#sarth), ex-[Assembly](#the-veiled-assembly) sympathizer*

**"[Priest Elyna](#priest-ambassador-elyna) gave me work when I couldn't stand the [Syndicate](#the-ironbound-syndicate) no more. Her eyes are tired, but her voice could calm a storm."**
-- *[Rund](#rund), reformed [Syndicate](#the-ironbound-syndicate) guard*

**"I trust their fire more than the [Brotherhood](#the-remnant-brotherhood)'s silence or the [Syndicate](#the-ironbound-syndicate)'s promises. At least with them, you *know* what they believe."**
-- *[Jara](#jara), teacher in [Ember's Hollow](#embers-hollow)*

**"They say the Flame unites us--but I've seen that same Flame used to justify punishment. Not from [Elyna](#priest-ambassador-elyna), but the quiet ones. The ones with red sashes."**
-- *[Hess](#hess), wandering bard*

---

## The Shard / Nightweb (Minor Faction)

<!-- CATEGORY: FACTION -->

**Pragmatism without Pretense**

*"Get it done. Or we will."*
--(Attributed to "[Whisper](#whisper)")

No banners. No sermons. Just results. The Shard operates in the cracks of power--smugglers, saboteurs, and freelancers with flexible morals. They don't ask for loyalty, only usefulness.

- **Focus:** Smuggling, espionage, [relic](#relics) theft
- **Locations:** Unknown, but often suspected in [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core)

**Quote:** *"Everyone has ideals. Ours is survival."*

"Don't listen to the stage acts. You want something done, come to us. A gate opened, a relic moved, a Syndicate thug disappeared? We get things done. We don't talk about balance. We keep it--our way."

**On everyone else:** "They all want to own the island. We just want to survive it."

### Whisper

<!-- CATEGORY: NPC, SECRET -->

The rumored leader (or one of several leaders) of the Nightweb. No one has confirmed their identity, gender, or even if "Whisper" is a single person or a title passed between operatives. Some say they've met Whisper without knowing it; others claim Whisper doesn't exist at all--just a convenient fiction to make the Nightweb seem more organized than it is.

### Whispers of the Shard

**"Who built the new well in our village? Wasn't the [Syndicate](#the-ironbound-syndicate). Wasn't the [Brotherhood](#the-remnant-brotherhood). Someone just left tools and vanished. I hear that's how the Shard 'hires' you."**
-- *Anonymous note left in [Braycall Ridge](#braycall-ridge-syndicate-stronghold)*

**"They don't ask questions, don't make speeches. They get it done--for a price. That's dangerous power, but sometimes it's the only kind that answers."**
-- *Unknown informant*

**"You want [relics](#relics)? The [Brotherhood](#the-remnant-brotherhood) files. [Syndicate](#the-ironbound-syndicate) vaults. There's always a Shard already inside."**
-- *Graffiti carved into a shipping crate*

---

## Minor Factions and Gangs

<!-- CATEGORY: FACTION -->

These minor organizations bring the island's social and criminal gravity to life, offering flavor, hexcrawl hooks, and side conflicts:

### Black Reef Corsairs

Ruthless bandits operating from hidden coves along Tharros's coast. They smuggle goods, raid supply ships, and sometimes strike inland. They're heavily tied to the [Nightweb](#the-shard--nightweb-minor-faction), serving as their maritime muscle. Connected to the [Corsair Clans](#corsair-clans) culture.

### The Embercut Brotherhood

A gang of ex-laborers and disgruntled miners who loot abandoned [Syndicate](#the-ironbound-syndicate) camps and relist their plunder. Mercurial in loyalty, they're opportunists who can be allies or enemies of any faction.

### Forest Wraiths

Stealthy vigilantes protecting [Assembly](#the-veiled-assembly) territory. Part partisan militia, part mythic ghost story, they sabotage [Syndicate](#the-ironbound-syndicate) operations and leave ominous warnings carved into trees.

### Flamebound Zealots

A radical sect offshoot of the [Church of the Eternal Flame](#the-church-of-the-eternal-flame). They interpret any [Relic](#relics) manifestation as holy fire--and destroy artifacts in fervent holy fury, sometimes attacking innocents. Related to the [Flamekeepers](#flamekeepers) culture.

### Relic Runners

Independent treasure hunters and [relic](#relics) dealers unaffiliated with any faction. They hire PCs to locate and smuggle [Relics](#relics), cutting deals with whoever offers the best price--or the safest escape.

---
<!-- CATEGORY: LOCATION -->
# Part V: Locations

## Major Settlements

### Marrowhold (First and Central Settlement - Neutral Core)

<!-- CATEGORY: LOCATION -->

**Population:** ~700
**Alignment:** Neutral (Officially), Pragmatically Entangled

**Origins:**
- Founded by early settlers, idealists, and independent colonists who arrived before or alongside the factions.
- Grew around a defensible ruin with fertile ground and clean water--a rare luxury on Tharros.
- Originally a **communal project** meant to unite people under shared survival.

**Evolution:**
- As the [Syndicate](#the-ironbound-syndicate) and [Brotherhood](#the-remnant-brotherhood) established themselves nearby, they **offered aid, investment, and "cooperation"**.
- Today, both have **minor offices and operatives here**, offering "services" and "advice."
- [Assembly](#the-veiled-assembly) sympathizers live quietly among the herbalists, farmers, and ferrymen.

**Tone:**
- Fragile, democratic, exhausted. It survives because **everyone wants to claim it--but no one wants to be the first to break it**.
- Locals play politics carefully; **even the mayor has more enemies than friends.**

---

## Minor Settlements and Districts

<!-- CATEGORY: LOCATION -->

| Settlement | Type | Affiliation | Population | Description | Notable Features |
| ---------- | ---- | ----------- | ---------- | ----------- | ---------------- |
| **Marrowwood** | Forest region | [Assembly](#the-veiled-assembly)-sympathetic | Unknown | Forested area near [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core) | Home to farmers/homesteaders |
| **Ember's Hollow** | Settlement/district | [Church](#the-church-of-the-eternal-flame) presence | Unknown | Settlement with Church influence | Teachers, believers |

---

### Braycall Ridge (Syndicate Stronghold)

<!-- CATEGORY: LOCATION, FACTION -->

**Population:** ~500 (150 core [Syndicate](#the-ironbound-syndicate), 350 laborers or dependents)
**Alignment:** [Syndicate](#the-ironbound-syndicate)-dominated, with [Brotherhood](#the-remnant-brotherhood) "consultants"
**Public Motto:** *"Progress through unity. Together, we rise."*

**Origins:**
- Founded as a **mining camp** that struck deep veins of metal and crystalline [Precursor](#precursors--ancestors) material.
- Quickly expanded under [Syndicate](#the-ironbound-syndicate) management; heavily reliant on imported labor.
- Founded not by executive decree but by **a charismatic expedition leader**, now a [Syndicate](#the-ironbound-syndicate) agent ([Magnate Theron](#magnate-theron)'s protege).
- Marketed as a **land of opportunity**, with jobs, safety, and wages better than back home--especially for those displaced by mainland wars or famine.

**Evolution:**
- [Brotherhood](#the-remnant-brotherhood) surveyors were granted access (in exchange for support), and now maintain a quiet **research annex** nearby.
- The [Assembly](#the-veiled-assembly) considers the whole town **blighted**, occasionally attacking convoys or disrupting supply lines.

**Surface Image:**
- Public schools (basic), free meals for laborers, and well-built housing compared to other outposts.
- A celebratory vibe: **"We're building something real here."**
- Encourages settler-owned businesses (so long as they don't compete with [Syndicate](#the-ironbound-syndicate) control).

**Below the Surface:**
- **Debt contracts** trap workers in long-term labor.
- Those who challenge [Syndicate](#the-ironbound-syndicate) practices are **transferred, dismissed... or disappear**.
- Regular "safety inspections" are also loyalty checks.

**Tone:**
- Tense but functional. Hard work, low pay, and high danger.
- **Everyone's tired. Most people drink. Some hear things in the mines.**

**Player Perception:**
- PCs may arrive thinking it's the **most functional and welcoming place** on the island.
- They'll only see the rot if they **dig--or stay too long.**

---

### Aurel's Reach (Brotherhood Hub)

<!-- CATEGORY: LOCATION, FACTION -->

**Population:** ~220
**Alignment:** [Brotherhood](#the-remnant-brotherhood) Core, Limited Outsider Access
**Public Motto:** *"Understanding is freedom. Truth is our inheritance."*

**Origins:**
- Established by the [Brotherhood](#the-remnant-brotherhood) on a plateau near concentrated [Relic](#relics) sites.
- Named for the first scholar to map the "Patterned Pulse" of [Reckonings](#reckonings)--who died shortly after.
- Originally a **multinational expedition** of scholars, artists, and philosophers.
- The [Brotherhood](#the-remnant-brotherhood) later absorbed the site into their order, touting it as a **"free learning enclave."**

**Evolution:**
- A gated campus-town with observation towers, [relic](#relics) containment vaults, and a strict curfew.
- **Local workers are vetted** extensively before being allowed entry or employment.
- [Syndicate](#the-ironbound-syndicate) "sponsors" some equipment shipments, but they're kept at arm's length.

**Surface Image:**
- Open forums for debate, guest lectures, community events.
- Locals may **volunteer in artifact handling**, receive basic education, or even learn old languages.
- Seen as **peaceful, intelligent, and principled**.

**Below the Surface:**
- Sensitive knowledge is strictly **controlled and compartmentalized**.
- Disagreeing with doctrine may result in polite exile--or reeducation.
- Some scholars **"retire" into internal wards** for study... and never return.

**Tone:**
- Cold, cerebral, clinical. **"Truth before comfort"** is the unspoken motto.
- Outsiders are tolerated, not welcomed.

**Player Perception:**
- PCs may be **invited as allies** or student-partners.
- They may start to notice discrepancies--**missing reports, redacted maps**, or subtle memory lapses near certain vaults.

---

### Thistleshade (Assembly Stronghold)

<!-- CATEGORY: LOCATION, FACTION -->

**Population:** ~100 permanent (150+ migratory allies, up to 200+ seasonal sympathizers, refugees)
**Alignment:** [Assembly](#the-veiled-assembly)-aligned, Anti-structure by design
**Public Motto:** *"Walk gently. Take only what you can carry in silence."*

**Origins:**
- Founded by defectors from early expeditions and locals who believed the island must be preserved, not extracted.
- A convergence point of people who **felt the island call to them**, mostly defectors, outcasts, and a few scholars who turned against their orders.
- Exists as a **cluster of glades, treehouses, and caves** connected by hidden trails.
- Located in the **dense interior**, half built into cliffs, canopies, and hollowed-out stone arches overgrown with glowing moss.

**Evolution:**
- Refuses centralized leadership. [Maera](#maera) is their voice, not their ruler.
- Openly rejects [Syndicate](#the-ironbound-syndicate) and [Brotherhood](#the-remnant-brotherhood) expansion, but sends envoys to [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core).
- Embraced by the [Veiled Assembly](#the-veiled-assembly) as **proof that coexistence was still possible**.

**Surface Image:**
- Beautiful, serene commune. Living gardens. Flowing springs.
- A calm, serene commune--**all are welcome** (if they behave).
- Shared meals, open-air gathering circles, botanical gardens of natural remedies.
- Open-air teaching circles on herbalism, history, and "how to listen to the land."
- Teachers, herbalists, and spiritual guides offer aid to anyone who approaches peacefully.
- No one raises a voice. Everyone listens. **It feels like being accepted by something ancient.**

**Below the Surface:**
- Some rooms are **sealed off with living roots**.
- "Foundlings" who appear after [Reckonings](#reckonings) are **tested** in rituals no outsider is told about.
- All guests are watched, even those who think they're friends.
- Anyone asking "too much" is offered tea... and a walk.
- Outsiders are gently "redirected" if they stay too long or ask the wrong questions.
- The [Assembly](#the-veiled-assembly) has **sabotaged other settlements** and has an internal "circle of the root" that vets everything.
- Some plants used in healing are **not legal**--and some are not explainable.

**Tone:**
- Peaceful but severe. **"All are welcome, but not all are forgiven."**
- The island accepts those who listen. It punishes those who don't.

**Player Perception:**
- First impression: **safe haven in a hostile land**.
- Long-term: **strange coincidences, disappearances, and "natural accidents."**

---

### Ashlight Monastery (Church Enclave)

<!-- CATEGORY: LOCATION, FACTION -->

**Population:** ~90 (about 30 militant, 60 clergy or pilgrims)
**Alignment:** Religious, independent but lobbying
**Public Motto:** *"The Flame welcomes all. The darkness welcomes none."*

**Origins:**
- Pilgrims followed visions and ancient texts to a volcanic ridgeline.
- Founded by visionaries who followed a fire seen in dreams to a glowing ridge.
- Built their home near a radiant anomaly.
- Declared it holy ground, believing the **island itself was wounded--and the Flame seeks to heal it.**

**Evolution:**
- [Church](#the-church-of-the-eternal-flame) leadership supports missionary work in [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core) and [Braycall](#braycall-ridge-syndicate-stronghold), though not always welcome.
- Friction with [Brotherhood](#the-remnant-brotherhood) is rising over the "theft" of sacred [relics](#relics).

**Surface Image:**
- Offers **shelter, medicine, and spiritual guidance** to travelers and pilgrims.
- The Flame is never forced upon anyone. Their prayers sound like poetry.
- Sermons preach **hope, unity, and purification from past sins.**

**Below the Surface:**
- Those "blessed by the Flame" sometimes return... different.
- Militant members prepare for a **coming [reckoning](#reckonings)** they believe the Flame prophesies.
- Nonbelievers who disrupt rituals are **politely asked to leave**--and never seen again.

**Tone:**
- Controlled, ritualistic, "righteously eerie."
- Stoic, warm-hearted, mysterious--bordering on fanaticism.
- Their fire never goes out, and no one is sure why.

**Player Perception:**
- Peaceful sanctuary--especially for those burned by other factions.
- But the deeper you stay, the **hotter the truth becomes.**

---

### Nettlehook (Black Market Free Port - Nightweb Presence)

<!-- CATEGORY: LOCATION, FACTION -->

**Population:** ~300
**Alignment:** Officially unaffiliated. The [Nightweb](#the-shard--nightweb-minor-faction) is present here because it's convenient--but Nettlehook is not their headquarters, and not truly "owned" by any faction.
**Public Motto:** *"No gods. No masters. No questions."*

**Readaloud (Guests):**
Nettlehook announces itself as noise and salt: hammer-on-nail, rope against wood, gulls, shouted prices, and laughter that comes too easily. The port is a patchwork of pilings and boardwalks over brackish water, with mangroves crowding the edges and old Corsair stone half-swallowed by tide and moss. Tar-lanterns swing from crooked posts; canvas awnings and scavenged sailcloth throw shade over open tables where everything from dried fish to odd little tools is traded without ceremony. There are no banners above the docks—only blank poles, weathered signs, and the constant motion of small boats slipping in and out like they belong to nobody.

**Readaloud (Locals):**
Locals say Nettlehook is not lawless—only neutral, and stubborn about it. The port does not care which banner someone fled; it cares whether they try to raise one here. Disputes are handled fast and plain by a local council and a simple rule spoken like a prayer: everyone gets one warning, and then the docks stop being friendly. In that kind of freedom—where names are optional and questions are a choice—rumors thrive that the [Nightweb](#the-shard--nightweb-minor-faction) has eyes in every crowd; perhaps it does. But Nettlehook endures by staying unclaimed, and it will burn its own bridges before it becomes anyone's fortress.

**Description (Town Style):**
Nettlehook is built on pilings and stitched-together boardwalks in a muddy delta, more floating maze than planned town. Buildings are low, practical, and weather-beaten—salt-stained timber, tarred rope, scavenged stone, and patched canvas. The whole place feels temporary by design: stalls can vanish overnight, footbridges can be pulled up, and nothing important is ever stored in only one place.

**Major Landmarks:**
- **The Blankpole Quay**: A wide pier-plaza lined with empty banner poles and windworn warning boards—where announcements are made and disputes are settled in public.
- **The Tideboard Market**: Long tables under layered sailcloth awnings; goods are sold in small lots, quick deals, and unlabelled bundles.
- **Council Steps**: A raised set of stone steps reclaimed from old Corsair ruins; the nearest thing Nettlehook has to a courthouse.
- **The Lanternwalk**: A high, narrow boardwalk strung with tar-lanterns that stays passable even at high water; night traffic funnels through here.
- **Corsair Stonehook**: A half-collapsed black-stone mooring ring at the delta edge—older than the port, still used for quiet arrivals.

**Origins:**
- Built in a delta where old [Corsair](#corsair-clans) ruins offered mooring and secrecy.
- A failed smuggler's port turned anarchist haven after being abandoned for years.
- Refounded by freebooters, exiles, and independent traders **refusing to bend to any faction**.
- Became a trade stop for those **sick of rules, taxes, or questions**.

**Evolution:**
- Hosts merchants, mercenaries, spies, and smugglers from every faction.
- Everyone denies knowing the [Nightweb](#the-shard--nightweb-minor-faction) exists. Especially the [Nightweb](#the-shard--nightweb-minor-faction).
- Quietly serves as a supply waypoint for underborne communities like [Orvane](#orvane): shaded goods, medicines, tools, and hard-to-source parts move inland by discreet couriers.

**Surface Image:**
- Bustling trade hub where anyone can do business.
- No taxes. **Everyone gets one warning**, then you're dealt with.
- Local council enforces a loose "don't cause trouble" code with fairness and speed.

**Below the Surface:**
- The [Nightweb](#the-shard--nightweb-minor-faction) has eyes here, but they are **guests in a place that survives by staying unclaimed**. Their agents can be found in crowds, not on thrones.
- Predatory lenders and would-be tyrants don't last; the local code is bluntly enforced, and the council will burn bridges to keep Nettlehook from becoming anyone's fortress.
- Rumors say **some residents don't age**, or forget their families (Unconfirmed).

**Tone:**
- Slippery, suspicious, strangely welcoming.
- Lively, egalitarian, dangerously honest.
- Gold talks louder than morality here.

**Player Perception:**
- Most freedom on the island. "Finally, people like us."
- Until someone starts digging--or asking who really owns the ferryman.

---

## Key Locations and Ruins

<!-- CATEGORY: LOCATION, HOOK -->

These are known on maps or in rumors but often **uncertain, shifting, or partial**.

| Location | Era | Type | Description | Danger Level |
| -------- | --- | ---- | ----------- | ------------ |
| **Spire Basin** | Unknown | Reckoning Site | Craterlike bowl surrounded by spiny rock. Site of the **Deep Pulse [Reckoning](#reckonings)**. | Extreme - No solo returns |
| **Gravemire Bastion** | [Pale Colonies](#the-pale-colonies) (~300 yrs) | Imperial Ruin | Crumbling keep in bogs. Stonework in stasis. Petrified skeletons mid-motion. | High - Reality unstable |
| **The Ember Rings** | [Flame Disciples](#the-flame-disciples) (~150 yrs) | Ritual Site | Stone circles with glasslike floors. Voices come when wind blows right. | Moderate - Auditory effects |
| **Whisperwind Hollow** | Unknown | Natural Anomaly | Fog-filled ravine where birds don't fly. [Assembly](#the-veiled-assembly) says it "remembers sorrow." | Low - Psychological |
| **The Singing Spine** | Pre-[Precursor](#ancestors--the-precursors)? | Mountain Range | Wind-hollowed caves that hum. May be skeleton of something buried. Invites dreamers inside. | High - Mental influence |
| **The Obsidian Veil** | [Precursor](#ancestors--the-precursors) | Forbidden Zone | "[Relics](#relics) bloom" from stone. Causes hallucinations or awakening. | Extreme - Transformation |
| **Corsair's Vault** | [Silent Trade](#the-silent-trade-enclave) (~80 yrs) | Sea Cave | Flooded cave with smuggled [relics](#relics). Crates emit light, music, voices. | High - Traps active |
| **The Garden That Eats** | Unknown | Estate Ruin | Overgrown estate where plants move. Those who sleep wake different--or don't. | Extreme - Consumption |
| **The Bone Ring** | Modern (~30 yrs) | Mining Town | Half-buried foundations. Town gone in 3 years. Carved phrase: *"The ground listened."* | Unknown |
| **Venter's Wharf** | [Pale Colonies](#the-pale-colonies) (~300 yrs) | Port Ruin | Pier jutting into bay. Sea unnaturally calm, ignores tides. | Low - Eerie |
| **Ashward Steps** | [Flame Disciples](#the-flame-disciples) (~150 yrs) | Underground | Spiral staircase below sea level. Deep levels warm with untraceable chanting. | High - Descent danger |
| **The Drift Market** | [Silent Trade](#the-silent-trade-enclave) (~80 yrs) | Floating Ruins | Scattered debris of floating settlement. Still drifts between anchor-points. | Moderate - Unstable |
| **Kiremon's Landing** | Modern (~30 yrs) | [Brotherhood](#the-remnant-brotherhood) Outpost | Sealed archives and survey towers. Access restricted. | Moderate - Guarded |
| **Port Brayne** | Modern (~35 yrs) | [Syndicate](#the-ironbound-syndicate) Settlement | Early [Syndicate](#the-ironbound-syndicate) outpost. Still operational. | Low - Civilized |
| **Cape Vaidari** | Unknown | Lighthouse | Mysterious lighthouse, [Orly](#orly)'s quest destination. Blinks three times on certain nights. | Unknown - "Sea gets hungry" |
| **Orvane** | Modern | Underground Settlement | Mixed-race settlement powered by [The Lightspire](#the-lightspire) relic. Inhabitants are light-sensitive. | Moderate - Environmental curse |

### Orvane

<!-- CATEGORY: LOCATION, HOOK -->

**Population:** Unknown (mixed-race community)
**Alignment:** Independent, isolated
**Type:** Underground settlement

**Description:**
An underground mixed-race settlement powered by "[The Lightspire](#the-lightspire)" [relic](#relics). The relic keeps the inhabitants alive but renders them light-sensitive--a blessing and a curse intertwined.

**How It Stays Hidden:**
- Orvane's trade rarely moves "to Orvane" directly. Couriers use **staggered drop points** (sealed crates left at agreed markers, culverts, or tide-caves), with different runners handling different legs.
- The true approaches are **dangerous and unreliable**: collapsed shafts, flooded passages, and tunnels that shift after storms or [Reckonings](#reckonings). Even honest maps go stale.
- To most outsiders, "Orvane" is a **rumor-name**, not a destination. Factions hear about underborne buyers in places like [Nettlehook](#nettlehook-black-market-free-port---nightweb-presence), but can rarely prove a fixed entrance or a stable route worth committing forces to.

**Connection:**
[EFRA-7](#efra-7) was reactivated here and seeks a new energy source to free the inhabitants from the Lightspire's curse.

---

## Failed Settlements: Remnants to Discover

<!-- CATEGORY: LOCATION, LORE, HOOK -->

These are the **known ruins or whispered relics** of Tharros's prior settlers. Each has potential for adventure, danger, and hints of what went wrong.

### The Pale Colonies (c. 300 years ago)

**Known Ruins:**
- **[Gravemire Bastion](#gravemire-bastion)**: A crumbling stone keep surrounded by swamp. Skeletons are petrified mid-motion--possibly by a [Reckoning](#reckonings) "freezing" a moment forever.
- **[Venter's Wharf](#venters-wharf)**: A pier still juts into a bay, but the sea around it is unnaturally calm and refuses to rise or fall with the tide.

**What's Left:**
- Letters etched into stone (not parchment).
- Forgotten imperial coinage--some fused with [Relic](#relics) metal.
- A half-complete map of Tharros's coastline... but it's *wrong*, possibly prophetic.

**Myths:**
- *"The Pale King still watches."* A stone statue in the central keep turns to face intruders over time, without movement.
- *"The Sun didn't rise one morning."* A [Reckoning](#reckonings) blanketed the sky in false starlight for a day. It never happened again.

### The Flame Disciples (c. 150 years ago)

**Known Ruins:**
- **[Ashward Steps](#ashward-steps)**: A spiral staircase carved into a basalt mountain, descending far below sea level. The deeper levels are warm and echo with chanting no one can trace.
- **[The Ember Rings](#the-ember-rings)**: Stone circles with fused, glasslike floors and burnt offerings untouched by time.

**What's Left:**
- "Sunmelted" icons--[Relic](#relics) cores possibly used as worship foci.
- Scrolls written in a mirror-script decipherable only with heat or firelight.
- Robes with golden-thread embroidery that glows during [Reckonings](#reckonings).

**Myths:**
- *"They tried to become flame."* The last of the sect attempted a grand ritual to merge with the Eternal Fire. Some say it worked. Others say they never truly died.
- *"A flame speaks beneath the mountain."* Some explorers report dreams of a radiant voice calling from the depths.

### The Silent Trade Enclave (c. 80 years ago)

**Known Ruins:**
- **[Corsair's Vault](#corsairs-vault)**: A locked and trapped sea cave with crates still intact--some emitting light, music, or voices.
- **[The Drift Market](#the-drift-market)**: Remains of a floating settlement scattered across the coast. Debris still drifts between anchor-points.

**What's Left:**
- A [Relic](#relics) compass that doesn't point north--it spins wildly until a [Reckoning](#reckonings) ends.
- Drug caches, rare metals, and maps etched into sharkskin.
- Hidden rendezvous stones etched with [Nightweb](#the-shard--nightweb-minor-faction) symbols.

**Myths:**
- *"You can still hear their deals."* On some beaches, during storms, whispered negotiations echo faintly--deals never finished.
- *"The ocean swallows liars."* A rumored curse that drowns oathbreakers in calm water.

### The Fledges

A utopian farming commune that vanished between two [Reckonings](#reckonings). Ask the [Assembly](#the-veiled-assembly), and they will tell you: *the land does not forget its scars*.

---

<!-- CATEGORY: LORE -->
# Part VI: Lore & Background

## Relics

<!-- CATEGORY: LORE, ITEM -->

Relics are materials, substances, and sometimes objects tied to **[Precursor](#ancestors--the-precursors)** activity or the strange presence that permeates Tharros. They don't obey natural laws, and interacting with them often has unpredictable, transformative consequences.

They are:
- **Not technological.** There's no circuitry or machinery--just impossible properties embedded in matter.
- **Inconsistent.** Two identical-looking Relics may behave differently. One may hum; another may scream.
- **Dangerous.** Exposure can mutate, enchant, corrupt, or simply kill.
- **Alive, maybe.** Some scholars argue Relics react to intention, emotion, or proximity to other Relics.

**Common Types:**
- **[Relic Ore](#relic-ore)**: Glittering, unstable mineral extracted through mining. The [Syndicate](#the-ironbound-syndicate) hoards it.
- **[Relic-touched Objects](#relic-touched-objects)**: Everyday items (cups, blades, mirrors) altered by proximity to [Reckonings](#reckonings).
- **[Precursor Artifacts](#precursor-artifacts)**: Deliberately shaped, often sealed--and far more dangerous.

**Cultural Reactions:**
- The **[Church](#the-church-of-the-eternal-flame)** believes Relics are sacred or cursed divine residue.
- The **[Brotherhood](#the-remnant-brotherhood)** wants to study and contain them.
- The **[Syndicate](#the-ironbound-syndicate)** wants to exploit and sell them.
- The **[Assembly](#the-veiled-assembly)** wants to leave them untouched--or destroyed if disturbed.

### Relic Types

<!-- CATEGORY: ITEM, LORE -->

| Relic Type | Description | Danger Level | Primary Interest |
| ---------- | ----------- | ------------ | ---------------- |
| **Relic Ore** | Glittering, unstable mineral extracted through mining | Moderate | [Syndicate](#the-ironbound-syndicate) hoards it; drives [Braycall Ridge](#braycall-ridge-syndicate-stronghold) operations |
| **Relic-touched Objects** | Everyday items (cups, blades, mirrors) altered by [Reckoning](#reckonings) proximity | Variable | Collectors, [Brotherhood](#the-remnant-brotherhood) researchers |
| **Precursor Artifacts** | Deliberately shaped by [Ancestors](#ancestors--the-precursors), often sealed | High | [Brotherhood](#the-remnant-brotherhood) study; [Church](#the-church-of-the-eternal-flame) considers sacred/cursed |
| **The Carved Box** | Surface changes based on viewer (geometry/faces/roots). Mysterious key to something important. | Unknown | Connected to [Orly](#orly)'s quest to [Cape Vaidari](#cape-vaidari) |
| **The Lightspire** | Powers underground settlement of [Orvane](#orvane). Grants life but causes light-sensitivity. | High | Keeps inhabitants alive; [EFRA-7](#efra-7) seeks replacement |

### The Carved Box

<!-- CATEGORY: ITEM, HOOK -->

**Type:** Mysterious [Precursor](#ancestors--the-precursors) artifact
**Appearance:** Surface changes based on viewer--showing geometry, faces, roots, or other patterns
**Properties:** Said to be a key to something that could decide many fates
**Current Status:** In possession of [Orly](#orly)
**Quest:** Must be delivered to "[The Lighthouse at Cape Vaidari](#the-lighthouse-at-cape-vaidari)"
**Mystery:** Its true purpose and function remain unknown (GM-controlled)

### The Lightspire

<!-- CATEGORY: ITEM, HOOK -->

**Type:** Life-sustaining [relic](#relics)
**Location:** Powers the underground settlement of [Orvane](#orvane)
**Properties:** Keeps inhabitants alive but renders them light-sensitive
**Effect:** A blessing and curse intertwined--sustains life at the cost of normal existence
**Quest:** [EFRA-7](#efra-7) seeks a new energy source to replace it and free the inhabitants

---

## Ancestors / The Precursors

<!-- CATEGORY: LORE, SECRET -->

No one knows who they were, but their presence haunts Tharros.

**Physical Evidence:**
- Impossible architecture (seamless stone, floating chambers, rooms that fold inward).
- Inscriptions in no known language.
- Tombs containing no bones--only light, or sound, or echoes of thought.

**Theories:**
| Source | Belief |
| ----- | ----- |
| [Brotherhood](#the-remnant-brotherhood) | Precursors were scholars who mastered reality and transcended. We are their inheritors. |
| [Church](#the-church-of-the-eternal-flame) | The Precursors were mortals touched by the divine--now judged and purified. |
| [Assembly](#the-veiled-assembly) | The Precursors were caretakers. They're still here, watching, disappointed. |
| [Syndicate](#the-ironbound-syndicate) | Does it matter? The [Relics](#relics) work, and they pay. |
| [Nightweb](#the-shard--nightweb-minor-faction) | "We found a door that whispered our names. It wanted to come with us." |

**The Unknowable:**
Whatever they left behind isn't just a [relic](#relics)--it's a *wound in nature*, or perhaps an open door.

---

## Reckonings

<!-- CATEGORY: LORE, MECHANIC, CREATURE -->

**Reckonings** are unpredictable supernatural events that sweep across parts of Tharros. Their nature varies wildly--some resemble natural disasters, others feel more like curses, dreams, or invasions.

**Effects May Include:**
- Time distortion (hours pass in seconds, or days become frozen).
- Physical transformation (living stone, fused limbs, reversed aging).
- Emotional or mental influence (area-wide fear, euphoria, madness).
- Spatial folding (rooms that weren't there before, paths that loop infinitely).
- The appearance of [Touched/Changed/Forgotten](#touched--changed--forgotten) or [Relic-Born Beasts](#relic-born-beasts).

**Frequency:**
Reckonings occur **without reliable pattern**--though they seem more common near:
- Sites of heavy [Relic](#relics) extraction.
- [Precursor](#ancestors--the-precursors) ruins.
- Large emotional events (battles, rituals, mass grief).

**Responses:**
| Faction | Strategy |
| ----- | ----- |
| [Syndicate](#the-ironbound-syndicate) | Exploit the aftermath for [Relics](#relics); compensate affected workers. |
| [Brotherhood](#the-remnant-brotherhood) | Document, analyze, and contain. |
| [Church](#the-church-of-the-eternal-flame) | Pray, purify, and protect. |
| [Assembly](#the-veiled-assembly) | Ride it out, and learn what the land wants. |

**Rumors:**
- A Reckoning once **spoke**--and some say it never stopped.
- A settlement was once **replaced** by another version of itself, people and all.

---

## Magic

<!-- CATEGORY: LORE, MECHANIC -->

There is no magic system on Tharros--at least, not in the traditional sense.

**Instead, there is:**
- **Relic Resonance**: Some people can "feel" [Relics](#relics) or [Reckonings](#reckonings) before they occur.
- **[Precursor](#ancestors--the-precursors) Echo**: Rare individuals appear to briefly gain abilities or knowledge near [Relics](#relics), as if channeling something ancient.
- **Unknowable Influence**: Some acts of "magic" cannot be explained at all. They just happen.

**The Rule:**
If something magical occurs, it is always **rare**, **costly**, and **never fully understood**.

---

## Divinity

<!-- CATEGORY: LORE, CULTURE -->

On Tharros, the divine is felt but not explained. Settlers brought faiths from the mainland, but the island seems to respond only to one: **The Eternal Flame**.

**Imported Faiths:**
- Several gods, spirits, or philosophies were practiced on the mainland. None of them have demonstrated power on Tharros.
- Priests report silence, cold altars, and failed miracles.

**The Eternal Flame:**
- A formless, symbolic deity (or presence) associated with light, purification, endurance, and transformation.
- The only faith that seems to **receive answers** on Tharros--though those answers are cryptic.
- Its priests dream of fire and speak in metaphors they don't fully understand.

**Interpretation:**
Whether the Flame is a god, a [Precursor](#ancestors--the-precursors) remnant, or something else entirely is unknown. The [Church](#the-church-of-the-eternal-flame) claims the former. Others aren't so sure.

### Faiths and Cults by Culture

<!-- CATEGORY: CULTURE, LORE -->

| Culture | Faith(s) |
| ----- | ----- |
| [Arvelorn](#arvelorn) | The Eternal Flame (state religion) |
| [Kaelthen](#kaelthen) | Nature spirits, ancestor worship, sacred groves |
| [Vethrani](#vethrani) | Void worship (forbidden elsewhere), death cults, philosophical nihilism |
| [Corsair Clans](#corsair-clans) | Sea spirits, luck gods, ancestor ghosts |
| [Threnn](#threnn) | Spirit pacts, beast totems, blood rites |

**On Tharros:**
- **Only the Eternal Flame** seems to be heard on the island--and even then, answers are cryptic.
- Some whisper that the island *swallows* other gods... or that the [Precursors](#ancestors--the-precursors) left no room for them.

---

## The Yearning

<!-- CATEGORY: LORE, MECHANIC -->

Some who visit Tharros **cannot leave**.

Not physically--but emotionally, spiritually, obsessively.

**Symptoms:**
- Recurring dreams of specific places on Tharros.
- An urge to return, even at great personal cost.
- A sense that the island **knows them** somehow.

**Explanations:**
- **Psychological?** Trauma bonding after surviving [Reckonings](#reckonings).
- **Spiritual?** A divine or [Precursor](#ancestors--the-precursors) "call" to those sensitive to the island.
- **Parasitic?** Something in the air or water that alters willpower.

**Faction Responses:**
| Faction | Response |
| ----- | ----- |
| [Brotherhood](#the-remnant-brotherhood) | Maps Yearning cases; suspects it ties to [Relic](#relics) exposure. |
| [Church](#the-church-of-the-eternal-flame) | Believes it's a trial. "The Flame tests those who survive the island's fire." |
| [Assembly](#the-veiled-assembly) | Embraces it. "To feel the Yearning is to hear the land." |
| [Syndicate](#the-ironbound-syndicate) | Ignores it unless productivity drops. |
| [Nightweb](#the-shard--nightweb-minor-faction) | Uses it. Those affected are easier to manipulate. |

---

## Flying on Tharros

<!-- CATEGORY: LORE, MECHANIC -->

**No one flies here.**

- Birds exist but do not soar. They leap, glide, and fall.
- Magical flight fails--or worse, reverses.
- Airships stall and crash.

**Theories:**
- The [Precursors](#ancestors--the-precursors) banned it (deliberately, or as a side effect).
- The [Reckonings](#reckonings) reject movement above a certain height.
- Something in the sky is watching--and will not tolerate trespass.

**Implications:**
- Ground travel is everything. Mountains and valleys are strategic.
- Cliffs and high places are naturally defensible--but also eerie.

---

## Origin of Races

<!-- CATEGORY: LORE, CULTURE, SECRET -->

Not all colonists of Tharros are human.

### Elves

Ancient, long-lived, few in number. Elves view Tharros with wary curiosity--some believe Precursor sites echo their oldest myths.

### Dwarves

Known for craft, endurance, and loyalty to stone. The Syndicate recruits dwarven miners eagerly. Some dwarves whisper that the island's heart is hollow.

### Halflings

Nimble, adaptable, underestimated. Many work trade routes or service jobs. The Nightweb has several halfling intermediaries.

### Goblins

Often marginalized, goblins eke out existence in refuse, forgotten corners, and abandoned mines. A few have joined the Assembly.

### Orcs

Powerful and proud, orcs on Tharros mostly came as mercenaries. Some have formed their own crews or allied with Corsairs.

### Gnomes

Intellectually curious and mechanically minded. Several gnomes hold rank in the Brotherhood.

### Changelings, Tieflings, Aasimar (Rare)

These "touched" beings are looked upon with suspicion, reverence, or dread--depending on the culture. Some believe they carry traces of [Precursor](#ancestors--the-precursors) influence.

---

## Hypotheses About Magic and Relics

<!-- CATEGORY: LORE, SECRET -->

Several theories circulate about how [Relics](#relics) work and what caused the [Reckonings](#reckonings).

### Relic-Born Theory

- [Relics](#relics) are "seeds" or "fragments" of something larger.
- The [Reckonings](#reckonings) are the "blooming"--a cyclical release of stored energy.
- This explains why [Relics](#relics) cluster near [Reckoning](#reckonings) sites.

### Precursor Theory

- The [Ancestors](#ancestors--the-precursors) created the [Relics](#relics)--but lost control, or ascended.
- The [Reckonings](#reckonings) are echoes of their final act: a mass event that wiped them out or transformed them.
- Evidence: Ruins show signs of sudden abandonment, not war.

### Dimensional Leak Theory

- [Relics](#relics) are not from this world.
- The [Precursors](#ancestors--the-precursors) opened a door to another reality--and it's still cracked.
- [Reckonings](#reckonings) are moments when the leak widens.

### Symbiotic Theory ([Assembly](#the-veiled-assembly) Favored)

- The [Relics](#relics) are part of Tharros itself--a living immune system.
- The [Reckonings](#reckonings) are responses to damage: overharvesting, overbuilding, disrespect.
- The island is not malicious--it is *teaching*.

### Divine Residue Theory ([Church](#the-church-of-the-eternal-flame) Favored)

- [Relics](#relics) are the remnants of a divine war, or the ashes of failed gods.
- [Reckonings](#reckonings) are trials sent to test the faithful.
- Only through purity can the island be "healed."

---

## Other Stories and Mysteries

<!-- CATEGORY: LORE, HOOK, SECRET -->

Legends, rumors, and unexplained phenomena whispered across Tharros.

| Story/Mystery | Type | Description | Related Location | Connected To |
| ------------- | ---- | ----------- | ---------------- | ------------ |
| **The Lighthouse at Cape Vaidari** | Legend/Location | Abandoned lighthouse. On certain nights, blinks three times--"when the sea gets hungry." Destination for [The Carved Box](#the-carved-box). Nature unknown--could be [relic](#relics) beacon, natural formation, or something else. | Cape Vaidari | [Orly](#orly)'s quest |
| **The Bone Ring** | Mystery | Mining town gone in 3 years. Carved phrase: *"The ground listened. We stopped asking."* | Inland Tharros | Modern era warning |
| **The Cinnamon Beast** | Folklore | Creature from [Orly](#orly)'s grandmother's sayings. May be myth or real predator. | Unknown | Folk wisdom, winter |
| **The Pale King** | Legend | Stone statue in Gravemire Bastion that turns to face intruders over time--without movement. | Gravemire Bastion | [Pale Colonies](#the-pale-colonies) |
| **The Deep Pulse Reckoning** | Event | Major [Reckoning](#reckonings) at Spire Basin. No one who enters alone returns. | Spire Basin | [Reckonings](#reckonings) |

---

<!-- CATEGORY: CREATURE -->
# Part VII: Creatures & Monsters

## Overview

Tharros is home to beasts and beings no mainland taxonomy can classify. Some emerged from [Reckonings](#reckonings), others may predate even the [Precursors](#ancestors--the-precursors). They are not simply dangerous--they are **wrong**, in ways that disturb even hardened survivors.

**Categories:**
- **Touched**: Once-living creatures altered by [Reckoning](#reckonings) exposure.
- **Changed**: Humans or sapient beings who didn't survive a [Reckoning](#reckonings) intact.
- **Forgotten**: Creatures that may have always existed but were *unseen* until recently.
- **[Relic-Born Beasts](#relic-born-beasts)**: Entities seemingly generated by [Relic](#relics) proximity or activation.

---

## Touched / Changed / Forgotten

<!-- CATEGORY: CREATURE, LORE -->

These creatures range from tragic to terrifying.

### Shimmerglass Stag

A deer-like creature with translucent, crystalline antlers that refract light into strange colors. Harmless--until startled, when it emits disorienting light pulses.

### The Hollowed

Former settlers who survived a [Reckoning](#reckonings) but lost something inside. They wander, mute and hollow-eyed, mimicking actions from their past lives. Some still tend farms that no longer exist.

### Mireling

A swamp creature that looks like a mass of roots and mud until it moves. It ambushes by dragging prey beneath the surface.

### Voidling

A small, shadowy form that feeds on emotion. It grows larger when fear or despair are nearby. Harmless alone; deadly in swarms.

---

## Relic-Born Beasts

<!-- CATEGORY: CREATURE, LORE, SECRET -->

These entities seem to spawn from [Relic](#relics) energy, particularly during or after [Reckonings](#reckonings).

### Gloamwing

A bat-winged creature that phases in and out of visibility. It hunts by echolocation and disorientation.

### Fluxwarden

A hulking, armored beast that patrols [Precursor](#ancestors--the-precursors) ruins. It ignores those who do not touch [Relics](#relics)--but attacks with lethal precision if provoked.

### Echovore

A creature that feeds on sound. Entire camps have gone silent after an Echovore passed through.

### The Weeping Pillar

Not a creature in the traditional sense--a [Relic](#relics)-like column that "cries" and attracts wildlife. Animals near it become aggressive and coordinated.

---

## Specific Creature Entries

<!-- CATEGORY: CREATURE -->

### The Cinnamon Beast

<!-- CATEGORY: CREATURE, HOOK -->
**Description**: A strange "cinnamon-scented void-beast" with unknown true nature.
**Behavior**: Raided [Sunstorm](#sunstorm)'s caravan camp but hasn't harmed anyone since.
**Lore**: [Sunstorm](#sunstorm) was tasked to hunt it but secretly slacks on the mission. Its origins and purpose remain mysterious.

### Mirelings

**Description**: Swamp predators that appear as drifting vegetation until they strike.
**Behavior**: Ambush hunters. Drag prey into water. Dissolve bones slowly.
**Lore**: Some believe Mirelings are Touched plants, not animals.

### The Hollowed

**Description**: Empty-eyed humanoids wandering aimlessly.
**Behavior**: Non-aggressive unless provoked. May mimic past routines.
**Lore**: Victims of [Reckonings](#reckonings) who lost their "selves." The [Assembly](#the-veiled-assembly) treats them with reverence.

### Voidlings

**Description**: Small, shadowy entities that feed on negative emotion.
**Behavior**: Swarm near grief, fear, or despair. Drain willpower.
**Lore**: Some believe they're fragments of the [Precursors](#ancestors--the-precursors)' failed creations.

### Shimmerglass Stag

**Description**: Deer-like creature with crystalline antlers.
**Behavior**: Skittish. Emits blinding light when startled.
**Lore**: Prized by hunters--antlers fetch high prices but are unstable.

### Gloamwing

**Description**: Winged predator that phases in and out of visibility.
**Behavior**: Nocturnal. Uses echolocation and visual confusion.
**Lore**: The [Brotherhood](#the-remnant-brotherhood) wants specimens. The [Church](#the-church-of-the-eternal-flame) wants them burned.

### Fluxwarden

**Description**: Massive armored beast guarding [Precursor](#ancestors--the-precursors) sites.
**Behavior**: Passive until [Relics](#relics) are disturbed. Then relentless.
**Lore**: May be [Precursor](#ancestors--the-precursors) constructs. No two look alike.

---

## The Unknowable

<!-- CATEGORY: CREATURE, SECRET, HOOK -->

Some things on Tharros defy categorization entirely.

### The Singing Spine

A mountain range that hums. Explorers report dreams of being **invited inside**. See [The Singing Spine](#the-singing-spine) location entry.

### The Watcher in the Fog

A shape seen at the edge of vision during [Reckonings](#reckonings). It never approaches. It never leaves.

### The Drowned Choir

Voices heard beneath the waves near [Corsair's Vault](#corsairs-vault). They sing in no known language--but listeners sometimes understand.

### The Garden That Eats

An overgrown estate where plants move with purpose. Those who sleep there wake... different. Or don't wake at all. See [The Garden That Eats](#the-garden-that-eats) location entry.

---

<!-- CATEGORY: LORE, HISTORY -->
# Part VIII: History

## Settlement Timeline

<!-- CATEGORY: LORE, HISTORY -->

Tharros has been "discovered" and "colonized" multiple times. Each wave ended in failure, disappearance, or transformation.

### The Precursors (Unknown Era)

- Built impossible structures across the island.
- Left [Relics](#relics), inscriptions, and echoes.
- Vanished without war, plague, or visible cause.

### The Pale Colonies (~300 Years Ago)

- Imperial-era settlers from the mainland established forts and mines.
- Lasted approximately 50 years before total collapse.
- Ruins: [Gravemire Bastion](#gravemire-bastion), [Venter's Wharf](#venters-wharf).
- No survivors returned to the mainland.

### The Flame Disciples (~150 Years Ago)

- Religious pilgrims followed visions to the island.
- Established ritual sites and monasteries.
- Disappeared after attempting a "grand convergence."
- Ruins: [Ashward Steps](#ashward-steps), [The Ember Rings](#the-ember-rings).

### The Silent Trade Enclave (~80 Years Ago)

- Smugglers, corsairs, and black-market traders built hidden ports.
- Thrived for decades before a [Reckoning](#reckonings) scattered them.
- Ruins: [Corsair's Vault](#corsairs-vault), [The Drift Market](#the-drift-market).

### Current Settlers (~40 Years Ago to Present)

- Modern colonization began with [Syndicate](#the-ironbound-syndicate)-funded expeditions.
- [Brotherhood](#the-remnant-brotherhood) scholars and [Church](#the-church-of-the-eternal-flame) missionaries followed.
- The [Assembly](#the-veiled-assembly) formed from defectors and sympathizers.
- Tensions escalate as [Reckoning](#reckonings) frequency may be increasing.

---

## Recent History Timeline

<!-- CATEGORY: LORE, HISTORY, HOOK -->

| Year | Event |
| ---- | ----- |
| -40 | First modern expedition lands. [Syndicate](#the-ironbound-syndicate) stakes initial claims. |
| -35 | [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core) founded as neutral settlement. |
| -30 | [Brotherhood](#the-remnant-brotherhood) establishes [Aurel's Reach](#aurels-reach-brotherhood-hub) research outpost. |
| -28 | [Church](#the-church-of-the-eternal-flame) pilgrims found [Ashlight Monastery](#ashlight-monastery-church-enclave). |
| -25 | [Braycall Ridge](#braycall-ridge-syndicate-stronghold) mining operations begin. |
| -20 | The [Veiled Assembly](#the-veiled-assembly) emerges as organized resistance. |
| -15 | [Thistleshade](#thistleshade-assembly-stronghold) established as [Assembly](#the-veiled-assembly) refuge. |
| -12 | Major [Reckoning](#reckonings) at [Spire Basin](#spire-basin); dozens lost. |
| -10 | [Nettlehook](#nettlehook-black-market-free-port---nightweb-presence) becomes recognized black market port. |
| -8 | [Brotherhood](#the-remnant-brotherhood)-[Syndicate](#the-ironbound-syndicate) cooperation agreement signed. |
| -5 | [Church](#the-church-of-the-eternal-flame) begins aggressive missionary expansion. |
| -3 | "[The Weeping Season](#the-weeping-season)" -- three [Reckonings](#reckonings) in one month. |
| -1 | [Nightweb](#the-shard--nightweb-minor-faction) presence in [Nettlehook](#nettlehook-black-market-free-port---nightweb-presence) becomes undeniable. |
| Now | Factions consolidate. [Reckonings](#reckonings) may be increasing. Something is changing. |

---

## The Reckonings: A Pattern?

<!-- CATEGORY: LORE, MECHANIC, SECRET -->

Scholars have attempted to track [Reckonings](#reckonings) for patterns. Results are inconclusive--but suggestive.

**Possible Triggers:**
- Mass extraction of [Relic ore](#relic-ore)
- Large gatherings or emotional events
- Disturbance of [Precursor](#ancestors--the-precursors) sites
- Unknown cosmic or seasonal cycles

**Possible Patterns:**
- [Reckonings](#reckonings) cluster geographically, then shift
- Frequency has increased in recent years
- Some locations have never experienced a [Reckoning](#reckonings) (why?)

**The [Brotherhood](#the-remnant-brotherhood)'s Secret Theory:**
A sealed document suggests [Reckonings](#reckonings) are not random--they're **responses**. To what, the document does not say.

---

## The Weeping Season

<!-- CATEGORY: LORE, HISTORY, HOOK -->

A devastating period three years ago when three [Reckonings](#reckonings) occurred in a single month. Settlements were damaged, dozens were killed or Changed, and the psychological toll on survivors lingers. Some believe the frequency of [Reckonings](#reckonings) is increasing--and that the Weeping Season was only the beginning.

---

<!-- CATEGORY: NPC -->
# Part IX: NPCs

All named characters in Tharros, from faction leaders to everyday people. Major characters have links to their detailed chapters.

## Complete NPC Directory

<!-- CATEGORY: NPC -->

| Name | Type | Sex | Species | Nationality | Ethnicity/Culture | Community | Faction | Location | Role/Occupation | Description/Fun Fact |
| ---- | ---- | --- | ------- | ----------- | ---------------- | --------- | ------- | -------- | --------------- | -------------------- |
| **[Sunstorm](#sunstorm)** | PC | M | Katari | — | Caravan Katari | Wayfinder caravan | [Assembly](#the-veiled-assembly) (loosely) | Nomadic | Katari Ranger/Wayfinder | 3' tall orange tabby; hunting the [Cinnamon Beast](#the-cinnamon-beast) |
| **[EFRA-7](#efra-7)** | PC | M | Clank | — | — | Wandering construct | Seeks [Brotherhood](#the-remnant-brotherhood) | [Orvane](#orvane) | Clank Wizard construct | Seeks energy source to free [Orvane](#orvane) from [Lightspire](#the-lightspire) curse |
| **[Orly](#orly)** | PC | M | Galapa | Galari Shoals | Shoals Galapa | Lost coastal village | Unaligned | Shipwreck survivor | [Galapa](#galapa) protector | Carries [The Carved Box](#the-carved-box) to [Cape Vaidari](#cape-vaidari) |
| **[Cordyceps](#cordyceps)** | PC | M | Elf (Transformed) | — | Forest-elf enclave | Exiled outcast | Unaligned | Exiled | Wanderer (self-healing) | Suppresses forest corruption within own body |
| **[Frogulus](#frogulus)** | PC | M | Giant-frog (Giant/Ribbet) | Tharros | Ribbet poolhold | Nettlehook dockside | Unaligned; Anti-[Syndicate](#the-ironbound-syndicate); Pro-[Church](#the-church-of-the-eternal-flame-minor-faction) | [Nettlehook](#nettlehook-black-market-free-port---nightweb-presence) | Giant-frog warrior | Displaced by Syndicate "progress"; found Orly washed ashore |
| **[Magnate Theron](#magnate-theron)** | Major | M | Human | Virelia | Serenei | Virelian industrial elite | [Syndicate](#the-ironbound-syndicate) | [Braycall Ridge](#braycall-ridge-syndicate-stronghold) | Syndicate Leader | "We didn't come here to pray--we came to build" |
| **[High Archivist Alaric](#high-archivist-alaric)** | Major | M | Human | Myrrhun | Tharain | Brotherhood senior scholars | [Brotherhood](#the-remnant-brotherhood) | [Aurel's Reach](#aurels-reach-brotherhood-hub) | Brotherhood Leader | From [Myrrhun](#myrrhun-cradle-of-arcane-studies-mountainous-interior); "We are here to remember" |
| **[Maera](#maera)** | Major | F | Human | Virelia | Serenei | Assembly leadership | [Assembly](#the-veiled-assembly) | [Thistleshade](#thistleshade-assembly-stronghold) | Assembly Voice | Defector; "The island called me" |
| **[Priest-Ambassador Elyna](#priest-ambassador-elyna)** | Major | F | Human | Arvelorn | Arvelorn | Church hierarchy | [Church](#the-church-of-the-eternal-flame) | [Ashlight Monastery](#ashlight-monastery-church-enclave) | Church Leader | From [Arvelorn](#arvelorn); tired eyes, voice calms storms |
| **[Whisper](#whisper)** | Major | ? | Unknown | Unknown | Unknown | Nightweb | [Nightweb](#the-shard--nightweb-minor-faction) | Unknown | Nightweb Leader(s) | Identity unconfirmed; may be title, not person |
| Gregor | Minor | M | Human | Korralt | Panthyr | Braycall mill workers | Pro-[Syndicate](#the-ironbound-syndicate) | [Braycall Ridge](#braycall-ridge-syndicate-stronghold) | Mill foreman | Believes in "progress through hard work" |
| Daro | Minor | M | Human | Virelia | Serenei | Marrowhold tavern crowd | Pro-[Syndicate](#the-ironbound-syndicate) | [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core) | Tavern regular | Sister got prosthetic leg from Syndicate |
| Old Lenne | Minor | F | Human | Skaldmere | Nordahr | Retired miners | Anti-[Syndicate](#the-ironbound-syndicate) | Unknown | Retired miner | "They take more than they give" |
| Calia | Minor | F | Human | Korralt | Panthyr | Interior guides | [Brotherhood](#the-remnant-brotherhood)-adjacent | Tharros interior | Local guide | Worked multiple Brotherhood expeditions |
| Miran | Minor | M | Human | Virelia | Serenei | Displaced settlers | Anti-[Brotherhood](#the-remnant-brotherhood) | Former homestead | Displaced settler | Lost home to excavation claim |
| Tarel | Minor | M | Galapa | Galari Shoals | Shoals Galapa | Northern coast fishers | [Brotherhood](#the-remnant-brotherhood)-adjacent | Northern coast | Fisher | Works with survey crews for pay |
| Bennet | Minor | M | Human | Myrrhun | Tharain | Aurel's Reach scholars | Anti-[Brotherhood](#the-remnant-brotherhood) | [Aurel's Reach](#aurels-reach-brotherhood-hub) area | Scholar | Denied access to research |
| Nina | Minor | F | Human | Virelia | Serenei | Merchant widows | Pro-[Brotherhood](#the-remnant-brotherhood) | Unknown | Merchant widow | Child received Brotherhood education |
| Rhea | Minor | F | Drakona | Veskar Wards | Veskar | Thistleshade herbalists | [Assembly](#the-veiled-assembly) | [Thistleshade](#thistleshade-assembly-stronghold) | Herbalist | Critical of environmental exploitation |
| Yarin | Minor | M | Human | Kaelthen | Kaelthen | Border farmers | [Assembly](#the-veiled-assembly) sympathizer | [Marrowwood](#marrowwood) border | Farmer | Quiet Assembly supporter |
| Ilso | Minor | M | Human | Korralt | Panthyr | Refugee survivors | Anti-[Assembly](#the-veiled-assembly) | Abandoned hamlet | Refugee | Witnessed Assembly methods firsthand |
| Marda | Minor | F | Human | — | Mixed | Courier network | Neutral | Trade routes | Courier | Finds Assembly "strange but honest" |
| Kerrik | Minor | M | Human | Myrrhun | Tharain | Disgraced assistants | Ex-[Brotherhood](#the-remnant-brotherhood) | Unknown | Former assistant | Considers Assembly stubborn but principled |
| Orla | Minor | F | Human | Korralt | Panthyr | Outskirt settlers | [Assembly](#the-veiled-assembly)-adjacent | [Marrowhold](#marrowhold-first-and-central-settlement---neutral-core) outskirts | Settler | Received help from Assembly midwives |
| Verra | Minor | F | Dwarf | Korralt | Korralt Dwarven | Blacksmith family | Pro-[Church](#the-church-of-the-eternal-flame) | Unknown | Blacksmith's wife | Grateful for Church healing |
| Sarth | Minor | M | Human | Kaelthen | Kaelthen | Former Assembly | Ex-[Assembly](#the-veiled-assembly) | Unknown | -- | Thinks Church is "too soft" |
| Rund | Minor | M | Human | Skaldmere | Nordahr | Ashlight guards | [Church](#the-church-of-the-eternal-flame) | [Ashlight Monastery](#ashlight-monastery-church-enclave) | Reformed guard | Ex-Syndicate, now serves Priest Elyna |
| Jara | Minor | F | Human | Arvelorn | Arvelorn | Ember's Hollow teachers | Pro-[Church](#the-church-of-the-eternal-flame) | [Ember's Hollow](#embers-hollow) | Teacher | Believes in Church convictions |
| Hess | Minor | M | Mixed Ancestry (Human/Elf) | — | Mixed | Wandering performers | Wary of [Church](#the-church-of-the-eternal-flame) | Wandering | Bard | Has witnessed the Church's darker side |
| Tanis | Minor | M | Infernis | Hollow Marches | Infernis | Nettlehook dockhands | [Nightweb](#the-shard--nightweb-minor-faction)-adjacent | [Nettlehook](#nettlehook-black-market-free-port---nightweb-presence) | Dockhand | Appreciates Syndicate honesty about motives |

---

<!-- CATEGORY: MECHANIC -->
# Part X: Mechanics & GM Tools

## Faction Reputation System

<!-- CATEGORY: MECHANIC -->

Track PC standing with each major faction using a simple scale:

| Level | Status | Effects |
| ----- | ------ | ------- |
| -3 | Hostile | Attacked on sight. Bounties issued. |
| -2 | Distrusted | Denied services. Watched closely. |
| -1 | Unfavorable | Higher prices. Cold reception. |
| 0 | Neutral | Standard treatment. |
| +1 | Favorable | Minor discounts. Friendly contacts. |
| +2 | Trusted | Access to restricted areas/info. |
| +3 | Allied | Full support. Leadership contact. |

**Actions that affect reputation:**
- Completing faction missions (+1 to +2)
- Sabotaging faction operations (-1 to -2)
- Public support or criticism (+/- 1)
- Major betrayal or heroism (+/- 3)

---

## Reckoning Effects Table

<!-- CATEGORY: MECHANIC, CREATURE -->

Roll or choose when a Reckoning occurs:

| d10 | Effect |
| --- | ------ |
| 1 | Time Slip - Hours pass in minutes, or vice versa |
| 2 | Emotional Wave - Area-wide fear, rage, or euphoria |
| 3 | Spatial Fold - Rooms rearrange, paths loop |
| 4 | Creature Emergence - Touched/Changed appear |
| 5 | Relic Bloom - New Relics manifest from stone/air |
| 6 | Memory Echo - Visions of past events replay |
| 7 | Physical Transformation - Matter changes state |
| 8 | Sensory Distortion - Sounds become colors, etc. |
| 9 | The Watching - Something observes. Nothing more. |
| 10 | The Speaking - A voice addresses someone directly |

---

## Random Encounter Seeds

<!-- CATEGORY: HOOK, MECHANIC -->

| d8 | Encounter |
| -- | --------- |
| 1 | Syndicate patrol checking papers and cargo |
| 2 | Brotherhood surveyors mapping a Reckoning site |
| 3 | Assembly scouts observing from concealment |
| 4 | Church missionaries offering aid and sermons |
| 5 | Nightweb contact with a "business proposition" |
| 6 | Touched creature behaving strangely (not hostile... yet) |
| 7 | Refugees fleeing a settlement after a Reckoning |
| 8 | Rival adventurers seeking the same objective |

---

## Adventure Hooks

<!-- CATEGORY: HOOK -->

1. **The Missing Survey Team**: A Brotherhood team vanished near the Singing Spine. Their last message mentioned "an invitation."

2. **Syndicate Strike**: Workers at Braycall Ridge are planning a strike. Both sides want the PCs to tip the balance.

3. **The Flame's Vision**: A Church priest has dreams of a Relic that could "heal the island." Its location matches a Syndicate excavation.

4. **Assembly Sabotage**: The Assembly needs supplies smuggled into Thistleshade. The route passes through Nightweb territory.

5. **Reckoning Survivors**: A village survived a Reckoning intact--but residents don't remember the last three days.

6. **The Carved Box**: Rumors of a Precursor artifact that shows different things to different viewers. Multiple factions want it.

7. **Nettlehook Debts**: A PC's contact is in deep with the Nightweb. They need help--or they'll start talking.

8. **The Hollowed Child**: A Changed child was found near Marrowhold. It speaks prophecy. Everyone wants custody.

---
