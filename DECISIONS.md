# Decision log

Add an entry every time the team makes a real choice: a tool, a design, a trade-off.
About 1–2 entries a week. Newest at the top. Write the reasoning yourselves; AI may fix the wording.

## Template
```
## YYYY-MM-DD — [The decision, in a few words]
Options: [A] / [B] / [C]
Chose: [what] — [why]
AI: [what the AI suggested, and what you did with it — or "not used"]
Who: [name(s)]
```

## Example
```
## 2026-11-20 — Save progress locally first
Options: PlayerPrefs / JSON file / Cloud Save
Chose: JSON file now, Cloud Save later
Why: works offline, easy to move later
AI: suggested a SQLite database — rejected, too heavy for one save file
Who: Yuval
```

---

<!-- Your entries start here -->

# Decision log

This file documents the team's game design and engineering decisions.

## 2026-11-05 — Choose Swipemata as our mobile game concept

**Options:** One-thumb endless runner / Sorting puzzle / Gesture-based autonomous robot puzzle (Swipemata)

**Chose:** Swipemata — a hybrid-casual puzzle game where drawing a circle, straight line, or zigzag creates a robot with a specific autonomous behavior.

**Why:** The concept fits the course requirements: Android portrait mode, one-thumb controls, 1–3 minute sessions, a simple core loop, and measurable goals. The initial version can be developed with three levels and a small upgrade system. It also offers meaningful software engineering challenges, including gesture recognition, finite-state machines, data-driven levels, and saving player progress. We chose to limit the initial scope to three predefined gestures instead of implementing unrestricted drawing recognition or complex AI models.

**AI:** ChatGPT helped brainstorm different game concepts, suggested the shape-to-robot mechanic, and assisted with drafting the pitch and decision log. The final choice and scope are reviewed and approved by the team.

**Who:** Wardah Abu Freih

  
