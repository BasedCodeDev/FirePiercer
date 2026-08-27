> **Want to play Fire Piercer?** Visit the [official itch.io page](https://duckpondstudios.itch.io/fire-piercer-sun-jam-2026) for the Windows download, screenshots, release information, and comments.

# Fire Piercer

Fire Piercer is a top-down local cooperative game about outrunning an impending blizzard aboard a train powered by the Last Dragon. Keep the Dragon's Heart burning, repair the route ahead, and make the right track changes to survive.

The game was created for **Sun Jam 2026** in Sunshine Coast, Queensland, Australia, around the keywords **Activate & Heat**.

This repository contains the Unreal Engine source project behind the game. The [itch.io page](https://duckpondstudios.itch.io/fire-piercer-sun-jam-2026) is the main public home for Fire Piercer and the best place for players to download it.

## Gameplay

- Apply the brakes to buy time, but do not stop for too long—the blizzard is closing in.
- Collect coal and throw it into the Dragon's Heart to keep the train moving.
- Collect wood and use it to repair bridges.
- Toggle trackside switches to choose the train's route.

## Development

Fire Piercer is built with **Unreal Engine 5.7** using C++ and Blueprint assets. Development is currently set up for Windows.

### Requirements

- Unreal Engine 5.7
- Visual Studio with the components listed in [`.vsconfig`](.vsconfig)
- Git LFS

### Getting started

1. Clone the repository.
2. Run `git lfs pull` to fetch Unreal assets.
3. Open `TrainGame.uproject` in Unreal Engine 5.7.
4. If prompted, allow Unreal Engine to rebuild the project modules.

The default editor and game map is `Content/Maps/LVL_TestMap.umap`.

### Repository layout

- `Source/TrainGame/` — gameplay code for the player, train, resources, tracks, bridges, and game framework.
- `Plugins/Interaction/` — the reusable actor interaction system.
- `Content/` — maps, Blueprints, art, animation, audio, UI, and other Unreal assets.
- `Config/` — project, engine, and input configuration.
- [`TECH_SPEC.md`](TECH_SPEC.md) — early architecture and implementation notes.

## Team

- Christian — Lead Programmer
- Seb — Art, Design & Code
- Zack — UI and Sound
- Jacqui — Concept Artist

Created by [Duck Pond Studios](https://duckpondstudios.itch.io/) and [hogs9](https://hogs9.itch.io/).
