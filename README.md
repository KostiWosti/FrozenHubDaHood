# FrozenHubDaHood
Dahood script. Basic at the moment. More coming soon
--Frozen Hub script 2.0
--Credits to Kostas#0001
--Huge update soon!
 pcall(function()
  game.StarterGui:SetCore("SendNotification", {
    Title = 'Huge Update Soon';
    Text = 'Huge update coming soon with lots of changes';
    Duration = 20;
  })
  game.StarterGui:SetCore("SendNotification", {
    Title = 'Join our discord server';
    Text = 'link copied in clipboard, https://discord.gg/rrBYSjZ7eM';
    Duration = 20;
  })
  setclipboard('https://discord.gg/rrBYSjZ7eM')
  if not game.Players.LocalPlayer:IsInGroup(10686621) then
    coroutine.resume(coroutine.create(function()
       wait(10)
       game.StarterGui:SetCore("SendNotification", {
        Title = 'You are not in the group';
        Text = 'You are not in our group. The link is copied in your clipboard, thx';
        Duration = 20;
       })
       setclipboard('https://web.roblox.com/groups/10686621/Kostas-Land#!/about')
    end))
  end
end)

local ScreenGui = Instance.new("ScreenGui")
local FrozenHub = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local FrozenHubText = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local CloseButton = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local FoodTpSF = Instance.new("ScrollingFrame")
local UICorner_5 = Instance.new("UICorner")
local BurgerButton = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local TacoButton = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local CanBerryButton = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local PopCornButton = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local PizzaButton = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local ChickenButton = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local DonutButton = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local StarBloxLatteButton = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local Pizza2Button = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local Burger2Button = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local Chicken2Button = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local Donut2Button = Instance.new("TextButton")
local UICorner_17 = Instance.new("UICorner")
local PepperSprayButton = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local FlyButton = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local Version = Instance.new("TextLabel")
local UICorner_20 = Instance.new("UICorner")
local Credits = Instance.new("TextLabel")
local UICorner_21 = Instance.new("UICorner")
local FoodTpLabel = Instance.new("TextLabel")
local UICorner_22 = Instance.new("UICorner")
local GunsTpSF = Instance.new("ScrollingFrame")
local UICorner_23 = Instance.new("UICorner")
local RevolverButton = Instance.new("TextButton")
local UICorner_24 = Instance.new("UICorner")
local DoubleBarrelButton = Instance.new("TextButton")
local UICorner_25 = Instance.new("UICorner")
local FlameThrowerButton = Instance.new("TextButton")
local UICorner_26 = Instance.new("UICorner")
local _20kRPGButton = Instance.new("TextButton")
local UICorner_27 = Instance.new("UICorner")
local _6kRPGButton = Instance.new("TextButton")
local UICorner_28 = Instance.new("UICorner")
local ShotGunButton = Instance.new("TextButton")
local UICorner_29 = Instance.new("UICorner")
local TacticalShotGunButton = Instance.new("TextButton")
local UICorner_30 = Instance.new("UICorner")
local P90Button = Instance.new("TextButton")
local UICorner_31 = Instance.new("UICorner")
local SilencerArButton = Instance.new("TextButton")
local UICorner_32 = Instance.new("UICorner")
local SilencerButton = Instance.new("TextButton")
local UICorner_33 = Instance.new("UICorner")
local GlockButton = Instance.new("TextButton")
local UICorner_34 = Instance.new("UICorner")
local SMGButton = Instance.new("TextButton")
local UICorner_35 = Instance.new("UICorner")
local AK47Button = Instance.new("TextButton")
local UICorner_36 = Instance.new("UICorner")
local DrumGunButton = Instance.new("TextButton")
local UICorner_37 = Instance.new("UICorner")
local AUGButton = Instance.new("TextButton")
local UICorner_38 = Instance.new("UICorner")
local HighMediumArmorButton = Instance.new("TextButton")
local UICorner_39 = Instance.new("UICorner")
local MediumArmorPCButton = Instance.new("TextButton")
local UICorner_40 = Instance.new("UICorner")
local MediumArmorDHButton = Instance.new("TextButton")
local UICorner_41 = Instance.new("UICorner")
local GunsTpLabel = Instance.new("TextLabel")
local UICorner_42 = Instance.new("UICorner")
local LocationTpSF = Instance.new("ScrollingFrame")
local UICorner_43 = Instance.new("UICorner")
local BankTPButton = Instance.new("TextButton")
local UICorner_44 = Instance.new("UICorner")
local CasinoTPButton = Instance.new("TextButton")
local UICorner_45 = Instance.new("UICorner")
local ABAllGunsButton = Instance.new("TextButton")
local UICorner_46 = Instance.new("UICorner")
local AdminBaseButton = Instance.new("TextButton")
local UICorner_47 = Instance.new("UICorner")
local SchoolTPButton = Instance.new("TextButton")
local UICorner_48 = Instance.new("UICorner")
local HoodFitTPButton = Instance.new("TextButton")
local UICorner_49 = Instance.new("UICorner")
local HoodKicksTPButton = Instance.new("TextButton")
local UICorner_50 = Instance.new("UICorner")
local UpHillTPButon = Instance.new("TextButton")
local UICorner_51 = Instance.new("UICorner")
local DownHillTPButton = Instance.new("TextButton")
local UICorner_52 = Instance.new("UICorner")
local TrainTPButton = Instance.new("TextButton")
local UICorner_53 = Instance.new("UICorner")
local SewerTPButton = Instance.new("TextButton")
local UICorner_54 = Instance.new("UICorner")
local TOBTPButton = Instance.new("TextButton")
local UICorner_55 = Instance.new("UICorner")
local OtherLocations = Instance.new("TextButton")
local UICorner_56 = Instance.new("UICorner")
local FireWorkTPButton = Instance.new("TextButton")
local UICorner_57 = Instance.new("UICorner")
local MasksTPButton = Instance.new("TextButton")
local UICorner_58 = Instance.new("UICorner")
local SledgeHammerTPButton = Instance.new("TextButton")
local UICorner_59 = Instance.new("UICorner")
local StopSignTPButton = Instance.new("TextButton")
local UICorner_60 = Instance.new("UICorner")
local LocationTpLabel = Instance.new("TextLabel")
local UICorner_61 = Instance.new("UICorner")
local SpeedButton = Instance.new("TextButton")
local UICorner_62 = Instance.new("UICorner")
local InfJumpButton = Instance.new("TextButton")
local UICorner_63 = Instance.new("UICorner")
local TeleportQ = Instance.new("TextButton")
local UICorner_64 = Instance.new("UICorner")
local ResetButton = Instance.new("TextButton")
local UICorner_65 = Instance.new("UICorner")
local TextBox = Instance.new("TextBox")
local UICorner_66 = Instance.new("UICorner")
local HeadLess = Instance.new("TextButton")
local UICorner_67 = Instance.new("UICorner")
local EspButton = Instance.new("TextButton")
local UICorner_68 = Instance.new("UICorner")
local SkyDiveButton = Instance.new("TextButton")
local UICorner_69 = Instance.new("UICorner")
local SafePlaceButton = Instance.new("TextButton")
local UICorner_70 = Instance.new("UICorner")
local LoadVButton = Instance.new("TextButton")
local UICorner_71 = Instance.new("UICorner")
 
--Properties:
 
ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
 
FrozenHub.Name = "FrozenHub"
FrozenHub.Parent = ScreenGui
FrozenHub.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
FrozenHub.Position = UDim2.new(0.0166540481, 0, 0.611311674, 0)
FrozenHub.Size = UDim2.new(0, 476, 0, 280)
FrozenHub.Selectable = true 
FrozenHub.Active = true 
FrozenHub.Draggable = true 
 
UICorner.Parent = FrozenHub
 
TextLabel.Parent = FrozenHub
TextLabel.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
TextLabel.Position = UDim2.new(0, 0, 0.0062467074, 0)
TextLabel.Size = UDim2.new(0, 476, 0, 42)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = ""
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000
 
UICorner_2.Parent = TextLabel
 
