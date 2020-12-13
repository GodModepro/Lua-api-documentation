# VIEW ANGLES

Returns current view angles

Syntax:	engine.get_view_angles

```lua
local function cm()
  local viewangles = engine.get_view_angles()
end

client.add_callback("on_createmove", cm)
```
