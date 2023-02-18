# ReturnOldRoblox
Updates spec's old roblox coregui script to work with the latest version of Roblox.

```
--// config settings
getgenv().config = {
    old_console = true,
    old_plist = true,
    old_graphics = false,
    dev = true
}

--// mods
getgenv().mods = {
    fps_counter = true,
    built_in_silentre = true,
    c00l_mode = true
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/SheldoFishHead/ReturnOldRoblox/main/Source"))()
```
