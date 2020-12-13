# CENTERED TEXT

Drawing text

Syntax:	render.draw_text_centered

Parameters:	font, x, y, color, centered_x, centered_y, text

```lua
local function draw()
  local font =  render.create_font("Verdana", 12, 600, true, true, true)
  render.draw_text_centered(font, 100, 100, color.new(255, 0, 0), true, true, "Hello, world!")
end

client.add_callback("on_paint", draw)
```
