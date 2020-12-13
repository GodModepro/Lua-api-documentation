# TEXT

Drawing text

Syntax:	render.draw_text

Parameters:	font, x, y, color, text

```lua
local function draw()
  local font =  render.create_font("Verdana", 12, 600, true, true, true)
  render.draw_text(font, 100, 100, color.new(255, 0, 0), "Hello, world!")
end

client.add_callback("on_paint", draw)
```
