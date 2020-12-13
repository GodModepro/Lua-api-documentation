# SCREEN WIDTH

Returns screen width

Syntax:	render.get_screen_width

```lua
local function screen_sizes()
    local screen_width = render.get_screen_width()
    local screen_height = render.get_screen_height()
end

client.add_callback("on_paint", screen_sizes)
```
