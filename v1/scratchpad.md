# OSRS Player Designed Island Submission

## Background and Motivation
The user wants to participate in Jagex's "Player Designed Island Competition".
**Concept:** "The Isle of Skrap" (Flotsheim/Jettstrom).
**New Requirement:** Create a **Minimap Style** sketch (`Sketch_1.6`) that accurately represents the island's layout and scale, based on provided reference images (Pandemonium, Northern Ocean map).

## Key Challenges and Analysis
- **Minimap Aesthetic:** OSRS minimaps use specific colors (Water `#6277cf`, Land `#6f4e37`, Dots, Icons).
- **Scale:** User provided a "7x7 room" reference. Skrap is ~120x120 tiles. The minimap must reflect this density.
- **Location:** Must fit into the "Northern Ocean" gap (Image 7) north-east of Neitiznot.
- **Verticality:** Minimaps are 2D. We will depict the "Top-Down" view of the walkable surfaces.

## High-level Task Breakdown
1.  **Create `Sketch_1.6_Minimap_Preview.svg`:**
    - **Base:** OSRS Water Blue background.
    - **Style:** Flat, sharp edges (pixel-art style vector).
    - **Features:**
        - **Flotsheim:** Brown ship decks, connected by tan bridges.
        - **Jettstrom:** Grey dock platforms.
        - **Icons:** Yellow `$` (Bank), Blue Anchor (Sailing), Quest Star.
    - **Context:** Include a rough outline of the "Northern Ocean" islands (Neitiznot edge) for placement context, or just focus on the island itself with a "World Map" border.
2.  **Verify Scale:** Ensure the buildings drawn look like they could fit a 7x7 grid inside.

## Project Status Board
- [x] Brainstorm Concepts
- [x] Select Final Concept
- [x] Create Technical Sketches (1.1 - 1.5)
- [ ] **Create Minimap Sketch (1.6)** (In Progress)
- [ ] Final Package

## Executor's Feedback or Assistance Requests
- **Action Required:** Generate the Minimap SVG.
