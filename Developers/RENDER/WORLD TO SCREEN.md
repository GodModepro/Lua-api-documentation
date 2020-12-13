# WORLD TO SCREEN

Return x/y object positions in world

Syntax:	render.world_to_screen

Parameters:	(vector)screen_pos

```lua
local function draw()
  local font =  render.create_font("Verdana", 12, 600, true, true, true)
  local random_origin = render.world_to_screen(vector.new(1400, 600, 200))
  render.draw_text(font, random_origin.x , random_origin.y , color.new(255, 0, 0), tostring(engine.get_level_name))
end

client.add_callback("on_paint", draw)
```
