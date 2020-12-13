# GET WEAPON

Returns player weapon

Syntax:	entitylist.get_weapon_by_player

Parameters:	entity

```lua
local function test()
  for i = 0, 64 do
     local e = entitylist.get_player_by_index(i)
     if e ~= nil and e:get_alive() then
       local weapon = entitylist.get_weapon_by_player(e)
       local weapon_name = weapon:get_name()
       client.log("index " .. tostring(i) .. " has" .. weapon_name)
     end
  end
end

client.add_callback("on_createmove", test)
```

`is_empty` - returns true, if weapon doesnt have ammo (true/false)

`can_fire` - returns true, if weapon can fire (true/false)

`is_non_aim` - returns true, if weapon cant shoot (knife/zeus/grenade) (true/false)

`can_double_tap` - returns true, if weapon can double tap (true/false)

`get_name` - returns weapon name (string)