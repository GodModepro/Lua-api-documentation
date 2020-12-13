# ADD INDICATOR

Adds indicator to left bar

Syntax:	indicator.add

Parameters:	text, color

```lua
local function add_indicator()
  indicator.add("Red I", color.new(255, 0, 0, 255))
end

client.add_callback("on_paint", add_indicator)
```