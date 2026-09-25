## What's Changed

### Features
- Blind mode in the Map settings: the map shows only what you see yourself and what your PDA reveals. Squads, outposts and garrisons report nothing, your own faction included. It overrides fog of war, remembered owners still work from your own sightings, and a new game starts with every base unknown
- A new game offers to simulate the Zone for up to 20 days before you start
- ZCP compatibility is applied automatically for ZCP 1.4 and 1.5; the separate ZCP patch is gone
- ZCP can choose Warfare's mutant spawns, behind a new setting
- Offline fights between mutants and humans are decided by species relations
- With ReDone Collection installed, main bases move to where it puts faction traders (untested)
- In story mode Warfare squads stay off smarts locked by quests
- Loners and ecologists rest as guests on bases of factions they are not at war with

### Improvements
- Performance pass: targeting, offline combat, fog of war and the simulation tick do much less work on busy saves

### Bug Fixes
- Fix Warfare's squad sizing never running
- Fix mutant lairs re-sending the squad already there instead of the new one
- Fix a crash in patrol attack rolls on a squad that no longer exists
- Fix a base's own defense counting the distance power multiplier twice
- Fix protected main bases passing to friendly factions
- Remove the story/warfare incompatibility note from the new-game tooltips
