# WORLD BIBLE

## Series

**Title:** *The Warlock Nobody Wanted*

## Purpose

This document is the entry point for the complete World Bible used by Qwen3 and AnythingLLM.

It does not replace the detailed canon files. It identifies the authoritative sources, establishes the story's verified starting state, and defines how retrieved information must be interpreted.

All story generation, episode planning, scene writing, character dialogue, image prompts, and video prompts must comply with this document and the files listed below.

---

# REQUIRED AUTHORITY ORDER

When sources disagree, use this order of authority:

1. `00_Master_Canon.md`
2. `State/CONTINUITY_STATE.md`
3. `Lore/Timeline.md`
4. `01_Master_Prompt.md`
5. `02_World_Map.md`
6. `Characters/Main_Character.md`
7. `Characters/Character_Appearance_Guide.md`
8. `Characters/Relationship_Matrix.md`
9. Other files in `Characters/`
10. Files in `Regions/`
11. Files in `Classes/`
12. Other files in `Lore/`
13. Files in `Episodes/`

A lower-authority document must never overwrite a higher-authority document.

If two same-level sources conflict, report the conflict instead of selecting or inventing an answer.

---

# VERIFIED STORY-START FACTS

These facts are fixed at Episode 0 and must be used during validation.

## Main Character

**Name:** Aldric Voss  
**Age:** 50 years old  
**Life Stage:** Young adult under this world's aging standard  
**Gender:** Male  
**Height:** 6 feet, or 183 centimeters  
**Class:** Warlock  
**Hidden Path:** Sovereign, not publicly known at story start  
**Current Rank:** F Rank  
**Current Army Size:** 0  
**Current Territory:** None  
**Political Influence:** None  
**Known Relics:** None at Episode 0  
**Known Formal Allies:** None at Episode 0  
**Known Formal Enemies:** None at Episode 0  
**Home Region:** Ashen Frontier

Aldric is kind, humble, charismatic, compassionate, responsible, and protective. He assists people in need without expecting payment or recognition.

Aldric has secretly practiced limited Warlock abilities in the Blackwood since awakening at age sixteen. He concealed this training because Warlocks are mocked, distrusted, and rejected. His secret preparation gives him discipline and knowledge, but it does not give him an army before the story begins.

---

# WORLD AGING STANDARD

**Average human lifespan:** 200 years

General life stages:

- Ages 0 to 15: Child
- Ages 16 to 40: Youth
- Ages 40 to 75: Young adult
- Ages 75 to 125: Middle age
- Ages 125 to 175: Senior
- Ages 175 to 220: Elder
- Ages 220 and above: Exceptional longevity

Aldric must not be described as elderly or physically old merely because he is 50.

---

# SOCIETY

The population consists of Awakened and Unawakened people.

Most people are Unawakened and possess no class ability. Unawakened people include villagers, farmers, craftspeople, merchants, ordinary soldiers, scholars, nobles, politicians, kings, queens, princes, and emperors.

Political authority and class power are separate. A ruler may have no class ability, while an Awakened individual may possess great combat power without holding legal authority.

---

# THE TWELVE GREAT CLASSES

The recognized classes are:

1. Warrior
2. Hunter
3. Mage
4. Monk
5. Paladin
6. Priest
7. Rogue
8. Shaman
9. Warlock
10. Death Knight
11. Demon Hunter
12. Druid

No additional class may be invented during validation or ordinary scene generation unless a new class is explicitly approved as a major canon addition.

Warlock is publicly regarded as the lowest-prestige class.

Detailed rules are stored in the individual files under `Classes/`.

---

# LEGION DOMINION

Legion Dominion is not a faction, religion, kingdom, or enemy organization.

Legion Dominion is the lost Sovereign Warlock authority over armies, soldiers, commanders, battlefields, military knowledge, fortresses, and conquest.

Its potential capabilities include:

- Summoning spectral soldiers
- Raising eligible fallen warriors under established limits
- Restoring forgotten military units
- Recruiting defeated enemies under defined conditions
- Summoning ancient commanders
- Absorbing battlefield memories
- Developing troop specializations
- Establishing military strongholds

At Episode 0, Legion Dominion is dormant and Aldric's army size is zero.

Its activation, limitations, costs, and growth must follow `Characters/Main_Character.md`, `Classes/Warlock.md`, `Lore/Power_System.md`, `State/CONTINUITY_STATE.md`, and the chronological episodes.

---

# THE ANCIENT WARLOCK EMPIRE

