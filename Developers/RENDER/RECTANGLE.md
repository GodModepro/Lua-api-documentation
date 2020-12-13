# RECTANGLE

Draws rectangle

Syntax:	render.draw_rect

Parameters:	x, y, width, height, color

```lua
local function rectangle()
    render.draw_rect(10, 10, 100, 100, color.new(150, 150, 200))
end

client.add_callback("on_paint", rectangle)
```
