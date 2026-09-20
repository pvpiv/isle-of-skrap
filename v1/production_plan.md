# Production Plan: The Isle of Skrap

**Goal:** Create a professional, "dev-ready" submission package for the Jagex Player Designed Island Competition.
**Output Directory:** `.cursor/sketches/` (User to create folder)
**Master Document:** `.cursor/submission_draft.md`

---

## 1. Naming & Organization Protocol
*   **File Naming:** `Sketch_[ID]_[Description].png` (e.g., `Sketch_1.1_Map_Overview.png`)
*   **Versioning:** If iterating, append `_v2`, `_v3`.
*   **Format:** Clear line art or annotated diagrams. No "AI Slop". Focus on readability.

---

## 2. Asset Task List (For Agents/User)
*Current Phase: Visualization*

### Series 1: Geography & Layout (Art Team)
- [x] **Task 1.1:** Create `Sketch_1.1_Map_Overview.svg`
    - *Subject:* Top-down view of the crescent/atoll shape.
    - *Annotations:* Label "Flotsheim (North)", "Jettstrom (South)", "The Gutter (Center)", "The Bridge".
- [x] **Task 1.2:** Create `Sketch_1.2_Flotsheim_Section.svg`
    - *Subject:* Side-view/Cutaway of the "Vertical Favela".
    - *Detail:* Show stacked ship hulls, rope ladders, and the "Whale Ribcage Bank".
- [x] **Task 1.3:** Create `Sketch_1.3_Jettstrom_Docks.svg`
    - *Subject:* Isometric view of the industrial docks.
    - *Detail:* Show the "Stream Incinerator" vent and the large Crane.
- [x] **Task 1.4:** Create `Sketch_1.4_Full_Side_Profile.svg`
    - *Subject:* Silhouette of the island showing the volcano underwater.
- [x] **Task 1.5:** Create `Sketch_1.5_Flotsheim_Floors.svg`
    - *Subject:* Top-down floor plans for Levels 0, 1, 2, 3.
    - *Detail:* Show ladder/stair connections and the "Whale Ribcage" interior.
- [x] **Task 1.6:** Create `Sketch_1.6_Minimap_Preview.svg`
    - *Subject:* OSRS Minimap style view of the island.
    - *Detail:* Water blue background, brown/grey landmasses, and standard Map Icons (Bank, Quest, Transport).

### Series 2: Mechanics & UI (Dev/UX Team)
- [x] **Task 2.1:** Create `Sketch_2.1_Recycler_Interface.svg`
    - *Subject:* UI Mockup for the "Reverse Smithing" interface.
    - *Flow:* Input Slot (Platebody) -> Arrow -> Output Slot (Ores) + Chance %.
- [x] **Task 2.2:** Create `Sketch_2.2_Contract_Board.svg`
    - *Subject:* The "Salvage Contract" interaction.
    - *Text:* "Wanted: 5x Driftwood Planks. Reward: 50 Scrap."

### Series 3: Mood & Aesthetics (Audio/Narrative Team)
- [x] **Task 3.1:** Create `Sketch_3.1_NPC_Concepts.svg`
    - *Subject:* "Flotsheim Hoarder" (bulky, many bags) vs "Jettstrom Trader" (sleek, holding clipboard).

---

## 3. The Storyboard (Implementation Guide)
*This section maps the assets to the submission text for the Jagex Team.*

### Slide 1: High Level Concept
> **Text:** "The Isle of Skrap is a singular landmass divided by a cultural feud..."
> **Visual Reference:** `Sketch_1.1_Map_Overview.png`
> **Dev Note:** Use standard island generation templates (similar to Fossil Island small islands).

### Slide 2: The Flotsheim District (Bank)
> **Text:** "A vertical maze of rigging... The Grand Hold is inside a leviathan's ribcage."
> **Visual Reference:** `Sketch_1.2_Flotsheim_Section.png`
> **Dev Note (Environment):** Reuse "shipwreck_01" and "whale_bones_large" assets.
> **Dev Note (Audio):** Creaking wood loops, wind occlusion.

### Slide 3: The Jettstrom District (Utility)
> **Text:** "Industrial cranes and the Recycler..."
> **Visual Reference:** `Sketch_1.3_Jettstrom_Docks.png`
> **Dev Note (Mechanics):** Crane activity reuses Port Piscarilius crane code (Asset ID: `crane_repair`).

### Slide 4: The Recycler Mechanic (Timeless Feature)
> **Text:** "One man's trash... Turn alchables into raw resources."
> **Visual Reference:** `Sketch_2.1_Recycler_Interface.png`
> **Dev Note (Balancing):** Output should be ~40-60% of GE value in raw mats to prevent economy breaking.

---

## 4. Instructions for Future Agents
1.  **Check Status:** Read this file to see which Sketches are unchecked `[ ]`.
2.  **Context:** Read `.cursor/submission_draft.md` for the specific lore details of that sketch.
3.  **Execution:**
    - If generating art (ASCII/SVG/Description): Output the file to `.cursor/sketches/`.
    - If guiding user: Provide the specific prompt or description for them to draw.
4.  **Update:** Mark the task as `[x]` and add the filename to the Storyboard section if changed.

