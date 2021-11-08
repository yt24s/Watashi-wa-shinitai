                                             --[Made By yt製 X rauly製]--
                                                              
        local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/GreenDeno/Venyx-UI-Library/main/source.lua"))()
        local hub = library.new("Farmbot X Pauly", 5013109572)

        wait(1)
            game:GetService("StarterGui"):SetCore("SendNotification", {
            Title = "local farmbot#0001";
            Text = "shit loads rq huh";
        })

        wait(1)
            game:GetService("StarterGui"):SetCore("SendNotification", {
            Title = "raul22#4448";
            Text = "halal mode";
        })

        -- themes
        local themes = {
        Background = Color3.fromRGB(24, 24, 24),
        Glow = Color3.fromRGB(15, 255, 255),
        Accent = Color3.fromRGB(10, 180, 180),
        LightContrast = Color3.fromRGB(23, 146, 146),
        DarkContrast = Color3.fromRGB(14, 14, 14),  
        TextColor = Color3.fromRGB(255, 255, 255)
        }

        --main page
        local page = hub:addPage("Main", 5012544693)
        local main = page:addSection("Main")

      main:addToggle("No Slow", nil, function(aha)
    local NSLOW = aha
    if NSLOW then
    _G.NoSlow = true
    while _G.NoSlow do
        wait()
        local uis = game:GetService("UserInputService")
uis.InputBegan:connect(function(ip, gpe)
    if ip.KeyCode == Enum.KeyCode.ButtonX and not gpe then
        wait(0.1)
					local player = game.Players.LocalPlayer
					function FindNearest(position)
						local lowest = 50 -- infinity
						local NearestPlayer = nil
						for i, v in pairs(game.Players:GetPlayers()) do
							if v.Name ~= game.Players.LocalPlayer.Name then
								if v and v.Character then
									local distance = v:DistanceFromCharacter(position)
									if distance < lowest then
										lowest = distance
										NearestPlayer = v
									end
								end
							end
						end
						return NearestPlayer
					end
					target = FindNearest(game.Players.LocalPlayer.Character:WaitForChild("Head").Position);
					local man = game.Players.LocalPlayer.Character;
					local enemy = game.Players[target.Name].Character;
					man.PrimaryPart.CFrame = enemy.PrimaryPart.CFrame * CFrame.new(Vector3.new(0, 0, 3))
					game:GetService("Workspace").Camera.CFrame = enemy.PrimaryPart.CFrame
		end
end)
for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
    if v.Name == "Justice Combination" then
local action = game.Players.LocalPlayer.Character:WaitForChild("Action")
    if action then wait() action:Destroy() end end
    if v.Name == "Action" then
v:Destroy()
end
    if v.Name == "Attacking" then
v:Destroy()
end
    if v.Name == "Using" then
v:Destroy()
end
    if v.Name == "hyper" then
    v:Destroy()
    end
    if v.Name == "Hyper" then
    v:Destroy()
    end
    if v.Name == "heavy" then
    v:Destroy()
    end
    if v.Name == "KiBlasted" then
        v:Destroy()
        end
        if v.Name == "Tele" then
        v:Destroy()
        end
        if v.Name == "tele" then
        v:Destroy()
        end
        if v.Name == "Killed" then
            v:Destroy()
            end
            if v.Name == "Slow" then
            v:Destroy()
            end
if v.Name == "Block" and v.Value == true then
v.Value = false
end
end
end
else
    _G.NoSlow = false
end
end)

main:addSlider("Tele Speed", 0, 0, 2500, function(Tele)
down = false
velocity = Instance.new("BodyVelocity")
velocity.maxForce = Vector3.new(10000000, 0, 10000000)
local speed    = Tele
gyro           = Instance.new("BodyGyro")
gyro.maxTorque = Vector3.new(10000000, 0, 10000000)

local hum = game.Players.LocalPlayer.Character.Humanoid

function onButton1Down(mouse)
down = true
velocity.Parent = game.Players.LocalPlayer.Character.UpperTorso
velocity.velocity = (hum.MoveDirection) * speed
gyro.Parent = game.Players.LocalPlayer.Character.UpperTorso
while down do
if not down then break end
velocity.velocity = (hum.MoveDirection) * speed
local refpos = gyro.Parent.Position + (gyro.Parent.Position - workspace.CurrentCamera.CoordinateFrame.p).unit * 5
gyro.cframe = CFrame.new(gyro.Parent.Position, Vector3.new(refpos.x, gyro.Parent.Position.y, refpos.z))
wait(0.1)
end
end

function onButton1Up(mouse)
velocity.Parent = nil
gyro.Parent = nil
down = false
end
--To Change the key in those 2 lines, replace the "q" with your desired key
function onSelected(mouse)
mouse.KeyDown:connect(function(k) if k:lower()=="q"then onButton1Down(mouse)end end)
mouse.KeyUp:connect(function(k) if k:lower()=="q"then onButton1Up(mouse)end end)
end

onSelected(game.Players.LocalPlayer:GetMouse())
end)

main:addSlider("Custom Speed", 0, 0, 25000, function(CustomSpeed)
lmao = {CustomSpeed}
while wait() do
function setSpeed(walkspeedSet)
local plr = game:GetService"Players".LocalPlayer
local serverTraits = plr.Backpack:WaitForChild'ServerTraits'

for i,v in next, getconnections(serverTraits.Input.OnClientEvent) do
   local speed = ((walkspeedSet))
   v:Fire({speed})
   break
end 
end 
setSpeed(lmao[1])
end
end)

