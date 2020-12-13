# LOCAL PLAYER

Returns local player

Syntax:	entitylist.get_local_player

```lua
local function test()
  local lc_player = entitylist.get_local_player()
  local index = lc_player:get_index()
end

client.add_callback("on_createmove", test)
```

`get_index`- returns entity index (int)

`get_dormant` - returns dormant state (true/false)

`get_team` - returns team number (int)

`get_alive` - returns entitie's lifestate (true/false)

`get_velocity` - returns entitie's velocity (vector)

`get_origin` - returns entitie's abs origin (vector)

`get_angles` - returns entitie's eye angles (vector)

`get_hitbox_position(i)` - returns entitie's hitbox position (vector)

`has_helmet` - returns entitie's helmet exist (true/false)

`has_heavy_armor` - returns entitie's heavy armor exist (true/false)

`is_scoped `- returns entitie's scoped state (true/false)

`get_health` - returns entitie's helath (int)