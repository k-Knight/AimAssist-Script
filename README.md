# AimAssist Script

### About

This script works on all games (unless the character is not in workspace)
Feel free to edit any of the settings inside the script.

Control options (default):
- `ToggleAimbotKey` - turn aim assist On/Off (default: F15)
- `ToggleTeamCheckKey` - toggle team check (default: F14)

By editing this script values one is able to customize: FOV , circle color, circle filled, circle thickness, circle radius (fov or size), circle position and how many sides does the circle have (set to 64 for a circle, anything below 3 won't work)

### Settings of the script

```lua
local TeamCheck = true -- If set to true then the script would only lock your aim at enemy team members.
local AimParts = {"Torso", "UpperTorso", "LowerTorso", "Head"} -- Where the aimbot script would lock at (first item - highest priority).
local Sensitivity = 0.0 -- How many seconds it takes for the aimbot script to officially lock onto the target's aimpart.

local CircleSides = 64 -- How many sides the FOV circle would have.
local CircleColor = Color3.fromRGB(255, 255, 255) -- (RGB) Color that the FOV circle would appear as.
local CircleTransparency = 0.25 -- Transparency of the circle.
local CircleRadius = 80 -- The radius of the circle / FOV.
local CircleFilled = false -- Determines whether or not the circle is filled.
local CircleVisible = true -- Determines whether or not the circle is visible.
local CircleThickness = 0 -- The thickness of the circle.
local ToggleAimbotKey = Enum.KeyCode.F15 -- The key that turns aimbot on/off
local ToggleTeamCheckKey = Enum.KeyCode.F14 -- The key that toggles the team chech condition
```

## Script (With FOV Circle)

Load the script by using the code below or by copying it from [here](https://raw.githubusercontent.com/k-Knight/AimAssist-Script/main/AimAssist%20Script.lua).
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/k-Knight/AimAssist-Script/main/AimAssist%20Script.lua"))()
```