main:addToggle("Stay In Form", nil, function(StayinForm)
	if StayinForm == true then
		if game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("SaiyanAuraWeak") then
			game.Players.LocalPlayer.Character.HumanoidRootPart.SaiyanAuraWeak:Destroy()
		end

		if game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("MajinParticle") then
			game.Players.LocalPlayer.Character.HumanoidRootPart.MajinParticle:Destroy()
		end

		if game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Lightning2") then
			game.Players.LocalPlayer.Character.HumanoidRootPart.Lightning2:Destroy()
		end

		if game.Players.LocalPlayer.Character:FindFirstChild("SaiyanHair") then
			game.Players.LocalPlayer.Character.SaiyanHair:Destroy()
		end

		if game.Players.LocalPlayer.Character.Head:FindFirstChild("Tatoo") then
			game.Players.LocalPlayer.Character.Head.Tatoo:Destroy()
		end

		if game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("MajinAura") then
			game.Players.LocalPlayer.Character.HumanoidRootPart.MajinAura:Destroy()
		end

	else
		game.Players.LocalPlayer.Character.Humanoid.Health = 0
	end
end)

main:addToggle("Bean Spam", nil, function(BeanSpamT)
    if BeanSpamT == true then
        BeanSpamR = game:GetService("RunService").RenderStepped:connect(function()
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.EatSenzu:FireServer(true)
        end)
else
    BeanSpamR:Disconnect()
    end
end)

main:addDropdown("Slot Changer", {"Slot1","Slot2","Slot3"}, function(value)
    local A_1 = game:GetService("Workspace").FriendlyNPCs["Character Slot Changer"]
    local Event = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
    Event:FireServer(A_1)
    wait(0.3)
    local A_1 = 
    {
        [1] = "Yes"
    }
    local Event = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
    Event:FireServer(A_1)
    wait(0.3)
    local A_1 = 
    {
        [1] = "k"
    }
    local Event = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
    Event:FireServer(A_1)
    wait(0.3)
    local A_1 = 
    {
        [1] = value
    }
    local Event = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
    Event:FireServer(A_1)
    wait(0.3)
    local A_1 = 
    {
        [1] = "k"
    }
    local Event = nil
    Event:FireServer(A_1)
end);

main:addButton("Freeze Timer", function()
    repeat wait() until game:IsLoaded()
wait(.5)
game:GetService("RunService").Stepped:Connect(function()
                    if game.Players.LocalPlayer.Character:FindFirstChild("True") then
                        game.Players.LocalPlayer.Character:FindFirstChild("True"):Destroy()
                    end
end)
end)

main:addButton("Hide Level", function()
    game:service'RunService'.RenderStepped:connect(function()
        pcall(function()
        for i,v in next, game:service'Players'.LocalPlayer.Character:children() do
                if (string.find(tostring(v.Name):lower(), 'lvl.')) then 
                v:Destroy()
            end
        end
    end)
    end)
    end)

    main:addButton("Hide Wings", function()
    repeat wait()
    until game:IsLoaded()
    game.Players.LocalPlayer.PlayerGui:WaitForChild("HUD")

    local Live = game:WaitForChild("Workspace").Live
    local Char = Live:WaitForChild(game.Players.LocalPlayer.Name)

    while wait() do
        pcall(function()
            Char["RebirthWings"].Handle.AccessoryWeld:Destroy()
        end)
    end
    end)

    main:addButton("Hide Halo", function()
    local plr = game.Players.LocalPlayer
    game.Workspace.Live[plr.name].RealHalo["Handle"]:Destroy()
    end)

main:addButton("Click TP (V)", function()
plr = game.Players.LocalPlayer
hum = plr.Character.HumanoidRootPart
mouse = plr:GetMouse()
mouse.KeyDown:connect(function(key)
if key == "v" then
if mouse.Target then
hum.CFrame = CFrame.new(mouse.Hit.x, mouse.Hit.y + 5, mouse.Hit.z)
end
end
end)
end)

local main = page:addSection("Godmode")
main:addToggle("Earth Godmode", nil, function(Earth_Godmode)
	if Earth_Godmode == true then
		local God = game.Workspace.Touchy.Part
		local Root = game.Players.LocalPlayer.Character.HumanoidRootPart
		EGod = game:GetService("RunService").RenderStepped:Connect(function()
				firetouchinterest(Root, God, 0)
				firetouchinterest(Root, God, 1)
				if game.Players.LocalPlayer.PlayerGui:FindFirstChild("Popup") then
					game.Players.LocalPlayer.PlayerGui.Popup:Destroy()
				end
			end)
	else
		EGod:Disconnect()
		if game.Players.LocalPlayer.PlayerGui:FindFirstChild("Popup") then
			game.Players.LocalPlayer.PlayerGui.Popup:Destroy()
		end
	end
end)

main:addToggle("Hair Godmode", nil, function(HGM)
    if HGM == true then
local plr = game.Players.LocalPlayer
game.Workspace.Live[plr.name].Parent = game.Workspace.Effects
wait()
local args1 = game:GetService("Workspace").FriendlyNPCs["Hair Stylist"]
game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart:FireServer(args1)
wait(0.30)
local args = {
    [1] = {
        [1] = "Yes",
    },
}
game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance:FireServer(unpack(args))

game:GetService("RunService").RenderStepped:connect(function()
    game:GetService("Players").LocalPlayer.PlayerGui.Setup.Enabled = false
end)
else
    game.Players.LocalPlayer.Character.Humanoid.Health = 0
    end
end)

main:addToggle("Rainbown Godmode", nil, function(RGM)
    if RGM == true then
local plr = game.Players.LocalPlayer
game.Workspace.Live[plr.name].Parent = game.Workspace.Effects
wait()
local args1 = game:GetService("Workspace").FriendlyNPCs["Hair Stylist"]
game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart:FireServer(args1)
wait(0.30)
local args = {
    [1] = {
        [1] = "Yes",
    },
}
game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance:FireServer(unpack(args))

game:GetService("RunService").RenderStepped:connect(function()
    game:GetService("Players").LocalPlayer.PlayerGui.Setup.Enabled = false
    game:GetService("Players").LocalPlayer.Backpack.HairScript.RemoteEvent:FireServer(game:GetService("Players").LocalPlayer.PlayerGui.Setup.Frame.Side.HairColor,"up")
    game:GetService("Players").LocalPlayer.Backpack.HairScript.RemoteEvent:FireServer(game:GetService("Players").LocalPlayer.PlayerGui.Setup.Frame.Side.Skin,"up")
    game:GetService("Players").LocalPlayer.Backpack.HairScript.RemoteEvent:FireServer(game:GetService("Players").LocalPlayer.PlayerGui.Setup.Frame.Side.Hair,"up")
    end)
else
    game.Players.LocalPlayer.Character.Humanoid.Health = 0
    end
end)