FrozenHubText.Name = "FrozenHubText"
FrozenHubText.Parent = FrozenHub
FrozenHubText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FrozenHubText.BackgroundTransparency = 1.000
FrozenHubText.Position = UDim2.new(0.0252100825, 0, -0.00369003415, 0)
FrozenHubText.Size = UDim2.new(0, 200, 0, 50)
FrozenHubText.Font = Enum.Font.Cartoon
FrozenHubText.Text = "Frozen Hub "
FrozenHubText.TextColor3 = Color3.fromRGB(48, 238, 255)
FrozenHubText.TextSize = 40.000
 
UICorner_3.Parent = FrozenHubText
 
CloseButton.Name = "CloseButton"
CloseButton.Parent = FrozenHub
CloseButton.BackgroundColor3 = Color3.fromRGB(17, 255, 255)
CloseButton.Position = UDim2.new(0.863445342, 0, 0.0222588293, 0)
CloseButton.Size = UDim2.new(0, 54, 0, 35)
CloseButton.Font = Enum.Font.SourceSans
CloseButton.Text = ""
CloseButton.TextColor3 = Color3.fromRGB(0, 0, 0)
CloseButton.TextSize = 14.000
 
UICorner_4.Parent = CloseButton
 
FoodTpSF.Name = "FoodTpSF"
FoodTpSF.Parent = FrozenHub
FoodTpSF.Active = true
FoodTpSF.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
FoodTpSF.Position = UDim2.new(0.776008427, 0, 0.164167121, 0)
FoodTpSF.Size = UDim2.new(0, 106, 0, 76)
 
UICorner_5.Parent = FoodTpSF
 
BurgerButton.Name = "BurgerButton"
BurgerButton.Parent = FoodTpSF
BurgerButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
BurgerButton.Position = UDim2.new(0, 0, 0.00852615573, 0)
BurgerButton.Size = UDim2.new(0, 95, 0, 24)
BurgerButton.Font = Enum.Font.Cartoon
BurgerButton.Text = "Burger"
BurgerButton.TextColor3 = Color3.fromRGB(48, 238, 255)
BurgerButton.TextSize = 20.000
BurgerButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-274.771454, 22.647892, -803.879639, 0.999972463, -1.05459677e-07, -0.00741726346, 1.05597955e-07, 1, 1.82509954e-08, 0.00741726346, -1.90337417e-08, 0.999972463) 
 
end)
 
UICorner_6.Parent = BurgerButton
 
TacoButton.Name = "TacoButton"
TacoButton.Parent = FoodTpSF
TacoButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
TacoButton.Position = UDim2.new(0, 0, 0.0585261583, 0)
TacoButton.Size = UDim2.new(0, 95, 0, 24)
TacoButton.Font = Enum.Font.Cartoon
TacoButton.Text = "Taco"
TacoButton.TextColor3 = Color3.fromRGB(48, 238, 255)
TacoButton.TextSize = 20.000
TacoButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-282.772827, 22.647892, -803.879639, 0.999999344, -1.38746046e-08, -0.00115643325, 1.38771794e-08, 1, 2.21873298e-09, 0.00115643325, -2.23477947e-09, 0.999999344) 
end)
 
UICorner_7.Parent = TacoButton
 
CanBerryButton.Name = "CanBerryButton"
CanBerryButton.Parent = FoodTpSF
CanBerryButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
CanBerryButton.Position = UDim2.new(-0.0094339624, 0, 0.110311866, 0)
CanBerryButton.Size = UDim2.new(0, 95, 0, 24)
CanBerryButton.Font = Enum.Font.Cartoon
CanBerryButton.Text = "Canberry"
CanBerryButton.TextColor3 = Color3.fromRGB(48, 238, 255)
CanBerryButton.TextSize = 20.000
CanBerryButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-207.829163, 21.7530231, -827.642639, -0.0224982798, 4.57507188e-09, -0.999746859, -1.54677622e-08, 1, 4.92431651e-09, 0.999746859, 1.55746367e-08, -0.0224982798) 
end)
 
UICorner_8.Parent = CanBerryButton
 
PopCornButton.Name = "PopCornButton"
PopCornButton.Parent = FoodTpSF
PopCornButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
PopCornButton.Position = UDim2.new(-0.0094339624, 0, 0.158526152, 0)
PopCornButton.Size = UDim2.new(0, 95, 0, 24)
PopCornButton.Font = Enum.Font.Cartoon
PopCornButton.Text = "PopCorn"
PopCornButton.TextColor3 = Color3.fromRGB(48, 238, 255)
PopCornButton.TextSize = 20.000
PopCornButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(166.691879, 25.1280212, -998.321106, 0.999939322, 5.54006014e-08, 0.0110182576, -5.57659696e-08, 1, 3.28529843e-08, -0.0110182576, -3.34654366e-08, 0.999939322) 
end)
 
UICorner_9.Parent = PopCornButton
 
PizzaButton.Name = "PizzaButton"
PizzaButton.Parent = FoodTpSF
PizzaButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
PizzaButton.Position = UDim2.new(0, 0, 0.21031186, 0)
PizzaButton.Size = UDim2.new(0, 95, 0, 24)
PizzaButton.Font = Enum.Font.Cartoon
PizzaButton.Text = "Pizza"
PizzaButton.TextColor3 = Color3.fromRGB(48, 238, 255)
PizzaButton.TextSize = 20.000
PizzaButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-324.4487, 23.6806679, -285.318451, -0.0330012776, -2.78930479e-09, -0.999455333, -3.04010461e-09, 1, -2.69044298e-09, 0.999455333, 2.94966052e-09, -0.0330012776) 
end)
 
 
UICorner_10.Parent = PizzaButton
 
ChickenButton.Name = "ChickenButton"
ChickenButton.Parent = FoodTpSF
ChickenButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
ChickenButton.Position = UDim2.new(-0.0094339624, 0, 0.265668988, 0)
ChickenButton.Size = UDim2.new(0, 95, 0, 24)
ChickenButton.Font = Enum.Font.Cartoon
ChickenButton.Text = "Chicken"
ChickenButton.TextColor3 = Color3.fromRGB(48, 238, 255)
ChickenButton.TextSize = 20.000
ChickenButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-325.847595, 23.6806679, -296.516235, -0.0124196773, 7.86344145e-08, -0.999922872, 2.42121256e-08, 1, 7.83397454e-08, 0.999922872, -2.32373036e-08, -0.0124196773) 
end)
 
 
UICorner_11.Parent = ChickenButton
 
DonutButton.Name = "DonutButton"
DonutButton.Parent = FoodTpSF
DonutButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
DonutButton.Position = UDim2.new(0, 0, 0.317454696, 0)
DonutButton.Size = UDim2.new(0, 95, 0, 24)
DonutButton.Font = Enum.Font.Cartoon
DonutButton.Text = "Donut"
DonutButton.TextColor3 = Color3.fromRGB(48, 238, 255)
DonutButton.TextSize = 20.000
DonutButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(601.176697, 48.9980583, -252.327759, -0.00544541143, -6.05304393e-08, -0.999985158, -3.39272503e-08, 1, -6.03465864e-08, 0.999985158, 3.35981341e-08, -0.00544541143) 
end)
 
 
UICorner_12.Parent = DonutButton
 
StarBloxLatteButton.Name = "StarBloxLatteButton"
StarBloxLatteButton.Parent = FoodTpSF
StarBloxLatteButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
StarBloxLatteButton.Position = UDim2.new(-0.0094339624, 0, 0.369240403, 0)
StarBloxLatteButton.Size = UDim2.new(0, 95, 0, 24)
StarBloxLatteButton.Font = Enum.Font.Cartoon
StarBloxLatteButton.Text = "StarBlox Latte"
StarBloxLatteButton.TextColor3 = Color3.fromRGB(48, 238, 255)
StarBloxLatteButton.TextSize = 15.000
StarBloxLatteButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(601.079163, 48.9980583, -257.993195, 0.012154798, 4.36705072e-08, -0.99992615, 2.40912001e-08, 1, 4.39665797e-08, 0.99992615, -2.46238265e-08, 0.012154798) 
end)
 
 
UICorner_13.Parent = StarBloxLatteButton
 
