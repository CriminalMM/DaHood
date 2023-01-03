getgenv().bot = true 
getgenv().emt = -100

game:GetService("RunService").heartbeat:Connect(function()
if getgenv().bot ~= false then
local antiurmum = game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity
game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = Vector3.new(0, getgenv().emt, 0)
    game:GetService("RunService").RenderStepped:Wait()
    game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = antiurmum
end
end)
