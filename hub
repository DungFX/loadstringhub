-- Load Orion Lib
local OrionLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/shlexware/Orion/main/source"))()

-- Create the UI window
local Window = OrionLib:MakeWindow({Name = "Chocomint Scripts Hub V1", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

-- Create tabs
local Tab = Window:MakeTab({
    Name = "Main",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})

-- Add buttons for each script
Tab:AddButton({
    Name = "W-Azure | 🟢",
    Callback = function()
        loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
    end    
})

-- Script 2
Tab:AddButton({
    Name = "RedZ9999 | 🟢",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()  -- Replace with your script URL
    end    
})

-- Script 3
Tab:AddButton({
    Name = "RelZ | 🟢",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/farghii/relzhub/main/execute.hack", true))()  -- Replace with your script URL
    end    
})

-- Script 4
Tab:AddButton({
    Name = "Rise | 🟢",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/TrashLua/BloxFruits/main/FreeScripts.lua"))()  -- Replace with your script URL
    end    
})

-- Finalize and open UI
OrionLib:Init()
