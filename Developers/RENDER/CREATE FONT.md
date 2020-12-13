# CREATE FONT

creating font

Syntax:	render.create_font

Parameters:	font name, size, weight, antialias, dropshadow, outline

```lua
local function draw()
   render.create_font("Verdana", 12, 600, true, true, true)
end

client.add_callback("on_paint", draw))
```