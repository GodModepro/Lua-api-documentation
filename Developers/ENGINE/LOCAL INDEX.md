# LOCAL INDEX

Returns local player index

Syntax:	engine.get_local_player_index

```lua
local function draw()
  local player = engine.get_player_for_user_id(1)
  local me = engine.get_local_player_index()
  if player ~= me then
      -- something
  end
end

client.add_callback("on_paint", draw
```
