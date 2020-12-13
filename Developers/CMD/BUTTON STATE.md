# BUTTON STATE

Returns button state

Syntax:	cmd.get_button_state

Parameters:	button

```lua
local function draw()
  if cmd.get_button_state(buttons.in_use) then
    render.draw_triangle(100, 100,  120, 90, 80, 90, color.new(255, 0, 0))
  end
end

client.add_callback("on_paint", draw)
```
