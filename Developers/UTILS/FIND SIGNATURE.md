# FIND SIGNATURE

Gets function by signature

Syntax:	utils.find_signature

Parameters:	module, signature

```lua
local ffi = require("ffi")

ffi.cdef[[
typedef int(__fastcall* clantag_t)(const char*, const char*);
]]

local fn_change_clantag
local set_clantag

local function clantag()
  if (fn_change_clantag == nil) then
    fn_change_clantag = utils.find_signature("engine.dll", "53 56 57 8B DA 8B F9 FF 15")
  end

  if ((set_clantag == nil) and (fn_change_clantag ~= nil)) then
     set_clantag =  ffi.cast("clantag_t", fn_change_clantag)
  end

  local choke = cmd.get_choke()

  if (choke == 0) then
    set_clantag("132", "312")
  end
end

client.add_callback("on_createmove", clantag)
```