Pizza2Button.Name = "Pizza2Button"
Pizza2Button.Parent = FoodTpSF
Pizza2Button.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
Pizza2Button.Position = UDim2.new(-0.0094339624, 0, 0.429954678, 0)
Pizza2Button.Size = UDim2.new(0, 95, 0, 24)
Pizza2Button.Font = Enum.Font.Cartoon
Pizza2Button.Text = "Pizza 2"
Pizza2Button.TextColor3 = Color3.fromRGB(48, 238, 255)
Pizza2Button.TextSize = 30.000
Pizza2Button.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(311.721222, 49.2806778, -623.808594, 0.99998039, 3.16532045e-08, -0.00625941902, -3.11588195e-08, 1, 7.90801593e-08, 0.00625941902, -7.88835735e-08, 0.99998039) 
end)
 
UICorner_14.Parent = Pizza2Button
 
Burger2Button.Name = "Burger2Button"
Burger2Button.Parent = FoodTpSF
Burger2Button.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
Burger2Button.Position = UDim2.new(0, 0, 0.487097532, 0)
Burger2Button.Size = UDim2.new(0, 95, 0, 24)
Burger2Button.Font = Enum.Font.Cartoon
Burger2Button.Text = "Burger 2"
Burger2Button.TextColor3 = Color3.fromRGB(48, 238, 255)
Burger2Button.TextSize = 25.000
Burger2Button.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-601.412659, 21.8730183, 289.429688, 0.00411823252, -2.33988473e-08, 0.999991536, -4.51974813e-08, 1, 2.358518e-08, -0.999991536, -4.52942288e-08, 0.00411823252) 
end)
 
UICorner_15.Parent = Burger2Button
 
Chicken2Button.Name = "Chicken2Button"
Chicken2Button.Parent = FoodTpSF
Chicken2Button.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
Chicken2Button.Position = UDim2.new(-0.0094339624, 0, 0.551383257, 0)
Chicken2Button.Size = UDim2.new(0, 95, 0, 24)
Chicken2Button.Font = Enum.Font.Cartoon
Chicken2Button.Text = "Chicken 2"
Chicken2Button.TextColor3 = Color3.fromRGB(48, 238, 255)
Chicken2Button.TextSize = 22.000
Chicken2Button.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(300.45639, 49.2806778, -623.795837, 0.999986887, 5.46115064e-09, 0.00512147369, -5.5369429e-09, 1, 1.47847175e-08, -0.00512147369, -1.48128807e-08, 0.999986887) 
end)
 
UICorner_16.Parent = Chicken2Button
 
Donut2Button.Name = "Donut2Button"
Donut2Button.Parent = FoodTpSF
Donut2Button.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
Donut2Button.Position = UDim2.new(-0.0094339624, 0, 0.617454708, 0)
Donut2Button.Size = UDim2.new(0, 95, 0, 24)
Donut2Button.Font = Enum.Font.Cartoon
Donut2Button.Text = "Donut 2"
Donut2Button.TextColor3 = Color3.fromRGB(48, 238, 255)
Donut2Button.TextSize = 22.000
Donut2Button.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-601.409119, 21.8730183, 274.527588, -0.00222188071, 3.92492616e-08, 0.999997556, -1.96634993e-08, 1, -3.92930488e-08, -0.999997556, -1.97507557e-08, -0.00222188071) 
end)
 
UICorner_17.Parent = Donut2Button
 
PepperSprayButton.Name = "PepperSprayButton"
PepperSprayButton.Parent = FoodTpSF
PepperSprayButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
PepperSprayButton.Position = UDim2.new(0, 0, 0.672811866, 0)
PepperSprayButton.Size = UDim2.new(0, 95, 0, 24)
PepperSprayButton.Font = Enum.Font.Cartoon
PepperSprayButton.Text = "Pepper Spray"
PepperSprayButton.TextColor3 = Color3.fromRGB(48, 238, 255)
PepperSprayButton.TextSize = 15.000
PepperSprayButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-214.120758, 21.7530231, -816.730286, -0.999992847, 3.91884782e-08, -0.00378896436, 3.92064265e-08, 1, -4.66314187e-09, 0.00378896436, -4.81165996e-09, -0.999992847)
end)
 
UICorner_18.Parent = PepperSprayButton
 
FlyButton.Name = "FlyButton"
FlyButton.Parent = FrozenHub
FlyButton.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
FlyButton.BorderColor3 = Color3.fromRGB(65, 65, 65)
FlyButton.Position = UDim2.new(0, 0, 0.178571433, 0)
FlyButton.Size = UDim2.new(0, 86, 0, 32)
FlyButton.Font = Enum.Font.Cartoon
FlyButton.Text = "Fly"
FlyButton.TextColor3 = Color3.fromRGB(48, 238, 255)
FlyButton.TextSize = 35.000
FlyButton.MouseButton1Click:Connect(function()
	repeat wait() until game.Players.LocalPlayer.Character
 
	local player = game.Players.LocalPlayer
	local character = player.Character
	local humanoid = character:WaitForChild("Humanoid")
	local torso = character:WaitForChild("LowerTorso")
	local mouse = player:GetMouse()
 
	local enabled = false 
 
	mouse.KeyDown:Connect(function(key)
		if key == "x" then
			if enabled == false then
				enabled = true 
				local bodyvelocity = Instance.new("BodyVelocity", torso)
				bodyvelocity.MaxForce = Vector3.new(math.huge,math.huge,math.huge)
 
				while enabled == true do
					bodyvelocity.Velocity = mouse.Hit.lookVector * 100
					wait()
				end
 
 
			end
 
			if enabled == true then
				enabled = false 
				torso:FindFirstChild("BodyVelocity"):Destroy()
			end
		end
	end)
end)
 
UICorner_19.Parent = FlyButton
 
Version.Name = "Version"
Version.Parent = FrozenHub
Version.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Version.BackgroundTransparency = 1.000
Version.Position = UDim2.new(0.264705867, 0, 0.00345282303, 0)
Version.Size = UDim2.new(0, 200, 0, 50)
Version.Font = Enum.Font.Cartoon
Version.Text = "1.0"
Version.TextColor3 = Color3.fromRGB(48, 238, 255)
Version.TextSize = 40.000
 
UICorner_20.Parent = Version
 
Credits.Name = "Credits"
Credits.Parent = FrozenHub
Credits.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Credits.BackgroundTransparency = 1.000
Credits.Position = UDim2.new(0.502100825, 0, 0.0213099662, 0)
Credits.Size = UDim2.new(0, 200, 0, 50)
Credits.Font = Enum.Font.Cartoon
Credits.Text = "Made by Kostas#0001"
Credits.TextColor3 = Color3.fromRGB(48, 238, 255)
Credits.TextSize = 15.000
 
UICorner_21.Parent = Credits
 
FoodTpLabel.Name = "FoodTpLabel"
FoodTpLabel.Parent = FrozenHub
FoodTpLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FoodTpLabel.BackgroundTransparency = 1.000
FoodTpLabel.Position = UDim2.new(0.607142866, 0, 0.210595712, 0)
FoodTpLabel.Size = UDim2.new(0, 79, 0, 50)
FoodTpLabel.Font = Enum.Font.Cartoon
FoodTpLabel.Text = "Food TP"
FoodTpLabel.TextColor3 = Color3.fromRGB(48, 238, 255)
FoodTpLabel.TextSize = 25.000
 
UICorner_22.Parent = FoodTpLabel
 
GunsTpSF.Name = "GunsTpSF"
GunsTpSF.Parent = FrozenHub
GunsTpSF.Active = true
GunsTpSF.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
GunsTpSF.Position = UDim2.new(0.773907602, 0, 0.457024276, 0)
GunsTpSF.Size = UDim2.new(0, 106, 0, 67)
 
UICorner_23.Parent = GunsTpSF
 
RevolverButton.Name = "RevolverButton"
RevolverButton.Parent = GunsTpSF
RevolverButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
RevolverButton.Position = UDim2.new(0, 0, 0.00852615573, 0)
RevolverButton.Size = UDim2.new(0, 95, 0, 24)
RevolverButton.Font = Enum.Font.Cartoon
RevolverButton.Text = "Revolver"
RevolverButton.TextColor3 = Color3.fromRGB(48, 238, 255)
RevolverButton.TextSize = 15.000
RevolverButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-638.601624, 21.7480202, -123.792183, -0.999904811, 7.32983985e-09, 0.0137979398, 6.03266237e-09, 1, -9.40540232e-08, -0.0137979398, -9.39618303e-08, -0.999904811)
end)
 
UICorner_24.Parent = RevolverButton
 
