# ZombieEscape — Future Plans

ZombieEscape is under active development. This page collects the main directions, larger ideas, and long-term goals currently being considered for the game.

> This is a living roadmap, not a promise of features or release dates. Priorities can change as systems are tested, performance is measured, and player feedback arrives.

---

## Core priorities

### Co-op multiplayer

Explore ways for players to survive together in the same world. Possible co-op features include shared exploration, group combat, trading, shared bases, cooperative events, survivor settlements, and synchronized vehicles.

Multiplayer requires careful work on networking, synchronization, persistence, security, and the interaction between GPS and manual movement. It is therefore a long-term direction rather than a near-term promise.

### Farming and renewable resources

Add farming as a longer-term survival system for homes and settlements:

- Planting, watering, growth, and harvesting
- Different crops, seeds, yields, and growth times
- Weather, daylight, soil, power, and water requirements
- Food preservation and cooking integration
- Farm plots, greenhouses, and suitable furniture or tools
- NPC survivors helping with settlement agriculture

The goal is to give established players a renewable food source without removing the need to explore and scavenge.

### Combat System V2

Continue the combat overhaul with clearer feedback, more tactical choices, and stronger integration with injuries, equipment, skills, and the world:

- Improved melee and ranged combat flow
- Better target selection and reaction controls
- More meaningful weapon handling, reloads, ammunition, range, and accuracy
- Expanded dodge, defense, cover, stealth, and status mechanics
- Smarter enemy tactics and group behavior
- Better combat animations, effects, sound, and readability
- Further balancing of armor, body-part damage, injuries, and healing
- More combat encounters and enemy varieties

### Crafting and Housing V2

Turn crafting and housing into deeper, connected progression systems:

- More recipes, materials, tools, workstations, and skill requirements
- Recipe discovery and clearer progression
- Repair, maintenance, dismantling, and material recovery
- Larger furniture and construction catalogues
- Better blueprint planning, placement, rotation, and room organization
- Stronger defenses, traps, gates, barricades, and raid preparation
- Expanded storage, utilities, power, lighting, water, cooking, and sleeping
- More meaningful house upgrades and settlement specialization
- Improved survivor roles and work inside player-owned homes

---

## World and character presentation

### World paperdoll characters

Replace the purely top-down player and NPC presentation with more expressive paperdoll-based world figures. Equipment, clothing, weapons, injuries, and selected visual traits should be recognizable directly on the map.

Planned exploration includes:

- Angled or perspective-aware figures instead of completely top-down sprites
- Directional walking, running, shambler, combat, and vehicle animations
- Visible armor, backpacks, clothing, weapons, and attachments
- More variation between players, survivors, raiders, traders, and zombies
- Reuse of the equipment paperdoll layers where practical

### Higher-resolution visual assets

Improve the clarity and consistency of weapons, items, equipment, characters, vehicles, furniture, buildings, effects, and interface art:

- Higher-resolution item and weapon artwork
- More detailed attachment and modified-weapon visuals
- Consistent scale, lighting, outlines, and color language
- Improved paperdoll and world-sprite layers
- Better map markers and combat effects
- Device-aware assets that remain readable on small screens without wasting memory

The aim is a clearer and more polished style while preserving good Android performance.

---

## More content

### More items in every category

Expand the item catalogue across the whole survival loop:

- Food, drinks, ingredients, seeds, and cooked meals
- Medical supplies, medicines, diagnostics, and treatment tools
- Melee weapons, firearms, bows, ammunition, and explosives
- Armor, clothing, backpacks, masks, footwear, and protective gear
- Crafting resources, tools, components, and repair parts
- Furniture, containers, workstations, defenses, and utilities
- Vehicle parts, fuel-related items, upgrades, and cargo equipment
- Rare, specialist, event, faction, and location-specific loot

New content should have a useful role, sensible spawn locations, balanced weight and rarity, and clear visual identity.

### More weapons and attachments

Grow the modular weapon system with additional firearms, melee weapons, bows, and compatible parts:

- Stocks, grips, optics, sights, magazines, barrels, and muzzle devices
- Suppressors, lights, lasers, slings, and specialist attachments
- Clear compatibility rules and slot information
- Visible attachment combinations on previews, inventory icons, paperdolls, and world figures
- Meaningful trade-offs involving damage, accuracy, range, handling, weight, noise, and capacity
- Expanded crafting, looting, trader, repair, and rarity integration

---

## Polish and quality

### Interface and gameplay polish

- More consistent screens, navigation, icons, spacing, and terminology
- Better onboarding, contextual help, player wiki coverage, and accessibility
- Clearer feedback for distance, requirements, cooldowns, danger, and failure states
- More animation, audio, haptics, and visual effects where they improve readability
- Improved save handling, migration, recovery, and player-facing error messages
- Continued balance passes across loot, survival, combat, progression, trading, and raids

### Performance improvements

Performance remains a permanent development priority, especially on mid-range and older Android devices:

- Faster initial world and building loading
- Improved caching and reduced network/data usage
- More efficient map rendering, marker updates, and animated assets
- Continued NPC pathfinding, collision, goal-selection, and simulation optimization
- Lower memory use and fewer unnecessary background operations
- Smoother menus, inventories, interiors, combat effects, and large NPC populations
- Better measurement, regression testing, and device-specific tuning

### More language support

Expand localization beyond the currently supported languages:

- Translate player-facing screens, items, tutorials, messages, and documentation
- Improve terminology consistency and remove hard-coded text
- Support longer translations and different layouts cleanly
- Add translation review and contribution guidance
- Consider right-to-left and non-Latin scripts where technically practical

---

## Further ideas

Other areas being considered include:

- More building interiors, shops, landmarks, and location-specific gameplay
- Weather, seasons, environmental hazards, and world ambience
- Deeper factions, reputation, quests, dialogue, and settlement relationships
- Expanded events, raids, rescues, convoys, crashes, and world encounters
- More vehicles, aircraft, upgrades, damage, repair, and fuel gameplay
- Improved NPC personalities, routines, professions, cooperation, and settlement roles
- Achievements, challenges, difficulty options, and long-term progression
- Better testing tools and balancing workflows for the connected simulation

---

## Want to help?

Help is welcome in Android/Kotlin development, game systems, multiplayer research, UI/UX, pixel art and animation, item art, sound, balancing, testing, accessibility, documentation, and translation.

If you would like to contribute in one of these areas, please [open an issue](https://github.com/arn-c0de/ZombieEscape-Preview/issues/new) in the public preview repository. Include:

- The area you want to help with
- A short description of your idea or proposed contribution
- Relevant experience or examples of previous work, if available
- The language, device, or game system involved

The main source repository is private, so access and collaboration are considered individually. Please do not post passwords, access tokens, private keys, or sensitive personal/location information.

---

**Navigation:** [README](README.md) | [Player Wiki](wiki/Home.md) | [Future Plans](PLANS.md) | [Project History](HISTORY.md) | [Changelog](CHANGELOG.md)
