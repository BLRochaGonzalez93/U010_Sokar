# U010_Sokar

[English](README.en.md) | [Español](README.md)

## Summary

Complete concept/GDD for a first-person 3D horror experience. **SOKAR: La Venganza del Mal** proposes a psychological horror adventure where Daniel Hernández returns to the family house after his father's death and becomes trapped between a deteriorated everyday reality and a supernatural dimension tied to a curse.

The design focuses on an immersive experience based on exploration, tension, sound, stealth, flashlight usage, puzzles and an unpredictable demonic entity.

## Collaboration

Concept project developed together with **Hugo C.R.** and **Sergio M.C.**  
My planned contribution focuses on gameplay programming, interaction system, stealth, audio detection, limited combat, performance and technical structure.

## Documentation

- [`GDD_SOKAR_LaVenganzaDelMal.pdf`](../Media/Diagrams/GDD_SOKAR_LaVenganzaDelMal.pdf)
- 
## Planned technologies

- Unity
- C#
- Unity 3D physics system
- First Person Controller
- UI
- AudioSource
- Post Processing
- Lighting
- Blender
- Substance Painter
- Photoshop
- Visual Studio
- Git LFS
- GitHub

## Documented design

- First-person 3D horror.
- Mystery story and family curse.
- Protagonist: Daniel Hernández.
- Main enemy: Sokar.
- Main environment: the Hernández family house.
- Parallel world / supernatural dimension.
- Deteriorated, oppressive and changing house.
- Demonic entity with human and canine traits.
- Initial menu integrated into a wall with blood stains.
- Minimalist HUD to preserve immersion.
- Planned controls for gamepad and keyboard/mouse.
- Progressive difficulty curve.
- Replayability through endings, secrets, collectibles and achievements.

## Planned systems

- `FirstPersonController`
- `InteractionSystem`
- `StealthSystem`
- `AudioDetectionSystem`
- `FlashlightSystem`
- `DynamoRechargeSystem`
- `InventorySystem`
- `PuzzleSystem`
- `JumpscareManager`
- `SokarAI`
- `SaveLoadSystem`
- `UIManager`
- `SoundManager`
- `NarrativeManager`

## Planned mechanics

- First-person movement.
- House exploration.
- Interaction with doors, drawers, keys, notes and objects.
- Limited combat using environment objects.
- Stealth, hiding spots and silent movement.
- Audio detection in stealth mode.
- Strategic flashlight usage.
- Manual dynamo recharge.
- Limited inventory.
- Environmental recognition.
- Visual and audio clues.
- Numeric lock puzzle.
- Vial puzzle.
- Key search.
- Symbols and rituals.
- Collectibles and voice recordings.
- Random jumpscares.
- Multiple endings.
- Achievements.

## Content pending development

There are no scripts or playable build at this stage. The project is documented as a complete concept and design.

Next steps:

- Create a base prototype in Unity.
- Implement first-person controller.
- Implement interaction system.
- Implement flashlight and dynamo recharge.
- Implement limited inventory.
- Implement stealth system.
- Implement audio detection.
- Implement Sokar stealth mode.
- Implement random jumpscares.
- Implement main puzzles.
- Create the family house greybox.
- Create the first version of the Sokar entity.
- Add minimalist HUD.
- Create save/load system.
- Prepare the first playable demo.

## Planned architecture

The initial architecture could be organized into:

- `Player` — controller, camera, input and movement.
- `Interaction` — interactable objects, doors, drawers, keys and notes.
- `Stealth` — hiding spots, crouching, sound and detection.
- `Sokar` — AI, chase, stealth mode and events.
- `Inventory` — slots, usable items and key items.
- `Flashlight` — light, energy, dynamo and consumption.
- `Puzzles` — locks, vials, symbols and rituals.
- `Narrative` — diary, dialogues, scenes and events.
- `UI` — HUD, pause, options, inventory and sound meter.
- `Audio` — footsteps, ambience, scares, demon and dynamic music.
- `Save` — save, load and progress.

## Screenshots

> Final screenshots pending.

Planned path:

![Gameplay](./Media/screenshots/gameplay-01.png)

## Build

There is currently no public release available.

**Build coming soon.**

## Status

**Concept / complete GDD.**

The project includes detailed documentation, but it is not yet in playable development phase.

## Learnings

This project allowed me to design a complete GDD for a 3D horror experience.

It also helped me plan stealth, audio and exploration systems, as well as tension mechanics based on flashlight, sound and hiding spots.

In addition, it allowed me to work on narrative design through mystery, diary, symbols, rituals and a family curse, together with environment-integrated puzzles.

Finally, the project helped define a minimalist UI focused on immersion and a team production structure with programming, FX and modeling roles.
