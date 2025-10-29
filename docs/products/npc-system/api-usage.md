---
sidebar_position: 2
---

# API Usage

**Here's what you can do with the API:**
- Spawn a bot
*more will be later soon*

:::wawrning
Nothing here will work in a local script, only in server scripts.

## Spawn a bot
In your **server script:**
```lua
local API = game.Workspace["NPC System"]:WaitForChild("API")

API:Fire("SpawnBot", {
    startFloor = 1,
    destination = 2,
})
```

*Parameters:*
|Name|Type|Required|
|-|-|-|
|startFloor|number|✗|
|destination|number|✗|

:::tip[TIP]
If `startFloor` or `destination` is not given, it will pick a random number.
:::