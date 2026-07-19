
**Navigation:** [README](README.md) | [Changelog](CHANGELOG.md)

# CHANGELOG

All notable changes to this project are documented in this file. This is the same
version history as the private development repository, provided here so the public
preview stays traceable version by version.

---

## [1.1.9] - 2026-07-19 (current)

### Added
- Interior systems expansion with improved loot and NPC healing.
- Power-grid M7 foundation and enterable shops.

### Fixed
- NPC getting stuck in the nook between adjacent buildings: the A* start is now
  relocated with a connectivity-aware search that stays on the agent's own side of
  the walls, and the relocated start is kept as the first waypoint so the agent is
  guided out of the pocket instead of steered into the wall.
- House weight fix.

---

## [1.1.8] - 2026-07-19

### Added
- **Weapon attachment system:** modular attachment workbench with a live pixel-art
  view, six new attachments (wood stock, red dot, long-range scope, drum mag, holo,
  compensator), distinct weapon sprites, an inventory MOD badge and slot upgrade hints.
  Weapon rendering is unified across icon, preview and paperdoll.
- **Interiors, power & lighting:** interior power/lighting design and interior planning.
- **Modular map-asset system** with animated forest vegetation and animated vehicle
  map sprites (plus interaction guards); documented for future extension.
- **Realistic NPC life simulation:** day/night routine, sleep and personality traits
  (shown in the NPC popup), plus an NPC behaviour-goal simulator with reporting, drift
  detection and goal chains (and a `run.sh` launcher).
- Player house ownership, NPC house raids and a survivor-rescue event.
- NPC combat with retaliation AI and a building long-press menu.
- Persistent campfire and stove cooking system.
- App-wide day/night theme with themed colors and toggle, real-time time-of-day
  lighting and a clock HUD.
- Node-mapped POI fetching (fuel stations, shops).
- Map combat FX (floating damage numbers, health bars), inventory grid, item icons
  and paperdoll icons.
- A* plan-then-steer pathfinding in both the app and the Python simulator.
- Expanded whole-app test suite with real-data coverage; combat, NPC, vehicle and
  medical-supply test suites.

### Changed
- Modernized UI: dark theme, Material 3 look, redesigned HUD and new icons.
- Reorganized the game package into logical sub-packages.
- Polished crafting and trader-menu integration; modernized game menus and expanded
  NPC controls.
- Medical treatments now consume inventory supplies.
- Decoupled item emoji from names and centralized loot spawn rates.
- Sped up OSM loading with Overpass mirror failover and parallel fetches; stale OSM
  cache is auto-invalidated.

### Fixed
- Movement anisotropy fix and non-blocking building loads while driving.
- Map lifecycle performance.
- OSM 403 tile block resolved by sending a policy-compliant User-Agent.
- NPCs stuck in "Sell Surplus" (unable to deposit trade money, or while wounded /
  unable to reach the trader).
- NPCs fleeing zombies when their ranged weapon is out of ammo.
- Nap loop that stalled all NPCs.
- Inventory & looting refactor: item data loss, thread-safety and coroutine scopes.

---

## [1.1.7] - 2026-07-16

### Added
- CodeQL dual-database security scanning.

### Changed
- Split large classes into modules, removed dead code and translated the codebase
  to English.
- Refined game systems and simplified documentation.

### Fixed
- Security fixes.
- Pass the Activity context to the `CombatSystem` constructor.
- English string fixes.

---

## [1.1.6] - 2025-12-05

### Added
- Multi-language support implementation.
- NPC raid house feature with select all button.
- Batch save system with per-NPC save throttling.

### Fixed
- NPC behavior fixes.

---

## [1.1.5] - 2025-12-05

### Added
- NPC house persistence and ownership logging.
- NPC food and water system.
- NPC item hauling and using system.

### Fixed
- NPC goal fixes and return home behavior while fighting.
- NPC behavior fixes for eating, drinking, and goals.

---

## [1.1.4] - 2025-12-04

### Added
- NPC healing system and behavior.
- NPC attack modes.
- NPC medical combat overhaul.
- NPC medical system implementation.
- Documentation navigation improvements.

### Fixed
- NPC collision pusher fix.

---

## [1.1.3] - 2025-12-04

### Added
- Map zoom preference setting.
- Database info display in main menu.
- New building area types and fetching phases 4 + 5.
- Inventory compact mode.
- Main menu tab persistence feature.
- New medical system.
- Main menu skills modular 2x grid layout.
- Vehicle icon map rotation.
- Main menu performance optimizations.

