
local Rayfield = loadstring(game:HttpGet('https://raw.githubusercontent.com/shlexware/Rayfield/main/source'))()

local Window = Rayfield:CreateWindow({
    Name = "CPX HUB",
    LoadingTitle = "CPX HUB",
    LoadingSubtitle = "By Shezzfy",
    ConfigurationSaving = {
       Enabled = true,
       FolderName = nil,
       FileName = "CPX HUB"
    },
 KeySystem = true, 
    KeySettings = {
       Title = "CPX HUB - Key System",
       Subtitle = "",
       Note = "You must enter a key to use the script",
       FileName = "CPX HUB - KEY SYSTEM",
       SaveKey = true,
       GrabKeyFromSite = false, 
       Key = "KEY-18325067120672"
    }
 })

 local Tab = Window:CreateTab("Info", 4483362458)

 local Button = Tab:CreateButton({
   Name = "CPX HUB - BY SHEZZFY",
   Callback = function()
   end,
})


 local Tab = Window:CreateTab("Pet Simulator X", 4483362458) -- Title, Image

 local Button = Tab:CreateButton({
    Name = "Trade Scam - On",
    Callback = function()
    -- The function that takes place when the button is pressed
    end,
 })

 local Button = Tab:CreateButton({
    Name = "Trade Scam - Off",
    Callback = function()
    -- The function that takes place when the button is pressed
    end,
 })

local Section = Tab:CreateSection("Pet Dupes")

local Button = Tab:CreateButton({
   Name = "Dupe Huges/Tytanic x25 (SOON)",
   Callback = function()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "Dupe Pets x25 (SOON)",
   Callback = function()
   -- The function that takes place when the button is pressed
   end,
})

local Section = Tab:CreateSection("Dupe Gems")

local Button = Tab:CreateButton({
   Name = "Dupe Gems x1000 (SOON)",
   Callback = function()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "Instant Dupe Gems (SOON)",
   Callback = function()
   -- The function that takes place when the button is pressed
   end,
})

local Section = Tab:CreateSection("Fake Partner")

local Button = Tab:CreateButton({
   Name = "Fake Partner",
   Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/IlllIlIIIlllIlIlllIIlIlllIlIIlllI/PartnerPSX/main/BetterPartnerTag", true))()
   end,
})

local Section = Tab:CreateSection("Visual Pets")

local Button = Tab:CreateButton({
   Name = "Visual Pets",
   Callback = function()
   --SOON VISUAL SCRIPT
   end,
})


 local Tab = Window:CreateTab("Player", 4483362458) -- Title, Image
 
 local Button = Tab:CreateButton({
    Name = "SOON",
    Callback = function()
    -- The function that takes place when the button is pressed
    end,
 })
 
 local Player = Window:NewTab("Player")
local PlayerSection = Player:NewSection("Player Settings")

PlayerSection:NewToggle("Super Boost", "Fast and High Jump", function(state)
    if state then
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 120
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 120
    else
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
    end
end)
 
 
