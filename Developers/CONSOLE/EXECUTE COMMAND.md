# EXECUTE COMMAND

Executes client command

Syntax:	console.execute

Parameters:	string

```lua
local function shot(shot_info)
    local result = shot_info.result
    if result == "Hit" and shot_info.server_damage >= 100 then
       console.execute("say 1")
    end
end
client.add_callback("on_shot", shot)
```