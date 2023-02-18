# ReturnOldRoblox
Updates spec's old roblox coregui script to work with the latest version of Roblox. (ty noto)

```lua
--// config settings
getgenv().config = {
    old_console = true,
    old_plist = true,
    old_graphics = true,
    dev = true
}

--// mods
getgenv().mods = {
    fps_counter = true,
    built_in_silentre = true,
    c00l_mode = false
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/SheldoFishHead/ReturnOldRoblox/main/Source"))()
```