The Ancient Warlock Empire was real.

Its original Warlocks were Sovereigns rather than merely demonic summoners. The empire united different classes and regions and followed the Sovereign Doctrine, which taught that power exists to protect and leadership is service.

The empire fell during the Sundering War. Its records, relics, and history were later suppressed or destroyed. Modern official history falsely portrays Warlocks as useless, cursed, or inherently dangerous.

The Ancient Warlock Empire must not be described as an evil world-conquering cult unless a character is repeating known propaganda and the narration clearly identifies that claim as propaganda or incomplete knowledge.

Detailed canon is stored in `Lore/Ancient_Warlock_Empire.md`.

---

# FIXED REGIONS

The established world regions include:

- Ashen Frontier
- Crimson Deserts
- Ember Crown
- Forbidden North
- Golden Sea
- Iron Peaks
- Shadow Coast
- Wildheart Expanse
- Oceans and established sea routes

Region names, positions, climates, capitals, terrain, and dominant cultures are controlled by `02_World_Map.md` and the corresponding files in `Regions/`.

Do not invent a capital, relocate a city, change a climate, or rename a region when the relevant source is missing from retrieval. State that the answer cannot be verified from the retrieved canon.

---

# GEOGRAPHICAL CONTINUITY

The world map is fixed.

Geography may change only because of an explicit in-story event such as:

- Natural disaster
- War damage
- Powerful magic
- Activation of a major artifact
- A specifically authorized world-changing plot event

Any geographical change becomes permanent canon and must be recorded in both:

- `State/CONTINUITY_STATE.md`
- `Lore/Timeline.md`

---

# CINEMATIC FORMAT

The series uses a widescreen movie presentation.

**Required aspect ratio:** 16:9

Scenes should use:

- Cinematic establishing shots
- Wide environmental compositions
- Character-focused medium shots
- Emotional close-ups
- Consistent costumes and physical features
- Region-specific weather, architecture, and lighting
- Movie-style sound design and pacing

Do not default to vertical 9:16 composition.

Do not add subtitles, captions, logos, or overlay text unless explicitly requested.

---

# EPISODE CONTINUITY

Before creating an episode or scene:

1. Check `00_Master_Canon.md`.
2. Check `State/CONTINUITY_STATE.md`.
3. Check `Lore/Timeline.md`.
4. Check the current episode or preceding episode when available.
5. Check all directly relevant character, class, region, faction, artifact, and relationship files.
6. Verify the current location, date, rank, army size, injuries, equipment, relationships, knowledge, and unresolved events.
7. Use only information supported by retrieved canon.
8. Do not silently resolve contradictions.
9. Do not create facts during a validation request.
10. Treat completed episodes as recorded history.

---

# KNOWLEDGE BOUNDARIES

Narrator knowledge and character knowledge are different.

A character may know only what that character has:

- Personally witnessed
- Been told by a credible source
- Learned from a discovered record
- Deduced from available evidence
- Been granted through an established magical ability

Do not allow characters to know Aldric's hidden path, Legion Dominion, secret training, relic discoveries, or Warlock history before the story establishes how the knowledge was obtained.

---

# RETRIEVAL AND VALIDATION RULES

When responding to a World Bible validation request:

- Use retrieved documents only.
- Do not generate dramatic prose.
- Do not add a cliffhanger.
- Do not invent names, ranks, cities, armies, classes, factions, or historical events.
- Cite the source filename after each answer when requested.
- If the answer is unavailable, respond: `NOT FOUND IN RETRIEVED CANON`.
- If sources conflict, respond: `CANON CONFLICT`, then list the conflicting filenames and values.

The model must never claim to have read a file that was not retrieved or included in context.

---

# EPISODE 0 STATE

At the opening of the story:

- Aldric Voss is 50 years old.
- Aldric is a Warlock at F Rank.
- Aldric lives in or near the Ashen Frontier.
- Aldric has no army.
- Legion Dominion is dormant.
- The world does not know Aldric's true potential.
- Aldric has practiced limited abilities secretly in the Blackwood since age sixteen.
- Aldric helps people in need.
- The Ancient Warlock Empire remains suppressed history.
- No world geography has been altered by the current story.
- No completed episode has yet changed the timeline.

---

# FINAL DIRECTIVE

Treat the World Bible as established reality.

Preserve geography.

Preserve history.

Preserve character identity.

Preserve power-system limitations.

Preserve consequences.

When canon is missing, say that it is missing.

Never replace missing canon with invention during validation.