main:addToggle("Ranked/HTC Godmode", nil, function(WGM)
    if WGM == true then
local plr = game.Players.LocalPlayer
game.Workspace.Live[plr.Name].Stats["Ki-Resist"]:Destroy()
game.Workspace.Live[plr.Name].Stats["Phys-Resist"]:Destroy()
else
    game.Players.LocalPlayer.Character.Humanoid.Health = 0
    end
end)
        
        local main = page:addSection("Hide")

       

        main:addButton("Hide Sensor", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.PowerLevel:Destroy() 
end)    
        
        main:addButton("Hide Senzu Aura", function()
        if not game:IsLoaded() then
game.Loaded:Wait()
end

game:GetService("RunService").RenderStepped:Connect(function()
for i,v in pairs(game.Players.LocalPlayer.Character.HumanoidRootPart:GetChildren()) do 
if v.Name:find("Critz") then
v:Destroy()
end end
end)
wait()
game:GetService("RunService").RenderStepped:Connect(function()
for i,v in pairs(game.Players.LocalPlayer.Character.HumanoidRootPart:GetChildren()) do 
if v.Name:find("Inf") then
v:Destroy()
end end
end)
wait()
game:GetService("RunService").RenderStepped:Connect(function()
for i,v in pairs(game.Players.LocalPlayer.Character.HumanoidRootPart:GetChildren()) do 
if v.Name:find("Eva") then
v:Destroy()
end end
end)
end)

main:addButton("Hide Form Aura", function()
      if game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("TempAura") or game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Lightning") then
    game.Players.LocalPlayer.Character.HumanoidRootPart.TempAura:Destroy()
    game.Players.LocalPlayer.Character.HumanoidRootPart.Lightning:Destroy()
    end
end)

local main = page:addSection("MoveSpam")

main:addButton("MeleeMoveSpam", function()
if not game:IsLoaded() then
game.Loaded:Wait()
end
wait(0.2)
local lplr = game.Players.LocalPlayer
local mouse = lplr:GetMouse()
_G.on = false
on = true
off = false

game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "yt製";
    })
    
game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "Move Spam";
    Text = "Press u to enable/disable.";
    })

