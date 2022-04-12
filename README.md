### Important
- This mod requires [AceCoreLib](https://gitlab.com/accensi/hd-addons/acecorelib).
- To cast self/mass spells, look at your feet and summon a rune. When casting such spells, you must be within the sigil to be able to activate the runes.
- When casting targeted spells, you can only activate the runes from behind. There is an angle limit so you cannot cheese runes from behind a corner.
- Touch spells require the sigil to be within 2m of the target.
- Gold numbers denote values that change with spell level.
- When updating the mod mid-playthrough after new spells have been added, use `ARC_ReInitSpells` to refresh the list. Existing spells will not be reset.

### Notes
---
- Loadout code is `arc`.
- Configuration codes are:
	- `blues`: Starting blues. Up to 4 digits.
- Blue barrels may spawn in place of regular explosive barrels. To utilize them, you need to have a partial potion on you. Using the barrel will fill it up. One barrel is the equivalent of 5 potions, or 2 soulspheres. Barrel can be shot and will leak! It can also break if it takes too much damage.

### How it works
- Blues are absorbed passively into the tome at a standard rate of one bluesphere per 20 minutes. That rate grows or shrinks depending on the current amount of blues you have in you. More spheres means faster absorption and vice versa. You can't eat a single bluesphere and become a god of death.

### Known issues
---
- Sometimes some runes can spawn above the sigil when floors are involved. This is unfixable due to the engine not allowing anything below the floor or above the ceiling unless it has +NOINTERACTION, but at that point you would be completely unable to trigger the runes.

### Incompatibilities
---
- Josh's Action Bubbles seems to make the rune activation not work unless you are crouching. This is an issue with the Player Heading feature. Turn it off and Arcanum will work.