# GRADIENT

Draws gradient rectangle

Syntax:	render.draw_rect_filled_gradient

```lua
local function draw()
  render.draw_rect_filled_gradient(100, 100, 150, 30, color.new(255, 0, 0), color.new(0, 255, 0), 1)
end

client.add_callback("on_paint", draw)
```
