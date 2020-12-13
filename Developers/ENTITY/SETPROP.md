# SETPROP

Sets netvar value

Syntax:	(entity):set_prop..

Parameters:	table, netvar, value

```lua
local lc_player = entitylist.get_local_player()
lc_player:set_prop_bool("CBaseEntity", "m_bSpotted", true)
```

`set_prop_int`

`set_prop_float`

`set_prop_bool`
