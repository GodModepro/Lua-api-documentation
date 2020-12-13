# SHORT MAP NAME

Returns current short map name

Syntax:	engine.get_level_name_short

```lua
local function draw()
  local font =  render.create_font("Verdana", 12, 600, true, true, true)
  render.draw_text(font, 100, 100, color.new(255, 0, 0), tostring(engine.get_level_name_short()))
end

client.add_callback("on_paint", draw)
```
