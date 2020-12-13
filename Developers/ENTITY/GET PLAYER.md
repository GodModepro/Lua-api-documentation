# GET PLAYER

returns player by index

Syntax:	entitylist.get_player_by_index

Parameters:	index

```lua
local function test()
  for i = 0, 64 do
     local e = entitylist.get_player_by_index(i)
     if e ~= nil and e:get_alive() then
       client.log("index " .. tostring(i) .. " alive" )
     end
  end
end

client.add_callback("on_createmove", test)
```

`get_index` - returns entity index (int)

`get_dormant` - returns dormant state (true/false)

`get_team` - returns team number (int)

`get_alive` - returns entitie's lifestate (true/false)

`get_velocity` - returns entitie's velocity (vector)

`get_origin` - returns entitie's abs origin (vector)

`get_angles` - returns entitie's eye angles (vector)

`get_hitbox_position(i)` - returns entitie's hitbox position (vector)

`has_helmet` - returns entitie's helmet exist (true/false)

`has_heavy_armor` - returns entitie's heavy armor exist (true/false)

`is_scoped` - returns entitie's scoped state (true/false)

`get_health` - returns entitie's helath (int)