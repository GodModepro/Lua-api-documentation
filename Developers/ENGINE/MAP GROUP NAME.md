# MAP GROUP NAME

Returns current map group name

Syntax:	engine.get_map_group_name

```lua
local function draw()
  local font =  render.create_font("Verdana", 12, 600, true, true, true)
  render.draw_text(font, 100, 100, color.new(255, 0, 0), tostring(engine.get_map_group_name()))
end

client.add_callback("on_paint", draw)
```
