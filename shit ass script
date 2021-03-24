game:GetService("Players").LocalPlayer.Chatted:Connect(function(msg)
   if msg:lower() == ";bat" then
      b = game.Workspace:FindFirstChild("BatDrop")
      b.CFrame = CFrame.new(game.Players.LocalPlayer.Character.Torso.Position)
   end
   if msg:lower() == ";pistol" then
      b = game.Workspace:FindFirstChild("PistolDrop")
      b.CFrame = CFrame.new(game.Players.LocalPlayer.Character.Torso.Position)
   end
   if msg:lower() == ";money" then
      b = game.Workspace:FindFirstChild("CashDrop")
      b.CFrame = CFrame.new(game.Players.LocalPlayer.Character.Torso.Position)
   end
   if msg:lower() == ";gold" then
      b = game.Workspace:FindFirstChild("GoldDrop")
      b.CFrame = CFrame.new(game.Players.LocalPlayer.Character.Torso.Position)
   end
   if msg:lower() == ";lockpick" then
      b = game.Workspace:FindFirstChild("LockPickDrop")
      b.CFrame = CFrame.new(game.Players.LocalPlayer.Character.Torso.Position)
   end
   if msg:lower() == ";machete" then
      b = game.Workspace:FindFirstChild("MacheteDrop")
      b.CFrame = CFrame.new(game.Players.LocalPlayer.Character.Torso.Position)
   end
   if msg:lower() == ";smg" then
      b = game.Workspace:FindFirstChild("SMGDrop")
      b.CFrame = CFrame.new(game.Players.LocalPlayer.Character.Torso.Position)
   end
   if msg:lower() == ";kill all" then
      print("no can doo")
   end
end)

game.Workspace.ChildAdded:Connect(function(child)
   if child.Name == "CashWad" then
      child.Parent = game.Players.LocalPlayer.Backpack
   end
end)
plr = game.Players.LocalPlayer
char = plr.Character or plr.CharacterAdded:Wait()
char.DescendantAdded:Connect(function(v)
   if v.Name == "Attacking" then
      wait()
      v:Destroy()
   end
end)
game.Players.LocalPlayer.Character.DescendantAdded:Connect(function(v)
   if v.Name == "StaminaCD" then
      wait()
      v:Destroy()
   end
end)

game:GetService("Players").LocalPlayer.Chatted:Connect(function(msg)
   if string.sub(msg,1,7) == ".attack" then
      print("h")
      local targetName = string.sub(msg,9)
      local target = targetName
      for i,v in pairs(game.Workspace:GetDescendants()) do
         if v.Name == game.Players.LocalPlayer.Name then
            LocalPlayer = v
         end
      end
      repeat wait()
         LocalPlayer.HumanoidRootPart.CFrame = game.Players[target].Character.HumanoidRootPart.CFrame
         wait(0.1)
         LocalPlayer.Katana.ServerStuff.M1:FireServer()
      until game.Players[target].Character.Humanoid.Health < 8

   end



end)
game:GetService("Players").LocalPlayer.Chatted:Connect(function(msg)
   if string.sub(msg,1,6) == ".bring" then
      pos = char.HumanoidRootPart.Position
      local targetName = string.sub(msg,8)
      local target = targetName
      for i,v in pairs(game.Workspace:GetDescendants()) do
         if v.Name == game.Players.LocalPlayer.Name then
            LocalPlayer = v
         end
      end
      repeat wait()
         LocalPlayer.HumanoidRootPart.CFrame = game.Players[target].Character.HumanoidRootPart.CFrame
         wait(0.1)
         LocalPlayer.Katana.ServerStuff.M1:FireServer()
      until game.Players[target].Character.Humanoid.Health < 4
      game.Workspace.LivingThings.LocalPlayer.RagdollClient.Server:FireServer()
      wait(0.4)
      char.HumanoidRootPart.CFrame = CFrame.new(pos)

   end



end)

e = Instance.new("Message",workspace)
e.Text = "LuaWise Trash Admin STOLEN BY YODA AND X6QL <3"
wait(2)
e:Destroy()





game.StarterGui:SetCore("SendNotification", {
    Title = "leaked by ghost gang"; -- change text
    Text = "leaked by yoda GHOST ON TOP";  -- change text
    Duration = 8.5;
})
