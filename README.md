local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
local location = CFrame.new(-254.72934, 4.24109602, -63.4645386, 1, 0, 0, 0, 1, 0, 0, 0, 1)
local humanoid = game.Players.LocalPlayer.Character.Humanoid
humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
wait(0.1)
pl.CFrame = location
