# SCRiptLUCK-Anime-TappersFUNK
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/zxciaz/VenyxUI/main/Reuploaded"))() --someone reuploaded it so I put it in place of the original back up so guy can get free credit.
local venyx = library.new("FUNK|HUB", 5013109572)
local page = venyx:addPage("Main", 5012544693)
local section1 = page:addSection("AUTO-FARM")
section1:addToggle("Autofarm", nil, function(value)
_G.AUTOFARM = value
spawn(function()
    while _G.AUTOFARM do wait()
    game:GetService'VirtualUser':CaptureController()
    game:GetService'VirtualUser':Button1Down(Vector2.new(Vector2.new(934, 383)))

end
end)
end)
--Autoyen
local section2 = page:addSection("Auto-Getyen")
section2:addToggle("Autoyen", nil, function(yenc)
_G.yen = yenc
while _G.yen do wait()
for i,v in pairs(game:GetService("Workspace").Worlds.StarterWorld.Yen:GetDescendants()) do
    if v.name == "TouchInterest" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
      
end
end
end
end)

