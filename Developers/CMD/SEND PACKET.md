# SEND PACKET

Returns current sendpacket state

Syntax:	cmd.get_send_packet

```lua
local function draw()
  if cmd.get_send_packet() then
    render.draw_triangle(100, 100,  120, 90, 80, 90, color.new(255, 0, 0))
  end
end

client.add_callback("on_paint", draw)
```
