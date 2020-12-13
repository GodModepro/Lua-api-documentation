# IN GAME

Returns in-game state

Syntax:	engine.is_in_game

```lua
local function draw()
  if engine.is_in_game() then
      render.draw_triangle(100, 100,  120, 90, 80, 90, color.new(255, 0, 0))
  end
end

client.add_callback("on_paint", draw)
```
