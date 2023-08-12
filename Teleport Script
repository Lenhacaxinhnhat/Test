local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()
local Window = Rayfield:CreateWindow({
    Name = "Tutorial Hub | Teleport Blox Fruit",
    LoadingTitle = "Blox Fruits | Script Teleport",
    LoadingSubtitle = "by Arik",
    ConfigurationSaving = {
       Enabled = true,
       FolderName = nil, -- Create a custom folder for your hub/game
       FileName = "Big Hub"
    },
    Discord = {
       Enabled = true,
       Invite = "https://discord.gg/3acWjThz", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
       RememberJoins = true -- Set this to false to make them join the discord every time they load it up
    },
    KeySystem = true, -- Set this to true to use our key system
    KeySettings = {
       Title = "Script Teleport | Blox Fruit",
       Subtitle = "Key System",
       Note = "How To Get Key : | Discord Tutorial Hub : tvdFyKw3",
       FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
       SaveKey = false, -- The user's key will be saved, but if you change the key, they will be unable to use your script
       GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
       Key = {"Hello"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
    }
 })

 local InfoTab = Window:CreateTab("Home", 4483362458) -- Title, Image
 local Section = InfoTab:CreateSection("Infomation")
 local Input = InfoTab:CreateInput({
    Name = "Script By : ",
    PlaceholderText = "Arik",
    RemoveTextAfterFocusLost = false,
    Callback = function(Text)
    -- The function that takes place when the input is changed
    -- The variable (Text) is a string for the value in the text box
    end,
 })
 local Input = InfoTab:CreateInput({
    Name = "Script Update : ",
    PlaceholderText = "1",
    RemoveTextAfterFocusLost = false,
    Callback = function(Text)
    -- The function that takes place when the input is changed
    -- The variable (Text) is a string for the value in the text box
    end,
 })
 local Section = InfoTab:CreateSection("Update Day")
 local Input = InfoTab:CreateInput({
    Name = "Update Day : ",
    PlaceholderText = "Soon",
    RemoveTextAfterFocusLost = false,
    Callback = function(Text)
    -- The function that takes place when the input is changed
    -- The variable (Text) is a string for the value in the text box
    end,
 })
 local Input = InfoTab:CreateInput({
    Name = "Update New : ",
    PlaceholderText = "Auto Fram,Auto Raid,Auto Chest,...",
    RemoveTextAfterFocusLost = false,
    Callback = function(Text)
    -- The function that takes place when the input is changed
    -- The variable (Text) is a string for the value in the text box
    end,
 })
 local Section = InfoTab:CreateSection("Update Script")
 local Input = InfoTab:CreateInput({
    Name = "Kaitun : ",
    PlaceholderText = "Auto Fram All",
    RemoveTextAfterFocusLost = false,
    Callback = function(Text)
    -- The function that takes place when the input is changed
    -- The variable (Text) is a string for the value in the text box
    end,
 })
 local Input = InfoTab:CreateInput({
    Name = "Bounty Fram : ",
    PlaceholderText = "Auto Fram Bounty/Honor",
    RemoveTextAfterFocusLost = false,
    Callback = function(Text)
    -- The function that takes place when the input is changed
    -- The variable (Text) is a string for the value in the text box
    end,
 })
 local Input = InfoTab:CreateInput({
    Name = "Main Rewrite : ",
    PlaceholderText = "Auto Fram",
    RemoveTextAfterFocusLost = false,
    Callback = function(Text)
    -- The function that takes place when the input is changed
    -- The variable (Text) is a string for the value in the text box
    end,
 })
 local Input = InfoTab:CreateInput({
    Name = "Showcase  : ",
    PlaceholderText = "Showcase Item",
    RemoveTextAfterFocusLost = false,
    Callback = function(Text)
    -- The function that takes place when the input is changed
    -- The variable (Text) is a string for the value in the text box
    end,
 })
 local Input = InfoTab:CreateInput({
    Name = "Misc : ",
    PlaceholderText = "Auto Trial,Auto Race,...",
    RemoveTextAfterFocusLost = false,
    Callback = function(Text)
    -- The function that takes place when the input is changed
    -- The variable (Text) is a string for the value in the text box
    end,
 })
 local Input = InfoTab:CreateInput({
    Name = "Pvp : ",
    PlaceholderText = "Pvp",
    RemoveTextAfterFocusLost = false,
    Callback = function(Text)
    -- The function that takes place when the input is changed
    -- The variable (Text) is a string for the value in the text box
    end,
 })

 local MainTab = Window:CreateTab("Teleport Map", 4483362458) -- Title, Image
 local Section = MainTab:CreateSection("Sea")
 local Dropdown = MainTab:CreateDropdown({
    Name = "Choses Sea",
    Options = {"Sea 1","Sea 2","Sea 3"},
    CurrentOption = {"Sea 1"},
    MultipleOptions = false,
    Flag = "Dropdown1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
    Callback = function(Option)
    -- The function that takes place when the selected option is changed
    -- The variable (Option) is a table of strings for the current selected options
    end,
 })
 local Button = MainTab:CreateButton({
    Name = "Teleport",
    Callback = function()
    -- The function that takes place when the button is pressed
    end,
 })
 local Section = MainTab:CreateSection("Sea 1")
 local Dropdown = MainTab:CreateDropdown({
    Name = "Choses Map",
    Options = {"Starter Pirate Island","Starter Marine Island","Jungle","Pirate Village","Desert","Middle Island","Frozen Village","Marine Fortress","Skylands","Prison","Colosseum","Magma Village","Underwater City","Fountain City"},
    CurrentOption = {"Starter Pirate Island"},
    MultipleOptions = false,
    Flag = "Dropdown1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
    Callback = function(Option)
    -- The function that takes place when the selected option is changed
    -- The variable (Option) is a table of strings for the current selected options
    end,
 })
 local Button = MainTab:CreateButton({
    Name = "Teleport",
    Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7753.17676, 5562.67822, -446.663971, -0.220987827, -0, -0.97527653, -0, 1, -0, 0.975276649, 0, -0.220987797)
    -- The function that takes place when the button is pressed
    end,
 })
 local Section = MainTab:CreateSection("Sea 2")
 local Dropdown = MainTab:CreateDropdown({
    Name = "Choses Map",
    Options = {"Kingdom of Rose","Usoap’s Island","Cafe","Don Swan's Mansion","Green Zone","Graveyard Island","Snow Mountain","Hot and Cold","Cursed Ship","Ice Castle","Forgotten Island","Dark Arena"},
    CurrentOption = {"Kingdom of Rose"},
    MultipleOptions = false,
    Flag = "Dropdown1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
    Callback = function(Option)
    -- The function that takes place when the selected option is changed
    -- The variable (Option) is a table of strings for the current selected options
    end,
 })
 local Button = MainTab:CreateButton({
    Name = "Teleport",
    Callback = function()
    -- The function that takes place when the button is pressed
    end,
 })
 local Section = MainTab:CreateSection("Sea 3")
 local Dropdown = MainTab:CreateDropdown({
    Name = "Choses Map",
    Options = {"Port Town","Hydra Island","Floating Turtle","Castle on the Sea","Haunted Castle","Sea of Treats"},
    CurrentOption = {"Port Town"},
    MultipleOptions = false,
    Flag = "Dropdown1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
    Callback = function(Option)
    -- The function that takes place when the selected option is changed
    -- The variable (Option) is a table of strings for the current selected options
    end,
 })
 local Button = MainTab:CreateButton({
    Name = "Teleport",
    Callback = function()
    -- The function that takes place when the button is pressed
    end,
 })

 local OtherTab = Window:CreateTab("Local Player", 4483362458) -- Title, Image
 local Section = OtherTab:CreateSection("Movement")
 local Slider = OtherTab:CreateSlider({
    Name = "WalkSpeed",
    Range = {100, 500},
    Increment = 10,
    Suffix = "WS",
    CurrentValue = 10,
    Flag = "Slider1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
    Callback = function(Value)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value
    -- The function that takes place when the slider changes
    -- The variable (Value) is a number which correlates to the value the slider is currently at
    end,
 })
 local Slider = OtherTab:CreateSlider({
    Name = "JumpPower",
    Range = {100, 500},
    Increment = 10,
    Suffix = "JP",
    CurrentValue = 10,
    Flag = "Slider1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
    Callback = function(Value)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = Value
    -- The function that takes place when the slider changes
    -- The variable (Value) is a number which correlates to the value the slider is currently at
    end,
 })
 local Section = OtherTab:CreateSection("Others")
 local Section = OtherTab:CreateSection("Can't Turn Off Anti AFK")
 local Button = OtherTab:CreateButton({
    Name = "Anti AFK",
    Callback = function()
        while wait() do
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7753.17676, 5562.67822, -446.663971, -0.220987827, -0, -0.97527653, -0, 1, -0, 0.975276649, 0, -0.220987797)
            end
    -- The function that takes place when the button is pressed
    end,
 })
 local Toggle = OtherTab:CreateToggle({
    Name = "Hop Sever",
    CurrentValue = false,
    Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
    Callback = function(Value)
        local module = loadstring(game:HttpGet"https://raw.githubusercontent.com/LeoKholYt/roblox/main/lk_serverhop.lua")()

module:Teleport(game.PlaceId)
    -- The function that takes place when the toggle is pressed
    -- The variable (Value) is a boolean on whether the toggle is true or false
    end,
 })
 local Section = OtherTab:CreateSection("Fruit")
 local Toggle = OtherTab:CreateToggle({
    Name = "Random Fruit",
    CurrentValue = false,
    Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
    Callback = function(Value)
    -- The function that takes place when the toggle is pressed
    -- The variable (Value) is a boolean on whether the toggle is true or false
    end,
 })
 local Toggle = OtherTab:CreateToggle({
    Name = "Auto Fruit And Hop Sever",
    CurrentValue = false,
    Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
    Callback = function(Value)
        if not game:IsLoaded() then
            game.Loaded:Wait()
        end
        repeat
            task.wait()
        until game:GetService("Players") and game:GetService("Workspace") and game:GetService("ReplicatedStorage")
        
        local LocalPlayer = game:GetService("Players").LocalPlayer
        loadstring(game:HttpGet("https://pastebin.com/raw/tUUGAeaH", true))()
        
        local function returnHRP()
            if not LocalPlayer.Character then
                return
            end
            if not LocalPlayer.Character:FindFirstChild("HumanoidRootPart") then
                return
            else
                return LocalPlayer.Character:FindFirstChild("HumanoidRootPart")
            end
        end
        local function returnHUM()
            if not LocalPlayer.Character then
                return
            end
            if not LocalPlayer.Character:FindFirstChild("Humanoid") then
                return
            else
                return LocalPlayer.Character:FindFirstChild("Humanoid")
            end
        end
        repeat
            task.wait()
        until returnHRP() and returnHUM()
        local HrpTable = {
            Velocity = returnHRP().Velocity,
            Transparency = returnHRP().Transparency,
            Rotation = returnHRP().Rotation,
            Size = returnHRP().Size,
            Orientation = returnHRP().Orientation,
            Anchored = returnHRP().Anchored
        }
        
        local function spoofHRP()
            for i, v in pairs(HrpTable) do
                spoof(returnHRP(), tostring(i), returnHRP():GetAttribute(v))
            end
        
            return true
        end
        
        local function TpTo(CFrame, Refresh)
            if Refresh then
                returnHUM().Health = 0
                LocalPlayer.CharacterAdded:Wait()
                repeat
                    task.wait()
                until returnHRP() and returnHUM()
                spoofHRP()
                spoofHUM()
            else
                spoofHRP()
            end
        
            returnHRP().CFrame = CFrame
        
            return true
        end
        
        --Be nice and leave the credits in!
        for i=1,100 do
            print("Script made by noxu#2161\nMore scripts here: extorius.ezyro.com\nBe nice and leave the credits in!\n---------------------")
        end
        
        local Fruit_InServer = false
        local Fruits_InServer = {}
        local Fruit_InHand = nil
        
        for _,v in ipairs(workspace:GetChildren()) do
            if v:IsA("Tool") then
                Fruit_InServer = true
                table.insert(Fruits_InServer, v)
            end
        end
        
        if Fruit_InServer then
            repeat
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(table.unpack({    [1] = "SetTeam",    [2] = "Pirates",}))
                task.wait(.4)
            until LocalPlayer.Team == game:GetService("Teams")["Pirates"]
            
            for _,v in pairs(Fruits_InServer) do
                returnHRP().CFrame=v.Handle.CFrame
                task.wait(.1)
                Fruit_InHand = string.gsub(v.Name, " Fruit", "")
                Fruit_InHand = Fruit_InHand.."-"..Fruit_InHand
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(table.unpack({    [1] = "StoreFruit",    [2] = Fruit_InHand,    [3] = returnHRP().Parent:FindFirstChildOfClass("Tool"),}))
                task.wait(.1)
            end
            
            task.wait(.5)
            local module = loadstring(game:HttpGet"https://raw.githubusercontent.com/LeoKholYt/roblox/main/lk_serverhop.lua")()
            module:Teleport(game.PlaceId)
        else
            local module = loadstring(game:HttpGet"https://raw.githubusercontent.com/LeoKholYt/roblox/main/lk_serverhop.lua")()
            module:Teleport(game.PlaceId)
        end
    -- The function that takes place when the toggle is pressed
    -- The variable (Value) is a boolean on whether the toggle is true or false
    end,
 })
