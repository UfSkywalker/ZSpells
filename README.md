# ZSpells

A spell mod for **Baldur's Gate: Enhanced Edition**, **Baldur's Gate II: Enhanced Edition** and **EET**. It adds spells from Pathfinder: Kingmaker, Pathfinder: Wrath of the Righteous and Neverwinter Nights, together with three mythic spells and a few original ones.

Chinese documentation: [README.schinese.md](README.schinese.md)

## Requirements

- Baldur's Gate: Enhanced Edition, Baldur's Gate II: Enhanced Edition, or EET
- Enhanced Edition games only

## Installation

1. Extract the release package into your game folder, so that `Setup-ZSpells.exe` and the `ZSpells` folder sit next to the game executable. This repository does not include the prebuilt installer; the release package does.
2. Run the installer:
   - **Windows:** `Setup-ZSpells.exe` (or rename a WeiDU binary to `Setup-ZSpells.exe`)
   - **macOS / Linux:** run your WeiDU binary from the game folder, for example `./weidu ZSpells/Setup-ZSpells.tp2`
3. Choose a language: **English** or **Simplified Chinese**.
4. Install the main component. The two Improved Anvil components are optional.

## Components

| Component | Description |
| --- | --- |
| 0 (main) | Adds Z's spell notes and the spells recorded in them. |
| 1 | Improved Anvil only: restores the original Project Image, Simulacrum, Spell Trap and Chain Contingency, and removes Hand of Undoing, Tenser's Partial Transformation and Monster Summoning VII. Requires Improved Anvil. |
| 2 | Improved Anvil only: restores the original Staff of the Magi. Requires Improved Anvil. |

## Z's spell notes

Once the mod is installed you can buy Z's spell notes from shops and study them. There are 13 different notes:

- Z's PF Spell Notes - Battering Blast
- Z's PF Spell Notes - Mage Armor
- Z's PF Spell Notes - Low Transmutation - Ability Enhancement
- Z's PF Spell Notes - Defense, Detection and Retreat
- Z's PF Spell Notes - Enchantment - Empowerment
- Z's PF Spell Notes - Destruction
- Z's PF Spell Notes - Necromancy
- Z's Spell Notes - Original - Corrupt Elements
- Z's PF Spell Notes - Conjuration and Elements
- Z's PF Spell Notes - Protection and Spellbreaking
- Z's Mythic Spell Notes - Absolute Death
- Z's Mythic Spell Notes - Corrupt Magic
- Z's Mythic Spell Notes - Threefold Wish

They can be bought from:

- Thalantyr (High Hedge)
- Halbazzer Drin (Sorcerous Sundries, Siege of Dragonspear only)
- Ribald (Adventurer's Mart)
- Lazarus Librarus (Saradush)

If **IWD1_EET** or **IWD2_EET** is installed, they are also sold by:

- Orrick the Grey (Kuldahar)
- Elytharra (Targos Town)

If you have already visited these shops before installing the mod, you need to start a new game.

## Spells

**Level 1:** Mage Armor I (PF), Expeditious Retreat (PF), Enlarge Person (PF), Reduce Person (PF), Shield (PF)

**Level 2:** Bull's Strength, Cat's Grace, Bear's Endurance, Fox's Cunning, Owl's Wisdom, Eagle's Splendor, Animalistic Power (NWN2)

**Level 3:** Heroism (PF), Rage (PF) - the barbarian's fury, Keen Edge (PF), Battering Blast (PF)

**Level 4:** Mage Armor II (PF), Prismatic Orb (NWN2), Controlled Fireball (a 4th-level fireball with no friendly fire), Lesser Ruby Ray of Reversal

**Level 5:** Echolocation (PF) - a transmutation True Sight, Mass Stoneskin (PF) - costs material components, Greater Rage - the berserker's raging attack, Corrupt Elemental Bomb - original

**Level 6:** Greater Heroism (PF), Battering Blast (Heightened/Piercing) - the metamagic version, ignores magic resistance, Hellfire Ray - use it a few times and you will see how it differs between Baldur's Gate and Wrath of the Righteous, Disintegrate (PF version), Greater Remove Magic

**Level 7:** Mage Armor III (PF), Finger of Death (PF version), Undeath to Death (NWN version) - the Neverwinter version, though the icon is still the PF one, Greater Spell Shield, Greater Breach

**Level 8:** Stormbolts, Battering Blast (Heightened/Piercing/Empowered), Greater Corrupt Elemental Bomb - original

**Level 9:** Mage Armor IV (PF), Heroic Invocation, Wail of the Banshee (PF version), Mass Greater Spell Shield, Mage's Disjunction

**Mythic:** Absolute Death, Corrupt Magic, Threefold Wish

## Learning mythic spells

- character level 20 or higher
- a Wisdom score above 22
- permanently losing 1 point of Wisdom and 100,000 experience points when the spell is learned

Mythic spells are innate abilities and need not be memorized. Studying a mythic spell note again increases the number of uses. Casting a mythic spell also requires paying its cost.

## Changelog

### v1.2

- Added a new spell note, Z's PF Spell Notes - Protection and Spellbreaking.
- Added new spells: Lesser Ruby Ray of Reversal (4th level, removes one spell protection of 5th level or lower), Greater Remove Magic (6th level, dispels at a +15 caster level advantage), Greater Spell Shield (7th level, immune to dispelling for 4 rounds), Greater Breach (7th level, works on liches and rakshasas), Mass Greater Spell Shield (9th level, the mass version of Greater Spell Shield), Mage's Disjunction (9th level, always dispels unless the target is protected by Spell Immunity: Abjuration).
- Z's PF Spell Notes - Destruction gained a new spell: Controlled Fireball (4th level, a fireball with no friendly fire).
- Added three mythic spell notes: Z's Mythic Spell Notes - Absolute Death, - Corrupt Magic and - Threefold Wish.
- Stormbolts has new visual effects.

### v1.1

- Adjusted the duration of most spells.
- Added a new spell note, Z's PF Spell Notes - Conjuration and Elements.
- Added new spells: Animalistic Power (NWN2), Lesser Prismatic Orb (adapted from Baldur's Gate 3 and NWN2), Prismatic Orb (adapted from Baldur's Gate 3 and NWN2), Shadow Shield (NWN).

## Credits

- WeiDU by Wes Weimer, the WeiDU team and contributors.
- The `resolve_state` helper follows a function posted on the Gibberlings Three forums, credited there to Ardanis.
- Spell names and mechanics are recreated from Pathfinder (Paizo), Pathfinder: Kingmaker and Pathfinder: Wrath of the Righteous (Owlcat Games), and from Neverwinter Nights (BioWare / Obsidian Entertainment).

## Licence

MIT. See [LICENSE](LICENSE). The licence covers the original code, text and assets created for this mod. It does not cover Baldur's Gate, Dungeons & Dragons, Pathfinder, Neverwinter Nights or any other intellectual property owned by their respective owners.

This is a non-commercial fan modification. It requires installed copies of the games it is played with, and it is not affiliated with or endorsed by Beamdog, Wizards of the Coast, Paizo, Owlcat Games or Hasbro.
