local NotificationLoad = loadstring(game:HttpGet(('https://raw.githubusercontent.com/treeofplant/Notif/main/library.lua'),true))()

local MAINTENCE = Instance.new("ScreenGui")
local Draggable = Instance.new("Frame")
local Mainframe = Instance.new("Frame")
local DropShadowHolder = Instance.new("Frame")
local DropShadow = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local TOPTITLE = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local Ignore = Instance.new("Frame")
local Lightuxname = Instance.new("TextLabel")
local GameName = Instance.new("TextLabel")
local Page1 = Instance.new("Frame")
local MAINTENCE_2 = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local CopyCord = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local Minimize = Instance.new("ImageButton")

--Properties:

MAINTENCE.Name = "MAINTENCE"
MAINTENCE.Parent = game.CoreGui
MAINTENCE.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Draggable.Name = "Draggable"
Draggable.Parent = MAINTENCE
Draggable.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Draggable.BorderColor3 = Color3.fromRGB(0, 0, 0)
Draggable.BorderSizePixel = 0
Draggable.Position = UDim2.new(0.372212827, 0, 0.348635226, 0)
Draggable.Size = UDim2.new(0, 330, 0, 50)

Mainframe.Name = "Mainframe"
Mainframe.Parent = Draggable
Mainframe.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
Mainframe.BorderColor3 = Color3.fromRGB(0, 0, 0)
Mainframe.BorderSizePixel = 0
Mainframe.Position = UDim2.new(-0.00966519397, 0, -0.00736206071, 0)
Mainframe.Size = UDim2.new(0, 336, 0, 160)

DropShadowHolder.Name = "DropShadowHolder"
DropShadowHolder.Parent = Mainframe
DropShadowHolder.BackgroundTransparency = 1.000
DropShadowHolder.BorderSizePixel = 0
DropShadowHolder.Position = UDim2.new(-0.00970873795, 0, -0.00819672085, 0)
DropShadowHolder.Size = UDim2.new(1.0226537, 0, 1.01639342, 0)
DropShadowHolder.ZIndex = 0

DropShadow.Name = "DropShadow"
DropShadow.Parent = DropShadowHolder
DropShadow.AnchorPoint = Vector2.new(0.5, 0.5)
DropShadow.BackgroundTransparency = 1.000
DropShadow.BorderSizePixel = 0
DropShadow.Position = UDim2.new(0.5, 0, 0.5, 0)
DropShadow.Size = UDim2.new(1, 47, 1, 47)
DropShadow.ZIndex = 0
DropShadow.Image = "rbxassetid://6014261993"
DropShadow.ImageColor3 = Color3.fromRGB(0, 0, 0)
DropShadow.ImageTransparency = 0.500
DropShadow.ScaleType = Enum.ScaleType.Slice
DropShadow.SliceCenter = Rect.new(49, 49, 450, 450)

UICorner.CornerRadius = UDim.new(0, 4)
UICorner.Parent = Mainframe

TOPTITLE.Name = "TOPTITLE"
TOPTITLE.Parent = Mainframe
TOPTITLE.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
TOPTITLE.BorderColor3 = Color3.fromRGB(0, 0, 0)
TOPTITLE.BorderSizePixel = 0
TOPTITLE.Size = UDim2.new(0, 336, 0, 28)

UICorner_2.CornerRadius = UDim.new(0, 4)
UICorner_2.Parent = TOPTITLE

Ignore.Name = "Ignore"
Ignore.Parent = TOPTITLE
Ignore.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
Ignore.BorderColor3 = Color3.fromRGB(0, 0, 0)
Ignore.BorderSizePixel = 0
Ignore.Position = UDim2.new(0, 0, 0.837837815, 0)
Ignore.Size = UDim2.new(0, 309, 0, 6)

Lightuxname.Name = "Lightuxname"
Lightuxname.Parent = TOPTITLE
Lightuxname.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Lightuxname.BackgroundTransparency = 1.000
Lightuxname.BorderColor3 = Color3.fromRGB(0, 0, 0)
Lightuxname.BorderSizePixel = 0
Lightuxname.Position = UDim2.new(0.0385098271, 0, 0.013147627, 0)
Lightuxname.Size = UDim2.new(0, 55, 0, 29)
Lightuxname.Font = Enum.Font.SourceSansBold
Lightuxname.Text = "Lightux │"
Lightuxname.TextColor3 = Color3.fromRGB(255, 255, 255)
Lightuxname.TextSize = 14.000
Lightuxname.TextXAlignment = Enum.TextXAlignment.Left

GameName.Name = "GameName"
GameName.Parent = TOPTITLE
GameName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GameName.BackgroundTransparency = 1.000
GameName.BorderColor3 = Color3.fromRGB(0, 0, 0)
GameName.BorderSizePixel = 0
GameName.Position = UDim2.new(0.216999993, 0, 0.0130000003, 0)
GameName.Size = UDim2.new(0, 175, 0, 29)
GameName.Font = Enum.Font.SourceSansBold
GameName.Text = "MAINTENCE"
GameName.TextColor3 = Color3.fromRGB(47, 148, 255)
GameName.TextSize = 13.000
GameName.TextXAlignment = Enum.TextXAlignment.Left

