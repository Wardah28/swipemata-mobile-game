# Pitch: Swipemata 
------------------------------------------------------------------------------------------------------------------------------------
Genre: Hybrid-casual puzzle | Platform: Android, portrait | Controls: One thumb | Engine: Unity 6 / C#

Pitch: Draw a shape, spawn a tiny autonomous robot, and combine robot abilities to solve satisfying 1–3-minute puzzles.
------------------------------------------------------------------------------------------------------------------------------------
## Core loop
Draw → Spawn → Watch → Solve → Earn → Upgrade.

The player draws one gesture on the arena:

Circle: Creates a Collector Bot that automatically gathers nearby crystals.

Straight Line: Creates a Runner Bot that dashes in the drawn direction to activate switches.

Zigzag: Creates a Breaker Bot that approaches and destroys nearby fragile obstacles.

Each robot acts autonomously. The challenge is choosing the correct shape, location, and sequence to complete each puzzle.
------------------------------------------------------------------------------------------------------------------------------------
## Meta
Completing levels and collecting crystals rewards players with DNA Sparks, the in-game currency.

Players spend DNA Sparks on laboratory upgrades, such as increased collection range, faster robots, and lab decorations. Currency, upgrades, and progress are saved locally.
------------------------------------------------------------------------------------------------------------------------------------
## Why come back?
Players return to improve their level ratings, complete challenges using fewer gestures, collect more DNA Sparks, and unlock laboratory upgrades.

Each level can be replayed to earn up to three stars based on efficiency and completion time.
------------------------------------------------------------------------------------------------------------------------------------
## Who and when
Designed for casual mobile players who enjoy quick, creative puzzles.

Session length: 1–3 minutes.

Suitable for short breaks, commuting, and everyday mobile gaming.
------------------------------------------------------------------------------------------------------------------------------------
## Goals
The initial version contains three levels:

Level 1 — Crystal Nest: Collect all five crystals using the Collector Bot to unlock the gate.

Level 2 — Long Hall: Use the Runner Bot to activate a distant switch and open the exit.

Level 3 — Combo Lab: Combine all three robots: break obstacles, collect crystals, and activate the final switch.

Measurable progress: Completed levels, stars earned, crystals collected, DNA Sparks accumulated, and upgrades unlocked.
------------------------------------------------------------------------------------------------------------------------------------
## Feel
The game should feel playful, responsive, satisfying, and rewarding.

Colorful swipe trails, adorable robots, sparkling crystal collection, satisfying destruction effects, animations, sound effects, and subtle vibrations provide immediate feedback.

The visual style will use simple or free assets, prioritizing enjoyable gameplay and responsive controls.
------------------------------------------------------------------------------------------------------------------------------------
## Scope & Engineering Focus
The initial solo scope is three short, data-driven levels with one gesture-based mechanic, three autonomous robot behaviors, and a simple currency/upgrade system.

Development focuses on gesture recognition, finite-state machines, level objectives, data-driven design, local persistence, and testing using Unity and C#.
