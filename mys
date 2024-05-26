task.wait(7)
local plr = game.Players.LocalPlayer
repeat task.wait()
until plr.PlayerGui.Load.Frame.Visible
if plr.PlayerGui.Load.Frame.Visible == true then
for i,v in pairs(getconnections(game:GetService("Players").LocalPlayer.PlayerGui.Load.Frame.Load.MouseButton1Click)) do
       v:Fire()
   end
end
wait(2)
if plr.PlayerGui.Load.Frame.Visible == true then
for i,v in pairs(getconnections(game:GetService("Players").LocalPlayer.PlayerGui.Load.Frame.Load.MouseButton1Click)) do
       v:Fire()
   end
end
wait(2)
if plr.PlayerGui.Load.Frame.Visible == true then
for i,v in pairs(getconnections(game:GetService("Players").LocalPlayer.PlayerGui.Load.Frame.Load.MouseButton1Click)) do
       v:Fire()
   end
end
repeat task.wait()
until plr.Backpack:FindFirstChild("Melee") or plr.Backpack:FindFirstChild("Table Kick") or plr.Backpack:FindFirstChild("Black Leg") or plr.Backpack:FindFirstChild("Seastone Cestus") or plr.Backpack:FindFirstChild("Aqua Staff")
wait(7)
workspace:WaitForChild("UserData"):WaitForChild("User_"..game.Players.LocalPlayer.UserId):WaitForChild("Stats"):FireServer()
wait(5)
game.Players.LocalPlayer:Kick()
game:GetService("TeleportService"):TeleportToPlaceInstance(game.PlaceId, game.JobId)
