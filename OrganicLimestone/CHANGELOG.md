# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.0] - 2026-06-10

This is just a minor updated that "made" me update the mod itself to latest SML version. The mod worked prior to this, but I just decided to do it and killed two birds with one stone.
I just found (after a hiatus without playing Satisfactory) that the outputs of both the Wood and Leaves were a bit overtuned (specially the Wood one) so I just "downgraded" them just to make sure both respect the intended progression.

### Changed

- [Tweaked] Recipe to produce Leaves from Limestone in the Constructor (Unlocked at Tier 0 - HUB Upgrade 3)

```cpp
4 Limestone (60 per min) => 1 Leaves (15 per min)
Produced in: Constructor, Crafting Bench
Production Rate: 15 per min
Cycle Time: 4 sec
```

- [Tweaked] Recipe to produce Wood from Limestone in the Constructor (Unlocked at Tier 0 - HUB Upgrade 3)

```cpp
12 Limestone (72 per min) => 1 Wood (6 per min)
Produced in: Constructor, Crafting Bench
Production Rate: 6 per min
Cycle Time: 10 sec
```

## [1.2.0] - 2026-06-10

This update was brought to you courtesy of an issue someone posted over on the Github page [Suggestion: Alt recipe for refinery/blender](https://github.com/ShinryuAspect/SatisfactoryModsCollection/issues/1).

### Added

- Alternate recipe to produce Biomass and a Liquid Biofuel byproduct from Limestone in the Refinery (Unlocked at Tier 5 - Oil Processing)

```cpp
4 Limestone (30 per min) + 4.8 Water (36 per min) => 8 Biomass (60 per min) + 2.0 Liquid Biofuel (15 per min)
Produced in: Refinery
Production Rate: 60 per min
Cycle Time: 8 sec
```

- Alternate recipe to produce Biomass and a Liquid Biofuel byproduct from Limestone in the Blender (Unlocked at Tier 7 - Control System Development)

```cpp
6 Limestone (90 per min) + 0.8 Nitric Acid (12 per min) + 3.6 Water (54 per min) => 10 Biomass (150 per min) + 2.8 Liquid Biofuel (42 per min)
Produced in: Blender
Production Rate: 150 per min
Cycle Time: 4 sec
```

- Alternate recipe to produce Leaves and a Liquid Biofuel byproduct from Limestone in the Refinery (Unlocked at Tier 5 - Oil Processing)

```cpp
2 Limestone (20 per min) + 3.2 Water (32 per min) => 4 Leaves (40 per min) + 0.8 Liquid Biofuel (8 per min)
Produced in: Refinery
Production Rate: 40 per min
Cycle Time: 6 sec
```

- Alternate recipe to produce Leaves and a Liquid Biofuel byproduct from Limestone in the Blender (Unlocked at Tier 7 - Control System Development)

```cpp
6 Limestone (90 per min) + 1.2 Nitric Acid (18 per min) + 3.2 Water (48 per min) => 20 Leaves (300 per min) + 1.6 Liquid Biofuel (24 per min)
Produced in: Blender
Production Rate: 300 per min
Cycle Time: 4 sec
```

- Alternate recipe to produce Wood and a Liquid Biofuel byproduct from Limestone in the Refinery (Unlocked at Tier 5 - Oil Processing)

```cpp
8 Limestone (48 per min) + 4.0 Water (24 per min) => 4 Wood (24 per min) + 2.0 Liquid Biofuel (12 per min)
Produced in: Refinery
Production Rate: 24 per min
Cycle Time: 10 sec
```

- Alternate recipe to produce Wood and a Liquid Biofuel byproduct from Limestone in the Blender (Unlocked at Tier 7 - Control System Development)

```cpp
10 Limestone (100 per min) + 1.6 Nitric Acid (16 per min) + 3.2 Water (32 per min) => 6 Wood (60 per min) + 3.2 Liquid Biomass (32 per min)
Produced in: Blender
Production Rate: 60 per min
Cycle Time: 6 sec
```

### Changed

- Update mod's description

## [1.1.1] - 2026-06-06

### Fixed

Wrong SML version dependency

## [1.1] - 2026-06-06

### Added

- Recipe to produce Leaves from Limestone in the Constructor (Unlocked at Tier 0 - HUB Upgrade 3)

```cpp
4 Limestone (60 per min) => 2 Leaves (30 per min)
Produced in: Constructor, Crafting Bench
Production Rate: 30 per min
Cycle Time: 4 sec
```

- Recipe to produce Wood from Limestone in the Constructor (Unlocked at Tier 0 - HUB Upgrade 3)

```cpp
6 Limestone (36 per min) => 2 Wood (12 per min)
Produced in: Constructor, Crafting Bench
Production Rate: 12 per min
Cycle Time: 10 sec
```

### Changed

- Migrate the mod to no longer depend of [ContentLib](https://ficsit.app/mod/ContentLib)

## [1.0.0] - 2025-09-30

Initial release

### Added

- Recipe to produce Biomass from Limestone in the Constructor (Unlocked at Tier 0 - HUB Upgrade 6)

```cpp
6 Limestone (60 per min) => 4 Biomass (40 per min)
Produced in: Constructor, Crafting Bench
Production Rate: 40 per min
Cycle Time: 6 sec
```