DoubleBarrelButton.Name = "DoubleBarrelButton"
DoubleBarrelButton.Parent = GunsTpSF
DoubleBarrelButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
DoubleBarrelButton.Position = UDim2.new(0, 0, 0.0638832971, 0)
DoubleBarrelButton.Size = UDim2.new(0, 95, 0, 24)
DoubleBarrelButton.Font = Enum.Font.Cartoon
DoubleBarrelButton.Text = "Double Barrel"
DoubleBarrelButton.TextColor3 = Color3.fromRGB(48, 238, 255)
DoubleBarrelButton.TextSize = 15.000
DoubleBarrelButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1039.65466, 21.7480202, -261.678497, -0.999978662, 2.73100431e-09, -0.00653474545, 2.4805864e-09, 1, 3.83290875e-08, 0.00653474545, 3.83120593e-08, -0.999978662)
end)
 
UICorner_25.Parent = DoubleBarrelButton
 
FlameThrowerButton.Name = "FlameThrowerButton"
FlameThrowerButton.Parent = GunsTpSF
FlameThrowerButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
FlameThrowerButton.Position = UDim2.new(0, 0, 0.117454723, 0)
FlameThrowerButton.Size = UDim2.new(0, 95, 0, 24)
FlameThrowerButton.Font = Enum.Font.Cartoon
FlameThrowerButton.Text = "Flame Thrower"
FlameThrowerButton.TextColor3 = Color3.fromRGB(48, 238, 255)
FlameThrowerButton.TextSize = 15.000
FlameThrowerButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-157.165833, 53.8086281, -99.1251984, 0.999804437, -1.29598909e-08, -0.0197750013, 1.36690881e-08, 1, 3.57281387e-08, 0.0197750013, -3.59914587e-08, 0.999804437)
end)
 
UICorner_26.Parent = FlameThrowerButton
 
_20kRPGButton.Name = "$20kRPGButton"
_20kRPGButton.Parent = GunsTpSF
_20kRPGButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
_20kRPGButton.Position = UDim2.new(0, 0, 0.172811866, 0)
_20kRPGButton.Size = UDim2.new(0, 95, 0, 24)
_20kRPGButton.Font = Enum.Font.Cartoon
_20kRPGButton.Text = "$20k RPG"
_20kRPGButton.TextColor3 = Color3.fromRGB(48, 238, 255)
_20kRPGButton.TextSize = 15.000
_20kRPGButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(113.609001, -26.7520103, -275.426819, -0.999690533, 1.9806784e-10, 0.0248774029, 1.23806118e-10, 1, -2.98664804e-09, -0.0248774029, -2.98264391e-09, -0.999690533)
end)
 
UICorner_27.Parent = _20kRPGButton
 
_6kRPGButton.Name = "$6kRPGButton"
_6kRPGButton.Parent = GunsTpSF
_6kRPGButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
_6kRPGButton.Position = UDim2.new(0, 0, 0.226383299, 0)
_6kRPGButton.Size = UDim2.new(0, 95, 0, 24)
_6kRPGButton.Font = Enum.Font.Cartoon
_6kRPGButton.Text = "$6k RPG"
_6kRPGButton.TextColor3 = Color3.fromRGB(48, 238, 255)
_6kRPGButton.TextSize = 15.000
_6kRPGButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-790.518616, -39.6511879, -932.861511, -0.00231389143, -5.91973492e-09, 0.999997318, 8.33165288e-08, 1, 6.1125367e-09, -0.999997318, 8.33304554e-08, -0.00231389143)
end)
 
UICorner_28.Parent = _6kRPGButton
 
ShotGunButton.Name = "ShotGunButton"
ShotGunButton.Parent = GunsTpSF
ShotGunButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
ShotGunButton.Position = UDim2.new(0, 0, 0.285311878, 0)
ShotGunButton.Size = UDim2.new(0, 95, 0, 24)
ShotGunButton.Font = Enum.Font.Cartoon
ShotGunButton.Text = "ShotGun"
ShotGunButton.TextColor3 = Color3.fromRGB(48, 238, 255)
ShotGunButton.TextSize = 15.000
ShotGunButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-581.899597, 8.31280422, -724.745972, -0.0263437554, 3.18295967e-08, -0.999652922, -4.92068608e-08, 1, 3.31373897e-08, 0.999652922, 5.00627451e-08, -0.0263437554)
end)
 
UICorner_29.Parent = ShotGunButton
 
TacticalShotGunButton.Name = "TacticalShotGunButton"
TacticalShotGunButton.Parent = GunsTpSF
TacticalShotGunButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
TacticalShotGunButton.Position = UDim2.new(0, 0, 0.346026152, 0)
TacticalShotGunButton.Size = UDim2.new(0, 95, 0, 24)
TacticalShotGunButton.Font = Enum.Font.Cartoon
TacticalShotGunButton.Text = "Tac ShotGun"
TacticalShotGunButton.TextColor3 = Color3.fromRGB(48, 238, 255)
TacticalShotGunButton.TextSize = 15.000
TacticalShotGunButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(470.679382, 48.0685158, -624.215942, -0.999962866, 6.74201885e-08, 0.0086163776, 6.66438709e-08, 1, -9.03852921e-08, -0.0086163776, -8.98077062e-08, -0.999962866)
end)
 
UICorner_30.Parent = TacticalShotGunButton
 
P90Button.Name = "P90Button"
P90Button.Parent = GunsTpSF
P90Button.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
P90Button.Position = UDim2.new(0, 0, 0.399597585, 0)
P90Button.Size = UDim2.new(0, 95, 0, 24)
P90Button.Font = Enum.Font.Cartoon
P90Button.Text = "P90"
P90Button.TextColor3 = Color3.fromRGB(48, 238, 255)
P90Button.TextSize = 15.000
P90Button.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(465.623566, 48.0685158, -619.040222, 0.0277550034, 7.10094454e-08, 0.999614775, -2.09982947e-08, 1, -7.04537797e-08, -0.999614775, -1.90347613e-08, 0.0277550034)
end)
 
UICorner_31.Parent = P90Button
 
SilencerArButton.Name = "SilencerArButton"
SilencerArButton.Parent = GunsTpSF
SilencerArButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
SilencerArButton.Position = UDim2.new(0.0094339624, 0, 0.458526134, 0)
SilencerArButton.Size = UDim2.new(0, 95, 0, 24)
SilencerArButton.Font = Enum.Font.Cartoon
SilencerArButton.Text = "Silencer AR"
SilencerArButton.TextColor3 = Color3.fromRGB(48, 238, 255)
SilencerArButton.TextSize = 15.000
SilencerArButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(490.658539, 48.0685234, -631.530945, 0.999624074, -9.41550127e-08, -0.0274168178, 9.26915007e-08, 1, -5.46509469e-08, 0.0274168178, 5.20890957e-08, 0.999624074)
end)
 
UICorner_32.Parent = SilencerArButton
 
SilencerButton.Name = "SilencerButton"
SilencerButton.Parent = GunsTpSF
SilencerButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
SilencerButton.Position = UDim2.new(0, 0, 0.519240439, 0)
SilencerButton.Size = UDim2.new(0, 95, 0, 24)
SilencerButton.Font = Enum.Font.Cartoon
SilencerButton.Text = "Silencer "
SilencerButton.TextColor3 = Color3.fromRGB(48, 238, 255)
SilencerButton.TextSize = 15.000
SilencerButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(495.491669, 48.0685158, -621.501221, 0.00779420184, -8.45573744e-09, -0.999969602, 2.12927294e-08, 1, -8.29002911e-09, 0.999969602, -2.12274678e-08, 0.00779420184)
end)
 
UICorner_33.Parent = SilencerButton
 
GlockButton.Name = "GlockButton"
GlockButton.Parent = GunsTpSF
GlockButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
GlockButton.Position = UDim2.new(0, 0, 0.579954743, 0)
GlockButton.Size = UDim2.new(0, 95, 0, 24)
GlockButton.Font = Enum.Font.Cartoon
GlockButton.Text = "Glock"
GlockButton.TextColor3 = Color3.fromRGB(48, 238, 255)
GlockButton.TextSize = 15.000
GlockButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(496.2453, 48.0685158, -629.267761, -0.0407462567, -1.85926528e-08, -0.999169528, 4.44704362e-08, 1, -2.04216164e-08, 0.999169528, -4.52656117e-08, -0.0407462567)
end)
 
