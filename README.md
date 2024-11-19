# DND-Sheet
A DnD Sorcerer Character Sheet

In the DND_sheet folder is the Executable (.exe)
and the CharacterSheet.json in the Format

    "Name": "Mensch",
    "Race": "",
    "Class": "",
    "Level": "",
    "STR": 0,
    "DEX": 0,
    "CON": 0,
    "INT": 0,
    "WIS": 0,
    "CHA": 0,
    "HitPoints": 0,
    "Max_HitPoints": 0,
    "AC": 0,
    "INI": 0,
    "SPEED": 0,
    "HitDice": 0,
    "Max_HitDice": 0,
    "DeathSave_Passed": 0,
    "DeathSave_Failed": 0,
    "Proficiency": 0,
    "Proficiencies": [
    ],
    "Weapons": [
    ],
    "Abilities": [
    ],
    "Inventory": [
    ],
    "Gold": 0,
    "Silver": 0,
    "Copper": 0,
    "Spell_Att": 0,
    "Spell_Save": 0,
    "Spell_Slots": [
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0
    ],
    "Max_Spell_Slots": [
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0
    ],
    "Spells": [
    ],
    "sorceryPoints": 0,
    "Max_sorceryPoints": 0,
    "sorc_Ability": "",
    "Madness_count": []


To add a Weapon add :

    {
            "name": "Sword",
            "bonus": "2",
            "damage": "1d8"
        }
to the Weapon[] List


To add a Ability add:

    {
            "name": "Dark Vision",
            "description": "This is a Ability"
        }

to the Ability[] List


To add an Item add:

    {
            "name": "Key",
            "amount": 1
        }

to the Inventory[] List


To add a Spell add:

    {
            "name": "Feuerball",
            "level": 3,
            "attack": 0,
            "effect": "4d8",
            "description": ""
        }

to the Spells[] List

-------------------------------------

Spellslots are in Order

[
        0, #Level 1
        0, #Level 2
        0, #Level 3
        0, #Level 4
        0, #Level 5
        0, #Level 6
        0, #Level 7
        0, #Level 8
        0  #Level 9
    ]

The number represents the ammount of SpellsSlots of that Level