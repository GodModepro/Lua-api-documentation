# SET VIEW ANGLES

Sets new view angle

Syntax:	engine.set_view_angles

Parameters:	angle

```lua
local function cm()
  local viewangles = engine.get_view_angles()
  engine.set_view_angles(vector.new(viewangles.x, viewangles.y + 180.0, viewangles.z))
end

client.add_callback("on_createmove", cm)
```