UICorner_34.Parent = GlockButton
 
SMGButton.Name = "SMGButton"
SMGButton.Parent = GunsTpSF
SMGButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
SMGButton.Position = UDim2.new(0, 0, 0.631740451, 0)
SMGButton.Size = UDim2.new(0, 95, 0, 24)
SMGButton.Font = Enum.Font.Cartoon
SMGButton.Text = "SMG"
SMGButton.TextColor3 = Color3.fromRGB(48, 238, 255)
SMGButton.TextSize = 15.000
SMGButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-576.883789, 8.31280422, -719.800293, -0.999641776, -2.06766675e-08, 0.0267634466, -2.22495089e-08, 1, -5.84704871e-08, -0.0267634466, -5.90450142e-08, -0.999641776)
end)
 
UICorner_35.Parent = SMGButton
 
AK47Button.Name = "AK47Button"
AK47Button.Parent = GunsTpSF
AK47Button.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
AK47Button.Position = UDim2.new(0, 0, 0.687097669, 0)
AK47Button.Size = UDim2.new(0, 95, 0, 24)
AK47Button.Font = Enum.Font.Cartoon
AK47Button.Text = "AK47"
AK47Button.TextColor3 = Color3.fromRGB(48, 238, 255)
AK47Button.TextSize = 15.000
AK47Button.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-587.541382, 8.31280422, -750.389465, 0.999372125, -4.17936352e-09, -0.0354303531, 2.41876297e-09, 1, -4.97347301e-08, 0.0354303531, 4.96178068e-08, 0.999372125)
end)
 
UICorner_36.Parent = AK47Button
 
DrumGunButton.Name = "DrumGunButton"
DrumGunButton.Parent = GunsTpSF
DrumGunButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
DrumGunButton.Position = UDim2.new(0, 0, 0.744240522, 0)
DrumGunButton.Size = UDim2.new(0, 95, 0, 24)
DrumGunButton.Font = Enum.Font.Cartoon
DrumGunButton.Text = "DrumGum"
DrumGunButton.TextColor3 = Color3.fromRGB(48, 238, 255)
DrumGunButton.TextSize = 15.000
DrumGunButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-78.2484741, 22.8027725, -85.7358475, -0.999937773, -4.2142279e-08, 0.0111581804, -4.23651016e-08, 1, -1.97332763e-08, -0.0111581804, -2.02047659e-08, -0.999937773)
end)
 
UICorner_37.Parent = DrumGunButton
 
AUGButton.Name = "AUGButton"
AUGButton.Parent = GunsTpSF
AUGButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
AUGButton.Position = UDim2.new(0, 0, 0.804954767, 0)
AUGButton.Size = UDim2.new(0, 95, 0, 24)
AUGButton.Font = Enum.Font.Cartoon
AUGButton.Text = "AUG"
AUGButton.TextColor3 = Color3.fromRGB(48, 238, 255)
AUGButton.TextSize = 15.000
AUGButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-272.612, 52.4884796, -217.939453, -0.999906957, 1.27559152e-09, 0.0136420252, 4.15293577e-10, 1, -6.30651655e-08, -0.0136420252, -6.30536334e-08, -0.999906957)
end)
 
UICorner_38.Parent = AUGButton
 
HighMediumArmorButton.Name = "HighMediumArmorButton"
HighMediumArmorButton.Parent = GunsTpSF
HighMediumArmorButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
HighMediumArmorButton.Position = UDim2.new(0, 0, 0.862097621, 0)
HighMediumArmorButton.Size = UDim2.new(0, 95, 0, 24)
HighMediumArmorButton.Font = Enum.Font.Cartoon
HighMediumArmorButton.Text = "High Medium Armor"
HighMediumArmorButton.TextColor3 = Color3.fromRGB(48, 238, 255)
HighMediumArmorButton.TextSize = 10.000
HighMediumArmorButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-933.781921, -28.5019836, 565.307739, -0.999503672, 2.64601727e-08, 0.0315028988, 2.60706834e-08, 1, -1.277433e-08, -0.0315028988, -1.19466872e-08, -0.999503672)
end)
 
 
UICorner_39.Parent = HighMediumArmorButton
 
MediumArmorPCButton.Name = "MediumArmorPCButton"
MediumArmorPCButton.Parent = GunsTpSF
MediumArmorPCButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
MediumArmorPCButton.Position = UDim2.new(0, 0, 0.92102617, 0)
MediumArmorPCButton.Size = UDim2.new(0, 95, 0, 24)
MediumArmorPCButton.Font = Enum.Font.Cartoon
MediumArmorPCButton.Text = "Medium Armor Police"
MediumArmorPCButton.TextColor3 = Color3.fromRGB(48, 238, 255)
MediumArmorPCButton.TextSize = 10.000
MediumArmorPCButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-257.370453, 21.7979774, -76.8927307, 0.99832356, 8.99725894e-09, -0.0578793995, -1.07275246e-08, 1, -2.95836156e-08, 0.0578793995, 3.01549221e-08, 0.99832356)
end)
 
 
UICorner_40.Parent = MediumArmorPCButton
 
MediumArmorDHButton.Name = "MediumArmorDHButton"
MediumArmorDHButton.Parent = GunsTpSF
MediumArmorDHButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
MediumArmorDHButton.Position = UDim2.new(0, 0, 0.965669036, 0)
MediumArmorDHButton.Size = UDim2.new(0, 95, 0, 24)
MediumArmorDHButton.Font = Enum.Font.Cartoon
MediumArmorDHButton.Text = "Medium Armor DH"
MediumArmorDHButton.TextColor3 = Color3.fromRGB(48, 238, 255)
MediumArmorDHButton.TextSize = 10.000
MediumArmorDHButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-606.042297, 10.3477135, -788.486816, 0.0265148636, -8.36093506e-08, 0.999648392, -6.66198341e-09, 1, 8.38154577e-08, -0.999648392, -8.88199647e-09, 0.0265148636)
end)
 
 
UICorner_41.Parent = MediumArmorDHButton
 
GunsTpLabel.Name = "GunsTpLabel"
GunsTpLabel.Parent = FrozenHub
GunsTpLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GunsTpLabel.BackgroundTransparency = 1.000
GunsTpLabel.Position = UDim2.new(0.594537795, 0, 0.478452861, 0)
GunsTpLabel.Size = UDim2.new(0, 79, 0, 50)
GunsTpLabel.Font = Enum.Font.Cartoon
GunsTpLabel.Text = "Guns TP"
GunsTpLabel.TextColor3 = Color3.fromRGB(48, 238, 255)
GunsTpLabel.TextSize = 25.000
 
UICorner_42.Parent = GunsTpLabel
 
LocationTpSF.Name = "LocationTpSF"
LocationTpSF.Parent = FrozenHub
LocationTpSF.Active = true
LocationTpSF.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
LocationTpSF.Position = UDim2.new(0.773907602, 0, 0.724881411, 0)
LocationTpSF.Size = UDim2.new(0, 106, 0, 70)
 
UICorner_43.Parent = LocationTpSF
 
BankTPButton.Name = "BankTPButton"
BankTPButton.Parent = LocationTpSF
BankTPButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
BankTPButton.Position = UDim2.new(0, 0, 0.00852615573, 0)
BankTPButton.Size = UDim2.new(0, 95, 0, 24)
BankTPButton.Font = Enum.Font.Cartoon
BankTPButton.Text = "Bank"
BankTPButton.TextColor3 = Color3.fromRGB(48, 238, 255)
BankTPButton.TextSize = 20.000
BankTPButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-443.827301, 38.9954453, -283.855194, 0.0213130936, 8.4739753e-08, -0.999772847, 2.06969055e-08, 1, 8.52002273e-08, 0.999772847, -2.25080843e-08, 0.0213130936)
end)
 
UICorner_44.Parent = BankTPButton
 
