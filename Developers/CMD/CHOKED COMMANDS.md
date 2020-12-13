# CHOKED COMMANDS

Returns current choke

Syntax:	Syntax	cmd.get_choke

```lua
local function draw()
  local font =  render.create_font("Verdana", 12, 600, true, true, true)
  render.draw_text(font, 100, 100, color.new(255, 0, 0), tostring(cmd.get_choke()))
end

client.add_callback("on_paint", draw)
```
