
function CheckQuest()
    local Lv = game:GetService("Players").LocalPlayer.Data.Level.Value
    if Lv == 1 or Lv <= 9 then
        Mon = "Bandit [Lv. 5]"
        NameMon = "Bandit"
        LvQuest = 1
        NameQuest = "BanditQuest1"
        CFrameMon = CFrame.new(1038.2711181640625, 24.537282943725586, 1550.2586669921875)
        CFrameQuest = CFrame.new(1059.8109130859375, 16.362747192382812, 1549.0882568359375)
    elseif Lv == 10 or Lv <= 14 then
        Mon = "Monkey [Lv. 14]"
        NameMon = "Monkey"
        LvQuest = 1
        NameQuest = "JungleQuest"
        CFrameMon = CFrame.new(-1443.7662353515625, 61.851966857910156, -47.555946350097656)
        CFrameQuest = CFrame.new(-1599.8194580078125, 36.852149963378906, 153.0706024169922)
        elseif Lv == 15 or Lv <= 29 then
        Mon = "Gorilla [Lv. 20]"
        NameMon = "Gorilla"
        LvQuest = 2
        NameQuest = "JungleQuest"
        CFrameMon = CFrame.new(-1443.7662353515625, 61.851966857910156, -47.555946350097656)
        CFrameQuest = CFrame.new(-1599.8194580078125, 36.852149963378906, 153.0706024169922) 
     end
 end
 
     
 
 local EzenHub = Instance.new("ScreenGui")
 local Frame = Instance.new("Frame")
 local UICorner = Instance.new("UICorner")
 local Key = Instance.new("TextBox")
 local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
 local UITextSizeConstraint = Instance.new("UITextSizeConstraint")
 local TextButton = Instance.new("TextButton")
 local UICorner_2 = Instance.new("UICorner")
 local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
 local UITextSizeConstraint_2 = Instance.new("UITextSizeConstraint")
 local Logo = Instance.new("ImageLabel")
 local UIAspectRatioConstraint_3 = Instance.new("UIAspectRatioConstraint")
 local tex = Instance.new("TextLabel")
 local UIAspectRatioConstraint_4 = Instance.new("UIAspectRatioConstraint")
 local UITextSizeConstraint_3 = Instance.new("UITextSizeConstraint")
 local about = Instance.new("TextLabel")
 local UIAspectRatioConstraint_5 = Instance.new("UIAspectRatioConstraint")
 local UITextSizeConstraint_4 = Instance.new("UITextSizeConstraint")
 local buy = Instance.new("TextButton")
 local UIAspectRatioConstraint_6 = Instance.new("UIAspectRatioConstraint")
 local UITextSizeConstraint_5 = Instance.new("UITextSizeConstraint")
 local UIAspectRatioConstraint_7 = Instance.new("UIAspectRatioConstraint")
 local BG2 = Instance.new("Frame")
 local UICorner_3 = Instance.new("UICorner")
 local Frame_2 = Instance.new("Frame")
 local UICorner_4 = Instance.new("UICorner")
 local TextLabel = Instance.new("TextLabel")
 local UIAspectRatioConstraint_8 = Instance.new("UIAspectRatioConstraint")
 local UITextSizeConstraint_6 = Instance.new("UITextSizeConstraint")
 local UIAspectRatioConstraint_9 = Instance.new("UIAspectRatioConstraint")
 local Toggle = Instance.new("TextButton")
 local UICorner_5 = Instance.new("UICorner")
 local UIAspectRatioConstraint_10 = Instance.new("UIAspectRatioConstraint")
 local TextLabel_2 = Instance.new("TextLabel")
 local UIAspectRatioConstraint_11 = Instance.new("UIAspectRatioConstraint")
 local UITextSizeConstraint_7 = Instance.new("UITextSizeConstraint")
 local UIAspectRatioConstraint_12 = Instance.new("UIAspectRatioConstraint")
 local Togle2 = Instance.new("TextButton")
 local UICorner_6 = Instance.new("UICorner")
 local UIAspectRatioConstraint_13 = Instance.new("UIAspectRatioConstraint")
 local UITextSizeConstraint_8 = Instance.new("UITextSizeConstraint")
 
 --Properties:
 
 EzenHub.Name = "EzenHub"
 EzenHub.Parent = game.CoreGui
 EzenHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
 
 Frame.Parent = EzenHub
 Frame.BackgroundColor3 = Color3.fromRGB(67, 67, 67)
 Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
 Frame.BorderSizePixel = 0
 Frame.Position = UDim2.new(0.35891813, 0, 0.298543692, 0)
 Frame.Size = UDim2.new(0.281432748, 0, 0.402912617, 0)
 
 UICorner.Parent = Frame
 
 Key.Name = "Key"
 Key.Parent = Frame
 Key.BackgroundColor3 = Color3.fromRGB(100, 100, 100)
 Key.BorderColor3 = Color3.fromRGB(0, 0, 0)
 Key.BorderSizePixel = 0
 Key.Position = UDim2.new(0.0467532463, 0, 0.620481908, 0)
 Key.Size = UDim2.new(0.906493485, 0, 0.102409638, 0)
 Key.Font = Enum.Font.SourceSansBold
 Key.PlaceholderText = "Key"
 Key.Text = ""
 Key.TextColor3 = Color3.fromRGB(255, 255, 255)
 Key.TextScaled = true
 Key.TextSize = 14.000
 Key.TextWrapped = true
 
 UIAspectRatioConstraint.Parent = Key
 UIAspectRatioConstraint.AspectRatio = 10.265
 
 UITextSizeConstraint.Parent = Key
 UITextSizeConstraint.MaxTextSize = 34
 
 TextButton.Parent = Frame
 TextButton.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
 TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
 TextButton.BorderSizePixel = 0
 TextButton.Position = UDim2.new(0.241558447, 0, 0.762048185, 0)
 TextButton.Size = UDim2.new(0.519480526, 0, 0.150602415, 0)
 TextButton.Font = Enum.Font.Unknown
 TextButton.Text = "Submit"
 TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
 TextButton.TextScaled = true
 TextButton.TextSize = 14.000
 TextButton.TextWrapped = true
 
 UICorner_2.Parent = TextButton
 
 UIAspectRatioConstraint_2.Parent = TextButton
 UIAspectRatioConstraint_2.AspectRatio = 4.000
 
 UITextSizeConstraint_2.Parent = TextButton
 UITextSizeConstraint_2.MaxTextSize = 50
 
 Logo.Name = "Logo"
 Logo.Parent = Frame
 Logo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
 Logo.BorderColor3 = Color3.fromRGB(0, 0, 0)
 Logo.BorderSizePixel = 0
 Logo.Position = UDim2.new(0.368831158, 0, 0.105421685, 0)
 Logo.Size = UDim2.new(0.259740263, 0, 0.30120483, 0)
 Logo.Image = "rbxassetid://15821421084"
 
 UIAspectRatioConstraint_3.Parent = Logo
 
 tex.Name = "tex"
 tex.Parent = Frame
 tex.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
 tex.BackgroundTransparency = 1.000
 tex.BorderColor3 = Color3.fromRGB(0, 0, 0)
 tex.BorderSizePixel = 0
 tex.Position = UDim2.new(0.241558447, 0, 0.512048185, 0)
 tex.Size = UDim2.new(0.519480526, 0, 0.0662650615, 0)
 tex.Font = Enum.Font.SourceSansBold
 tex.Text = "How to Get Key?"
 tex.TextColor3 = Color3.fromRGB(255, 255, 255)
 tex.TextScaled = true
 tex.TextSize = 26.000
 tex.TextWrapped = true
 
 UIAspectRatioConstraint_4.Parent = tex
 UIAspectRatioConstraint_4.AspectRatio = 9.091
 
 UITextSizeConstraint_3.Parent = tex
 UITextSizeConstraint_3.MaxTextSize = 26
 
 about.Name = "about"
 about.Parent = Frame
 about.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
 about.BackgroundTransparency = 1.000
 about.BorderColor3 = Color3.fromRGB(0, 0, 0)
 about.BorderSizePixel = 0
 about.Position = UDim2.new(-0.207792208, 0, -0.4246988, 0)
 about.Size = UDim2.new(1.41558444, 0, 0.150602415, 0)
 about.Font = Enum.Font.SourceSansBold
 about.Text = "Buy Key in Discord ..."
 about.TextColor3 = Color3.fromRGB(255, 8, 0)
 about.TextScaled = true
 about.TextSize = 14.000
 about.TextWrapped = true
 
 UIAspectRatioConstraint_5.Parent = about
 UIAspectRatioConstraint_5.AspectRatio = 10.900
 
 UITextSizeConstraint_4.Parent = about
 UITextSizeConstraint_4.MaxTextSize = 50
 
 buy.Name = "buy"
 buy.Parent = Frame
 buy.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
 buy.BackgroundTransparency = 1.000
 buy.BorderColor3 = Color3.fromRGB(0, 0, 0)
 buy.BorderSizePixel = 0
 buy.Position = UDim2.new(0.259740263, 0, 0.512048185, 0)
 buy.Size = UDim2.new(0.519480526, 0, 0.0662650615, 0)
 buy.Font = Enum.Font.SourceSans
 buy.Text = ""
 buy.TextColor3 = Color3.fromRGB(0, 0, 0)
 buy.TextScaled = true
 buy.TextSize = 14.000
 buy.TextWrapped = true
 
 UIAspectRatioConstraint_6.Parent = buy
 UIAspectRatioConstraint_6.AspectRatio = 9.091
 
 UITextSizeConstraint_5.Parent = buy
 UITextSizeConstraint_5.MaxTextSize = 14
 
 UIAspectRatioConstraint_7.Parent = Frame
 UIAspectRatioConstraint_7.AspectRatio = 1.160
 
 BG2.Name = "BG2"
 BG2.Parent = EzenHub
 BG2.BackgroundColor3 = Color3.fromRGB(76, 76, 76)
 BG2.BorderColor3 = Color3.fromRGB(0, 0, 0)
 BG2.BorderSizePixel = 0
 BG2.Position = UDim2.new(0.329678267, 0, 0.354368925, 0)
 BG2.Size = UDim2.new(0.339912295, 0, 0.395631075, 0)
 BG2.Visible = false
 
 UICorner_3.Parent = BG2
 
 Frame_2.Parent = BG2
 Frame_2.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
 Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
 Frame_2.BorderSizePixel = 0
 Frame_2.Size = UDim2.new(0.99999994, 0, 0.30674848, 0)
 
 UICorner_4.Parent = Frame_2
 
 TextLabel.Parent = Frame_2
 TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
 TextLabel.BackgroundTransparency = 1.000
 TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
 TextLabel.BorderSizePixel = 0
 TextLabel.Position = UDim2.new(0.0215053763, 0, 0.109999999, 0)
 TextLabel.Size = UDim2.new(0.959139764, 0, 0.800000012, 0)
 TextLabel.Font = Enum.Font.Unknown
 TextLabel.Text = "Ezen Hub"
 TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
 TextLabel.TextScaled = true
 TextLabel.TextSize = 14.000
 TextLabel.TextWrapped = true
 
 UIAspectRatioConstraint_8.Parent = TextLabel
 UIAspectRatioConstraint_8.AspectRatio = 5.575
 
 UITextSizeConstraint_6.Parent = TextLabel
 UITextSizeConstraint_6.MaxTextSize = 80
 
 UIAspectRatioConstraint_9.Parent = Frame_2
 UIAspectRatioConstraint_9.AspectRatio = 4.650
 
 Toggle.Name = "Toggle"
 Toggle.Parent = BG2
 Toggle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
 Toggle.BorderColor3 = Color3.fromRGB(0, 0, 0)
 Toggle.BorderSizePixel = 0
 Toggle.Position = UDim2.new(0.0215053763, 0, 0.564417183, 0)
 Toggle.Size = UDim2.new(0.959139705, 0, 0.15337424, 0)
 Toggle.Font = Enum.Font.SourceSansBold
 Toggle.Text = ""
 Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
 Toggle.TextSize = 14.000
 
 UICorner_5.Parent = Toggle
 
 UIAspectRatioConstraint_10.Parent = Toggle
 UIAspectRatioConstraint_10.AspectRatio = 8.920
 
 TextLabel_2.Parent = BG2
 TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
 TextLabel_2.BackgroundTransparency = 1.000
 TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
 TextLabel_2.BorderSizePixel = 0
 TextLabel_2.Position = UDim2.new(0.0344086029, 0, 0.37730062, 0)
 TextLabel_2.Size = UDim2.new(0.946236491, 0, 0.15337424, 0)
 TextLabel_2.Font = Enum.Font.SourceSansBold
 TextLabel_2.Text = "Kaitan Mode"
 TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
 TextLabel_2.TextScaled = true
 TextLabel_2.TextSize = 14.000
 TextLabel_2.TextWrapped = true
 
 UIAspectRatioConstraint_11.Parent = TextLabel_2
 UIAspectRatioConstraint_11.AspectRatio = 8.800
 
 UITextSizeConstraint_7.Parent = TextLabel_2
 UITextSizeConstraint_7.MaxTextSize = 50
 
 UIAspectRatioConstraint_12.Parent = BG2
 UIAspectRatioConstraint_12.AspectRatio = 1.426
 
 Togle2.Name = "Togle2"
 Togle2.Parent = EzenHub
 Togle2.BackgroundColor3 = Color3.fromRGB(76, 76, 76)
 Togle2.BorderColor3 = Color3.fromRGB(0, 0, 0)
 Togle2.BorderSizePixel = 0
 Togle2.Position = UDim2.new(0.0343567245, 0, 0.503640771, 0)
 Togle2.Size = UDim2.new(0.0372807011, 0, 0.0606796108, 0)
 Togle2.Visible = false
 Togle2.Font = Enum.Font.SourceSans
 Togle2.Text = ""
 Togle2.TextColor3 = Color3.fromRGB(0, 0, 0)
 Togle2.TextScaled = true
 Togle2.TextSize = 14.000
 Togle2.TextWrapped = true
 
 UICorner_6.Parent = Togle2
 
 UIAspectRatioConstraint_13.Parent = Togle2
 UIAspectRatioConstraint_13.AspectRatio = 1.020
 
 UITextSizeConstraint_8.Parent = Togle2
 UITextSizeConstraint_8.MaxTextSize = 14
 
 -- Scripts:
 
 local function NPYTYSY_fake_script() -- TextButton.LocalScript 
     local script = Instance.new('LocalScript', TextButton)
 
     -- กำหนด Key เป็น Table
     local Key = {
         EzenKey11294 = true,
         EzenKeyASc3asdij89 = true,
         EzenKeyASdc124 = true,
         EzenKeyIcOo1042199 = true,
         Admin = true
     }
     
     -- ตั้งค่า MouseButton1Click event
     script.Parent.MouseButton1Click:Connect(function()
         -- หา TextBox ที่ชื่อ "Key" ใน Parent
         local textBox = script.Parent.Parent:FindFirstChild("Key")
     
         -- ตรวจสอบว่า textBox มีค่าหรือไม่
         if textBox then
             local inputCode = textBox.Text
     
             -- ตรวจสอบว่า inputCode ตรงกับ Key หรือไม่
             if Key[inputCode] then
                 textBox.PlaceholderText = "Suscess!"
                 script.Parent.Parent.Parent.Frame.Visible = false
                 wait(2)
                 script.Parent.Parent.Parent.BG2.Visible = true
                 script.Parent.Parent.Parent.Togle2.Visible = true
             else
                 textBox.PlaceholderText = "Error ไม่พบ Key!"
             end
         else
             textBox.PlaceholderText = "Error โปรดติดต่อ Support!"
         end
     end)
     
 end
 coroutine.wrap(NPYTYSY_fake_script)()
 local function EGXMHX_fake_script() -- buy.LocalScript 
     local script = Instance.new('LocalScript', buy)
 
     local about = script.Parent.Parent.about
     
     
     about.Visible = false
     local button = script.Parent
     
     button.MouseButton1Click:Connect(function()
         about.Visible = true
         wait(2)
         about.Visible = false
     end)
 end
 coroutine.wrap(EGXMHX_fake_script)()
 local function WNLE_fake_script() -- Toggle.LocalScript 
     local script = Instance.new('LocalScript', Toggle)
 
     local st = false
     
     script.Parent.BackgroundColor3 = Color3.fromHSV(0, 1, 1)
     
     
     script.Parent.MouseButton1Click:Connect(function()
         if st == false then
             _G.Farm = true
                         --_G.FastAttack = true
                         --_G.BringMob = true
             game.Players.LocalPlayer.Character:WaitForChild("Humanoid").WalkSpeed = 200
             script.Parent.BackgroundColor3 = Color3.fromHSV(0.353, 0.924178, 0.827451)
             st = true
         elseif st == true then
             game.Players.LocalPlayer.Character:WaitForChild("Humanoid").WalkSpeed = 16
             _G.Farm = false
                         --_G.FastAttack = false
                         --_G.BringMob = false
             script.Parent.BackgroundColor3 = Color3.fromHSV(0, 1, 1)
             st = false
         end
     end)
 end
 coroutine.wrap(WNLE_fake_script)()
 local function SZAYSZ_fake_script() -- Togle2.LocalScript 
     local script = Instance.new('LocalScript', Togle2)
 
     script.Parent.MouseButton1Click:Connect(function()
         if script.Parent.Parent.BG2.Visible == false then
             script.Parent.Parent.BG2.Visible = true
         elseif script.Parent.Parent.BG2.Visible == true then
             script.Parent.Parent.BG2.Visible = false
         end
     end)
 end
 coroutine.wrap(SZAYSZ_fake_script)()
 
 
 spawn(function()
    while wait() do
        if _G.BringMob then
            pcall(function()
            CheckQuest()
       for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
for x,y in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
if v.Name == Mon then
    if y.Name == Mon then
   v.HumanoidRootPart.CFrame = y.HumanoidRootPart.CFrame
   v.HumanoidRootPart.Size = Vector3.new(60,60,60)
   y.HumanoidRootPart.Size = Vector3.new(60,60,60)
   v.HumanoidRootPart.Transparency = 1
   v.HumanoidRootPart.CanCollide = false
   y.HumanoidRootPart.CanCollide = false
   v.Humanoid.WalkSpeed = 0
   y.Humanoid.WalkSpeed = 0
   v.Humanoid.JumpPower = 0
   y.Humanoid.JumpPower = 0
   if sethiddenproperty then
     sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
end
end
end
end
end
end)
end
end
end)