### Changed
- Map icon stutter softening.

### Fixed
- Quick action menu fixes.
- Stats fixes.
- Combat system logic and integration fixes.
- Stamina regeneration fix.
- Fetch fixes.

---

## [1.1.2] - 2025-12-03

### Added
- Clear NPC house inventory button.
- NPC home icons and info stats.
- Database thread safety improvements.
- CoroutineScope, DAO bulk operations, debounced saves implementation.
- Documentation sorting.

### Changed
- Vehicle speed improvements.
- NPC combat vs player bridge refactor.
- Player inventory to database with hardening.
- Housing and location manager refactoring.

### Fixed
- NPC combat vs player fixes.
- SpatialHashGrid fixes in Kotlin and Python.
- NPC home item save and load fixes.
- NPC behavior for looting and storing items.
- License fix in README.
- Various small fixes.

---

## [1.1.1] - 2025-12-02

### Added
- Adaptive Pathfinding Learning System (APLS):
	- Modern self-improving pathfinding system that learns from each simulation round.
	- Uses evolutionary algorithms and gradient-based optimization to tune parameters.
	- Features adaptive heuristic tuning and multi-objective optimization (speed, path quality, success rate).
- NPC pathtrace full implementation with Python bridge live tuning.
- Python dashboard parameter settings menu.
- Self-training, bridge, and auto-inject by approval.

### Changed
- Various pathfinding fixes and improvements.

### Fixed
- NPC behavior fixes.
- Python simulation tool fixes.

---

## [1.1.0] - 2025-12-02

### Added
- Z-LIFE Simulator Python integration and tools.
- Python-Kotlin bridge for AI training.
- Pathfinding bridge service for improved AI.
- New pathfinding and collision avoidance for NPCs.
- Bidirectional combat system for Z-LIFE.
- Paveway helper tuning and improvements.

### Changed
- Major improvements to pathfinding and collision logic.
- Refined combat system logic for AI vs AI.
- Various fixes and tuning in simulation and dashboard tools.

### Fixed
- Multiple bugfixes in simulation, dashboard, and spawn logic.
- General code and documentation fixes.

---

## [1.0.11] - 2025-12-01

### Added
- Vehicle inventory mode trigger.
- Credits / Attribution page.
- Car driving implementation (phase 1/2).

### Changed
- Refactored VehicleManager.
- Improved building/area database fetch system.
- Tuned player movement performance.
- New main menu.

### Fixed
- Vehicle base-inventory and transfer fixes.
- Vehicle eject fix.
- Misc UI fixes and fetch/markdown fixes.

---

## [1.0.10] - 2025-12-01

### Added
- Vehicles feature (Phase 1).
- Vehicle system resources (entities, manager & UI helpers).
- Vehicle-related icons and docs.

---

## [1.0.9] - 2025-12-01

### Added
- Building visibility radius setting and building fetch improvements.
- Settings menu updates for building fetching.
- New area types, zombies, and walkable areas.
- Vehicle items (phase 1).

### Changed
- Keep building outlines visible while allowing hide of filled areas/icons.
- Merge changes to MainActivity to keep road loading for all tiers.
- Loot balancing and effect armor integration.

### Fixed
- Zombie spawning fixes.
- Language and other minor fixes.

---

## [1.0.8] - 2025-11-30

### Added
- Documentation phase 1.

### Changed
- Collision pusher integration implementation.
- Player manual building collision improvements.
- Manual movement fixes.
- Replaced buttons with joystick for movement.
- PlayerMovementManager: GPS and manual movement system.

---

## [1.0.7]

### Fixed
- Map tile cache fixes.
- Home Base options bug.

### Added
- Event location database integration.

### Changed
- Item spawn quantity fixes.
- Item spawn overhaul implementation.
- Wandering trader feature.
- Alert status improvements.

---

## [1.0.6]

### Added
- Loot pickup range feature.

### Changed
- Loot package overhaul.

---

## [1.0.5]

### Changed
- Loot table updates.

---

## [1.0.4]

### Fixed
- Revive inventory clearing bug.

### Changed
- Food use improvements.
- Effect manager enhancements.

---

## [1.0.3]

### Added
- Loot building areas feature.

---

## [1.0.1]

### Initial Release
- Initial project setup and codebase.

---

**Note:** For versions without explicit release notes, changes are inferred from commit messages. For more detailed information, refer to the commit history.
