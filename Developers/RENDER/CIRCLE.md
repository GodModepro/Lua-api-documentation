# CIRCLE

Draws circle

Syntax:	render.draw_circle

Parameters:	x, y, points, radius, color

```lua
local function draw()
  render.draw_circle(100, 100, 30, 60, color.new(255, 0, 0))
end

client.add_callback("on_paint", draw)
```
