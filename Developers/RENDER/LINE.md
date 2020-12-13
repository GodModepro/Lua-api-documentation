# LINE

Draws line

Syntax:	render.draw_line

Parameters:	x, y, x1, y1, color

```lua
local function draw_line()
    render.draw_line(10, 10, 150, 150, color.new(0, 0, 255))
end

client.add_callback("on_paint", draw_line)
```
