# PAUSE

Returns pause state

Syntax:	engine.is_paused

```lua
local function draw()
  if engine.is_pausedthen
    render.draw_triangle(100, 100,  120, 90, 80, 90, color.new(255, 0, 0))
  end
end

client.add_callback("on_paint", draw)
```
