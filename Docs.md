## Load the UI
```lua
local MythixzUILib = loadstring(game:HttpGet("https://yourpastebinlink.com/raw"))()
```

## Window
```lua
local ui = MythixzUILib:Create({
    Icon = "rbxassetid://8622542227",
    Title = "Mythixz Hub",
    Description = "The best scripts in one place. All categorized and easy to use inside one beautiful UI.",
})

```

## Loading Delay
```lua
task.spawn(function()
    for i = 1, 100 do
        ui:SetProgress(i)
        wait(0.05)
    end
end)

```

## Execute script after loading
```lua
ui:OnLoaded(function()
    print("Meow") -- [[Replace with your actual script]]
end)
```
