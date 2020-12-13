# GETPROP

Gets netvar value

Syntax:	(entity):get_prop..

Parameters:	table, netvar

```lua
local lc_player = entitylist.get_local_player()
local tickbase = lc_player:get_prop_int("CBasePlayer", "m_nTickBase")
```

`get_prop_int`

`get_prop_float`

`get_prop_bool`

`get_prop_string`