Page1.Name = "Page1"
Page1.Parent = Mainframe
Page1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Page1.BackgroundTransparency = 1.000
Page1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Page1.BorderSizePixel = 0
Page1.Position = UDim2.new(0, 0, 0.172130883, 0)
Page1.Size = UDim2.new(0, 336, 0, 305)

MAINTENCE_2.Name = "MAINTENCE"
MAINTENCE_2.Parent = Page1
MAINTENCE_2.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
MAINTENCE_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
MAINTENCE_2.BorderSizePixel = 0
MAINTENCE_2.Position = UDim2.new(0.0325575322, 0, 0.0426229499, 0)
MAINTENCE_2.Size = UDim2.new(0, 313, 0, 108)

UICorner_3.CornerRadius = UDim.new(0, 4)
UICorner_3.Parent = MAINTENCE_2

TextLabel.Parent = MAINTENCE_2
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0127797481, 0, 0.0405405387, 0)
TextLabel.Size = UDim2.new(0, 303, 0, 69)
TextLabel.Font = Enum.Font.SourceSansSemibold
TextLabel.Text = "This script is currently bugged and we are working on a revamp to fix every game script there will be a new loadstring so please join the discord to stay notified when each script is released with a new loadstring"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 15.000
TextLabel.TextWrapped = true
TextLabel.TextYAlignment = Enum.TextYAlignment.Top

CopyCord.Name = "CopyCord"
CopyCord.Parent = MAINTENCE_2
CopyCord.BackgroundColor3 = Color3.fromRGB(75, 151, 226)
CopyCord.BorderColor3 = Color3.fromRGB(0, 0, 0)
CopyCord.BorderSizePixel = 0
CopyCord.Position = UDim2.new(0.326907426, 0, 0.679286242, 0)
CopyCord.Size = UDim2.new(0, 105, 0, 28)
CopyCord.Font = Enum.Font.SourceSansSemibold
CopyCord.Text = "Copy Discord"
CopyCord.TextColor3 = Color3.fromRGB(255, 255, 255)
CopyCord.TextSize = 15.000

UICorner_4.Parent = CopyCord

Minimize.Name = "Minimize"
Minimize.Parent = Draggable
Minimize.Active = false
Minimize.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Minimize.BackgroundTransparency = 1.000
Minimize.Position = UDim2.new(0.936248362, 0, 0.0929724127, 0)
Minimize.Selectable = false
Minimize.Size = UDim2.new(0, 19, 0, 19)
Minimize.Image = "http://www.roblox.com/asset/?id=16499830557"

-- Scripts:

local function MIDSBI_fake_script() -- CopyCord.LocalScript 
	local script = Instance.new('LocalScript', CopyCord)

	script.Parent.MouseButton1Down:connect(function()
	
		setclipboard('https://discord.gg/sdCSmXRjuX')
		
		NotificationLoad:NewNotification({ 
			["Mode"] = "Success", -- Choose one (Success/Info/Error)
			["Title"] = "Copied", -- Title of notification
			["Description"] = "Paste the invite in your discord app servers", -- Description of notification
			["Timeout"] = 5, -- How long the notification will last
			["Audio"] = true -- Plays audio if enabled on each notification
	
		})
	end)
end
coroutine.wrap(MIDSBI_fake_script)()
local function RISGNEK_fake_script() -- Minimize.LocalScript 
	local script = Instance.new('LocalScript', Minimize)

	script.Parent.MouseButton1Down:connect(function()
	
		MAINTENCE:Destroy()
	
		MAINTENCE:deleteTimeout(2)
	
	end)
end
coroutine.wrap(RISGNEK_fake_script)()
local function IWEWS_fake_script() -- Draggable.drag 
	local script = Instance.new('LocalScript', Draggable)

	local UserInputService = game:GetService("UserInputService")
	local runService = (game:GetService("RunService"));
	
	local gui = script.Parent
	
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	function Lerp(a, b, m)
		return a + (b - a) * m
	end;
	
	local lastMousePos
	local lastGoalPos
	local DRAG_SPEED = (8); -- // The speed of the UI darg.
	function Update(dt)
		if not (startPos) then return end;
		if not (dragging) and (lastGoalPos) then
			gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, lastGoalPos.X.Offset, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, lastGoalPos.Y.Offset, dt * DRAG_SPEED))
			return 
		end;
	
		local delta = (lastMousePos - UserInputService:GetMouseLocation())
		local xGoal = (startPos.X.Offset - delta.X);
		local yGoal = (startPos.Y.Offset - delta.Y);
		lastGoalPos = UDim2.new(startPos.X.Scale, xGoal, startPos.Y.Scale, yGoal)
		gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, xGoal, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, yGoal, dt * DRAG_SPEED))
	end;
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
			lastMousePos = UserInputService:GetMouseLocation()
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	runService.Heartbeat:Connect(Update)
end
coroutine.wrap(IWEWS_fake_script)()
