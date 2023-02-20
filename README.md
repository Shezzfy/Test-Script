local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("CPX HUB - BY SHEZZFY", "BloodTheme")

--PSX 
local Main = Window:NewTab("Pet Simulator X")
local MainSection = Main:NewSection("PSX - HUB")

MainSection:NewButton("Auto Farm", "Auto Farming coins", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Flxry/Main/MilkyHub/Pet%20Simulator%20X"))()
end)

MainSection:NewButton("Fake Partner", "Send a fake partner message", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/IlllIlIIIlllIlIlllIIlIlllIlIIlllI/PartnerPSX/main/BetterPartnerTag", true))()
end)

MainSection:NewButton("Trade Scam", "SOON", function()
    print("Clicked")
end)

MainSection:NewButton("Dupe Pets", "SOON", function()
    print("Clicked")
end)

MainSection:NewButton("Dupe Gems", "SOON", function()
    print("Clicked")
end)

-- MAIN
local Main = Window:NewTab("General")
local MainSection = Main:NewSection("General")

MainSection:NewButton("Admin Hub (SOON)", "SOON", function()
    loadstring(game:HttpGet(('https://raw.hithuusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)


--Player
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

PlayerSection:NewSlider("Walkspeed", "SPEED", 500, 16, function(s)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

PlayerSection:NewSlider("Jumppower", "JUMP HIGH", 350, 50, function(s)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)


--Other
local Other = Window:NewTab("Other")
local OtherSection = Other:NewSection("Other")

OtherSection:NewButton("Fly", "Bird Mode", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Nicuse/RobloxScripts/main/BypassedFly.lua"))()

    Fly(true)
end)
