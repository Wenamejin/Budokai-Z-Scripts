![image](https://github.com/user-attachments/assets/3423b68c-caf5-4aa4-9a17-ea2037d87b8f)


With this script you can see your own BP

To execute:

local url = "https://raw.githubusercontent.com/Wenamejin/Budokai-Z-Scripts/refs/heads/main/SELFBPVIEW.lua"
local success, result = pcall(function()
    return loadstring(game:HttpGet(url))()
end)

