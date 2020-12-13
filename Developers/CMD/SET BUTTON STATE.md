# SET BUTTON STATE

Sets button state

Syntax:	cmd.set_button_state

Parameters:	button, state

```lua
local function duck()
  cmd.set_button_state(buttons.in_duck, true)
end

client.add_callback("on_createmove", duck)
```
