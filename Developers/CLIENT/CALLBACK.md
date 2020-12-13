# CALLBACK

Adds callback

Syntax:	client.add_callback

Parameters:	name, function

`Callback list`

`on_shot` - when aimbot is firing
`on_paint` - hook to draw something..
`on_createmove` - tick processing hook

`Examples`

```lua
local function draw()
  -- draw something
end
client.add_callback("on_paint", draw)
```

```lua
local function createmove_func()
  -- do something
end
client.add_callback("on_createmove", createmove_func)
```

```lua
local function shot(shot_info)
  local result = shot_info.result
  if result == "Hit" then
    client.log("Hitted")
  end
end
client.add_callback("on_shot", shot)
```