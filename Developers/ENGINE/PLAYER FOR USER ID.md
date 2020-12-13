# PLAYER FOR USER ID

Returns player for user ID

Syntax:	engine.get_player_for_user_id

Parameters:	index

```lua
local function draw()
  local player = engine.get_player_for_user_id(1)
  local me = engine.get_local_player_index()
  if player ~= me then
      -- something
  end
end

client.add_callback("on_paint", draw)
```
