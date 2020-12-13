# TRIANGLE

Draws filled rectangle

Syntax:	render.draw_triangle

Parameters:	x, y, x2, y2, x3, y3, color

```lua
local function draw()
  render.draw_triangle(100, 100,  120, 90, 80, 90, color.new(255, 0, 0))
end

client.add_callback("on_paint", draw)
```
