# TEXT WIDTH

Returns text width

Syntax:	render.get_text_width

Parameters:	font, text

```lua
local function draw()
  local font =  render.create_font("Verdana", 12, 600, true, true, true)
  local padding = render.text_width(font, "Hello")
end

client.add_callback("on_paint", draw)
```
