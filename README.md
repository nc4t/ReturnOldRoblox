# ReturnOldRoblox
Fixed spec's 2016 coregui script to work with the latest version of Roblox.
noto#6693 helped
added health bars on players

```lua
--// config settings
getgenv().config = {
    old_console = true,
    old_plist = true,
    old_graphics = true,
    dev = true,
    health_bar = true
}

--// mods
getgenv().mods = {
    fps_counter = true,
    built_in_silentre = false,
    c00l_mode = false
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/SheldoFishHead/ReturnOldRoblox/main/Source.lua"))()
```
