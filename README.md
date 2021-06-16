### Important
- This mod requires [AceCoreLib](https://gitlab.com/accensi/hd-addons/acecorelib).
- To cast self/mass spells, look at your feet and summon a rune. When casting such spells, you must be within the sigil to be able to activate the runes.
- When casting targeted spells, you can only activate the runes from behind. There is an angle limit so you cannot cheese runes from behind a corner.
- Touch spells require the rune to be within 2m of the target.
- Gold numbers denote values that change with spell level.
- When updating the mod after new spells have been added, use `ARC_ReInitSpells` to refresh the list. Existing spells will not be reset.

### Notes
---
- Loadout code is `arc`.
- Configuration codes are:
	- `blues`: Starting blues.
- Catalyst is the amount of blues you need to have to begin casting a spell. Cost is what will be deducted upon casting.

### Known Issues
---
- Sometimes some runes can spawn above the sigil when floors are involved. This is unfixable due to the engine not allowing anything below the floor or above the ceiling unless it has +NOINTERACTION, but at that point you would be completely unable to trigger the runes.

### Incompatibilities
---
- Josh's Action Bubbles seems to make the rune activation not work unless you are crouching. This is an issue with the Player Heading feature. Turn it off and Arcanum will work.