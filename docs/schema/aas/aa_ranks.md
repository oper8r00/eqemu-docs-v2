# aa_ranks

!!! info
	This page was last generated 2022.02.23

## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| id | int | [AA Identifier](aa_ability.md) |
| upper_hotkey_sid | int | Upper Hotkey SID |
| lower_hotkey_sid | int | Lower Hotkey SID |
| title_sid | int | Title SID |
| desc_sid | int | Description SID |
| cost | int | Cost in AA Points |
| level_req | int | Level Required |
| spell | int | [Spell Identifier](../../schema/spells/spells_new.md) |
| spell_type | int | [Spell Type](../../../../server/spells/spell-types) |
| recast_time | int | Recast Timer |
| expansion | int | [Expansion Identifier](../../../../server/operation/expansion-list) |
| prev_id | int | Previous Rank Identifier |
| next_id | int | Next Rank Identifier |

