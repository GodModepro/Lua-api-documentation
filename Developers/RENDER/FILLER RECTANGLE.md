# FILLER RECTANGLE

Draws filled rectangle

Syntax:	render.draw_rect_filled

Parameters:	x, y, width, height, color

```lua
local function rectangle()
    render.draw_rect_filled(10, 10, 100, 100, color.new(150, 150, 200))
end

client.add_callback("on_paint", rectangle)
```
