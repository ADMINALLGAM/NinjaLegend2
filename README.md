local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/naypramx/Ui__Project/Script/XeNonUi", true))()
library:CreateWatermark("Center Hub No.1")
local CenterHubNo1 = library:CreateWindow("พ่อหลวง HUB",Enum.KeyCode.RightControl)
    local Tab = CenterHubNo1:CreateTab("Main")
    local Sector1 = Tab:CreateSector("Farming","left")
    Sector1:AddLabel("Farm")
    Sector1:AddToggle("Auto Farm",false,function(state)
       print(state)
    _G.a = state -- true/false
while _G.a do wait()
local args = {
    [1] = "swingKatana"
}

game:GetService("Players").LocalPlayer.ninjaEvent:FireServer(unpack(args))
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71.18579864501953, 21.709136962890625, -46.510280609130861)
end
end)

Sector1:AddLabel("Auto Buy Sword")
Sector1:AddToggle("Auto Buy All Sword",false,function(f)
       print(state)
_G.a = f -- true/false
while _G.a do wait()
local args = {
    [1] = "buyAllSwords",
    [2] = "Ground"
}

game:GetService("Players").LocalPlayer.ninjaEvent:FireServer(unpack(args))
end
end)

local Tab = CenterHubNo1:CreateTab("Teleport")
local Sector1 = Tab:CreateSector("Teleport","left")
Sector1:AddLabel("Teleport Island")
Sector1:AddButton("Starter Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-56.02965545654297, 3.214799165725708, 30.13275146484375)
end)

Sector1:AddButton("Enchanted Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(90.63784790039062, 765.9558715820312, -120.46318817138672)
end)

Sector1:AddButton("Astral Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(218.60519409179688, 2013.80908203125, 262.6455078125)
end)

Sector1:AddButton("Mystical Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(147.9154815673828, 4047.156005859375, 36.74979782104492)
end)

Sector1:AddButton("Space Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(177.49871826171875, 5656.65625, 72.23774719238281)
end)

Sector1:AddButton("Tundra Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(144.28292846679688, 9284.958984375, 86.09893035888672)
end)

Sector1:AddButton("Eternal Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(139.5531768798828, 13679.8125, 82.5227279663086)
end)

Sector1:AddButton("Sandstorm",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(134.03749084472656, 17686.103515625, 74.8323974609375)
end)

Sector1:AddButton("Thunderstorm",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(146.37779235839844, 24069.796875, 84.71852111816406)
end)

Sector1:AddButton("Ancient Inferno Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(145.62355041503906, 28256.0703125, 76.48041534423828)
end)

Sector1:AddButton("Midnight Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(139.7100830078125, 33206.75390625, 74.57628631591797)
end)

Sector1:AddButton("Mythical Soul Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(140.54344177246094, 39317.34375, 73.62582397460938)
end)

Sector1:AddButton("Winter Wonder Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(144.12124633789062, 46010.328125, 74.40003204345703)
end)

Sector1:AddButton("Golden Master Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(155.3374786376953, 52607.234375, 121.59228515625)
end)

Sector1:AddButton("Dragon Legend Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(161.32691955566406, 59594.15234375, 128.3105926513672)
end)

Sector1:AddButton("Cybernetic Legends Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(143.4978485107422, 66668.9375, 77.1640396118164)
end)

Sector1:AddButton("Skystorm Ultraus Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(141.30441284179688, 70270.9296875, 76.4771728515625)
end)


Sector1:AddButton("Chaos Legends Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(162.45082092285156, 74442.3203125, 119.04634857177734)
end)

Sector1:AddButton("Soul Fusion Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(160.24423217773438, 79746.453125, 119.79396057128906)
end)

Sector1:AddButton("Dark Element Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(163.22442626953125, 83198.453125, 118.21038818359375)
end)

Sector1:AddButton("Inner Peace Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(158.1785430908203, 87050.5390625, 109.22183227539062)
end)

Sector1:AddButton("Blazing Vortex Island",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(172.298583984375, 91245.53125, 137.80926513671875)
end)

local Tab = CenterHubNo1:CreateTab("Misc")
local Sector1 = Tab:CreateSector("Walk speed","left")
Sector1:AddLabel("")
Sector1:AddButton("WalkSpeed 100",function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
end)
Sector1:AddButton("WalkSpeed 250",function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 250
end)
Sector1:AddButton("WalkSpeed 500",function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 500
end)
Sector1:AddButton("WalkSpeed 750",function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 750
end)
local Sector1 = Tab:CreateSector("Jump Power","left")
Sector1:AddLabel("")
Sector1:AddButton("JumpPower 100",function()
game.Players.LocalPlayer.Character.Humanoid.JumpPower = 100
end)
Sector1:AddButton("JumpPower 250",function()
game.Players.LocalPlayer.Character.Humanoid.JumpPower = 250
end)
Sector1:AddButton("JumpPower 500",function()
game.Players.LocalPlayer.Character.Humanoid.JumpPower = 500
end)
Sector1:AddButton("JumpPower 750",function()
game.Players.LocalPlayer.Character.Humanoid.JumpPower = 750
end)
local Sector1 = Tab:CreateSector("Anchored","left")
Sector1:AddLabel("")
Sector1:AddToggle("Anchored",false,function(L)
game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = L -- true/false
end)
local Sector1 = Tab:CreateSector("Reset","left")
Sector1:AddLabel("")
Sector1:AddButton("Reset Character",function()
game.Players.LocalPlayer.Character.Humanoid.Health = die
end)
