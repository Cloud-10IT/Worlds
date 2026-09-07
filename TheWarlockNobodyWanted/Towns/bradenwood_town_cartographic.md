# CARTOGRAPHIC REFERENCE: BRADENWOOD TOWN
**Map Code:** `bradenwood_town_cartographic`  
**Region:** Shadow Coast  
**Scale:** 1 Grid Square = ~20 Feet  
**Orientation:** West-Facing Waterfront (Port / Sea)

---

## OVERVIEW & KEY MAP LEGEND

This document maps every lettered node (`A` through `O`) on the top-down cartographic layout (`image_5.png`) for **Bradenwood Town**. Use these letter anchors in your visual prompts and scene descriptions to maintain 100% spatial consistency.

```
                  [H: NORTH GATE]
               (2 Guards, 1 on Wall)
                         |
  +----------------------|----------------------+
  |                   [A: HOMES]                |
  |  [G: LOGGERS]                [F: CLOTHIER]  |  
  |             [D: TOWN TAVERN]                |
  | [B: BLACKSMITH]              [E: JEWELER]   |-- [I: EAST GATE]
  |                   [A: HOMES]                |   (2 Guards, 1 on Wall)
  | [C: DOCK TAVERN]                            |
[M: PORT]                                       |
  |                                             |
[O: LIGHTHOUSE]                                 |
  +----------------------|----------------------+
                         |
                  [J: SOUTH GATE]
               (2 Guards, 1 on Wall)
```

---

## NODE DIRECTORY & SPATIAL ANCHORS

### Defensive Perimeter & Fortifications
* **`H` — North Gate (Entrance):** Main northern thoroughfare into the cobblestone grid. Flanked by two blue stone watchtowers. Guarded by 2 infantry at ground level and 1 marksman/scout on the wide parapet.
* **`I` — East Gate (Entrance):** Eastern access portal facing the dense Shadow Coast woodlands (`K`). Maintained by a 3-guard detachment.
* **`J` — South Gate (Entrance):** Southern exit pathway leading toward coastal lowlands. Includes a dedicated guardhouse and blue stone parapet walk.
* **Blue Stone Wall (Perimeter):** 8-foot-tall, wide-topped blue masonry rampart enclosing nodes `A` through `G`. Wide enough for 3 armed guards to walk side-by-side.

### Waterfront & Maritime District (West Side)
* **`M` — The Port / Docks:** Extensive wooden piers, stone wharves, and moorings along the western shoreline. Handles merchant ships, fishing vessels, and regional sea trade.
* **`O` — The Lighthouse:** Positioned on a rocky promontory directly south of the port (`M`). Houses a high-elevation beacon casting light over the sea approaches and jagged coastal cliffs (`L`).
* **`C` — Dockside Tavern:** Situated directly inside the western blue stone gate/wall, steps away from the port docks (`M`). Serves sea captains, sailors, and dockworkers.

### Commercial & Artisan District
* **`B` — Blacksmith Forge:** High-heat stone workshop located on the western inner ring. Supplies ironwork, weapons for the gate guards (`H`, `I`, `J`), and ship repairs for the port (`M`).
* **`E` — Jeweler Shop:** Located along the eastern inner thoroughfare. Deals in gems, refined metals, and luxury goods for wealthy sea captains.
* **`F` — Clothier / Tailor:** Positioned near the north-eastern commercial sector. Crafts heavy cloaks, sails, and formal attire.

### Industry, Hospitality & Residential
* **`D` — Town Center Tavern:** Primary social hub located in the heart of the central cobblestone square. Catering to locals, loggers, and off-duty guards.
* **`G` — Loggers Guild & Timber Yard:** Sprawling northeastern yard with raw logs, sawing frames, and timber storage brought in from the northern woods (`K`).
* **`A` — Residential Dwellings / Homes:** Multi-story stone and timber homes arrayed along the paved cobblestone streets.

### Surrounding Environment
* **`K` — Northern & Eastern Forest:** Thick pine/hardwood forest bordering the North (`H`) and East (`I`) gates.
* **`L` — Coastal Cliffs & Shoals:** Jagged rock formations flanking the outer harbor north and south of the port (`M`).
* **`N` — Compass Rose & Sea Navigation:** Western ocean expanse along the Shadow Coast.

---

## SCENE GENERATION PROMPT ANCHORS

When writing ComfyUI direct injection prompts for scenes set in Bradenwood, reference the specific letter anchors:

* **Scene set at Port/Lighthouse:**
  > `"Camera tracking low across the cobblestone pier at Node M (The Port), looking south toward Node O (The Lighthouse) rising above the blue stone sea wall..."`
* **Scene set at North Entrance:**
  > `"Eye-level wide shot of Node H (North Gate). Two guards with spears stand at the timber doors, with a third guard patrolling the 8-foot blue stone wall parapet above..."`
* **Scene set in Town Square:**
  > `"Medium dolly shot moving down the central cobblestone street between Node D (Town Center Tavern) and Node B (Blacksmith forge)..."`