CasinoTPButton.Name = "CasinoTPButton"
CasinoTPButton.Parent = LocationTpSF
CasinoTPButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
CasinoTPButton.Position = UDim2.new(0.0094339624, 0, 0.0674547255, 0)
CasinoTPButton.Size = UDim2.new(0, 95, 0, 24)
CasinoTPButton.Font = Enum.Font.Cartoon
CasinoTPButton.Text = "Casino"
CasinoTPButton.TextColor3 = Color3.fromRGB(48, 238, 255)
CasinoTPButton.TextSize = 20.000
CasinoTPButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1005.64337, 49.5979729, -140.114838, 0.999962509, -2.49530423e-08, -0.00865768455, 2.45369538e-08, 1, -4.8166374e-08, 0.00865768455, 4.79521347e-08, 0.999962509)
end)
 
UICorner_45.Parent = CasinoTPButton
 
ABAllGunsButton.Name = "ABAllGunsButton"
ABAllGunsButton.Parent = LocationTpSF
ABAllGunsButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
ABAllGunsButton.Position = UDim2.new(0, 0, 0.122811869, 0)
ABAllGunsButton.Size = UDim2.new(0, 95, 0, 24)
ABAllGunsButton.Font = Enum.Font.Cartoon
ABAllGunsButton.Text = "Admin base 1"
ABAllGunsButton.TextColor3 = Color3.fromRGB(48, 238, 255)
ABAllGunsButton.TextSize = 15.000
ABAllGunsButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-875.140991, -33.8614006, -537.132446, -0.999922991, 8.72552786e-09, -0.0124095315, 8.01801203e-09, 1, 5.70636658e-08, 0.0124095315, 5.69597738e-08, -0.999922991)
end)
 
UICorner_46.Parent = ABAllGunsButton
 
AdminBaseButton.Name = "AdminBaseButton"
AdminBaseButton.Parent = LocationTpSF
AdminBaseButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
AdminBaseButton.Position = UDim2.new(0, 0, 0.179954723, 0)
AdminBaseButton.Size = UDim2.new(0, 95, 0, 24)
AdminBaseButton.Font = Enum.Font.Cartoon
AdminBaseButton.Text = "Admin base 2"
AdminBaseButton.TextColor3 = Color3.fromRGB(48, 238, 255)
AdminBaseButton.TextSize = 15.000
AdminBaseButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-797.612305, -39.6511879, -898.220642, -0.977431357, 2.66475997e-08, 0.211253226, 2.53373837e-08, 1, -8.90895446e-09, -0.211253226, -3.3552876e-09, -0.977431357)
end)
 
UICorner_47.Parent = AdminBaseButton
 
SchoolTPButton.Name = "SchoolTPButton"
SchoolTPButton.Parent = LocationTpSF
SchoolTPButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
SchoolTPButton.Position = UDim2.new(0, 0, 0.237097576, 0)
SchoolTPButton.Size = UDim2.new(0, 95, 0, 24)
SchoolTPButton.Font = Enum.Font.Cartoon
SchoolTPButton.Text = "School"
SchoolTPButton.TextColor3 = Color3.fromRGB(48, 238, 255)
SchoolTPButton.TextSize = 20.000
SchoolTPButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-619.982422, 21.2480221, 208.335999, -0.996029675, 5.03382296e-08, -0.0890220851, 4.26572058e-08, 1, 8.81846987e-08, 0.0890220851, 8.40371399e-08, -0.996029675)
end)
 
 
UICorner_48.Parent = SchoolTPButton
 
HoodFitTPButton.Name = "HoodFitTPButton"
HoodFitTPButton.Parent = LocationTpSF
HoodFitTPButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
HoodFitTPButton.Position = UDim2.new(0, 0, 0.29602614, 0)
HoodFitTPButton.Size = UDim2.new(0, 95, 0, 24)
HoodFitTPButton.Font = Enum.Font.Cartoon
HoodFitTPButton.Text = "Hood Fit"
HoodFitTPButton.TextColor3 = Color3.fromRGB(48, 238, 255)
HoodFitTPButton.TextSize = 20.000
HoodFitTPButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-75.7986984, 21.7530231, -599.938843, 0.985586643, -2.58283865e-08, 0.169171333, 2.27611654e-08, 1, 2.00700985e-08, -0.169171333, -1.59302846e-08, 0.985586643)
end)
 
 
UICorner_49.Parent = HoodFitTPButton
 
HoodKicksTPButton.Name = "HoodKicksTPButton"
HoodKicksTPButton.Parent = LocationTpSF
HoodKicksTPButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
HoodKicksTPButton.Position = UDim2.new(0.0094339624, 0, 0.351383299, 0)
HoodKicksTPButton.Size = UDim2.new(0, 95, 0, 24)
HoodKicksTPButton.Font = Enum.Font.Cartoon
HoodKicksTPButton.Text = "Hood Kicks"
HoodKicksTPButton.TextColor3 = Color3.fromRGB(48, 238, 255)
HoodKicksTPButton.TextSize = 20.000
HoodKicksTPButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-187.337204, 21.7530231, -410.240051, -0.0507876165, -6.08253217e-08, 0.9987095, 3.77629945e-08, 1, 6.28242915e-08, -0.9987095, 4.09049576e-08, -0.0507876165)
end)
 
UICorner_50.Parent = HoodKicksTPButton
 
UpHillTPButon.Name = "UpHillTPButon"
UpHillTPButon.Parent = LocationTpSF
UpHillTPButon.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
UpHillTPButon.Position = UDim2.new(0.0094339624, 0, 0.410311878, 0)
UpHillTPButon.Size = UDim2.new(0, 95, 0, 24)
UpHillTPButon.Font = Enum.Font.Cartoon
UpHillTPButon.Text = "Up Hill Shop"
UpHillTPButon.TextColor3 = Color3.fromRGB(48, 238, 255)
UpHillTPButon.TextSize = 15.000
UpHillTPButon.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(480.919006, 48.0030136, -596.770691, 0.999710441, -2.7938988e-08, -0.0240638703, 3.04541956e-08, 1, 1.04155745e-07, 0.0240638703, -1.04858429e-07, 0.999710441)
end)
 
UICorner_51.Parent = UpHillTPButon
 
DownHillTPButton.Name = "DownHillTPButton"
DownHillTPButton.Parent = LocationTpSF
DownHillTPButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
DownHillTPButton.Position = UDim2.new(0, 0, 0.465669036, 0)
DownHillTPButton.Size = UDim2.new(0, 95, 0, 24)
DownHillTPButton.Font = Enum.Font.Cartoon
DownHillTPButton.Text = "Down Hill Shop"
DownHillTPButton.TextColor3 = Color3.fromRGB(48, 238, 255)
DownHillTPButton.TextSize = 15.000
DownHillTPButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-557.427612, 7.99787045, -736.275879, 0.03801734, 6.72411318e-08, 0.999277055, -4.68214516e-08, 1, -6.55084662e-08, -0.999277055, -4.42971455e-08, 0.03801734)
end)
 
UICorner_52.Parent = DownHillTPButton
 
TrainTPButton.Name = "TrainTPButton"
TrainTPButton.Parent = LocationTpSF
TrainTPButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
TrainTPButton.Position = UDim2.new(0, 0, 0.524597585, 0)
TrainTPButton.Size = UDim2.new(0, 95, 0, 24)
TrainTPButton.Font = Enum.Font.Cartoon
TrainTPButton.Text = "Train"
TrainTPButton.TextColor3 = Color3.fromRGB(48, 238, 255)
TrainTPButton.TextSize = 20.000
TrainTPButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(583.734863, 34.4980125, -133.031525, 0.897819638, -8.82528539e-08, 0.440363318, 9.73705596e-08, 1, 1.88855998e-09, -0.440363318, 4.11828367e-08, 0.897819638)
end)
 
UICorner_53.Parent = TrainTPButton
 
SewerTPButton.Name = "SewerTPButton"
SewerTPButton.Parent = LocationTpSF
SewerTPButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
SewerTPButton.Position = UDim2.new(0.0094339624, 0, 0.581740439, 0)
SewerTPButton.Size = UDim2.new(0, 95, 0, 24)
SewerTPButton.Font = Enum.Font.Cartoon
SewerTPButton.Text = "Sewer"
SewerTPButton.TextColor3 = Color3.fromRGB(48, 238, 255)
SewerTPButton.TextSize = 20.000
SewerTPButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-421.873993, -21.2519798, 37.4928894, -0.999464154, -8.69155503e-09, -0.032732822, -9.90285987e-09, 1, 3.68436943e-08, 0.032732822, 3.71480979e-08, -0.999464154)
end)
 
