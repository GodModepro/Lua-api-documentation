# TAKING SCREENSHOT

Returns taking steam-screenshot state

Syntax:	engine.is_taking_screenshot

```lua
local function draw()
  if not engine.is_taking_screenshot() then
    render.draw_triangle(100, 100,  120, 90, 80, 90, color.new(255, 0, 0))
  end
end

client.add_callback("on_paint", draw)
```