mouse.KeyDown:connect(function(key)
    if key == "u" then
        if _G.on == false then
            _G.on = on
            game:GetService("StarterGui"):SetCore("SendNotification", {
                Title = "Spam Enabled";
                Text = "Press u to disable.";
                })
            while _G.on == true do
                wait()
                game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Flash Strike"])
game.Players.LocalPlayer.Character["Flash Strike"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Flash Skewer"])
game.Players.LocalPlayer.Character["Flash Skewer"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Sweep Kick"])
game.Players.LocalPlayer.Character["Sweep Kick"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Wolf Fang Fist"])
game.Players.LocalPlayer.Character["Wolf Fang Fist"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Neo Wolf Fang Fist"])
game.Players.LocalPlayer.Character["Neo Wolf Fang Fist"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Anger Rush"])
game.Players.LocalPlayer.Character["Anger Rush"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Meteor Crash"])
game.Players.LocalPlayer.Character["Meteor Crash"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["God Slicer"])
game.Players.LocalPlayer.Character["God Slicer"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["TS Molotov"])
game.Players.LocalPlayer.Character["TS Molotov"]:Activate()
wait()
            end
        elseif _G.on == true then
            _G.on = off
            game:GetService("StarterGui"):SetCore("SendNotification", {
                Title = "Spam Disabled";
                Text = "Press u to enable.";
                })
        end
    end
end)
while wait() do
for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
if v.Name == "Justice Combination" then
local action = game.Players.LocalPlayer.Character:WaitForChild("Action")
if action then wait() action:Destroy() end end
if v.Name == "Attacking" then
v:Destroy()
end
if v.Name == "Action" then
v:Destroy()
end
if v.Name == "Killed" then
v:Destroy()
end
if v.Name == "Block" and v.Value == true then
v.Value = false
end
end
end
end)

main:addButton("KiMoveSpam", function()
--[_iamyt#0001_]--
--[By: yt製]--
--[[Special Thanks to LazarTM for keybinding script.]]--
game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "yt製";
        })

wait(1)
local lplr = game.Players.LocalPlayer
local mouse = lplr:GetMouse()
_G.on = false
on = true
off = false

game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "Ki Move Spam";
    Text = "Press j to enable/disable.";
    })

mouse.KeyDown:connect(function(key)
    if key == "j" then
        if _G.on == false then
            _G.on = on
            game:GetService("StarterGui"):SetCore("SendNotification", {
                Title = "Spam Enabled";
                Text = "Press j to disable.";
                })
            while _G.on == true do
                wait()
                game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Demon Flash"])
game.Players.LocalPlayer.Character["Demon Flash"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Big Bang Kamehameha"])
game.Players.LocalPlayer.Character["Big Bang Kamehameha"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Burning Blast"])
game.Players.LocalPlayer.Character["Burning Blast"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Kick Barrage"])
game.Players.LocalPlayer.Character["Kick Barrage"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Wolf Fang Fist"])
game.Players.LocalPlayer.Character["Wolf Fang Fist"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Neo Wolf Fang Fist"])
game.Players.LocalPlayer.Character["Neo Wolf Fang Fist"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Anger Rush"])
game.Players.LocalPlayer.Character["Anger Rush"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Meteor Crash"])
game.Players.LocalPlayer.Character["Meteor Crash"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Blaster Meteor"])
game.Players.LocalPlayer.Character["Blaster Meteor"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["TS Molotov"])
game.Players.LocalPlayer.Character["TS Molotov"]:Activate()
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Mach Kick"])
game.Players.LocalPlayer.Character["Mach Kick"]:Activate()
            end
        elseif _G.on == true then
            _G.on = off
            game:GetService("StarterGui"):SetCore("SendNotification", {
                Title = "Spam Disabled";
                Text = "Press j to enable.";
                })
        end
    end
end)
while wait() do
for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
if v.Name == "Justice Combination" then
local action = game.Players.LocalPlayer.Character:WaitForChild("Action")
if action then wait() action:Destroy() end end
if v.Name == "Attacking" then
v:Destroy()
end
if v.Name == "Action" then
v:Destroy()
end
if v.Name == "Killed" then
v:Destroy()
end
if v.Name == "Block" and v.Value == true then
v.Value = false
end
end
end
end)





--Misc page
    local page = hub:addPage("Misc", 5012544693)
        local main = page:addSection("Misc")

 main:addSlider("Saturation", 25, -25, 0, function(Saturation)
    game.Lighting.ColorCorrection.Saturation = Saturation
end)
 
 main:addSlider("FOV", 90, 1, 120, function(FV)
    game.Workspace.Camera.FieldOfView = FV
end)

main:addButton("Lock On (N)", function()
local plrs = game:GetService("Players")
local presskeytoaim = true; local aimkey = "n"
local raycast = false

local espupdatetime = 5; autoesp = false



local lockaim = true; local lockangle = 5



--function findwat(folder, what)
--	for i, smth in pairs(folder:GetChildren()) do
--		if string.find(string.lower(tostring(smth)), string.lower(what)) then
--			return smth
--		end
--	end
--end
--
--local plrs = findwat(game, "Players")




local Gui = Instance.new("ScreenGui")
local Move = Instance.new("Frame")
local Main = Instance.new("Frame")
local st1 = Instance.new("TextLabel")
local st1_2 = Instance.new("TextLabel")
local st1_3 = Instance.new("TextLabel")
local Name = Instance.new("TextLabel")
--Properties:

-- Scripts:


local plrsforaim = {}

local lplr = game:GetService("Players").LocalPlayer
Move.Draggable = true
Gui.ResetOnSpawn = false
Gui.Name = "Chat"
Gui.DisplayOrder = 999

	Gui.Parent = plrs.LocalPlayer.PlayerGui


f = {}



local cam = game.Workspace.CurrentCamera

local mouse = lplr:GetMouse()
local switch = false
local key = "k"
local aimatpart = nil
mouse.KeyDown:Connect(function(a)
	if a == "t" then
		print("worked1")
		f.addesp()
	elseif a == "u" then
		if raycast == true then
			raycast = false
		else
			raycast = true
		end
	elseif a == "l" then
		if autoesp == false then
			autoesp = true
		else
			autoesp = false
		end
	end
	if a == "j" then
		if mouse.Target then
			mouse.Target:Destroy()
		end
	end
	if a == key then
		if switch == false then
			switch = true
		else
			switch = false
			if aimatpart ~= nil then
				aimatpart = nil
			end
		end
	elseif a == teambasedswitch then
		if TeamBased == true then
			TeamBased = false
			teambasedstatus.Text = tostring(TeamBased)
		else
			TeamBased = true
			teambasedstatus.Text = tostring(TeamBased)
		end
	elseif a == aimkey then
		if not aimatpart then
			local maxangle = math.rad(20)
			for i, plr in pairs(plrs:GetChildren()) do
				if plr.Name ~= lplr.Name and plr.Character and plr.Character.Head and plr.Character.Humanoid and plr.Character.Humanoid.Health > 1 then
					if TeamBased == true then
						if plr.Team.Name ~= lplr.Team.Name then
							local an = checkfov(plr.Character.Head)
							if an < maxangle then
								maxangle = an
								aimatpart = plr.Character.Head
							end
						end
					else
						local an = checkfov(plr.Character.Head)
							if an < maxangle then
								maxangle = an
								aimatpart = plr.Character.Head
							end
							print(plr)
					end
					plr.Character.Humanoid.Died:Connect(function()
						if aimatpart.Parent == plr.Character or aimatpart == nil then
							aimatpart = nil
						end
					end)
				end
			end
		else
			aimatpart = nil
		end
	end
end)

function getfovxyz (p0, p1, deg)
	local x1, y1, z1 = p0:ToOrientation()
	local cf = CFrame.new(p0.p, p1.p)
	local x2, y2, z2 = cf:ToOrientation()
	--local d = math.deg
	if deg then
		--return Vector3.new(d(x1-x2), d(y1-y2), d(z1-z2))
	else
		return Vector3.new((x1-x2), (y1-y2), (z1-z2))
	end
end

function getaimbotplrs()
	plrsforaim = {}
	for i, plr in pairs(plrs:GetChildren()) do
		if plr.Character and plr.Character.Humanoid and plr.Character.Humanoid.Health > 0 and plr.Name ~= lplr.Name and plr.Character.Head then
			
			if TeamBased == true then
				if plr.Team.Name ~= lplr.Team.Name then
					local cf = CFrame.new(game.Workspace.CurrentCamera.CFrame.p, plr.Character.Head.CFrame.p)
					local r = Ray.new(cf, cf.LookVector * 10000)
					local ign = {}
					for i, v in pairs(plrs.LocalPlayer.Character:GetChildren()) do
						if v:IsA("BasePart") then
							table.insert(ign , v)
						end
					end
					local obj = game.Workspace:FindPartOnRayWithIgnoreList(r, ign)
					if obj.Parent == plr.Character and obj.Parent ~= lplr.Character then
						table.insert(plrsforaim, obj)
					end
				end
			else
				local cf = CFrame.new(game.Workspace.CurrentCamera.CFrame.p, plr.Character.Head.CFrame.p)
				local r = Ray.new(cf, cf.LookVector * 10000)
				local ign = {}
				for i, v in pairs(plrs.LocalPlayer.Character:GetChildren()) do
					if v:IsA("BasePart") then
						table.insert(ign , v)
					end
				end
				local obj = game.Workspace:FindPartOnRayWithIgnoreList(r, ign)
				if obj.Parent == plr.Character and obj.Parent ~= lplr.Character then
					table.insert(plrsforaim, obj)
				end
			end
			
			
		end
	end
end

function aimat(part)
	cam.CFrame = CFrame.new(cam.CFrame.p, part.CFrame.p)
end
function checkfov (part)
	local fov = getfovxyz(game.Workspace.CurrentCamera.CFrame, part.CFrame)
	local angle = math.abs(fov.X) + math.abs(fov.Y)
	return angle
end

game:GetService("RunService").RenderStepped:Connect(function()
	if aimatpart then
		aimat(aimatpart)
		if aimatpart.Parent == plrs.LocalPlayer.Character then
			aimatpart = nil
		end
	end
	
	
--	if switch == true then
--		local maxangle = 99999
--		
--		--print("Loop")
--		if true and raycast == false then
--			for i, plr in pairs(plrs:GetChildren()) do
--				if plr.Name ~= lplr.Name and plr.Character and plr.Character.Head and plr.Character.Humanoid and plr.Character.Humanoid.Health > 1 then
--					if TeamBased then
--						if plr.Team.Name ~= lplr.Team.Name or plr.Team.TeamColor ~= lplr.Team.TeamColor then
--							local an = checkfov(plr.Character.Head)
--							if an < maxangle then
--								maxangle = an
--								aimatpart = plr.Character.Head
--								if an < lockangle then
--									break
--								end
--							end
--						end
--					else
--						local an = checkfov(plr.Character.Head)
--							if an < maxangle then
--								maxangle = an
--								aimatpart = plr.Character.Head
--								if an < lockangle then
--									break
--								end
--							end
--					end
--					
--					
--					
--					
--				end
--			end
--		elseif raycast == true then
--			
--		end
		
		if raycast == true and switch == false and not aimatpart then
			getaimbotplrs()
			aimatpart = nil
			local maxangle = 999
			for i, v in ipairs(plrsforaim) do
				if v.Parent ~= lplr.Character then
					local an = checkfov(v)
					if an < maxangle and v ~= lplr.Character.Head then
						maxangle = an
						aimatpart = v
						print(v:GetFullName())
						v.Parent.Humanoid.Died:connect(function()
							aimatpart = nil
						end)
					end
				end
			end
		
	end
end)
delay(0, function()
	while wait(espupdatetime) do
		if autoesp == true then
			pcall(function()
			f.addesp()
			end)
		end
	end
end)
warn("loaded")
end)

main:addToggle("ESP", nil, function(ESPT)
   if ESPT == true then
    backupesp1 = game:GetService("Players").LocalPlayer.NameDisplayDistance
backupesp2 = game:GetService("Players").LocalPlayer.HealthDisplayDistance
    local Holder = Instance.new("Folder", game.CoreGui)
Holder.Name = "ESP"

local UpdateFuncs = {}

local Box = Instance.new("BoxHandleAdornment")
Box.Name = "nilBox"
Box.Size = Vector3.new(4, 7, 4)
Box.Color3 = Color3.new(100 / 255, 100 / 255, 100 / 255)
Box.Transparency = 0.7
Box.ZIndex = 0
Box.AlwaysOnTop = true
Box.Visible = true

local NameTag = Instance.new("BillboardGui")
NameTag.Name = "nilNameTag"
NameTag.Enabled = false
NameTag.Size = UDim2.new(0, 200, 0, 50)
NameTag.AlwaysOnTop = true
NameTag.StudsOffset = Vector3.new(0, 1.8, 0)
local Tag = Instance.new("TextLabel", NameTag)
Tag.Name = "Tag"
Tag.BackgroundTransparency = 1
Tag.Position = UDim2.new(0, -50, 0, 0)
Tag.Size = UDim2.new(0, 300, 0, 20)
Tag.TextSize = 20
Tag.TextColor3 = Color3.new(100 / 255, 100 / 255, 100 / 255)
Tag.TextStrokeColor3 = Color3.new(0 / 255, 0 / 255, 0 / 255)
Tag.TextStrokeTransparency = 0.4
Tag.Text = "nil"
Tag.Font = Enum.Font.SourceSansBold
Tag.TextScaled = false

local LoadCharacter = function(v)
	repeat wait() until v.Character ~= nil
	v.Character:WaitForChild("Humanoid")
	local vHolder = Holder:FindFirstChild(v.Name)
	vHolder:ClearAllChildren()
	local b = Box:Clone()
	b.Name = v.Name .. "Box"
	b.Adornee = v.Character
	b.Parent = vHolder
	local t = NameTag:Clone()
	t.Name = v.Name .. "NameTag"
	t.Enabled = true
	t.Parent = vHolder
	t.Adornee = v.Character:WaitForChild("Head", 5)
	if not t.Adornee then
		return UnloadCharacter(v)
	end
	t.Tag.Text = v.Name
	b.Color3 = Color3.new(v.TeamColor.r, v.TeamColor.g, v.TeamColor.b)
	t.Tag.TextColor3 = Color3.new(v.TeamColor.r, v.TeamColor.g, v.TeamColor.b)
	local UpdateNameTag = function()
		if not pcall(function()
			--v.Character.Humanoid.DisplayDistanceType = Enum.HumanoidDisplayDistanceType.None
			local maxh = math.floor(v.Character.Humanoid.MaxHealth)
			local h = math.floor(v.Character.Humanoid.Health)
			t.Tag.Text = v.Name .. "\n" .. ((maxh ~= 0 and tostring(math.floor((h / maxh) * 100))) or "0") .. "%  " .. tostring(h) .. "/" .. tostring(maxh)
		end) then
			UpdateFuncs[v] = nil
		end
	end
	UpdateNameTag()
	UpdateFuncs[v] = UpdateNameTag
end

local UnloadCharacter = function(v)
	local vHolder = Holder:FindFirstChild(v.Name)
	if vHolder and (vHolder:FindFirstChild(v.Name .. "Box") ~= nil or vHolder:FindFirstChild(v.Name .. "NameTag") ~= nil) then
		vHolder:ClearAllChildren()
	end
end

local LoadPlayer = function(v)
	local vHolder = Instance.new("Folder", Holder)
	vHolder.Name = v.Name
	v.CharacterAdded:Connect(function()
		pcall(LoadCharacter, v)
	end)
	v.CharacterRemoving:Connect(function()
		pcall(UnloadCharacter, v)
	end)
	LoadCharacter(v)
end

local UnloadPlayer = function(v)
	UnloadCharacter(v)
	local vHolder = Holder:FindFirstChild(v.Name)
	if vHolder then
		vHolder:Destroy()
	end
end

for i,v in pairs(game:GetService("Players"):GetPlayers()) do
	spawn(function() pcall(LoadPlayer, v) end)
end

game:GetService("Players").PlayerAdded:Connect(function(v)
	pcall(LoadPlayer, v)
end)

game:GetService("Players").PlayerRemoving:Connect(function(v)
	pcall(UnloadPlayer, v)
end)

game.ItemChanged:Connect(function(i, v)
	if i:IsA("Player") and v == "TeamColor" then
		if Holder:FindFirstChild(i.Name) then
			UnloadCharacter(i)
			wait()
			LoadCharacter(i)
		end
	elseif i:IsA("Humanoid") and i.Parent then
		local p = game:GetService("Players"):GetPlayerFromCharacter(i.Parent)
		if p and Holder:FindFirstChild(p.Name) then
			UpdateFuncs[p]()
		end
	end
end)
game:GetService("Players").LocalPlayer.NameDisplayDistance = 0
game:GetService("Players").LocalPlayer.HealthDisplayDistance = 0
else
    game:GetService("CoreGui").ESP:Destroy()
game:GetService("Players").LocalPlayer.NameDisplayDistance = backupesp1
game:GetService("Players").LocalPlayer.HealthDisplayDistance = backupesp2
    end
    end)

    main:addToggle("Show Hitbox", nil, function(Hitbox)
        if Hitbox == true then
            settings():GetService("RenderSettings").ShowBoundingBoxes = true
        else
            settings():GetService("RenderSettings").ShowBoundingBoxes = false
        end
    end)



        local main = page:addSection("Glitch")
        
       main:addButton("KnockBack", function()
       if not game:IsLoaded() then
game.Loaded:Wait()
end

local plr = game.Players.LocalPlayer

while wait() do
    pcall(function()
        game:GetService("Workspace").Live[plr.Name].Head.KnockBacked:Destroy()
    end)
end
end)

main:addButton("BoneCrush", function()
if not game:IsLoaded() then
game.Loaded:Wait()
end

local plr = game.Players.LocalPlayer

while wait() do
    pcall(function()
        game:GetService("Workspace").Live[plr.Name].Head.KnockBacked:Destroy()
    end)
end
end)













        local main = page:addSection("Free")
        
        main:addButton("DarkChat", function()
        if not game:IsLoaded() then
    game.Loaded:wait();
end;
wait(3)

    pcall(function()
lplr=game.Players.LocalPlayer;
char=lplr.Character;

part=Instance.new("Folder",char);
function DarkThemeFunction(lol)
   part.Name = lol
end;

DarkThemeFunction('DarkTheme');
end)
end)

main:addButton("Nimbus", function()
lplr=game.Players.LocalPlayer;
char=lplr.Character;
part=Instance.new("Part",char);
function NimbusFunction(lol)
   part.Name = lol
end;
NimbusFunction('Nimbus');
end)

main:addButton("Beerus", function()
if not game:IsLoaded() then
game.Loaded:Wait()
end wait()

player = game.Players.LocalPlayer while wait() do
if game.Workspace.Live[player.Name].Animate.idle:FindFirstChild("Animation1") then
game.Workspace.Live[player.Name].Animate.idle:FindFirstChild("Animation1").AnimationId = "rbxassetid://1171558651"
if game.Workspace.Live[player.Name].Animate.walk:FindFirstChild("RunAnim") then
game.Workspace.Live[player.Name].Animate.walk:FindFirstChild("RunAnim").AnimationId = "rbxassetid://1171558651"
end end end
end)


    


        


        



--Auto Page
      
      
      
      local page = hub:addPage("Auto", 5012544693)
        local main = page:addSection("Earth")
        
        main:addButton("AutoEarth", function()
        game.workspace.FriendlyNPCs["Quest Giver"]:Destroy()
game.workspace.FriendlyNPCs["Quest Giver"]:Destroy()
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["Bulma"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "Yes"
	}
)
wait(0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(0.7)
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["Spaceship"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "No"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(0.7)

local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["Trunks [Future]"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "Yes"
	}
)
wait(0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(0.7)
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["TimeMachine"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "No"
	}
)
wait(0.7)
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["Quest Giver"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "Yes"
	}
)
wait(0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(0.7)
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["NamekianShip"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "No"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(0.7)
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["Elder Kai"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "Yes"
	}
)
wait(0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(2.5)
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["Korin"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "SIP"
	}
)
wait(0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
end)
        
        

       local page = hub:addPage("Stats",5012544693)
	   local main = page:addSection("Auto Stats")

	   main:addToggle("Health Max", nil, function(bool)
        if bool == true then
            _G.stat1 = true
            repeat wait()
                local A_1 = game:GetService("Players").LocalPlayer.PlayerGui.HUD.Bottom.Stats["Health-Max"]
                local Event = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.AttemptUpgrade
                Event:FireServer(A_1)
            until _G.stat1 == false
        else
            _G.stat1 = false
        end
    end)

    main:addToggle("Ki Max", nil, function(bool)
        if bool == true then
            _G.stat2 = true
            repeat wait()
                local A_1 = game:GetService("Players").LocalPlayer.PlayerGui.HUD.Bottom.Stats["Ki-Max"]
                local Event = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.AttemptUpgrade
                Event:FireServer(A_1)
            until _G.stat2 == false
        else
            _G.stat2 = false
        end
    end)

    main:addToggle("Melee Damage", nil, function(bool)
        if bool == true then
            _G.stat3 = true
            repeat wait()
                local A_1 = game:GetService("Players").LocalPlayer.PlayerGui.HUD.Bottom.Stats["Phys-Damage"]
                local Event = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.AttemptUpgrade
                Event:FireServer(A_1)
            until _G.stat3 == false
        else
            _G.stat3 = false
        end
    end)

    main:addToggle("Ki Damage", nil, function(bool)
        if bool == true then
            _G.stat4 = true
            repeat wait()
                local A_1 = game:GetService("Players").LocalPlayer.PlayerGui.HUD.Bottom.Stats["Ki-Damage"]
                local Event = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.AttemptUpgrade
                Event:FireServer(A_1)
            until _G.stat4 == false
        else
            _G.stat4 = false
        end
    end)

    main:addToggle("Melee Resistance", nil, function(bool)
        if bool == true then
            _G.stat5 = true
            repeat wait()
                local A_1 = game:GetService("Players").LocalPlayer.PlayerGui.HUD.Bottom.Stats["Phys-Resist"]
                local Event = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.AttemptUpgrade
                Event:FireServer(A_1)
            until _G.stat5 == false
        else
            _G.stat5 = false
        end
    end)

    main:addToggle("Ki Resistance", nil, function(bool)
        if bool == true then
            _G.stat6 = true
            repeat wait()
                local A_1 = game:GetService("Players").LocalPlayer.PlayerGui.HUD.Bottom.Stats["Ki-Resist"]
                local Event = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.AttemptUpgrade
                Event:FireServer(A_1)
            until _G.stat6 == false
        else
            _G.stat6 = false
        end
    end)

    main:addToggle("Speed", nil, function(bool)
        if bool == true then
            _G.stat7 = true
            repeat wait()
                local A_1 = game:GetService("Players").LocalPlayer.PlayerGui.HUD.Bottom.Stats.Speed
                local Event = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.AttemptUpgrade
                Event:FireServer(A_1)
            until _G.stat7 == false
        else
            _G.stat7 = false
        end
    end)


-- teleport page
local page = hub:addPage("Teleport", 5012544693)
local main = page:addSection("City TP")

main:addButton("South", function()
    local tweenservice = game:GetService("TweenService")
local player = game:GetService("Players").LocalPlayer
local char = player.Character
local tweeninfo = TweenInfo.new(1, Enum.EasingStyle.Quad)
local cframe = {CFrame = CFrame.new(-456, 28, -6413)}
tweenservice:Create(char.HumanoidRootPart, tweeninfo, cframe):Play()
end)

main:addButton("West", function()
    local tweenservice = game:GetService("TweenService")
local player = game:GetService("Players").LocalPlayer
local char = player.Character
local tweeninfo = TweenInfo.new(1, Enum.EasingStyle.Quad)
local cframe = {CFrame = CFrame.new(-571, 23, -2884)}
tweenservice:Create(char.HumanoidRootPart, tweeninfo, cframe):Play()
end)
    
main:addButton("Central", function()
    local tweenservice = game:GetService("TweenService")
local player = game:GetService("Players").LocalPlayer
local char = player.Character
local tweeninfo = TweenInfo.new(1, Enum.EasingStyle.Quad)
local cframe = {CFrame = CFrame.new(-3835, 23, -1428)}
tweenservice:Create(char.HumanoidRootPart, tweeninfo, cframe):Play()
end)
    
main:addButton("Satan", function()
    local tweenservice = game:GetService("TweenService")
local player = game:GetService("Players").LocalPlayer
local char = player.Character
local tweeninfo = TweenInfo.new(1, Enum.EasingStyle.Quad)
local cframe = {CFrame = CFrame.new(-5964, 141, -3012)}
tweenservice:Create(char.HumanoidRootPart, tweeninfo, cframe):Play()
end)

main:addButton("East", function()
local tweenservice = game:GetService("TweenService")
local player = game:GetService("Players").LocalPlayer
local char = player.Character
local tweeninfo = TweenInfo.new(1, Enum.EasingStyle.Quad)
local cframe = {CFrame = CFrame.new(-6231, 22, -905)}
tweenservice:Create(char.HumanoidRootPart, tweeninfo, cframe):Play()
end)

main:addButton("Tower", function()
local tweenservice = game:GetService("TweenService")
local player = game:GetService("Players").LocalPlayer
local char = player.Character
local tweeninfo = TweenInfo.new(1, Enum.EasingStyle.Quad)
local cframe = {CFrame = CFrame.new(2047, 1495, -2282)}
tweenservice:Create(char.HumanoidRootPart, tweeninfo, cframe):Play()
end)

main:addButton("Lookout", function()
local tweenservice = game:GetService("TweenService")
local player = game:GetService("Players").LocalPlayer
local char = player.Character
local tweeninfo = TweenInfo.new(1, Enum.EasingStyle.Quad)
local cframe = {CFrame = CFrame.new(2412, 3945, -2275)}
tweenservice:Create(char.HumanoidRootPart, tweeninfo, cframe):Play()
end)



local main = page:addSection("Servers")
main:addButton("Rejoin", function()
game:GetService("TeleportService"):Teleport(game.PlaceId, game.Players.LocalPlayer)
end)
main:addButton("Server Hopper", function()
  local x = {}
    for _, v in ipairs(game:GetService("HttpService"):JSONDecode(game:HttpGetAsync("https://games.roblox.com/v1/games/" .. game.PlaceId .. "/servers/Public?sortOrder=Asc&limit=100")).data) do
        if type(v) == "table" and v.maxPlayers > v.playing and v.id ~= game.JobId then
            x[#x + 1] = v.id
        end
    end
    if #x > 0 then
        game:GetService("TeleportService"):TeleportToPlaceInstance(game.PlaceId, x[math.random(1, #x)])
    end
end)
main:addButton("Empty Server", function()
getgenv().AutoTeleport = true
getgenv().DontTeleportTheSameNumber = true --If you set this true it won't teleport to the server if it has the same number of players as your current server
getgenv().CopytoClipboard = true
loadstring(game:HttpGet("https://raw.githubusercontent.com/rapnz/scripts/master/AmnesiaEmptyServerFinder.lua"))()
end)

local main = page:addSection("ShopTP")
main:addButton("Red Shop", function()
local tweenservice = game:GetService("TweenService")
local player = game:GetService("Players").LocalPlayer
local char = player.Character
local tweeninfo = TweenInfo.new(1, Enum.EasingStyle.Quad)
local cframe = {CFrame = CFrame.new(-2793, 22, -1650)}
tweenservice:Create(char.HumanoidRootPart, tweeninfo, cframe):Play()
end)

main:addButton("Green Shop", function()
local tweenservice = game:GetService("TweenService")
local player = game:GetService("Players").LocalPlayer
local char = player.Character
local tweeninfo = TweenInfo.new(1, Enum.EasingStyle.Quad)
local cframe = {CFrame = CFrame.new(-577, 22, -2654)}
tweenservice:Create(char.HumanoidRootPart, tweeninfo, cframe):Play()
end)

main:addButton("Blue Shop", function()
local tweenservice = game:GetService("TweenService")
local player = game:GetService("Players").LocalPlayer
local char = player.Character
local tweeninfo = TweenInfo.new(1, Enum.EasingStyle.Quad)
local cframe = {CFrame = CFrame.new(-249, 25, -6418)}
tweenservice:Create(char.HumanoidRootPart, tweeninfo, cframe):Play()
end)

main:addButton("Jiren Shop", function()
local tweenservice = game:GetService("TweenService")
local player = game:GetService("Players").LocalPlayer
local char = player.Character
local tweeninfo = TweenInfo.new(1, Enum.EasingStyle.Quad)
local cframe = {CFrame = CFrame.new(776, 134, 625)}
tweenservice:Create(char.HumanoidRootPart, tweeninfo, cframe):Play()
end)

main:addButton("Zaros Shop", function()
local tweenservice = game:GetService("TweenService")
local player = game:GetService("Players").LocalPlayer
local char = player.Character
local tweeninfo = TweenInfo.new(1, Enum.EasingStyle.Quad)
local cframe = {CFrame = CFrame.new(623, 107, 3962)}
tweenservice:Create(char.HumanoidRootPart, tweeninfo, cframe):Play()
end)



local main = page:addSection("World TP")
main:addButton("Earth", function()
    game:GetService("TeleportService"):Teleport(536102540 , game.Players.LocalPlayer)
    end)
main:addButton("Namek", function()
    game:GetService("TeleportService"):Teleport(882399924 , game.Players.LocalPlayer)
    end)
main:addButton("Space", function()
    game:GetService("TeleportService"):Teleport(478132461 , game.Players.LocalPlayer)
    end)
main:addButton("Future", function()
    game:GetService("TeleportService"):Teleport(569994010 , game.Players.LocalPlayer)
    end)
main:addButton("Secret", function()
    game:GetService("TeleportService"):Teleport(2046990924 , game.Players.LocalPlayer)
    end)
main:addButton("Queue", function()
    game:GetService("TeleportService"):Teleport(3565304751 , game.Players.LocalPlayer)
    end)
main:addButton("Zaros", function()
    game:GetService("TeleportService"):Teleport(2651456105 , game.Players.LocalPlayer)
    end)
main:addButton("Heaven", function()
    game:GetService("TeleportService"):Teleport(3552157537 , game.Players.LocalPlayer)
    end)
main:addButton("Ranked Earth", function()
    game:GetService("TeleportService"):Teleport(489979581 , game.Players.LocalPlayer)
    end)
main:addButton("Ranked Heaven", function()
    game:GetService("TeleportService"):Teleport(3618359401 , game.Players.LocalPlayer)
    end)
main:addButton("Hyperbolic Time Chamber", function()
    game:GetService("TeleportService"):Teleport(882375367 , game.Players.LocalPlayer)
    end)





 -- last page
        local theme = hub:addPage("Settings", 5012544693)
        local colors = theme:addSection("Colors")
        local settings = theme:addSection("Settings")

        for theme, color in pairs(themes) do -- all in one theme changer, i know, im cool
        colors:addColorPicker(theme, color, function(color3)
        hub:setTheme(theme, color3)
        end)
        end

        settings:addKeybind("Toxic Clap", Enum.KeyCode.RightShift, function()
    local randommessagenumber = math.random(1,4)
        if randommessagenumber == 1 then
local args = {
    [1] = "Ur Trash Kid",
    [2] = "All"
}
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
end
        if randommessagenumber == 2 then
local args = {
    [1] = "LOL Noob",
    [2] = "All"
}
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
end
        if randommessagenumber == 3 then
local args = {
    [1] = "I had Lag and still won Noob",
    [2] = "All"
}
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
end
        if randommessagenumber == 4 then
local args = {
    [1] = "Go Back to Fortnite You Skid",
    [2] = "All"
}
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
end
end)
        
        settings:addKeybind("Show/Hide Gui", Enum.KeyCode.RightAlt, function()
            hub:toggle()
            end, function()
        end)

        settings:addKeybind("Hard Reset", Enum.KeyCode.Delete, function()
game.Players.LocalPlayer.Character.UpperTorso:Destroy()
end)





        -- load
        hub:SelectPage(hub.pages[1], true)
