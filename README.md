# Island Exploration Sandbox

First-person 3D exploration scene in Unity. The player picks up objects, places them on triggers to unlock a teleport between two areas (beach and basement), with the ambient audio mix swapping in real time when they cross over. Unity coursework, 2024.



## Tech

- C#
- Unity
- First-person controller
- Trigger zones and audio mixing

## What I built

- **Interaction layer** — pickup and put-down logic with raycast targeting, object follow on a held offset, drop physics on release.
- **Trigger system** — placement zones detect the right object, lock/unlock state, fire the teleport when conditions are met.
- **UI state** — locked vs. unlocked indicators, contextual interaction prompts.
- **Audio control** — ambient mix swap on area transition, source enable/disable on the receiving end.

Environment uses licensed low-poly asset packs; all interaction, audio, and trigger logic is mine.

## Running it

Clone, open in Unity 2022.3+ LTS, open the main scene, press Play.

## Contact

[willluar.github.io](https://willluar.github.io) · williamcj@hotmail.co.uk