UICorner_54.Parent = SewerTPButton
 
TOBTPButton.Name = "TOBTPButton"
TOBTPButton.Parent = LocationTpSF
TOBTPButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
TOBTPButton.Position = UDim2.new(0, 0, 0.638883293, 0)
TOBTPButton.Size = UDim2.new(0, 95, 0, 24)
TOBTPButton.Font = Enum.Font.Cartoon
TOBTPButton.Text = "Top Of Bank"
TOBTPButton.TextColor3 = Color3.fromRGB(48, 238, 255)
TOBTPButton.TextSize = 15.000
TOBTPButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-330.669373, 80.4318924, -289.412445, -0.0181988254, 1.17059592e-07, 0.999834359, 8.39122816e-09, 1, -1.16926245e-07, -0.999834359, 6.26191854e-09, -0.0181988254)
end)
 
UICorner_55.Parent = TOBTPButton
 
OtherLocations.Name = "OtherLocations"
OtherLocations.Parent = LocationTpSF
OtherLocations.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
OtherLocations.Position = UDim2.new(0, 0, 0.699597597, 0)
OtherLocations.Size = UDim2.new(0, 95, 0, 24)
OtherLocations.Font = Enum.Font.Cartoon
OtherLocations.Text = "Other Locations "
OtherLocations.TextColor3 = Color3.fromRGB(48, 238, 255)
OtherLocations.TextSize = 10.000
 
UICorner_56.Parent = OtherLocations
 
FireWorkTPButton.Name = "FireWorkTPButton"
FireWorkTPButton.Parent = LocationTpSF
FireWorkTPButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
FireWorkTPButton.Position = UDim2.new(0, 0, 0.760311842, 0)
FireWorkTPButton.Size = UDim2.new(0, 95, 0, 24)
FireWorkTPButton.Font = Enum.Font.Cartoon
FireWorkTPButton.Text = "FireWork"
FireWorkTPButton.TextColor3 = Color3.fromRGB(48, 238, 255)
FireWorkTPButton.TextSize = 15.000
FireWorkTPButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-836.810608, 21.7980328, -298.707642, 0.999813259, 4.49756534e-08, -0.0193243064, -4.33450573e-08, 1, 8.47995238e-08, 0.0193243064, -8.39460768e-08, 0.999813259)
end)
 
 
UICorner_57.Parent = FireWorkTPButton
 
MasksTPButton.Name = "MasksTPButton"
MasksTPButton.Parent = LocationTpSF
MasksTPButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
MasksTPButton.Position = UDim2.new(0, 0, 0.817454696, 0)
MasksTPButton.Size = UDim2.new(0, 95, 0, 24)
MasksTPButton.Font = Enum.Font.Cartoon
MasksTPButton.Text = "Masks"
MasksTPButton.TextColor3 = Color3.fromRGB(48, 238, 255)
MasksTPButton.TextSize = 15.000
MasksTPButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-212.21579, 21.7530231, -825.271179, 0.0128095821, -7.40249675e-08, 0.999917924, -2.68082996e-08, 1, 7.43744764e-08, -0.999917924, -2.77588068e-08, 0.0128095821)
end)
 
 
UICorner_58.Parent = MasksTPButton
 
SledgeHammerTPButton.Name = "SledgeHammerTPButton"
SledgeHammerTPButton.Parent = LocationTpSF
SledgeHammerTPButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
SledgeHammerTPButton.Position = UDim2.new(0.0094339624, 0, 0.876383245, 0)
SledgeHammerTPButton.Size = UDim2.new(0, 95, 0, 24)
SledgeHammerTPButton.Font = Enum.Font.Cartoon
SledgeHammerTPButton.Text = "Hammer"
SledgeHammerTPButton.TextColor3 = Color3.fromRGB(48, 238, 255)
SledgeHammerTPButton.TextSize = 15.000
SledgeHammerTPButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-900.376282, 21.7480202, -295.888733, 0.0256226715, -2.29450823e-08, 0.999671698, 6.3381151e-08, 1, 2.13280895e-08, -0.999671698, 6.28138608e-08, 0.0256226715)
end)
 
 
UICorner_59.Parent = SledgeHammerTPButton
 
StopSignTPButton.Name = "StopSignTPButton"
StopSignTPButton.Parent = LocationTpSF
StopSignTPButton.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
StopSignTPButton.Position = UDim2.new(0.0094339624, 0, 0.938883245, 0)
StopSignTPButton.Size = UDim2.new(0, 95, 0, 24)
StopSignTPButton.Font = Enum.Font.Cartoon
StopSignTPButton.Text = "Stop Sign"
StopSignTPButton.TextColor3 = Color3.fromRGB(48, 238, 255)
StopSignTPButton.TextSize = 15.000
StopSignTPButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-225.556534, 21.9748363, -81.7998352, -0.999848425, 8.29760261e-10, 0.0174111594, 9.32595112e-10, 1, 5.8981402e-09, -0.0174111594, 5.91348348e-09, -0.999848425)
end)
 
UICorner_60.Parent = StopSignTPButton
 
LocationTpLabel.Name = "LocationTpLabel"
LocationTpLabel.Parent = FrozenHub
LocationTpLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LocationTpLabel.BackgroundTransparency = 1.000
LocationTpLabel.Position = UDim2.new(0.589999974, 0, 0.760999978, 0)
LocationTpLabel.Size = UDim2.new(0, 79, 0, 50)
LocationTpLabel.Font = Enum.Font.Cartoon
LocationTpLabel.Text = "Locations"
LocationTpLabel.TextColor3 = Color3.fromRGB(48, 238, 255)
LocationTpLabel.TextSize = 25.000
 
UICorner_61.Parent = LocationTpLabel
 
SpeedButton.Name = "SpeedButton"
SpeedButton.Parent = FrozenHub
SpeedButton.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
SpeedButton.BorderColor3 = Color3.fromRGB(65, 65, 65)
SpeedButton.Position = UDim2.new(0, 0, 0.339285731, 0)
SpeedButton.Size = UDim2.new(0, 86, 0, 32)
SpeedButton.Font = Enum.Font.Cartoon
SpeedButton.Text = "Speed"
SpeedButton.TextColor3 = Color3.fromRGB(48, 238, 255)
SpeedButton.TextSize = 35.000
SpeedButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100 
end)
 
UICorner_62.Parent = SpeedButton
 
InfJumpButton.Name = "InfJumpButton"
InfJumpButton.Parent = FrozenHub
InfJumpButton.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
InfJumpButton.BorderColor3 = Color3.fromRGB(65, 65, 65)
InfJumpButton.Position = UDim2.new(0, 0, 0.514285684, 0)
InfJumpButton.Size = UDim2.new(0, 86, 0, 32)
InfJumpButton.Font = Enum.Font.Cartoon
InfJumpButton.Text = "Inf Jump"
InfJumpButton.TextColor3 = Color3.fromRGB(48, 238, 255)
InfJumpButton.TextSize = 23.000
InfJumpButton.MouseButton1Click:Connect(function()
	local InfiniteJumpEnabled = true
	game:GetService("UserInputService").JumpRequest:connect(function()
		if InfiniteJumpEnabled then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
		end
	end)
end)
 
UICorner_63.Parent = InfJumpButton
 
TeleportQ.Name = "Teleport(Q)"
TeleportQ.Parent = FrozenHub
TeleportQ.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
TeleportQ.BorderColor3 = Color3.fromRGB(65, 65, 65)
TeleportQ.Position = UDim2.new(0, 0, 0.692857146, 0)
TeleportQ.Size = UDim2.new(0, 86, 0, 32)
TeleportQ.Font = Enum.Font.Cartoon
TeleportQ.Text = "Teleport(Q)"
TeleportQ.TextColor3 = Color3.fromRGB(48, 238, 255)
TeleportQ.TextSize = 15.000
TeleportQ.MouseButton1Click:Connect(function()
	local Player = game:GetService("Players").LocalPlayer
	local Mouse = Player:GetMouse()
	Mouse.KeyDown:Connect(function(key)
		if key == "q" then
			Player.Character:MoveTo(Mouse.Hit.p)
		end
	end)
end)
 
