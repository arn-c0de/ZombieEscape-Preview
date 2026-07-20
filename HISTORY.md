# ZombieEscape — Project History

This page preserves notable moments in ZombieEscape's development, from the first playable map experiments to the current survival simulation. It is a visual milestone log rather than a complete list of every code change.

New milestones, screenshots, and short retrospectives will be added as the project grows. For exact version-by-version changes, see the [Changelog](CHANGELOG.md).

---

## November 2025 — The first playable world

ZombieEscape began as an Android experiment that placed a player, zombies, buildings, and loot on a real-world map. The earliest versions established the systems that still define the game: a home safezone, location-based movement, survival values, building searches, world events, and persistent progress.

The screenshot below comes from the early 1.x period. It shows the original dark map presentation with large colored markers, a dense zombie population, the first safezone/home marker, the early HUD, and the joystick-based manual controls.

<div align="center">
  <img alt="Historical ZombieEscape screenshot showing the early zombie map and HUD" src="images/zombies.png" width="360" />
  <br />
  <em>Early ZombieEscape 1.x: the first zombie-heavy map and safezone gameplay.</em>
</div>

### Early foundations

- **1.0.1:** Initial project and first playable release.
- **1.0.3–1.0.7:** Building loot, item effects, food use, loot packages, pickup range, events, the traveling trader, and home-base fixes.
- **1.0.8:** GPS/manual movement was consolidated and the original direction buttons were replaced by a joystick.
- **1.0.9:** Larger world-data tiers, new area types, revised zombie spawning, armor/effect integration, and configurable building visibility.
- **1.0.10–1.0.11:** The first vehicle system, driving, vehicle storage, and a redesigned main menu.

---

## December 2025 — From survival prototype to living simulation

The project expanded rapidly beyond the initial map-and-loot loop. NPCs gained autonomous goals, homes, inventories, hunger, thirst, medical needs, and combat behavior. Vehicles, the medical model, and the main user interface became persistent game systems rather than isolated experiments.

### Simulation and progression milestones

- **1.1.0:** Z-LIFE simulation tools, improved NPC pathfinding, collision avoidance, and AI-versus-AI combat.
- **1.1.1:** Adaptive pathfinding experiments and simulator-to-game tuning workflows.
- **1.1.2:** Persistent player inventory, NPC homes and storage, stronger database handling, vehicle improvements, and combat fixes.
- **1.1.3:** Body-part medical gameplay, compact inventory mode, skills presentation, map zoom preferences, and additional building areas.
- **1.1.4–1.1.6:** NPC healing, attack modes, food and water needs, item hauling, house ownership, raids, and multilingual support.

---

## July 2026 — A connected survival sandbox

By version 1.1.8, ZombieEscape had become a connected open-world survival sandbox. The major systems now interact: time and lighting affect the world, NPCs follow daily routines, houses can be claimed and raided, survivors can be recruited, equipment is visible on a paperdoll, and weapons can be customized.

### Major expansion

- **1.1.7:** Security hardening, broad codebase cleanup, and improved automated checks.
- **1.1.8:** Weapon attachments, enterable interiors, power and lighting, persistent cooking stations, player housing, survivor rescue, raids, day/night presentation, improved combat effects, vehicle animation, inventory grids, and plan-then-steer A* navigation.
- **1.1.9:** Expanded interiors, improved interior loot and NPC healing, the first power-grid foundation, enterable shops, and further navigation fixes for dense adjacent buildings.

The current public screenshots are available in the [README](README.md). They show how far the interface, world presentation, and connected game systems have progressed since the early screenshot above.

---

## Future milestones

This history will grow alongside the game. Future entries should capture meaningful player-facing steps such as:

- Public test builds and release milestones
- Major world, survival, combat, NPC, housing, or vehicle expansions
- Important visual redesigns with before/after screenshots
- Community testing milestones
- The first stable public release

### Entry format

When adding a milestone, use a dated heading, a short explanation of why it mattered to players, a focused list of changes, and one representative image where possible. Detailed patch notes belong in the [Changelog](CHANGELOG.md); this file should tell the broader story.

---

**Navigation:** [README](README.md) | [Player Wiki](wiki/Home.md) | [Future Plans](PLANS.md) | [History](HISTORY.md) | [Changelog](CHANGELOG.md)
