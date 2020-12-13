# IS HLTV

Returns hltv state

Syntax:	engine.is_hltv

```lua
local function draw()
  if engine.is_hltv() then
    render.draw_triangle(100, 100,  120, 90, 80, 90, color.new(255, 0, 0))
  end
end

client.add_callback("on_paint", draw)
```
