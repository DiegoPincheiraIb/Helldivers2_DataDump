# Helldivers 2 Data Dump
Standalone repository; originally a fork of [Shalzuth's repository](https://github.com/shalzuth/HelldiversData).

Given it is a standalone version of a fork, **it is still incomplete**. I am currently migrating data from the fork to this repository.

Structure can (and will) differ from Shalzuth's original datamining.

There are two main branches of this repository:
1. **Post EAC:** Current game's data, contained on `main` branch.
2. **Pre EAC:** Data up until 7.1.X. Mainly used for Hellforge projects. Located on `7.1.X` branch.

## Repository Structure

There are five main folders for the data:
1. Components: Includes all `structs`.
2. Entities: **Main data dump.** Contains data from `generated_entities.dl_bin`.
3. Entity Deltas: Entity Deltas data dump. Contains data from `generated_entity_deltas.dl_bin`.
4. Enums: Contains documented **enum** parameters. They are inferred rather than datamined directly, **so they may be incomplete/wrong.**
5. Settings: Complementary data dump. Contains data from `generated_XXXX_settings.dl_bin`.
6. Translations: Contains strings related to the game. Mainly retrieved from Strings folder of [AsunderKnight's repository](https://github.com/asunderknight/HD2-leaks).