UICorner_64.Parent = TeleportQ
 
ResetButton.Name = "ResetButton"
ResetButton.Parent = FrozenHub
ResetButton.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
ResetButton.BorderColor3 = Color3.fromRGB(65, 65, 65)
ResetButton.Position = UDim2.new(0, 0, 0.853571415, 0)
ResetButton.Size = UDim2.new(0, 86, 0, 32)
ResetButton.Font = Enum.Font.Cartoon
ResetButton.Text = "Reset"
ResetButton.TextColor3 = Color3.fromRGB(48, 238, 255)
ResetButton.TextSize = 35.000
ResetButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid.Health = 0
end)
 
UICorner_65.Parent = ResetButton
 
TextBox.Parent = FrozenHub
TextBox.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
TextBox.BorderColor3 = Color3.fromRGB(65, 65, 65)
TextBox.Position = UDim2.new(0.214285702, 0, 0.171428561, 0)
TextBox.Size = UDim2.new(0, 86, 0, 35)
TextBox.Font = Enum.Font.Cartoon
TextBox.Text = "FOV"
TextBox.TextColor3 = Color3.fromRGB(48, 238, 255)
TextBox.TextSize = 30.000
 
UICorner_66.Parent = TextBox
 
HeadLess.Name = "HeadLess"
HeadLess.Parent = FrozenHub
HeadLess.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
HeadLess.BorderColor3 = Color3.fromRGB(65, 65, 65)
HeadLess.Position = UDim2.new(0.214285716, 0, 0.339285672, 0)
HeadLess.Size = UDim2.new(0, 86, 0, 32)
HeadLess.Font = Enum.Font.Cartoon
HeadLess.Text = "HeadLess"
HeadLess.TextColor3 = Color3.fromRGB(48, 238, 255)
HeadLess.TextSize = 21.000
HeadLess.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.Head.Transparency = 1
	for i,v in pairs(game.Players.LocalPlayer.Character.Head:GetChildren()) do
		if (v:IsA("Decal")) then
			v:Destroy()
		end
	end
end)
 
 
UICorner_67.Parent = HeadLess
 
EspButton.Name = "EspButton"
EspButton.Parent = FrozenHub
EspButton.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
EspButton.BorderColor3 = Color3.fromRGB(65, 65, 65)
EspButton.Position = UDim2.new(0.214285716, 0, 0.510714293, 0)
EspButton.Size = UDim2.new(0, 86, 0, 32)
EspButton.Font = Enum.Font.Cartoon
EspButton.Text = "ESP"
EspButton.TextColor3 = Color3.fromRGB(48, 238, 255)
EspButton.TextSize = 35.000
EspButton.MouseButton1Click:Connect(function()
	local esp_settings = { ---- table for esp settings 
		textsize = 8,
		colour = 255,255,255
	}
 
	local gui = Instance.new("BillboardGui")
	local esp = Instance.new("TextLabel",gui) ---- new instances to make the billboard gui and the textlabel
 
 
 
	gui.Name = "Cracked esp"; ---- properties of the esp
	gui.ResetOnSpawn = false
	gui.AlwaysOnTop = true;
	gui.LightInfluence = 0;
	gui.Size = UDim2.new(1.75, 0, 1.75, 0);
	esp.BackgroundColor3 = Color3.fromRGB(255, 255, 255);
	esp.Text = ""
	esp.Size = UDim2.new(0.0001, 0.00001, 0.0001, 0.00001);
	esp.BorderSizePixel = 4;
	esp.BorderColor3 = Color3.new(esp_settings.colour)
	esp.BorderSizePixel = 0
	esp.Font = "GothamSemibold"
	esp.TextSize = esp_settings.textsize
	esp.TextColor3 = Color3.fromRGB(esp_settings.colour) -- text colour
 
	game:GetService("RunService").RenderStepped:Connect(function() ---- loops faster than a while loop :)
		for i,v in pairs (game:GetService("Players"):GetPlayers()) do
			if v ~= game:GetService("Players").LocalPlayer and v.Character.Head:FindFirstChild("Cracked esp")==nil  then -- craeting checks for team check, local player etc
				esp.Text = "{"..v.Name.."}"
				gui:Clone().Parent = v.Character.Head
			end
		end
	end)
end)
 
UICorner_68.Parent = EspButton
 
SkyDiveButton.Name = "SkyDiveButton"
SkyDiveButton.Parent = FrozenHub
SkyDiveButton.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
SkyDiveButton.BorderColor3 = Color3.fromRGB(65, 65, 65)
SkyDiveButton.Position = UDim2.new(0.214285716, 0, 0.692857146, 0)
SkyDiveButton.Size = UDim2.new(0, 86, 0, 32)
SkyDiveButton.Font = Enum.Font.Cartoon
SkyDiveButton.Text = "SkyDive"
SkyDiveButton.TextColor3 = Color3.fromRGB(48, 238, 255)
SkyDiveButton.TextSize = 25.000
SkyDiveButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-366.669159, 569.630188, -166.57576, 0.974489331, -0.0169809274, 0.223790482, -1.0203725e-08, 0.997133553, 0.0756612271, -0.22443381, -0.0737310573, 0.971696019)
end)
 
 
UICorner_69.Parent = SkyDiveButton
 
SafePlaceButton.Name = "SafePlaceButton"
SafePlaceButton.Parent = FrozenHub
SafePlaceButton.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
SafePlaceButton.BorderColor3 = Color3.fromRGB(65, 65, 65)
SafePlaceButton.Position = UDim2.new(0.214285716, 0, 0.853571415, 0)
SafePlaceButton.Size = UDim2.new(0, 86, 0, 32)
SafePlaceButton.Font = Enum.Font.Cartoon
SafePlaceButton.Text = "Safe Place "
SafePlaceButton.TextColor3 = Color3.fromRGB(48, 238, 255)
SafePlaceButton.TextSize = 15.000
SafePlaceButton.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-219.180573, -27.256979, 248.523193, -0.999738038, 3.16151016e-09, 0.0228867289, 2.5122e-09, 1, -2.83993415e-08, -0.0228867289, -2.83344068e-08, -0.999738038)
end)
 
UICorner_70.Parent = SafePlaceButton
 
LoadVButton.Name = "LoadVButton"
LoadVButton.Parent = FrozenHub
LoadVButton.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
LoadVButton.BorderColor3 = Color3.fromRGB(65, 65, 65)
LoadVButton.Position = UDim2.new(0.413865566, 0, 0.171428546, 0)
LoadVButton.Size = UDim2.new(0, 86, 0, 32)
LoadVButton.Font = Enum.Font.Cartoon
LoadVButton.Text = "Load Older Version"
LoadVButton.TextColor3 = Color3.fromRGB(48, 238, 255)
LoadVButton.TextSize = 10.000
 
UICorner_71.Parent = LoadVButton
-- Scripts:
 
local function LQTK_fake_script() -- CloseButton.LocalScript 
	local script = Instance.new('LocalScript', CloseButton)
 
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false 
	end)
 
end
coroutine.wrap(LQTK_fake_script)()
local function TLPN_fake_script() -- TextBox.LocalScript 
	local script = Instance.new('LocalScript', TextBox)
 
	local Box = script.Parent
 
	Box.MouseEnter:Connect(function()
 
		if Box.Text == '30' then
			game.Workspace.CurrentCamera.FieldOfView = 30
		end
 
	end)
 
	Box.MouseEnter:Connect(function()
 
		if Box.Text == '60' then
			game.Workspace.CurrentCamera.FieldOfView = 60
		end
 
	end)
 
	Box.MouseEnter:Connect(function()
 
		if Box.Text == '90' then
			game.Workspace.CurrentCamera.FieldOfView = 90
		end
 
	end)
 
	Box.MouseEnter:Connect(function()
 
		if Box.Text == '120' then
			game.Workspace.CurrentCamera.FieldOfView = 120
		end
 
	end)
 
	Box.MouseEnter:Connect(function()
 
		if Box.Text == '150' then
			game.Workspace.CurrentCamera.FieldOfView = 150
		end
 
	end)
 
	Box.MouseEnter:Connect(function()
 
		if Box.Text == '200' then
			game.Workspace.CurrentCamera.FieldOfView = 200
		end
 
	end)
 
 
end
coroutine.wrap(TLPN_fake_script)()
