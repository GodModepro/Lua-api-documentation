# ADD POSITIONED INDICATOR

Adds an indicator with custom position

Syntax:	indicator.add_position

Parameters:	text, color, position

```lua
local function add_indicator()
  indicator.add_position("Red I(first)", color.new(255, 0, 0, 255), 1)
end

client.add_callback("on_paint", add_indicator)
```