spawn(function()
    while wait() do
        if _G.AutoFarm then
            pcall(function()
            CheckQuest()
    if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
    TP(CFrameQuest)
    if (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 5 then
    wait(.1)
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest",NameQuest,LvQuest)
    end
    elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
        if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text,NameMon) then
            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                if v.Name == Mon and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid")   then
                    if v.Humanoid.Health > 0 then
                    repeat wait()
                        click()
                        Equip(_G.SelectWeapon)
                        HealthMin = v.Humanoid.MaxHealth * 90 / 100
                        Magma = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
                        if Magma <= 230 then
                            if v.Humanoid.Health > HealthMin then
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,0,14)
                                else
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,15,0)
                            end
                        end
                            if v.Humanoid.Health > HealthMin then
                        Distance = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude 
                        Speed = 300 
                        tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
                        tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,0,14)})
                        tween:Play() 
                        else
                        Distance = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude 
                        Speed = 300 
                        tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
                        tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,15,0)})
                        tween:Play()
                            end
                        v.HumanoidRootPart.Size = Vector3.new(60,60,60)
                        v.HumanoidRootPart.CanCaillde = false
                    until _G.AutoFarm == false or v.Humanoid.Health <= 0
                    else
                        TP(CFrameMon)
                    end
                    if not string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text,NameMon) then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                    end
                    if game.Players.LocalPlayer.Character.Humanoid.Health <= 0 then
                        _G.AutoFarm = false
                        wait(3)
                        _G.AutoFarm = true
                        end
                end
                end
        end
        end
       end)
end
end
end)


spawn(function()
    game:GetService("RunService").Heartbeat:Connect(function()
        if _G.AutoFarm then
        if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") then
            setfflag("HumanoidParallelRemoveNoPhysics", "False")
            setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
            game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
            end
        end
    end)
end)


 
 function Equip(Tool)
    if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(ToolX) then
        getgenv().Tol = game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(ToolX)
        game.Players.LocalPlayer.Character.Humanoid:EquipTool(Tol)
end
end

while true do wait(.1)
    pcall(function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Melee",Point)
    end)
    end

